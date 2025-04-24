<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="PORTFOLIO.css">
   
</head>
<body>
    <header>
        <div class="logo">
             <h1 class="colour">PORTFOLIO</h1>
        </div>
        <div class="INTRO">
            <h1>Hello, I'm <span class="text">kamal</span></h1>
          <p>A passionate Web Developer</p>
    
        </div>
        <div class="nav">
            <div class="box">
            <a href="#about">ABOUT</a>
            </div>
            <div class="box">
            <a href="#skills">SKILLS</a>
            </div>
            <div class="box">
            <a href="#projects">PROJECTS</a>
            </div>
            <div class="box">
            <a href="#contact">CONTACT</a>
            </div>
        </div>

        </div>
    </header>
    <div id="about">
       <H2 class="aboutme">ABOUT ME</H2>
        <p>
           Hello! I'm a passionate and dedicated web developer with a strong <br> interest in creating dynamic and responsive websites. <br> I specialize in <span>HTML, CSS, JavaScript , PYTHON </span> and I'm currently <br> expanding  my skills into <SPan2>Full Stack Development</SPan2>.<br> I enjoy solving real-world problems through code and <br> continuously improving my knowledge and skillset.
        </p>
        <p>
           My goal is to become a versatile Full Stack Developer who can <br> handle everything from user-friendly frontends to powerful backends. <br> I'm always open to new opportunities and <br> Let's build something amazing together!
        </p>
    </div>
   <div id="skills">
       <H2 class="myskills">MY SKILLS</H2>
       <ol type="1" class="arr">HTML</ol>
       <OL type="1" class="arr">CSS</OL>
       <OL type="1" class="arr">JAVASCRIPT</OL>
       <ol type="1" class="arr">PYTHON PROGRAMING</ol>
   </div>
   <div id="projects">
       <h2 class="myprojects">MY PROJECTS</h2>
       <H4>PROJECT ONE</H4>
       <OL><STrong>PORTFOLIO</STrong> using <SPan>HTML</SPan> , <SPan>CSS</SPan> , <SPan>JAVASCRIPT</SPan></OL>
       <a href="https://github.com/kamal1128">git link</a>
   </div>
   <footer>
       <DIV id="contact">
           <h2 class="mycontact">CONTACT</h2>
           <p class="space">GMAIL: kamalkandukuri12345@gmail.com </p>
           <p class="space">github:https://github.com/kamal1128</p>
           <p class="space">PHONE:+91 9347898813</p>
       </DIV>
   </footer>

   


</html>







   //CSS
   
*{ 
  margin: 0;
  box-sizing: border-box;
  padding: 0;
 
  color: rgb(173, 161, 161);
}
html{
  scroll-behavior: smooth;
}
body{
  font-family: 'Times New Roman', Times, serif;
  background-color: rgb(11, 11, 11);
  color: rgb(195, 185, 185);
}
@keyframes fadeIn {
  0% { opacity: 0; transform: translateY(-20px); }
  100% { opacity: 1; transform: translateY(0); }
}

header{
  background-color: rgb(20, 19, 19);
  color: white;
  text-align: center;
  background: url('IMM.jpg') no-repeat center/cover;
  color: white;
  animation: fadeIn 2s ease-in;
  display: flex;
  justify-content: space-between;
 
  
}
.logo{
  font-size: 1.5rem;
    font-weight: bold;
    color:yellow;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  padding: 20px;
}
.colour{
  color: yellow;
}
h1{
  cursor: default;
  
}
.nav{
  list-style: none;
  display: flex;
  gap: 20px;
  height: min-content;
  
}
.box{
  padding:5px;
}
.box:hover:hover{
  transform: scale(0.95);
}

.nav a{
  text-decoration: none;
  color:rgb(195, 185, 185);
  
}
header .nav a{
  color: yellow;
}
.INTRO{
  padding: 60px 20px;
  font-size: larger;
  padding: 200px;
}
.text{
  color:skyblue;
}
#about{
  padding: 200px;
}
.aboutme , .myskills , .myprojects , .mycontact{
  padding: 150px;
  font-size: 50px;
  color: #FFB347;
}

#about , #skills , #projects , #contact{
  text-align: center;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  font-size: 20px;
  padding: 200px;

  
}
h2{
  padding: 40px;
}
p{
  font-size: larger;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
br{
  padding: 40px;
}


ol{
  justify-content: space-between;
}
a{
  text-align: right;
  padding: 10px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  
}
.arr{
  padding: 10px;
}
#projects{
  padding: 100px;
}
footer{
  background-color:rgb(20, 19, 19) ;
 
}
.space{
       display: grid;
       grid-row: auto;
       padding: 30px;
}
span{
  color: aqua;
  font-family: Arial, Helvetica, sans-serif;
}
span2{
  color: rgb(157, 157, 80);
}
