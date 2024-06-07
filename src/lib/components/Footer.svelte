<section class="footer">
  <div class="container">

    <div class="column">
      <div class="logo">
        <img src="/img/logo1.png" alt="">
        <span><h2>HM&Y Technologies</h2></span>
      </div>
      <p><i class="motto">a place for technology & innovation</i></p>
      <h1>Contacts & Support.</h1>
      <div class="icons">
        <p><span><i class="fa-solid fa-envelope"></i></span>hmy@hmytechnologies.com</p>
        <p><span><i class="fa-solid fa-phone"></i></span>+255 777 810 700</p>
        <p><span><i class="fa-regular fa-globe"></i></span>www.hmytechnologies.com</p>
        <p><span><i class="fa-brands fa-square-facebook"></i></span>facebook.com/hmytechnologies</p>
      </div>
    </div>

    <div class="column">
      <h1 class="underline">Visit Us</h1>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
        Nobis vero officiis voluptatem deleniti adipisci ducimus vitae 
        voluptatum laborum, veniam molestiae inventore asperiores, corporis 
        dolorem! Accusamus suscipit incidunt deserunt optio eveniet consectetur
      </p> 
    </div>

    <div class="column">
      <h1 class="underline">About Us</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
        Accusamus possimus, consequatur modi odit placeat fuga suscipit 
        quis recusandae, tempora dicta quisquam facere pariatur, quaerat 
        iste quod eveniet tempore! Quas totam, enim molestiae amet magnam 
        reprehenderit culpa quisquam libero sapiente fugit, voluptates 
        repudiandae nesciunt. Corporis facere aperiam dolorem, pariatur, 
        tempore quisquam voluptatibus perferendis nam laudantium dolor, 
        facilis consequatur enim quaerat placeat?</p>
    </div>
  </div>

  <div class="copyright">
    <p>&copy 2023 HM&Y Technologies.All rights reserved.</p>
    <p>Designed by <span>HM&Y Technologies</span></p>
  </div>
</section>
<style>
  section{
    background-color: rgb(43, 3, 48);
    width: 100%;
    height: 50vh;
    padding-bottom: 23px;
  }
  .container{
    display: flex;
    justify-content: center;
    align-items: center;
    
  }
  .logo img{
    width: 70px;
    height: 70px;
    transform: rotate(25deg);
  }
  
  .logo span h2{
    color: rgb(20, 95, 209);
    position: relative;
    top: -69px;
    font-size: 18px;
    left: 42px;
  }
  .column{
    width: calc(25%);
    margin-top: 65px;
    color: #fff;
  }
  .underline::after{
    content: '';
    position: absolute;
    background-color: #fff;
    width: 18%;
    height: 3px;
  }
  /* .underline:hover::after{
    width: 20%;
  } */
  .icons i{
    margin-right: 12px;
  }
  .motto{
    background-color: rgb(6, 207, 6);
    color: white;
    border-radius: 0px 12px 0px 12px;
    padding: 10px 12px;
    margin-bottom: 34px;
  }
  .copyright{
    display: block;
    margin: 32px auto;
    text-align: center;
    line-height: 8px;
    color: #fff;
  }
  .copyright p span{
    color: rgb(6, 207, 6);
  }
</style>