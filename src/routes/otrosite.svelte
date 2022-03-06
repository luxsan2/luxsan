<script>
	function backHome() {
		window.location.href = '/';
	}
</script>

<main class="bg-white overflow-hidden h-screen absolute z-0">
	<div class="container mx-auto h-screen pt-32 md:pt-0 px-6 z-10 flex items-center justify-between">
		<div
			class="container mx-auto px-6 flex flex-col-reverse lg:flex-row justify-between items-center relative"
		>
			<div class="w-full mb-16 md:mb-8 text-center lg:text-left">
				<h1
					class="font-light font-sans text-center lg:text-left text-5xl lg:text-8xl mt-12 md:mt-0 text-gray-700"
				>
					Sorry, this page isn&#x27;t available
				</h1>
				<button
					on:click={backHome}
					class="px-2 py-2 w-36 mt-16 font-light transition ease-in duration-200 hover:bg-yellow-400 border-2 text-lg border-gray-700 bg-yellow-300 focus:outline-none"
				>
					Go back home
				</button>
			</div>
			<div class="block w-full mx-auto md:mt-0 relative max-w-md lg:max-w-2xl">
				<img
					src="https://i.kym-cdn.com/photos/images/original/001/076/181/1f8.jpg"
					alt="kitty"
					horror
				/>
			</div>
		</div>
	</div>
</main>
