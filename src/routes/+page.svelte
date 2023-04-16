<svelte:head>
	<title>1jupp Racing Team</title>
</svelte:head>

<header class="grid grid-cols-1 sm:grid-cols-2 p-0 m-0">
	<div>
		<div class="relative isolate px-6 pt-14 lg:px-8">
			<div class="mx-auto max-w-2xl py-32 sm:py-48 lg:py-56">
				<div class="text-left">
					<h1
						class="text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl"
					>
						1jupp Racing Team
					</h1>
					<p class="mt-6 text-lg leading-8 text-gray-700">
						Team of VHK students, on a mission to build the best Greenpower
						Racing car.
					</p>
					<div class="items-left justify-left mt-10 flex gap-x-6">
						<a
							href="/ee"
							class="rounded-md bg-gray-200 px-3.5 py-2.5 text-sm font-semibold text-gray-900 focus-visible:outline-2 focus-visible:outline-offset-2"
							>In Estonian <span aria-hidden="true">(estonian flag)</span></a
						>
						<a
							href="#aboutus"
							class="rounded-md bg-gray-200 px-3.5 py-2.5 text-sm font-semibold text-gray-900 focus-visible:outline-2 focus-visible:outline-offset-2"
							>Learn more <span aria-hidden="true">→</span></a
						>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div>
		<img
			src="https://static.pexels.com/photos/158971/pexels-photo-158971.jpeg"
			alt="1jupp Racing Team"
			class="h-full w-full object-cover"
		/>
	</div>
</header>

<main>
	<div id="sponsors" class="grid grid-cols-2" />

	<div id="aboutus" class="bg-white px-12 py-12 lg:px-60">
		<h2 class="tracking-light text-3xl font-bold text-gray-900 sm:text-4xl">
			About
		</h2>
		<p class="mt-6 text-lg leading-8 text-gray-700">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum repellat
			nesciunt, officia provident quas error dicta inventore minus voluptatibus
			vel blanditiis neque dolor sed nam esse quaerat accusantium exercitationem
			nobis.
		</p>
	</div>

	<div class="py-12">
		<img
			src="https://static.pexels.com/photos/158971/pexels-photo-158971.jpeg"
			alt="1jupp Racing Team"
			class="h-full w-full object-cover px-12 lg:px-60"
		/>
	</div>

	<div class="bg-white px-12 py-12 sm:py-32 lg:px-60 xl:grid-cols-4">
		<div class="max-w-7xl">
			<h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">
				Our team
			</h2>
		</div>

		<ul
			role="list"
			class="grid gap-x-8 gap-y-12 py-7 sm:grid-cols-2 sm:gap-y-16 xl:col-span-2"
		>
			<li>
				<div class="flex items-center gap-x-6">
					<img
						class="h-48 w-48 rounded-full"
						src="https://static.pexels.com/photos/158971/pexels-photo-158971.jpeg"
						alt=""
					/>
					<div>
						<h3 class="text-4xl font-semibold tracking-tight text-gray-900">
							Henri Aunin
						</h3>
						<p class="text-base font-semibold leading-8 text-gray-400">
							Telemeetria
						</p>
					</div>
				</div>
			</li>
		</ul>
	</div>

	<div class="bg-white px-12 py-12 lg:px-60">
		<h2 class="tracking-light text-3xl font-bold text-gray-900 sm:text-4xl">
			Press
		</h2>
		<p class="mt-6 text-lg leading-8 text-gray-700">
			<iframe
				width="560"
				height="315"
				src="https://www.youtube.com/embed/1jupp"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
				allowfullscreen
			/>
		</p>
	</div>

	<div class="bg-white px-12 py-12 lg:px-60">
		<div class="max-w-2xl content-center">
			<h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">
				Contact us
			</h2>
			<p class="mt-6 text-lg leading-8 text-gray-600">
				For press inquiries or sponsor contact.
			</p>
            <a href="mailto:contact@hen.ee" class="text-blue-500">contact@hen.ee</a>
		</div>
	</div>

</main>
