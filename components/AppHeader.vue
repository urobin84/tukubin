<template>
  <div
    class="flex flex-col min-w-[1024px] items-center bg-[#FFFFFF] z-[999] fixed top-0 right-0 left-0 border-b border-b-[#F0F3F7] h-[121px]">
    <div class="hidden sm:flex w-full  h-[32px] z-[3] bg-[#F0F3F7] px-8 fixed justify-between left-0 right-0">
      <div class="flex justify-center items-center min-w-[168px] mr-4 gap-[2px]">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" class="mt-0" height="170" fill="none">
          <path fill-rule="evenodd" clip-rule="evenodd"
            d="M8 74.25h8A2.75 2.75 0 0 1 18.75 77v14A2.75 2.75 0 0 1 16 93.75H8A2.75 2.75 0 0 1 5.25 91V77A2.75 2.75 0 0 1 8 74.25Zm8.884 17.634A1.25 1.25 0 0 0 17.25 91V77A1.25 1.25 0 0 0 16 75.75h-1A1.49 1.49 0 0 1 13.5 77h-3A1.49 1.49 0 0 1 9 75.75H8A1.25 1.25 0 0 0 6.75 77v14A1.25 1.25 0 0 0 8 92.25h8c.331 0 .65-.132.884-.366ZM11 89.25h2a.75.75 0 1 1 0 1.5h-2a.75.75 0 1 1 0-1.5Z"
            fill="#8D96AA" />
        </svg>

        <Label class="text-[#6D7588] text-xs leading-8 flex flex-wrap items-center ">Download TukuBin
          App</Label>
      </div>
      <div class="flex flex-row gap-4 justify-between items-center">
        <div class="text-[#6D7588] text-xs leading-8 flex-nowrap">Tentang TukuBin</div>
        <div class="text-[#6D7588] text-xs leading-8 flex-nowrap">Mitra TukuBin</div>
        <div class="text-[#6D7588] text-xs leading-8 flex-nowrap">Pusat Edukasi Seller</div>
        <div class="text-[#6D7588] text-xs leading-8 flex-nowrap">Promo</div>
        <div class="text-[#6D7588] text-xs leading-8 flex-nowrap">TukuBin Care</div>
      </div>
    </div>
    <div class="h-[64px] w-[96%] sm:left-[32px] pl-4 sm:top-[30px] top-0 fixed flex items-center">
      <div class="text-4xl text-green-600 w-[150px] hidden sm:flex items-center my-1 flex-shrink-0">TukuBin</div>
      <div class="h-full hidden sm:flex items-center cursor-pointer mt-[1px] mr-[8px] ml-[24px]">
        <div class="w-full rounded relative flex items-center p-2 h-[121px]">
          <NavigationMenu>
            <NavigationMenuList>
              <NavigationMenuItem>
                <NavigationMenuTrigger
                  class="text-[#212121] text-sm leading-[18px] text-ellipsis h-[40px] w-[74px] flex items-center justify-center">
                  Kategori</NavigationMenuTrigger>
                <NavigationMenuContent>
                  <div>
                    <div class="AllCategoryTab">
                      <div class="BtnHeaderCategoty">Belanja</div>
                      <div class="BtnHeaderCategoty">Featured</div>
                      <div class="BtnHeaderCategoty">Kebutuhan Harian</div>
                      <div class="BtnHeaderCategoty">Tagihan</div>
                      <div class="BtnHeaderCategoty">Top-Up</div>
                      <div class="BtnHeaderCategoty">TukuBin Keuangan</div>
                      <div class="BtnHeaderCategoty">Pajak & Pendidikan</div>
                      <div class="BtnHeaderCategoty">Travel & Entertainment</div>
                      <div class="BtnHeaderCategoty">Halal Corner</div>
                      <div class="BtnHeaderCategoty">Lain - lain</div>
                    </div>
                    <div class="CategoryContainer">
                      <div class="AllCategories">
                        <a href="#" class="ItemListCategories">Rumah Tangga</a>
                        <a href="#" class="ItemListCategories">Audio, Kamera & Elektronik Lainnya</a>
                        <a href="#" class="ItemListCategories">Buku</a>
                        <a href="#" class="ItemListCategories">Dapur</a>
                        <a href="#" class="ItemListCategories">Elektronik</a>
                        <a href="#" class="ItemListCategories">Fashion Anak & Bayi</a>
                        <a href="#" class="ItemListCategories">Fashion Muslim</a>
                        <a href="#" class="ItemListCategories">Fashion Pria</a>
                        <a href="#" class="ItemListCategories">Fashion Wanita</a>
                        <a href="#" class="ItemListCategories">Film & Musik</a>
                        <a href="#" class="ItemListCategories">Gaming</a>
                        <a href="#" class="ItemListCategories">Handphone & Tablet</a>
                        <a href="#" class="ItemListCategories">Ibu & Bayi</a>
                        <a href="#" class="ItemListCategories">Kecantikan</a>
                        <a href="#" class="ItemListCategories">Kesehatan</a>
                        <a href="#" class="ItemListCategories">Komputer & Laptop</a>
                        <a href="#" class="ItemListCategories">Logam Mulia</a>
                        <a href="#" class="ItemListCategories">Mainan & Hobi</a>
                        <a href="#" class="ItemListCategories">Makanan & Minuman</a>
                        <a href="#" class="ItemListCategories">Office & Stationery</a>
                        <a href="#" class="ItemListCategories">Olahraga</a>
                        <a href="#" class="ItemListCategories">Otomotif</a>
                        <a href="#" class="ItemListCategories">Perawatan Hewan</a>
                        <a href="#" class="ItemListCategories">Perawatan Tubuh</a>
                        <a href="#" class="ItemListCategories">Perlengkapan Pesta</a>
                        <a href="#" class="ItemListCategories">Pertukangan</a>
                        <a href="#" class="ItemListCategories">Produk Lainnya</a>
                        <a href="#" class="ItemListCategories">Properti</a>
                        <a href="#" class="ItemListCategories">Tiket, Travel, Voucher</a>
                        <a href="#" class="ItemListCategories">Wedding</a>
                      </div>
                      <div class="AllCategoryCild">
                        <div class=" flex flex-col pt-8 px-8 ">
                          <div class="flex">
                            <img src="./../public/images/imgRumahTanggaCategory.png" alt="Rumah Tangga"
                              class="ImageCategoryCaption">
                            <div class="CaptionCategoryList">Rumah Tangga</div>
                          </div>
                          <div class="flex w-full">
                            <div class="grid grid-cols-5 gap-6 w-full">
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                              <div class="GroupSubCategoryContainer">
                                <div>
                                  <a href="#" class="SubCaptionCategory">Dekorasi</a>
                                </div>
                                <div class="ListChildCategoryContainer">
                                  <a href="#" class="ItemListChildCategory">Cover Kipas Angin</a>
                                  <a href="#" class="ItemListChildCategory">Cover Kursi</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Hiasan Natal</a>
                                  <a href="#" class="ItemListChildCategory">Jam Dinding</a>
                                  <a href="#" class="ItemListChildCategory">Jam Meja</a>
                                  <a href="#" class="ItemListChildCategory">Keset</a>
                                  <a href="#" class="ItemListChildCategory">Lampu Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Lilin Aroma Terapi</a>
                                  <a href="#" class="ItemListChildCategory">Lukisan</a>
                                  <a href="#" class="ItemListChildCategory">Patung</a>
                                  <a href="#" class="ItemListChildCategory">Pohon Natal</a>
                                  <a href="#" class="ItemListChildCategory">Reed Diffuser</a>
                                  <a href="#" class="ItemListChildCategory">Slinger</a>
                                  <a href="#" class="ItemListChildCategory">Stiker Kaca</a>
                                  <a href="#" class="ItemListChildCategory">Tanaman Artifical</a>
                                  <a href="#" class="ItemListChildCategory">Taplak Meja</a>
                                  <a href="#" class="ItemListChildCategory">Tempat Lilin</a>
                                  <a href="#" class="ItemListChildCategory">Vas Bunga</a>
                                  <a href="#" class="ItemListChildCategory">Wall Sticker</a>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </NavigationMenuContent>
              </NavigationMenuItem>
            </NavigationMenuList>
          </NavigationMenu>
        </div>
      </div>
      <div class="relative w-[49%] sm:w-[68%] md:w-[73%] min-w-[150px]">
        <div class="w-full items-center flex">
          <div class="w-full flex box-border border-[1px] border-[#BFC9D9] rounded-lg h-[40px] ">
            <div class="h-full m-0">
              <div
                class="bg-white rounded-lg overflow-hidden pl-2 pr-2 gap-2 w-full flex h-full items-center justify-center">
                <Icon name="ion:search-outline" size="24" class=" py-1 inline-block text-[#6D7588]" />
                <input type="text" class="py-2 w-full text-sm border-none outline-none text-[#212121]"
                  placeholder="Cari di TukuBin">
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex items-center ml-[40px] z-[475] flex-shrink-0">
        <div class="w-[40px] h-[40px] flex justify-center items-center">
          <Icon name="ion:cart-outline" size="24" class="  py-1 inline-block text-[#6D7588]" />
        </div>
        <div class="w-[40px] h-[40px] hidden justify-center items-center">
          <Icon name="ion:notifications-outline" size="24" class="  py-1 inline-block text-[#6D7588]" />
        </div>
        <div class="w-[40px] h-[40px] hidden justify-center items-center">
          <Icon name="ion:mail-outline" size="24" class="  py-1 inline-block text-[#6D7588]" />
        </div>
      </div>
      <div class="w-[1.2px] min-w-[1.2px] h-[24px] bg-[#E4EBF5] ml-[24px]"></div>
      <div class="flex justify-between items-center gap-3 w-[158px] ml-[24px]">
        <button
          class="h-[32px] px-4 font-extrabold text-xs bg-[#FFFFFF] text-[#00AA5B] cursor-pointer border-[1px] border-[#00AA5B] rounded-lg">Masuk</button>
        <button
          class="h-[32px] text-white px-4 font-extrabold text-xs bg-[#00AA5B] cursor-pointer border-none rounded-lg">Daftar</button>
      </div>
    </div>
    <div class="fixed top-[98px] w-[45%] left-[319px] flex -z-[1]">
      <a href="#" class="trendkingKeywordList">
        Dc Mcfarlane</a>
      <a href="#" class="trendkingKeywordList">
        Ssd 1tb</a>
      <a href="#" class="trendkingKeywordList">
        Jersey Timnas</a>
      <a href="#" class="trendkingKeywordList">
        Kabel Lan</a>
      <a href="#" class="trendkingKeywordList">
        Meja Kerja</a>
      <a href="#" class="trendkingKeywordList">
        Helm Bogo </a>
    </div>
    <div class="flex justify-between fixed top-[94px] right-[24px] cursor-pointer items-center -z-[1]">
      <div class="flex items-center">
        <div>
          <Icon name="ion:location-outline" size="20" class=" w-6 h-6 py-1 inline-block text-[#6D7588]" />
        </div>
        <p class="block relative font-normal text-[0.857143rem] leading-4 tracking-[0px] text-[#212121] mx-1">Dikirim ke
        </p>
        <p
          class=" whitespace-nowrap overflow-hidden overflow-ellipsis max-w-[100%-100px] flex-shrink-[1] text-[0.857143rem]">
          <b>Jakarta
            Pusat</b>
        </p>
        <div class="text-[#212121] w-5 h-5">
          <svg width="100%" height="100%" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M12 15.25a.74.74 0 0 1-.53-.22l-5-5A.75.75 0 0 1 7.53 9L12 13.44 16.47 9a.75.75 0 0 1 1.06 1l-5 5a.74.74 0 0 1-.53.25Z">
            </path>
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style>

</style>