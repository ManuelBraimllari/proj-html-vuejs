<template>
  <div class=" mt-4">
        <!-- Prima sezione-->
        <div class=" container primapart">
          <div class="left-container">
              <h1 class="mb-4">Start Investing in You</h1>
              <p class="mb-5">With over 1200 courses in 18 subjects, you're garanteed to finde something that's right for you.</p>
              <button class="butt">JOIN FOR FREE</button>
              
          </div>
          <div class="right-container">
              <img src="@/assets/img/base.png" alt="" class="immg1">
              <img src="@/assets/img/book1.png" alt="" class="immg2">
              <img src="@/assets/img/book2.png" alt="" class="immg3">
              <img src="@/assets/img/magnifier.png" alt="" class="immg4">
          </div>
        </div>

        <div class="container seconda">
          <div class="first">
              <h3>Worldwide Recognize</h3>
              <p class="mt-3">
                  Our online cosure certificates ca be used around the world 
                  and also in most popular universities and companies.
              </p>
          </div>
          <div class="second">
              <h3>Mosty Online Learning (sd)</h3>
              <p class="mt-3">
                  Masterstudy online certificates can be obtained in a range of specializwd areas and typically take about a year to complete.
              </p>
          </div>
          <div class="third">
              <h3>Graduate in as little as 1 Year</h3>
              <p class="mt-3">
                  Online post-graduate certificates are a popular way to develope your professional qialifications of Masterstudy.
              </p>
          </div>
        </div>

        <div class="container terza">
          <div class="left-container">
              <img src="@/assets/img/cat_1-1540x750.jpg" alt="">
              <div class="d-flex justify-content-between">
                      <p class="mt-2">Software Developement</p>
                      <p class="mt-2 secondo-paragraf">5 Courses</p>
                  </div>
          </div>
          <div class="right-container">
              <div class="primo">
                  <img src="@/assets/img/cat_2-370x155.jpg" alt="" class="imm1">
                  <div class="d-flex justify-content-between">
                      <p class="mt-2">Art</p>
                      <p class="mt-2 secondo-paragrafo">8 Courses</p>
                  </div>
              </div>
              <div>
                  <img src="@/assets/img/cat_3-370x155.jpg" alt="" class="imm2">
                 <div class="d-flex justify-content-between">
                      <p class="mt-2">Material Designe</p>
                      <p class="mt-2 secondo-paragrafo">5 Courses</p>
                  </div>
              </div>
          </div>
      </div>

      <div class="container quarta">
        <div class="imma1">
          <img src="@/assets/img/cat_4-370x155.jpg" alt="">
          <div class="d-flex justify-content-between">
                      <p class="mt-2">Music</p>
                      <p class="mt-2 secondo-paragrafo">5 Courses</p>
          </div>
        </div>
        <div class="imma2">
          <img src="@/assets/img/cat_5-370x155.jpg" alt="">
          <div class="d-flex justify-content-between">
                      <p class="mt-2">Exercise</p>
                      <p class="mt-2 secondo-paragrafo">7 Courses</p>
                  </div>
        </div>
        <div class="imma3">
          <img src="@/assets/img/cat_6-370x155.jpg" alt="">
          <div class="d-flex justify-content-between">
                      <p class="mt-2">Photography</p>
                      <p class="mt-2 secondo-paragrafo">4 Courses</p>
                  </div>
        </div>
      </div>
       <!--Seconda sezione-->
       <div class="cont-generale">
            <div class="container divisorio">
                <div class="left-container">
                    <h1>Limitless learning, more possibilities</h1>
                    <p class="mt-4">Online courses open the opportunity for learning to almost anyone, regardless of their scheduling commitments</p>
                    <button class="mt-3 butt">READ MORE</button>
                </div>    
            </div>
       </div>

       <h1 class="titolo-corsi">Recent courses</h1>
       <div class="categorie">
        <a href="https://www.google.com/">All Categories</a>
        <a href="https://www.google.com/">Art</a>
        <a href="https://www.google.com/">Exercise</a>
        <a href="https://www.google.com/">Material Designe</a>
        <a href="https://www.google.com/">Music</a>
        <a href="https://www.google.com/">Photography</a>
        <a href="https://www.google.com/">Software Developement</a>
       </div>

       <div class="card-sections d-flex flex-wrap">
        <div class="cardd" v-for="objCards in arrCards" :key="objCards.text">
            <img :src="objCards.img" alt="">
            <p class="catt">{{objCards.categoria}}</p>
            <p class="p-testo">{{objCards.text}}</p>
            <hr >
            <div class="d-flex justify-content-between paragrafi">
                <p> {{objCards.time}}</p>
                <p>{{objCards.prezzo}}</p>
            </div>
        </div>

        <button class="mt-5 mb-5 butt">SHOW ALL</button>
       </div>
       <div class="contenitore">
            <div class="container general">
                <h1>We are Proud</h1>
                <p class="mini-par">Certificate courses are indistructed by highly educated and qualified instructors who hold doctorals and master's level degrees.</p>
                <div class="d-flex justify-content-between boxx">
                    <div class="small-cont">
                        2000
                        <p>STUDENTS</p> 
                    </div>
                    <div class="small-cont">
                        950
                        <p>COURSES</p>
                    </div>
                    <div class="small-cont">
                        1600
                        <p>HOURS VIDEO</p>
                    </div>
                    <div>
                        150
                        <p>COUNTRIES REACHED</p>
                    </div>
                </div>
            </div>

            <img src="@/assets/img/we_proud.png" alt="" class="imm-sfondo">
       </div>
       <div class="cont-iscrizione">
        <div class="container d-flex justify-content-between iscrizione">
            <div class="left-container">
                <h4>Subscribe our newsletter</h4>
                <p>There are many variation of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words</p>
            </div>
            <div class="right-container">
                <h4>YOUR E-MAIL ADDRESS</h4>
                <div class="input-group mb-3">
                     <input type="text" class="form-control" placeholder="Enter your E-mail" aria-label="Recipient's username" aria-describedby="button-addon2">
                     <button class="btn btn-outline-secondary bottonn" type="button" id="button-addon2">SUBSCRIBE</button>
                </div>
                
            </div>
        </div>
       </div>

       <div class="contenitore">
            <h1 class="titolo-corsi">Popular courses</h1>
            <p class="secondotit">Discover our popular courses for self learning</p>

            <div class="card-sections d-flex flex-wrap">
                <div class="cardd" v-for="objCards in arrCardds" :key="objCards.text">
                    <img :src="objCards.img1" alt="">
                    <p class="catt">{{objCards.categoria1}}</p>
                    <p class="p-testo">{{objCards.text1}}</p>
                    <hr >
                    <div class="d-flex justify-content-between paragrafi">
                        <p> {{objCards.time1}}</p>
                        <p>{{objCards.prezzo1}}</p>
                    </div>
                </div>
            </div>
                <div class="container text-center">
                    <div class="btn-group mb-5" role="group" aria-label="Basic example">
                            <button type="button freccia" class="btn btn-primary"> <font-awesome-icon icon="fa-solid fa-arrow-left" /> ?</button>
                            <button type="button freccia" class="btn btn-primary"> <font-awesome-icon icon="fa-solid fa-arrow-up" /> ?</button>
                    </div>
                </div>
        </div>   
        
        <div class="cont-gross d-flex text-center">
            <div class="left-container d-flex">
                <div>
                    <img src="@/assets/img/image_box_1-221x231.png" alt="">
                </div>
                <div>
                    <h2>Become an Instructor</h2>
                    <p>Teach what you love. Masterstudy gives you the tools to create a course.</p>
                    <button class="butt">START TRACHING</button>
                </div>
            </div>
            <div class="right-container d-flex">
                <div>
                    <img src="@/assets/img/image_box_2-234x231.png" alt="">
                </div>
                <div>
                    <h2>Setup For Business</h2>
                    <p>Get unlimited access to 2,500 of Udemy's top courses for your team</p>
                    <button class="butt">DOING BUSINESS</button>
                </div>
            </div>
        </div>
        <div class="prima-part">
    <div class=" cont-foot">
        <h1>Come as you are</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque, laborum? Minima magnam officiis ab pariatur atque ipsa deserunt, impedit in assumenda a neque eius consequuntur cupiditate, voluptatum repudiandae cumque qui.
        Sed totam ratione omnis doloribus excepturi voluptatum provident necessitatibus nostrum eius eveniet! Reiciendis, quia reprehenderit. Similique rerum inventore vel praesentium doloribus. Eos, repellendus. Quia odio, minus blanditiis autem accusantium exercitationem!
        Culpa at quam architecto quae magnam totam recusandae pariatur nemo consequuntur, natus, iure dolores fuga fugit, corrupti eveniet magni adipisci! Suscipit totam similique vitae esse tempora quae iure sed asperiores?</p>
        <h3>Tim Sab</h3>
        <p>General Developer, Stylemix Themes</p>
    </div>
  </div>
  </div>
 
    
</template>

<script >


export default {
    data() {
        return{
            arrCards:[
                {
                    img:'img/photo-1.jpeg',
                    categoria:'Apache >',
                    text: 'Web Coding and Apache Basics',
                    time: '6 hours',
                    prezzo: 'Free',
                },
                {
                    img:'img/photo-2.jpg',
                    categoria:'Art >',
                    text: 'Web Coding and Apache Basics',
                    time: '6 hours',
                    prezzo: '$45',
                },
                {
                    img:'img/photo-3.jpg',
                    categoria:'Software Developement >',
                    text: 'Web Coding and Apache Basics',
                    prezzo: 'Free',
                },
                {
                    img:'img/photo-4.jpeg',
                    categoria:'Electronic >',
                    text: 'Web Coding and Apache Basics',
                    prezzo: '$49',
                },
                {
                    img:'img/photo-5.jpeg',
                    categoria:'Comunication >',
                    text: 'Web Coding and Apache Basics',
                    time: '6 hours',
                },
                {
                    img:'img/photo-6.jpg',
                    categoria:'Art >',
                    text: 'Web Coding and Apache Basics',
                    time: '6 hours',
                    prezzo: '$70',
                },
                {
                    img:'img/photo-7.jpeg',
                    categoria:'Bicycling >',
                    text: 'Web Coding and Apache Basics',
                    time: '6 hours',
                    prezzo: '$20',
                },
                {
                    img:'img/photo-8.jpg',
                    categoria:'Documentary >',
                    text: 'Web Coding and Apache Basics',
                    time: '6 hours',
                    prezzo: '$60',
                },
                {
                    img:'img/photo-9.jpg',
                    categoria:'Art >',
                    text: 'Web Coding and Apache Basics',
                    time: '6 hours',
                    prezzo: '$79',
                },
                {
                    img:'img/photo-10.png',
                    categoria:'Nvidia >',
                    text: 'Web Coding and Apache Basics',
                    prezzo: 'Free',
                },
                {
                    img:'img/photo-11.png',
                    categoria:'Art >',
                    text: 'Web Coding and Apache Basics',
                    time: '6 hours',
                    prezzo: 'Free',
                },
                {
                    img:'img/photo-12.jpg',
                    categoria:'Software Developement >',
                    text: 'Web Coding and Apache Basics',
                    time: '2 hours',
                    prezzo: 'Free',
                },
                
            ],
            arrCardds:[
            {
                    img1:'img/photo-1.jpeg',
                    categoria1:'Apache >',
                    text1: 'Web Coding and Apache Basics',
                    time1: '6 hours',
                    prezzo1: 'Free',
                },
                {
                    img1:'img/photo-2.jpg',
                    categoria1:'Art >',
                    text1: 'Web Coding and Apache Basics',
                    time1: '6 hours',
                    prezzo1: '$45',
                },
                {
                    img1:'img/photo-3.jpg',
                    categoria1:'Software Developement >',
                    text1: 'Web Coding and Apache Basics',
                    prezzo1: 'Free',
                },
                {
                    img1:'img/photo-4.jpeg',
                    categoria1:'Electronic >',
                    text1: 'Web Coding and Apache Basics',
                    prezzo1: '$49',
                },
                {
                    img1:'img/photo-5.jpeg',
                    categoria1:'Comunication >',
                    text1: 'Web Coding and Apache Basics',
                    time1: '6 hours',
                },
                {
                    img1:'img/photo-6.jpg',
                    categoria1:'Art >',
                    text1: 'Web Coding and Apache Basics',
                    time1: '6 hours',
                    prezzo1: '$70',
                },
            ]
        }
    }
 
    
    
}

</script>

<style lang="scss" scoped>
.butt{
   border-radius: 50px;
   padding: 0.5rem 3rem;
   background-color: #195EC8;
   color: white;
   border: 0px;
 }
.primapart{
    display: flex;
}
.primapart .left-container{
    width: 60%;
    text-align: left;
    padding-top: 220px;
}
.primapart .right-container{
    width: 40%;
    position: relative;
}
.primapart .left-container h1{
   font-size: 50px;
}
.primapart .left-container p{
   font-size: 22px;
}
.immg2{
      position: absolute;
      right: -51px;
      top: 105px;
}
.immg3{
      position: absolute;
      right: 60px;
      top: 270px;
}
.immg4{
      position: absolute;
      right: -20px;
      top: 320px;
}
.seconda{
    display: flex;
    justify-content: space-between;
    margin-top: 90px;
}
.seconda h3{
    font-size: 15px;
}
.seconda p{
    color: gray;
}
.first{
      width: 30%;
      border: 1px solid #F2F6FB;
      background-color: #F2F6FB;
      text-align: left;
      padding: 1.5rem;
      font-size: 12px;
}
.second{
      width: 30%;
      border: 1px solid #F2F6FB;
      background-color: #F2F6FB;
      text-align: left;
      padding: 1.5rem;
      font-size: 12px;
}
.third{
      width: 30%;
      border: 1px solid #F2F6FB;
      background-color: #F2F6FB;
      text-align: left;
      padding: 1.5rem;
      font-size: 12px;
}
.terza{
    display: flex;
    justify-content: space-between;
    margin-top: 100px;
}
.terza .left-container img{
    max-width: 848px;
}
.terza .right-container img{
    width: 390px;
}
.terza .right-container{
    justify-content: space-between;
    display: flex;
    flex-direction: column;
}
.terza .secondo-paragrafo{
    color: gray;
}
.quarta{
    display: flex;
    justify-content: space-between;
    margin-top: 30px;
}
.quarta img{
    width: 400px;
}
.quarta .secondo-paragrafo{
    color: gray;
}
.cont-generale{
    background-image: url('../assets/img/Untitled-1-1-1-1-1.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position-x: center;
    background-position-y: center
}
.divisorio{
    height: 600px;
    text-align: left;
    justify-content: center;
}

.cont-generale .left-container{
    padding-top: 200px;
    width: 400px;
}
.titolo-corsi{
    text-align: center;
    margin-top: 50px;
}
.categorie{
    text-align: center;
    margin-top: 50px;
}
.categorie a{
    margin:0 1rem;
    text-decoration: none;
}
.cardd{
    margin:0 1rem;
    text-align:left;
    border: 1px solid rgb(198, 193, 193);
    margin-bottom: 3rem;
}
.card-sections{
    justify-content: center;
    margin-top: 50px;
}
.paragrafi{
    margin: 0 1rem;
    color: gray;
}
.cardd hr{
    margin: 1rem 1rem;
}
.p-testo{
    margin-left: 1rem;
    font-size: 15px;
    margin-top: 1rem;
}
.catt{
    color: gray;
    margin-top: 1rem;
    font-size: 12px;
    margin-left: 1rem;
}
.contenitore .general{
    text-align: center;
}

.contenitore .general .boxx{
    font-size: 60px;
    margin-top: 100px;
}
.contenitore .general .boxx p{
    font-size: 20px;
}
.small-cont{
    border-right: 2px solid rgb(220, 220, 220);
    padding:0 6rem;
}
.contenitore{
    background-color: #F0F4FA;
    padding-top: 5rem;
}

.contenitore .mini-par{
    padding: 0 16rem;
    margin-top: 2rem;
    color: gray;
}
.imm-sfondo{
    margin-top: -150px;
}
.iscrizione{
    padding: 4rem 0;
}
.iscrizione .left-container{
    width: 60%;
}
.iscrizione .right-container{
    width: 40%;
}
.cont-iscrizione{
    background-color: #4ED7A8;
    color: white;
}
.bottonn{
    background-color: blue;
    color: white;
}
.iscrizione .right-container h4{
    font-size: 20px;
    margin-bottom: 1rem;
}

.secondotit{
    text-align: center;
    color: gray;
    margin-top: 2rem;
}
.freccia{
    background-color: rgb(255, 255, 255);
    color: gray;
}
.cont-gross .left-container{
    border: 1px solid rgb(200, 200, 200);
    padding: 3rem;
    text-align: left;
}
.cont-gross .right-container{
    border: 1px solid rgb(200, 200, 200);
    padding: 3rem;
    text-align: left;
}
.cont-gross{
    margin:5rem 5rem ;
    gap: 2rem;
}
.cont-gross h2{
    margin-top: 4rem;
}
.cont-gross  button{
    margin-left: 4rem;
}
.cont-gross p{
    margin-left: 4rem;
}
.cont-gross  h2{
    margin-left: 4rem;
}

.prima-part{
    background-image: url(../assets/img/brooke-cagle-224821-unsplash-1-1920x700.jpg);
    height: 700px;
}
.cont-foot{
  background-color: white;
  padding-top: 2rem;
  margin-right: 50rem;
  margin-left: 30rem;
  border: 2px solid white;
}
/* non capisco perche il container non mi si stacca dal toop*/ 

</style>