<template>

    <div class="flex flex-wrap overflow-hidden">
        <div class="w-full overflow-hidden">
            <Header/>
        </div>
        <div class="w-full overflow-hidden my-5 px-4">
            <section>
                <div class="w-full py-5 px-6 bg-gray-400">
                    <div class=" flex flex-wrap">
                        <p>See This All Component Here.</p>
                    </div>

                    <div @click="showButtonFunction" class="hover:bg-gray-500 hover:text-white shadow-md transition duration-300 ease-in-out rounded-lg bg-white text-xl text-green-800 font-bold py-2 w-full px-3 border-2 border-green-600 cursor-pointer my-3">
                        <p>Button Component</p>
                    </div>
                    <!-- Button Show -->
                    <div v-if="showButton" id="button-handling" class="bg-white border-2 border-black p-5">
                        <!-- frist -->
                        <div class="my-5">
                            <span class="mr-3">
                                <button class="bg-purple-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50">Focus Button</button>
                            </span>
                            <span class="mr-3"> 
                                <button class="bg-purple-500 py-2 px-3 rounded-md text-white focus:outline-none hover:bg-purple-600">Non-Focus Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-red-500 hover:bg-red-700 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-red-600 focus:ring-opacity-50">
                                Hover me
                                </button>
                            </span>
                        </div>
                        <!-- second -->
                        <div class="my-6">
                            <span class="mr-3">
                                <button class="bg-blue-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-red-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-red-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-gray-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-gray-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-yellow-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-yellow-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-green-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-green-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-indigo-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-indigo-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-pink-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-pink-600 focus:ring-opacity-50">Button</button>
                            </span>
                        </div>

                        <!-- three -->
                        <div class="my-6">
                            <span class="mr-3">
                                <button class="hover:bg-blue-500 border-2 border-blue-500 text-blue-500 hover:text-white transition duration-300 ease-in-out py-2 px-3 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="hover:bg-red-500 border-2 border-red-500 text-red-500 hover:text-white transition duration-300 ease-in-out py-2 px-3 rounded-md focus:outline-none focus:ring-2 focus:ring-red-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="hover:bg-gray-500 border-2 border-gray-500 text-gray-500 hover:text-white transition duration-300 ease-in-out py-2 px-3 rounded-md focus:outline-none focus:ring-2 focus:ring-gray-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="hover:bg-yellow-500 border-2 border-yellow-500 text-yellow-500 hover:text-white transition duration-300 ease-in-out py-2 px-3 rounded-md focus:outline-none focus:ring-2 focus:ring-yellow-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="hover:bg-green-500 border-2 border-green-500 text-green-500 hover:text-white transition duration-300 ease-in-out py-2 px-3 rounded-md focus:outline-none focus:ring-2 focus:ring-green-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="hover:bg-indigo-500 border-2 border-indigo-500 text-indigo-500 hover:text-white transition duration-300 ease-in-out py-2 px-3 rounded-md focus:outline-none focus:ring-2 focus:ring-indigo-600 focus:ring-opacity-50">Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="hover:bg-pink-500 border-2 border-pink-500 text-pink-500 hover:text-white transition duration-300 ease-in-out py-2 px-3 rounded-md focus:outline-none focus:ring-2 focus:ring-pink-600 focus:ring-opacity-50">Button</button>
                            </span>
                        </div>

                        <!-- Four -->
                        <div class="my-6">
                            <span class="mr-3">
                                <button class="bg-blue-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-sm">Small Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-red-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-red-600 focus:ring-opacity-50 text-md">Medium Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-gray-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-gray-600 focus:ring-opacity-50 text-lg" >Large Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-yellow-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-yellow-600 focus:ring-opacity-50 text-xl">Extra Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-green-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-green-600 focus:ring-opacity-50 text-2xl">Extra Large Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-indigo-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-indigo-600 focus:ring-opacity-50 text-3xl">H-M-E-L-B</button>
                            </span>
                            <span class="mr-3">
                                <button class="bg-pink-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-pink-600 focus:ring-opacity-50 text-4xl">H-E-L-Button</button>
                            </span>
                        </div>

                        <!-- Five -->
                        <div class="my-6">
                            <span class="mr-3 ">
                                <button class="bg-blue-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 w-full text-md">Small Button</button>
                            </span>
                            <span class="mr-3">
                                <button class="mt-3 hover:bg-red-500 border-2 border-red-500 text-red-500 hover:text-white transition duration-300 ease-in-out  py-2 px-3 rounded-md w-full focus:outline-none focus:ring-2 focus:ring-red-600 focus:ring-opacity-50 text-md">Medium Button</button>
                            </span>
                        </div>

                        <!-- Six -->
                        <div class="my-6">
                            <span class="mr-3 ">
                                <input class="bg-blue-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md" type="submit" name="submit" value="Input Button">
                            </span>
                            <span class="mr-3">
                                 <input class="bg-red-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-red-600 focus:ring-opacity-50 text-md" type="submit" name="submit" value="Input Button">
                            </span>
                            <span class="mr-3">
                                 <input class="bg-green-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-green-600 focus:ring-opacity-50 text-md" type="submit" name="submit" value="Input Button">
                            </span>
                            <span class="mr-3">
                                 <input class="bg-yellow-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-yellow-600 focus:ring-opacity-50 text-md" type="submit" name="submit" value="Input Button">
                            </span>
                            <span class="mr-3">
                                 <input class="bg-gray-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-gray-600 focus:ring-opacity-50 text-md" type="submit" name="submit" value="Input Button">
                            </span>
                            <span class="mr-3">
                                 <input class="bg-pink-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-pink-600 focus:ring-opacity-50 text-md" type="submit" name="submit" value="Input Button">
                            </span>
                            <span class="mr-3">
                                 <input class="bg-purple-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50 text-md" type="submit" name="submit" value="Input Button">
                            </span>
                        </div>

                        <!-- Seven -->
                        <div class="my-6">
                            <span class="mr-5 ">
                                <a class="bg-blue-500 py-2 px-3 rounded-l-md text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md border-2 border-blue-600" href="">Pre</a>
                                <a class="bg-blue-500 py-2 px-3 text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md border-l-1 border-r-2 border-t-2 border-b-2 border-blue-600" href="">1</a>
                                <a class="bg-blue-500 py-2 px-3 text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md border-l-1 border-r-2 border-t-2 border-b-2 border-blue-600" href="">2</a>
                                <a class="bg-blue-500 py-2 px-3 text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md border-l-1 border-r-2 border-t-2 border-b-2 border-blue-600" href="">3</a>
                                <a class="bg-blue-500 py-2 px-3 text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md border-l-1 border-r-1 border-t-2 border-b-2 border-blue-600" href="">4</a>
                                <a class="bg-blue-500 py-2 px-3 rounded-r-md text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md border-2 border-blue-600" href="">Next</a>
                            </span>
                            <span class="mr-5 ">
                                <a class="bg-blue-500 py-2 px-3 rounded-md mr-1 text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md" href="">Pre</a>

                                <a class="bg-blue-500 py-2 px-3 rounded-md mr-1 text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">1</a>
                                <a class="bg-blue-500 py-2 px-3 rounded-md mr-1 text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">2</a>
                                <a class="bg-blue-500 py-2 px-3 rounded-md mr-1 text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">3</a>
                                <a class="bg-blue-500 py-2 px-3 rounded-md mr-1 text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">4</a>

                                <a class="bg-blue-500 py-2 px-3 rounded-md text-white focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">Next</a>
                            </span>
                            <span class="mr-5 ">
                                <a class="hover:bg-blue-500 border-2 border-blue-500 text-blue-500 hover:text-white py-2 px-3 rounded-md mr-1 focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md" href="">Pre</a>

                                <a class="hover:bg-blue-500 border-2 border-blue-500 text-blue-500 hover:text-white py-2 px-3 rounded-md mr-1 focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">1</a>
                                <a class="hover:bg-blue-500 border-2 border-blue-500 text-blue-500 hover:text-white py-2 px-3 rounded-md mr-1 focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">2</a>
                                <a class="hover:bg-blue-500 border-2 border-blue-500 text-blue-500 hover:text-white py-2 px-3 rounded-md mr-1 focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">3</a>
                                <a class="hover:bg-blue-500 border-2 border-blue-500 text-blue-500 hover:text-white py-2 px-3 rounded-md mr-1 focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">4</a>

                                <a class="hover:bg-blue-500 border-2 border-blue-500 text-blue-500 hover:text-white py-2 px-3 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-600 focus:ring-opacity-50 text-md " href="">Next</a>
                            </span>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        <div class="w-full overflow-hidden">
            <Footer/>
        </div>
    </div>


</template>

<script setup>
import Header from '../components/inc/Header.vue'
import Footer from '../components/inc/Footer.vue'


const ButtonHandling = {
  data() {
    return {
      showButton: false
    }
  },
  methods: {
    showButtonFunction() {
      this.showButton = !this.showButton
    }
  }
}

createApp(ButtonHandling).mount('#button-handling')

// export default {
//     setup(props) {
//         const showButton = ref(false);
//         const showingTerms = ref(false);

//         const toggleTerms = value => {
//             const { screenview } = useGtag();
//             screenview({
//                 screen_name: "termas_window"
//             });
//             showingTerms.value = value ?? !showingTerms.value;
//         };
//         const showButtonFunction = () => {
//             showButton.value = true;
//             showingTerms.value = false;
//         };
//     }
// };


</script>
