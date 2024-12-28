<script>
	import Tab1 from './components/Tab1.svelte'
	import Tab2 from './components/Tab2.svelte'
	import Tab3 from './components/Tab3.svelte'
	import Tabs from './components/Tabs.svelte'
	let items = [
		{ label: 'Content', value: 1, component: Tab1 },
		{ label: 'Interactions', value: 2, component: Tab2 },
		{ label: 'Tab 3', value: 3, component: Tab3 }
	]
</script>

<main class="main" data-theme="light">
	<Tabs {items} />
</main>
