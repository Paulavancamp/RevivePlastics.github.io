<html>
  <title>Revive</title>
  <style>
    /* Important styles */
@import url(https://fonts.googleapis.com/css?family=Raleway);
@import url('https://fonts.googleapis.com/css?family=Lobster');
@import url('https://fonts.googleapis.com/css?family=Cute+Font|Freckle+Face|Gugi|Monoton|Special+Elite');
body { 
  color: #555; 
  text-align:center;
  width:100%;
  font-family: "raleway", helvetica;
}
#backdrop{
   background-image:url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS_GrX_j7rV1MTsPTshGIuSzM1Fkl4Qym42x07lERl4Pcgxynl1");
  position:fixed;
  width:100%;
  height:100%;
}
.grid-container {
  display: grid;
  position:relative;
  z-index:5;
  width:100%;
  height:100%;
  grid-template-columns:33% 33% 34%;
  grid-gap: 0px;
}
.grid-container > div {
  text-align: center;
  padding: 20px;
}

.menu-before{
  display:none;
}

.menu-after {
  display: block;
  background-color:white;
}

ul, li, li a {
  list-style: none;
  display: block;
  margin: 0;
  padding: 0;
}
li a {
  padding: 5px;
  color: #305030;
  text-decoration: none;
  transition: all .2s;
}
li a:hover,
li a:focus {
  background: #305030;
  color: #fff;
}

#button{
  padding:20px;
  font-size:25px;
  background-color:transparent;
  font-family: 'Raleway', cursive;
  border:none;
  
}
#button:hover{
 color:#30a030;
}
#links{
  grid-row-start:1;
  grid-column-start:1;
  grid-column-end:4;
  grid-row-end:2;
  background-color:white;
}
#intro{
  grid-row-start:2;
  grid-row-end:3;
  grid-column-start:1;
  grid-column-end:4;
  font-size:50px;
   background-color:white;
}
#details{
  grid-row-start:4;
  grid-row-end:5;
  grid-column-start:1;
  grid-column-end:4;
  font-size:50px;
   background-color:white;
}
#Logo{
  grid-row-start:3;
  grid-row-end:4;
  grid-column-start:1;
  grid-column-end:4;
  background-color:#555;
}
/*Collect!*/
#collect-image{
  grid-row-start:5;
  grid-row-end:6;
  grid-column-start:1;
  grid-column-end:2;
}
#collect-title{
  grid-row-start:5;
  grid-row-end:6;
  grid-column-start:2;
  grid-column-end:3;
  font-size:50px;
  background-color:white;
  font-family: 'Monoton', cursive;

}
#collect-info{
  grid-row-start:5;
  grid-row-end:6;
  grid-column-start:3;
  grid-column-end:4;
  background-color:white;
}
#clean-title{
  grid-row-start:6;
  grid-row-end:7;
  grid-column-start:1;
  grid-column-end:2;
  font-size:50px;
  background-color:white;
  font-family: 'Freckle Face', cursive;
}
#clean-image{
  grid-row-start:7;
  grid-row-end:6;
  grid-column-start:2;
  grid-column-end:3;
}
#clean-info{
  grid-row-start:6;
  grid-row-end:7;
  grid-column-start:3;
  grid-column-end:4;
  background-color:white;
}
#create-info{
  grid-row-start:7;
  grid-row-end:8;
  grid-column-start:1;
  grid-column-end:2;
  background-color:white;
}
#create-title{
  grid-row-start:7;
  grid-row-end:8;
  grid-column-start:2;
  grid-column-end:3;
  font-size:50px;
  background-color:white;
  font-family: 'Gugi', cursive;
}
#create-image{
  grid-row-start:7;
  grid-row-end:8;
  grid-column-start:3;
  grid-column-end:4;
}
#why{
  grid-row-start:8;
  grid-row-end:9;
  grid-column-start:1;
  grid-column-end:4; 
  font-size:50px;
  background-color:white;
}
p{ 
  font-size: 20px;
  margin:0% 5%;
  text-align: left; 
  color: #888; }
.callout{
  background: #555;
  color:#eec;
  font-family:courier;
  margin-right:5px;
}
    
    
   </style>
  <meta http-equiv="Content-type" content="text/html;charset=UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<body>
  
  <div id=backdrop></div>
  
<div class="grid-container">
<div id=links>
  <button id=button>Menu</button>
  <span id = menu>
  <ul>
    <li><a href="#">About</a></li>
    <li><a href="#">Gallery</a></li>
    <li><a href="#">Credits</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
  </span>
</div>

 <div id=intro>
  <img id=logo src ="">
  <h2>Reduce. Reuse. Revive.</h2>
  <p>Revive is a plastic recycling workshop.  Revive creates a closed-loop system on Marquette's campus where plastic waste can be turned into beautiful and reusable products.This project began in fall of 2018 and is quickly gaining momentum. Browse around to learn more about the process and progress so far. <br><br></p>
  </div>
  <div id=Logo><img src=""></div>
  <div id=details>
  <h2>How does it work?</h2>
  </div>
  <div id=collect-image></div>
  <div id = collect-title><h2>Collect</h2></div>
  <div id=collect-info><p><span class=callout>Collect:</span>The collection process begins the moment you (yes YOU!) toss your recyclable plastic item in the recycling bins on campus. The facility team then sets aside the bags for the Revive team to sort through! </p>
  <p><span class=callout>Sort:</span>After it's been collected, plastic is sorted by type and only types #1, #2, #4, and #5 are kept to use.  The remaining plastic, aluminum, paper, and glass is returned to recycling bags for other facilities to process.  As we sort, extra parts (like bottle caps) and labels are removed to make the cleaning process easier.</p>
  </div>
  <div id=clean-title><h2>Clean</h2></div>
  <div id=clean-image></div>
  <div id=clean-info>
   <p><span class=callout>Clean:</span>Next, all materials are cleaned from food/liquid contamination. Soft soap and water are used rather than harsh chemicals to avoid toxins and environmental contamination - and to cut down on $$.  </p>
    <p><span class=callout>Shred:</span>At this point the plastic is ready to be refined into small, usable flakes. A special machine is used to tear the solid materials into smaller pieces.</p>
    </div>
    <div id=create-info>
    <p><span class=callout>Inject:</span>Plasic shreds are sent through a machine that melts the plastics and injects them into solid molds.</p>
   <p><span class=callout>Sell:</span>Finally, the plastics are re-introduced into the Marquette and Milwaukee community to be used again (and again, and again...)</p>
    </div>
   <div id=create-title><h2>Create</h2></div>
  <div id=create-image></div>
  
<div id=why>
  <h2>Why is it important?</h2>
  <p>Wow so many reasons, where to begin...</p>
  <p class=reasons><span class = callout>Saves space in landfils</span> - Did you know, 91% of plastics end up in landfils? Well it is a sad but true fact. Recycling makes it possible to reuse materials over and over before they end up in the ground. <a href = #>Click here</a> to read more. </p>
  <p class=reasons><span class = callout>Boosts the economy!</span></p>
  <p class=reasons><span class = callout>Increases mindfulness</span>Each time you place recycleables in a recycling bin - as opposed to the trash can - you are making an intentional choice. As you continue to practice, you begin to notice others also recycling (or not).</p>
  </div>
</body>
  </div>
  
  <script>
  var Toggle = document.getElementById("button");
var menu = document.getElementById("menu");
menu.className = "menu-before";

var show = function() {
	menu.className = "menu-after";
}
var hide = function() {
	menu.className = "menu-before";
}

Toggle.addEventListener("click", show);
Toggle.addEventListener("dblclick", hide);
  
  </script>
