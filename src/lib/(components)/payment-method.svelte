<script lang="ts">
	import * as Card from '$lib/components/ui/card/index.js';
	import { Button } from '$lib/components/ui/button/index.js';
	import { Label } from '$lib/components/ui/label/index.js';
	import { Input } from '$lib/components/ui/input/index.js';

	const months = [
		'January',
		'February',
		'March',
		'April',
		'May',
		'June',
		'July',
		'August',
		'September',
		'October',
		'November',
		'December'
	];
</script>

<Card.Root>
	<Card.Header>
		<Card.Title>Payment Method</Card.Title>
		<Card.Description>Add a new payment method to your account.</Card.Description>
	</Card.Header>
	<Card.Content class="grid gap-6">
		<div class="grid gap-2">
			<Label for="name">Name</Label>
			<Input id="name" placeholder="First Last" />
		</div>
		<div class="grid gap-2">
			<Label for="number">Card number</Label>
			<Input id="number" placeholder="" />
		</div>
		<div class="grid grid-cols-3 gap-4">
			<div class="grid gap-2">
				<Label for="month">Expires</Label>
			</div>
			<div class="grid gap-2">
				<Label for="year">Year</Label>
			</div>
			<div class="grid gap-2">
				<Label for="cvc">CVC</Label>
				<Input id="cvc" placeholder="CVC" />
			</div>
		</div>
	</Card.Content>
	<Card.Footer>
		<Button class="w-full">Continue</Button>
	</Card.Footer>
</Card.Root>
