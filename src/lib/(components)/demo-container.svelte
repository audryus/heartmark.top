<script lang="ts">
	import { cn } from '$lib/utils.js';

	let className = undefined;
	export { className };
</script>

<div class={cn('flex items-center justify-center [&>div]:w-full', className)} {...$$restProps}>
	<slot />
</div>
