# Workshop
Test
<!doctype html>
<html lang="de">
    

	<head>
		<meta charset="utf-8">

		<title>Workshop - Responsive Design</title>

		<!--meta name="description" content="Workshop zu Embaded Videos"-->
		<meta name="author" content=" Mike Klement und Daniel Franken">

		<meta name="apple-mobile-web-app-capable" content="yes" />
		<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />

		<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
        
		<!--link rel="stylesheet" href=".../revealjs-framework/css/reveal.min.css"-->
        <!--link rel="stylesheet" href=".../revealjs-framework/css/theme/medieninformatik.css" id="theme"-->
        <link rel ="stylesheet" href="Workshop.css"> 
		< Code syntax highlighting >
		<!--link rel="stylesheet" href=".../revealjs-framework/lib/css/zenburn.css"-->

		<!-- Printing and PDF exports -->
		<script>
			var link = document.createElement( 'link' );
			link.rel = 'stylesheet';
			link.type = 'text/css';
			link.href = "Workshop.css";
		</script>
        
        <!--[if lt IE 9]>
		<script src="../revealjs-framework/lib/js/html5shiv.js"></script>
		<![endif]-->
        </head>   
	<body>
        <div class="reveal">
            <div class="slides">
                
                <!-- Intro Folie -->
                
                <section>
                    <h1>Webbasierte Anwendung </h1>
                    <h2 class="u">Responsive Design Workshop</h2>
                    <p>16. November 2017</p>
                    <p>
                        Studiengang Medieninformatik an der technischen Hochschule Köln 
                        <br> Campus Gummersbach
                    </p>
                    <p style="margin-top:11%"> Mike Klement und Daniel Franken</p>
                </section>
                <!-- EINLEITUNG was?  -->
                                
                <section>
                    <h2 class="u">Was ist Responsive Design?</h2>
                    <ul>              
                        <li><p>Einheitliche Darstellung von Informationen</p></li>
                        <li><p>Unterschiedliche Displaygrößen</p></li>
                        <li><p>Flexibles Layout</p></li> 
                        <li><p>"form follows function"</p></li> 
                    </ul>
                </section>
                 <!-- EINLEITUNG wie?  -->
                  <section>
                    <h2 class="u">Wie wird Responsive Design umgesetzt?</h2>
                    <ul>              
                        <li><p>HTML5</p></li>
                        <li><p>CSS3 Media Queries</p></li>
                        <li><p>(jQuery)</p></li>
                    </ul>
                </section>
                
                  <!-- EINLEITUNG Standards  -->
                                
                <section>
                    <h2 class="u">Standard Auflösungen von Smartphones und Tablets</h2>
                    <ul>              
                        <li><p>Smartphones: 320px bis 480px</p></li>
                        <li><p>Tablet: 768px bis 1024px</p></li>
                        <li><p>Desktop: 1024px  +</p></li> 
                        <img src="resolution.jpeg"  width="700" height="350" >
                    </ul>
                </section>
                
                    <!-- EINLEITUNG Developer tools  -->
                  <section>
                    <h2 class="u">Wie teste ich ob eine Webseite "Responsive" ist?</h2>
                    <ul>              
                        <li><p>Developer Tools</p></li>
                        <li><p>Bildschirmgrößen testen</p></li>
                        <img src="FirefoxLogo.jpeg"  width="150" height="150" >
                         <img src="safariLogo.jpeg"  width="150" height="150" >
                    </ul>
                </section>
                
            <!-- EINLEITUNG Pro's?  -->
                  <section>
                    <h2 class="u">Pro's</h2>
                      <img src="Pros.jpg"  width="150" height="150" >
                    <ul>              
                        <li><p>Geräte übergreifende Flexibilität </p></li>
                        <li><p>Kostengünstiger</p></li>
                        <li><p>Allgemein Angepasst</p></li>
                        <li><p>Leute müssen keine Ahnung haben</p></li>
                    </ul>
                </section>
                <!-- EINLEITUNG Con's?  -->
                  <section>
                    <h2 class="u">Con's</h2>
                      <img src="Cons.jpg"  width="150" height="150" >
                    <ul>              
                        <li><p>Verbraucht gleiches Datenvolumen </p></li>
                        <li><p>Daher teurer für den Nutzer</p></li>
                        <li><p>Mobile Ansichten sind komprimierter</p></li>
                    </ul>
                </section>
                  <!-- EINLEITUNG wie?  -->
                  <section>
                    <h2 class="u">Wie wird die Zukuft für Responsive Design aussehen?</h2>
                    <ul>              
                        <li><p>Responsive Design wird sich durchsetzen </p></li>
                        <li><p>Einfach umsetzbar</p></li>
                        <li><p>Benutzerorientiert</p></li>
                        <li><p>Ansprechend</p></li>
                    </ul>
                </section>
                <!-- Media Queries Einleitung -->
                
                <section>
                    <h2 class="u">Komponenten für Responsive Design in CSS</h2>
                    <ul>
                        <li><p>Relative Angaben</p></li>
                        <li><p>Selten absolute Angaben</p></li>                   
                        <li><p>Media Queries</p></li>            
                    </ul>
                </section>
                
                <!-- Relative Angaben -->
                
                <section>
                    <h2 class="u">Relative Angaben</h2>
                    <ul>              
                        <li><p>Allgemeine Anpassung</p></li>
                        <li><p>"rem" / "em"</p></li>
                        <li><p>Prozentangaben </p></li> 
                    </ul>
                    <aside class="notes">
                        <p> 
                            Beispiel zeigen mit style.css
                        </p>
                    </aside>
                </section>
                
                <!-- Absolute Angaben -->
                
                <section>
                    <h2 class="u">Absolute Angaben</h2>
                    <ul>              
                        <li><p>Möglichst selten</p></li>
                        <li><p>Angaben mit "px"</p></li>
                        <li><p>z.B. Fenstergröße </p></li> 
                        <li><p>Media Queries </p></li> 
                    </ul>
                    <aside class="notes">
                        <p> 
                            Beispiel zeigen mit style.css
                        </p>
                    </aside>
                </section>
                
                <!-- Media-Queries Einleitung: -->
                
                <section>
                    <h2 class="u">Media Queries</h2>
                    <ul>              
                        <li><p>Syntax: @media screen</p></li>
                        <li><p>Fenstergrößen </p></li>
                        <li><p>Selektoren oder HTML-Tags </p></li>
                        <li><p>z.B. Schriftgröße ändern </p></li> 
                    </ul>
                    <aside class="notes">
                        <p> 
                            Beispiel zeigen mit style.css
                        </p>
                    </aside>
                </section>
                
                <!-- Aufgabe 1 -->
                
                <section>
                    <h2 class="u">Aufgabe 1</h2>
                    <ul>              
                        <li><p>Kontaktseite bearbeiten</p></li>
                        <li><p>Aufgaben im Master-Branch</p></li>
                        <li><p>Unter "responsive_design_training"</p></li>
                        <li><p>Im Ordner Style auf "style_uebung1.css"</p></li>
                        <li><p>Im Ordner img ist ein Screenshot der gelösten Seite</p></li>
                        <li><p>Cheat-Sheets am Ende angehangen</p></li>
                    </ul>
                </section>
                
                <!-- Aufgabe 2 -->
                
                <section>
                    <section>
                    <h2 class="u">Aufgabe 2</h2>
                    <ul>              
                        <li><p>Speisekarte bearbeiten</p></li>
                        <li><p>Unter "responsive_design_training"</p></li>
                        <li><p>Im Ordner Style auf "style_uebung2.css"</p></li>
                    </ul>
                    </section>
                    <section>
                    <h2 class="u">Zusatzaufgabe</h2>
                    <ul>              
                        <li><p>Home-Seite, Kontaktseite und Speisekarte anpassen</p></li>
                        <li><p>Unten links auf jeder Seite soll Logo "viel drin" angehangen werden</p></li>
                        <li><p>Das Bild soll "relativ" groß sein bei der Desktop Seite</p></li>
                        <li><p>Je Nach größe des mobilen Devices "klein" oder "ausgeblendet"</p></li>
                        <li><p>Bild ist im Ordner img und heißt "vieldrin.jpg"</p></li>
                    </ul>
                    </section>
                </section>
                      
                <!--Cheat-Sheets:   -->

                <section>
                    <h2 class="u">Cheat-Sheets:</h2>
                    <a href="http://www.codeply.com/responsive-design-cheatsheet.html">Codeply Responsive Design</a>
                    <br>
                    <a href="http://mac-blog.org.ua/css-3-media-queries-cheat-sheet/">Mac-Blog Media Queries</a>
                </section>
                
                <!--Quellen:   -->
                
                <section>
                    <h2 class="u">Quellen:</h2>
                    <a href="#" class="navigate-left">http://www.responsive-webdesign.mobi/was-ist-responsive-webdesign/</a>
                    <a href="#" class="navigate-left">https://www.youtube.com/watch?v=g2taIe7ZFUA</a>
                    <a href="#" class="navigate-left">https://wiki.selfhtml.org/wiki/CSS</a>
                </section>
            </div>
        </div>
        
        
        <script src="../revealjs-framework/lib/js/head.min.js"></script>
        <script src="../revealjs-framework/js/reveal.min.js"></script>

		<script>
            Reveal.initialize({
				controls: true,
				progress: true,
				history: true,
				center: true,

				transition: 'slide', // none/fade/slide/convex/concave/zoom

				// Optional reveal.js plugins
				dependencies: [
                {
                    src: '../revealjs-framework/lib/js/classList.js',
                    condition: function () {
                        return !document.body.classList;
                    }
                },
                {
                    src: '../revealjs-framework/plugin/markdown/marked.js',
                    condition: function () {
                        return !!document.querySelector('[data-markdown]');
                    }
                },
                {
                    src: '../revealjs-framework/plugin/markdown/markdown.js',
                    condition: function () {
                        return !!document.querySelector('[data-markdown]');
                    }
                },
                {
                    src: '../revealjs-framework/plugin/highlight/highlight.js',
                    async: true,
                    callback: function () {
                        hljs.initHighlightingOnLoad();
                    }
                },
                {
                    src: '../revealjs-framework/plugin/zoom-js/zoom.js',
                    async: true,
                    condition: function () {
                        return !!document.body.classList;
                    }
                },
                {
                    src: '../revealjs-framework/plugin/notes/notes.js',
                    async: true,
                    condition: function () {
                        return !!document.body.classList;
                    }
                }
				]
			});
            
            
        </script>
        </body>
</html>
