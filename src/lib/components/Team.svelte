<!-- <script lang="ts">
    import CardSlider from "./CardSlider.svelte";


  const breakpoints = {
    767: {
      slidesPerView: 2
    }
  };

</script>

<CardSlider {breakpoints} spaceBetween={30} /> -->

<section>
  <div class="container">
    <div class="section-header">
      <h1>Meet Our Team</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
        Laudantium ut modi ipsum quod quibusdam fuga itaque 
        voluptates aliquam iure pariatur et, suscipit ipsa corrupti 
        sequi voluptatem possimus aspernatur autem dicta impedit! 
        Nulla, error! Iste unde magni ducimus perferendis facere 
        sed doloremque enim dicta. Nobis ab laborum voluptatem 
        itaque fugiat debitis.
      </p>
    </div>
    <div class="card-content">

      <div class="swiper card-slider js-card-slide">
        <div class="swiper-wrapper">

          <div class="swiper-slide card-item">
            <div class="card-txt">
              <h1>Full Stack Developer</h1>
              <p>AbdulMajid</p>
              <p><b>2</b><span>years of <br>experience</span></p>
              <a href={''}><i class="fa fa-star"></i>abdulmajeedhaji</a>
              <div class="divImg">
                <img src="/img/Programmer.png" alt="">
              </div>
            </div>
          </div>
          <div class="swiper-slide card-item">
            <div class="card-txt">
              <h1>Full Stack Developer</h1>
              <p>AbdulMajid</p>
              <p><b>2</b><span>years of <br>experience</span></p>
              <a href={''}><i class="fa fa-star"></i>abdulmajeedhaji</a>
              <div class="divImg">
                <img src="/img/bg1.jpg" alt="">
              </div>
            </div>
          </div>
          <div class="swiper-slide card-item">
            <div class="card-txt">
              <h1>Full Stack Developer</h1>
              <p>AbdulMajid</p>
              <p><b>2</b><span>years of <br>experience</span></p>
              <a href={''}><i class="fa fa-star"></i>abdulmajeedhaji</a>
              <div class="divImg">
                <img src="/img/bg1.jpg" alt="">
              </div>
            </div>
          </div>
          <div class="swiper-slide card-item">
            <div class="card-txt">
              <h1>Full Stack Developer</h1>
              <p>AbdulMajid</p>
              <p><b>2</b><span>years of <br>experience</span></p>
              <a href={''}><i class="fa fa-star"></i>abdulmajeedhaji</a>
              <div class="divImg">
                <img src="/img/bg1.jpg" alt="">
              </div>
            </div>
          </div>
          <div class="swiper-slide card-item">
            <div class="card-txt">
              <h1>Full Stack Developer</h1>
              <p>AbdulMajid</p>
              <p><b>2</b><span>years of <br>experience</span></p>
              <a href={''}><i class="fa fa-star"></i>abdulmajeedhaji</a>
              <div class="divImg">
                <img src="/img/bg1.jpg" alt="">
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="swiper-pagination js-card-pagination"></div>

    </div>

  </div>
</section>
<style>
  .container{
    max-width: 1170px;
    margin: auto;
    padding: 0 15px;
  }
  
  .card-item{
    /* max-width: 550px; */
    height: 359px;
    background-color: brown;
    border: none;
    border-radius: 15px;
    padding: 34px 50px;
    background: linear-gradient(90deg, #e3ffe7 0%, #d9e7ff 100%);
    color: #fff;
    /* margin: 20px; */
  }
  .divImg img{
    width: 450px;
    height: 450px;
    position: relative;
    top: -190px;
  }
  .divImg{
    float: right;
  }
  .swiper-pagination{
    position: relative;
    margin-top: 40px;
    bottom: auto;
  }
  .swiper-pagination-bullet{
    height: 12px;
    width: 12px;
    background-color: hsl(0, 0%, 100%);
  }
</style>