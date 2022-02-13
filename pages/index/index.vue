<template>
	<view class="index">
    <Search></Search>
    <Preference></Preference>
    <Title></Title>
    <Delicacy></Delicacy>
    <Takeout></Takeout>
	</view>
</template>

<script>
  import Search from './components/search.vue'
  import Preference from './components/preference.vue'
  import Title from './components/title.vue'
  import Delicacy from './components/delicacy.vue'
  import Takeout from './components/takeout.vue'
	export default {
    components: {
      Search,
      Preference,
      Title,
      Delicacy,
      Takeout
    },
		data() {
			return {
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
</style>
