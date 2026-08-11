---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>

<head>
<style>
li::marker {
  color: rgb(20, 90, 50);
}
</style>
<style>
    p1 {color:rgb(30, 132, 73); font-style :italic}
    news {color:rgb(230, 136, 34); font-style :italic}
</style>
</head>

![Photo]({{ site.baseurl }}/assets/images/Farzaneh.jpg "Farzaneh"){:style="height:17em;"}

<span style="color:rgb(20, 90, 50); font-size: 20pt; font-weight:bold">
 Farzaneh Derakhshan<br> </span>
<span style="color:rgb(30, 132, 73); font-size: 12pt; font-weight:bold">
Assistant Professor <br>
Computer Science Department, Illinois Tech<br></span>
<span style="font-size: 12pt; color:rgb(23, 32, 42);">
Ph.D. Pure and Applied logic [[CV]]({{ site.baseurl }}/assets/docs/CV.pdf)<br>
Carnegie Mellon University<br></span>
<span style="font-size: 10pt; color:rgb(23, 32, 42); line-height:1">
Address: 208F Stuart Building, 10 W 31st Street,<br>
Illinois Institute of Technology, Chicago, IL 60616<br></span>
<span style="font-size: 10pt; color:rgb(23, 32, 42); line-height:1">
Email: [lastname][dot][firstname] [at] gmail [dot] com</span><br><br>

<body>
<span style=" color:rgb(23, 32, 42); line-height:1">
I am an assistant professor at the Illinois Institute of Technology in the computer science department. My research aims to facilitate the design of concurrent programs by exploring the logical concepts underlying concurrency and building elegant formal methods to guarantee the correctness, e.g., safety and reactivity, and other desirable requirements, e.g., security and fault tolerance, for concurrent programs. <br>
My current research projects include designing a modal logic to reason about systems with both under- and over-approximation, using relational logic for GPU side-channel security and secure compilation, designing type systems for intermittent computing, and behavioral types for security.<br>
Before joining Illinois Tech, I received a Ph.D. from Carnegie Mellon University in 2021, advised by Prof. Frank Pfeninng. Following my Ph.D., I worked as a postdoctoral fellow at Carnegie Mellon University, advised by Prof. Limin Jia and Prof. Stephanie Balzer.<br><br>
</span>
</body>


<span style="color:rgb(30, 132, 73); font-size: 17pt; font-weight:bold">
News </span>

{: .news }
<ul style="list-style-type:square;">
<li> I'm honored that our ESOP 2026 paper, <p1> Recursive Logical Relations for Intuitionistic Linear Logic Session Types</p1>, has been recognized with the <a href="https://etaps.org/awards/best-paper">Distinguished Paper Award</a> and the
<a href="https://eatcs.org/index.php/best-etaps-paper">Best EATCS Paper Award</a>.</li>
<li>Our paper, <p1>Recursive Logical Relations for Intuitionistic Linear Logic Session Types</p1>, has been accepted for publication at ESOP 2026.<br></li>
<li>Our paper, <p1>Quantified Underapproximation via Labeled Bunches</p1>, will appear at OOPSLA 2025.<br></li>
<li>I will be serving on the program committees for LICS 2026 and <a href="https://etaps.org/2026/conferences/esop/">ESOP 2026</a>.<br></li>
<li> I'm happy to be co-organizing the <a href="https://www.dagstuhl.de/seminars/seminar-calendar/seminar-details/26071"> Dagstuhl Seminar 26071</a> on Behavioural Types for Resilience with Robbert Krebbers, Roland Kuhn, and Nobuko Yoshida, happening February 8–13, 2026.</li>
<li> I had the pleasure of co-chairing <a href="https://places-workshop.github.io/2025/">PLACES 2025</a> with Jan Hoffmann this year.</li>
</ul>

