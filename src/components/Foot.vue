<template>
    <footer>
      <p>Source code? Thanks to gitstalk!!</p>
      <a href="https://github.com/Yash71/gitAnalyz">✏️ thelittlewonder/gitstalk</a>
    </footer>
</template>

<script>
export default {
  name: "Foot",
  data() {
    return {};
  }
};
</script>

<style scoped lang="scss">
footer {
  font-size: 0.75em;
  letter-spacing: 0.01em;
  text-align: center;

  p {
    color: #aaaaaa;
    margin-bottom: 0.5em;
  }
}

@media screen and (max-width: 767px) {
  footer {
    padding: 1.5em 0;
  }
}

@media screen and (min-width: 768px) {
  footer {
    padding-top: 3em;
  }
}

</style>
