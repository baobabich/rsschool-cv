# Yauheni Babeikin
### CONTACT INFORMATION:

**E-mail:** baobabich@gmail.com 

**Phone:** +375(29)2475111

**Telegram:** @baobabich

**Location:** Mogilev, Republic of Belarus

### OBJECTIVE: ###

My goal is to start a career of a junior Front-End developer. I want to improve my skills in web development and to join a team of high-level professionals in which could be useful. Ready to do the best as it possible and to learn new materials and technologies quickly.

### SKILLS: ###

+ HTML, CSS (basic level)
+ JavaScript (basic level)
+ Version control GIT (basic level)

### CODE EXAMPLES: ###
```html
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
    <link rel="stylesheet" href="../www/Untitled-1.css">
    <script src="../www/GetStarted.js"></script>
  </head>
  <body>
    <header>
      <div class="headerline">
        <div id="logo">
          <img src="../www/logo.png" alt="LOGO НЕ ЗАГРУЖАЕТСЯ" srcset="">
            <div id="menu">
              <a href="https://youtu.be/2c6swYxDmTY" id="for_her">[FOR HER]</a>
              <a href="https://youtu.be/Cn3dFOBfBso" id="for_him">[FOR HIM]</a>
              <a href="https://youtu.be/T_-Q24nM3RI" id="for_babies">[FOR BABIES]</a>
              <a href="https://youtu.be/T_-Q24nM3RI" id="for_children">[FOR CHILDREN]</a>
              <a href="https://youtu.be/4n_VdkgKCJk" id="acessorize">[ACESSORIZE]</a>
             </div>
         </div>
     </div>
    </header>
    <main>
      <div class="maincontainer">
        <img src="" id="img_main">
          <div id="newsblock_red">
            <h1>[NEWSBLOCK]</h1>
            <p class="news-title">Новости региона:</p><br>
            <P class="addnews-block">На этой неделе в Могилёве произошло 10 дорожно-транпортных происшествий</P><br>
            <p class="author-name">Автор: Е.В. Бабейкин</p>
          </div>
          <div id="sportblock_green">
            <h1>[SPORTBLOCK]</h1>
          </div>
          <div id="autoblog_blue">
            <h1>[AUTOBLOG]</h1>
          </div>
          <div id="comments_white">
            <h1>[COMMENTS]</h1>
          </div>
     </div>   
    </main>
    <footer>
      <div class="foootline">
         <div id="company">
           <p><h1>[About Us]</h1></p><br>
           <p>Leadership</p><br>
           <p>Structure</p><br>
           <p>Contacts</p>
         </div>
         <div id="support">
           <p><h1>[For Business]</h1></p><br>
           <p>Contract <br> 
            manufacturing</p><br>
           <p>Structure</p><br>
           <p>Contacts</p>
         </div>
      </div>
    </footer>
  </body>   
</html>
```
```CSS
html,
body {
    margin: 0px;
    background-color: aquamarine;
}

header  {
    position: relative;
    margin: 0px;
    width: 100%;
    height: 200px;
    background-color: white;
    border-bottom: 10px solid black;
}

.headerline #logo {
    margin-left: 20px;
}

.headerline #menu {
    float: right;
    margin-top: 100px;
    margin-right: 40px;
    width: 675px;
}

#menu a {
    color: black;
}

#menu a:hover {
    color: white;
    background-color: coral;
}

#for_her,
#for_him,
#for_babies,
#for_children,
#acessorize {
    padding: 10px;
}

main {
    display: flex;
    justify-content: center;
    position: absolute;
    left: 0;
    width: 100%;
    height: 100%;
    min-height: 100%;
    background-color: white;
}

.maincontainer {
    width: auto;
}

.maincontainer div {
   
    float: left;
    margin: 10px;
    width: 300px;
    height: 300px;
    background-color: coral;
    border: 2px solid black;
    -webkit-transition: all 1s ease;
}

.maincontainer div:hover {
    width: 325px;
    height: 325px;
}

#newsblock_red h1,
#sportblock_green h1,
#autoblog_blue h1,
#comments_white h1 {
    padding: 0px;
    text-align: center;
    text-decoration: underline;
}

div .news-title {
    padding: 0px;
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    
}

div .addnews-block {
    padding: 5px;
}

div .author-name {
    padding-right: 5px;
    text-align: right;
}

footer {
    display: flex;
    justify-content: center;
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 80px;
    border-top: 5px solid black;
    background-color: white;
}

.foootline div {
    float: left;
    margin: 10px;
}

#company p,
#company h1,
#support p,
#support h1 {
    margin-bottom: -15px;
    padding-left: 5px;
}

#company,
#support {
    width: auto;
    height: auto;
    margin-left: 10px;
    border-left: 2px solid black;
    
}
```
```JavaScript
var images = new Array(); 
var i = 0;
  images[0] = '.\Desktop\images\1.jpg';
  images[1] = '.\images\2.jpg'; 
  images[2] = '.\images\3.jpg';
  images[3] = '.\images\4.jpg';
function viewImages() {
  document.getElementById("img_main").src = images[i]; 
  i++;
  if (i == images.length) {
  i = 0;
  }
  setTimeout("viewImages()",5000);
}   
```
### EXPERIENCE: ###

No programming experience.

### EDUCATION: ###

+ 2013 Mogilev state university of foodstuffs technology. (Higher education)

Engineer of automation of technological processes and production procedures.

+ Codeacademy ([achievements](https://www.codecademy.com/users/Yauheni/achievements))
+ Htmlacademy ([achievements](https://htmlacademy.ru/profile/id955927/achievements))
+ [learn.javascript.ru](https://learn.javascript.ru/)
+ Streamline English courses (sertificate of Intermediate level)

### ENGLISH: ###

With the help of a dictionary I can translate a large amount of text. Not bad pronounciation and orfography. Without problem can introduce myself and understand my companion. Succesfully completed Streamline English courses and got sertificate of Intermediate level.
My last job was associated with communication with foreign organizations for buying import equipment
and spare parts, as I performed duties of chef engineer of pharmaceutical production.
To write a common email or translate instructions and specifications was ordinary routine. 


