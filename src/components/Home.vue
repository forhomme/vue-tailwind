<template>
  <div class="w-full bg-gradient-to-br to-blue-100">
    <div class="flex flex-col md:flex-row px-24 py-56 max-w-screen-xl mx-auto">
      <div class="flex flex-col max-w-full md:w-1/2 mb-24 md:mb-0">
        <span class="flex items-center px-1 text-6xl text-black">
          <h1 class="font-bold">Marketing mudah.</h1>
        </span>
        <p class="pt-8 font-normal text-gray-600 leading-relaxed text-xl">
          Semua Tools yang kamu butuhkan untuk tingkatkan jangkauan media sosialmu
        </p>
        <div class="flex pt-8 space-x-6">
          <button class="flex py-2 px-4 justify-center items-center border-2 rounded-md border-blue-600 text-white
          bg-blue-600 hover:bg-white hover:text-blue-600 font-medium hover:shadow-lg transition-shadow duration-300">Mulai pemakaian</button>
          <button class="flex py-2 px-4 justify-center items-center border-2 rounded-md border-blue-600 text-blue-600
          bg-white hover:bg-blue-600 hover:text-white font-medium hover:shadow-lg transition-shadow duration-300">Eksplore semua tool</button>
        </div>
      </div>
      <div class="flex w-full md:w-1/2">
        <img class="md:max-w-lg w-auto drop-shadow-2xl self-end" src="../assets/img/social_media.png" alt="">
      </div>
    </div>
    <div class="flex flex-col px-24 py-18 max-w-full mx-auto items-center justify-center">
      <span class="flex items-center text-4xl text-black">
        <h1 class="font-bold">Aplikasi Terpopuler</h1>
      </span>
      <p class="pt-8 font-normal text-gray-600 leading-relaxed text-xl">Lebih dari 20 tools untuk marketing media sosialmu. Coba sekarang!</p>
      <div class="grid grid-cols-1 max-w-4xl items-center justify-center py-8 px-4 space-x-6 space-y-6 lg:grid-cols-3">
        <div class="flex flex-1 border border-2 bg-gray-100 box-content w-56 h-24 hover:bg-gray-200 ml-6 mt-6 px-4 py-4">
          <div class="flex">
            <div class="w-1/4">
              <img class="h-8 w-8" src="../assets/img/seo.jpg">
            </div>
            <div class="w-3/4 flex flex-col">
              <h3 class="font-medium leading-relaxed">SEO Keyword Tool</h3>
              <p class="font-sans text-sm">Cari kata yang memiliki traffic terbanyak</p>
            </div>
          </div>
        </div>
        <div class="flex flex-1 border border-2 bg-gray-100 box-content w-56 h-24 hover:bg-gray-200 px-4 py-4">
          <div class="flex flex-col">
            <h3 class="font-medium leading-relaxed">Youtube Keyword Tool</h3>
            <p class="font-sans text-sm">Cari kata yang sering dicari di Youtube</p>
          </div>
        </div>
        <div class="flex flex-1 border border-2 bg-gray-100 box-content w-56 h-24 hover:bg-gray-200 px-4 py-4">
          <div class="flex flex-col">
            <h3 class="font-medium leading-relaxed">IG Hashtags Explorer</h3>
            <p class="font-sans text-sm">Cari Hashtags paling hot di Instagram</p>
          </div>
        </div>
        <div class="flex flex-1 border border-2 bg-gray-100 box-content w-56 h-28 hover:bg-gray-200 px-4 py-4">
          <div class="flex flex-col">
            <h3 class="font-medium leading-relaxed">Tiktok Explorer</h3>
            <p class="font-sans text-sm">Cari Video dan Challenge paling hot di Tiktok</p>
          </div>
        </div>
        <div class="flex flex-1 border border-2 bg-gray-100 box-content w-56 h-28 hover:bg-gray-200 px-4 py-4">
          <div class="flex flex-col">
            <h3 class="font-medium leading-relaxed">Keyword Suggestion</h3>
            <p class="font-sans text-sm">Cari kata terbaik untuk blog</p>
          </div>
        </div>
        <div class="flex flex-1 border border-2 bg-gray-100 box-content w-56 h-28 hover:bg-gray-200 px-4 py-4">
          <div class="flex flex-col">
            <h3 class="font-medium leading-relaxed">Social Media Data</h3>
            <p class="font-sans text-sm">Cari seluruh Data di Social Media</p>
          </div>
        </div>
      </div>
      <div class="flex items-center mx-auto justify-center py-8 my-10">
        <button class="py-2 px-4 text-white rounded-md bg-blue-600 hover:bg-blue-800 font-medium">Lihat Semua Tools</button>
      </div>
      <div class="flex flex-col px-24 py-18 max-w-full mx-auto items-center justify-center mb-10">
        <span class="flex items-center text-4xl text-black">
        <h1 class="font-bold">Buat Kegiatan Marketing Kamu Menjadi Mudah</h1>
      </span>
        <p class="pt-8 font-normal text-gray-600 leading-relaxed text-xl">FBig adalah website terpercaya untuk kebutuhan marketingmu.</p>
        <p class="pb-8 font-normal text-gray-600 leading-relaxed text-xl">Kami memiliki semua peralatan yang kamu butuhkan untuk mengembangkan usahamu</p>
      </div>
      <div class="flex flex-1 border border-2 bg-gray-100 box-content w-3/4 h-60 hover:bg-gray-200 px-4 py-4 mb-20">
        <div class="flex flex-col w-2/4 px-8 justify-items-center">
          <span class="flex items-center text-4xl text-black my-10">
            <h1 class="font-bold">Coba FBig Gratis</h1>
          </span>
          <p class="font-sans text-sm">Cari Hashtags paling hot di Instagram</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
}
</script>

<style scoped>

</style>