<script>
	export let danger = false
</script>

<!-- https://daisyui.com/components/button -->
<button on:click class:danger class='btn btn-primary { $$props.class }'>
	<slot />
</button>

<style>
.danger { @apply
	btn-error;
}
</style>
