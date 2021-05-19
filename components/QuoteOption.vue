<template>
	<div class="cuote-option">
		<div id="a">
		<div id="b">Descripcion: {{value.descripcion}}</div>
		<div id="b">Plazo de entrega: {{value.PlazoEntrega}}</div>
		<div id="b">Total: {{value.Total ? value.Total : "Gratis"}}</div>
	</div>
	</div>
</template>

<script>
	
export default {
	
	props: {
		value: {
			type: Object,
			required: true
		}
	}
	
};

</script>

<style lang="scss" scoped>
#a{
	margin: 0;
	padding: auto;
	background: #007bff; 
}
#b{
	border-radius: 1px;
	margin: 3px;
	font-color: white;
	border-radius: 20px
}
</style>
