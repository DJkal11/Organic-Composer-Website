<div class="display-intro transition">
  <div class="intro">
    <h3 class="name">-- Sustainable</h3>
    <h1>Organic Composer</h1>
    <iframe class="video" width="400" height="300" src="https://www.youtube.com/embed/3SNM_QkEvvg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
  <div class="space">
    <img class="home-img" src="nature.svg" alt="dawn" />
  </div>
</div>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Raleway:wght@500&display=swap");

  .display-intro {
    display: inline-flex;
  }

  .intro {
    padding: 90px;
    padding-top: 0px;
    padding-right: 10px;
    margin-top: 0px;
    flex: 1;
  }

  .name {
    color: #00b56a;
  }

  .space {
    margin-right: 120px;
    width: 100%;
    padding: 5px;
    flex: 1;
  }

  .home-img {
   max-width: 100%;
   
  }

  .video {
    margin-top: 70px;
    border: 1px solid black;
    border-radius:10%;
  }

  .transition {
    animation-name: fadeInUp;
    animation-duration: 0.25s;
    transition-timing-function: ease-in;
    animation-fill-mode: both;
  }
  
  @keyframes fadeInUp {
  0% {
    opacity: 0;
    transform: translate3d(0, 100%, 0);
  }

  100% {
    opacity: 1;
    transform: none;
  }
}

  @media (max-width: 900px) {
   .display-intro {
     flex-direction: column;
     background-color: #222831;
   }

   .intro {
     padding: 10px;
     margin-top: 20px;
   }

   .space {
     padding: 0px;
   }

  }


</style>
