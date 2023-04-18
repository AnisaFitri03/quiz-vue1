<template>
    <div class="main-container">
     <div class="container-one">
       <div class="profile">
         <img src="../assets/fitri.jpg" alt="">
         <h2>Anisa Fitri</h2>
         <p>Teknik Informatika </p>
         <p>Universitas Islam Negeri Sultan Syarif Kasim</p>
       </div>
       <div class="sosial-links">
         
           <div class="link">
             <a href="https://www.instagram.com/anisaafitrii_03"><img src="../assets/Instagram.png" alt="" style="width:35px;height:35px;">
               <h3>Instagram</h3></a>
           </div>
           <div class="link">
             <a href="https://wa.me/qr/THYRYHC2HX2MN1"><img src="../assets/Whatsapp.png" alt="" style="width:35px;height:35px;">
               <h3>Whatsapp</h3></a>
           </div>
           <div class="link">
             <a href="https://t.me/Anisaachaniago"><img src="../assets/Telegram.png" alt="" style="width:35px;height:35px;">
               <h3>Telegram</h3></a>
           </div>
         
       </div>
     </div>
     <div class="container-two">
        <div class="about-me">
         <h2>My Biodata</h2>
         
           <p> Nama             : Anisa Fitri</p>
           <p> Jenis Kelamin    : Perempuan</p> 
           <p> Agama            : Islam</p>
           <p> Tempat/Tgl Lahir : Balam Sempurna/14 november 2003</p>
           <p> Status           : Mahasiswa</p>
           <p> Alamat           : Bagan Sinembah, Rokan Hilir</p>
           <p> Hobi             : Memasak</p>

           <p> "Pembelajaran tidak dapat dengan kebetulan, ia harus dicari dengan semangat dan dijalani dengan tekun" </p>
           <p> "Jangan malu dengan kegagalan, belajarlah darinya dan mulai lagi"</p>
           <p> "Sukses adalah sebuah perjalanan, bukan sebuah tujuan. Usaha sering lebih penting daripada hasilnya"</p>

        </div>
          
       <div class="tecnology-section">
         <div class="logo">
          <img src="../assets/javascript.jpg" alt="" style="width:70px;height:50px;">
          <img src="" alt="">
          </div> 
        </div>

        <div class="button-container">
           <div class="project-button">
             <a href="">Log in Project</a>
            </div>
            <div>
            </div>
          </div>
      </div>
    </div>
   </template>
     
   <script>
   
   </script>
     
   <style scoped>
     img{
       height: 30px;
     }
     .main-container{
       display: flex;
       flex-direction: row;
       background-color: rgb(171, 173, 172);
       border-radius: 70px;
       
     }
     .container-one{
       background: linear-gradient(rgba(17, 20, 18, 0.96), rgba(92, 99, 95, 0.9), rgba(63, 65, 65, 0.96)),center/cover no-repeat;
       padding: 2.5%;
       margin: 2%;
       color: antiquewhite;
       width: 30%;
       border-radius: 25px;
     }
   
     .profile img{
       background-color: rgb(195, 214, 208) ;
       height: 13rem;
       border-radius: 30%;
     }
     .link a{  
       text-decoration: none;
       color: rgb(7, 7, 7);
       font-size: 20px;
     }
     .link img{
       height: 13rem;
     }
     .container-two{
       background: linear-gradient(rgba(29, 31, 30, 0.96), rgba(49, 49, 49, 0.9), rgba(52, 53, 53, 0.96)),center/cover no-repeat;
       margin: 2.5%;
       margin-left: 2%;
       border-radius: 2%;
       color: rgb(214, 212, 210);
       width: 70%;
     }
     .about-me{
       text-align: left;
     }
     .logo img{
       height: 4rem;
     }
   
     .button-container{
       margin-top: 5px;
       display: flex;
       flex-direction: row;
       justify-content: center;
       align-items: center;
   
       
     }
   
     .project-button{
       background-color: rgb(0, 0, 0) ;
       border-radius: 25%;
       padding: 5px;
       margin: 6px;
     }
     .project-button a{
       text-decoration: none;
       color: rgb(255, 255, 255);
     }
   
   </style>
     