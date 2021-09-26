<!-- @format -->

<template>
	<div id="app">
		<div class="container mt-5">
			<div class="row justify-content-mdcenter">
				<div class="col-md-8 bg-white p-3">
					{{ name }}'s To-do List
					<hr />
					<div class="row d-flex jstify-content-between px-3 py-2">
						<div>{{ task }}</div>
						<div>
							<input type="checkbox" class="form-check-input" />{{ comp }}
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "App",
	data() {
		return {
			name: "Ahmed",
			list: [
				{ task: "make a phone call", comp: false },
				{ task: "pick up kids", comp: false },
				{ task: "coffee", comp: false },
				{ task: "study", comp: false },
			],
		};
	},
};
</script>

<style>
body {
	background-color: #f8f8f8 !important;
}
</style>
