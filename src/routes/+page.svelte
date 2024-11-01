<script>
	import BoxRow from '$lib/box-row.svelte';
	import TextBox from '$lib/text-box.svelte';
</script>

<div class="h-screen w-screen font-sans">
	<nav class="w-full mt-4">
		<div class="mx-auto flex flex-wrap items-center container">
			<img src="/logo.webp" class="me-2 max-h-16" alt="tocq.io logo" />
			<span class="self-center whitespace-nowrap text-xl font-semibold text-zinc-800"
				>Data for the people</span
			>
			<div class="ml-auto">
				<a href="https://myspace.tocq.io" target="_blank"
					><h2 class="text-md font-semibold hover:underline text-fuchsia-900">Try the playground</h2></a
				>
			</div>
		</div>
	</nav>
	<div class="mx-auto bg-zinc-50 container p-4 my-8 rounded-xl">
		<span class="self-center text-5xl font-black text-center text-zinc-600"
			>The low-code collaboration platform for AI supported data workflows</span
		>
	</div>
	<BoxRow>
		<TextBox title="Real-time collaboration"
			>User can collaborate on a canvas in realtime. Prompts can be used to generate SQL and other
			code in the execution graph. Results can be reviewed and published as components or dashboards
			or scheduled for the backend.</TextBox
		>
		<TextBox title="Hyper modularised"
			>A hyper modularised engine empowers users to not only use platform features seamlessly but
			define and run their own extensions as data processing plug-ins or functions. Users can share
			and re-use plug-ins and functions.</TextBox
		>
	</BoxRow>
	<BoxRow>
		<TextBox title="AI supported"
			>AI models support the user on their journey through the data. It generates SQL, source code
			and charts, always transparently and reproducible so users can change the outcome and
			understand the AI’s input.</TextBox
		>
		<TextBox title="Fluid scalability"
			>Running data processing in a browser or on a laptop and deploying or publishing seamlessly to
			tocq.io. Paying for what is needed in processing time. Bridging existing data storage,
			services and inference stacks.</TextBox
		>
	</BoxRow>
	<BoxRow>
		<TextBox title="(Open) catalogue"
			>The data catalogue uses natural language understanding to index its data and support users. A
			generous Open Data catalogue is used as test bed and base layers for users to build on top and
			possibly share data.</TextBox
		>
		<TextBox title="Data publishing"
			>Once ready, dashboards can be created from the execution model. A drag and dop UI supports
			quick creation of dashboards or widgets with text, media, and data. They can be reviewed and
			published on tocq.io.</TextBox
		>
	</BoxRow>
	<BoxRow>
		<TextBox title="Governance included"
			>A smart data governance stack with signing keys for all individuals and non-human
			participants based on hierarchical key management guarantees traceability and reproducibility
			across all stakeholders.</TextBox
		>
		<TextBox title="Secure processing"
			>End-to-end encryption and smart policy management allow organisations and its users to
			process critical and private data. For the most demanding customers zero knowledge processing
			could be a possible direction.</TextBox
		>
	</BoxRow>
	<footer class="pb-3">
		<hr class="border-zinc-100 mx-12" />
		<div class="mx-auto flex flex-row items-center container my-4">
			<span class="text-sm text-fuchsia-700">© 2024 <a href="https://tocq.io/" class="hover:underline">tocq.io</a>. All Rights Reserved.
			</span>
			<div class="ml-auto">
				<a href="https://github.com/tocq-io" target="_blank" class="text-fuchsia-700 hover:text-fuchsia-900">
					<svg class="w-4 h-4" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
						  <path fill-rule="evenodd" d="M10 .333A9.911 9.911 0 0 0 6.866 19.65c.5.092.678-.215.678-.477 0-.237-.01-1.017-.014-1.845-2.757.6-3.338-1.169-3.338-1.169a2.627 2.627 0 0 0-1.1-1.451c-.9-.615.07-.6.07-.6a2.084 2.084 0 0 1 1.518 1.021 2.11 2.11 0 0 0 2.884.823c.044-.503.268-.973.63-1.325-2.2-.25-4.516-1.1-4.516-4.9A3.832 3.832 0 0 1 4.7 7.068a3.56 3.56 0 0 1 .095-2.623s.832-.266 2.726 1.016a9.409 9.409 0 0 1 4.962 0c1.89-1.282 2.717-1.016 2.717-1.016.366.83.402 1.768.1 2.623a3.827 3.827 0 0 1 1.02 2.659c0 3.807-2.319 4.644-4.525 4.889a2.366 2.366 0 0 1 .673 1.834c0 1.326-.012 2.394-.012 2.72 0 .263.18.572.681.475A9.911 9.911 0 0 0 10 .333Z" clip-rule="evenodd"/>
					</svg>
					<span class="sr-only">GitHub account</span>
				</a>
			</div>
		</div>
	</footer>
</div>
