<template>
<div class="root">
  <div class="flex-wrapper">

    <main>
    <div class="intro-flex-wrapper">
        <div class="intro-wrapper">
          <span class="color">Multi Media Designer </span>
          <h1><span class="surname">EDINA</span><br><span class="familyname">ILYES</span></h1>
        </div>
        <div class="button-wrapper">
        <a class="linkbutton" href="#footer">Connection</a>
        <a target="_blank" class="linkbutton" href="https://www.instagram.com/m.m.deviser/">Drawing Works</a>
        <a target="_blank" class="linkbutton" href="https://www.instagram.com/especial_photo/">Photography Portfolio</a>
        <a target="_blank" class="linkbutton2" href="https://www.dropbox.com/s/qyaf5vi39kiqy89/cv..pdf?dl=0">CV</a>
        <a target="_blank" class="linkbutton2" href="https://www.dropbox.com/s/q26r7aapzb3kxha/card.pdf?dl=0">Business Card</a>
        </div>
        </div>

         <p class="intro"> Hi everyone! Welcome in my portfolio,</p>
        <p class="intro">I am a highly motivated multimedia designer with experience in 
        frontend development including website and graphic design, video recording and editing. 
        I have learned telemarketing and how to advertise our products, according to making user 
        experience researches. Main subjects as a Multi-Media Design student: 
        User Experience, Content Creation, Design Development, Business.
        </p>
        
        <p class="intro">  I enjoy challenges and I am consistently achieving high standards with a holistic and creative
         approach to all my projects. I contribute to a friendly
          work environment and thrive best working idependtly.  </p>
      
         <iframe  width="420" height="315" class="video"
          src="https://youtu.be/NU-nNwoy-6M">
          </iframe>
      
        <!--<video width="320" height="240" controls>
            <source src="movie.mp4" type="video/mp4"></video>-->
             <!--<>-->

        <p>I am studying currently Multi-Media Design at EASV in Esbjerg, Denmark.
         I got an insight into basics of creating websites
          by HTML5, CSS3, Js  in Visual Studio Code,</p>
        
            <img class="icon" alt="linkedin logo" src="../assets/css.png">
            <img class="icon" alt="linkedin logo" src="../assets/HTML.png">
            <img class="icon" alt="linkedin logo" src="../assets/Js.png">
            
        <p>Learning Business User experience by using Adobe products such as Illustrator,
         Premier Pro, After effect, allowed me to expand my horizons.
          Creative cloud gave me new capabilities which let me show new ideas and unique site of creativity in my design.</p>

            <img class="icon" alt="linkedin logo" src="../assets/pr.jpg">
            <img class="icon" alt="linkedin logo" src="../assets/ps.jpg">
            <img class="icon" alt="linkedin logo" src="../assets/xd.png">
            <img class="icon" alt="linkedin logo" src="../assets/ai.png">
            <img class="icon" alt="linkedin logo" src="../assets/ae.png">
            <img class="icon" alt="linkedin logo" src="../assets/id.png">
            
            
        
        <!--<img src="smiley.gif" alt="Smiley face" width="42" height="42">
        <img src="smiley.gif" alt="Smiley face" width="42" height="42">-->

        <p>I love taking pictures, drawing, video recording and editing .
         My dream is to find a company in Denmark where I can use my knowledge and gain more experience.</p>

        <p>If you have any question feel free to contact me.</p>

    </main>

    <aside>
      <div class="profildiv">
        <img src="../assets/profil.jpg" alt="PictureOfMe" class="imageprofil">
      </div>
        <span>SKILLS</span>
        <div class="skills">
         <ul>
            <li>Frontend development</li>
            <li>Griffith design</li>
            <li>Photography</li>
            <li>Video editing</li>
            <li>UX/UI design</li>
            <li>(user experience and user interface design)</li>
        </ul>
         </div>
          <div class="education">           
        <ul>
            <li><span >Education</span> </li>
            <p></p>
            <li>Business Academy Southwest</li>
            <li>Multi Media Design,</li>
            <li>Graduated May 2020</li>
        </ul>
          </div>
        <div >
         <img src="../assets/lan.jpg" alt="PictureOfMe" class="imageprofil">
        </div>

    </aside>
    
    </div>
            <div class="flex-space-around">
          <a target="_blank" class="linkbuttondestop" href="https://www.instagram.com/m.m.deviser/">Drawing Works</a>
          <a target="_blank" class="linkbuttondestop" id="responseheadline" href="https://www.instagram.com/especial_photo/">Photography Portfolio</a>
        </div>
        
<a target="_blank" class="linkbuttonmobil" href="https://www.instagram.com/m.m.deviser/">Drawing Works</a>
    <div class="flex-space-around" id="carro-wrapper" >
       <div class="carousel-wrapper" flat>
          <v-carousel flat hide-delimiters="true" hide-controls="true">
            <v-carousel-item flat id="carousel-image" 
              v-for="(picture,i) in drawingPictures"
              :key="i"
            
            >
            <img id="carimg" :src="picture.src" :alt="picture.src"/></v-carousel-item>
          </v-carousel>
        </div>
        <div class="carousel-wrapper">
          <v-carousel  hide-delimiters="true"  hide-controls="true">
            <v-carousel-item id="carousel-image"
              v-for="(picture,i) in photographyPictures"
              :key="i"
            
            >
              <img id="carimg" :src="picture.src" :alt="picture.src"/></v-carousel-item></v-carousel-item>
          </v-carousel>  
        </div>
      </div>
      <a target="_blank" class="linkbuttonmobil" id="responseheadline" href="https://www.instagram.com/especial_photo/">Photography Portfolio</a>



    
    <footer id="footer">
    <div class="button-wrapper">
        <a target="_blank" class="linkbutton1" href="https://www.dropbox.com/s/qyaf5vi39kiqy89/cv..pdf?dl=0">CV</a>
        <a target="_blank" class="linkbutton1" href="https://www.dropbox.com/s/q26r7aapzb3kxha/card.pdf?dl=0">Business Card</a>
        </div>

     <address>
        CONTACT<br> 
        EMAIL: edinailyes10@gmil.com<br>
        PHONE: +45 50324910<br>
        ADDRESS: Hasselvangen, 10<br>
        Denmark
      </address>
      <a target="_blank" href="https://www.linkedin.com/in/edina-ilyes-a50999171/">
      <img class="icon"  alt="linkedin logo" src="../assets/linkedinlogo.png">
       </a>
      <a target="_blank" href="https://www.instagram.com/edina_ilyes/">
        <img class="icon"  alt="linkedin logo" src="../assets/insta.png">
      </a>
    </footer>
  </div>
</template>

<script>

 export default {
   name: 'HelloWorld',
    data () {
      return {
        drawingPictures: [
          {
            src: require('../assets/drawingglass.png')
          },
          {
            src: require('../assets/weding.png')
          },
            {
            src: require('../assets/smile.png')
          }
        ],
        photographyPictures: [
          {
            src: require('../assets/csilla.png')
          },
          {
            src: require('../assets/reka.png')
          },
          {
            src: require('../assets/house.png')
          }
        ]
      }
    }
  }
</script>

<!-- <h1 class="classname" >Edina</h1> -->
<style scoped>
/* <due to 3rd party package, I need to target the implemented class */
.v-carousel{
  max-height:350px;
  box-shadow:none !important
}
.v-carousel__controls {
  background-color:#ffffff00 !important
}
#carimg {
  height:300px;
  width:300px;
    background-size: contain /* cover */ 
}
#carousel-image {
  /* Do stuff*/ 
  height:500px;
  width:;
  background-size: contain /* cover */ 
}
.v-window__container--is-active {
    height: 100% !important;
}
/*HTML tags */
a{
  text-decoration:none;
}
p{
  text-align:justify;
}
h1{
  color:red;
}
main{
  width: 75%;
  margin-right:3%;
}
aside{
  width: 25%;
}
footer{
  background-color: gray;
  height: 100px;
  display:flex;
  flex-direction:row;
  padding-top: 10px;
  margin-top:50px;
}
address{
  width: 90%;
}
/*Classes */
.color{
color: black;
}
.education{
   display:flex;
  flex-direction:row;
  margin-top: 10px;
  padding: 15px 15px 30px 25px;
  
}

.carousel-wrapper{
  width:40%;
}
.flex-space-around{
  display:flex;
  justify-content:space-around;
  margin-top: 30px;
}
.skills{
  display:flex;
  flex-direction:row;
  padding: 15px 15px 20px 15px;
  }
.flex-wrapper{
  display:flex;
  flex-direction:row;
  padding: 100px 30px 0px 30px;
}
.intro-flex-wrapper{
  display:flex;
  flex-direction:row;
  justify-content:space-around;
}
.icon{
  width:30px;
  height:30px;
  margin-left:10px;
}
button, .linkbutton, .linkbuttondestop, .linkbutton2, .linkbuttonmobil, .linkbutton1{
  width: 200px;
  margin-bottom: 10px;
  border-radius: 30px;
  background-color: pink; 
  border: 1px solid green;
}

.button-wrapper{
  display:flex;
  flex-direction: column;
}
.surname{
   position: relative;
   left: 15px;
   line-height:70px;
   color: gray;
}
.familyname{
   position: relative;
   left: 50px;
    color: gray;
}   
.imageprofil{
  display: block;
  width: 100%;
  height: auto;
  margin-bottom:40px;
}
/*MEDIA queries */

@media only screen and (max-width: 1900px) and (min-width: 631px)  {
.linkbuttonmobil{
  display:none;
 }
  main{
    width:90%;
    padding:0 5%;
    padding-right: 3%;
  }
 .linkbutton2{
  display:none;
 }
}

@media only screen and (max-width: 631px) {
  .flex-wrapper{
  flex-direction: column;
}
.video{
    width:90%;
  }

  aside{
    width:90%;
    padding:0 5%;
  }
  main{
    width:90%;
    padding:0 5%;
    margin-right: 0px;
    padding-right: 1%;
  }
  #carro-wrapper {
    display:flex;
flex-direction: column;
  }
.linkbutton{
  display:none;
 }
.linkbuttondestop{
  display:none;
 }


.carousel-wrapper {
    width:100%
  }

.linkbutton1{
  display:none;
 }
 .profildiv{
align: center;
}
.imageprofil{
  display: block;
  width: 50%;
  height: auto;
  margin-bottom:30px;
  margin-left:80px;
}
.skills{
  display:flex;
  flex-direction:row;
  padding: 15px 15px 20px 38px;
  }
.education{
   display:flex;
  flex-direction:row;
  margin-top: 10px;
  padding: 15px 15px 30px 75px;
  
}

}

</style>
