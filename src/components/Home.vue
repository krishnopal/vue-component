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

                    <div class="hover:bg-gray-500 hover:text-white shadow-md transition duration-300 ease-in-out rounded-lg bg-white text-xl text-green-800 font-bold py-2 w-full px-3 border-2 border-green-600 cursor-pointer my-3">
                        <p>Button Component</p>
                    </div>
                    <!-- Button Show -->
                    <div id="button-handling" class="bg-white border-2 border-black p-5">
                        <!-- frist -->
                        <div class="my-5">
                            <FristButton/>
                        </div>
                        <!-- second -->
                        <div class="my-6">
                            <SecondButton/>
                        </div>

                        <!-- three -->
                        <div class="my-6">
                            <ThreeButton/>
                        </div>

                        <!-- Four -->
                        <div class="my-6">
                            <FourButton/>
                        </div>

                        <!-- Five -->
                        <div class="my-6">
                            <FiveButton/>
                        </div>

                        <!-- Six -->
                        <div class="my-6">
                            <SixButton/>
                        </div>

                        <!-- Seven -->
                        <div class="my-6">
                            <SevenButton/>
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

import FristButton from '../components/Button/FristButton.vue'
import SecondButton from '../components/Button/SecondButton.vue'
import ThreeButton from '../components/Button/ThreeButton.vue'
import FourButton from '../components/Button/FourButton.vue'
import FiveButton from '../components/Button/FiveButton.vue'
import SixButton from '../components/Button/SixButton.vue'
import SevenButton from '../components/Button/SevenButton.vue'

//  v-if="showButton"
// @click="showButtonFunction"
// const ButtonHandling = {
//   data() {
//     return {
//       showButton: false
//     }
//   },
//   methods: {
//     showButtonFunction() {
//       this.showButton = !this.showButton
//     }
//   }
// }

// createApp(ButtonHandling).mount('#button-handling')

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
