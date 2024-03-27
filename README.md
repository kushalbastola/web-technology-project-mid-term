<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="theme-color" content="#f53f2b">
    <meta http-equiv="x-ua-compatible" content="ie=edge" />
    <meta name="description" content="Portfolio To your site">
      <meta name="keywords" content="HTML, CSS, JavaScript, wavify.js, Developer">
       <meta name="author" content="Kushal Bastola">
        <link rel="shortcut icon" href="assets/img/aboutme.jpg" type="image/x-icon">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <link rel="stylesheet" href="assets/css/main.css">
   
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@master/devicon.min.css">
  
    <script src="https://kit.fontawesome.com/4019246ab4.js" crossorigin="anonymous"></script>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />
   
    <title>Kushal Bastola | Web designer</title>
</head>

<body>
   
    <div class="landing">
    
        <div class="img animate__animated animate__slideInDown wow" data-wow-duration="1.5s" data-wow-delay="0.3s"><img src="assets/img/me.jpg" alt="name photo"></div>
        <div class="me animate__animated animate__slideInUp wow" data-wow-duration="1.5s" data-wow-delay="0.3s">
            
            <section class="shortme">
                <h2>Kushal Bastola</h2>
            </section>
            <h3 id="typed"></h3>
        </div>
    </div>
    <div class="about">
        <div class="title">Portfolio</div>
        <div class="card-wrapper">
            <div class="box box1 animate__animated animate__slideInLeft wow" data-wow-duration="1s" data-wow-delay="0s"><span> <b>About Me</b></span>
                
                <img src="assets/img/aboutme.jpg" alt="">
                <p>Hey, I'm Kushal Bastola, a BIT student at Texas International College.<br> Passionate about software and app development,<br>
                     I'm eager to dive into the world of IT. <br> Ready for any challenge, I thrive on collaboration and continuous learning.

                </p>
                <div class="youtube.com"><button type="submit"  onclick=" window.open('http:\/\/youtube.com.adithyapai.com', '_blank')">youtube.com</button></div>
            </div>
            <div class="box box2 animate__animated animate__slideInUp wow" data-wow-duration="1s" data-wow-delay="0.37s"> <span><b>Skills</b></span>
                <br> <span> Programming</span>
                <ul class="mainlist">
                    
                    <ul class="sublist">
                        <li class="icon"><i class="devicon-c-plain-wordmark"></i></li>
                        <li>C</li>
                    </ul>
                    <ul class="sublist">
                        <li class="icon"><i class="devicon-cplusplus-plain-wordmark"></i></li>
                        <li>C++</li>
                    </ul>
                    <ul class="sublist">
                        <li class="icon"><i class="devicon-python-plain-wordmark"></i></li>
                        <li>Python</li>
                    </ul>
                    <ul class="sublist">
                        <li class="icon"><i class="devicon-java-plain-wordmark"></i></li>
                        <li>Java</li>
                    </ul>
                </ul><span style="width: 100%; text-align: center;">Design</span>
                <ul class="mainlist">
                    
                    <ul class="sublist">
                        <li class="icon"><img src="https://img.icons8.com/windows/48/000000/adobe-illustrator.png" alt="illustrator" /></li>
                        <li>Illustrator</li>
                    </ul>
                    <ul class="sublist">
                        <li class="icon"><img src="https://img.icons8.com/windows/48/000000/adobe-photoshop.png" alt="Photoshop" /></li>
                        <li>Photoshop</li>
                    </ul>
                    <ul class="sublist">
                        <li class="icon"><img src="https://img.icons8.com/windows/48/000000/adobe-xd.png" alt="adobe xd" /></li>
                        <li>XD</li>
                    </ul>
                    <ul class="sublist">
                        <li class="icon"><img src="https://img.icons8.com/windows/48/000000/figma.png" alt="figma" /></li>
                        <li>Figma</li>
                    </ul>
                </ul>
                <span>Tools</span>
                <ul class="mainlist">
                    <ul class="sublist">
                        <li class="icon"><img src="https://img.icons8.com/windows/32/000000/git.png" alt="git" /></li>
                        <li>Git</li>
                    </ul>
                    <ul class="sublist">
                        <li class="icon"><img src="https://img.icons8.com/windows/32/000000/github.png" alt="github" /></li>
                        <li>Github</li>
                    </ul>
                    <ul class="sublist">
                        <li class="icon"><img src="https://img.icons8.com/carbon-copy/32/000000/visual-studio-code-2019.png" alt="vscode" /></li>
                        <li>VS Code</li>
                    </ul>
                    <ul class="sublist">
                        <li class="icon"><img src="https://img.icons8.com/windows/32/000000/gitlab.png" alt="gitlab"></li>
                        <li>Gitlab</li>
                    </ul>                <div>
                        <ul>
                           
                            <li class=""><a href="https://github.com/kushalbastola" target="_blank"><i class="fab fa-github iconn"></i></a></li>
                            <li><a href="https://www.linkedin.com/in/kushal-bastola-4908082a3/" target="_blank"><i class="fab fa-linkedin-in  iconn"></i></a></li>
                            <li><a href="mail:bastolakushal919@gmail.com" target="_blank"><i class="fas fa-at  iconn"></i></a></li>
                            <li><a href="https://twitter.com/kusal333" target="_blank"><i class="fab fa-twitter  iconn"></i></a></li>
                        </ul>
                   
                    </div>
                    <div class="footer">Made with ❤️ by <a>Kushal Bastola</a></div>
    
                </ul>
            </div>
            


        </div>

        <!--TypedJs -->
        <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.11"></script>
        <script>
            //Enter your specilizations here
            var typed = new Typed("#typed", {
                strings: ['Programmer', 'Gamer ', 'Designer'],
                typeSpeed: 50,
                smartBackspace: true,
                backSpeed: 35,
                loop: true,
                showCursor: false,
            });
        </script>
        <!--Wow js is for aniamtion on scroll-->
        <script src="https://cdnjs.cloudflare.com/ajax/libs/wow/1.1.2/wow.min.js" integrity="sha512-Eak/29OTpb36LLo2r47IpVzPBLXnAMPAVypbSZiZ4Qkf8p/7S/XRG5xp7OKWPPYfJT6metI+IORkR5G8F900+g==" crossorigin="anonymous"></script>
        <script>
            new WOW().init();
        </script>


<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>
</body>

</html>
