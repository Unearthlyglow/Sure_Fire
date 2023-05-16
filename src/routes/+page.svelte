<script>
  import '@picocss/pico';
  import ccmBuilding from '../public/assets/CCM.png'
  import blueBlock from '../public/assets/blueBlock.png'
  import redBlock from '../public/assets/redBlock.png'
  import purpleBlock from '../public/assets/purpleBlock.png'
</script>

<div class="container-fluid">
  <img class="ccm" src={ccmBuilding} alt="Caps" />

    <!-- <div class="ccmLogo" ref="ccmLogo"> -->
      <img src="~/assets/CCMLogo.png" alt="" />
      <!-- [Enable Once Tabs are Ready] -->
<!--  <div class="header--tabs">
        <a href="#tools" class="header--tab">Software Tools && Equipment ||</ a>
        <a href="#portfolio" class="header--tab">Portfolio ||</a>
        <a href="#servicesTitle" class="header--tab">Services ||</a>
        <a href="#section--contact" class="header--tab">Contact </a>
      </div> -->
      <header>
        <h3 class="header--CyberSpace--quote">Cyberspace // It's Almost Better Than Life</h3>
        <h4 class="header--CyberSpace--moat">Please excuse the lack of a website. When I first created this site I did it in a hurry and it lacked confidence and had some bugs. I've been busy with other projects but will be periodically updating this website as time progresses - May 2023 || ~Award</h4>
      </header>
    </div>


    <!-- <p class="aboutAward">Hello, my name is <span>Award Malisi.</span></p> -->

    <!-- <p class="aboutMe">
      I am a Web Developer and UI/UX Designer. I specialize in working with
      small to medium based companies to ensure their business is best dressed
      when viewed on the world wide web<span>.</span>
    </p> -->

    <!-- <div class="header--redBlock">
      <img src={blueBlock} alt="3d Blue Block" />
    </div>
    <div class="header--greenBlock">
      <img src={purpleBlock} alt="3d Green Block" />
    </div>
    <div class="header--prismBlock">
      <img src={redBlock} alt="Prism" />
    </div> -->


<style scoped lang="scss">
  $base: #fff6e0;
  $red: #8c2525;
  $green: #142e29;
  $blue: #15104a;
  $yellow: #cca131;
  $light-yellow: #e8d9b4;

  //Global
  p {
    color: black;
    font-weight: 400;
  }

//Container
  .container-fluid {
    background-color: #fff6e0;
    height: 60rem;
  }

  .header--CyberSpace--quote {
    font-size: 2.2rem;
    font-weight: 900;
    color: $red;
    text-align: center;
  }

  .header--CyberSpace--moat {
    font-size: 1.8rem;
    font-weight: 900;
    color: $blue;
    text-align: center;
  }

  .header--greenBlock {
    >img {
      height: 16rem;
    }
  }

  .header--prismBlock {
    >img {
      height: 20rem;
    }
  }

  .header--redBlock {
    >img {
      height: 20rem;
    }
  }

 </style>