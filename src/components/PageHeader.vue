<template>
<div>
            <div class="d-flex justify-content-between centrale">
               <div class="dropp">
                           <div class="dropdown">
                     <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                        English
                     </button>
                     <ul class="dropdown-menu">
                        <li><button class="dropdown-item" type="button">Altra lingua</button></li>
                        <li><button class="dropdown-item" type="button">Altra lingua</button></li>
                        <li><button class="dropdown-item" type="button">Altra lingua</button></li>
                        <li><button class="dropdown-item" type="button">Altra lingua</button></li>
                        <li><button class="dropdown-item" type="button">Altra lingua</button></li>
                     </ul>
                     </div>
               </div>
               <div class="linkk">
                  <ul>
                        <a href="">Courses</a>
                        <a href="">Zoom</a >
                        <a href="">Pages</a >
                        <a href="">Bundles</a >
                        <a href="">Course Formats</a >
                        <a href=""> Add Course</a >
                        <a href="">Demos</a >
                        <a href=""><font-awesome-icon icon="fa-brands fa-twitter" />?</a >
                        <a href=""><font-awesome-icon icon="fa-brands fa-instagram"/>?</a >
                        <a href=""><font-awesome-icon icon="fa-brands fa-behance" />?</a >
                        <a href=""><font-awesome-icon icon="fa-light fa-basketball" />?</a>
                        <a href="">?</a >
                        <a href=""><font-awesome-icon icon="fa-brands fa-git" />?</a>
                        <a href=""><font-awesome-icon icon="fa-brands fa-linkedin-in" />?</a >
                        <a href="">?</a>
                  </ul> 
               </div>
            </div>
            <hr>
            <div class="d-flex justify-content-between seconda-sez">
               <div>
                  <img src="@/assets/img/MasterStudy_logo.svg" alt="">
               </div>
               <a href="">CATEGORY</a>
               <div>
                  <div class="input-group mb-3">
                     <input type="text" class="form-control" placeholder="Serche courses" aria-label="Recipient's username" aria-describedby="button-addon2">
                     <button class="btn btn-outline-secondary bottonn" type="button" id="button-addon2">Serch</button>
                </div>
               </div>
               <a href="">Become an Istructor</a>
               <a href="">For Enterprises</a>
               <a href="">Log in</a>
               <button class="butt">SING UP</button>
               <div>?</div>
            </div>
</div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.centrale{
   margin: 0 10rem;
}
 .dropp{
   padding-top: 1rem;
 }

 .linkk{
   padding-top: 1rem;
 }
 .linkk a{
   text-decoration: none;
   margin: 0 8px ;
   color: gray;
 }
 .seconda-sez{
   margin:0 10rem;
   text-align: center;
 }
 .seconda-sez a{
   text-decoration: none;
   color: gray;
 }
 .butt{
   border-radius: 50px;
   padding: 0 2rem;
   background-color: blue;
   color: white;
   border: 0px;
 }
</style>