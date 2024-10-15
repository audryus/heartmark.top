<script lang="ts">
	import * as Card from '$lib/components/ui/card/index.js';
	import { Label } from '$lib/components/ui/label/index.js';
</script>

<Card.Root>
	<Card.Header>
		<Card.Title>Cookie Settings</Card.Title>
		<Card.Description>Manage your cookie settings here.</Card.Description>
	</Card.Header>
	<Card.Content class="grid gap-6">
		<div class="flex items-center justify-between space-x-2">
			<Label for="necessary" class="flex flex-col space-y-1">
				<span>Strictly Necessary</span>
				<span class="text-muted-foreground text-xs font-normal leading-snug">
					These cookies are essential in order to use the website and use its features.
				</span>
			</Label>
		</div>
		<div class="flex items-center justify-between space-x-2">
			<Label for="functional" class="flex flex-col space-y-1">
				<span>Functional Cookies</span>
				<span class="text-muted-foreground text-xs font-normal leading-snug">
					These cookies allow the website to provide personalized functionality.
				</span>
			</Label>
		</div>
		<div class="flex items-center justify-between space-x-2">
			<Label for="performance" class="flex flex-col space-y-1">
				<span>Performance Cookies</span>
				<span class="text-muted-foreground text-xs font-normal leading-snug">
					These cookies help to improve the performance of the website.
				</span>
			</Label>
		</div>
	</Card.Content>
	<Card.Footer></Card.Footer>
</Card.Root>
