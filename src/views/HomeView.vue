<template>
  <div class="gradient-dark-blue text-white">
    <div class="xl:container px-6 py-24 lg:py-40 mx-auto lg:grid grid-cols-10 gap-24">
      <div class="flex flex-col col-span-5 lg:col-span-4">
        <div class="text-lg zest">ZEST FEST 2024</div>
        <div class="border-b-[1px] h-3 border-gray-500" />
        <div class="mt-3 font-bold text-3xl leading-normal">The most TALKED ABOUT zesty nigga linkup of the year!</div>
        <div class="bg-[#c410c4] rounded-lg p-6 border mb-2 mt-8">
          <div>Date: 8th May 2024</div>
          <div>Venue: pump.fun</div>
          <div>Time: Right now!</div>
        </div>
        <div class="text-justify mt-7">
          ZEST FEST 2024 is getting gayer than ever! Get ready to oil up, twerk and edge at ZEST FEST! This isn't just any event; it's a
          gathering of the zestiest niggas around! You've never seen shit as zesty as this!
          Whether you're a fan of exhilarating twerk-offs, oiled-up naked massages with multiple black men, or just looking
          to infuse a little zest into your life, ZESTFEST 2024 is where you need to be.
        </div>
        <div class="mt-6 text-justify" style="font-size: 30px" :class="show? '':'opacity-70'"><strong>Why should you pull your zesty ass up to the ZEST FEST?</strong></div>
        <div v-if="show">
          <div class="my-6">
            <strong>OILED TWERK EDUCATION:</strong> Dive into a series of invigorating classes led
            by BBL Drizzy himself. Once you learn what he has to teach, you'll never shake your gyatt the same again!
          </div>
          <div class="my-6">
            <strong>EDGING SEMINAR:</strong> Led by Ambatukam Ambassing, and attended by the leaders of the edging industry, this is a fucking game changer. Trust me bro. I went once and now I can't fucking stop edging.
          </div>
          <div class="my-6">
            <strong>DIRTY TALK MASTERCLASS:</strong> Is that dick good? YES KING! How good is that dick? *intense moaning* HOW GOOD IS THAT DICK BITCH? Amazing...
          </div>
        </div>
        <div class="mt-8 flex gap-3 items-center cursor-pointer mb-3" @click="show = !show">
          <div>Show {{ show?"Less":"More"  }}</div>
          <CircleArrowDown  v-if="!show"/>
          <CircleArrowUp v-else />
        </div>
      </div>

      <div class="col-span-5 lg:col-span-6 bg-white rounded-lg flex flex-col h-fit text-black">
        <div class="mx-auto my-8 text-3xl font-medium">BUY SOME $ZEST NIGGA</div>
        <div class="gap-4 mx-auto">
          <div class="flex flex-col gap-1.5">
            <div>ZEST FEST 2023 WAS FUCKING CRAZY! 😭 YOU DON'T WANT TO MISS THIS 💯</div><br>
            <video width="200" controls>
  <source src="../assets/zest.mp4" type="video/mp4">
</video>
        </div></div>

        <button
          class="mx-auto text-sm px-4 my-8 w-fit gradient-blue-light text-white rounded-md py-3 hover:border-[#3040E8] font-semibold border"
        >
          <a href="https://www.pump.fun/board">FUCK YEAH I WANNA BUY SOME $ZEST</a>
        </button>
      </div>
    </div>
          <div class="font-bold text-2xl xl:container px-6 flex flex-col items-center gap-6 pb-24 min-w-max mx-auto" style="font-size: 50px">Hella niggas are coming btw</div>

    <div class="xl:container px-6 gap-6 items-center min-w-max grid grid-cols-4 mx-auto">
      <img class="rounded-full w-40 h-40" src="@/assets/drake.jpg/" />
      <div>
        <div class="text-left font-bold">BBL Drizzy</div>
        <div>Winner of "Zestiest Nigga" Award 2013-2023.</div>
      </div>
      <img class="rounded-full w-40 h-40" src="@/assets/lebron.jpg/" />
      <div>
        <div class="text-left font-bold">LeBonBon</div>
        <div>Drop that shit like it's hot daddy 😍</div>
      </div>
            <img class="rounded-full w-40 h-40" src="@/assets/dreamybull.jpg/" />
      <div>
        <div class="text-left font-bold">Ambatukam "DreamyBull" Ambassing</div>
        <div>Ambatabusss, Ambatukam, Ambassinggg 😩</div>
      </div>
                  <img class="rounded-full w-40 h-40" src="@/assets/lilnas.jpg/" />
      <div>
        <div class="text-left font-bold">Little Nas X</div>
        <div>Yeah this nigga gay asf.</div>
      </div>
                        <img class="rounded-full w-40 h-40" src="@/assets/dog.jpg/" />
      <div>
        <div class="text-left font-bold">This dog is super fucking gay 😭</div>
        <div>Seriously who the fuck trained this nigga.</div>
      </div>
                              <img class="rounded-full w-40 h-40" src="@/assets/drake2.jpg/" />
      <div>
        <div class="text-left font-bold">BBL Drizzy again</div>
        <div>Someone stop this nigga 😭😭</div>
      </div>

    </div>
    <br>
  </div>
  
  <footer>
    <p>© Copyright Zesty Ass Niggas 2024</p>
  </footer>
</template>

<script setup lang="ts">
import InputText from 'primevue/inputtext'
import { ref } from 'vue'
import { CircleArrowDown,CircleArrowUp } from 'lucide-vue-next';

const show = ref(false)
</script>

<style scoped>
footer {
  width: 100%;
  padding: 20px 0;
  background-color: #fff;
  text-align: center;
  box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.1);

  bottom: 0;
  left: 0;
}

footer p {
  color: #333;
  margin: 0;
  font-size: 16px;
}

.x{
  -webkit-text-fill-color: transparent;
}
</style>
