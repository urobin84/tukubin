<script setup lang="ts">
import { type HTMLAttributes, computed } from 'vue'
import {
  NavigationMenuViewport,
  type NavigationMenuViewportProps,
  useForwardProps,
} from 'radix-vue'
import { cn } from '@/lib/utils'

const props = defineProps<NavigationMenuViewportProps & { class?: HTMLAttributes['class'] }>()

const delegatedProps = computed(() => {
  const { class: _, ...delegated } = props

  return delegated
})

const forwardedProps = useForwardProps(delegatedProps)
</script>

<template>
  <div class="absolute left-[-210px] top-full bg-slate-300 h-full flex justify-center">
    <NavigationMenuViewport v-bind="forwardedProps" :class="
        cn(
          'relative mt-[39px] h-[493px] w-full overflow-hidden rounded-b-md border border-[#F0F3F7] bg-popover text-popover-foreground data-[state=open]:animate-in data-[state=closed]:animate-out data-[state=closed]:zoom-out-95 data-[state=open]:zoom-in-90 md:w-[--radix-navigation-menu-viewport-width]',
          props.class,
        )
      " />
  </div>
</template>
