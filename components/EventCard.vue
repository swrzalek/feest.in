<template>
  <div class="py-4 px-8 rounded-2xl md:my-10 my-5 card">
    <div>
      <h2 class="text-white text-3xl font-semibold">Design Tools</h2>
      <p class="mt-2 text-white">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae dolores
        deserunt ea doloremque natus error, rerum quas odio quaerat nam ex
        commodi hic, suscipit in a veritatis pariatur minus consequuntur!
      </p>
    </div>
    <div class="flex justify-end mt-4">
      <button
        type="button"
        class="
          border border-gray-300
          text-white
          rounded-md
          px-4
          py-2
          m-2
          transition
          duration-500
          ease
          select-none
          hover:bg-gray-200
          focus:outline-none focus:shadow-outline
        "
      >
        Show more
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'EventCard',
}
</script>

<style scoped>
.card {
  background: rgba(64, 64, 64, 0.2);
  box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
  backdrop-filter: blur(3px);
  -webkit-backdrop-filter: blur(6px);
  border: 1px solid rgba(255, 255, 255, 0.18);
}
</style>
