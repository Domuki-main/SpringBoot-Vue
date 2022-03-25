<template>
  <div>
	  <Header/>
  </div>
  <router-view/>
</template>

<style>

</style>

<script type="text/javascript">
	import Header from "@/components/Header"
	export default{
		name: "Layout",
		components:{
			Header
		}
	}
</script>