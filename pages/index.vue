
<template>


  <div class="relative mb-10">
    <div class="carousel">
      <button @click="prevImage"
        class="absolute left-0 top-1/2 transform -translate-y-1/2 bg-gray-300 p-2 rounded-full opacity-50 hover:opacity-100 transition-opacity duration-300">
        &lt;
      </button>
      <img :src="images[currentImage]" alt="Carousel Image" class="mx-auto slide-image" :key="currentImage" />
      <button @click="nextImage"
        class="absolute right-0 top-1/2 transform -translate-y-1/2 bg-gray-300 p-2 rounded-full opacity-50 hover:opacity-100 transition-opacity duration-300">
        &gt;
      </button>
    </div>
  </div>



  <div class="flex flex-row 2xl:mx-40 mb-20 lg:mx-8">
    <div class="flex lg:flex-row flex-col md:pr-20 pr-0 h-full w-full mx-auto mb-16 ">
      <div class="flex-none lg:ml-0 md:ml-0 mx-10 md:pl-10 pl-0" >
        <img src="//theme.hstatic.net/1000184473/1000237392/14/whoweare.jpg?v=328" alt="Chúng tôi là ai">
      </div>
      <div class="2xl:pl-14 2xl:pt-[100px] md:pl-10 pl-0 mt-5 mb-10">
        <div class="text-sm font-medium text-gray-500">
          Với đội ngũ nhân viên trẻ, năng động, nhiệt huyết và chuyên nghiệp,
          Contruction tin rằng sẽ mang đến cho khách hàng không gian sống và làm việc không những sang trọng,
          đẳng cấp mà còn thể hiện được nét văn hóa riêng của mỗi doanh nghiệp, gia đình.
        </div>
        <div class="mt-10">
          <button
            class="bg-yellow-400 w-[146px] h-[45px] rounded-md font-semibold text-white hover:text-yellow-400 hover:bg-white hover:border-yellow-400 hover:border">XEM
            TIẾP »</button>
        </div>
      </div>
    </div>
  </div>




  <div class="grid lg:grid-cols-4 md:grid-cols-2 grid-cols-1 gap-10 2xl:mx-40 lg:mx-10 md:mx-20 mx-10 text-center mb-20">
    <div class="h-[300px] bg-zinc-200">
      <div class="flex justify-center mt-20">
        <svg xmlns="http://www.w3.org/2000/svg" height="2em"
          viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
          <path
            d="M208 64a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zM9.8 214.8c5.1-12.2 19.1-18 31.4-12.9L60.7 210l22.9-38.1C99.9 144.6 129.3 128 161 128c51.4 0 97 32.9 113.3 81.7l34.6 103.7 79.3 33.1 34.2-45.6c6.4-8.5 16.6-13.3 27.2-12.8s20.3 6.4 25.8 15.5l96 160c5.9 9.9 6.1 22.2 .4 32.2s-16.3 16.2-27.8 16.2H288c-11.1 0-21.4-5.7-27.2-15.2s-6.4-21.2-1.4-31.1l16-32c5.4-10.8 16.5-17.7 28.6-17.7h32l22.5-30L22.8 246.2c-12.2-5.1-18-19.1-12.9-31.4zm82.8 91.8l112 48c11.8 5 19.4 16.6 19.4 29.4v96c0 17.7-14.3 32-32 32s-32-14.3-32-32V405.1l-60.6-26-37 111c-5.6 16.8-23.7 25.8-40.5 20.2S-3.9 486.6 1.6 469.9l48-144 11-33 32 13.7z" />
        </svg>
      </div>
      <h3 class="mt-6 mb-4">SÁNG TẠO</h3>
      <p class="text-sm">Với đội ngũ kiến trúc sư, kỹ sư, thợ lành nghề, dồi dào kinh nghiệm, công ty sẽ mang đến cho
        khách hàng sự hài lòng về chất lượng công trình đồng...</p>
    </div>

    <div class="h-[300px] bg-zinc-200">
      <div class="flex justify-center mt-20">
        <svg xmlns="http://www.w3.org/2000/svg" height="2em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M438.6 105.4c12.5 12.5 12.5 32.8 0 45.3l-256 256c-12.5 12.5-32.8 12.5-45.3 0l-128-128c-12.5-12.5-12.5-32.8 0-45.3s32.8-12.5 45.3 0L160 338.7 393.4 105.4c12.5-12.5 32.8-12.5 45.3 0z"/></svg>
      </div>
      <h3 class="mt-6 mb-4">AN TOÀN</h3>
      <p class="text-sm">Với đội ngũ kiến trúc sư, kỹ sư, thợ lành nghề, dồi dào kinh nghiệm, công ty sẽ mang đến cho
        khách hàng sự hài lòng về chất lượng công trình đồng...</p>
    </div>

    <div class="h-[300px] bg-zinc-200">
      <div class="flex justify-center mt-20">
        <svg xmlns="http://www.w3.org/2000/svg" height="2em" viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M495.9 166.6c3.2 8.7 .5 18.4-6.4 24.6l-43.3 39.4c1.1 8.3 1.7 16.8 1.7 25.4s-.6 17.1-1.7 25.4l43.3 39.4c6.9 6.2 9.6 15.9 6.4 24.6c-4.4 11.9-9.7 23.3-15.8 34.3l-4.7 8.1c-6.6 11-14 21.4-22.1 31.2c-5.9 7.2-15.7 9.6-24.5 6.8l-55.7-17.7c-13.4 10.3-28.2 18.9-44 25.4l-12.5 57.1c-2 9.1-9 16.3-18.2 17.8c-13.8 2.3-28 3.5-42.5 3.5s-28.7-1.2-42.5-3.5c-9.2-1.5-16.2-8.7-18.2-17.8l-12.5-57.1c-15.8-6.5-30.6-15.1-44-25.4L83.1 425.9c-8.8 2.8-18.6 .3-24.5-6.8c-8.1-9.8-15.5-20.2-22.1-31.2l-4.7-8.1c-6.1-11-11.4-22.4-15.8-34.3c-3.2-8.7-.5-18.4 6.4-24.6l43.3-39.4C64.6 273.1 64 264.6 64 256s.6-17.1 1.7-25.4L22.4 191.2c-6.9-6.2-9.6-15.9-6.4-24.6c4.4-11.9 9.7-23.3 15.8-34.3l4.7-8.1c6.6-11 14-21.4 22.1-31.2c5.9-7.2 15.7-9.6 24.5-6.8l55.7 17.7c13.4-10.3 28.2-18.9 44-25.4l12.5-57.1c2-9.1 9-16.3 18.2-17.8C227.3 1.2 241.5 0 256 0s28.7 1.2 42.5 3.5c9.2 1.5 16.2 8.7 18.2 17.8l12.5 57.1c15.8 6.5 30.6 15.1 44 25.4l55.7-17.7c8.8-2.8 18.6-.3 24.5 6.8c8.1 9.8 15.5 20.2 22.1 31.2l4.7 8.1c6.1 11 11.4 22.4 15.8 34.3zM256 336a80 80 0 1 0 0-160 80 80 0 1 0 0 160z"/></svg>
      </div>
      <h3 class="mt-6 mb-4">BẢO MẬT</h3>
      <p class="text-sm">Với đội ngũ kiến trúc sư, kỹ sư, thợ lành nghề, dồi dào kinh nghiệm, công ty sẽ mang đến cho
        khách hàng sự hài lòng về chất lượng công trình đồng...</p>
    </div>

    <div class="h-[300px] bg-zinc-200">
      <div class="flex justify-center mt-20">
        <svg xmlns="http://www.w3.org/2000/svg" height="2em" viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M400 0H176c-26.5 0-48.1 21.8-47.1 48.2c.2 5.3 .4 10.6 .7 15.8H24C10.7 64 0 74.7 0 88c0 92.6 33.5 157 78.5 200.7c44.3 43.1 98.3 64.8 138.1 75.8c23.4 6.5 39.4 26 39.4 45.6c0 20.9-17 37.9-37.9 37.9H192c-17.7 0-32 14.3-32 32s14.3 32 32 32H384c17.7 0 32-14.3 32-32s-14.3-32-32-32H357.9C337 448 320 431 320 410.1c0-19.6 15.9-39.2 39.4-45.6c39.9-11 93.9-32.7 138.2-75.8C542.5 245 576 180.6 576 88c0-13.3-10.7-24-24-24H446.4c.3-5.2 .5-10.4 .7-15.8C448.1 21.8 426.5 0 400 0zM48.9 112h84.4c9.1 90.1 29.2 150.3 51.9 190.6c-24.9-11-50.8-26.5-73.2-48.3c-32-31.1-58-76-63-142.3zM464.1 254.3c-22.4 21.8-48.3 37.3-73.2 48.3c22.7-40.3 42.8-100.5 51.9-190.6h84.4c-5.1 66.3-31.1 111.2-63 142.3z"/></svg>
      </div>
      <h3 class="mt-6 mb-4">CHẤT LƯỢNG</h3>
      <p class="text-sm">Với đội ngũ kiến trúc sư, kỹ sư, thợ lành nghề, dồi dào kinh nghiệm, công ty sẽ mang đến cho
        khách hàng sự hài lòng về chất lượng công trình đồng...</p>
    </div>
  </div>



  <div class="flex lg:flex-row flex-col w-full mx-auto">
    <div class="2xl:pr-32 md:pr-20 lg:ml-0 md:ml-20 lg:mx-auto mx-10 text-right">
      <div class="flex md:flex-row my-auto md:mt-32 mt-10">
        <div class="">
          <p class="float-right font-normal text-lg">THI CÔNG XÂY DỰNG</p>
          <p class="float-right text-zinc-500 xl:pl-28 text-sm ">
            Với đội ngũ kiến trúc sư, kỹ sư, thợ lành nghề, dồi dào kinh nghiệm,
            công ty sẽ mang đến cho khách hàng sự hài lòng về chất lượng công trình
          </p>
        </div>
        <div class="flex items-center justify-center 2xl:ml-10 ml-10  ">
          <svg xmlns="http://www.w3.org/2000/svg" height="2em"
            viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
            <path
              d="M208 64a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zM9.8 214.8c5.1-12.2 19.1-18 31.4-12.9L60.7 210l22.9-38.1C99.9 144.6 129.3 128 161 128c51.4 0 97 32.9 113.3 81.7l34.6 103.7 79.3 33.1 34.2-45.6c6.4-8.5 16.6-13.3 27.2-12.8s20.3 6.4 25.8 15.5l96 160c5.9 9.9 6.1 22.2 .4 32.2s-16.3 16.2-27.8 16.2H288c-11.1 0-21.4-5.7-27.2-15.2s-6.4-21.2-1.4-31.1l16-32c5.4-10.8 16.5-17.7 28.6-17.7h32l22.5-30L22.8 246.2c-12.2-5.1-18-19.1-12.9-31.4zm82.8 91.8l112 48c11.8 5 19.4 16.6 19.4 29.4v96c0 17.7-14.3 32-32 32s-32-14.3-32-32V405.1l-60.6-26-37 111c-5.6 16.8-23.7 25.8-40.5 20.2S-3.9 486.6 1.6 469.9l48-144 11-33 32 13.7z" />
          </svg>
        </div>
      </div>

      <div class="flex md:flex-row my-auto 2xl:mt10 mt-10">
        <div class="">
          <p class="float-right font-normal text-lg">XÂY DỰNG CÔNG TRÌNH</p>
          <p class="float-right text-zinc-500 xl:pl-28 text-sm">
            Với đội ngũ kiến trúc sư, kỹ sư, thợ lành nghề, dồi dào kinh nghiệm,
            công ty sẽ mang đến cho khách hàng sự hài lòng về chất lượng công trình
          </p>
        </div>
        <div class="flex items-center justify-center 2xl:ml-10 ml-10">
          <svg xmlns="http://www.w3.org/2000/svg" height="2em"
            viewBox="0 0 512 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
            <path
              d="M78.6 5C69.1-2.4 55.6-1.5 47 7L7 47c-8.5 8.5-9.4 22-2.1 31.6l80 104c4.5 5.9 11.6 9.4 19 9.4h54.1l109 109c-14.7 29-10 65.4 14.3 89.6l112 112c12.5 12.5 32.8 12.5 45.3 0l64-64c12.5-12.5 12.5-32.8 0-45.3l-112-112c-24.2-24.2-60.6-29-89.6-14.3l-109-109V104c0-7.5-3.5-14.5-9.4-19L78.6 5zM19.9 396.1C7.2 408.8 0 426.1 0 444.1C0 481.6 30.4 512 67.9 512c18 0 35.3-7.2 48-19.9L233.7 374.3c-7.8-20.9-9-43.6-3.6-65.1l-61.7-61.7L19.9 396.1zM512 144c0-10.5-1.1-20.7-3.2-30.5c-2.4-11.2-16.1-14.1-24.2-6l-63.9 63.9c-3 3-7.1 4.7-11.3 4.7H352c-8.8 0-16-7.2-16-16V102.6c0-4.2 1.7-8.3 4.7-11.3l63.9-63.9c8.1-8.1 5.2-21.8-6-24.2C388.7 1.1 378.5 0 368 0C288.5 0 224 64.5 224 144l0 .8 85.3 85.3c36-9.1 75.8 .5 104 28.7L429 274.5c49-23 83-72.8 83-130.5zM56 432a24 24 0 1 1 48 0 24 24 0 1 1 -48 0z" />
          </svg>
        </div>
      </div>


      <div class="flex md:flex-row my-auto 2xl:mt10 mt-10 xl:mb-0 mb-10">
        <div class="">
          <p class="float-right font-normal text-lg">SƠN SỬA CÔNG TRÌNH</p>
          <p class="float-right text-zinc-500 xl:pl-28 text-sm">
            Với đội ngũ kiến trúc sư, kỹ sư, thợ lành nghề, dồi dào kinh nghiệm,
            công ty sẽ mang đến cho khách hàng sự hài lòng về chất lượng công trình
          </p>
        </div>
        <div class="flex items-center justify-center 2xl:ml-10 ml-10">
          <svg xmlns="http://www.w3.org/2000/svg" height="2em"
            viewBox="0 0 384 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
            <path
              d="M162.4 6c-1.5-3.6-5-6-8.9-6h-19c-3.9 0-7.5 2.4-8.9 6L104.9 57.7c-3.2 8-14.6 8-17.8 0L66.4 6c-1.5-3.6-5-6-8.9-6H48C21.5 0 0 21.5 0 48V224v22.4V256H9.6 374.4 384v-9.6V224 48c0-26.5-21.5-48-48-48H230.5c-3.9 0-7.5 2.4-8.9 6L200.9 57.7c-3.2 8-14.6 8-17.8 0L162.4 6zM0 288v32c0 35.3 28.7 64 64 64h64v64c0 35.3 28.7 64 64 64s64-28.7 64-64V384h64c35.3 0 64-28.7 64-64V288H0zM192 432a16 16 0 1 1 0 32 16 16 0 1 1 0-32z" />
          </svg>
        </div>
      </div>


    </div>
    <div class="flex-none lg:ml-0 md:ml-20 mx-10">
      <img class="md:h-[555px] md:w-[555px] w-full" src="//theme.hstatic.net/1000184473/1000237392/14/service.jpg?v=328"
        alt="">
    </div>
  </div>

  <div class="mb-36 bg-[url('/assets/photos/slideshow_2.webp')] w-full md:h-[273px] h-[520px] bg-no-repeat bg-cover bg-center md:mt-20 mt-0">
    <div class="w-full h-full flex md:flex-row flex-col justify-around items-center text-center text-white">
      <div class="w-auto h-auto">
        <div class="text-2xl font-bold">
          Dự án hoàn thành
        </div>
        <div class="text-4xl font-bold">
          1000
        </div>
      </div>
      <div class="w-auto h-auto">
        <div class="text-2xl font-bold">
          Dự án đang làm
        </div>
        <div class="text-4xl font-bold">
          99
        </div>
      </div>
      <div class="w-auto h-auto">
        <div class="text-2xl font-bold">
          Khách hàng
        </div>
        <div class="text-4xl font-bold">
          1009
        </div>
      </div>
      <div class="w-auto h-auto">
        <div class="text-2xl font-bold">
          Nhân viên
        </div>
        <div class="text-4xl font-bold">
          179
        </div>
      </div>
    </div>
  </div>


  <div class=" flex flex-row 2xl:mx-40 mb-20 lg:mx-8 mt-20">
    <div class="flex md:flex-row flex-col md:pr-10 pr-0 h-full w-full mx-auto mb-16">
      <div class="flex-none lg:ml-0 md:ml-0 mx-10 md:pl-10 pl-0">
        <img src="//theme.hstatic.net/1000184473/1000237392/14/whyus.jpg?v=328" alt="Tại sao ">
      </div>
      <div class="2xl:pl-14 2xl:pt-[30px] mt-[30px] md:pl-0 mb-20 mx-auto">
        <div class="text-sm font-medium text-gray-500">
          <p class="text-xl font-bold mt-3">✔ Chất lượng tuyệt vời</p>
          <p class="text-xl font-bold mt-3">✔ An toàn tuyệt đối</p>
          <p class="text-xl font-bold mt-3">✔ Sáng tạo không giới hạn</p>
          <p class="text-xl font-bold mt-3">✔ Bảo mật thông tin</p>
          <p class="text-xl font-bold mt-3">✔ Tuân thủ đúng thời gian</p>
          <p class="text-xl font-bold mt-3">✔ Nhân viên thân thiện, dễ thương</p>
        </div>
      </div>
    </div>
  </div>


  <div class="swiper-container h-[600px] hidden 2xl:block">
    <div><p class="text-black font-bold text-[28px] 2xl:ml-44 ml-5 pt-3 mx-auto">TIN TỨC</p></div>
    <div class="swiper-wrapper flex flex-row justify-center items-center pt-10 pl-5">
      <!-- Thêm các slide ở đây -->
      <div class="swiper-slide">
        <div class="min-[830px]:w-[360px] w-full">
    <div class="flex justify-center">
        <img class="imgnews" src="//file.hstatic.net/1000184473/article/blog-construction-1-450x231_511e7daf6f9849c6af7b8236841090ce_large.jpg" alt="">
    </div>
    <div class="news grid grid-rows-3 grid-flow-col gap-4">
<div class="calendar mt-4 ">
    <div class="col-span-2 h-7 bg-gray-200"><p class="text-base justify-center text-center">27</p></div>
    <div class="col-span-2 h-6 bg-yellow-300"><p class="text-xs justify-center text-center">Tháng 05</p></div>
</div>
<div class="row-span-3 h-10 mt-4 text-lg font-semibold ml-14">
    <a class="hover:text-yellow-500" href="">Thiết kế quán cafe cực đẹp</a>
</div>
</div>
<div class=" text-gray-600 text-sm">
    <p>Hẳn là bạn đã bắt gặp vô vàn những công trình kiến trúc tuyệt vời trên thế giới, nhưng khi ngắm nhìn những công trình do Matthias Jung thiết kế, bạ...</p>
</div>
  </div>
      </div>


      <div class="swiper-slide">
        <div class="min-[830px]:w-[360px] w-full">
    <div class="flex justify-center">
        <img class="imgnews" src="//file.hstatic.net/1000184473/article/blog-construction-1-450x231_511e7daf6f9849c6af7b8236841090ce_large.jpg" alt="">
    </div>
    <div class="news grid grid-rows-3 grid-flow-col gap-4">
<div class="calendar mt-4 ">
    <div class="col-span-2 h-7 bg-gray-200"><p class="text-base justify-center text-center">27</p></div>
    <div class="col-span-2 h-6 bg-yellow-300"><p class="text-xs justify-center text-center">Tháng 05</p></div>
</div>
<div class="row-span-3 h-10 mt-4 text-lg font-semibold ml-14">
    <a class="hover:text-yellow-500" href="">Thiết kế quán cafe cực đẹp</a>
</div>
</div>
<div class=" text-gray-600 text-sm">
    <p>Hẳn là bạn đã bắt gặp vô vàn những công trình kiến trúc tuyệt vời trên thế giới, nhưng khi ngắm nhìn những công trình do Matthias Jung thiết kế, bạ...</p>
</div>
  </div>
      </div>


      <div class="swiper-slide">
        <div class="min-[830px]:w-[360px] w-full">
    <div class="flex justify-center">
        <img class="imgnews" src="//file.hstatic.net/1000184473/article/blog-construction-1-450x231_511e7daf6f9849c6af7b8236841090ce_large.jpg" alt="">
    </div>
    <div class="news grid grid-rows-3 grid-flow-col gap-4">
<div class="calendar mt-4 ">
    <div class="col-span-2 h-7 bg-gray-200"><p class="text-base justify-center text-center">27</p></div>
    <div class="col-span-2 h-6 bg-yellow-300"><p class="text-xs justify-center text-center">Tháng 05</p></div>
</div>
<div class="row-span-3 h-10 mt-4 text-lg font-semibold ml-14">
    <a class="hover:text-yellow-500" href="">Thiết kế quán cafe cực đẹp</a>
</div>
</div>
<div class=" text-gray-600 text-sm">
    <p>Hẳn là bạn đã bắt gặp vô vàn những công trình kiến trúc tuyệt vời trên thế giới, nhưng khi ngắm nhìn những công trình do Matthias Jung thiết kế, bạ...</p>
</div>
  </div>
      </div>


      <div class="swiper-slide">
        <div class="min-[830px]:w-[360px] w-full">
    <div class="flex justify-center">
        <img class="imgnews" src="//file.hstatic.net/1000184473/article/blog-construction-1-450x231_511e7daf6f9849c6af7b8236841090ce_large.jpg" alt="">
    </div>
    <div class="news grid grid-rows-3 grid-flow-col gap-4">
<div class="calendar mt-4 ">
    <div class="col-span-2 h-7 bg-gray-200"><p class="text-base justify-center text-center">27</p></div>
    <div class="col-span-2 h-6 bg-yellow-300"><p class="text-xs justify-center text-center">Tháng 05</p></div>
</div>
<div class="row-span-3 h-10 mt-4 text-lg font-semibold ml-14">
    <a class="hover:text-yellow-500" href="">Thiết kế quán cafe cực đẹp</a>
</div>
</div>
<div class=" text-gray-600 text-sm">
    <p>Hẳn là bạn đã bắt gặp vô vàn những công trình kiến trúc tuyệt vời trên thế giới, nhưng khi ngắm nhìn những công trình do Matthias Jung thiết kế, bạ...</p>
</div>
  </div>
      </div>
      <!-- Thêm slide khác tùy ý -->
    </div>

    

    <!-- Thêm nút điều hướng nếu cần -->
    <div class="swiper-button-next"></div>
    <div class="swiper-button-prev"></div>
  </div>


  <div class="w-full h-[350px] bg-cyan-900">
    <div class="grid grid-rows-3 grid-flow-col gap-2 sm:pt-0 pt-20  ">
      <div class="sm:ml-[170px] sm:mt-[40px] col-span-2">
        <p class="text-lg text-white font-bold">LIÊN HỆ VỚI CHÚNG TÔI</p>
      </div>
      <div class="sm:ml-[170px] sm:mb-5 sm:mt-[40px] col-span-2">
        <p class="text-white text-[14px]">Với đội ngũ kiến trúc sư, kỹ sư, thợ lành nghề, dồi dào kinh nghiệm,
          công ty sẽ mang đến cho khách hàng sự hài lòng về chất lượng công trình đồng thời thể hiện được giá trị thương
          hiệu.</p>
      </div>
      <div class="sm:ml-[170px] sm:mt-[40px] col-span-2 sm:pt-0 pt-5">
        <button class="border-2 py-2 px-4 rounded-md text-white font-medium hover:bg-yellow-300 hover:border-yellow-300">LIÊN HỆ</button>
      </div>
      <div class="row-span-3 col-span-1 mt-9 mr-52 hidden lg:inline-block">
        <img src="https://theme.hstatic.net/1000184473/1000237392/14/contact-index.png?v=328" alt="">
      </div>
    </div>
  </div>


</template>



<script>
import Swiper from 'swiper';




export default {
  mounted() {
    new Swiper('.swiper-container', {
      // Cấu hình Swiper ở đây
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      },
    });
  },

  data() {
    return {
      currentImage: 0,
      images: [
        'https://theme.hstatic.net/1000184473/1000237392/14/slideshow_1.jpg?v=328',
        'https://theme.hstatic.net/1000184473/1000237392/14/slideshow_2.jpg?v=328'
      ]
    };
  },
  methods: {
    prevImage() {
      if (this.currentImage === 0) {
        this.currentImage = this.images.length - 1;
      } else {
        this.currentImage--;
      }
    },
    nextImage() {
      if (this.currentImage === this.images.length - 1) {
        this.currentImage = 0;
        setInterval(this.nextImage, 2000);
      } else {
        this.currentImage++;
        setInterval(this.prevImage, 2000);
      }
    },
  },
  layout: 'footer',
};
</script>
