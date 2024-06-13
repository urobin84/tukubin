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
  <div class="absolute left-[-230px] top-[76px] h-full  flex justify-center">
    <NavigationMenuViewport v-bind="forwardedProps" :class="
        cn(
          'MegaMenuContainer',
          props.class,
        )
      " />
  </div>
</template>
