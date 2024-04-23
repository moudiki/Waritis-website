<script setup>

</script>
<template >
    <div class="w-[1440px] mx-auto mt-10 border-2  border-black relative">
        <header >
            <nav class="flex justify-between ">
                <NuxtLink to="/" class="cursor-pointer"><img src="~/assets/Logo.png " class="w-[134px] h-[60px] ml-[75px] cursor-pointer"></NuxtLink>
                
                <ul class="flex gap-4 mr-[75px] mt-3 cursor-pointer">
                    <NuxtLink>Accueil</NuxtLink>
                    <NuxtLink to="/expertise">Expertise</NuxtLink>
                    <NuxtLink>Realisations</NuxtLink>
                    <NuxtLink>Carriere</NuxtLink>
                    <NuxtLink>Qui sommes nous ?</NuxtLink>
                    <Nuxtlink> Contacts</Nuxtlink>
                    <NuxtLink>Actualites</NuxtLink>
                </ul>
            </nav>
        </header>
        <body>
            <img class="w-[1285px] h-[732px] ml-[153px] mt-5" src="~/assets/pic1.png "    alt="">
            <img class="w-[1285px] h-[732px] ml-[153px] mt-5 absolute top-[60px] " src="~/assets/Rectangle 144.png">
            <img class="w-[1285px] h-[732px] ml-[153px] mt-5 absolute top-[60px] mix-blend-hue" src="~/assets/Rectangle 145.png"> 

            <div class="w-[800px] flex bg-[#239596] text-white rounded-r-full absolute top-[750px] left-[310px]">
                <div class="pt-9 pb-9 pl-4 pr-4 ml-3">
                    <h4>CONSEIL</h4>
                    <p class="text-sm">Faire l'audit de la capacite<br>d'inovation et guider</p>
                </div>
                <div class="pt-9 pb-9 pl-4 pr-4 ml-3">
                    <h4>TECHNOLOGIE</h4>
                    <p class="text-sm">Developper des logiciels innovants,<br>Digital/Data/Cloud.</p>
                </div>
                <div class="pt-9 pb-9 pl-4 pr-4 ml-3">
                    <h4>TRANSFORMATION</h4>
                    <p class="text-sm">Accelerer la transformation de votre <br>organisation, votre culture ou votre IT.</p>
                </div>
            </div>

            <div class="bg-[#002626] p-[80px] mt-[100px] flex relative h-[673px]">
                <img src="~/assets/Group 1386.png" class=" absolute top-[300px] left-[0.3px]">
                <img src="~/assets/Group 1380.png" class=" opacity-10 absolute top-[80px] left-[210px]">
               
                <img src="~/assets/Mask Group.png" class=" ml-[735px]">
                <img src="~/assets/T 1.png" class="absolute top-[43px] left-[930px]">
                <div class="absolute top-[100px] left-[170px] text-white p-5">
                    <div class="w-[10px] h-[59px] bg-[#31B956] absolute top-[15px] left-0.5"></div>
                    <div class="ml-5">
                        <h1 class="text-[30px]">Nous sommes des <br>profesionnels passionnes</h1>
                        <p class="mt-5 text-[16px]">
                            des passionnes qui sont convaincus que la tech est une <br>
                            source de progres pour la societe. Nous accompagnons <br>
                            la transformation numerique des entreprises, en les <br>
                            aidant a concevoir leur strategie et a deployer leur <br>
                            roadmap a l'echelle, afin de delivrer rapidement la <br>
                            valeur attendue.
                        </p>

                    </div>
                    <button class="w-[201px] h-[41px] text-white border-[1px] border-white bg-none rounded-[36px] absolute left-[200px] top-[400px]"
                    >Savoir plus</button>
                </div>
                
            </div>
            <div class="w-[800px] h-[115px] bg-[#239596] text-white mt-[80px] rounded-[70px] text-center m-auto p-9 ">
                <span >Nos Services</span>
            </div>
            <div class="grid grid-cols-3 gap-5  w-[800px] h-[600px] mt-9 m-auto">
                <div class=" bg-[#FAFAFA] rounded-[16px] hover:border-1 hover:border-[#31B956]"> 
                    <p>Analyses des donnees</p>
                </div>
                <div class=" bg-[#FAFAFA] rounded-[16px]"> 
                    <p>Cloud Computing</p>
                </div>
                <div class=" bg-[#FAFAFA] rounded-[16px]">
                    <p>Deploiement</p>
                 </div>
                <div class="  bg-[#FAFAFA] rounded-[16px]">
                    <p>Analyses des donnees</p>    
                </div>
                <div class="  bg-[#FAFAFA] rounded-[16px]"> 
                    <p>Cloud Computing</p>
                </div>
                <div class="  bg-[#FAFAFA] rounded-[16px]">
                    <p>Deploiement</p>    
                </div>
                
            </div>
            <div class="w-full mt-10 bg-[#F3F6F7] p-10">
                <div class="flex ml-[200px] gap-4">
                    <div class="w-[10px] h-[59px] bg-[#31B956] "></div>
                    <h1 class="text-[#239596] mt-3 text-3xl ">Nos Clients et partenaires</h1>
                </div>
                <p class="ml-[200px] mt-8">
                    Nous vous accompagnons a chaque etape du processus avec une vision long terme, en commencant par des conseil jusqu'a <br>
                    la realisation du produit ou du service. Quel que soit le secteur d'activite, nous considerons nos projets comme des relations <br>
                    humaines avant tout. Voici quelques-une de nos relations.
                </p>

                    
            </div>
            <div class="bg-[#002626] rounded-[20px] flex justify-between p-10 w-[1243px] m-auto mt-10">
                <div class="text-white">
                    <h1 class="text-[50px] mt-5">Vous aimez ce que nous faisons ?<br><span class="text-[20px] mb-10">Contactez nous</span> 
                    </h1>
                   
                    
                </div>
                <button class="bg-white rounded-[8px] h-[60px] p-5 mt-auto mb-auto " >Demandez des conseils</button>
            </div>
            <div class="mt-20 w-full">
                <h1 class="text-[#239596] text-[50px] m-auto text-center">Notre equipe</h1>
                <div class="flex gap-36 m-auto ml-44 mt-20">
                    <div class="relative cursor-pointer">
                        <img src="~/assets/John.png" alt="" class="">
                        <div class=" absolute top-0 w-[100%] h-[100%] rounded-full opacity-0 hover:opacity-100  hover:bg-gradient-to-b from-transparent to-[#5239FA]">
                            <img src="~/assets/Socials.png" class="mt-28 ml-11">
                    
                        </div>
                    </div>
                    <div class=" relative cursor-pointer">
                        <img src="~/assets/Simon.png">
                        <div class=" absolute top-0 w-[100%] h-[100%] rounded-full opacity-0 hover:opacity-100 hover:bg-gradient-to-b from-transparent to-[#5239FA]">
                            <img src="~/assets/Socials.png" class="mt-28 ml-11">
                    
                        </div>
                    </div>
                    <div class="relative cursor-pointer">  
                        <img src="~/assets/Paul.png" >
                        <div class=" absolute top-0 w-[100%] h-[100%] rounded-full opacity-0 hover:opacity-100 hover:bg-gradient-to-b from-transparent to-[#5239FA] ">
                            <img src="~/assets/Socials.png" class="mt-28 ml-11">
                    
                        </div>
                    </div>
                    <div class="relative cursor-pointer">
                        <img src="~/assets/Sarah.png" alt="">
                        <div class=" absolute top-0 w-[100%] h-[100%] rounded-full opacity-0 hover:opacity-100 hover:bg-gradient-to-b from-transparent to-[#5239FA]">
                            <img src="~/assets/Socials.png" class="mt-28 ml-11">
                    
                        </div>
                    </div>
                </div>
                
            </div>

            <div class="w-[1246px] h-[798px] m-auto  mt-48 relative">
                <img src="~/assets/woman-writing.png" class="h-[798px] ">
                <img src="~/assets/Rectangle 144 (1).png" class="w-[1246px] h-[798px] absolute top-0 ">
                <img src="~/assets/Background.png" class="w-[1246px] h-[798px] absolute top-0 mix-blend-hue">
                <div class=" absolute flex top-0 text-white h-full">
                    <div class="w-[50%]  p-16 mt-[40px]">
                        <h1 class="text-center text-[52px]">Beneficiez de nos conseils<br> faites partir de la transformation</h1>
                        <p class="text-center mt-24">Lorem ipsum dolor sit amet consectetur adipisicing elit. At quaerat excepturi, ducimus culpa officia assumenda a est vel ipsam incidunt optio soluta perferendis atque facere natus sequi. Nesciunt, non expedita.</p>
                    </div>
                    <form class=" w-[50%] bg-[#24A1A2] h-full p-20">
                        <h1 class="text-center text-4xl mt-8">Envoyez nous un mail</h1>
                        <p class="text-center mt-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias, in perspiciatis que do machin.</p>
                        <input type="text" placeholder="Votre nom" class=" w-full mt-10 p-5 bg-[#24A1A2] border-2 border-white rounded-[5px]">
                        <input type="email" placeholder="email" class="w-full mt-10 p-5 bg-[#24A1A2] border-2 border-white rounded-[5px]">
                        <textarea placeholder="votre message" rows="5" cols="50" class="w-full mt-10 bg-[#24A1A2] border-2  border-white rounded-[5px] p-5"></textarea>
                        <button class="w-full bg-white text-black  mt-10 p-5 rounded-[41px]">Envoyez</button>
                    </form>
                </div>
                
            </div>
            <div class="w-[1246px]  m-auto   mt-40 flex gap-24 ">
                <div class="mt-3 ">
                    <h1 class="text-[#239596] text-[42px]">Frequently asked <br>questions</h1>
                    <p class="text-[#239596] text-[18px]">Contact us for more info</p>
                </div>
                
                 <div class="relative   w-[66%]">
                        <div class="mb-8 relative">
                            <input type="checkbox" class="appearance-none peer" id="q1">
                        
                            <label for="q1" class="flex  gap-20 after:absolute after:content-['+'] after:right-0 after:top-7 after:text-[20px]   peer-checked:after:rotate-45 
                            cursor-pointer"  >
                                <h1 class="text-[28px] text-[#239596]">01</h1> 
                                <h1 class="text-[28px]  ">How much time does it take?</h1>
                        
                            </label>
                            <p class="h-0 overflow-hidden peer-checked:h-full ml-28 text-[20px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium<br> amet numquam fugit rem.</p>
 
                        </div>
                        <div class="border-t-2 mb-8 relative">
                            <input type="checkbox" class="appearance-none peer" id="q2">
                        
                            <label for="q2" class="flex  gap-20 after:absolute after:content-['+'] after:right-0 after:top-7 after:text-[20px]   peer-checked:after:rotate-45 
                            cursor-pointer"  >
                                <h1 class="text-[28px] text-[#239596]">02</h1> 
                                <h1 class="text-[28px]  ">How much time does it take?</h1>
                        
                            </label>
                            <p class="h-0 overflow-hidden transition ease-in-out duration-5000 peer-checked:h-full ml-28 text-[20px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium<br> amet numquam fugit rem.</p>
 
                        </div>
                        <div class="border-t-2 mb-8 relative">
                            <input type="checkbox" class="appearance-none peer" id="q3">
                        
                            <label for="q3" class="flex  gap-20 after:absolute after:content-['+'] after:right-0 after:top-7 after:text-[20px]   peer-checked:after:rotate-45 
                            cursor-pointer"  >
                                <h1 class="text-[28px] text-[#239596]">03</h1> 
                                <h1 class="text-[28px]  ">How much time does it take?</h1>
                        
                            </label>
                            <p class="h-0 overflow-hidden peer-checked:h-full ml-28 text-[20px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium<br> amet numquam fugit rem.</p>
 
                        </div>
                        <div class="border-t-2 mb-8 relative">
                            <input type="checkbox" class="appearance-none peer" id="q4">
                        
                            <label for="q4" class="flex  gap-20 after:absolute after:content-['+'] after:right-0 after:top-7 after:text-[20px]   peer-checked:after:rotate-45 
                            cursor-pointer"  >
                                <h1 class="text-[28px] text-[#239596]">04</h1> 
                                <h1 class="text-[28px]  ">How much time does it take?</h1>
                        
                            </label>
                            <p class="h-0 overflow-hidden peer-checked:h-full ml-28 text-[20px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium<br> amet numquam fugit rem.</p>
 
                        </div>
                        <div class="border-t-2 relative">
                            <input type="checkbox" class="appearance-none peer" id="q5">
                        
                            <label for="q5" class="flex  gap-20 after:absolute after:content-['+'] after:right-0 after:top-7 after:text-[20px]   peer-checked:after:rotate-45 
                            cursor-pointer"  >
                                <h1 class="text-[28px] text-[#239596]">05</h1> 
                                <h1 class="text-[28px]  ">How much time does it take?</h1>
                        
                            </label>
                            <p class="h-0 overflow-hidden peer-checked:h-full ml-28 text-[20px]">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium<br> amet numquam fugit rem.</p>
 
                        </div>
                                               
                    </div >
                    
                    
                

            </div>
            

            
        </body>
        <footer class="mt-20 bg-[#002626] text-white px-20 py-7">

                <div class="flex justify-between mt-5">
                    <img src="~/assets/Logo2.png" alt="">
                    <p class="mt-5 mr-28">We are information Technologists</p>
                </div>
                <div class="mt-10 flex justify-between">
                    <img src="~/assets/Social_Logo.png" alt="">
                    <hr class="w-[450px]">
                </div>
                <div class="flex gap-40 px-10 text-[13px] ml-16 mt-9">
                    <div class="w-[15%] ">
                        Cabinet de conseil et d'expertises en technoligie, international et independant. ippon accompagne la transformation numerique des entreprises, en les aidant a concevoir leur strategie et a deployer 
                        leur roadmap a l'echelle,afin de delivrer rapidement la valeur attendue

                    </div>
                    <div>
                        <ul>
                            <li>ReactJS Developers</li>
                            <li class="mt-2">AngularJS Developers</li>
                            <li class="mt-2">NodeJS Developers</li>
                            <li class="mt-2">Android Developers</li>
                            <li class="mt-2">iOS Developers</li>


                        </ul>
                        
                    </div>
                    <div>
                        <ul>
                            <li>Qui sommes-nous?</li>
                            <li class="mt-2"> Communaute</li>
                            <li class="mt-2">Blog</li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <li>Informations legales</li>
                            <li class="mt-2"> Conditions generales d'utilisation</li>
                            <li class="mt-2"> Politique de confidentialite</li>
                            <li class="mt-2">Politique cookies</li>
                            <li class="mt-2">Gestion des cookies</li>
                            <li class="mt-2">Index egalite</li>
                        </ul>
                    </div>
                </div>
        
            <hr class="mt-5">
            <div class="mt-3 m-auto  w-fit">
                <p> @ 2022 Hellomercato-Afrologix</p>
            </div>
            
        </footer>

    </div>
    
</template>

<style >
    *{
        margin: 0;
        padding: 0;
    }
</style>