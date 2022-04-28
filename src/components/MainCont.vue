<script>
export default {
  props: {
    nomes: {
      type: Array,
    },
    titulo: {
      type: String,
      default: "Titulo Aqui!",
    },
  },
  data() {
    return {};
  },
};
</script>
<template>
  <aside class="block">
    <h1>{{ titulo }}</h1>
    <ul>
      <p v-for="nome of nomes" :key="nome">
        {{ nome }}
      </p>
    </ul>
  </aside>
</template>
