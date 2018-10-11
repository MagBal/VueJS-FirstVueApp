<template>
  <footer>
      <p>{{copyright}} {{title}}</p>
  </footer>
</template>

<script>
export default {
  props: {
    title: {
      type: String
    }
  },
  data() {
    return {
      copyright: "Copyright 2018"
    };
  }
};
</script>

<style scoped>
footer {
  background: #000;
  padding: 6px;
}
p {
  color: #fff;
  text-align: center;
}
</style>
