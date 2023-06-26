<template>
  <section id="urunler" class="flex w-full flex-col items-center justify-center gap-4 pt-12">
    <h2 class="flex justify-center gap-2">
      Basic Card
      <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24">
        <path
          fill="currentColor"
          d="m12 20l-8-8l1.4-1.425l5.6 5.6V4h2v12.175l5.6-5.6L20 12l-8 8Z"
        />
      </svg>
    </h2>
    <div
      class="my-4 min-h-[32rem] w-80 max-w-sm overflow-hidden rounded-lg bg-white shadow-lg sm:w-auto"
    >
      <div>
        <img
          src="https://images.unsplash.com/photo-1494976388531-d1058494cdd8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80"
          class="h-56 w-full object-cover object-center"
          alt="car image"
        />
      </div>
      <div class="px-6 py-4">
        <h2 class="text-xl font-bold text-gray-800">Amazing Car</h2>
        <p class="line-clamp-4 py-2 text-lg text-gray-700/80">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Enim exercitationem harum ad
          tenetur ea illo quam sint excepturi error id consequatur mollitia obcaecati quia
          perferendis nobis fugiat aut, eum quibusdam!
        </p>
        <div class="mt-4 flex w-full items-center justify-end text-gray-700">
          <button
            class="cursor-pointer rounded-lg bg-gray-800 px-4 py-4 text-sm text-white/90 shadow-md shadow-blue-400 transition-all duration-200 hover:text-white hover:shadow-md hover:shadow-blue-900"
          >
            Detay gör
          </button>
        </div>
      </div>
    </div>
  </section>
</template>
