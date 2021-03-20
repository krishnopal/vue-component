<template>

    <div class="flex flex-wrap overflow-hidden">
        <div class="w-full overflow-hidden">
            <Header/>
        </div>
        <div class="w-full overflow-hidden">
            <section>
                <div class="w-full mt-16  px-3">
                    <div class=" px-4 flex flex-wrap bg-gray-400 py-5">
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempore reiciendis asperiores iste laudantium ipsa praesentium aliquid laborum error voluptas sint, rem sit possimus minus numquam distinctio illo dicta impedit ipsum?</p>
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

defineProps({
//   msg: String
})

</script>
