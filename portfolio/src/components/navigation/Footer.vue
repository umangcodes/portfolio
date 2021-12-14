<template>
  <div
    id="Footer"
    class="relative bottom-0 border-t h-auto w-screen"
    style="
      background-image: url('https://wallpaperaccess.com/full/1947484.jpg');
    "
  >
    <div class="flex flex-col items-center justify-center mt-5 mx-5 h-40">
      <div class="flex items-center justify-center">
        <a href="#" class="px-5">
          <linkedin-icon />
        </a>
        |
        <a href="#" class="px-5">
          <github-icon />
        </a>
      </div>
      <span class="text-xl text-white font-medium pt-5">email@domain.com</span>
    </div>
    <div class="flex items-center justify-center my-2">
      <span class="text-lg font-extralight font-sans italic"
        >A project by Umang Agrawal</span
      >
    </div>
  </div>
</template>

<script>
import LinkedinIcon from "../icons/Linkedin-icon.vue";
import GithubIcon from "../icons/Github-icon.vue";
export default {
  components: {
    LinkedinIcon,
    GithubIcon,
  },
};
</script>

<style lang="scss" scoped></style>
