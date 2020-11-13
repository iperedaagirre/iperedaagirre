
    </head>
    <body translate="no" onload="draw()">
    
    
    <script src="js/jquery-2.2.4.min.js"></script>
    <link href="https://fonts.googleapis.com/css?family=Share+Tech|Share+Tech+Mono" rel="stylesheet">
    <title>Designs by Laighlin</title>
    
    
    <canvas id="bg"></canvas>
    <main id="content" style="opacity: 1; margin-top: 0px;">
    <h1>
    <div class="hex moved"></div><span>About the Dev</span></h1>
    <div class="subtext" id="main">
    <p>The name's Lin (which is short for Lindeun or Laighlin, depending on where you know me from). I'm a 24-year-old South Asian design student with a tech sort of background and a lot to say about the trends and direction of the contemporary design
    world.</p>
    <p>I wanted to be an engineer for most of my life. By the time I changed my mind about that, my liaison with the applied sciences had drastically altered my worldview already. This still informs much of my work and work ethic - design is no less
    of a science in my eyes than physics or computing. (In other words, I like design as long as I can be a nerd about it.)</p>
    </div>
    <h2>
    <div class="hex"></div><span>Skills</span></h2>
    <div class="subtext coll">
    A good grasp of object-oriented programming and computing-related math as a whole. Proficient in CSS3 and HTML5; making significant inroads into JavaScript and JQuery. Adobe Illustrator is both enjoyable for me and putty in my hands. <i>Putty.</i> In addition to my knowledge of coding, I also speak five human languages and am in the process of learning a few more.
    </div>
    <h2>
    <div class="hex"></div><span>Hobbies &amp; Interests</span></h2>
    <div class="subtext coll">
    Small indie coding projects (semi-professionally). Music (unprofessionally). Massively multiplayer online games (clumsily). Cooking (hungrily).
    </div>
    <h2>
    <div class="hex"></div><span>Currently Working On</span></h2>
    <div class="subtext coll">
    An accessibility app for Android, a couple of desktop themes for a blogging platform I casually use, and a photography project detailing the interplay of natural and artifical in urban environments.
    </div>
    <h2>
    <div class="hex"></div><span>Find Me</span></h2>
    <div class="subtext coll">
    <a>Twitter</a> | <a>Tumblr</a> | <a>Codepen</a> | <a>Behance</a>
    </div>
    <h2>
    <div class="hex"></div><span>Contact Me</span></h2>
    <div class="subtext coll">
    <ul>
    <li>Phone: +12 345 678 90</li>
    <li>E-mail: <a>lindeun@yahoo.com</a></li>
    <li>Discord: <a>Laighlin#0371</a></li>
    </ul>
    </div>
    </main>
    <svg viewBox="0 0 500 150" preserveAspectRatio="none" class="wave" id="one"><path d="M-13.36,88.98 C168.85,182.73 276.72,-73.84 506.31,79.10 L500.00,150.00 L0.00,150.00 Z"></path></svg>
    <svg viewBox="0 0 500 150" preserveAspectRatio="none" class="wave" id="two"><path d="M-13.36,88.98 C168.85,182.73 276.72,-73.84 506.31,79.10 L500.00,150.00 L0.00,150.00 Z"></path></svg>
    <div id="hex-holder">
    <div class="hex" id="uno"></div>
    <div class="hex" id="dos"></div>
    <div class="hex" id="tres"></div>
    </div>
    
    
    <script id="rendered-js">
    function draw() {
      var canvas = $('canvas')[0];
      if (canvas.getContext) {
        var ctx = canvas.getContext('2d');
        ctx.fillStyle = 'rgb(200, 0, 0)';
        ctx.fillRect(10, 10, 50, 50);
        ctx.fillStyle = 'rgba(0, 0, 200, 0.5)';
        ctx.fillRect(30, 30, 50, 50);
      }
    }
    
    $(document).ready(function () {
      // $(document).draw();
      $('#content').animate({
        opacity: 1,
        marginTop: '0' },
      800);
      $('h2').click(function () {
        $(this).next('.subtext').slideToggle('fast');
        $(this).children('.hex').toggleClass('moved');
      });
    });
    //# sourceURL=pen.js
        </script>
    
    
    </body></html>


<!--
### Hi there 👋



**iperedaagirre/iperedaagirre** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
