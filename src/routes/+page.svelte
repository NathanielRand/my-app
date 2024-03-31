<script>
	import { Alert, Hr } from 'flowbite-svelte';
	import { Section } from 'flowbite-svelte-blocks'
  	import { FireOutline } from 'flowbite-svelte-icons';
</script>

<Section>
    <div class="py-6 px-4 mx-auto max-w-screen-xl text-center">
        <h1 class="mb-4 text-4xl md:text-5xl lg:text-7xl font-black tracking-tight leading-none text-gray-900 dark:text-white">
			Code so good,<br><c class="lg:text-5xl">it practically writes itself</c>
		</h1>
        <p class="mb-8 text-lg font-normal text-gray-500 lg:text-2xl sm:px-16 lg:px-48 dark:text-gray-400">The best code comes from the weirdest of places and the most unlikely of times. Let us help you bring your ideas to life with code that will make your projects <c class='text-primary-600'>sizzle</c>.</p>
        <div class="flex flex-col space-y-4 sm:flex-row sm:justify-center sm:space-y-0">
            <a href="#" class="inline-flex justify-center items-center py-3 px-5 text-2xl uppercase font-thin text-center text-white rounded-lg bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 dark:focus:ring-primary-900">
                Get started
                <svg class="w-4 h-4 ms-2 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
                </svg>
            </a>
            <a href="#" class="py-3 px-5 sm:ms-4 text-xl uppercase font-black text-gray-900 focus:outline-none bg-white rounded-lg border border-gray-200 hover:bg-gray-100 hover:text-primary-700 focus:z-10 focus:ring-4 focus:ring-gray-100 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-70">
                Learn more
            </a>  
        </div>
    </div>
</Section>

<Hr />

<section>
	<h3>Step 1: Select Service</h3>
	<div class="grid grid-cols-1 gap-4 mt-4 sm:grid-cols-2 lg:grid-cols-3">
		<div class="p-4 bg-white border border-gray-200 rounded-lg dark:bg-gray-800 dark:border-gray-600">
			<h4 class="text-xl font-black text-gray-900 dark:text-gray-400">Web Development</h4>
			<p class="mt-2 text-gray-500 dark:text-gray-500">Websites, web apps, and more.</p>
		</div>
		<div class="p-4 bg-white border border-gray-200 rounded-lg dark:bg-gray-800 dark:border-gray-600">
			<h4 class="text-xl font-black text-gray-900 dark:text-gray-400">Automation</h4>
			<p class="mt-2 text-gray-500 dark:text-gray-500">Automate your business processes.</p>
		</div>
		<div class="p-4 bg-white border border-gray-200 rounded-lg dark:bg-gray-800 dark:border-gray-600">
			<h4 class="text-xl font-black text-gray-900 dark:text-gray-400">Data Analysis</h4>
			<p class="mt-2 text-gray-500 dark:text-gray-500">Get insights from your data.</p>
		</div>
	</div>
</section>
