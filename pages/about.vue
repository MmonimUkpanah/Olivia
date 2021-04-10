<template>
    <div>
        <div class="nav" ref="set21" v-if="act">
            <div class="nav1" ref="set22">
                <font-awesome-icon class="icon" :icon="['fas', 'sliders-h']" @click="showNav" />
                <div class="nav2">
                <nuxt-link class="link" to="/"><h2>HOME</h2></nuxt-link>
                <nuxt-link class="link" to="about"><h2>ABOUT COMPANY</h2></nuxt-link>
                <nuxt-link class="link" to="team"><h2>OUR TEAM</h2></nuxt-link>
                <nuxt-link class="link" to="production"><h2>PRODUCTION</h2></nuxt-link>
                <nuxt-link class="link" to="products"><h2>PRODUCTS</h2></nuxt-link>
                </div>
                
            </div>
        </div>
    <div class="index">
      <div class="index0">
        <div>
          <font-awesome-icon class="icon2" :icon="['fas', 'sliders-h']" @click="showNav" />
        </div>
        <div class="index1">
          <h2>Olivia</h2>
        </div>
      </div>
      <div class="index2">
          <h1>Olivia</h1>
          
        <h2>ABOUT OUR COMPANY</h2>
      </div>
      
     
    </div>
    <div class="pro">
      <div class="pro0">
        <h2>THE SECRET OF A <span class="pro4">PREMIUM PRODUCT</span>  IS SO SIMPLE:</h2>
      </div>
      
      <div class="pro1">
        <div class="pro2">
          <h2>HEAVY CROP OF  <span class="pro4">WORLD-FAMOUS</span> UKRAINIAN SUNFLOWERS </h2>
        </div>
        <div class="pro3">
          <h2>HIGH <span class="pro4">QUALITY</span>  STANDARDS</h2> 
        </div>
      </div>
      <div class="pro1">
        <div class="pro2">
          <h2>MANUFACTURING ON <span class="pro4">MODERN</span> LINES</h2>
        </div>
        <div class="pro3">
          <h2>EVERYDAY<span class="pro4"> WORK</span >  THAT WE ENJOY</h2> 
        </div>
      </div>
    </div>
    <div class="cele">
      <div class="cele1">
      </div>
      <div class="cele2">
        <p>Olivia is the leading brand of the Ukrainian company PAT Sumskyi Zavod Prodovolchykh
             Tovariv (a private joint-stock company). It is a major Ukrainian sunflower seeds
              processing company that has been producing a large range of products for over 
              30 years.</p>
          <p>The high quality of the products is accomplished through the combination 
              of modern and effective production and bountiful harvest of well-known 
              Ukrainian sunflowers. Olivia sunflower oil is an abundance of carefully picked 
              and processed sunflowers.</p>
          <p>Our company produces refined and unrefined sunflower oil. We also offer an 
              extensive range of sunflower seeds products and raw material processing services.</p>
          <p>We have experience in manufacturing products for hot climates with the 
            possibility of storage and distribution in high temperature conditions.</p>
      </div>
    </div>
    <div class="ad">
      <h2>OLIVIA VALUES</h2>
      <div class="ad1">
        <div class="ad2">
          <p>We value a straightforward partnership since simple and clear cooperation mechanisms allow saving the most important business resource, time.</p>
        </div>
        <div class="ad2">
          <p>We are open to partnership and provide an opportunity to create a private label using our own formulas and technological tasks.</p>
        </div>
        <div class="ad2">
          <p>We are expending the horizons of our abilities by offering shipping to any country in the world.</p>
        </div>
        
      </div>
    </div>
    <div class="cele">
      <div class="cele2">
        <h2> SUSTAINABLE DEVELOPMENT</h2>
        <p><span class="cele5">RESPONSIBILITY TOWARDS NATURAL RESOURCES OF UKRAINE </span> </p>
        <p>A complex approach to environmental protection is a very important part of the company's work. It involves the optimal usage of the resources and implementation of measures for the preservation of the environment.</p>
        <p><span class="cele5">PRODUCT SAFETY </span> </p>
          <p>Our company produces refined and unrefined sunflower oil. We also offer an 
              extensive range of sunflower seeds products and raw material processing services.</p>
          <p>We have experience in manufacturing products for hot climates with the 
            possibility of storage and distribution in high temperature conditions.</p>
        <p><span class="cele5">RESPONSIBLE EMPLOYER </span></p>
        <p>Our company's main priority is to create a comfortable and safe work environment. This is the reason why the company improves production processes, organizes trainings, and creates convenient working conditions for its employees.</p>
      </div>
      <div class="cele1">
      </div>
    </div>
    <footer-sections/>
    </div>
</template>
<style scoped>
    @font-face {
    font-family: DMSans;
    src: url("/font/DMSans-Regular.ttf");
    }
    *{
        font-family: 'DM Sans', sans-serif  !important;
        padding: 0;
        margin: 0;
    }
    .nav{
        width: 30%;
        height: 100vh;
        position: fixed;
        top: 0;
        left: 0;
        background: #ffbe3c;
    }
    .nav1{
        margin-left: 3rem;
        margin-right: 3rem;
        padding-top: 2rem;
    }
    .nav1 img{
        border:1px solid white;
        width: 5rem;
        background: white;
        border-radius: 50%;
    }
    .nav2{
      margin-top: 3rem;
      color: white;
    }
    .link{
      color: white;
    }
    .nav2 h2{
      margin-bottom: 2rem;
    }
    .icon{
        color: black;
     
      padding: 1rem;
      font-size: 4rem;
      border-radius: 50%;
      border: 2px solid black;
    }
    .icon2{     
      color: white;
      margin-left: 3rem;
      margin-top: 2rem;
      padding: 1rem;
      font-size: 4rem;
      border-radius: 50%;
      background: #ffbe3c;
    }
  .index{
    background: transparent url(/img/de.jpg) center center/cover;
    height: 100vh;
    
  }
  .index0{
    display: grid;
    grid-template-columns: 1fr 1fr;
    position: fixed;
    width: 100%;
    margin-bottom: 10rem;
  }
  .index1{
    text-align: right;
    margin-top: 2rem;
    margin-right: 7rem;
    color: white;
  }
  .index1 h2{
    font-size: 50px;
  }
  .index2{
    text-align: center;
  }
  .index2 h1{
      color: white;
    font-size: 100px;
   padding-top: 5rem;
  }
  
  .index2 h2{
    color: white;
    font-size: 50px;
    padding-top: 20rem;
  }
  .cele{
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  
  .cele1{
    background: url("/img/olia.jpg") center center/cover ;
  }
  .cele2{
    padding: 5rem 5rem;
  }
  .cele2 h2{
    font-size: 30px;
    margin-bottom: 1rem;
  }
  .cele2 p{
    font-size: 20px;
    margin-bottom: 1.5rem;
  
  }
.cele5{
  font-weight: bold;
  color: #ffbe3c;
}
.pro{
  margin-top: 4rem;
  margin-bottom: 2rem;
}
.pro0{
  text-align: center;
  margin-left: 15%;
  margin-right: 15%;
}
.pro0 h2{
  font-size: 45px;
}
.pro1{
  display: grid;
  grid-template-columns: 1fr 1fr;
  margin-left: 3rem;
  margin-right: 3rem;
  margin-top: 3rem;
  text-align: center;
}
.pro1 h2{
  font-size: 40px;
  
}
.pro2{
  padding-right: 4rem;
  
}
.pro3{
  padding-left: 4rem;
  margin-top: 7rem;
  
  
                     

}
.pro4{
  color: #ffbe3c;
}
.ad{
  margin-top: 3rem;
  text-align: center;
}
.ad h2{
  font-size: 50px;
  font-weight: bold;
  margin-bottom: 1rem;
}
.ad1{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr ;
  grid-column-gap: 1rem;
  margin-left: 10%;
  margin-right: 10%;
}
.ad2{
  text-align: center;
}
.ad2 p{
  font-size: 20px;
}







@media(max-width:567px){
    .nav{
        width: 100%;
        height: 100vh;
        position: fixed;
        top: 0;
        left: 0;
        background: #ffbe3c;
    }
    .nav1{
        margin-left: 10px;
        margin-right: 10px;
        padding-top: 2rem;
    }
    .nav1 img{
        border:1px solid white;
        width: 5rem;
        background: white;
        border-radius: 50%;
    }
    .icon{
        color: #ffbe3c;
     
      padding: 1rem;
      font-size: 4rem;
      border-radius: 50%;
      background: black;
    }
    .icon2{     
      color: white;
      margin-left: 10px;
      margin-top: 2rem;
      padding: 1rem;
      font-size: 4rem;
      border-radius: 50%;
      background: #ffbe3c;
    }
  .index{
    background: url(/img/ju.jpg) center center/cover;
    height: 100vh;
    
  }
  .index0{
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  .index1{
    text-align: right;
    margin-top: 2rem;
    margin-right: 10px;
    color: white;
  }
  .index1 h2{
    font-size: 50px;
  }
  .index2{
    text-align: center;
  }
  .index2 h2{
    color: white;
    font-size: 50px;
    padding-top: 15rem;
  }
  .cele{
    display: grid;
    grid-template-columns: 1fr;
  }
  .cele1 img{
    width: 100%;
    height: 100%;
  }
  .cele2{
    padding: 1rem 1rem;
  }
  .cele2 p{
    font-size: 20px;
    margin-bottom: 1.5rem;
  
  }
  .cele2 ul{
    list-style: none;
    margin-left: 1rem;
    margin-bottom: 1.5rem;
  }
  .cele2 ul li::before {
  content: "\2022";  /* Add content: \2022 is the CSS Code/unicode for a bullet */
  color: #ffbe3c; /* Change the color */
  font-weight: bold; /* If you want it to be bold */
  display: inline-block; /* Needed to add space between the bullet and the text */
  width: 1em; /* Also needed for space (tweak if needed) */
  margin-left: -1em; /* Also needed for space (tweak if needed) */
}
.cele2 ul li{
  font-size: 20px;
}
  .pro{
  margin-top: 4rem;
  margin-bottom: 4rem;
}
.pro0{
  text-align: center;
}
.pro0 h2{
  font-size: 45px;
}
.pro1{
  display: grid;
  grid-template-columns: 1fr;
  margin-left: 10px;
  margin-right: 10px;
  margin-top: 3rem;
}
.pro1 h2{
  font-size: 30px;
  
}
.pro2{
  padding-right: 0;
  margin-top: 1rem;
  text-align: center;
  
}
.pro3{
  padding-left: 0;
  margin-top: 2.5rem;
  text-align: center;           

}
.pro4{
  color: #ffbe3c;
}
.ad1{
  display: grid;
  grid-template-columns: 1fr;
  grid-column-gap: 1rem;
  margin-left: 10px;
  margin-right: 10px;
}
}
</style>






<script>
export default {
    data(){
        return{
            act:false,
            
        }
    },
    methods:{
        showNav(){
            if (this.act==true){
                this.act=false;
            }else{
                this.act=true;
               
            }
        },
    }
}
</script>