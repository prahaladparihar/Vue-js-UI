<template>
    <header>
        <h1> {{title}} </h1>
    </header>
</template>

<script>
export default {
  data() {
    return {
      title: "Vue js App"
    };
  }
};
</script>

<style scoped>
header {
  background: #4267b2;
  padding: 6px;
  border-bottom: 2px solid #222;
}
h1 {
  color: #fff;
  text-align: center;
}
</style>

