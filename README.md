<!DOCTYPE html>
<html>
<head>
<title>Security-Login</title>
<link rel="icon" href="https://cdn.iconscout.com/icon/premium/png-256-thumb/hacker-1511798-1281143.png" type="image/gif" sizes="16x16">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

body {
  background-color: #212121;
  padding: 30px 0;
}

/*---- bar botton ----*/
.snip1526 {
  font-family: 'Work Sans', Arial, sans-serif;
  text-align: center;
  text-transform: uppercase;
  font-weight: 400;
}

.snip1526 *,
.snip1526 *:after {
  box-sizing: border-box;
  -webkit-transition: all 0.25s linear;
  transition: all 0.25s linear;
}

.snip1526 li {
  display: inline-block;
  list-style: outside none none;
  margin: 0.5em 0.6em;
  -webkit-perspective: 50em;
  perspective: 50em;
}

.snip1526 a {
  backface-visibility: hidden;
  color: #ffffff;
  display: block;
  line-height: 2.2em;
  padding: 0 1.4em;
  position: relative;
  text-decoration: none;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  background-color: #667273;
  -webkit-transform-origin: 50% 50%;
  -ms-transform-origin: 50% 50%;
  transform-origin: 50% 50%;
}

.snip1526 a:after {
  background-color: #5c122e;
  color: transparent;
  content: attr(data-hover);
  top: 0%;
  line-height: 2.2em;
  position: absolute;
  left: 100%;
  width: 100%;
  -webkit-transform: translateX(0%) rotateY(90deg);
  transform: translateX(0%) rotateY(90deg);
  -webkit-transform-origin: 0% 50%;
  -ms-transform-origin: 0% 50%;
  transform-origin: 0% 50%;
}

.snip1526 li:hover a,
.snip1526 li.current a {
  -webkit-transform: translate(-50%) rotateY(-90deg);
  transform: translate(-50%) rotateY(-90deg);
  background-color: #1e2222;
  color: transparent;
}

.snip1526 li:hover a:after,
.snip1526 li.current a:after {
  background-color: #2E86C1;
  color: #ffffff;
  cursor: pointer;
}


/* Popup container - can be anything you want */
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

.popup {
    position: relative;
    display: inline-block;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

/* The actual popup */
.popup .popuptext {
    visibility: hidden;
    width: 160px;
    background-color: #555;
    color: #fff;
    text-align: center;
    border-radius: 6px;
    padding: 8px 0;
    position: absolute;
    z-index: 1;
    bottom: 125%;
    left: 50%;
    margin-left: -80px;
}

/* Popup arrow */
.popup .popuptext::after {
    content: "";
    position: absolute;
    top: 100%;
    left: 50%;
    margin-left: -5px;
    border-width: 5px;
    border-style: solid;
    border-color: #555 transparent transparent transparent;
}

/* Toggle this class - hide and show the popup */
.popup .show {
    visibility: visible;
    -webkit-animation: fadeIn 1s;
    animation: fadeIn 1s;
}

/* Add animation (fade in the popup) */
@-webkit-keyframes fadeIn {
    from {opacity: 0;} 
    to {opacity: 1;}
}

@keyframes fadeIn {
    from {opacity: 0;}
    to {opacity:1 ;}
}

/*-- mobile friendly---*/
* {
  box-sizing: border-box;
}
.menu {
  float:right;
  width:100%;
  text-align:center;
}

.main {
  float:left;
  width:60%;
  padding:0 20px;
}
.right {
  background-color:gray;
  float:left;
  width:30%;
  padding:15px;
  margin-top:7px;
  text-align:center;
  
   border: 1px solid black;
  border-radius: 3px;
  display: block;
 background: linear-gradient(to right, black 50%, gray 50%);
  background-size: 200% 100%;
  background-position: right bottom;
  transition: all .5s ease-out;
}
.right:hover {
  background-position: left bottom;
}

@media only screen and (max-width:620px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width:100%;
  }
}

#borderimg { 
    border: 5px solid transparent;
    padding: 15px;
     text-shadow: -1px -1px #aa3030;
    border-image: url(https://i.pinimg.com/236x/af/77/73/af77737f1634cdbdc207f0802d6c2f36--doodle-borders-memory-books.jpg) 30 round;
}


/* ------ log in ----- */
 input[type=text], input[type=password] {
    width: 100%;
    padding: 5px 10px;
    margin: 8px 0;
    display: inline-block;
    border: 2px solid gray;
    box-sizing: border-box;
}

button {
    background-color: blue;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    cursor: pointer;
    width: 100%;

}

.button_hover {
  background-color: gray;
  color: black;
  border: 2px solid black;
  margin: 8px 0;
}

.button_hover:hover {background-color: red;}

/*------------ hover sa baba ----*/
  .snip1585 {
  background-color: rgb(41, 46, 57);
  color: #fff;
  display: inline-block;
  font-family: 'Roboto', sans-serif;
  font-size: 24px;
  margin: 10px;
  max-width: 315px;
  min-width: 230px;
  overflow: hidden;
  position: relative;
  text-align: center;
  width: 100%;
}

.snip1585 * {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  -webkit-transition: all 0.45s ease;
  transition: all 0.45s ease;
}

.snip1585:before,
.snip1585:after {
  background-color: rgba(46, 52, 64,  0.5);
  border-top: 50px solid rgba(46, 52, 64, 0.5);
  border-bottom: 50px solid rgba(46, 52, 64, 0.5);
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  content: '';
  -webkit-transition: all 0.3s ease;
  transition: all 0.3s ease;
  z-index: 1;
  opacity: 0;
}

.snip1585:before {
  -webkit-transform: scaleY(2);
  transform: scaleY(2);
}

.snip1585:after {
  -webkit-transform: scaleY(2);
  transform: scaleY(2);
}

.snip1585 img {
  vertical-align: top;
  max-width: 100%;
  backface-visibility: hidden;
}

.snip1585 figcaption {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  align-items: center;
  z-index: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  line-height: 1.1em;
  opacity: 0;
  z-index: 2;
  -webkit-transition-delay: 0s;
  transition-delay: 0s;
}

.snip1585 h3 {
  font-size: 1em;
  font-weight: 400;
  letter-spacing: 1px;
  margin: 0;
  text-transform: uppercase;
}

.snip1585 h3 span {
  display: block;
  font-weight: 700;
}

.snip1585 a {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 3;
}

.snip1585:hover > img,
.snip1585.hover > img {
  opacity: 0.7;
}

.snip1585:hover:before,
.snip1585.hover:before,
.snip1585:hover:after,
.snip1585.hover:after {
  -webkit-transform: scale(1);
  transform: scale(1);
  opacity: 1;
}

.snip1585:hover figcaption,
.snip1585.hover figcaption {
  opacity: 1;
  -webkit-transition-delay: 0.1s;
  transition-delay: 0.1s;
}
/*---- hover sa baba ---*/
.snip1508 {
  font-family: 'Lato', sans-serif;
  position: relative;
  overflow: hidden;
  margin: 1px;
  min-width: 230px;
  max-width: 315px;
  width: 100%;
  color: #ffffff;
  text-align: left;
  font-size: 16px;
  background-color: #1A1A1A;
   display: inline-block;
}

.snip1508 * {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  -webkit-transition: all 0.45s ease;
  transition: all 0.45s ease;
}

.snip1508 img {
  vertical-align: top;
  max-width: 100%;
  backface-visibility: hidden;
}

.snip1508 figcaption {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1;
  padding: 30px;
  background-color: #202123;
  -webkit-transform: translateX(-100%);
  transform: translateX(-100%);
  -webkit-box-shadow: 0 0 50px rgba(0, 0, 0, 0.5);
  box-shadow: 0 0 50px rgba(0, 0, 0, 0.5);
}

.snip1508 h2,
.snip1508 h3,
.snip1508 p {
  margin: 0;
}

.snip1508 h2,
.snip1508 h3 {
  font-family: 'Slabo 27px', serif;
  line-height: 1.2em;
}

.snip1508 h2 {
  font-size: 1.9em;
  color: #35ADF9;
}

.snip1508 h3 {
  color: #EBEBEB;
  font-size: 1.3em;
  font-weight: normal;
  letter-spacing: 1px;
}

.snip1508 p {
  border-top: 1px solid rgba(255, 255, 255, 0.2);
  font-size: 0.9em;
  margin-top: 12px;
  padding: 12px 0 15px;
  line-height: 1.5em;
}

.snip1508 a {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1;
}

.snip1508:hover > img,
.snip1508.hover > img {
  -webkit-transform: translateX(-100%);
  transform: translateX(-100%);
}

.snip1508:hover figcaption,
.snip1508.hover figcaption {
  -webkit-transform: translateX(0%);
  transform: translateX(0%);
}


</style>
</head>


<body style="font-family:Verdana;color:#aaaaaa;" oncontextmenu="return false;">

<div class="cover" style="background-image: url(https://newevolutiondesigns.com/images/freebies/robot-facebook-cover-18.jpg);padding:15px;text-align:center;height:300px;width:100%">
</div>


<div class="popup" onclick="myFunction()" style="position:absolute;  ;top:318px; center:100%">
<div style="overflow:auto" >
<span class="popuptext" id="myPopup">input my second security code first to access The Navigations</span>
<ul class="snip1526">
  <div class="menu">
    <ul class="snip1526">
  <li class="current"><a href="#" data-hover="Home">Home</a></li>
  <li onclick="location.href='#';"><a data-hover="Information">About Me</a></li>
  <li onclick="location.href='#';"><a data-hover="Samples">School Works</a></li>
  <li onclick="location.href='#';"><a data-hover="Samples">My Works</a></li>
  <li onclick="location.href='#';"><a data-hover="Skills">Talents</a></li>
  <li onclick="location.href='#';"><a data-hover="Contact">Reach Me</a></li>
</ul>
  </div>




  <div class="main">
<div style="padding-left: 35px;"> 
<center>
<p id="borderimg"  style="=padding-top:20px ; color: white; size: 20px;font-family:courier">
Hello Dear visitor, Welcome to my World.<br><br>

My name is Yvette Camille A. Flores , I'm a front end web developer <br>
I Design and Build user interface  with a strong passion for designing beautiful and functional user experiences<br><br>


<a href="url">Click here to ontinue</a></p>
    
</center></div>
  </div>
  
  
  
  
  

  <div class="right">
  <div style="padding-left:50px;padding:10px">
  


<div class="container">
  
 <form action="https://yvetteflores.github.io/Main-login/">
    <button class="button_hover" type="submit" onclick="checkPswd();" onkeypress="checkPswd();">Logout</button>
</form>


</div>


  </div>
</div></div>




<div style="text-align:center;padding:10px;margin-top:7px;">  <h2>My Amazing Team</h2><p> there was no limit to what you can learn with an open mind</p>
<figure class="snip1508">
  <img height="200px" width="450px"  src="http://techcabal.com/wp-content/uploads/2016/09/programmer.png" alt="sample85" />
  <figcaption>
    <h2>Yvette Flores</h2>
    <h3>Front-End developer
    </h3>
    <p>I'm learning real skills that I can apply throughout the rest of my life ...</p>
  </figcaption>
  <a href="#"></a>
</figure>
<figure class="snip1508"><img height="200px" width="450px" src="https://hackaday.com/wp-content/uploads/2020/06/hw.png?w=800"  />
  <figcaption>
    <h2>Camille Flores</h2>
    <h3>Web Developer</h3>
    <p>Imagination is the beginning of creation</p>
  </figcaption>
  <a href="#"></a>
</figure>
<figure class="snip1508"><img height="200px" width="450px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRD3io3lAwvIcgBFMtEaKy3GF_5zGxzg4pnvw&usqp=CAU"  />
  <figcaption>
    <h2>Flores Yc</h2>
    <h3>Lead Developer</h3>
    <p>Strong passion Took me in this place </p>
  </figcaption>
  <a href="#"></a>
</figure>
    
</div>




<script type="text/javascript">

 
            
            // anti inspect
            document.onkeydown = function (e) {
                if (event.keyCode == 123) {
                    return false;
                }
                if (e.ctrlKey && e.shiftKey && e.keyCode == 'I'.charCodeAt(0)) {
                    return false;
                }
                if (e.ctrlKey && e.shiftKey && e.keyCode == 'J'.charCodeAt(0)) {
                    return false;
                }
                if (e.ctrlKey && e.keyCode == 'U'.charCodeAt(0)) {
                    return false;
                }
            }

            const input = document.querySelector('#myInput');
            input.addEventListener('keyup', function (e) {
                if (e.keyCode === 13) {
                    alert('hi');
                }
            });
        //hover sa baba script
           $(".hover").mouseleave(
  function () {
    $(this).removeClass("hover");
  }
);
            

</script>

</body>
</html>
