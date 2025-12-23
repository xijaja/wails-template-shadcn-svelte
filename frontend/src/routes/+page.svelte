<script lang="ts">
	import DarkModel from '$lib/components/blocks/theme-toggle.svelte';
	import LoginForm from '$lib/components/login-form.svelte';
</script>

<div class="flex h-screen w-full items-center justify-center px-4">
	<div class="flex flex-col items-center gap-4">
		<LoginForm />
		<DarkModel />
	</div>
</div>
