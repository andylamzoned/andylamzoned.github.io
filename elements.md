---
layout: "post"
title: 
date: 2021-01-16 01:29
category: 
author: 
tags: []
summary: 
---

<!doctype html>
<html lang="{{ site.lang | default: "en-US" }}">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">

{% seo %}
    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">
    <script src="https://code.jquery.com/jquery-1.12.4.min.js" integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ=" crossorigin="anonymous"></script>
    <script src="{{ '/assets/js/respond.js' | relative_url }}"></script>
    <!--[if lt IE 9]>
      <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
    <!--[if lt IE 8]>
    <link rel="stylesheet" href="{{ '/assets/css/ie.css' | relative_url }}">
    <![endif]-->
    <link rel="stylesheet" href="assets/css/main.css" />
    <noscript><link rel="stylesheet" href="assets/css/noscript.css" /></noscript>


  </head>
  <body class="is-preload">
    <div class="wrapper">
      <section>
        <div id="title">
          <br>
          <h1>Managing Enterprise Servers Portfolio</h1>
          <br>
          <p>By: John David Lamzon</p>
          <br>
          <nav id="nav">
						<ul class="links">
							<li class="active"><a href="index.html">PRELIM</a></li>
							<li><a href="generic.html">MIDTERM</a></li>
							<li><a href="elements.html">FINALS</a></li>
					  </ul>
          </nav>
          <br>
          <hr>
          <span class="credits left">Project maintained by <a href="{{ site.github.owner_url }}">{{ site.github.owner_name }}</a></span>
        </div>
      <section class="posts">
        <article>
          <h1 class="post-title p-name" itemprop="name headline">Prelim: Hands-on Activity 1</h1>
          <a href="elements.html" class="image fit"><img src="assets/images/HA1.jpg" alt="" width="700" height="300"></a>
          <br>
          <ol>
          <li>
          <p>Document your work and email to your instructor</p>
          </li>
          <li>
          <p>Access your alpine VM via ssh or locally via console.</p>
          <img src="assets/images/1.png" alt="" />
          </li>
          <li>
          <p>Install bash and vim with apk add bash and apk add vim.</p>
          <img src="assets/images/2.png" alt="" />
          </li>
          <li>
          <p>Install Git using apk add git</p>
          <img src="assets/images/3.png" alt="" />
          </li>
          <li>
          <p>Create a directory named activity1</p>
          <img src="assets/images/4.png" alt="" />
          </li>
          <li>
          <p>Initialize Git using git init)</p>
          <img src="assets/images/4.png" alt="" />
          </li>
          <p>To check the status of the repository use git status and to add a file in the repository history use git add (to simulate you can create a file first)</p>
          <img src="assets/images/5.png" alt="" />
          <li>
          <p>To commit the changes in the repository use git commit -m "Your commit message"</p>
          <img src="assets/images/6.png" alt="" />
          </li>
          </ol>
        </article>
      </section>
  </div>

 </div>
    <div class="footer">
    <div class="footer-bottom">
        &copy; <a href="https://github.com/andylamzoned/andylamzoned.github.io">jdlamzon-tip.github.io</a> | Designed by John David Lamzon
        </div>
</div>  
    {% if site.google_analytics %}
      <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
        (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
        m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.Scom/analytics.js','ga');
        ga('create', '{{ site.google_analytics }}', 'auto');
        ga('send', 'pageview');
      </script>
    {% endif %}
  </body>
</html>




