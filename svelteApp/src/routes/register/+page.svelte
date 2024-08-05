<script>
    import Navbar from "$lib/components/navbar.svelte";
</script>

<Navbar />

<main class="bg-black">
    <div class="h-screen flex justify-evenly items-center font-thin">
        <form class="bg-white shadow-md rounded px-8 pt-6 pb-8 mb-4">

            <div class="text-center text-lg mb-4">
                Register
            </div>

            <div class="mb-4">
              <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="fname" type="text" placeholder="First Name">
            </div>

            <div class="mb-4">
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="lname" type="text" placeholder="Last Name">
            </div>

            <div class="mb-4">
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="email" type="email" placeholder="Email address">
            </div>

            <div class="mb-4">
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="Username">
            </div>

            <div class="mb-4">
                <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="password" type="password" placeholder="Password">
            </div>

            <div class="flex items-center justify-evenly">
              <button class="bg-blue-500 hover:bg-blue-700 text-white font-thin py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="button">
                Sign up!
              </button>
            </div>
          </form>
    </div>
</main>