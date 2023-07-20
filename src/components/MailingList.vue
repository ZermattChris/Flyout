
<template>
    <div class="flex min-h-full flex-1 flex-col justify-center pb-6 py-18 ">
      <div class="sm:mx-auto sm:w-full sm:max-w-sm -mt-12">

        <img src="/Matterhorn-Art-Studios-logo.svg" alt="Matterhorn Art Studios Logo" />

        <h2 class="mt-10 text-center text-2xl font-bold leading-9 tracking-tight text-gray-900">Interested in updates to our Project?</h2>
        <h3 class="text-center text-xl leading-9 tracking-tight text-gray-500">Drop us your email.</h3>
      </div>
  
      <div class="mt-10 sm:mx-auto sm:w-full sm:max-w-sm">
        <form class="space-y-6" action="#" method="POST">
          <div>
            <label for="email" class="block text-sm font-medium leading-6 text-gray-900">Email address</label>
            <div class="mt-2">
              <input id="email" name="email" type="email" autocomplete="email" required="Please enter a valid email address." class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6" />
            </div>
          </div>
   
          <div>
            <button type="submit" class="flex w-full justify-center rounded-md bg-indigo-600 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Sign up</button>
          </div>
        </form>
  
        <p class="mt-10 text-center text-sm text-gray-500">
          We will only send you an Email when we have something new and noteworthy - absolutely no spam!
        </p>
      </div>
    </div>
  </template>
  
