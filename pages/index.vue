<template>
  <div class="h-100 d-flex ">
    <div class="float-left w-50 align-self-center">
      <logo />
    </div>
    <div class="float-left w-50 h-100 bg-dark text-white d-flex">
      <div class="p-3 align-self-center text-center">
        <h1>Welcome</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Velit
          tenetur est beatae ratione? Quibusdam ut nemo enim, corrupti
          accusantium officia, suscipit obcaecati ab neque asperiores itaque id,
          fugiat ratione dolor.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
