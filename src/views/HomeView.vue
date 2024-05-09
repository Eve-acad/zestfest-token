<template>
  <div class="gradient-dark-blue text-white">
    <div class="xl:container px-6 py-24 lg:py-40 mx-auto lg:grid grid-cols-10 gap-24">
      <div class="flex flex-col col-span-4">
        <div class="font-semibold text-lg">TONIGHT'S SPECIALS</div>
        <div class="border-b-[1px] h-3 border-gray-500" />
        <div class="mt-3 font-bold text-3xl leading-normal">
          ZEST FEST TALK SHOW
        </div>
        <div class="bg-[#141c42] rounded-lg p-6 border mb-2 mt-8">
          <div>🗓 Date: 8th May 2024</div>
          <div>📍Venue: Pump.fun</div>
          <div>⏰Time: 12.00 pm</div>
        </div>
        <div class="text-justify mt-7">
          Get ready to spice up your life at ZEST FEST! This isn't just any event; it's a celebration of enthusiasm, energy, and the zestful spirit of the iconic Zesty LeBron! Whether you're a fan of exhilarating talks, engaging discussions, or just looking to infuse a little zest into your routine, this fest is where you need to be.
        </div>
        <div class="mt-6 text-justify">
          Why Attend ZEST FEST?
        </div>
        <div class="my-6">You will learn:</div>
        <div class="my-6">
          • <strong>Inspiring Talks:</strong> Dive into a series of invigorating discussions led by Zesty LeBron himself. Explore topics that are as vibrant and dynamic as our speaker's legendary zest for life.
        </div>
        <div class="my-6">
          • <strong>Opportunities:</strong> Mix and mingle with other zest enthusiasts. Who knows? The connections you make here could lead to your next big adventure!
        </div>
        <div class="my-6">• <strong>Fun Activities:</strong> Engage in a variety of zest-themed activities designed to energize and inspire. Leave with not just insights but also an unforgettable experience.</div>
        <div class="my-6">
          Tickets: Available now! Secure your spot for an unforgettable journey into the world of zest.
        </div>


      </div>

      <div class="col-span-6 bg-white rounded-lg flex flex-col h-fit text-black">
        <div class="mx-auto my-8 text-3xl font-medium">Register now</div>
        <div class="grid grid-cols-2 gap-4 mx-auto">
          <div class="flex flex-col gap-1.5">
            <div>Business Email:*</div>
            <InputText type="text" placeholder="Business Email*" />
          </div>
          <div class="flex flex-col gap-1.5">
            <div>First Name:*</div>
            <InputText type="text" placeholder="First Name*" />
          </div>
          <div class="flex flex-col gap-1.5">
            <div>Last Name:*</div>
            <InputText type="text" placeholder="Last Name*" />
          </div>
          <div class="flex flex-col gap-1.5">
            <div>Company Name:*</div>
            <InputText type="text" placeholder="Company Name*" />
          </div>
          <div class="flex flex-col gap-1.5">
            <div>Job Title:*</div>
            <InputText type="text" placeholder="Job Title*" />
          </div>

        </div>
        <button
          class="mx-auto text-sm px-4 my-8 w-fit gradient-blue-light text-white rounded-md py-3 hover:border-[#3040E8] font-semibold border"
          href=""
        >
          SAVE MY SPOT
        </button>
      </div>
    </div>
    <div class="xl:container px-6 flex flex-col items-center gap-6 pb-24 min-w-max mx-auto">
      <div class="font-bold text-2xl">Speakers</div>
      <img
        class="rounded-full w-40 h-40"
        src="@\assets\lebron.jpg"
      />
      <div>
        <div class="text-center font-bold">Zesty Lebron</div>
        <div>Vice President, Content Marketing and Chief Baller, ZEST FEST</div>

      </div>

    </div>
    
  </div>
  <footer>
    <p>© Copyright Zesty LeBron 2024</p>
</footer>

</template>



<script setup lang="ts">
import Dropdown from 'primevue/dropdown'
import InputText from 'primevue/inputtext'
import { ref } from 'vue'
const selectedCountry = ref()
const countries = ref([
  { name: 'New York' },
  { name: 'Rome' },
  { name: 'London' },
  { name: 'Istanbul' },
  { name: 'Paris' }
])

const selectedTime = ref()

const time = ref([
  { name: 'May 14th / 11 a.m. PT ' },
  { name: 'May 15th / 11 a.m. BST ' },
  { name: 'May 16th / 1.p.m. AEST ' }
])
</script>

<style scoped>
footer {
    width: 100%;
    padding: 20px 0;
    background-color: #fff;
    text-align: center;
    box-shadow: 0 -2px 5px rgba(0,0,0,0.1);

    bottom: 0;
    left: 0;
}

footer p {
    color: #333;
    margin: 0;
    font-size: 16px;
}

</style>