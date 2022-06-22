<template>
  <div class="app-wrapper">
    <Drill />
  </div>
</template>

<script>
import Drill from "@/components/Drill";
export default {
  name: "App",
  components: { Drill },
  data() {
    return {};
  },
  methods: {},
  mounted() {},
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  flex-shrink: 0;
}
html {
  height: 100%;
}

body {
  height: 100%;
  position: relative;
  margin: 0;
}

#app {
  display: flex;
  justify-content: center;
}

input,
textarea,
select {
  font-size: 16px;
}

p {
  margin: 0;
}

a {
  text-decoration: none;
}

.app-wrapper {
  width: 100%;
  height: 100%;
}
</style>
