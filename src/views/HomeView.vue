<template>
    <div>
    <navbar />
    <section class="bg-bgPrimary pb-4">
        <div class="flex flex-col  lg:flex-row w-full mx-auto max-w-screen-xl p-4 items-center justify-center lg:py-14">
            <div class="mx-auto max-w-screen-xl text-left w-full lg:w-2/3 py-4 lg:py-20">
                <h1 class="mb-4 text-4xl font-semibold text-primary md:text-5xl lg:text-6xl">Sparking Tomorrow's
                    Innovations.</h1>
                <p class="mb-8 text-lg font-light text-secondary lg:text-xl">Welcome all to the inovus community, a
                    bunch of 21st century human beings. We provide the walls and you're the artist. Come join us to be a
                    part of this journey of relevation.</p>
                <div class="flex flex-col space-y-4 sm:flex-row sm:justify-left sm:space-y-0 sm:space-x-4">
                    <a href="#"
                        class=" bg-bgSecondary inline-flex justify-center items-center py-3 px-10 text-base font-medium text-center text-white rounded border border-secondary hover:bg-secondary hover:text-white">
                        Kick Start
                    </a>
                </div>
            </div>
            <div class="w-full lg:w-1/3 py-4 lg:py-20">
                <img class="w-full h-full" src="/assets/work-in-progress-animate.svg" alt="Gallery" />
            </div>
        </div>
        <!-- Social Proof -->
        <section class="bg-bgSecondary bg-opacity-60 mx-32 dark:bg-gray-900">
            <div class="max-w-screen-xl px-4 py-8 mx-auto text-center lg:py-16 lg:px-6">
                <dl class="grid max-w-screen-md gap-8 mx-auto text-gray-900 sm:grid-cols-3 dark:text-white">
                    <div class="flex flex-col items-center justify-center">
                        <dt class="mb-2 text-3xl text-bgPrimary md:text-4xl font-extrabold">2500+</dt>
                        <dd class="font-light text-bgPrimary dark:text-gray-400">Results</dd>
                    </div>
                    <div class="flex flex-col items-center justify-center">
                        <dt class="mb-2 text-3xl text-bgPrimary md:text-4xl font-extrabold">300+</dt>
                        <dd class="font-light text-bgPrimary dark:text-gray-400">Hours saved</dd>
                    </div>
                    <div class="flex flex-col items-center justify-center">
                        <dt class="mb-2 text-3xl text-bgPrimary md:text-4xl font-extrabold">10+</dt>
                        <dd class="font-light text-bgPrimary dark:text-gray-400">Active Users</dd>
                    </div>
                </dl>
            </div>
        </section>
        <!-- The story behind scrapper -->
        <!-- <StoryView /> -->

        <!-- what why how -->
        <section>
            <div>
                <img src="/assets/what.png" alt="" class="w-full my-4">
            </div>
        </section>
        <!-- statical content -->
        <div data-aos="fade-up" class="grid grid-cols-1 mx-32 sm:grid-cols-3 gap-4 mt-4">
            <div class="bg-white p-6 rounded-md border shadow-md flex flex-col items-center justify-center">
                <h3 class="text-sm font-bold text-gray-900 mb-2">Total Results</h3>
                <span class="text-2xl font-bold text-gray-800">24</span>
            </div>
            <div class="bg-white p-6 rounded-md border shadow-md flex flex-col items-center justify-center">
                <h3 class="text-sm font-bold text-gray-900 mb-2">Total Exams</h3>
                <span class="text-2xl font-bold text-gray-800">32</span>
            </div>
            <div class="bg-white p-6 rounded-md border shadow-md flex flex-col items-center justify-center">
                <h3 class="text-sm font-bold text-gray-900 mb-2">Total Email Sent</h3>
                <span class="text-2xl font-bold text-gray-800">322</span>
            </div>
        </div>
        <!-- bento grid  -->
        <section class="mx-32">
            <div class="my-3 bg-white grid grid-cols-1 py-6 rounded-lg shadow-md md:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="p-4 flex flex-col items-center justify-center text-center h-full">
                    <h1 class="text-xl font-bold mb-2 pb-5">Before</h1>
                    <p class="text-2xl font-extrabold">10 - 15 Mins</p>
                </div>

                <div class="p-4 flex flex-col items-center justify-center text-center h-full">
                    <h1 class="text-xl font-bold mb-2 pb-5">Average time saved per student</h1>
                    <img src="/assets/Vector 2.png" alt="">
                </div>

                <div class="p-4 flex flex-col items-center justify-center text-center h-full">
                    <h1 class="text-xl font-bold mb-2 pb-5">After</h1>
                    <p class="text-2xl font-extrabold">2 - 5 Mins</p>
                </div>
            </div>
        </section>
        <!-- second box -->
        <section class="mx-32">
            <div class="my-3 bg-white grid grid-cols-1 py-6 rounded-lg shadow-md md:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="p-4 flex flex-col items-center justify-center text-center h-full">
                    <h1 class="text-xl font-bold mb-2 pb-5">Before</h1>
                    <p class="text-2xl font-extrabold">5 - 6 Hrs</p>
                </div>

                <div class="p-4 flex flex-col items-center justify-center text-center h-full">
                    <h1 class="text-xl font-bold mb-2 pb-5">Average time saved per teachers</h1>
                    <img src="/assets/Vector 3.png" alt="">
                </div>

                <div class="p-4 flex flex-col items-center justify-center text-center h-full">
                    <h1 class="text-xl font-bold mb-2 pb-5">After</h1>
                    <p class="text-2xl font-extrabold">5 Mins</p>
                </div>
            </div>
        </section>
        <!-- testimonial -->
        <section class="py-9">
            <testimonial />
        </section>
        <!-- Contact session -->
        <section class="lg:p-10 p-4 my-10 border-t  border-gray-200 dark:border-gray-700">

<div class="mx-auto max-w-screen-xl text-left w-full p-4 lg:mb-4">
    <h1 class="mb-4 text-2xl font-semibold leading-none tracking-tight text-gray-900 md:text-3xl lg:text-4xl dark:text-white">
        Get in touch, stay connected! 
    </h1>

    <p class="text-lg font-light text-gray-500 lg:text-xl dark:text-gray-400">
        Reach out through our contact section to share thoughts, inquiries, or simply say hello. We value every connection and look forward to hearing from you. Let's build bridges together! 
    </p>
</div>



<div class="gap-16 items-center px-4 mx-auto max-w-screen-xl lg:grid lg:grid-cols-2 lg:px-6">
    <div class="py-8 space-y-8">

        <div class="flex flex-col items-center justify-center border rounded-lg p-8 bg-white">
            <div class=" border flex justify-center items-center mb-2 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                <svg class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z"></path></svg>
            </div>
            <h3 class="mb-2 text-xl font-semibold dark:text-white">Address:</h3>
            <p class="text-gray-500 text-center dark:text-gray-400">Kristu Jyoti College of Management & Technology<br/>Chethipuzha P.O, Changanacherry, Kottayam, Kerala, India.</p>
        </div>

        <div class="flex flex-col items-center justify-center border rounded-lg p-8 bg-white">
            <div class=" border flex justify-center items-center mb-2 w-10 h-10 rounded-full bg-primary-100 lg:h-12 lg:w-12 dark:bg-primary-900">
                <svg class="w-5 h-5 text-primary-600 lg:w-6 lg:h-6 dark:text-primary-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M6 6V5a3 3 0 013-3h2a3 3 0 013 3v1h2a2 2 0 012 2v3.57A22.952 22.952 0 0110 13a22.95 22.95 0 01-8-1.43V8a2 2 0 012-2h2zm2-1a1 1 0 011-1h2a1 1 0 011 1v1H8V5zm1 5a1 1 0 011-1h.01a1 1 0 110 2H10a1 1 0 01-1-1z" clip-rule="evenodd"></path><path d="M2 13.692V16a2 2 0 002 2h12a2 2 0 002-2v-2.308A24.974 24.974 0 0110 15c-2.796 0-5.487-.46-8-1.308z"></path></svg>                    
            </div>
            <h3 class="mb-2 text-xl font-bold dark:text-white">Support:</h3>
            <div class="justify-center items-center text-center">
                <p class="text-gray-500 text-left dark:text-gray-400">Email: <a class="text-primary hover:text-blue-500" href="mailto:inovuslabs@kjcmt.ac.in">inovuslabs@kjcmt.ac.in</a></p>
                <p class="text-gray-500 text-left dark:text-gray-400">Mobile: <a class="text-primary hover:text-blue-500" href="tel:+919400057152">+91 94000 57152</a></p>
            </div>
        </div>

    </div>



    
    
    <div class="py-8 lg:py-16 px-4 w-full mx-auto max-w-screen-md">
        <form action="#" class="space-y-8">
            <div>
                <div class="flex gap-2">
                    <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Your email address</label>
                    <span class="mb-2 text-xs font-normal text-gray-400 dark:text-gray-700">(So we can reply to you)</span>
                </div>
                <input type="email" id="email" class="shadow-sm bg-white border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-bgSecondary focus:border-bgSecondary block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-bgSecondary dark:shadow-sm-light" placeholder="name@company.com" required>
            </div>
            <div>
                <label for="subject" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-300">Subject</label>
                <input type="text" id="subject" class="block p-3 w-full text-sm text-gray-900 bg-white rounded-lg border border-gray-300 shadow-sm focus:ring-bgSecondary focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500 dark:shadow-sm-light" placeholder="Let us know how we can help you..." required>
            </div>
            <div class="sm:col-span-2">
                <label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-gray-400">Your message</label>
                <textarea id="message" rows="6" class="block p-2.5 w-full text-sm text-gray-900 bg-white rounded-lg shadow-sm border border-gray-300 focus:ring-bgSecondary focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="Leave a comment..."></textarea>
            </div>
            <button type="submit" class="py-2 px-5 text-sm font-medium text-center text-white rounded-lg bg-primary sm:w-fit hover:bg-blue-500 dark:bg-primary dark:hover:bg-blue-500">Send message</button>
        </form>
    </div>
    
</div>

</section>


    </section>

</div>
</template>
<script>
import navbar from '../components/Reuse/navbar.vue';
import StoryView from '../components/StoryView.vue';
import testimonial from '../components/Testimonial.vue';

export default {
    name: 'HomeView',
    components: {
        navbar,
        StoryView,
        testimonial
    }
}

</script>