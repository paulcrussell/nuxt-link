<script>
export default {
  data() {
    return { msg: "" };
  }
};
</script>
<template>
  <section>
    <section>
      <p>Current component: B</p>
      <span>Message is: {{ msg }}</span>
      <input v-model="msg" />
    </section>
    <nuxt-link to="/Product">Product</nuxt-link>
  </section>
</template>
