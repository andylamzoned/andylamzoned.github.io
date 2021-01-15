---
layout: "post"
title: 
date: 2021-01-16 01:29
category: 
author: 
tags: []
summary: 
---

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
        <div id="title">
          <br>
          <h1>Hands-on Activity 1: Install and configure your repository in Local Git</h1>
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
            <article class="post h-entry" itemscope="" itemtype="http://schema.org/BlogPosting">
<br>
  <header class="post-header">
    <h1 class="post-title p-name" itemprop="name headline">Prelim: Hands-on Activity 1</h1>
  </header>
  <div class="wrapper">
    <a href="elements.html" class="image fit"><img src="assets/images/HA1.jpg" alt="" width="700" height="300"></a>
    </div>
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

<div class="footer">
    <div class="footer-content">
        <div class="footer-section about"></div>
        <div class="footer-section links"></div>
        <div class="footer-section about"></div>
    </div>
    <div class="footer-bottom">
        &copy; jdlamzon-tip.github.io | Designed by John David Lamzon
        </div>
    <table class="table-footer-main">
    <tr>
    <td class="footer-head" colspan="3">SYSAD2 FINAL PROJECT
    </td>
    </tr>
    <tr>
    <td class="footer=cell">SYSAD2 FINAL PROJECT<br>
qjdalamzon@tip.edu.ph</td>
    <td class="footer=cell">eacena-tip</td>
    <td class="footer=cell">Contains all the hands-on activity,quiz, and major exam in System Adminitration 2 course.</td>
    </tr>
    </table>
</div>  
