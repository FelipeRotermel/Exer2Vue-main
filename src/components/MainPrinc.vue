<script>
import MainCont from "@/components/MainCont.vue";
export default {
  components: { MainCont },
};
</script>
<template>
  <main id="content">
    <MainCont titulo="Reyna" :nomes="['teste de texto .com .br']" />
    <MainCont titulo="Segundo Personagem" :nomes="['']" />
    <MainCont />
    <MainCont />
    <MainCont />
    <MainCont />
  </main>
</template>
