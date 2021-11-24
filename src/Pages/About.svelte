<script>
</script>



<div class="About-me transition">
  <div class="About">
    <h3 class="title">-- About the innovation</h3>
    <h2>
      Organic Composer is a software application designed to help people reduce their food
      waste by turning it into a resource of value. It provides personalized trusted solutions to
      help the customer. Providing them easy access to the correct knowledge and management
      skills needed to reduce their food waste. We believe that our innovative solution can reduce
      the local and global food waste problem.
    </h2>
   
  </div> 
  <div class="coding">
    <img class="about-img" src="mobile-nature.svg" alt="dawn" />
  </div>
</div>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Raleway:wght@500&display=swap");
  .About-me {
    font-family: "Raleway", sans-serif;
    color: #eeeeee;
    display: inline-flex;
    justify-content: space-between;
  }

  .About {
    padding: 90px;
    margin-top: 30px;
    flex: 1;
  }

  .coding {
    margin-right: 120px;
    flex: 1;
    
  }

  .about-img{
    
    max-width: 120%;
    
  }

  .title {
    color: #00b56a;
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

  @media (max-width: 1000px){
    .About-me{
      flex-direction: column;
      background-color: #222831;
    }

    .About {
      padding: 10px;
     margin-top: 20px;
    }

    .about-img{
    
    max-width: 100%;
    
  }

  }

</style>
