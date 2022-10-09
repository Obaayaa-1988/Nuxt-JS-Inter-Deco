<template>
  <div>
    <Navlist />
    <!--------section 1-->
    <div>
      <div class="flex flex-col justify-center items-center h-full mt-60">
        <h1 class="text-3xl font-extrabold mb-8 font-serif">
          MAKE BEAUTIFUL MEMORIES HERE
        </h1>
        <p class="">
          Our first async presentation went pretty well we highlighted the
          problem statement which is to
        </p>
        <button
          class="mb-8 bg-stone-600 py-3 px-8 text-white mt-12 font-extrabold"
        >
          View Store
        </button>
      </div>
    </div>

    <!---------------section 2-->

    <div class="w-4/5 m-auto">
      <div class="flex gap-5">
        <div>
          <div class="w-96 h-full">
            <img
              src="images/image19.jpg "
              class="w-full h-full pt-20 object-cover"
            />
          </div>
        </div>

        <div>
          <div class="w-96 h-full bg-white">
            <img src="images/image1.jpg " class="w-full h-full object-cover" />
          </div>
        </div>

        <div class="w-96 h-full bg-white">
          <img
            src="images/image17.jpg "
            class="w-full h-full pt-20 object-cover"
          />
        </div>
      </div>
    </div>

    <!-------------section 3---------->
    <div class="w-4/5 m-auto">
      <div class="flex justify-around">
        <div>
          <h1 class="text-xl font-semibold my-8 font-mono text-center">
            INTERIOR
            <hr class="border border-orange-600 font-extrabold" />
          </h1>
        </div>
        <div>
          <h1 class="text-xl my-8 font-mono font-semibold">
            DECORATION
            <hr class="border border-orange-600 font-extrabold" />
          </h1>
        </div>
        <div>
          <h1 class="text-xl font-semibold my-8 font-mono">
            ARCHITECTURE
            <hr class="border border-orange-600 font-extrabold" />
          </h1>
        </div>
      </div>

      <div class="flex justify-between">
        <div><h1 class="text-9xl text-gray-200 font-bold my-8">01</h1></div>
        <div><h1 class="text-9xl text-gray-200 font-bold my-8">02</h1></div>
        <div><h1 class="text-9xl text-gray-200 font-bold my-8">03</h1></div>
      </div>
    </div>

    <div class="w-full h-full bg-stone-600 flex justify-evenly mt-16">
      <div class="px-16">
        <img
          src="images/image1.jpg" class="w-full h-full rounded-2xl object-cover py-20 "
        />
      </div>
      <div class="flex flex-col justify-center items-center px-16">
        <!-- <h1 class="text-white text-7xl font-extrabold font-serif">INTERIOR</h1> -->
        <h1 class="text-white text-7xl font-extrabold font-serif">DESIGNS</h1>
        <p class="text-white pt-8">Engage More With Reality</p>
        <button
          class="
            mb-8
            bg-orange-600
            py-3
            px-8
            text-white
            mt-12
            font-extrabold font-mono
          "
        >
          Explore
        </button>
        <h2 class="mb-8 text-white text-l">Follow US</h2>
      </div>
    </div>

    <!-------------section 4-->

    <div class="bg-gray-100 w-full h-full m-auto">
      <div>
        <h1 class="text-center font-extrabold text-4xl py-20">OUR SERVICES</h1>
      </div>

      <div class="flex justify-between w-4/5 m-auto">
        <div>
          <h1 class=" font-extrabold text-2xl font-mono "  >FUNITURES</h1>
          <p class="w-4/5">
            Clear explanations of core points, detailed concept, identification
            of sources and good examples.
          </p>
        </div>

        <div>
          <h1 class=" font-extrabold text-2xl font-mono ">FUNITURES</h1>
          <p class="w-4/5">
            Clear explanations of core points, detailed concept, identification
            of sources and good examples.
          </p>
        </div>
        <div>
          <h1 class=" font-extrabold text-2xl font-mono ">FUNITURES</h1>
          <p class="w-4/5">
            Clear explanations of core points, detailed concept, identification
            of sources and good examples.
          </p>
        </div>
      </div>


      <div> 
        <div><img src="images/image3.jpg " class="w-full h-full pt-20 object-cover"/> </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
</style>

