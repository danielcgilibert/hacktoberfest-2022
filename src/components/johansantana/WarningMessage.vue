<script setup>
const props = defineProps({
	message: {
		type: String,
		required: true
	}
})

const { message } = props
</script>

<template>
	<div
		class="absolute bg-gray-700 p-3 px-5 left-1/2 -translate-x-1/2 -top-20 rounded-xl text-white whitespace-nowrap"
	>
		{{ message }}
	</div>
</template>
