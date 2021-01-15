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

  <header class="post-header">
    <h1 class="post-title p-name" itemprop="name headline">PRELIM: Hands-on Activity 2</h1>
    <p class="post-meta">
      <time class="dt-published" datetime="2021-01-12T00:00:00+00:00" itemprop="datePublished">Jan 12, 2021
      </time></p>
  </header>

  <div class="post-content e-content" itemprop="articleBody">
    <p><img src="https://user-images.githubusercontent.com/75419236/104220518-95267180-547a-11eb-98d4-01cfea075573.png" alt="r (33)"></p>
<ol>
  <li>
    <p>Create an account in Github</p>

    <p>Username should be your given initials and last name followed by -tip (e.g.  ajcanlas-tip)
  Use your TIP email address for this (if you have already linked your email with GitHub create a separate one)
  Verify your account in your email in GitHub,
<img src="https://user-images.githubusercontent.com/75419236/104205490-6eac0a80-5469-11eb-9f03-3756e2c481a8.png" alt="activity2-1"></p>
  </li>
  <li>
    <p>Create a repository with your username (in my case it is ajcanlas-tip) without any files, and it should be public.
<img src="https://user-images.githubusercontent.com/75419236/104205960-f5f97e00-5469-11eb-891b-3eb7fae735d3.png" alt="HA2 2"></p>
  </li>
  <li>
    <p>In your Alpine VM clone the repository you just created in my case this is my url <a href="https://github.com/ajcanlas-tip/ajcanlas-tip.git">https://github.com/ajcanlas-tip/ajcanlas-tip.git</a><br>
<img src="https://user-images.githubusercontent.com/75419236/104206321-54bef780-546a-11eb-9a73-a39f8a6b7f30.png" alt="HA2 3"></p>
  </li>
  <li>
    <p>Create a profile with Markdown this is a cheat sheat (Links to an external site.) in a “README.md” file</p>
    <p>README.md should have the following:</p>
    <ol>
      <li>
        <p>Your full name</p>
      </li>
      <li>
        <p>Year Level</p>
      </li>
      <li>
        <p>Interests</p>
      </li>
      <li>
        <p>email address</p>
      </li>
      <li>
        <p>Computer specs (CPU/Ram size/Disk type and size)</p>
      </li>
    </ol>
  </li>
  <li>
    <p>To add it to your profile add the README.md file commit it then push it in the repository (to push a repository use git push -u origin master)</p>
    <p>Commands:</p>
    <p><code class="language-plaintext highlighter-rouge">git add README.md</code></p>
    <p><code class="language-plaintext highlighter-rouge">git commit -m "First commit"</code></p>
    <p><code class="language-plaintext highlighter-rouge">git push -u origin master</code>
<img src="https://user-images.githubusercontent.com/75419236/104207112-31487c80-546b-11eb-86f2-bfeec08efa09.png" alt="HA2 4"></p>
  </li>
  <li>Fork this repository <a href="https://github.com/ajcanlas-tip/sysad2-12021.git">https://github.com/ajcanlas-tip/sysad2-12021.git</a>
<img src="https://user-images.githubusercontent.com/75419236/104208717-c3e91b80-546b-11eb-97ac-cb234c7385bd.png" alt="HA 2 5"></li>
  <li>Clone your newly forked repository with git clone <em>https://github.com/&lt; your username &gt;/sysad2-12021.git</em> and  go in the repository directory.
<img src="https://user-images.githubusercontent.com/75419236/104208705-c186c180-546b-11eb-94c0-0ea2436c9fa5.png" alt="HA 2 6"></li>
  <li>Make a new branch named “activity2” using git branch activity2 and <em>git checkout activity2</em>
<img src="https://user-images.githubusercontent.com/75419236/104208844-f135c980-546b-11eb-9ce3-3c5ae160c66e.png" alt="HA 2 7 "></li>
  <li>Make a new new remote upstream with git 
<img src="https://user-images.githubusercontent.com/75419236/104208847-f266f680-546b-11eb-94e0-5ab3c2042175.png" alt="HA 2 8"></li>
  <li>
    <p>Create your directory with your username, create a directory named “activity2” add the previous README.md file as HA2.md</p>

<p>Command used:</p>

<ol>
    <li>
    <p><code class="language-plaintext highlighter-rouge">mkdir &lt;your username&gt;</code></p>
    </li>
    <li>
    <p><code class="language-plaintext highlighter-rouge">mkdir activity2</code></p>
    </li>
    <li>
    <p><code class="language-plaintext highlighter-rouge">cp &lt;path of your README.md file&gt; HA2.md</code>
<img src="https://user-images.githubusercontent.com/75419236/104209195-5b4e6e80-546c-11eb-9f29-9fcbb461e76f.png" alt="HA 2 9"></p>
      </li>
    </ol>
  </li>
  <li>
    <p>add,commit and push it to your activity2 branch</p>

<p>Commands used:</p>

<ol>
    <li>
    <p><code class="language-plaintext highlighter-rouge">git add HA2.md</code></p>
    </li>
    <li>
    <p><code class="language-plaintext highlighter-rouge">git commit -s -n "activity2"</code></p>
    </li>
    <li>
    <p><code class="language-plaintext highlighter-rouge">git push -u origin upstream</code>
<img src="https://user-images.githubusercontent.com/75419236/104209878-31497c00-546d-11eb-91e4-64d39116d761.png" alt="HA 2 10"></p>
      </li>
    </ol>
  </li>
  <li>Request a pull request for the master branch in [https://github.com/ajcanlas-tip/sysad2-12021.git] (https://github.com/ajcanlas-tip/sysad2-12021.git) and activity2 branch of your forked repository
<img src="https://user-images.githubusercontent.com/75419236/104209877-30b0e580-546d-11eb-9d02-16967b137009.png" alt="HA 2 11"><br>
 This will be recorded based on your PR.</li>
</ol>>
    </div>
    

  </body>
</html>
