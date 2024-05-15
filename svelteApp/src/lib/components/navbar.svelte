<script>
    let transition = "transition-all duration-300 font-extrabold";
</script>

<header class="w-full top-0 sticky backdrop-blur-lg">
    <nav class="bg-black">
        <div class="max-w-full mx-auto py-3 px-20">
            <div class="flex justify-between font-mono">
                 <div class="flex space-x-4">
                    <div class="text-white flex items-center space-x-4 mr-4">
                        <a href="#">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 12c0-1.232-.046-2.453-.138-3.662a4.006 4.006 0 0 0-3.7-3.7 48.678 48.678 0 0 0-7.324 0 4.006 4.006 0 0 0-3.7 3.7c-.017.22-.032.441-.046.662M19.5 12l3-3m-3 3-3-3m-12 3c0 1.232.046 2.453.138 3.662a4.006 4.006 0 0 0 3.7 3.7 48.656 48.656 0 0 0 7.324 0 4.006 4.006 0 0 0 3.7-3.7c.017-.22.032-.441.046-.662M4.5 12l3 3m-3-3-3 3" />
                            </svg>
                        </a>
                        <span>Ansibly</span>
                    </div>
                    <div class="text-white space-x-4 transition-all duration-500">
                        <a href="#" class="hover:text-indigo-500 {transition}">Features</a>
                        <a href="#" class="hover:text-orange-500 {transition}">Pricing</a>
                    </div>
                </div>
                <div class="flex text-white">
                    <div class="space-x-4 ">
                        <a href="#" class="hover:text-cyan-500 {transition}">Login</a>
                        <a href="#" class="hover:bg-yellow-500 py-2 px-2 rounded-md {transition}">Sign up</a>
                    </div>
                </div>
            </div>
        </div>
    </nav>
</header>