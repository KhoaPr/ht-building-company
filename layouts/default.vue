<template>
  <div class="bg-cyan-950 mx-auto hidden lg:block">
    <div class="flex justify-between max-w-none h-14">
      <div class="flex justify-start w-1/2">
        <!-- Thẻ div Call -->
        <div
          class="font-sans ml-44 flex items-center justify-center text-sm font-medium"
        >
          <p class="text-white">Call:</p>
          <p class="text-white ml-4">0987654321</p>
        </div>
        <!-- Thẻ div Mail -->
        <div
          class="font-sans ml-10 flex items-center justify-center text-sm font-medium"
        >
          <p class="text-white">Mail:</p>
          <p class="text-white ml-4">abc@gmail.com</p>
        </div>
      </div>
      <div class="flex justify-end w-1/2">
        <div
          class="md:ml-10 font-sans ml-20 flex items-center justify-center text-sm font-medium mr-20"
        >
          <p class="text-white mr-6">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              height="1.5em"
              viewBox="0 0 448 512"
            >
              <path
                d="M400 32H48A48 48 0 0 0 0 80v352a48 48 0 0 0 48 48h137.25V327.69h-63V256h63v-54.64c0-62.15 37-96.48 93.67-96.48 27.14 0 55.52 4.84 55.52 4.84v61h-31.27c-30.81 0-40.42 19.12-40.42 38.73V256h68.78l-11 71.69h-57.78V480H400a48 48 0 0 0 48-48V80a48 48 0 0 0-48-48z"
              />
            </svg>
          </p>
          <p class="text-white mr-6">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              height="1.5em"
              viewBox="0 0 640 512"
            >
              <path
                d="M386.061 228.496c1.834 9.692 3.143 19.384 3.143 31.956C389.204 370.205 315.599 448 204.8 448c-106.084 0-192-85.915-192-192s85.916-192 192-192c51.864 0 95.083 18.859 128.611 50.292l-52.126 50.03c-14.145-13.621-39.028-29.599-76.485-29.599-65.484 0-118.92 54.221-118.92 121.277 0 67.056 53.436 121.277 118.92 121.277 75.961 0 104.513-54.745 108.965-82.773H204.8v-66.009h181.261zm185.406 6.437V179.2h-56.001v55.733h-55.733v56.001h55.733v55.733h56.001v-55.733H627.2v-56.001h-55.733z"
              />
            </svg>
          </p>
          <p class="text-white mr-6">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              height="1.5em"
              viewBox="0 0 576 512"
            >
              <path
                d="M549.655 124.083c-6.281-23.65-24.787-42.276-48.284-48.597C458.781 64 288 64 288 64S117.22 64 74.629 75.486c-23.497 6.322-42.003 24.947-48.284 48.597-11.412 42.867-11.412 132.305-11.412 132.305s0 89.438 11.412 132.305c6.281 23.65 24.787 41.5 48.284 47.821C117.22 448 288 448 288 448s170.78 0 213.371-11.486c23.497-6.321 42.003-24.171 48.284-47.821 11.412-42.867 11.412-132.305 11.412-132.305s0-89.438-11.412-132.305zm-317.51 213.508V175.185l142.739 81.205-142.739 81.201z"
              />
            </svg>
          </p>
          <a class="text-white mr-6"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              height="1.5em"
              viewBox="0 0 448 512"
            >
              <path
                d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"
              /></svg
          ></a>
        </div>
      </div>
    </div>
  </div>

  <header class="bg-white sticky top-0 shadow-md bg-opacity-60">
    <nav class="mx-auto flex max-w-7xl items-center justify-between lg:px-7 lg:py-0 py-4 " aria-label="Global">
      <div class="flex lg:flex-1 ">
        <a href="/" class="-m-1.5 p-1.5 pl-8">
          <span class="sr-only">Your Company</span>
          <img src="//theme.hstatic.net/1000184473/1000237392/14/logo.png?v=328" alt="HT Building Company">
        </a>
      </div>
      <div class="flex lg:hidden">
        <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 lg:mr-0 mr-5 text-gray-700" @click="mobileMenuOpen = true">
          <span class="sr-only">Open main menu</span>
          <Bars3Icon class="h-6 w-6" aria-hidden="true" />
        </button>
      </div>
      <PopoverGroup class="hidden lg:flex lg:gap-x-12 h-20 ">
        <a href="/" class="text-sm font-semibold leading-6 text-gray-900 flex items-center hover:border-t-yellow-400 hover:border-t-4 hover:bg-zinc-100 px-1">TRANG CHỦ</a>
        <Popover class="relative">
          <PopoverButton class="flex items-center gap-x-1 text-sm font-semibold leading-6 text-gray-900 py-7 hover:border-t-yellow-400 hover:border-t-4 hover:bg-zinc-100 px-1">
          GIỚI THIỆU
            <ChevronDownIcon class="h-5 w-5 flex-none text-gray-400" aria-hidden="true" />
          </PopoverButton>
          <transition enter-active-class="transition ease-out duration-200" enter-from-class="opacity-0 translate-y-1" enter-to-class="opacity-100 translate-y-0" leave-active-class="transition ease-in duration-150" leave-from-class="opacity-100 translate-y-0" leave-to-class="opacity-0 translate-y-1">
            <PopoverPanel class="absolute -left-8 top-full z-10 w-[300px] max-w-md overflow-hidden rounded-1xl bg-white shadow-lg ring-1 ring-gray-900/5">
              <div class="p-4">
                <div v-for="item in products" :key="item.name" class="group relative flex items-center gap-x-6 rounded-lg p-2 text-sm hover:bg-zinc-100">
                  <div class="flex-auto">
                    <a :href="item.href" class="block font-semibold text-gray-900">
                      {{ item.name }}
                      <span class="absolute inset-0" />
                    </a>
                    <p class="mt-1 text-gray-600">{{ item.description }}</p>
                  </div>
                </div>
              </div>
            </PopoverPanel>
          </transition>
        </Popover>

        <Popover class="relative">
          <PopoverButton class="flex items-center gap-x-1 text-sm font-semibold leading-6 text-gray-900 py-7 hover:border-t-yellow-400 hover:border-t-4 hover:bg-zinc-100 px-1">
          DỊCH VỤ
            <ChevronDownIcon class="h-5 w-5 flex-none text-gray-400" aria-hidden="true" />
          </PopoverButton>
          <transition enter-active-class="transition ease-out duration-200" enter-from-class="opacity-0 translate-y-1" enter-to-class="opacity-100 translate-y-0" leave-active-class="transition ease-in duration-150" leave-from-class="opacity-100 translate-y-0" leave-to-class="opacity-0 translate-y-1">
            <PopoverPanel class="absolute -left-8 top-full z-10 w-[300px] max-w-md overflow-hidden rounded-1xl bg-white shadow-lg ring-1 ring-gray-900/5">
              <div class="p-4">
                <div v-for="item in dichvu" :key="item.name" class="group relative flex items-center gap-x-6 rounded-lg p-2 text-sm hover:bg-zinc-100">
                  <div class="flex-auto">
                    <a :href="item.href" class="block font-semibold text-gray-900">
                      {{ item.name }}
                      <span class="absolute inset-0" />
                    </a>
                    <p class="mt-1 text-gray-600">{{ item.description }}</p>
                  </div>
                </div>
              </div>
            </PopoverPanel>
          </transition>
        </Popover>

        <a href="news" class="text-sm font-semibold leading-6 text-gray-900 flex items-center hover:border-t-yellow-400 hover:border-t-4 hover:bg-zinc-100 px-1">TIN TỨC</a>
        <a href="contact" class="text-sm font-semibold leading-6 text-gray-900 flex items-center hover:border-t-yellow-400 hover:border-t-4 hover:bg-zinc-100 px-1">LIÊN HỆ</a>
      </PopoverGroup>


      
    </nav>
    <Dialog as="div" class="lg:hidden" @close="mobileMenuOpen = false" :open="mobileMenuOpen">
      <div class="fixed inset-0 z-10" />
      <DialogPanel class="fixed inset-y-0 right-0 z-10 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10">
        <div class="flex items-center justify-between">
          <a href="/" class="-m-1.5 p-1.5">
            <span class="sr-only">Your Company</span>

          </a>
          <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700" @click="mobileMenuOpen = false">
            <span class="sr-only">Close menu</span>
            <XMarkIcon class="h-6 w-6" aria-hidden="true" />
          </button>
        </div>
        <div class="mt-6 flow-root">
          <div class="-my-6 divide-y divide-gray-500/10">
            <div class="space-y-2 py-6">
              <a href="/" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-zinc-100">TRANG CHỦ</a>
              <Disclosure as="div" class="-mx-3" v-slot="{ open }">
                <DisclosureButton class="flex w-full items-center justify-between rounded-lg py-2 pl-3 pr-3.5 text-base font-semibold leading-7 text-gray-900 hover:bg-zinc-100">
                  GIỚI THIỆU
                  <ChevronDownIcon :class="[open ? 'rotate-180' : '', 'h-5 w-5 flex-none']" aria-hidden="true" />
                </DisclosureButton>
                <DisclosurePanel class="mt-2 space-y-2">
                  <DisclosureButton v-for="item in [...products, ...callsToAction]" :key="item.name" as="a" :href="item.href" class="block rounded-lg py-2 pl-6 pr-3 text-sm font-semibold leading-7 text-gray-900 hover:bg-zinc-100">{{ item.name }}</DisclosureButton>
                </DisclosurePanel>
              </Disclosure>
              
              <Disclosure as="div" class="-mx-3" v-slot="{ open }">
                <DisclosureButton class="flex w-full items-center justify-between rounded-lg py-2 pl-3 pr-3.5 text-base font-semibold leading-7 text-gray-900 hover:bg-zinc-100">
                  DỊCH VỤ
                  <ChevronDownIcon :class="[open ? 'rotate-180' : '', 'h-5 w-5 flex-none']" aria-hidden="true" />
                </DisclosureButton>
                <DisclosurePanel class="mt-2 space-y-2">
                  <DisclosureButton v-for="item in [...dichvu, ...callsToAction]" :key="item.name" as="a" :href="item.href" class="block rounded-lg py-2 pl-6 pr-3 text-sm font-semibold leading-7 text-gray-900 hover:bg-zinc-100">{{ item.name }}</DisclosureButton>
                </DisclosurePanel>
              </Disclosure>
              <a href="news" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-zinc-100">TIN TỨC</a>
              <a href="contact" class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-zinc-100">LIÊN HỆ</a>
            </div>
          </div>
        </div>
      </DialogPanel>
    </Dialog>
  </header>

  <div>
    <slot />
  </div>


  <div class="swiper-container h-[155px]">
    <div><p class="text-black font-bold text-[28px] 2xl:ml-44 ml-5 pt-3 mx-auto">KHÁCH HÀNG CỦA CHÚNG TÔI</p></div>
    <div class="swiper-wrapper flex flex-row justify-center items-center pt-10">
      <!-- Thêm các slide ở đây -->
      <div class="swiper-slide">
        <img src="//theme.hstatic.net/1000184473/1000237392/14/doitac-1.png?v=328" alt="Brand 1">
      </div>
      <div class="swiper-slide">
        <img src="//theme.hstatic.net/1000184473/1000237392/14/doitac-2.png?v=328" alt="Brand 2">
      </div>
      <div class="swiper-slide">
        <img src="//theme.hstatic.net/1000184473/1000237392/14/doitac-3.png?v=328" alt="Brand 3">
      </div>
      <div class="swiper-slide">
        <img src="//theme.hstatic.net/1000184473/1000237392/14/doitac-4.png?v=328" alt="Brand 4">
      </div>
      <div class="swiper-slide">
        <img src="//theme.hstatic.net/1000184473/1000237392/14/doitac-5.png?v=328" alt="Brand 5">
      </div>
      <div class="swiper-slide">
        <img src="//theme.hstatic.net/1000184473/1000237392/14/doitac-6.png?v=328" alt="Brand 6">
      </div>
      <!-- Thêm slide khác tùy ý -->
    </div>

    <!-- Thêm nút điều hướng nếu cần -->
    <div class="swiper-button-next"></div>
    <div class="swiper-button-prev"></div>
  </div>

  <footer>
    <div
      class="flex lg:flex-row flex-col w-full lg:h-[320px] h-850px] bg-cyan-900 text-white pt-[30px]"
    >
      <div class="lg:w-4/12 w-full xl:pl-[150px] mb-5">
        <h4 class="mb-5">VỀ CHÚNG TÔI</h4>
        <p class="text-sm">
          Với đội ngũ nhân viên trẻ, năng động, nhiệt huyết và chuyên nghiệp,
          CONTRUCTION tin rằng sẽ mang đến cho khách hàng không gian sống và làm
          việc không những sang trọng, đẳng cấp mà còn thể hiện được nét văn hóa
          riêng của mỗi doanh nghiệp, gia đình. Tiêu chí kinh doanh hàng đầu của
          chúng tôi là tạo ra sản phẩm nội thất độc đáo, cung cấp giải pháp tối
          ưu cho khách hàng và đảm bảo hoàn thành dự án theo đúng ý tưởng thiết
          kế, chất lượng và tiến độ đã đề ra. Chúng tôi rất hân hạnh thiết lập
          mối quan hệ hợp tác lâu dài cùng Quí vị.
        </p>
      </div>
      <div class="lg:w-4/12 w-full lg:pl-[40px]">
        <h4 class="mb-5 text">ĐỊA CHỈ</h4>
        <p class="text_ft mb-5">📍 47 đường số 19, Thủ Đức, TP HCM</p>
        <p class="text_ft mb-5">📱 0972 214 097</p>
        <p class="text_ft mb-5">✉ thanh.nguyenhoai0912@gmail.com</p>
        <h4 class="mb-5">ĐĂNG KÝ NHẬN THÔNG BÁO</h4>
        <div class="flex sm:flex-row mx-1">
          <input
            class="sm:w-64 w-full h-9"
            name="contact[email]"
            type="email"
            id="contact_email"
            placeholder="  Đăng ký email"
            required=""
          />
          <button
            class="bg-white text-cyan-900 text-sm font-bold ml-2 sm:ml-2 w-24 h-9 lg:mb-0 mb-5 hover:bg-yellow-300"
          >
            Đăng Ký
          </button>
        </div>
      </div>
      <div class="lg:w-4/12 w-full">
        <h4 class="mb-5">FANPAGE</h4>
        <div class="">
          <iframe
            src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Ffacebook%3Flocale%3Dvi_VN&tabs=DangKhoaPX&width=300&height=10&small_header=false&adapt_container_width=false&hide_cover=false&show_facepile=false&appId=3080470772205455"
            width="300"
            height="150"
            style="border: none; overflow: hidden"
            scrolling="no"
            frameborder="0"
            allowfullscreen="true"
            allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
          ></iframe>
        </div>
        <div class="flex flex-row">
          <div class="mr-3">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="2em"
            viewBox="0 0 512 512"
          >
            <path
              d="M504 256C504 119 393 8 256 8S8 119 8 256c0 123.78 90.69 226.38 209.25 245V327.69h-63V256h63v-54.64c0-62.15 37-96.48 93.67-96.48 27.14 0 55.52 4.84 55.52 4.84v61h-31.28c-30.8 0-40.41 19.12-40.41 38.73V256h68.78l-11 71.69h-57.78V501C413.31 482.38 504 379.78 504 256z"
            />
          </svg>
        </div>
        <div class="mr-3">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="2em"
            viewBox="0 0 512 512"
          >
            <path
              d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"
            />
          </svg>
        </div>
        <div class="mr-3">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="2em"
            viewBox="0 0 640 512"
          >
            <path
              d="M386.061 228.496c1.834 9.692 3.143 19.384 3.143 31.956C389.204 370.205 315.599 448 204.8 448c-106.084 0-192-85.915-192-192s85.916-192 192-192c51.864 0 95.083 18.859 128.611 50.292l-52.126 50.03c-14.145-13.621-39.028-29.599-76.485-29.599-65.484 0-118.92 54.221-118.92 121.277 0 67.056 53.436 121.277 118.92 121.277 75.961 0 104.513-54.745 108.965-82.773H204.8v-66.009h181.261zm185.406 6.437V179.2h-56.001v55.733h-55.733v56.001h55.733v55.733h56.001v-55.733H627.2v-56.001h-55.733z"
            />
          </svg>
        </div>
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="2em"
            viewBox="0 0 448 512"
          >
            <path
              d="M224,202.66A53.34,53.34,0,1,0,277.36,256,53.38,53.38,0,0,0,224,202.66Zm124.71-41a54,54,0,0,0-30.41-30.41c-21-8.29-71-6.43-94.3-6.43s-73.25-1.93-94.31,6.43a54,54,0,0,0-30.41,30.41c-8.28,21-6.43,71.05-6.43,94.33S91,329.26,99.32,350.33a54,54,0,0,0,30.41,30.41c21,8.29,71,6.43,94.31,6.43s73.24,1.93,94.3-6.43a54,54,0,0,0,30.41-30.41c8.35-21,6.43-71.05,6.43-94.33S357.1,182.74,348.75,161.67ZM224,338a82,82,0,1,1,82-82A81.9,81.9,0,0,1,224,338Zm85.38-148.3a19.14,19.14,0,1,1,19.13-19.14A19.1,19.1,0,0,1,309.42,189.74ZM400,32H48A48,48,0,0,0,0,80V432a48,48,0,0,0,48,48H400a48,48,0,0,0,48-48V80A48,48,0,0,0,400,32ZM382.88,322c-1.29,25.63-7.14,48.34-25.85,67s-41.4,24.63-67,25.85c-26.41,1.49-105.59,1.49-132,0-25.63-1.29-48.26-7.15-67-25.85s-24.63-41.42-25.85-67c-1.49-26.42-1.49-105.61,0-132,1.29-25.63,7.07-48.34,25.85-67s41.47-24.56,67-25.78c26.41-1.49,105.59-1.49,132,0,25.63,1.29,48.33,7.15,67,25.85s24.63,41.42,25.85,67.05C384.37,216.44,384.37,295.56,382.88,322Z"
            />
          </svg>
        </div>
        </div>
        <div></div>
      </div>
    </div>
  </footer>

  <div class="relative isolate gap-x-6 overflow-hidden bg-gray-50 pl-6 py-2.5 sm:px-3.5 sm:before:flex-1">
    <div class="">
      <a href="https://www.haravan.com/" class="text-sm lg:pl-44 leading-6 text-gray-900">
        Copyright © 2017 HT Building Company. Powered by Haravan
        </a>
      <a href="about" class="flex-none rounded-full float-right mr-40 bg-gray-900 px-3.5 py-1 text-sm font-semibold text-white shadow-sm hover:bg-gray-700 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2">GIỚI THIỆU</a>
      <a href="search" class="flex-none rounded-full float-right  bg-gray-900 px-3.5 py-1 text-sm font-semibold text-white shadow-sm hover:bg-gray-700 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 ">TÌM KIẾM</a>
    </div>

  </div>
</template>

<script setup>
import { ref } from 'vue'
import {
  Dialog,
  DialogPanel,
  Disclosure,
  DisclosureButton,
  DisclosurePanel,
  Popover,
  PopoverButton,
  PopoverGroup,
  PopoverPanel,
} from '@headlessui/vue'
import {
  ArrowPathIcon,
  Bars3Icon,
  ChartPieIcon,
  CursorArrowRaysIcon,
  FingerPrintIcon,
  SquaresPlusIcon,
  XMarkIcon,
} from '@heroicons/vue/24/outline'
import { ChevronDownIcon, PhoneIcon, PlayCircleIcon } from '@heroicons/vue/20/solid'

const products = [
  { name: 'Về chúng tôi', href: 'about'},
  { name: 'Lịch sử hình thành', href: 'history'},  
]
const callsToAction = [

]

const dichvu = [
  { name: 'Thi công xây dựng', href: 'construction'},
  { name: 'Xây dựng công trình', href: 'construct'}, 
  { name: 'Sơn sửa công trình', href: 'paint'},  
]

const mobileMenuOpen = ref(false)
</script>