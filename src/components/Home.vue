<template>
  <div class="home">
    <h3>{{ msg2 }}</h3>
  </div>
</template>
<script>
export default {
  name: 'Home',
  props: {
    msg2: String,
  },
};
</script>
