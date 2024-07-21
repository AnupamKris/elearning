<template>
  <div class="flex flex-col">
    <div
      class="w-full bg-zinc-900 flex flex-col justify-center items-center hero-bg min-h-screen lg:min-h-[600px]"
    >
      <div
        class="flex justify-center items-center w-full max-w-[1200px] text-gray-100 px-10 h-[900px] pt-[200px] pb-[100px]"
      >
        <div class="flex flex-col w-[50%] justify-between h-full">
          <span class="font-bold my-10">Cyber Security Solutions for</span>
          <h1 class="text-5xl font-bold leading-[60px]">
            Organizations With Critical Infrastructure
          </h1>
          <p class="my-5 leading-7 font-semibold">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident
            eum voluptatum qui iure rem dolorem pariatur non eligendi totam et.
          </p>
          <Button class="py-5 font-bold px-10 w-[300px]">Discover More</Button>
          <div class="flex gap-5 my-10">
            <Icon class="h-4 w-4" name="uil:facebook" color="black" />
            <Icon class="h-4 w-4" name="uil:twitter" color="black" />
            <Icon class="h-4 w-4" name="uil:linkedin" color="black" />
            <Icon class="h-4 w-4" name="uil:instagram" color="black" />
          </div>
        </div>
        <div class="flex flex-col w-[50%] min-w-[50%]">
          <img
            src="https://html.designingmedia.com/redlight/assets/images/banner-img.png"
            alt=""
            class="w-full h-full object-cover"
          />
        </div>
      </div>

      <div
        class="flex justify-center items-center w-full max-w-[1000px] text-gray-100 px-10 h-[150px] pb-10"
      >
        <div>
          <button
            class="px-4 py-2 bg-zinc-950 text-sm text-orange-400 font-semibold mb-6"
          >
            VIRTUAL EVENTS
          </button>
          <p class="mb-3 text-left text-gray-400 text-sm">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia,
            quos.
          </p>

          <p class="text-gray-400">August 12, 2022</p>
        </div>
        <div class="sep mx-10"></div>
        <div>
          <button
            class="px-4 py-2 bg-zinc-950 text-sm text-orange-400 font-semibold mb-6"
          >
            VIRTUAL EVENTS
          </button>
          <p class="mb-3 text-left text-gray-400 text-sm">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia,
            quos.
          </p>

          <p class="text-gray-400">August 12, 2022</p>
        </div>
        <div class="sep mx-10"></div>
        <div>
          <button
            class="px-4 py-2 bg-zinc-950 text-sm text-orange-400 font-semibold mb-6"
          >
            VIRTUAL EVENTS
          </button>
          <p class="mb-3 text-left text-gray-400 text-sm">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia,
            quos.
          </p>

          <p class="text-gray-400">August 12, 2022</p>
        </div>
      </div>
    </div>
    <div
      class="w-full bg-zinc-900 flex flex-col justify-center items-center text-gray-100 min-h-screen lg:min-h-[600px]"
    >
      <div
        class="flex justify-center items-center w-full max-w-[1200px] text-gray-100 px-10 min-h-[900px] pt-[50px] pb-[100px] flex-col"
      >
        <h1 class="font-bold py-10">
          Trusted Over 1000+ Students in the World
        </h1>

        <h1 class="text-4xl font-bold">Why Choose Us</h1>
        <p class="text-center text-base text-gray-400 max-w-[500px] my-5">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident eum
          voluptatum qui iure rem dolorem pariatur non eligendi totam et.
        </p>

        <div class="flex gap-3 justify-center items-center px-10 mt-20">
          <div
            class="bg-[#0a0a0a] rounded-lg p-5 flex flex-col gap-3 border border-zinc-800"
            v-for="i in 3"
            :key="i"
          >
            <div
              class="h-20 w-20 bg-zinc-800 flex justify-center items-center rounded-md mt-5"
            >
              <Icon
                name="uil:facebook"
                color="black"
                class="h-16 w-16 bg-zinc-400"
              />
            </div>
            <h3 class="font-bold text-gray-300 text-2xl">Security Services</h3>
            <p class="text-sm text-gray-400 my-6">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ullam
              possimus totam incidunt dolorem soluta culpa laboriosam cupiditate
              animi eaque quae!
            </p>
            <span class="text-base mb-5">Learn More </span>
          </div>
        </div>

        <div
          class="flex justify-between items-center w-full text-gray-100 h-[550px] pb-10 min-h-[550px] my-20"
        >
          <div class="flex flex-col w-[40%] justify-between h-full">
            <img
              src="https://html.designingmedia.com/redlight/assets/images/cyber-security-left-img.png"
              alt=""
            />
          </div>
          <div class="flex flex-col w-[45%] justify-center h-full">
            <h1 class="font-bold text-4xl">
              Advanced <span class="text-red-500">Cyber Security</span> Provider
            </h1>
            <p class="text-gray-400 text-md my-5 leading-8">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia
              harum, vitae optio eligendi dolorum at beatae consectetur commodi
              necessitatibus saepe neque dolor temporibus ex quisquam! Autem
              optio consequuntur laboriosam nostrum.
            </p>
            <p class="text-gray-400 text-md leading-8">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum,
              accusamus?
            </p>

            <Button
              class="py-3 font-bold px-3 w-[200px] mt-5 border border-zinc-400 bg-transparent"
            >
              Discover More</Button
            >
          </div>
        </div>

        <div
          class="flex justify-center items-center w-full max-w-[1000px] text-gray-100 px-10 h-[150px] pb-10"
        >
          <h1 class="font-bold text-3xl">Our Courses</h1>
          <div class="flex flex-col gap-5 mt-10 flex-wrap">
            <div>
              <img
                src="https://picsum.photos/id/10/400/200"
                alt=""
                class="w-full h-full object-cover"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.hero-bg {
  background: linear-gradient(135deg, #521212, #18181b, #18181b);
}

.sep {
  border-right: 1px dashed #fff;
  height: 100%;
  width: 2px;
  min-width: 2px;
}
</style>
