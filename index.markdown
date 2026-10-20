---
layout: default
title: Home
---

<style>
  li::marker { color: rgb(20, 90, 50); }
  p1 { color: rgb(30, 132, 73); font-style: italic; }
  news { color: rgb(230, 136, 34); font-style: italic; }
</style>

<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h1>
    <span class="post-date">{{ post.date | date_to_string }}</span>
    {{ post.content }}
  </div>
  {% endfor %}
</div>

![Photo]({{ site.baseurl }}/assets/images/Farzaneh.jpg "Farzaneh"){:style="height:17em;"}

<span style="color:rgb(20, 90, 50); font-size: 20pt; font-weight:bold">
Farzaneh Derakhshan<br></span>
<span style="color:rgb(30, 132, 73); font-size: 12pt; font-weight:bold">
Research Assistant Professor<br>
Department of Computer Science, Northwestern University<br></span>
<span style="font-size: 12pt; color:rgb(23, 32, 42);">
Ph.D. Pure and Applied Logic [[CV]]({{ site.baseurl }}/assets/docs/CV.pdf)<br>
Carnegie Mellon University<br></span>
<span style="font-size: 10pt; color:rgb(23, 32, 42); line-height:1">
Address: Mudd Hall, Room 3512, 2233 Tech Drive,<br>
Northwestern University, Evanston, IL 60208<br></span>
<span style="font-size: 10pt; color:rgb(23, 32, 42); line-height:1">
Email: [lastname][dot][firstname] [at] gmail [dot] com</span><br><br>


<span style="color:rgb(23, 32, 42); line-height:1">
I am a research assistant professor in the Department of Computer Science at Northwestern University. My research aims to facilitate the design of concurrent programs by exploring the logical concepts underlying concurrency and building elegant formal methods to guarantee correctness, e.g., safety and reactivity, and other desirable requirements, e.g., security and fault tolerance. Increasingly, my work goes beyond yes-or-no guarantees: I study how much information a program leaks rather than only whether it leaks, and I design logics that combine testing and verification, so that the level of assurance a program has can be expressed and quantified. My current research projects include quantitative information flow for probabilistic session types, quantitative reasoning about side channels in GPU kernels using relational logic, a modal logic for quantified under- and over-approximation, and relational separation logic for validating separately compiled components.<br>
Before joining Northwestern, I was an assistant professor at the Illinois Institute of Technology. I received my Ph.D. from Carnegie Mellon University in 2021, advised by Prof. Frank Pfenning, and then worked as a postdoctoral fellow at Carnegie Mellon University, advised by Prof. Limin Jia and Prof. Stephanie Balzer.<br><br>
</span>

<span style="color:rgb(30, 132, 73); font-size: 17pt; font-weight:bold">
News</span>

<ul style="list-style-type:square;">
<li>I'm happy to be co-organizing a special session on Logic in Computer Science at the ASL 2027 North American Meeting at UIC, Chicago, May 12–15, 2027.</li>
<li>I joined the Department of Computer Science at Northwestern University as a research assistant professor in October 2026.</li>
<li>Congratulations to my student <a href="https://myradotzel.github.io/">Myra Dotzel</a>, co-advised with Limin Jia, on completing her Ph.D.! She is now a postdoc at the University of Michigan.</li>
<li>I'm serving on the program committees for POPL 2027 and OOPSLA 2027.</li>
<li>I'm honored that our ESOP 2026 paper, <p1>Recursive Logical Relations for Intuitionistic Linear Logic Session Types</p1>, has been recognized with the <a href="https://etaps.org/awards/best-paper">Distinguished Paper Award</a> and the <a href="https://eatcs.org/index.php/best-etaps-paper">Best EATCS Paper Award</a>.</li>
<li>Our paper, <p1>Recursive Logical Relations for Intuitionistic Linear Logic Session Types</p1>, has been accepted for publication at ESOP 2026.</li>
<li>Our paper, <p1>Quantified Underapproximation via Labeled Bunches</p1>, will appear at OOPSLA 2025.</li>
<li>I will be serving on the program committees for LICS 2026 and <a href="https://etaps.org/2026/conferences/esop/">ESOP 2026</a>.</li>
<li>I'm happy to be co-organizing the <a href="https://www.dagstuhl.de/seminars/seminar-calendar/seminar-details/26071">Dagstuhl Seminar 26071</a> on Behavioural Types for Resilience with Robbert Krebbers, Roland Kuhn, and Nobuko Yoshida, happening February 8–13, 2026.</li>
<li>I had the pleasure of co-chairing <a href="https://places-workshop.github.io/2025/">PLACES 2025</a> with Jan Hoffmann.</li>
</ul>