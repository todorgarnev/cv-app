<script lang="ts">
	export let id: string | null = null;
	export let animate: boolean = false;
	export let restart: boolean = false;
	export let bg: string = "";
</script>

<section
	data-auto-animate-id={id}
	data-auto-animate={animate || null}
	data-auto-animate-restart={restart || null}
	data-background-gradient={bg || null}
>
	<slot />
</section>
