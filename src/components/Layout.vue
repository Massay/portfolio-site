<script setup>

const projects = [
    {
        name: 'Fuel Pump Management System',
        summary: "Petrol Station Management software to track and monitor sales activities across service station. This app provides a centralize database to monitor sales activities across service stations.",
        folder: "fuel",
        images: [


            {
                name: "",
                logo: "current-page-analysis-per-station.png"
            },
            {
                name: "",
                logo: "current-page-analysis-per-station-variance-checker.png"
            },
            {
                name: "",
                logo: "creditsales.png"
            },
            {
                name: "",
                logo: "home-page.png"
            },

            {
                logo: "customer_report.png"
            }, {
                logo: "deliveries.png"
            },
            {
                logo: "entire-day-report.png"
            },
            {
                logo: "fuelpump-menu-for-station-supervisor-menu-items.png"
            },
            {
                name: "",
                logo: "cheque_sales.png"
            },
            {
                logo: "FuelTransfer.png"
            },
            {
                logo: "postpaid.png"
            },
        ]
    },
    {
        name: 'Medical Insurance Management System',
        summary: "An in-house medical insurance management system for staff is a tailored solution designed to manage and streamline the health insurance benefits provided to employees within an organization. This system helps in administering, tracking, and optimizing the medical insurance plans and claims for staff, ensuring that they receive the necessary support and coverage efficiently",
        folder: "insurance",
        features: [
            {
                name: 'Policy Administration',
            },
            {
                name: 'Claims Management'
            },
            {
                name: 'Employee Portal'
            },
            {
                name: 'Billing and Payments'
            },
            {
                name: 'Provider Network Management'
            },
            {
                name: 'Reporting and Analytics'
            },
            {
                name: 'Compliance and Security'
            },
            {
                name: 'Integration and Accessibility'
            }
        ],
        images: [
            {
                name: "Login Page",
                logo: "loginPage.png"
            },
            {
                name: "Dashboard View",
                logo: "dashboardView.png"
            },
            {
                name: "Clinics",
                logo: "clinics_list.png"
            },

            {
                name: "Visits",
                logo: "visits_List.png"
            }
        ]
    },
    {
        name: 'Visitors Log Management System',
        summary: "",
        images: [

        ]
    },
    {
        name: 'WARGA WARGA E-Sports Platform for Gambia Footballers',
        summary: "",
        images: [

        ]
    },
    {
        name: 'Pluto Integrated Solution',
        summary: "",
        images: [

        ]
    },
    {
        name: 'Coupon Management System  system',
        summary: "",
        images: [

        ]
    }
]

const programmingLanguages = [
    {
        name: 'C#',
        logo: 'icons8-c-64.png'
    },
    {
        name: "Php",
        logo: 'icons8-php-48.png'
    },
    {
        name: "Laravel",
        logo: 'icons8-laravel-48.png'
    },
    {
        name: "VueJs",
        logo: 'icons8-vuejs-64.png'
    },
    {
        name: 'Python',
        logo: 'icons8-python-48.png'
    },
    {
        name: 'Jenkins',
        logo: 'icons8-jenkins-48.png'
    },
    {
        name: "Html & Css",
        logo: 'icons8-tailwindcss-48.png'
    },
    {
        name: "Java",
        logo: 'icons8-java-64.png'
    },
    {
        name: "DevOps",
        logo: "icons8-devops-60.png"
    },
    {
        name: "Git",
        logo: "icons8-git-100.png"
    },
    {
        name: "Flutter",
        logo: "icons8-flutter-48.png"
    },
    {
        name: "Kotlin",
        logo: 'icons8-kotlin-48.png'
    },
    {
        name: "Mysql",
        logo: "icons8-mysql-48.png"
    },
    {
        name: "Javascript",
        logo: 'icons8-javascript-48.png'
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


const education = [
    {
        name: "Computer Science",
        university: "University of The Gambia",
        timeFrame: {
            from: 'September, 2011',
            to: 'January, 2014'
        },

    }
]

const experience = [
    {
        company: "GICTA",
        title: "Manager for Data and Application Services",
        timeFrame: {
            from: 'March, 2024',
            to: 'curent'
        },
        responsibilities: [
            {
                title: 'hello world'
            },
            {
                title: 'hello world 1'
            }
        ]
    },
    {
        company: "GNPC",
        title: "IT Manager",
        timeFrame: {
            from: 'April, 2021',
            to: 'May 2024'
        },
        responsibilities: [
            {
                title: 'hello world'
            },
            {
                title: 'hello world 1'
            }
        ]
    },
    {
        company: "GNPC",
        title: "Assistant IT Manager",
        timeFrame: {
            from: 'January, 2019',
            to: 'April 2021'
        },
        responsibilities: [
            {
                title: 'hello world'
            },
            {
                title: 'hello world 1'
            }
        ]
    },
    {
        company: "GNPC",
        title: "Senior IT Admin",
        timeFrame: {
            from: 'December, 2017',
            to: 'December 2019'
        },
        responsibilities: [
            {
                title: 'hello world'
            },
            {
                title: 'hello world 1'
            }
        ]
    },
    {
        company: "Volo Africa",
        title: "Software Developer",
        timeFrame: {
            from: 'October, 2015',
            to: 'October 2017'
        },
        responsibilities: [
            {
                title: 'hello world'
            },
            {
                title: 'hello world 1'
            }
        ]
    },
    {
        company: "Pristine Consulting",
        title: "Software Developer",
        timeFrame: {
            from: 'April, 2015',
            to: 'September 2017'
        },
        responsibilities: [
            {
                title: 'hello world'
            },
            {
                title: 'hello world 1'
            }
        ]
    },
    {
        company: "Insist Global",
        title: "Software Developer Intern",
        timeFrame: {
            from: 'April, 2013',
            to: 'December 2013'
        },
        responsibilities: [
            {
                title: 'hello world'
            },
            {
                title: 'hello world 1'
            }
        ]
    }
]

</script>

<template>
    <div class="flex min-w-full min-h-screen">
        <div class="w-[100%] lg:w-[75%] bg-gray-300 p-2 space-y-4 lg:p-2 md:space-y-0">
            <div class="flex justify-between">
                <div
                    class="flex flex-1 justify-between  lg:justify-start p-2 mx-2  rounded-md  bg-sky-900 text-gray-50">
                    <img class="w-20 h-auto md:w-28  md:h-28 rounded-lg" alt="Massay Bah"
                        src="/images/massaybah.jpeg" />
                    <div
                        class="flex flex-col ml-2  rounded-md px-1 md:items-start md:justify-start items-start justify-center">
                        <h1 class="font-bold text-sm md:text-lg">Massay Bah</h1>
                        <h1 class="font-semibold text-sm md:text-lg">Software Engineer</h1>
                        <h1 class="font-semibold text-sm md:text-lg">Banjul, The Gambia</h1>
                        <h1 class="font-semibold text-sm md:text-lg">(+220) 3199935 / 2565405</h1>
                    </div>
                </div>

                <div class="lg:flex-1 border-2 rounded-md hidden bg-sky-900 lg:grid place-content-center">
                    <div class="flex  justify-between space-x-2">
                        <div class="flex space-x-2">
                            <button class="px-8 bg-gray-50 py-2 flex items-center font-bold gap-2 rounded-sm">

                                <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 0 0 .75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 0 0-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0 1 12 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 0 1-.673-.38m0 0A2.18 2.18 0 0 1 3 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 0 1 3.413-.387m7.5 0V5.25A2.25 2.25 0 0 0 13.5 3h-3a2.25 2.25 0 0 0-2.25 2.25v.894m7.5 0a48.667 48.667 0 0 0-7.5 0M12 12.75h.008v.008H12v-.008Z" />
                                    </svg>
                                </span>Hire Me</button>
                            <button class="px-8 bg-gray-50 flex items-center font-bold gap-2 rounded-sm">
                                <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M21.75 9v.906a2.25 2.25 0 0 1-1.183 1.981l-6.478 3.488M2.25 9v.906a2.25 2.25 0 0 0 1.183 1.981l6.478 3.488m8.839 2.51-4.66-2.51m0 0-1.023-.55a2.25 2.25 0 0 0-2.134 0l-1.022.55m0 0-4.661 2.51m16.5 1.615a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V8.844a2.25 2.25 0 0 1 1.183-1.981l7.5-4.039a2.25 2.25 0 0 1 2.134 0l7.5 4.039a2.25 2.25 0 0 1 1.183 1.98V19.5Z" />
                                    </svg>

                                </span>

                                Email</button>
                        </div>

                        <div class="flex space-x-2">
                            <button class="px-8 bg-gray-50 py-2 flex items-center gap-2 font-bold rounded-sm">
                                <span><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                        stroke-width="1.5" stroke="currentColor" class="size-6">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 0 0 2.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 0 1-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 0 0-1.091-.852H4.5A2.25 2.25 0 0 0 2.25 4.5v2.25Z" />
                                    </svg>
                                </span>
                                Contact</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="py-2 flex flex-col space-y-2">
                <div class="border bg-gray-50 p-2 rounded-md">
                    <h1 class="font-semibold text-center leading-6 lg:text-2xl text-lg">Projects</h1>
                    <div v-for="(project, index) in projects" :key="index"
                        class="lg:text-lg text-sm leading-8 border my-4 p-2">
                        <h1 class="font-mono">[{{ index + 1 }}] <span class="font-bold"> {{ project.name }}</span> </h1>
                        <p class="text-xs lg:text-sm">{{ project.summary }}</p>
                        <div class="grid grid-cols-1 lg:grid-cols-2 gap-2 lg:gap-4 p-2  overflow-hidden">
                            <div  v-for="(image) in project.images" class="flex-1 w-auto object-cover overflow-hidden">
                                <!-- <img
                                :src="'/portfolio-site/images/' + project.folder + '/' + image.logo"
                                class="object-fill w-auto h-auto rounded-md border" :alt="image.logo"> -->
                            </div>
                        </div>
                    </div>
                </div>

                <div class="border  bg-gray-50 p-2 rounded-md">
                    <h1 class="font-semibold text-center leading-6 lg:text-2xl text-lg my-8">Skills & programming
                        Languages</h1>

                    <div class="grid grid-cols-1 md:grid-cols-4 gap-1 xl:grid-cols-6 md:gap-4 lg:gap-2">
                        <div v-for="(project, index) in programmingLanguages" :key="index"
                            class="bg-slate-950 text-gray-50 rounded-md flex flex-col px-2 py-8 justify-center items-center">
                            <span>
                                <img :src="'/portfolio-site/images/' + project.logo" :alt="project.name">
                            </span>
                            <span class="font-bold"> {{ project.name }}</span>
                        </div>
                    </div>

                </div>
                <!-- <div class="  bg-gray-50 p-2 rounded-md">
                    <h1 class="font-semibold text-center leading-6 lg:text-2xl text-lg">Frameworks</h1>
                    <ul>
                        <li v-for="(project, index) in frameworks" :key="index">
                            {{ project.name }}
                        </li>
                    </ul>
                </div> -->
                <div class=" bg-gray-50 p-2 rounded-md">
                    <h1 class="text-center leading-6 lg:text-2xl text-lg my-2 font-semibold">Experience</h1>

                    <div class="flex flex-col gap-2">

                        <div v-for="(ex, index) in experience" :key="index" class="p-1 rounded-md">

                            <h1 class="font-semibold lg:text-2xl text-lg"> {{ ex.company }}</h1>
                            <h3> {{ ex.title }}</h3>
                            <h3> {{ ex.timeFrame.from }} - {{ ex.timeFrame.to }}</h3>

                            <h4 class="font-bold">Responsibilities</h4>
                            <ul>
                                <li v-for="(res, indexInner)  in ex.responsibilities" :key="indexInner">

                                    {{ res.title }}
                                </li>
                            </ul>
                        </div>

                    </div>



                </div>

            </div>


        </div>

        <div class="lg:w-[25%] p-2 lg:inline-block bg-gray-300 hidden md:fixed right-0 top-0">
                <div class="flex flex-col  justify-around h-screen gap-3 pt-1 pb-4 px-2">
                            <div class="bg-yellow-500 rounded-md flex-1">
                                Side A
                            </div>
                            <div class="bg-blue-500 rounded-md  flex-1">
                                Side B
                            </div>
                            <div class="bg-green-500 rounded-md flex-1">
                                Side C
                            </div>
                            <div class="bg-orange-500 rounded-md flex-1">
                                Side D
                            </div>
                </div>
        </div>

        <!-- <nav class="p-2 h-16">

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
        </nav> -->
        <!-- <div class="flex  justify-start p-2 mx-2  rounded-md border bg-blue-400">
            <img class="w-20 h-auto rounded-lg" alt="Massay Bah" src="/images/massaybah.jpeg" />
            <div class="flex flex-col ml-2  rounded-md px-1">
                <h1 class="font-extrabold md:text-lg">Massay Bah</h1>
                <h1 class="font-extralight md:text-lg">Software Engineer</h1>
                <h1 class="font-extralight md:text-lg">Banjul, The Gambia</h1>
            </div>
        </div>
        <div class="flex space-x-2 p-4 ">
            <div class="min-w-[40%] border min-h-full bg-gray-50 p-2 rounded-md">
                <h1 class="font-extralight text-center leading-6 text-2xl">Projects</h1>
                <ul>
                    <li v-for="(project, index) in projects" :key="index">
                        {{ project.name }}
                    </li>
                </ul>
            </div>
            <div class="min-w-[40%] border min-h-full  bg-gray-50 p-2 rounded-md">

                <h1 class="font-extralight text-center leading-6 text-2xl">Programing Languages</h1>
                <ul>
                    <li v-for="(language, index) in programmingLanguages" :key="index">
                        {{ language.name }}
                    </li>
                </ul>
            </div>
        </div> -->
    </div>
</template>

<style scoped></style>
