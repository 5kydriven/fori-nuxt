<template>
	<div class="flex justify-center">
		<div
			class="min-h-[60vh] max-w-screen-xl mx-auto flex flex-col items-center justify-center gap-10  px-4 py-10"
		>
			<div class="flex flex-col md:flex-row items-center justify-between gap-10 p-4 rounded-md ">
				<div class="flex-1 flex justify-center items-center ">
					<div class="p-8 rounded-full bg-red-600">
						<img
							src="/chef.png"
							class="w-48 h-48 md:w-72 md:h-72 rounded-lg drop-shadow-2xl/50 "
						/>
					</div>
				</div>
				<div class="flex-1 space-y-4">
					<h1 class="text-3xl font-bold capitalize">
						We are more than multiple service
					</h1>
					<p class="text-gray-600">
						This restaurant is not just about food; it's about creating an unforgettable experience. From our exquisite menu to our attentive service, we strive to make every visit special. Whether you're here for a casual meal or a celebration, we have something for everyone.
					</p>
					<UButton
					label="About Us"
					color="error"
					@click="$router.push('/about')"
					/>
				</div>
			</div>
		</div>
	</div>
</template>
