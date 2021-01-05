<template>
  <div>
    <div class="bg-gray-100 p-16 mx-auto h-auto">
    <!-- Header -->
    <div class="grid md:grid-cols-1 rounded-xl text-white shadow-lg" style="background:url(assets/images/bg.jpg); background-size:cover">
      <div class="flex flex-col flex-wrap justify-center items-center py-10">
        <img class="inline-block h-60 w-60 rounded-full shadow-xl" src="~assets/images/foto.jpg" alt="">
        <div class="text-center">
          <h1 class="text-3xl pt-10 font-bold">Bayu Rasukma Raga</h1>
          <h1 class="text-xl pt-5 font-thin">Software Developer</h1>
        </div>
      </div>
    </div>


    <!-- Skill and Bio -->
     <div class="grid md:grid-cols-2 mt-10 gap-10">
       <div>
         <p>
           <b>07 September 1998</b> <br>
           Ds. Telukagung, Blok Sindu Praja, RT01B/RW01, No. 41, Kec/Kab Indramayu, Prov. Jawa Barat, Indonesia.
         </p>

         <p class="mt-10">I am a software developer who wants to change the world from the shadows. Maybe not the whole world, but at least in a smaller environment that could make a difference like the gravel causing an avalanche of mountains.</p>
       </div>

       <div>
         <div class="bg-white shadow-lg rounded-lg p-10">
           <h2 class="font-bold text-lg mb-5"><i class='bx bx-atom'></i> Skills</h2>
           <ul>
             <li class="flex flex-row flex-wrap justify-between">
               <a>PHP</a>

               <div class="w-2/6 pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-gray-200">
                  <div style="width:96%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-gray-700"></div>
                </div>
              </div>
             </li>
             <li class="flex flex-row flex-wrap justify-between">
               <a>JavaScript</a>

               <div class="w-2/6 pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-gray-200">
                  <div style="width:90%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-gray-700"></div>
                </div>
              </div>
             </li>
             <li class="flex flex-row flex-wrap justify-between">
               <a>Java</a>

               <div class="w-2/6 pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-gray-200">
                  <div style="width:40%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-gray-700"></div>
                </div>
              </div>
             </li>
             <li class="flex flex-row flex-wrap justify-between">
               <a>SQL</a>

               <div class="w-2/6 pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-gray-200">
                  <div style="width:80%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-gray-700"></div>
                </div>
              </div>
             </li>
             <li class="flex flex-row flex-wrap justify-between">
               <a>NoSQL</a>

               <div class="w-2/6 pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-gray-200">
                  <div style="width:70%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-gray-700"></div>
                </div>
              </div>
             </li>
           </ul>
         </div>
       </div>

       <div>
         <h2 class="font-bold text-lg mb-5"><i class='bx bxs-star'></i> Certification</h2>
           <ul>
             <li><a target="_blank" href="https://drive.google.com/file/d/15OcuLwUXQldxIpNrt0UfQ6yP9iEA7PsX/view?usp=sharing">SKKNI Programming</a> <i class='bx bx-link-external' ></i></li>
             <li><a target="_blank" href="https://drive.google.com/file/d/1feUCQEWtt5bMSfBVHFfh3A9Bl9LfAh9x/view?usp=sharing">SKKNI Database Programming</a> <i class='bx bx-link-external' ></i></li>
           </ul>
       </div>

       <div>
         <h2 class="font-bold text-lg mb-5"><i class='bx bxs-school'></i> Education</h2>
           <ul>
             <li>(2016-2019) <br><b>Politeknik Negeri Indramayu (Informatics Engineering)</b></li>
             <li class="mt-2">(2014-2016) <br><b>SMK Negeri 1 Indramayu (Multimedia)</b></li>
             <li class="mt-2">(2012-2014) <br><b>SMP N 1 Indramayu</b></li>
             <li class="mt-2">(2006-2012) <br><b>MI GUPPI Telukagung</b></li>
           </ul>
       </div>

       <div>
         <h2 class="font-bold text-lg mb-5"><i class='bx bx-building'></i> Experience</h2>
           <ul class="border-l-4 border-dotted border-gray-700 pl-10">
             <li>
               <h3 class="font-bold">PT Afedigi Indonesia</h3>
               <p class="font-thin italic">Senior Programmer</p>
             </li>
             <li>
               <h3 class="font-bold">PT Cyber Blitz Nusantara</h3>
               <p class="font-thin italic">Senior Programmer</p>
             </li>
             <li>
               <h3 class="font-bold">PT Cyber Blitz Nusantara</h3>
               <p class="font-thin italic">Junior Programmer</p>
             </li>
               <h3 class="font-bold">Roketin (Intern)</h3>
               <p class="font-thin italic">Web Developer</p>
           </ul>
       </div>
       <div>
         <div class="bg-white shadow-lg rounded-lg p-10 text-center">
           <h2 class="font-bold text-lg mb-5">Technology that i used</h2>
           <img class="w-auto" src="~assets/images/technology.png" alt="">
         </div>
       </div>



     </div>
    </div>

     <!-- Portofolio -->
    <div class="text-center p-16 bg-gray-300">
      <h1 class="font-bold text-2xl">Portofolio</h1>
      <div class="grid md:grid-cols-4 mt-10 gap-6">
       <div class="bg-white shadow-lg rounded-lg text-left">
          <img class="rounded-t-lg" src="~assets/images/jarvis.png">
          <div class="p-5">
            <h4 class="font-bold text-xl mb-2">Jarvis</h4>
            <p class="text-sm mb-5">Application for collecting employees data from subsidiary</p>

            <a class="font-thin text-sm"><i class='bx bxs-institution'></i> PT Telkom Indonesia</a>
          </div>
       </div>
       <div class="bg-white shadow-lg rounded-lg text-left">
          <img class="rounded-t-lg" src="~assets/images/greatpertamina.png">
          <div class="p-5">
            <h4 class="font-bold text-xl mb-2">I-Am Pertamina</h4>
            <p class="text-sm mb-5">HR Application for Job Promotion and Job Bidding</p>

            <a class="font-thin text-sm"><i class='bx bxs-institution'></i> PT Pertamina</a>
          </div>
       </div>
       <div class="bg-white shadow-lg rounded-lg text-left">
          <img class="rounded-t-lg" src="~assets/images/JMLI.png">
          <div class="p-5">
            <h4 class="font-bold text-xl mb-2">JM Click 2.0 (Learning)</h4>
            <p class="text-sm mb-5">Admin Panel for JM Click 2.0 Learning Module</p>

            <a class="font-thin text-sm"><i class='bx bxs-institution'></i> Jasa Marga Learning Institute</a>
          </div>
       </div>
       <div class="bg-white shadow-lg rounded-lg text-left">
          <img class="rounded-t-lg" src="~assets/images/togas.png">
          <div class="p-5">
            <h4 class="font-bold text-xl mb-2">Togas</h4>
            <p class="text-sm mb-5">Application for Audit and Monitoring SPBU Channel</p>

            <a class="font-thin text-sm"><i class='bx bxs-institution'></i> PT Pertamina</a>
          </div>
       </div>
       <div class="bg-white shadow-lg rounded-lg text-left">
          <img class="rounded-t-lg" src="~assets/images/bsm.png">
          <div class="p-5">
            <h4 class="font-bold text-xl mb-2">Software Excelent Report</h4>
            <p class="text-sm mb-5">Monitoring Branch Application</p>

            <a class="font-thin text-sm"><i class='bx bxs-institution'></i> Bank Mandiri Syariah</a>
          </div>
       </div>
       <div class="bg-white shadow-lg rounded-lg text-left">
          <img class="rounded-t-lg" src="~assets/images/serdadu.png">
          <div class="p-5">
            <h4 class="font-bold text-xl mb-2">SERDADU Pancasila</h4>
            <p class="text-sm mb-5">Reporting Application for Pancasila Activities (Ministry)</p>

            <a class="font-thin text-sm"><i class='bx bxs-institution'></i> Badan Pembinaan Ideologi Pancasila</a>
          </div>
       </div>
       <div class="bg-white shadow-lg rounded-lg text-left">
          <img class="rounded-t-lg" src="~assets/images/simpulkendali.png">
          <div class="p-5">
            <h4 class="font-bold text-xl mb-2">Simpul Kendali</h4>
            <p class="text-sm mb-5">Reporting Application for Pancasila Activities (Regional Goverment)</p>

            <a class="font-thin text-sm"><i class='bx bxs-institution'></i> Badan Pembinaan Ideologi Pancasila</a>
          </div>
       </div>
       <div class="bg-white shadow-lg rounded-lg text-left">
          <img class="rounded-t-lg" src="~assets/images/taxar.png">
          <div class="p-5">
            <h4 class="font-bold text-xl mb-2">Tax AR Sharp</h4>
            <p class="text-sm mb-5">Application for Tax Aging Report</p>

            <a class="font-thin text-sm"><i class='bx bxs-institution'></i> PT Sharp Electronics Indonesia</a>
          </div>
       </div>
       <div class="bg-white shadow-lg rounded-lg text-left">
          <img class="rounded-t-lg" src="~assets/images/i-monev.png">
          <div class="p-5">
            <h4 class="font-bold text-xl mb-2">i-Monev</h4>
            <p class="text-sm mb-5">Application for Monitoring and Evaluation Regional Office</p>

            <a class="font-thin text-sm"><i class='bx bxs-institution'></i>Badan Nasional Pengelola Perbatasan</a>
          </div>
       </div>
     </div>
    </div>

    <div class="bg-gray-100 p-16 mx-auto h-auto grid md:grid-cols-3">
      <div>
        <h1 class="font-bold text-2xl mb-5">Contact Me</h1>
        <ul>
          <li><a href="https://web.facebook.com/bayu.rasukmaraga/" target="_blank"><i class='bx bxl-facebook-circle'></i> Bayu Rasukma Raga</a></li>
          <li><a href="https://www.instagram.com/bey_raga/" target="_blank"><i class='bx bxl-instagram' ></i> bey_raga</a></li>
          <li><a href="#"><i class='bx bx-mail-send' ></i> bayurasukmaraga@gmail.com</a></li>
        </ul>
      </div>
      <div class="flex flex-col flex-wrap justify-center items-center">
        <h1 class="text-9xl"><i class='bx bxl-github' ></i></h1>
        <a href="https://github.com/BeyKun" target="_blank" class="mb-8">github.com/BeyKun</a>

        &copy; 2020 Beykun
      </div>
      <div class="sm:text-right">
        <h1 class="font-bold text-2xl mb-5">Pages</h1>
        <ul class="mb-10">
          <li>About</li>
          <li>Blog</li>
          <li>Portofolio</li>
        </ul>


      </div>
      <div>

      </div>
    </div>
  </div>
</template>

<script>
  import Modal from '../components/Modal'
  import Navbar from '../components/Navbar'
  export default {
    components: {
      Modal,
      Navbar
    },
    data() {
      return {
        open: false,
        portofolio: [
          {
            name: 'Jarvis',
            by: 'PT Telkom Indonesia',
            description: 'Application for collecting employees data from subsidiary',
            image: '/assets/images/jarvis.png'
          },
          {
            name: 'I-Am Pertamina',
            by: 'PT Pertamina',
            description: 'HR Application for Job Promotion and Job Bidding',
            image: '/assets/images/greatpertamina.png'
          },
          {
            name: 'JM Click 2.0 (Learning)',
            by: 'Jasa Marga Learning Institute',
            description: 'Admin Panel for JM Click 2.0 Learning Module',
            image: '/assets/images/jmli.png'
          },
          {
            name: 'Togas',
            by: 'PT Pertamina',
            description: 'Application for Audit and Monitoring SPBU Channel',
            image: '/assets/images/togas.png'
          },
          {
            name: 'Software Excelent Report',
            by: 'Bank Mandiri Syariah',
            description: 'Monitoring Branch Application',
            image: '/assets/images/bsm.png'
          },
          {
            name: 'SERDADU Pancasila',
            by: 'Badan Pembinaan Ideologi Pancasila',
            description: 'Reporting Application for Pancasila Activities (Ministry)',
            image: '/assets/images/serdadu.png'
          },
          {
            name: 'Simpul Kendali',
            by: 'Badan Pembinaan Ideologi Pancasila',
            description: 'Reporting Application for Pancasila Activities (Regional Goverment)',
            image: '/assets/images/simpulkendali.png'
          },
          {
            name: 'Tax AR Sharp',
            by: 'PT Sharp Electronics Indonesia',
            description: 'Application for Tax Aging Report',
            image: '/assets/images/taxar.png'
          },
          {
            name: 'i-Monev',
            by: 'Badan Nasional Pengelola Perbatasan',
            description: 'Application for Monitoring and Evaluation Regional Office',
            image: '/assets/images/i-monev.png'
          }
        ]
      }
    },
  }

</script>

<style>

</style>
