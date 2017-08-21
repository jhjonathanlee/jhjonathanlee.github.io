---
layout: post
title: "freeCodeCamp and Angular"
date: 2017-08-21
---

<p>
  It's a been awhile since my first post, but I've been quite busy since then with the job hunt and working my way through the freeCodeCamp Front End Certificate program. As of now, I'm tackling some of the practical projects and that's what I'm going to focus on here. As an aside, this website has not gotten much love.
</p>
<p>
  <h4>freeCodeCamp Projects</h4>
  Let's quickly walk through the three projects I've been working on and introduce some of the tech I've learned on the way.
  <ol>
    <li><a href="https://github.com/jhjonathanlee/quote-machine">Random Quote Generator</a></li>
    <li><a href="https://github.com/jhjonathanlee/skywatch">Local Weather App</a></li>
    <li><a href="https://github.com/jhjonathanlee/wikiviewer">Wikipedia Search Viewer</a></li>
  </ol>
  All of these apps are built purely with front end tech (AngularJS, JQuery, Bootstrap 3), and I've been adding on more frameworks as I go along. The quote generator and the local weather app are built with only JQuery and Bootstrap 3 (dead simple as these apps are), while the Wikipedia Search Viewer makes use of AngularJS. Even though I could have easily continued to use JQuery and Bootstrap 3 to finish up all the projects, I decided it would be useful to learn and apply a popular front end framework (I chose AngularJS because of the lovely online course available through <a href="https://www.codeschool.com/courses/shaping-up-with-angularjs">Code School</a>) to a smaller and more manageable project.
</p>
<p>
  AngularJS allows you to write more expressive HTML through the use of directives, which bind behavior (from your JavaScript) to DOM elements. You have built in directives like ng-model and ng-show, and you can create your own custom directives that allow you to define your own HTML tags that inject behavior from external HTML files. You write your AngularJS code in modules, which help with encapsulation by breaking up your code into functional or logical parts that you link up through dependencies. Another key component of AngularJS would be the controller, which defines app behavior through functions and values.
</p>
<p>
From and organizational perspective, AngularJS makes managing my code much, much more logical. Rather than having all of my JavaScript bundled up into $(document).ready(function() {...}) (although I've got nothing against JQuery), my JavaScript defines the name of the main module and any dependencies I need, thus averting a disastrous coding practice that reminds me of the dark days of my highschool programming and 3000 line main() functions. Most of the business logic is bundled up into their own modules that exist as dependencies. Not only are the separate modules reusable, they are infinitely more testable (something I have much to learn about). My HTML is more readable too. Instead of a couple of lines defining an unordered list with repeated list elements using ng-repeat on my main HTML page, I now have a single tag called article-list. If you delve deeper you'll realize it's the same HTML, but if you need a cursory glance over the HTML that one tag tells you a lot succinctly.
</p>
<p>
For my next project on freeCodeCamp (which uses the Twitch API), I'll definitely be flexing more AngularJS muscle, but I'll also be learning how to use a CSS precompiler. I haven't decided which one yet (SASS, LESS, there are so many...), but if there's anyone reading this I hope you'll make a suggestion. Reach me at jh.jonathanlee@gmail.com!
</p>