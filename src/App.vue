<template>
  <div>
	  <Header/>
	  <!-- body -->
	  <div style="display: flex;">
	  	<!-- side menu -->
		<Aside/>
		<!-- content -->
		<router-view style="flex: 1;"/>
	  </div>
  </div>
</template>

<style>

</style>

<script type="text/javascript">
	import Header from "@/components/Header.vue"
	import Aside from "@/components/Aside.vue"
	export default{
		name: "Layout",
		components:{
			Header,
			Aside
		}
	}
</script>