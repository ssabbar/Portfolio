<template>
  <div class="text-white">
    <div
      class="container-md border rounded-2xl m-4 p-3 fixed top-0 left-0 w-1/3"
    >
      <div class="grid grid-cols-2 gap-4">
        <span class="p-2 text-4xl">Salma</span>
        <span class="p-2">Full Stack Engineer</span>
      </div>
      <div>
        <div class="flex justify-center my-5">
          <img
            class="rounded-2xl h-64 align-middle"
            src="~/assets/images/SalmaPhoto.jpg"
          />
        </div>
        <div class="text-center text-xl">
          <span class="block">salma.sabbar@gmail.com</span>
          <span class="block text-2xl">Base in Toronto, ON</span>
        </div>

        <div class="text-center text-gray-500 mt-8 text-s">
          <span>© 2024 Salma. All Rights Reserved</span>
        </div>

        <div class="flex flex-wrap justify-center m-10">
          <DesignedIcon name="mdi:github" />
          <DesignedIcon name="mdi:linkedin" />
        </div>
        <DownloadButton />
      </div>
    </div>
  </div>
</template>