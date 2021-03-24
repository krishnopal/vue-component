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

                    <!-- Button Component -->
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
                    <!-- Button Component End-->

                    <!-- Alert Component -->
                    <div class="hover:bg-gray-500 hover:text-white shadow-md transition duration-300 ease-in-out rounded-lg bg-white text-xl text-green-800 font-bold py-2 w-full px-3 border-2 border-green-600 cursor-pointer my-3">
                        <p>Alert Component</p>
                    </div>
                    <div class="bg-white border-2 border-black p-5">
                        <div class="mb-2">
                            <GreenAlert/>
                        </div>
                        <div class="mb-2">
                            <RedAlert/>
                        </div>
                        <div class="mb-2">
                            <BlueAlert/>
                        </div>
                        <div class="mb-2">
                            <YellowAlert/>
                        </div>
                        <div class="mb-2">
                            <PinkAlert/>
                        </div>
                    </div>
                    <!-- Alert Component End-->

                    <!-- Avatar Component -->
                    <div class="hover:bg-gray-500 hover:text-white shadow-md transition duration-300 ease-in-out rounded-lg bg-white text-xl text-green-800 font-bold py-2 w-full px-3 border-2 border-green-600 cursor-pointer my-3">
                        <p>Avatar Component</p>
                    </div>
                    <div class="bg-white border-2 border-black p-5">
                        <div class="mb-2">
                            <FristAvatar/>
                        </div>
                        <div class="mb-2">
                            <SecondAvatar/>
                        </div>
                        <div class="mb-2">
                            <ThreeAvatar/>
                        </div>
                        <div class="mb-2">
                            <FourAvatar/>
                        </div>
                    </div>
                    <!-- Avatar Component End-->

                    <!-- Breadcrumb Component -->
                    <div class="hover:bg-gray-500 hover:text-white shadow-md transition duration-300 ease-in-out rounded-lg bg-white text-xl text-green-800 font-bold py-2 w-full px-3 border-2 border-green-600 cursor-pointer my-3">
                        <p>Breadcrumb Component</p>
                    </div>
                    <div class="bg-white border-2 border-black p-5">
                        <div class="mb-4">
                            <FristBreadcrumb/>
                        </div>
                        <div class="mb-2">
                            <SecondBreadcrumb/>
                        </div>
                    </div>
                    <!-- Breadcrumb Component End-->

                    <!-- Card Component -->
                    <div class="hover:bg-gray-500 hover:text-white shadow-md transition duration-300 ease-in-out rounded-lg bg-white text-xl text-green-800 font-bold py-2 w-full px-3 border-2 border-green-600 cursor-pointer my-3">
                        <p>Card Component</p>
                    </div>
                    <div class="bg-white border-2 border-black p-5">
                        <div class="mb-4">
                            <!-- ImageCard -->
                            <ImageCard/>
                        </div>
                        <div class="mb-4">
                            <!-- imageCardText -->
                            <ImageText/>
                        </div>
                        <div class="mb-4">
                            <!-- CardTitle -->
                            <CardTitle/>
                        </div>
                        <div class="mb-4">
                            <!-- FeaturedCard -->
                            <FeaturedCard/>
                        </div>
                        <div class="mb-4">
                            <!-- QuoteCard -->
                            <QuoteCard/>
                        </div>
                        <div class="mb-4">
                            <!-- FeaturedCenterCard -->
                            <FeaturedCenterCard/>
                        </div>
                        <div class="mb-4">
                            <!-- DoubleCard -->
                            <DoubleCard/>
                        </div>
                        <div class="mb-4">
                            <!-- ThreeCard -->
                            <ThreeCard/>
                        </div>
                    </div>
                    <!-- Card Component End-->

                    <!-- Home View Component -->
                    <div class="hover:bg-gray-500 hover:text-white shadow-md transition duration-300 ease-in-out rounded-lg bg-white text-xl text-green-800 font-bold py-2 w-full px-3 border-2 border-green-600 cursor-pointer my-3">
                        <p>Home View Component</p>
                    </div>
                    <div class="bg-white border-2 border-black p-5">
                        <div class="mb-4">
                            <HomeView/>
                        </div>
                    </div>
                    <!-- Home View Component End-->

                    <!-- From Component -->
                    <div class="hover:bg-gray-500 hover:text-white shadow-md transition duration-300 ease-in-out rounded-lg bg-white text-xl text-green-800 font-bold py-2 w-full px-3 border-2 border-green-600 cursor-pointer my-3">
                        <p>From Component</p>
                    </div>
                    <div class="bg-white border-2 border-black p-5">
                        <div class="mb-4">
                            <FristFrom/>
                        </div>
                        <div class="mb-4">
                            <SecondFrom/>
                        </div>
                    </div>
                    <!-- From Component End-->

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

import GreenAlert from '../components/Alert/GreenAlert.vue'
import BlueAlert from '../components/Alert/BlueAlert.vue'
import RedAlert from '../components/Alert/RedAlert.vue'
import YellowAlert from '../components/Alert/YellowAlert.vue'
import PinkAlert from '../components/Alert/PinkAlert.vue'

import FristAvatar from '../components/Avatar/FristAvatar.vue'
import SecondAvatar from '../components/Avatar/SecondAvatar.vue'
import ThreeAvatar from '../components/Avatar/ThreeAvatar.vue'
import FourAvatar from '../components/Avatar/FourAvatar.vue'

import FristBreadcrumb from '../components/Breadcrumb/FristBreadcrumb.vue'
import SecondBreadcrumb from '../components/Breadcrumb/SecondBreadcrumb.vue'

import ImageCard from '../components/Card/ImageCard.vue'
import CardTitle from '../components/Card/CardTitle.vue'
import FeaturedCard from '../components/Card/FeaturedCard.vue'
import QuoteCard from '../components/Card/QuoteCard.vue'
import FeaturedCenterCard from '../components/Card/FeaturedCenterCard.vue'
import DoubleCard from '../components/Card/DoubleCard.vue'
import ThreeCard from '../components/Card/ThreeCard.vue'
import ImageText from '../components/Card/ImageText.vue'

import HomeView from '../components/HomeView/HomeView.vue'

import FristFrom from '../components/From/FristFrom.vue'
import SecondFrom from '../components/From/SecondFrom.vue'


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
