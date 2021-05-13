</script>
<style>
 @import url('https://fonts.googleapis.com/css2?family=Girassol&family=Lateef&display=swap');
  
  h1{
  	text-align: center;
  }
  

  a{
  	text-decoration: none;
    color: inherit;
    transition: all 800ms ease-out;
  }
  
  a:hover{
  	color: inherit;
    transition: all 800ms ease-out;
  }
  
  .holy{
  	color: #ffffcc;
  }
  
  .holy:hover{
  	color: #ffffff;
  }
  
  .sinful{
  	color: #ff9999;
  }
  
  .sinful:hover{
  	color: #ffaaaa;
  }
  
  
  body {
    height: 100vh;
    width: 100vw;
    overflow: hidden;
  }
  
  #soul{
  	position: fixed;
    top: 0%;
    left: 0%;
  	height: 100%;
    width: 100%;
    overflow: hidden;
  }
  
  #absolve, #sin{
  	height: 50%;
    width: 100%;
    font-size: 10vh;
    transition: all 800ms ease-out;
    overflow: hidden;
    
  }
  
  #absolve:hover, #sin:hover{
  	
    transition: all 800ms ease-in-out;


  }
  
  #absolve{
  	position: absolute;
    top: 0%;
    left: 0%;
    font-family: 'Lateef', cursive;
    color: #ffff99;
    transition: all 800ms ease-in-out;
  }
  
  #absolve:hover{
  	
    transition: all 800ms ease-in-out;
  }
  
  #absolve:hover .choice-img{
  	filter: blur(0px);
    transition: all 800ms ease-in-out;
  }
  
  
  #sin{
  	background-color: black;
    position: absolute;
    top: 50%;
    left: 0%;
    font-family: 'Girassol', cursive;
    color: #ff6666;
    transition: all 800ms ease-in-out;
  }
  
  #sin:hover{
  	
    transition: all 800ms ease-in-out;
  }
  
  #sin:hover .choice-img{
  	filter: blur(0px);
    transition: all 800ms ease-in-out;
  }
  
  .choice-img{
  	width: 100%;
    height: auto;
    filter: blur(15px);
    transition: all 800ms ease-in-out;
  }
  
  #purity{
  	margin: -30% auto 0% auto;
    transition: all 800ms ease-in-out;
  }
  
  #temptation{
  	margin: -10% auto 0% auto;
    transition: all 800ms ease-in-out;
  }
  
  .choice-box{
  	height: 50%;
    width: 60%;
  	position: absolute;
    top: 25%;
    left: 20%;
    text-align: center;
    line-height: 25vh;
    z-index: 5;
    transition: all 800ms ease-in-out;



  }
  
  .choice-box:hover{
  	font-size: 12vh;
  	transition: all 800ms ease-in-out;
  }
  
  #heaven:hover{
  	text-shadow: 0 0 5px #FFFFFF;
    transition: all 800ms ease-in-out;
  }
  
  #hell:hover{
  	text-shadow: 0 0 5px #FF3D71;
    transition: all 800ms ease-in-out;
  }
  
  #saint, #sinner{
  	height: 0%;
    width: 100%;
    transition: all 800ms ease-in-out;
    opacity: 0.0;
  }
  
  #saint{
  	position: absolute;
    bottom: 100%;
    left: 0%;
    background-color: white;
    z-index: 10;
    color: #ffff99;
    font-size: 4vh;
    font-family: 'Lateef', cursive;
    background-image: url('https://i.imgur.com/7ooT7pZ.jpg');
    background-attachment: fixed;
    background-size: auto 100%;
    background-position: bottom right;
    background-repeat: no-repeat;
  }
  
  #sinner{
  	position: absolute;
    top: 80%;
    left: 0%;
    background-color: black;
    color: #ff6666;
    z-index: 10;  
    font-size: 3vh;
    font-family: 'Girassol', cursive;
    background-image: url('https://i.imgur.com/jHMwIn3.png');
    background-attachment: fixed;
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
      
      
  }
  
  #saint:target{
  	height: 100%;
  	position: absolute;
  	bottom: 0%;
    left: 0%;
    z-index: 10;
    transition: all 800ms ease-in-out;
    opacity: 1.0;
  }
  
  #sinner:target{
  	height: 100%;
  	position: absolute;
  	top: 0%;
    left: 0%;
    z-index: 10;
    transition: all 800ms ease-in-out;
    opacity: 1.0;
  }
  
  .exit{
  	position: absolute;
    top: 2%;
    right: 5%;
    height: 10vh;
    
      
  }
  
  #repent{
  	color: #ffff99;
    transition: all 800ms ease-in-out;
  }
  
  #repent:hover{
  	text-shadow: 0 0 5px #FFFFFF;
    transition: all 800ms ease-in-out;
  }
  
  #doubt{
  	color: #ff6666;
    transition: all 800ms ease-in-out;
  }
  
  #doubt:hover{
  	text-shadow: 0 0 5px #FF3D71;
    transition: all 800ms ease-in-out;
  }
  
  .story{
  	height: 100%;
    width: 40%;
    position: absolute;
    top: 0%;
    left: 0%;
    background-color: rgba(0,0,0,0.4);
    overflow: hidden;
    padding-left: 2%;
    
  }
  
  .story-inner{
  	height: 100%;
    width: 100%;
    padding-right: 17px;
    overflow-y: scroll;
  }
</style>
</head>
<body>
<div id="soul">
<div id="saint">
<a href="#reset">
<h1 class="exit" id="doubt">
Doubt Your Purity
</h1>
</a>
<div class="story">
<div class="story-inner">
<h1>Estelle Rosewood</h1>
A girl possessed by a <a href="#sinner" class="sinful">Succubus</a><br>
Age: Twenty-one<br>
Sex: Female<br>
Height: 5'3"<br>
Hair: White<br>
Eyes: Amber<br>
<h1>
About
</h1>
<p>Estelle Mary Abigail Grace Elisabeth Rosewood was abandoned at birth at the doorstep of a church. She was raised by nuns and taught to be <a target="_blank" href="https://i.imgur.com/cYp2bKk.png" class="holy" target="_blank">proper</a> and <a target="_blank" href="https://i.imgur.com/103s2gI.png" class="holy" target="_blank">pure</a>. When she was very young, Bishop Emeritus, head of the church, saw great potential and purity within Estelle's soul. So when she was still an infant, a ritual was performed on her. The ritual was to imbue a spark of holiness, of divinity, into Estelle, and allow her to ascend and become an angel among mortal men.</p>
<p>Unfortunately for the Bishop, the ritual he had come to possess was a cursed rite indeed, planted in his possession with a ruse by a demon seeking to corrupt his church. The successful ruse meant that rather than a spark of divinity, Estelle was host to the seed of a succubus. As Estelle grew older, so too did the succubus, with the <a target="_blank" href="https://i.imgur.com/KZwlLhJ.png" class="sinful" target="_blank">effects</a> not being clear until she grew much older. Estelle had always been taught to be <a target="_blank" href="https://i.imgur.com/pOzk5Hv.png" class="holy" target="_blank">loving</a> to all others. Once Scarlet's influence began to spread through her, those loving feelings began to manifest...<a target="_blank" href="https://i.imgur.com/fDynEvv.png" class="sinful" target="_blank">A little differently.</a> Eventually, Scarlet grew powerful enough to take over her body. The two are at odds with one another for control, but have times where they can live more peacefully with one another. It's unclear to her if Scarlet seeks to actually take over her body fully, or simply co-exist with her.</p>
<p>With time, the two have come to influence one another more strongly, with Estelle imparting more genuine kindness into Scarlet, and Scarlet in turn pushing Estelle to pursue more <a target="_blank" href="https://i.imgur.com/a6hAGPi.jpg" class="sinful" target="_blank">sexual freedom</a>. Terrified her secret would be discovered by her church, she fled under the guise of mission work, and sought to find answers for herself.</p>
<p><i>"Should I embrace the teachings of the church? Or does Scarlet truly desire my happiness by leading me down this other path?"</i></p>
<h1>OOC</h1>
<center>
Codes are mine<br>
DM Friendly<br>
For Story+Smut<br>
<br><br><br><br>
</center>
</div>
</div>
</a>
</div>
<div id="sinner">
<a href="#reset">
<h1 class="exit" id="repent">
Repent
</h1>
</a>
<div class="story">
<div class="story-inner">
<h1>Scarlet</h1>
A succubus possessing a <a href="#saint" class="holy">holy girl.</a><br>
Age: Unknown<br>
Sex: Female<span title="Flexible">*</span><br>
Height: 5'3"<br>
Hair: White<br>
Eyes: Pink<br>
<h1>
About
</h1>
<p>Scarlet is a succubus. She is a being born of <a target="_blank" href="https://i.imgur.com/lxc6hUT.png" class="sinful" target="_blank">lust</a> that strives to <a target="_blank" href="https://i.imgur.com/TVYswr4.png" class="sinful" target="_blank">greater</a> and <a target="_blank" href="https://i.imgur.com/c6QY03v.png" class="sinful" target="_blank">greater</a> heights. She was thrust into this world inside Estelle during a ritual that Estelle's church performed in hopes of putting a spark of divinity within Estelle, not realizing that the ritual in question was a cursed one that instead gave life to Scarlet - the spark of divinity was, in fact, the seed of demonic life that gave birth to Scarlet. Because of the nature of her birth, she refers to the bishop of the church as 'Papa Emeritus', and sometimes refers to Estelle as 'Mother dearest'.</p>
<p>Because Scarlet and Estelle share a body, their spirits in many ways intermingle. Estelle is a kind soul, so while Scarlet is driven by her lust and the powers that come from doing so, Estelle's influence makes Scarlet capable of a depth of <a target="_blank" href="https://i.imgur.com/FX3fA0v.jpg" class="holy" target="_blank">sincere emotion</a>, while she in turn seeks to awaken Estelle's deep desires.</p>
<p>Scarlet does not care who her sexual partners are, so long as they are mature and virile. Sex and the exploration of lust makes her stronger, both physically and magically. She is still young, but she has <a target="_blank" href="https://i.imgur.com/uidzxUc.png" class="sinful" target="_blank">wasted no time</a> exploring her sexual freedom in seducing men and women, and in turn has gained a respectable pool of strength given her age.</p>
<p><i>"Why are you wasting time talking? Fuck me already!"</i></p>
<h1>OOC</h1>
<center>
Codes are mine<br>
DM Friendly<br>
For Story+Smut<br>
<br><br><br><br>
</center>
</div>
</div>
</div>
<div id="absolve">
<div class="choice-box" id="heaven">
<a href="#saint">
Embrace Purity.
</a>
</div>
<img src="https://i.imgur.com/yKYHDwK.jpg" class="choice-img" id="purity">
</div>
<div id="sin">
<div class="choice-box" id="hell">
<a href="#sinner">
Sin. Sin. Sin.
</a>
</div>
<img src="https://i.imgur.com/RvSuzxo.jpg" class="choice-img" id="temptation">
</div><script src="https://ajax.cloudflare.com/cdn-cgi/scripts/7d0fa10a/cloudflare-static/rocket-loader.min.js" data-cf-settings="83f0b32df3baa50fef4495a1-|49" defer=""></script></body>
</html>
