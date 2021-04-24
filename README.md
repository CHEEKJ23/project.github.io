
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Project</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">
        <!-- Bootstrap core CSS -->
        <link href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.0/css/bootstrap.min.css" rel="stylesheet">
        <!-- Material Design Bootstrap -->
        <link href="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.19.1/css/mdb.min.css" rel="stylesheet">
        <link href="main.css" rel="stylesheet" type="text/css">
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
        <!-- Bootstrap tooltips -->
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.4/umd/popper.min.js"></script>
        <!-- Bootstrap core JavaScript -->
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.0/js/bootstrap.min.js"></script>
        <!-- MDB core JavaScript -->
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mdbootstrap/4.19.1/js/mdb.min.js"></script>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
  // first // 
     $(document).ready(function()

{

  $('#more').click(function() {

      $('#details').toggle();

  });

});
// first //

// second /
var username
username= prompt("Please Enter Your Name")
// second

// button 1 //
function button1() {
  alert("THANK YOU SO MUCHHHH >_<");
}
// button 1 //

// button 2 //
var name;
function button2() {
  alert("THANKS FOR GIVING YOUR COMMENT")
}
// button 2 //

// form //

function validateForm()
           {
               if(document.getElementById('userAge').value < 18)
               {
                   alert("Age is less than 18. Please leave.");
                   return false;
               }
              
               if(document.getElementById('userName').userName.value=="")
               {
                   alert("Name field cannot be empty");
                   return false;
               }
               if (document.getElementById('userAge').value>=18)
               alert ("Name and Age are valid");
               return true;
           }
// form //

// game:buttons //
function more1() {
  document.getElementById("details1").innerHTML = "Fortnite" ;
}

function more2() {
  document.getElementById("details2").innerHTML = "Apex Legend" ;
}

function more3() {
  document.getElementById("details3").innerHTML = "Valorant" ;
}
// game:buttons //
</script>
    </head>
    <body >
        <nav class="navbar navbar-expand-lg navbar-dark muted-color fixed-top bg-dark ">

            <div class="container">
          
         
              <a class="navbar-brand" href="#myPage"><i class="fas fa-dragon"></i> PROJECT</a>
          
           
              <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#basicExampleNav"
                aria-controls="basicExampleNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
          
            
              <div class="collapse navbar-collapse" id="basicExampleNav">
          
            
                <ul class="navbar-nav mr-auto">
                  <li class="nav-item active">
                    <a class="nav-link" href="#"><i class="fas fa-home"></i> Home
                      <span class="sr-only">(current)</span>
                    </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#me"><i class="fas fa-user"></i>ME</a>
                  </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#movie"><i class="fas fa-film"></i>MOVIE</a>
                  </li>
          
                  
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true"
                      aria-expanded="false"><i class="fas fa-chevron-circle-down"></i> Dropdown</a>
                    <div class="dropdown-menu dropdown-primary" aria-labelledby="navbarDropdownMenuLink">
                      <a class="dropdown-item" href="#game"><i class="fas fa-gamepad"></i> GAMES</a>
                      <a class="dropdown-item" href="#soccer"><i class="fas fa-futbol"></i> SOCCER</a>
                      <a class="dropdown-item" href="#music"><i class="fas fa-music"></i> MUSIC</a>
                    </div>
                  </li>
          
                </ul>
               
          
                <form class="form-inline">
                  <div class="md-form my-0">
                    <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
                  </div>
                </form>
              </div>
             
          
            </div>
          
          </nav>

          <div id="intro" class="view">

            <div class="mask rgba-black-light" style="text-align: center;margin-top: 50px;">

               
                <h2 class="display-4 font-weight-bold white-text pt-5 mb-2"><i class="fas fa-heart red-text"></i> WELCOME<script style="color: yellow;">document.write("<h2> My Beloved "+username+"</h2>")</script><i class="fas fa-heart pink-text"></i></h2>

                <hr class="hr-light">

                <h4 class="white-text my-4">BLACK LIVES MATTER </h4>
                <div id="details" style="display: none;color: white;">

                    <p>愿世间，再无流离失所；愿众生，再无谎言愚弄；愿天下，再无不公</p>
             
                 </div>
                <button type="button" class="btn btn-outline-white" id="more">CLICK ME<i class="fas fa-book ml-2"></i></button>
              
                <br>
<!-- modalllllll -->
                <button type="button" class="btn btn-outline-danger" data-toggle="modal" data-target="#centralModalSuccess"><i class="fas fa-arrow-alt-circle-right"></i> CLICK ME  <i class="fas fa-arrow-alt-circle-left"></i>
               </button>
               
               
                <div class="modal fade" id="centralModalSuccess" tabindex="-1" role="dialog" aria-labelledby="myModalLabel"
                  aria-hidden="true">
                  <div class="modal-dialog modal-notify modal-danger" role="document">
                    <!--Content-->
                    <div class="modal-content">
                      <!--Header-->
                      <div class="modal-header">
                        <p class="heading lead">SURPRISE!!!</p>
               
                       
                      </div>
               
                      <!--Body-->
                      <div class="modal-body">
                        <div class="text-center">
                      
                          <img src="https://i.pinimg.com/originals/fd/b0/e0/fdb0e0bc978358c1a82ee712f7141739.jpg" alt="hahaha" width="100%" height="500px">
                          <br>
                          <p>It is just a little nerve stimulation to wake reader's mind up~~</p>
                        </div>
                      </div>
               
                 
                      <div class="modal-footer justify-content-center">
                        <a type="button" class="btn btn-danger" onclick="button1()">I LIKE IT<i class="far fa-gem ml-1 text-white"></i></a>
                        <a type="button" class="btn btn-outline-danger waves-effect" data-dismiss="modal">CLOSE</a>
                      </div>
                    </div>
                 
                  </div>
                </div>
            </div>
          
          </div>
<!-- /modalllllll -->
          <main class="mt-5">
         <div class="container">
           <div class="row d-flex justify-content-center mb-4">
           <div class="col-md-8">
             <h1 class="mb-5 font-weight-bold" style="margin-top: 50px;">Hello Welcome <i class="fas fa-heart pink-text"></i></h1>
             <p class="grey-text">Welcome to my project, hope you enjoy viewing my project and give high marks, as high as you can. Gracias...</p>
           </div>
           <div class="row">

           
            <div class="col-lg-4 col-md-4 mb-1">
              <i class="fas fa-home fa-4x blue-text"></i>
                <h4 class="my-4 font-weight-bold">Home</h4>
                <p class="grey-text">I have two siblings, my younger brother and sister, including my parents, this family is made of 5 members. I love my family. </p>
            </div>
          
            <div class="col-lg-4 col-md-4 mb-1">
                <i class="fas fa-guitar fa-4x brown-text"></i>
                <h4 class="my-4 font-weight-bold">Guitar</h4>
                <p class="grey-text">I love to play guitar. When I was stressed and exhausted, playing guitar helps to relieve my harassment</p>
            </div>
            

            <div class="col-lg-4 col-md-4 mb-1">
                <i class="fas fa-bicycle fa-4x purple-text"></i>
                <h4 class="my-4 font-weight-bold">My favourite Motivating Quotes</h4>
                <p class="grey-text">Do my Best, So that I can't blame myself for anything.<br>No Pain, No Gain<br>Don't Just Think, Just Do It.<br>Be Confident.Anything Is Possible.</p>
            </div>
           </div>
         </div>
         </main>

              <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img class="d-block w-100" src="https://wallpaperaccess.com/full/1526021.jpg"
                      alt="First slide">
                  </div>
                  <div class="carousel-item">
                    <img class="d-block w-100" src="https://wallpapercave.com/wp/gJvyuLv.jpg"
                      alt="Second slide">
                  </div>
                  <div class="carousel-item">
                    <img class="d-block w-100" src="https://i.pinimg.com/originals/27/3e/43/273e43a71854d8359186ecc348370f8d.jpg"
                      alt="Third slide">
                  </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="sr-only">Next</span>
                </a>
              </div>
              
              
<hr class="my-5">

<section style="margin: 50px;">

  <div class="row">
     
      <div class="col-lg-4 col-md-12 mb-4 view overlay zoom">
          <div class="view overlay z-depth-1-half">
              <img src="https://wallpapercave.com/wp/wp2981069.jpg" class="img-fluid">
              <div class="mask rgba-white-slight"><img src="https://cdn.wallpapersafari.com/44/0/DdaiWN.jpg" class="img-fluid">
              </div>
            <h6 class="text-center">London</h6>
          
          </div>
        
       
      </div>
   
      <div class="col-lg-4 col-md-6 mb-4 view overlay zoom">
          <div class="view overlay z-depth-1-half">
              <img src="https://i.pinimg.com/originals/36/3c/48/363c48c1b272daffc4c06288fe460683.jpg" class="img-fluid">
             
                <div class="mask rgba-white-slight"><img src="https://images8.alphacoders.com/420/420238.jpg" class="img-fluid">
                </div>
            
              <h6 class="text-center">Iceland</h6>
            </div>
      
           
      </div>
     
      <div class="col-lg-4 col-md-6 mb-4 view overlay zoom">
          <div class="view overlay z-depth-1-half">
              <img src="https://i.pinimg.com/originals/06/77/f2/0677f2797786574d55a971543f8adb31.jpg" class="img-fluid">
            
                <div class="mask rgba-white-slight">
                  <img src="https://cdn.wallpapersafari.com/38/69/sxYv2N.jpg" class="img-fluid">
                </div>
           
            </div>
            <h6 class="text-center">Maldives</h6>
      </div>

  </div>
 
  <div class="row">
   
      <div class="col-lg-6 col-md-12 mb-4 view overlay zoom">
        <div class="view overlay z-depth-1-half">
        <img src="https://wallpapercave.com/wp/wp2305557.jpg" class="img-fluid">
        
        <div class="mask rgba-white-slight">
          <img src="https://wallpaperaccess.com/full/1193022.jpg" class="img-fluid">
        </div>
          <h6 class="text-center">Mars</h6>
      </div>
      </div>
       
        <div class="col-lg-6 col-md-12 mb-4 view overlay zoom" >
          <div class="view overlay z-depth-1-half"></div>
          <img src="https://wallpaperaccess.com/full/33924.jpg" class="img-fluid">
          
          <div class="mask rgba-white-slight">
            <img src="http://i.imgur.com/OOFWl4K.jpg" class="img-fluid">
          </div>
            <h6 class="text-center">China</h6>
      </div>
      </div>

  </div>
  <h4 class="my-4 font-weight-bold">Traveling</h4>
  <p class="grey-text">We travel, is not to escape life, but for life not to escape us.<br>Ya, Mars. I would like to join Elon Musk's project which is visit the Mars Planet, if I have the oppurtunity....</p>
</section>   
<hr class="my-5">
<section id="me">
  <div class="container-fluid" style="background-color: #1abc9c;" >
    <br>
     <h2 class="text-center white-text" id="font">WHO AM I ?</h2>
     <br>
     <div class="img"><img src="https://blog.radware.com/wp-content/uploads/2020/06/anonymous.jpg" class="img-fluid rounded-circle hoverable"
      alt="hoverable">
    </div>
     <br>
  <h4 class="text-center white-text" id="font" >I AM Inevitable & Anonymous</h4>
  <br>
</div>
  <div class="container-fluid" id="mebg">
    <h2 class="text-center white-text " id="font">Who Am I?</h2>
    <p class="text-center white-text" id="font" style="padding-top: 25px;">My name is Chee Kar Jun, an ordinary person but borned with a nice and handsome appearance. I love to sleep, eat, eat, and sleep. When I was 18,<br>I found coding very interesting, but when I truly started to learn it, I found it so hard to actually code by my own.......<br>HOWEVER, I will not give up. I know I can do it because I am supercalifragilisticexpialidocious (awesome)</p>

  </div>
  <br>
  <div class="container">
  <div class="row">
  
    <div class="col-lg-4 col-md-12 mb-4">

      <h4 class="my-4 font-weight-bold">Futsal (Hobby)</h4>
      <p class="grey-text">Futsal (also known as fútsal or footsal) is a football game played on a hard court, smaller than a football pitch, and mainly indoors. It has similarities to five-a-side football. Futsal is played between two teams of five players each, one of whom is the goalkeeper.<br>I love Futsal</p>
        <div class="view overlay z-depth-1-half">
            <img src="https://www.wallpapertip.com/wmimgs/228-2286695_futsal-wallpaper-hd.jpg" class="img-fluid" >
            <div class="mask rgba-white-slight"><img src="https://lh3.googleusercontent.com/proxy/vd29WFgLV8Y6pyARzcYV1p60H5-2TsxInAB3KTlLc1a_fJ_n5SzzKjq6eyHPKouRHCwMqHRuWcZE2-_6TtZPqAan2Df-eUIOKrQaIMSjN2elSAVZogImKSHH8ilgKN-HfUHJsMR_wA" class="img-fluid">
            </div>
                   
        </div>
     
    </div>
  
    <div class="col-lg-4 col-md-12 mb-4">

      <h4 class="my-4 font-weight-bold">Warren Buffett (Idol)</h4>
      <p class="grey-text">Buffett is chairman and largest shareholder of Berkshire Hathaway since 1970. He has been referred to as the "Oracle" or "Sage" of Omaha by global media. He is noted for his adherence to value investing.<br>Investing is one of my interest. I'll start investing using Buffett's strategy, which is Value Investing</p>

        <div class="view overlay z-depth-1-half">
            <img src="https://www.quietrev.com/wp-content/uploads/2015/03/warren-buffett_SOURCE_wallstreetplaybook.jpg" class="img-fluid">
          
              <div class="mask rgba-white-slight">
                <img src="https://wallpapercave.com/wp/wp2128226.jpg" class="img-fluid">
              </div>
         
          </div>
    
    </div>
  
    <div class="col-lg-4 col-md-12 mb-4">

      <h4 class="my-4 font-weight-bold">Sleep (Interest)</h4>
      <p class="grey-text">A good laugh and a long sleep are the best cures in the doctor's book.<br>The best thing to do first thing in the morning is to go right back to sleep. Sleep is the best meditation. Learn from yesterday, live for today, look to tomorrow, rest this afternoon.<br>Think less,Sleep more.</p>

        <div class="view overlay z-depth-1-half">
            <img src="https://images8.alphacoders.com/816/thumb-1920-816929.jpg" class="img-fluid">
            
              <div class="mask rgba-white-slight">
                <img src="http://integrisok.com/-/media/service-lines/inok_services_sleep_medicine_01.ashx?revision=72fe9d6d-0d67-4955-80e9-2d9fa5acc277" class="img-fluid">
              </div>
         
          </div>
    </div>

</div>
</div>
</section>
<hr class="my-5">
<!-- MOVIEEEEEEE -->
<section>
<div id="movie" class="flex-center">

  <div class="mask rgba-black-strong" style="text-align: center;padding:20px ;">

     
      <h2 class="display-4 font-weight-bold white-text pt-5 mb-2"><i class="fas fa-video fa-spin"></i>  MOVIE</h2>

      <h4 class="white-text my-4">When alone, movie is our best soulmate.<br><br>「電影的發明使我們的人生延長了三倍，因為我們在裡面獲得了至少兩倍不同的人生經驗。」<br>
        這就是我們之所以愛電影吧。</h4>
      
</div>
</div>
<br>
<div class="col-lg-8" style="padding-left: 50px;">
  <h4 class="my-4 font-weight-bold">Movies</h4>
  <p >Grab some snacks, open the aircon, sit on sofa, enjoy your weekend.</p><p class="grey-text">曾经有一份真诚的爱情放在我面前，我没有珍惜，等我失去的时候我才后悔莫及，人世间最痛苦的事莫过于此。
    如果上天能够给我一个再来一次的机会，我会对那个女孩子说三个字：我爱你。
    如果非要在这份爱上加上一个期限，我希望是……
    一万年---------周星驰</p></div>
  <div class="row">
    
    <div class="col-lg-12 col-md-12 " style="padding: 20px;">

     
      <div id="carousel-example-1z" class="carousel slide" data-ride="carousel" data-interval="2000">
    
        <div class="carousel-inner" role="listbox">
         
          <div class="carousel-item active">
            <img class="d-block w-100" src="https://wallpaperaccess.com/full/861811.jpg"
              alt="First slide">
          </div>
         
          <div class="carousel-item">
            <img class="d-block w-100" src="https://wallpapercave.com/wp/wp2592272.jpg"
              alt="Second slide">
          </div>
        
          <div class="carousel-item">
            <img class="d-block w-100" src="https://wallpaperaccess.com/full/329583.jpg"
              alt="Third slide">
          </div>

          <div class="carousel-item">
            <img class="d-block w-100" src="https://images7.alphacoders.com/915/thumb-1920-915515.jpg" alt="forthSlide">
          </div>
           
          <div class="carousel-item">
            <img class="d-block w-100" src="https://wallpaperaccess.com/full/1077150.jpg" alt="fifthSlide">
          </div>
  
          <div class="carousel-item">
            <img class="d-block w-100" src="https://wallpapercave.com/wp/wp3191907.jpg" alt="sixthSlide">
          </div>

          <div class="carousel-item">
            <img class="d-block w-100" src="https://wallpaperaccess.com/full/4503750.jpg" alt="seventhSlide">
          </div>

        </div>
      
        <a class="carousel-control-prev" href="#carousel-example-1z" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carousel-example-1z" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
   
      </div>
    </div>
    <!-- buttonYT -->

<div class="col-lg-4 col-md-12 col-sm-12" id="drama">
 <h4 class="my-4 font-weight-bold">Some Free Movies on Youtube <i class="fab fa-youtube red-text"></i></h4>
 <br>
 <br>
 <br>
 
 <button type="button" class="btn btn-grey" data-toggle="modal" data-target="#modalYT" style="width: 100%">Shaolin Soccer 少林足球</button>

<div class="modal fade" id="modalYT" tabindex="-1" role="dialog" aria-labelledby="myModalLabel"
  aria-hidden="true">
  <div class="modal-dialog modal-lg" role="document">

    <div class="modal-content">

      <div class="modal-body mb-0 p-0">

        <div class="embed-responsive embed-responsive-16by9 z-depth-1-half">
          <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Bihh-Ac-Z6s"
            allowfullscreen></iframe>
        </div>
        </div>
      </div>
     </div>
    </div>
    <br>
    <br>
        
    <!-- SECONDbutton -->
    <button type="button" class="btn btn-grey" data-toggle="modal" data-target="#modalYT2" style="width: 100%">AVATAR 阿凡达
</button>


<div class="modal fade" id="modalYT2" tabindex="-1" role="dialog" aria-labelledby="myModalLabel"
  aria-hidden="true">
  <div class="modal-dialog modal-lg" role="document">


    <div class="modal-content">

      <div class="modal-body mb-0 p-0">

        <div class="embed-responsive embed-responsive-16by9 z-depth-1-half">
          <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/WlI72lnN5BU"
            allowfullscreen></iframe>
        </div>
       
      </div>
    </div>
  </div>
</div>
      <br>
      <br>
      
      <!-- THIRD button -->
      <button type="button" class="btn btn-grey" data-toggle="modal" data-target="#modalYT3" style="width: 100%">Your Name 你的名字</button>


<div class="modal fade" id="modalYT3" tabindex="-1" role="dialog" aria-labelledby="myModalLabel"
  aria-hidden="true">
  <div class="modal-dialog modal-lg" role="document">


    <div class="modal-content">

    
      <div class="modal-body mb-0 p-0">

        <div class="embed-responsive embed-responsive-16by9 z-depth-1-half">
          <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/aZiHVkZ9Yps"
            allowfullscreen></iframe>
        </div>
      </div>
     </div>
    </div>
  </div>
</div>
<!-- 2nd -->
<div class="col-lg-4 col-md-12 col-sm-12" id="drama">
  <h4 class="my-4 font-weight-bold">Netflix Popular Drama Series: <br>Peaky Blinders <i class="fas fa-user-tie black-text"></i></h4>

  <div id="pbcarousel" class="carousel slide" data-ride="carousel" data-interval="1800">
    <div class="carousel-inner" id="pbcarousel">
      <div class="carousel-item active">
        <img class="d-block w-100" src="https://cdn.thegentlemansjournal.com/wp-content/uploads/2019/08/peaky-blinders-tailoring-header-2.png"
          alt="First slide" id="imgpb">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://thumbs-prod.si-cdn.com/Frk9N0whaZA7dSd13Tbcwd0-bbU=/420x240/filters:focal(634x85:635x86)/https://public-media.si-cdn.com/filer/7b/ba/7bba298e-7e2e-44f0-adb9-b47dfdc1e240/p05m69vt.jpg"
          alt="Second slide" id="imgpb">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://metro.co.uk/wp-content/uploads/2017/05/greggwallace-peakyblinders.jpg?quality=90&strip=all&w=1200&h=630&crop=1"
          alt="Third slide" id="imgpb">
      </div>
    </div>
</div>
</div>
<!-- 3rd -->
<div class="col-lg-4 col-md-12 col-sm-12" id="drama">
  <h4 class="my-4 font-weight-bold">Check weither you are suitable to watch the PEAKY BLINDERS (UNDER 18) <i class="fas fa-exclamation-triangle orange-text" ></i></h4>
<!-- form -->
<form method="post" action="https://www.netflix.com/my-en/title/80002479" onsubmit="return validateForm();" name="form">
  <div class="input-group mb-3">
    <div class="input-group-prepend">
      <span class="input-group-text" id="basic-addon1">Name</span>
    </div>
    <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="basic-addon1" name="userName" id="userName" required>
  </div>
  
  <div class="input-group mb-3">
    <input type="text" class="form-control" placeholder="Age" aria-label="Age" name="userAge" id="userAge"
      aria-describedby="basic-addon2" required>
    <div class="input-group-append">
      <span class="input-group-text" id="basic-addon2">Age</span>
    </div>
  </div>
  
  <div class="input-group">
    <div class="input-group-prepend">
      <span class="input-group-text">Reason</span>
    </div>
    <textarea class="form-control" aria-label="With textarea"></textarea>
  </div><br>
  <button class="btn btn-outline-grey btn-rounded btn-block" type="submit">Submit</button>
</div>
</form>
<!-- 分开 -->
<div class="container mt-5">

    <section class="dark-grey-text">

    <div class="container-fluid" id="mv"><h2 class="text-center font-weight-bold">MOVIES</h2>
      </div>
       <br>
 
    <p class="text-center">Movies move us like nothing else can, whether they're scary, funny, dramatic, romantic or anywhere in-between. So many titles, so much to experience.</p>
    <p class="text-center grey-text">电影，无论是令人恐惧，有趣，戏剧性，浪漫还是介于两者之间的任何事物，都使我们感动不已。 这么多的标题，那么多的故事。</p>
<br>
    <div class="row align-items-center">
  
      <div class="col-lg-5">
        <div class="view overlay rounded z-depth-2">
          <img class="img-fluid" src="https://images3.alphacoders.com/674/thumb-1920-674346.jpg" alt="Sample image">
          <a href="https://play.google.com/store/movies/details?id=F8dABMvqoT4">
            <div class="mask">
              <img src="https://images3.alphacoders.com/674/thumb-1920-674364.jpg" class="img-fluid">
            </div>
          </a>
        </div>

      </div>
      <div class="col-lg-7">

        <a href="#!" class="grey-text">
          <h6 class="font-weight-bold mb-3"><i class="fas fa-flask blue-text fa-spin"></i> SCIENCE FICTION</h6>
        </a>
       
        <h4 class="font-weight-bold blue-text"><strong>AVATAR</strong></h4>
     
        <p>A paraplegic Marine dispatched to the moon Pandora on a unique mission becomes torn between following his orders and protecting the world he feels is his home. When his brother is killed in a robbery, paraplegic Marine Jake Sully decides to take his place in a mission on the distant world of Pandora.</p>
     
        <a class="btn btn-blue btn-rounded " href="https://en.wikipedia.org/wiki/Avatar_(2009_film)">Read more</a>

      </div>
      
    </div>

    </section>
</div>
<!-- fen kai -->
<div class="container mt-5">
  <div class="row align-items-center">
    <div class="col-lg-7">

      <a href="#!" class="grey-text">
        <h6 class="font-weight-bold mb-3"><i class="fas fa-flask red-text fa-spin"></i> SCIENCE FICTION</h6>
      </a>
     
      <h4 class="font-weight-bold mb-3 red-text"><strong>Transformers</strong></h4>
   
      <p>An ancient struggle between two Cybertronian races, the heroic Autobots and the evil Decepticons, comes to Earth, with a clue to the ultimate power held by a teenager. High-school student Sam Witwicky buys his first car, who is actually the Autobot Bumblebee.</p>
   
      <a class="btn btn-red btn-rounded"href="https://en.wikipedia.org/wiki/Transformers_(film)">Read more</a>

    </div>
    <div class="col-lg-5">
      <div class="view overlay rounded z-depth-2">
        <img class="img-fluid" src="https://wallpapercave.com/wp/rFYqLaK.jpg" alt="Sample image" >
        <a href="https://www.netflix.com/my-en/title/70058026">
          <div class="mask">
            <img src="https://wallpaperaccess.com/full/1595489.jpg" class="img-fluid">
          </div>
        </a>
      </div>

    </div>
    
    </div>
</div>

<!-- fen kai -->
<div class="container mt-5">
  <div class="row align-items-center">
  
    <div class="col-lg-5">
      <div class="view overlay rounded z-depth-2">
        <img class="img-fluid" src="https://img1.looper.com/img/gallery/the-ending-of-annabelle-creation-explained/intro-1506455881.jpg" alt="Sample image">
        <a href="https://www.netflix.com/my-en/title/80013775">
          <div class="mask">
            <img src="https://wallpapercave.com/wp/wp1994791.jpg" class="img-fluid">
          </div>
        </a>
      </div>

    </div>
    <div class="col-lg-7">

      <a href="#!" class="grey-text">
        <h6 class="font-weight-bold mb-3"><i class="fas fa-ghost fa-spin"></i> HORROR</h6>
      </a>
     
      <h4 class="font-weight-bold mb-3"><strong>Annabelle</strong></h4>
   
      <p>A husband and a wife are happily married and expecting a child. Mia (the wife) has to stay at home until the baby is delivered. Then, one night, when her husband came home from work, he brought home a present for his miserable wife. He brought home a doll named Annabelle, for her collection.</p>
   
      <a class="btn btn-black btn-rounded " href="https://en.wikipedia.org/wiki/Annabelle_(film)" >Read more</a>

    </div>
    
    </div>
</div>
</section>
<!-- END of Movie -->
<br>
<hr>
<br>
<!-- GAMESSSSSSSSS -->
<section id="game">
  <div id="gameheading">
   <h1 class="text-center black-text"><i class="fas fa-gamepad fa-spin red-text"></i> GAMES <i class="fas fa-gamepad fa-spin blue-text"></i></h1>
  </div>
  <div class="row no-margin">
    <div class="col-lg-4  col-sm-12">
      
          <img src="https://cdn.vox-cdn.com/thumbor/KitwOGpLgoAytDlQm61rMg2pyHM=/0x0:1920x1080/1200x800/filters:focal(807x387:1113x693)/cdn.vox-cdn.com/uploads/chorus_image/image/68973193/EN_16BR_Social_KeyArt_Social.0.jpg" width="520" height="300"/>
        </a>

    </div>
    <div class="col-lg-4 col-md-12">
          <img src="https://tecake.com/wp-content/uploads/2020/10/apex-legends.jpg" width="520" height="300" />
        </a>

    </div>
    <div class="col-lg-4 col-md-12">
     
          <img src="https://www.talkesport.com/wp-content/uploads/csgo-visibility-update-appears-to-reveal-opponents-through-walls.jpg" width="520" height="300" />
        </a>

    </div>
    <div class="col-lg-4 col-md-12">
    
          <img src="https://img.republicworld.com/republic-prod/stories/promolarge/xxhdpi/afsxs3xawu4w0o62_1603716952.jpeg?tr=w-758,h-433" width="520" height="300"/>
        </a>

    </div>
    <div class="col-lg-4 col-md-12">
     
          <img src="https://www.konami.com/wepes/mobile/s/img/pes2021_ogp.png" width="520" height="300" />
        </a>

    </div>
    <div class="col-lg-4 col-md-12">
      
          <img src="https://image.api.playstation.com/vulcan/img/cfn/11307uYG0CXzRuA9aryByTHYrQLFz-HVQ3VVl7aAysxK15HMpqjkAIcC_R5vdfZt52hAXQNHoYhSuoSq_46_MT_tDBcLu49I.png" width="520" height="300"/>
        </a>

    </div>
    <div class="col-lg-4 col-md-12">
      
          <img src="https://cdn.gamer-network.net/2017/articles/2017-10-23-15-36/rockstar-did-not-think-gta-5-single-player-expansions-were-either-possible-or-necessary-1508769413396.jpg/EG11/thumbnail/1920x1277/format/jpg/quality/80" width="520" height="300" />
        </a>

    </div>
    <div class="col-lg-4 col-md-12">
     
          <img src="https://i.gadgets360cdn.com/large/cod_mobile_main_1570103396815.jpg" width="520" height="300"/>
        </a>

    </div>
    <div class="col-lg-4 col-md-12">
     
          <img src="https://d2skuhm0vrry40.cloudfront.net/2020/articles/2020-11-29-12-58/-1606654686177.jpg/EG11/thumbnail/750x422/format/jpg/quality/60" width="520" height="300"/>
        </a>

    </div>
  </div>
<br>
<br>
  <div class="container">
    <section class="dark-grey-text text-center">
  
      <h3 class="text-center font-weight-bold mb-3 ">Gaming Platform</h3>
      <p class="text-center text-muted w-responsive mx-auto mb-5">According to different interests, gamers will use their favourite platform to play their favourite games.</p>
  
      <div class="row">
          <div class="col-lg-4 col-md-12">
  
          <div class="view overlay z-depth-1">
            <img src="https://i.pinimg.com/originals/61/b5/33/61b533e8092ebcec97e1ed4aa41decca.png" class="img-fluid" alt="Sample image">
            <div class="mask rgba-black-slight">
              <h4 class="text-center white-text">Gaming PC</h4>
            </div>
          </div>
  
        </div>
      
        <div class="col-lg-4 col-md-6 ">
  
          <div class="view overlay z-depth-1">
            <img src="https://cdn.mos.cms.futurecdn.net/bcB3Kdypuv8MAA5GZZM3b.png" class="img-fluid" alt="Sample image">
            <div class=" mask rgba-black-slight">
              <h4 class="text-center black-text">PS5</h4>
            </div>
          </div>
    
        </div>
      
        <div class="col-lg-4 col-md-6">
  
          <div class="view overlay z-depth-1">
            <img src="https://wallpaperaccess.com/full/3478353.jpg" class="img-fluid" alt="Sample image">
            <div class="mask rgba-black-slight">
              <h4 class="text-center white-text">Nintendo Switch</h4>
            </div>
          </div>
      
        </div>
   
        <div class="col-lg-4 col-md-12">
  
          <div class="view overlay z-depth-1">
            <img src="https://images.wallpaperscraft.com/image/phone_smartphone_hand_144060_1920x1080.jpg" class="img-fluid" alt="Sample image">
            <div class="mask rgba-black-slight">
              <h4 class="text-center white-text">Mobile Phone</h4>
            </div>
          </div>
       
        </div>
      
        <div class="col-lg-4 col-md-6 ">
  
          <div class="view overlay z-depth-1">
            <img src="https://i.pinimg.com/originals/7d/68/8d/7d688d72135f64b73d1e3741c500ca21.jpg" class="img-fluid" alt="Sample image">
            <div class=" mask rgba-black-slight">
              <h4 class="text-center white-text">X-BOX</h4>
            </div>
          </div>
      
        </div>
      
        <div class="col-lg-4 col-md-6">
  
          <div class="view overlay z-depth-1">
            <img src="https://cdn.wallpapersafari.com/76/3/oG1qJi.jpg" class="img-fluid " alt="Sample image">
            <div class="mask rgba-black-slight">
              <h4 class="text-center white-text">PSP</h4>
            </div>
          </div>
          
        </div>
   
      </div>
      
      <br>
      <h2 class="font-weight-bold">GAMES</h2>
      <p class="grey-text">Escape reality And play GAMES<br>人间几十年，看世事梦幻似水，与天相比，游戏，不过渺小一物，却使人生变得更精彩。</p>
     
 <div class="row">
      <div class="col-lg-4 col-md-12">
  
        <div class="view overlay z-depth-1">
          <img src="https://5b0988e595225.cdn.sohucs.com/images/20180326/c4e515e6d30a4745a4510882cb86d612.jpeg" class="img-fluid" alt="Sample image">
          <div class="mask rgba-black-strong">
          <img src="https://uhdwallpapers.org/uploads/converted/19/08/12/fortnite-season-x-image-4k-1920x1080_477799-mm-90.jpg" class="img-fluid">
          </div>
        </div>
        <br>
        <div class="grey-text " id="details1" ></div>
        <button class="btn btn-outline-grey" onclick="more1()">Name</button>
      
      </div>
    
      <div class="col-lg-4 col-md-6 ">

        <div class="view overlay z-depth-1">
          <img src="https://images6.alphacoders.com/992/thumb-1920-992033.jpg" class="img-fluid" alt="Sample image">
          <div class=" mask rgba-black-strong">
            <img src="https://images.hdqwalls.com/download/4k-apex-legends-2020-ja-1920x1080.jpg" class="img-fluid" alt="Sample image">
          </div>
        </div>
        <br>
        <div class="grey-text " id="details2" ></div>
        <button class="btn btn-outline-grey" onclick="more2()">Name</button>
      </div>
    
      <div class="col-lg-4 col-md-6">

        <div class="view overlay z-depth-1">
          <img src="https://images6.alphacoders.com/107/thumb-1920-1072679.jpg" class="img-fluid " alt="Sample image">
          <div class="mask rgba-black-strong">
            <img src="https://i.redd.it/mrsexq9x68p41.jpg" class="img-fluid" alt="Sample image">
          </div>
        </div>
        <br>
        <div class="grey-text " id="details3" ></div>
        <button class="btn btn-outline-grey" onclick="more3()">Name</button>
      </div>
  </div>
  <br>
  <hr>
  <!-- pill -->
  <h1 class="grey-text " id="gamepilltitle">TYPES of GAMES</h1>
  <ul class="nav md-pills nav-justified " id="pills-tab" >
    <li class="nav-item">
      <a class="nav-link active" id="pills-home-tab" data-toggle="pill" href="#pills-1" role="tab"
        aria-controls="pills-home" aria-selected="true"><p class="grey-text">Shooter(FPS)</p></a>
    </li>
    <li class="nav-item">
      <a class="nav-link" id="pills-profile-tab" data-toggle="pill" href="#pills-2" role="tab"
        aria-controls="pills-profile" aria-selected="false"><p class="grey-text">Multiplayer online battle arena (MOBA)</p></a>
    </li>
    <li class="nav-item">
      <a class="nav-link" id="pills-contact-tab" data-toggle="pill" href="#pills-3" role="tab"
        aria-controls="pills-contact" aria-selected="false"><p class="grey-text">Stimulation and Sport</p></a>
    </li>
  </ul>
  <div class="tab-content pt-2 pl-1" id="pills-tabContent">
    <div class="tab-pane fade show active" id="pills-1" role="tabpanel" aria-labelledby="pills-home-tab">The shooter is another long-standing genre that developed several early offshoots and branched out into two primary sub-genres: the first-person shooter (FPS) and third-person shooter (TPS).
      There’s plenty of potential for overlap here, too, since many contemporary titles allow you to toggle between first and third-person viewpoints. Not only that, but most battle royale games – a sub-genre unto itself – operate as either first or third-person shooters, including Fortnite and PlayerUnknown’s Battlegrounds.<br><br><br>
      <div class="row">
        <div class="col-lg-4">
          <div class="view overlay z-depth-1">
            <img src="https://wallpaperaccess.com/full/875246.jpg" class="img-fluid" alt="Sample image">
        </div>
      </div>

      <div class="col-lg-4">
        <div class="view overlay z-depth-1">
          <img src="https://wallpaperaccess.com/full/1368836.jpg" class="img-fluid" alt="Sample image">
      </div>
    </div>

    <div class="col-lg-4">
      <div class="view overlay z-depth-1">
        <img src="https://images8.alphacoders.com/716/thumb-1920-716460.jpg" class="img-fluid" alt="Sample image">
    </div>
  </div>
      </div>
      </div>
    <div class="tab-pane fade" id="pills-2" role="tabpanel" aria-labelledby="pills-profile-tab">An increasingly popular subgenre with connections to a variety of other styles, multiplayer online battle arena games share many features with real-time strategy games. There’s a top-down perspective that emphasizes map and resource management, plus real-time competition between players.
      The major difference between MOBAs and RTS games is the player’s character and role. In a MOBA, you may have a faction alignment and many of the RTS basics in play, but you typically only control a single character. That’s a significant contrast with most RTS games, where you build communities and command multiple units.
    <br><br>
      <div class="row">
        <div class="col-lg-4">
          <div class="view overlay z-depth-1">
            <img src="https://images8.alphacoders.com/406/thumb-1920-406809.jpg" class="img-fluid" alt="Sample image">
        </div>
      </div>

      <div class="col-lg-4">
        <div class="view overlay z-depth-1">
          <img src="https://wallpapercave.com/wp/wp2532627.jpg" class="img-fluid" alt="Sample image">
      </div>
    </div>

    <div class="col-lg-4">
      <div class="view overlay z-depth-1">
        <img src="https://image.diyiyou.com/game/201905/24/1558685799_9.jpg" class="img-fluid" alt="Sample image">
    </div>
  </div>
      </div>  
    </div>

    <div class="tab-pane fade" id="pills-3" role="tabpanel" aria-labelledby="pills-contact-tab">These genres have evolved a lot over the years and you may actually see them in the same light. But it’s only with advances in graphics technology that they’ve begun to offer unique immersive experiences. The latest iterations provide impressive levels of detail and showcase just how much is possible with games.
Sports games have expanded in variety, offering full-fledged partnerships with major sporting organizations, from race tracks to the field or court. NBA 2K and Madden NFL are two well-known examples that feature detailed recreations of professional basketball and football, while Forza is a simulation-style car racing game.<br><br>

<div class="row">
  <div class="col-lg-4">
    <div class="view overlay z-depth-1">
      <img src="https://wallpapercave.com/wp/wp8012662.jpg" class="img-fluid" alt="Sample image">
  </div>
</div>

<div class="col-lg-4">
  <div class="view overlay z-depth-1">
    <img src="https://wallpaperaccess.com/full/3406334.jpg" class="img-fluid" alt="Sample image">
</div>
</div>

<div class="col-lg-4">
<div class="view overlay z-depth-1">
  <img src="https://images5.alphacoders.com/929/thumb-1920-929552.jpg" class="img-fluid" alt="Sample image">
</div>
</div>
</div>
</div>
  </div>
    </section>
  </div>
  <br>
  <br>
  <!-- youtbubeCarousellllllllll -->
  <div id="gamecarousel" class="carousel slide carousel-fade" data-ride="carousel" data-interval="false">

 
    <div class="carousel-inner" role="listbox">
  
      <div class="carousel-item active">
        <iframe width="100%" height="650"
        src="https://www.youtube.com/embed/IWwlislIBIY" allowfullscreen>
        </iframe>
      </div>
     
      <div class="carousel-item">
        <iframe width="100%" height="650"
        src="https://www.youtube.com/embed/qsKolB4HPuM" allowfullscreen>
        </iframe>
      </div>

      <div class="carousel-item">
        <iframe width="100%" height="650"
        src="https://www.youtube.com/embed/kGRiq-s34os" allowfullscreen>
        </iframe>
      </div>
 
    </div>
  
    <a class="carousel-control-prev" href="#gamecarousel" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#gamecarousel" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  
  </div>
</section>
<br>
<hr>
<!-- FOOTBALLLLLLLLLLLLLLLLL -->
<section id="soccer">
<h1 class="grey-text text-center" id="soccertitle"><i class="fas fa-futbol fa-spin purple-text"></i> SOCCER <i class="fas fa-futbol fa-spin pink-text"></i></h1> <br>

<p class="black-text text-center m-3" ><em><span class="black-text font-weight-bold">#1 LovingFootballSoccer <i class="fas fa-heart red-text"></i></span></em><br><br>

  When you're part of a team, it's like having an extra family. These guys will be there for you no matter what. You support one another when times get hard and celebrate when you win. If you want to feel as though you are a part of something special, you should join a football, team.</p>

  <p class="grey-text text-center m-3" >

    足球的世界是个单纯的世界。即使在一些贫民区，无论生活多么的沉重，踢足球的孩子永远会保持着单纯的笑容。</p>

<div id="soccercarousel" class="carousel slide carousel-fade" data-ride="carousel" data-interval="3000">

 
  <div class="carousel-inner" role="listbox">

    <div class="carousel-item active">
    <img src="https://cdn.wallpapersafari.com/15/39/FjVPQa.jpg" width="100%" height="700px" alt="soccer">
    </div>
   
    <div class="carousel-item">
      <img src="https://i.pinimg.com/originals/8b/19/2f/8b192f82b65a429b2d4d079cf87b30ec.jpg" width="100%" height="700px" alt="soccer">
    </div>

    <div class="carousel-item">
      <img src="https://images.performgroup.com/di/library/GOAL/bf/4a/cristiano-ronaldo-juventus-real-madrid-champions-league-2017-18_lhz69ekq2t971w72jtdu535jh.png?t=1881870404&w=1920&h=1080" width="100%" height="700px" alt="soccer">
    </div>
    
    
    <div class="carousel-item">
      <img src="https://i.pinimg.com/originals/44/2b/cd/442bcdf5df69e3ba451ad593262248d5.jpg" width="100%" height="700px" alt="soccer">
    </div>

    
    <div class="carousel-item">
      <img src="https://www.teahub.io/photos/full/171-1719753_england-manager-a-dream-job-david-beckham-football.jpg" width="100%" height="700px" alt="soccer">
    </div>

    
    <div class="carousel-item">
      <img src="https://wallpaperaccess.com/full/2315232.jpg" width="100%" height="700px" alt="soccer">
    </div>

    
    <div class="carousel-item">
      <img src="https://wallpaperaccess.com/full/1424715.jpg" width="100%" height="700px" alt="soccer">
    </div>

      
    <div class="carousel-item">
      <img src="https://wallpaperaccess.com/full/483263.jpg" width="100%" height="700px" alt="soccer">
    </div>

      
    <div class="carousel-item">
      <img src="https://images.daznservices.com/di/library/GOAL/8e/10/kylian-mbappe-psg-dijon-ligue-1-29022020_7rtje1wbvb771syoibzl1w2rs.jpg?t=-1778440560&quality=100" width="100%" height="700px" alt="soccer">
    </div>

      
    <div class="carousel-item">
      <img src="https://www.wallpapertip.com/wmimgs/157-1574974_sergio-ramos-y-messi.jpg" width="100%" height="700px" alt="soccer">
    </div>
  </div>

  <a class="carousel-control-prev" href="#soccercarousel" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#soccercarousel" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>

</div>
<br>
<!-- TEAMsssssssssssss -->
<h1 class="blue-text text-center" id="gameheading">MY FAVOURITE TEAM <i class="fas fa-futbol red-text"></i></h1>
<div class="container pt-5 my-4 z-depth-1 " id="barcelona">
  <section class="p-md-3 mx-md-5 text-center">
    <h2 class="text-center white-text font-weight-bold mb-4 pb-2"><i class="fas fa-users red-text"></i> Barcelona <i class="fas fa-users blue-text"></i></h2>
    <div class="row mask rgba-stylish-strong">
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/08/15509bbc-3a89-4fea-94e0-a48aeebe5df9/mini_TER-STEGEN-copia.png?width=670&height=790" class="rounded-circle z-depth-1" width="200px" height="200px" />
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Ter Stegen</h6>
            <p class="white-text">
              <small><i>Goalkeeper</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/08/72f9412a-048e-45f3-8bb8-86381cf728c5/mini_LENGLET.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Cle. Lenglet</h6>
            <p class="white-text">
              <small><i>Centre Back Defender</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/08/01a02c3b-63bd-4ddc-ae15-76907886d8ed/mini_PIQU-.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Gerard Pique</h6>
            <p class="white-text">
              <small><i>Centre Back Defender</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/08/d30c761d-fcb3-4de9-8d93-60edb745f61c/mini_jordi-alba.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Jordi Alba</h6>
            <p class="white-text">
              <small><i>Left Back Defender</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/08/a7cb563e-a998-46a0-897b-12e319b89ac7/mini_DEST.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Sergino Dest</h6>
            <p class="white-text">
              <small><i>Right Back defender</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/13/5fff7dbd-9963-4121-91de-eecf286c753f/mini_1920x1080-coutinho.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Philippe Continho</h6>
            <p class="white-text">
              <small><i>Attacker.Attacking Midfielder</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/08/ac507a09-945f-48c7-8937-2cd3b65992a2/mini_busquets.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Sergio Busquets</h6>
            <p class="white-text">
              <small><i>Defender.Defensive Midfielder</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/08/c32fc593-a16d-4471-a808-74489cff5a15/mini_de-jong.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Frenkie De Jong</h6>
            <p class="white-text">
              <small><i>Central Midfielder</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/13/1cf497ec-9b61-43f7-b353-f238dfa0fc5d/mini_1920x1080-ansu.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Ansu Fati</h6>
            <p class="white-text">
              <small><i>Left Winger.Speeding Bullet</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/08/9518739f-39fa-4729-b455-27a95966d5b4/mini_messi-copia.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Lionel Messi</h6>
            <p class="white-text">
              <small><i>Right Winger.Captain.</i></small>
            </p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-4 col-sm-6 mb-4">
        <div class="p-4">
          <div class="justify-content-center align-items-center">
            <img src="https://www.fcbarcelona.com/photo-resources/2020/10/08/2496225f-7f9c-4a7f-ad5c-820b806507c1/mini_GRIEZMANN.png?width=670&height=790" class=" rounded-circle z-depth-1"  width="200px" height="200px"/>
          </div>
          <div class="text-center mt-3">
            <h4 class="font-weight-bold white-text pt-2">Antoine Griezmann</h6>
            <p class="white-text">
              <small><i>Left Winger.Second Striker</i></small>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</div>
<!-- SuperStar -->
<div class="container">
  <h1 class="text-center purple-text" id="barca"><i class="fas fa-star"></i> SuperStars</h1>
  <div class="row ">
    <div class="col-sm-12 col-md-8 col-lg-4">
      <div class="rotate-container">
        <div class="card card-front text-center">
          <div class="card-background" style="background-image: url(https://images8.alphacoders.com/969/thumb-1920-969849.jpg);"></div>
          <div class="card-block"><img class="avatar" src="https://thumbor.forbes.com/thumbor/fit-in/416x416/filters%3Aformat%28jpg%29/https%3A%2F%2Fspecials-images.forbesimg.com%2Fimageserve%2F5ec593cc431fb70007482137%2F0x0.jpg%3Fbackground%3D000000%26cropX1%3D1321%26cropX2%3D3300%26cropY1%3D114%26cropY2%3D2093" alt="Avatar"/>
            <h3 class="card-title">Cristiano Ronaldo</h3>
            <p>JUVENTUS</p>
           
          </div>
        </div>
        <div class="card card-back text-center">
          <div class="card-header">
            <p>More About Him</p>
          </div>
          <div class="card-block">
            <h4>Left Winger</h4>
            <p>Cristiano Ronaldo, in full Cristiano Ronaldo dos Santos Aveiro, (born February 5, 1985, Funchal, Madeira, Portugal), Portuguese football (soccer) forward who was one of the greatest players of his generation.</p>

            
          </div>
        </div>
      </div>
    </div>

    <div class="col-sm-12 col-md-8 col-lg-4">
      <div class="rotate-container">
        <div class="card card-front text-center">
          <div class="card-background" style="background-image: url(https://www.teahub.io/photos/full/52-525064_tottenham-hotspur-wallpapers-tottenham-hotspur-wallpaper-hd.jpg);"></div>
          <div class="card-block"><img class="avatar" src="https://resources.premierleague.com/premierleague/photos/players/250x250/p85971.png" alt="Avatar"/>
            <h3 class="card-title">Son Heung Min 孙兴慜</h3>
            <p>TOTTENHAM HOTSPURS</p>
            <button class="btn btn-grey btn-rotate">Click to Triple Flip
            </button>
          </div>
        </div>
        <div class="card card-back text-center">
          <div class="card-header">
            <p>More About Him</p>
          </div>
          <div class="card-block">
            <h4>Left Winger / Left Midfielder</h4>
            <p>Son Heung-min (Korean: 손흥민 ; born 8 July 1992) is a South Korean professional footballer who plays as a forward for Premier League club Tottenham Hotspur and captains the South Korean national team。</p>

            <button class="btn btn-grey btn-rotate">Back </button>
          </div>
        </div>
      </div>
    </div>

    <div class="col-sm-12 col-md-8 col-lg-4">
      <div class="rotate-container">
        <div class="card card-front text-center">
          <div class="card-background" style="background-image: url(https://d3j2s6hdd6a7rg.cloudfront.net/v2/uploads/media/default/0001/40/thumb_39596_default_news_size_5.jpeg);"></div>
          <div class="card-block"><img class="avatar" src="https://resources.premierleague.com/premierleague/photos/players/250x250/p97032.png" alt="Avatar"/>
            <h3 class="card-title">Virgil Van Dijk</h3>
            <p>LIVERPOOL</p>
            
          </div>
        </div>
        <div class="card card-back text-center">
          <div class="card-header">
            <p>More About Him</p>
          </div>
          <div class="card-block">
            <h4>Centre Back: Defender</h4>
            <p>Virgil van Dijk is a Dutch professional footballer who plays as a centre-back for Premier League club Liverpool and captains the Netherlands national team. Considered one of the best defenders in the world, he is known for his strength, leadership and aerial ability.</p>

           
        </div>
      </div>
    </div>
  </div>
</div>
<br>
<!-- end of rotate cards -->
<div class="container">
  <h2 class="text-center" id="barca"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/4/47/FC_Barcelona_%28crest%29.svg/180px-FC_Barcelona_%28crest%29.svg.png" width="40px" height="40px" alt="barcelona"><span style="color: red;"> BARCE</span><span style="color: blue;">LONA</span></h2>
  <table class="table table-hover table-sm" cellspacing="0" width="100%">
    <thead class="black white-text">
      <tr>
        <th class="th-sm">Name</th>
        <th class="th-sm">Age</th>
        <th class="th-sm">Club</th>
        <th class="th-sm">Country</th>
        <th class="th-sm">Position</th>
        <th class="th-sm">Salary (per week)</th>
      </tr> 
    </thead>
    <tbody>
      <tr>
        <td>Lionel Messi</td>
        <td>33</td>
        <td>Barcelona</td>
        <td>Argentina</td>
        <td>Centre Forward</td>
        <td>£700,000</td>
      </tr>
      <tr>
        <td>Antoine Griezmann</td>
        <td>30</td>
        <td>Barcelona</td>
        <td>France</td>
        <td>Left Wing Forward</td>
        <td>£594,000</td>
      </tr>
      <tr>
        <td>Ousmane Dembele</td>
        <td>23</td>
        <td>Barcelona</td>
        <td>France</td>
        <td>Right Wing Forward</td>
        <td>£212,000</td>
      </tr>
      <tr>
        <td>Sergio Busquets</td>
        <td>32</td>
        <td>Barcelona</td>
        <td>Spain</td>
        <td>Defensive Midfielder</td>
        <td> £271,000</td>
      </tr>
      <tr>
        <td>Frenkie De Jong</td>
        <td>23</td>
        <td>Barcelona</td>
        <td>Holland</td>
        <td>Midfielder</td>
        <td>£360,000</td>
      </tr>
      <tr>
        <td>Philippe Continho</td>
        <td>28</td>
        <td>Barcelona</td>
        <td>Brazil</td>
        <td>Attacking Midfielder</td>
        <td>£250,000 </td>
      </tr>
      <tr>
        <td>Jordi Alba</td>
        <td>32</td>
        <td>Barcelona</td>
        <td>Spain</td>
        <td>Left Back Defender</td>
        <td>£350,000</td>
      </tr>
      <tr>
        <td>Gerard Pique</td>
        <td>34</td>
        <td>Barcelona</td>
        <td>Spain</td>
        <td>Centre Back Defender</td>
        <td>£450,000</td>
      </tr>
      <tr>
        <td>Clement Lenglet</td>
        <td>25</td>
        <td>Barcelona</td>
        <td>Spain</td>
        <td>Centre Back Defender</td>
        <td>£360,000</td>
      </tr>
      <tr>
        <td>Sergino Dest</td>
        <td>20</td>
        <td>Barcelona</td>
        <td>Holland</td>
        <td>Right Back Defender</td>
        <td>£210,000</td>
      </tr>
      <tr>
        <td>Ter Stegen</td>
        <td>28</td>
        <td>Barcelona</td>
        <td>Germany</td>
        <td>Goalkeeper</td>
        <td>£220,000</td>
      </tr>
    </tbody>
  </table>
</div>
</section>
<br>
<hr>
<section id="music">
<h1 class="text-center" id="musicc"><i class="fas fa-music"></i> MUSIC</h1>
<h5 class="text-center text-muted m-4">Music is life itself, it is the soundtrack of your life.<br><em>“Music, once admitted to the soul, becomes a sort of spirit and never dies.” – Edward Bulwer-Lytton.</em></h5>
<p class="grey-text text-right">凡音之起，由人心生也，人心之动，物使之然也。</p>
<div id="musiccarousel" class="carousel slide carousel-fade" data-ride="carousel" data-interval="false">

 
  <div class="carousel-inner" role="listbox">

    <div class="carousel-item active">
      <iframe width="100%" height="650"
      src="https://www.youtube.com/embed/RBumgq5yVrA" allowfullscreen>
      </iframe>
    </div>
   
    <div class="carousel-item">
      <iframe width="100%" height="650"
      src="https://www.youtube.com/embed/qIF8xvSA0Gw" allowfullscreen>
      </iframe>
    </div>

    <div class="carousel-item">
      <iframe width="100%" height="650"
      src="https://www.youtube.com/embed/NKeU1twQYX4" allowfullscreen>
      </iframe>
    </div>

    <div class="carousel-item">
      <iframe width="100%" height="650"
      src="https://www.youtube.com/embed/EqPtz5qN7HM" allowfullscreen>
      </iframe>
    </div>

    <div class="carousel-item">
      <iframe width="100%" height="650" 
      src="https://www.youtube.com/embed/XXYlFuWEuKI" allowfullscreen>
      </iframe>
    </div>

    <div class="carousel-item">
      <iframe width="100%" height="650"
      src="https://www.youtube.com/embed/kJQP7kiw5Fk" allowfullscreen>
      </iframe>
    </div>

  </div>

  <a class="carousel-control-prev" href="#musiccarousel" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#musiccarousel" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>

</div>

<div class="container">
  <p class="grey-text text-center">Marking a lot of projects must be very exhausted, here's some music for madam to relax a bit and keep going.<br>Gambateh~</p>
</div>
</section>


<!-- footerrrrrrrrrr -->
<br>

<footer class="page-footer font-small grey darken-3" >
 
  <div class="container">

    <div class="row">
      <div class="col-lg-12 col-md-12 py-5">
        <div class="mb-5 flex-center">

         
          <a class="fb-ic">
            <i class="fab fa-facebook-f fa-lg white-text mr-md-5 mr-3 fa-2x"> </i>
          </a>
        
          <a class="tw-ic">
            <i class="fab fa-twitter fa-lg white-text mr-md-5 mr-3 fa-2x"> </i>
          </a>
       
          <a class="gplus-ic">
            <i class="fab fa-google-plus-g fa-lg white-text mr-md-5 mr-3 fa-2x"> </i>
          </a>
         
          <a class="li-ic">
            <i class="fab fa-facebook-messenger white-text mr-md-5 mr-3 fa-2x"></i>
          </a>
        
          <a class="ins-ic">
            <i class="fab fa-instagram fa-lg white-text mr-md-5 mr-3 fa-2x"> </i>
          </a>
        
          <a class="pin-ic">
            <i class="fab fa-whatsapp white-text mr-md-5 mr-3 fa-2x"></i>
          </a>

          <a>
            <i class="fab fa-telegram-plane white-text mr-md-5 mr-3 fa-2x"></i>
          </a>
        </div>
      </div>
    </div>

    <div class="modal fade" id="modalContactForm" tabindex="-1" role="dialog" aria-labelledby="myModalLabel"
    aria-hidden="true">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header text-center">
          <h4 class="modal-title w-100 font-weight-bold">Write to us</h4>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body mx-3">
          <div class="md-form mb-5">
            <i class="fas fa-user prefix grey-text"></i>
            <input type="text" id="form34" class="form-control validate">
            <label data-error="wrong" data-success="right" for="form34">Your name</label>
          </div>
  
          <div class="md-form mb-5">
            <i class="fas fa-envelope prefix grey-text"></i>
            <input type="email" id="form29" class="form-control validate">
            <label data-error="wrong" data-success="right" for="form29">Your email</label>
          </div>
  
          <div class="md-form mb-5">
            <i class="fas fa-tag prefix grey-text"></i>
            <input type="text" id="form32" class="form-control validate">
            <label data-error="wrong" data-success="right" for="form32">Subject</label>
          </div>
  
          <div class="md-form">
            <i class="fas fa-pencil prefix grey-text"></i>
            <textarea type="text" id="form8" class="md-textarea form-control" rows="4"></textarea>
            <label data-error="wrong" data-success="right" for="form8">Your message</label>
          </div>
  
        </div>
        <div class="modal-footer d-flex justify-content-center">
          <button class="btn btn-grey" onclick="button2()">Send <i class="fas fa-paper-plane-o ml-1"></i></button>
        </div>
      </div>
    </div>
  </div>
  
  <div class="text-center">
    <a href="" class="btn btn-grey btn-rounded mb-4" data-toggle="modal" data-target="#modalContactForm">COMMENT</a>
  </div>
  </div>

  <div class="footer-copyright text-center py-3">© 2021 Copyright:
    <a href="#">D210061A@sc.edu.my</a> <p class="dark-grey-text">Chee Kar Jun</p>
  </div>
</footer>
</div>
<script>
  $(function() {
  // For card rotation
     $('.btn-rotate').click(function(){
          $('.card-front').toggleClass(' rotate-card-front');
          $('.card-back').toggleClass(' rotate-card-back');
     });
  });
</script>
    </body>
</html>
