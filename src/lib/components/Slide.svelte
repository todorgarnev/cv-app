<script lang="ts">
	export let id: string | null = null;
	export let animate: boolean = false;
	export let restart: boolean = false;
	export let bgGradient: string = "";
	export let bgColor: string = "";
</script>

<section
	data-auto-animate-id={id}
	data-auto-animate={animate || null}
	data-auto-animate-restart={restart || null}
	data-background-gradient={bgGradient || null}
	data-background-color={bgColor || null}
>
	<slot />
</section>
