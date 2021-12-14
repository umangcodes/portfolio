<template>
  <div class="h-auto">
    <Intro />
    <!-- cover image/ intro -->
    <div class="grid grid-cols-2 h-50 w-full">
      <!-- <img
        class="object-cover h-50 w-full"
        src="@/assets/cover-image.jpg"
        alt=""
      /> -->
      <div class="cols-start-1 text-3xl font-thin h-50">
        Front end Web developer Lorem ipsum dolor sit amet consectetur
        adipisicing elit. Aliquam sequi perferendis quidem deleniti, doloremque
        ex temporibus natus nobis illum ipsa iste officiis, qui vero ratione
        accusamus. Neque rerum labore dicta?
      </div>
    </div>
    <!-- interests -->
    <!-- skills -->
    <Skills />
    <!-- projects -->
    <!-- blog -->
  </div>
</template>

<script>
// @ is an alias to /src
import Intro from "../components/home/Intro.vue";
import Skills from "../components/home/Skills.vue";
export default {
  name: "Home",
  components: {
    Intro,
    Skills,
  },
};
</script>
