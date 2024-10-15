<script lang="ts">
	import { Button } from '$lib/components/ui/button/index.js';
	import * as Card from '$lib/components/ui/card/index.js';
</script>

<Card.Root>
	<Card.Header>
		<Card.Title>Team Members</Card.Title>
		<Card.Description>Invite your team members to collaborate</Card.Description>
	</Card.Header>
	<Card.Content class="grid gap-6">
		<div class="flex items-center justify-between space-x-4">
			<div class="flex items-center space-x-4">
				<div>
					<p class="text-sm font-medium leading-none">Sofia Davis</p>
					<p class="text-muted-foreground text-sm">m@example.com</p>
				</div>
			</div>
		</div>
		<div class="flex items-center justify-between space-x-4">
			<div class="flex items-center space-x-4">
				<div>
					<p class="text-sm font-medium leading-none">Jackson Lee</p>
					<p class="text-muted-foreground text-sm">p@example.com</p>
				</div>
			</div>
		</div>
	</Card.Content>
</Card.Root>
