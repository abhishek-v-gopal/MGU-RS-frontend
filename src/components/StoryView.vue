<template>
    <section>
        <div class="w-full mx-auto max-w-screen-xl p-4 items-center justify-center lg:py-14">
            <h1 class="text-bgSecondary text-6xl mb-4">SCRAPPER<span class="text-gray-900 text-sm">THE STORY</span></h1>
            
            <div class="relative flex items-center mt-10">
                <!-- Background div -->
                <div class="bg-bgSecondary rounded-lg w-full h-96 flex items-center">
                    <!-- Image container -->
                    <div class="w-1/3 -ml-16">
                        <img class="w-auto h-96 transform translate" src="/assets/Cartoonimage.png" alt="Gallery" />
                    </div>                    
                    <!-- Circular placeholders -->                     
                    <div class="w-2/3 grid grid-cols-2 gap-8 pr-16">
                        <div class="mr-32 ">
                            <div
                                class="group relative rounded-full border-4 border-dashed border-white h-24 w-24 flex items-center justify-center animate-[smoothZoom_6s_ease-in-out_infinite] [animation-delay:0.2s] hover:animate-none">
                                <div class="bg-white rounded-full h-16 w-16 flex items-center justify-center">
                                    <span class="text-green-500 text-2xl font-bold"><img src="/assets/icon/Vector.png"
                                            alt="" class="h-5"></span>
                                </div>
                                <div
                                    class="absolute top-1/2 right-full transform -translate-y-3/4 z-40 ml-4 bg-white rounded-lg shadow-lg p-6 opacity-0 group-hover:opacity-100 transition-all duration-300 w-72 h-48">
                                    <h3 class="text-bgSecondary text-xl font-bold mb-2">Dialog Box 1</h3>
                                    <p class="text-gray-800">This is the content of the dialog box for the fourth
                                        circle.</p>
                                </div>
                            </div>
                        </div>
                        
                        
                        

                        <div class="mr-32">
                            <div
                                class="group relative rounded-full border-4 border-dashed border-white h-24 w-24 flex items-center justify-center animate-[smoothZoom_6s_ease-in-out_infinite] [animation-delay:0.4s] hover:animate-none">
                                <div class="bg-white rounded-full h-16 w-16 flex items-center justify-center">
                                    <span class="text-green-500 text-2xl font-bold"><img
                                            src="/assets/icon/Vector (3).png" alt="" class="h-5"></span>
                                </div>
                                <div
                                    class="absolute top-1/2 right-full transform -translate-y-3/4  ml-4 z-40 bg-white rounded-lg shadow-lg p-6 opacity-0 group-hover:opacity-100 transition-all duration-300 w-72 h-48">
                                    <h3 class="text-bgSecondary text-xl font-bold mb-2">Dialog Box 3</h3>
                                    <p class="text-gray-800">This is the content of the dialog box for the fourth
                                        circle.</p>
                                </div>
                            </div>
                        </div>

                        <div class="ml-48">
                            <div
                                class="group relative rounded-full border-4 border-dashed border-white h-24 w-24 flex items-center justify-center animate-[smoothZoom_6s_ease-in-out_infinite] [animation-delay:0.6s] hover:animate-none">
                                <div class="bg-white rounded-full h-16 w-16 flex items-center justify-center">
                                    <span class="text-green-500 text-2xl font-bold"><img
                                            src="/assets/icon/Vector (1).png" alt="" class="h-5"></span>
                                </div>
                                <div
                                    class="absolute top-1/2 right-full transform  ml-4 z-40 bg-white rounded-lg shadow-lg p-6 opacity-0 group-hover:opacity-100 transition-all duration-300 w-72 h-48">
                                    <h3 class="text-bgSecondary text-xl font-bold mb-2">Dialog Box 2</h3>
                                    <p class="text-gray-800">This is the content of the dialog box for the fourth
                                        circle.</p>
                                </div>
                            </div>
                        </div>

                        <div class="ml-48">
                            <div
                                class="group relative rounded-full border-4 border-dashed border-white h-24 w-24 flex items-center justify-center animate-[smoothZoom_6s_ease-in-out_infinite] [animation-delay:0.8s] hover:animate-none">
                                <div class="bg-white rounded-full h-16 w-16 flex items-center justify-center">
                                    <span class="text-green-500 text-2xl font-bold"><img
                                            src="/assets/icon/Vector (3).png" alt="" class="h-5"></span>
                                </div>
                                <div
                                    class="absolute top-1/2 right-full transform  ml-4 z-40 bg-white rounded-lg shadow-lg p-6 opacity-0 group-hover:opacity-100 transition-all duration-300 w-72 h-48">
                                    <h3 class="text-bgSecondary text-xl font-bold mb-2">Dialog Box 4</h3>
                                    <p class="text-gray-800">This is the content of the dialog box for the fourth
                                        circle.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'StoryView',
}
</script>
<style>
@keyframes smoothZoom {

    0%,
    100% {
        transform: scale(1) translateY(0);
        opacity: 0.5;
    }

    50% {
        transform: scale(1.15) translateY(-10px);
        opacity: 1;
    }
}

@keyframes floatingShadow {

    0%,
    100% {
        transform: scale(1) translateY(0);
        opacity: 0.3;
        filter: blur(4px);
    }

    50% {
        transform: scale(0.9) translateY(0);
        opacity: 0.2;
        filter: blur(6px);
    }
}
</style>