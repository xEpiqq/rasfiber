<div class="flex h-screen flex-col justify-center px-4 py-12 lg:px-8 items-center">
	<div class="w-full sm:mx-auto sm:max-w-sm">
	  <img
		class="mx-auto h-10 w-auto"
		src="https://tailwindui.com/plus/img/logos/mark.svg?color=indigo&shade=600"
		alt="Your Company"
	  />
	  <h2 class="mt-10 text-center text-2xl font-bold tracking-tight text-gray-900">
		Rasfiber Payroll
	  </h2>
	</div>
  
	<div class="mt-10 w-full sm:mx-auto sm:max-w-sm">
	  <form class="space-y-6" action="?/login" method="POST">
		<div>
		  <label for="email" class="block text-sm font-medium text-gray-900">
			Email address
		  </label>
		  <div class="mt-2">
			<input
			  id="email"
			  name="email"
			  type="email"
			  autocomplete="email"
			  required
			  class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm"
			/>
		  </div>
		</div>
  
		<div>
		  <div class="flex items-center justify-between">
			<label for="password" class="block text-sm font-medium text-gray-900">
			  Password
			</label>
			<div class="text-sm">
			  <a href="#" class="font-semibold text-indigo-600 hover:text-indigo-500">
				Forgot password?
			  </a>
			</div>
		  </div>
		  <div class="mt-2">
			<input
			  id="password"
			  name="password"
			  type="password"
			  autocomplete="current-password"
			  required
			  class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm"
			/>
		  </div>
		</div>
  
		<div>
		  <button
			type="submit"
			class="flex w-full justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
		  >
			Sign in
		  </button>
		</div>
	  </form>
	</div>
  </div>
  