<template>
    <footer>
        <p> <i class="fa fa-copyright" aria-hidden="true"> {{copyright}} </i></p>
    </footer>
</template>
<script>
export default {
  data() {
    return {
      copyright: "2018 PP"
    };
  }
};
</script>
<style scoped>
footer {
  background: #222;
  padding: 5px;
}
p {
  color: #fff;
  text-align: center;
}
</style>


