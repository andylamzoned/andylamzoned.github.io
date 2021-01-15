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
        <tbody>
<tr style="height: 29px;">
<td style="width: 100%; height: 29px;"><strong>1. Objectives</strong></td>
</tr>
<tr style="height: 35px;">
<td style="width: 100%; height: 35px;">Create a git repository locally and emphasize the use of Git in your local project in a CI/CD environment.</td>
</tr>
<tr style="height: 29px;">
<td style="width: 100%; height: 29px;"><strong>2. Intended Learning Outcomes (ILO)</strong></td>
</tr>
<tr style="height: 29px;">
<td style="width: 100%; height: 29px;">
<ol>
<li class="paragraph ng-attr-widget">Evaluate the concepts of DevOps culture and its benefits rather than traditional silos.</li>
<li class="paragraph ng-attr-widget">Evaluate the concepts of Continuous Integration/Deployment/Delivery</li>
<li class="paragraph ng-attr-widget">Create a local repository in Git in the local machine</li>
</ol>
</td>
</tr>
<tr style="height: 29px;">
<td style="width: 100%; height: 29px;"><strong>3. Discussion</strong></td>
</tr>
<tr style="height: 29px;">
<td style="width: 100%; height: 29px;"><a title="1.3 Local Git command" href="/courses/14414/pages/1-dot-3-local-git-command" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/pages/1-dot-3-local-git-command" data-api-returntype="Page">1.3 Local Git command</a></td>
</tr>
<tr style="height: 29px;">
<td style="width: 100%; height: 29px;"><strong>4. Resources</strong></td>
</tr>
<tr style="height: 29px;">
<td style="width: 100%; height: 29px;">
<p>1x Oracle VirtualBox</p>
<p>1x Alpine VM</p>
</td>
</tr>
<tr style="height: 29px;">
<td style="width: 100%; height: 29px;"><strong>5. Procedure</strong></td>
</tr>
<tr style="height: 4120px;">
<td style="width: 100%; height: 4120px;">
<p>Document your work and email to your instructor.</p>
<p>Access your alpine VM via ssh or locally via console.</p>
<p><img src="/courses/14414/files/3591257/download" alt="HA1.1.png" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/files/3591257" data-api-returntype="File" style="max-width: 706px;"></p>
<p>Install bash and vim with <em>apk add bash</em> and <em>apk add vim</em></p>
<p><img src="/courses/14414/files/3591255/download" alt="HA1.2.png" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/files/3591255" data-api-returntype="File" style="max-width: 706px;"></p>
<p>Install Git using <em>apk add git</em></p>
<p><img src="/courses/14414/files/3591256/download" alt="HA1.3.png" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/files/3591256" data-api-returntype="File" style="max-width: 706px;"></p>
<p>Create a directory named <em>activity1</em></p>
<p><img src="/courses/14414/files/3591258/download" alt="HA1.4.png" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/files/3591258" data-api-returntype="File" style="max-width: 706px;"></p>
<p>Initialize Git using <em>git init</em></p>
<p><img src="/courses/14414/files/3591259/download" alt="HA1.5.png" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/files/3591259" data-api-returntype="File" style="max-width: 706px;"></p>
<p>To check the status of the repository use <em>git status&nbsp;</em>and to add a file in the repository history use <em>git add&nbsp;</em>(to simulate you can create a file first)</p>
<p><img src="/courses/14414/files/3591260/download" alt="HA1.7.png" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/files/3591260" data-api-returntype="File" style="max-width: 706px;"></p>
<p>To commit the changes in the repository use <em>git commit -m "Your commit message"</em></p>
<p><img src="/courses/14414/files/3591261/download" alt="HA1.8.png" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/files/3591261" data-api-returntype="File" style="max-width: 706px;"></p>
</td>
</tr>
<tr style="height: 53px;">
<td style="width: 100%; height: 53px;">
<p><strong>6. Supplementary Activity</strong></p>
</td>
</tr>
<tr style="height: 53px;">
<td style="width: 100%; height: 53px;">
<p>N/A</p>
</td>
</tr>
<tr style="height: 53px;">
<td style="width: 100%; height: 53px;">
<p><strong>7.&nbsp; Problem Analysis</strong></p>
</td>
</tr>
<tr style="height: 53px;">
<td style="width: 100%; height: 53px;">
<p>Answer this discussion:</p>
<p><a title="Discussion 1.3: Git as a local repository" href="/courses/14414/discussion_topics/186258" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/discussion_topics/186258" data-api-returntype="Discussion">Discussion 1.3: Git as a local repository</a></p>
<p><a title="Discussion 1.3: Git as centralized repository" href="/courses/14414/discussion_topics/186258" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/discussion_topics/186258" data-api-returntype="Discussion"></a></p>
</td>
</tr>
<tr style="height: 53px;">
<td style="width: 100%; height: 53px;">
<p><strong>8. Conclusion</strong></p>
</td>
</tr>
<tr style="height: 53px;">
<td style="width: 100%; height: 53px;">
<p>Add your conclusion here in this discussion:</p>
<p><a title="Discussion 1.3: Git as a local repository" href="/courses/14414/discussion_topics/186258" data-api-endpoint="https://tip.instructure.com/api/v1/courses/14414/discussion_topics/186258" data-api-returntype="Discussion">Discussion 1.3: Git as a local repository</a></p>
</td>
</tr>
</tbody>
    </div>
    

  </body>
</html>
