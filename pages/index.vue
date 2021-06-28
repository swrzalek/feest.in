<template>
  <div class="container-outer">
    <div class="container-inner">
      <div class="container mx-auto px-4">
        <div>
          <span class="text-white text-3xl font-semibold">Festivals</span>
          <span class="text-white text-opacity-50 text-3xl font-semibold mx-4"
            >Concerts</span
          >
          <span class="text-white text-opacity-50 text-3xl font-semibold"
            >Cultural Events</span
          >
        </div>
        <div>
          <div
            class="border border-gray-300 text-white rounded-md inline-block"
          >
            <div
              class="
                rounded-l-md
                hover:bg-white hover:text-gray-300 hover:bg-opacity-25
                border-r
                cursor-pointer
                inline-block
                px-4
                py-2
                transition
                duration-500
                ease
                select-none
                focus:outline-none focus:shadow-outline
              "
            >
              Location
            </div>
            <div
              class="
                hover:bg-white hover:text-gray-300 hover:bg-opacity-25
                cursor-pointer
                inline-block
                px-4
                py-2
                transition
                duration-500
                ease
                select-none
                focus:outline-none focus:shadow-outline
              "
            >
              Genre
            </div>
          </div>
        </div>
        <div class="grid md:grid-cols-2 gap-4 justify-items-center">
          <EventCard />
          <EventCard />
          <EventCard />
          <EventCard />
          <EventCard />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import EventCard from '../components/EventCard'
export default {
  components: {
    EventCard,
  },
}
</script>

<style lang="scss">
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  &-outer {
    margin: 0 auto;
    min-height: 100vh;
    min-width: 100%;
    background: url('../assets/bg.jpg') no-repeat center center fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }
  &-cover {
    min-height: 100vh;
    background: linear-gradient(
      126.6deg,
      rgba(255, 255, 255, 0.12) 28.69%,
      rgba(255, 255, 255, 0) 100%
    );
    backdrop-filter: blur(1px);
  }
}
</style>
