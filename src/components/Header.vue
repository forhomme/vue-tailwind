<template>
 <header class="w-full font-sans bg-white text-gray-900 bg-gradient-to-br to-blue-100">
   <nav class="flex items-center justify-between px-4 py-4 max-w-screen-xl mx-auto">
     <a href="#" class="text-4xl font-bold tracking-wide">F<span class="text-blue-700">bIg</span></a>
     <div class="flex items-center space-x-14">
       <ul class="flex items-center space-x-8">
         <li>
           <a href="#" class="font-medium text-gray-600 hover:text-white hover:bg-gray-400 py-2 px-6 transition
           duration-150 ease-in-out rounded-lg hover:shadow-lg">Login</a>
         </li>
         <li>
           <button class="bg-blue-700 text-white font-bold py-2 px-6 rounded-lg border border-white hover:bg-gray-400
         transition-shadow duration-300 ease-in-out hover:shadow-lg">Sign Up</button>
         </li>
       </ul>
     </div>
   </nav>
 </header>
</template>

<script>
export default {
  name: "Header",
  data () {
    return {
      menus: ["Sign in", "Sign up"]
    }
  }
}
</script>