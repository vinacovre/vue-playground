<template>
  <li class="tab-menu-item" v-for="(item, index) in items" :key="`item_${index}`">
    {{ item }}
  </li>
</template>

<script>
export default {
	name: 'tab-menu-item',
	props: {},
	data() {
    return {
      items: ['All', 'Active', 'Done'],
    }
	},
};
</script>

<style scoped>
.tab-menu-item {
	display: inline;
	color: #394053;
}
</style>
