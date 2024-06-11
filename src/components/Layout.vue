<script setup>

const projects = [
    {
        name: 'Fuel Pump Management System'
    },
    {
        name: 'Medical Insurance Management System'
    },
    {
        name: 'Visitors Log Management System'
    },
    {
        name: 'E-Sports Platform for Gambia Footballers'
    },
    {
        name: 'Pluto Integrated Solution'
    },
    {
        name: 'Coupon Management System  stem'
    }
]

const programmingLanguages = [
    {
        name: 'C#'
    },
    {
        name: "Php"
    },
    {
        name: "Dart"
    },
    {
        name: "Python"
    },
    {
        name: "Html & Css"
    },
    {
        name: "Kotlin"
    },
    {
        name: "Javascript"
    }
]


const frameworks = [
    {
        name: '.Net Framework'
    },
    {
        name: "Laravel"
    },
    {
        name: "VueJs"
    },
    {
        name: "Angular"
    },
    {
        name: "React"
    }
]

</script>

<template>
    <div class="bg-gray-100 min-w-full min-h-screen">

        <nav class="p-2 h-16">

            <ul class="flex justify-evenly space-x-2">
                <li class="flex flex-col items-center bg-blue-300 flex-1 py-2 rounded-md ">
                  

                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6">
                        <path
                            d="M19.006 3.705a.75.75 0 1 0-.512-1.41L6 6.838V3a.75.75 0 0 0-.75-.75h-1.5A.75.75 0 0 0 3 3v4.93l-1.006.365a.75.75 0 0 0 .512 1.41l16.5-6Z" />
                        <path fill-rule="evenodd"
                            d="M3.019 11.114 18 5.667v3.421l4.006 1.457a.75.75 0 1 1-.512 1.41l-.494-.18v8.475h.75a.75.75 0 0 1 0 1.5H2.25a.75.75 0 0 1 0-1.5H3v-9.129l.019-.007ZM18 20.25v-9.566l1.5.546v9.02H18Zm-9-6a.75.75 0 0 0-.75.75v4.5c0 .414.336.75.75.75h3a.75.75 0 0 0 .75-.75V15a.75.75 0 0 0-.75-.75H9Z"
                            clip-rule="evenodd" />
                    </svg>
                    <span class="font-extrabold">Home</span>


                </li>
                <li class="flex flex-col items-center bg-blue-300 flex-1 py-2 rounded-md">
                
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6">
                        <path fill-rule="evenodd"
                            d="M9.315 7.584C12.195 3.883 16.695 1.5 21.75 1.5a.75.75 0 0 1 .75.75c0 5.056-2.383 9.555-6.084 12.436A6.75 6.75 0 0 1 9.75 22.5a.75.75 0 0 1-.75-.75v-4.131A15.838 15.838 0 0 1 6.382 15H2.25a.75.75 0 0 1-.75-.75 6.75 6.75 0 0 1 7.815-6.666ZM15 6.75a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5Z"
                            clip-rule="evenodd" />
                        <path
                            d="M5.26 17.242a.75.75 0 1 0-.897-1.203 5.243 5.243 0 0 0-2.05 5.022.75.75 0 0 0 .625.627 5.243 5.243 0 0 0 5.022-2.051.75.75 0 1 0-1.202-.897 3.744 3.744 0 0 1-3.008 1.51c0-1.23.592-2.323 1.51-3.008Z" />
                    </svg>
                    <span class="font-extrabold">Projects</span>

                </li>
                <li class="flex flex-col items-center bg-blue-300 flex-1 py-2 rounded-md">
                  
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6">
                        <path fill-rule="evenodd"
                            d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"
                            clip-rule="evenodd" />
                    </svg>
                    <span class="font-extrabold">Skills</span>

                </li>
                <li class="flex flex-col items-center bg-blue-300 flex-1 py-2 rounded-md">
                   
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6">
                        <path
                            d="M6 3a3 3 0 0 0-3 3v2.25a3 3 0 0 0 3 3h2.25a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3H6ZM15.75 3a3 3 0 0 0-3 3v2.25a3 3 0 0 0 3 3H18a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3h-2.25ZM6 12.75a3 3 0 0 0-3 3V18a3 3 0 0 0 3 3h2.25a3 3 0 0 0 3-3v-2.25a3 3 0 0 0-3-3H6ZM17.625 13.5a.75.75 0 0 0-1.5 0v2.625H13.5a.75.75 0 0 0 0 1.5h2.625v2.625a.75.75 0 0 0 1.5 0v-2.625h2.625a.75.75 0 0 0 0-1.5h-2.625V13.5Z" />
                    </svg>

                    <span class="font-extrabold">Hobbies</span>

                </li>
                <li class="flex flex-col items-center bg-blue-300 flex-1 py-2 rounded-md">
                   


                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6">
                        <path d="M10.5 18.75a.75.75 0 0 0 0 1.5h3a.75.75 0 0 0 0-1.5h-3Z" />
                        <path fill-rule="evenodd"
                            d="M8.625.75A3.375 3.375 0 0 0 5.25 4.125v15.75a3.375 3.375 0 0 0 3.375 3.375h6.75a3.375 3.375 0 0 0 3.375-3.375V4.125A3.375 3.375 0 0 0 15.375.75h-6.75ZM7.5 4.125C7.5 3.504 8.004 3 8.625 3H9.75v.375c0 .621.504 1.125 1.125 1.125h2.25c.621 0 1.125-.504 1.125-1.125V3h1.125c.621 0 1.125.504 1.125 1.125v15.75c0 .621-.504 1.125-1.125 1.125h-6.75A1.125 1.125 0 0 1 7.5 19.875V4.125Z"
                            clip-rule="evenodd" />
                    </svg>

                    <span class="font-extrabold">Contact</span>

                </li>
            </ul>
        </nav>

        <div class="flex items-center justify-between p-2 mx-2 my-4 rounded-md border">
            <div class="flex flex-col">
                <h1 class="font-extrabold md:text-lg">Massay Bah</h1>
            <h1 class="font-extrabold md:text-lg">Software Engineer</h1>
            <h1 class="font-extrabold md:text-lg">Massay Bah</h1>
            </div>
            <img class="w-20 h-auto rounded-lg" alt="Massay Bah" src="/images/massaybah.jpeg" />
        </div>


        <div class="flex space-x-2 p-4 ">

            <div class="min-w-[40%] border min-h-full bg-gray-300 p-2 rounded-md">

                <h1 class="font-extralight text-center leading-6 text-2xl">Projects</h1>
                <ul>
                    <li v-for="(project, index) in projects" :key="index">
                        {{ project.name }}
                    </li>
                </ul>
            </div>

            <div class="min-w-[40%] border min-h-full  bg-gray-300 p-2 rounded-md">

                <h1 class="font-extralight text-center leading-6 text-2xl">Programing Languages</h1>
                <ul>
                    <li v-for="(language, index) in programmingLanguages" :key="index">
                        {{ language.name }}
                    </li>
                </ul>
            </div>

        </div>







    </div>
</template>

<style scoped></style>
