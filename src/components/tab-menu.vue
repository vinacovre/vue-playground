<template>
	<ul>
		<tab-menu-item v-for="(item, index) in items" :key="index" :item="item"></tab-menu-item>
	</ul>
</template>

<script>
import TabMenuItem from './tab-menu-item';

export default {
	name: 'tab-menu',
	props: {
		items: {
			type: Array,
			default: () => [],
		},
  },
  components: {
    TabMenuItem,
  },
};
</script>

<style scoped></style>
