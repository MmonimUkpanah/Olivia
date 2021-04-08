<template>
  <div>
    <div class="nav" ref="set21" v-if="act">
            <div class="nav1" ref="set22">
                <font-awesome-icon class="icon" :icon="['fas', 'sliders-h']" @click="showNav" />
                <h2>djdjjd</h2>
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
        <h2>Olivia</h2>
      </div>
      
     
    </div>
    <div class="cele">
      <div class="cele1">
        <img src="/img/olia.jpg" alt="">
      </div>
      <div class="cele2">
        <p>Olivia is the leading brand of the Ukrainian sunflower seeds processing company 
          PAT Sumskyi Zavod Prodovolchykh Tovariv (a private joint-stock company)</p>
          <p>We produce</p>
          <ul>
            <li>refined sunflower oil winterized, deodorized;</li>
            <li>unrefined sunflower oil;</li>
            <li>sunflower meal (granulated and non-granulated);</li>
            <li>biofuel sunflower husk pellets;</li>
            <li>other sunflower oil-based products.</li>
          </ul>
          <p>We have experience in manufacturing products for hot climates with the 
            possibility of storage and distribution in high temperature conditions.</p>
      </div>
    </div>
    <div class="pro">
      <div class="pro1">

      </div>
    </div>
  </div>
</template>
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
    .icon{
        color: #ffbe3c;
     
      padding: 1rem;
      font-size: 4rem;
      border-radius: 50%;
      background: black;
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
    background: url(/img/ju.jpg) center center/cover;
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
  .index2 h2{
    color: white;
    font-size: 150px;
    padding-top: 10rem;
  }
  .cele{
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  .cele1 img{
    width: 100%;
    height: 70%;
  }
  .cele2{
    padding: 7rem 5rem;
  }
  .cele2 p{
    font-size: 20px;
    margin-bottom: 1.5rem;
    font-weight: bold;
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
    font-size: 100px;
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
    font-weight: bold;
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
  }
</style>