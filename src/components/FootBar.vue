<template>
  <div class="grid-item-copyright mt-auto">
  <span>
    Copyright &copy; IT-Together {{getCurrentYear()}}</span>
  </div>
</template>

<script>
export default {
  name: "FootBar",
  methods: {
    getCurrentYear: function() {
			return new Date().getFullYear()
		}
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.grid-item-copyright {
  background: #315eff;
  color:white;
  position: relative;
  padding: 1em 0;
  text-align: center;
}
</style>
