<header>
  <div id="logo">
    <span><img src="/img/logo1.png" alt=""></span>
    <span><h2>HM&Y Technologies</h2></span>
  </div>
  <nav>
    <ul>
      <li>
        <a href={''}>PRODUCT</a>
      </li>
      <li>
        <a href={''}>SERVICES</a>
      </li>
      <li>
        <a href={''}>PORTFOLIO</a>
      </li>

      <!-- <li class="nav-item">
        <a class="nav-link collapsed" data-bs-target="#components-nav" data-bs-toggle="collapse" href="#" aria-expanded="false">SERVICES
        </a>
        <ul id="components-nav" class="nav-content collapse" data-bs-parent="#sidebar-nav" style="">
          <li>
            <a href="components-cards.html">Mobile App Service</a>
          </li>
          <li>
            <a href="components-cards.html">Web App Service</a>
          </li>
          <li>
            <a href="components-cards.html">Website Design Service</a>
          </li>
          <li>
            <a href="components-cards.html">Front-End Service</a>
          </li>
          <li>
            <a href="components-cards.html">Back-End Service</a>
          </li>
          <li>
            <a href="components-cards.html">AI Development Services</a>
          </li>
        </ul>
      </li> -->
    </ul>
  </nav>
  <div class="btn-cont">
    <button class="btnCont">CONTACT US</button>
  </div>
</header>
<style>
  header{
    display: flex;
    justify-content: space-between;
    background: url(/img/bg2.jpg);
    height: 65vh;
    width: 100%;
    background-position: center;
    background-size: cover;
    /* padding: 20px; */
    margin-bottom: 100px;
    opacity: 0.8;
  }
  #logo{
    margin: 25px;
    display: flex;
    cursor: pointer;
    position: relative;
    left: 44px;
  }
  #logo img{
    width: 100px;
    height: 100px;
    transform: rotate(25deg);

  }
  #logo h2{
    /* margin-left: -35px; */
    color: rgb(6, 63, 148);
    position: relative;
    top: 10px;
    left: -30px;
  }
  /* nav{
    background-color: transparent;
  } */
  nav ul{
    list-style: none;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    gap: 3rem;
    margin: 48px 30px;
  }
  nav li a{
    text-decoration: none;
    color: #fff;
    cursor: pointer;
    font-weight: bold;
  }
  .btn-cont{
    margin: 40px 40px 0 0;
  }
  .btnCont{
    padding: 15px 25px;
    background: linear-gradient(90deg, #1CB5E0 0%, #000851 100%);
    color: #fff;
    border: none;
    border-radius: 25px;
    font-weight: bold;
    font-size: 18px;
    cursor: pointer;
  }
  .btnCont:hover{
    background: linear-gradient(90deg, #000851 0%, #1CB5E0 100%);
  }
  @media(max-width:768px){
    
  }
</style>