---
layout: essay
type: essay
title: Semantic UI - It's Pretty Tight
# All dates must be YYYY-MM-DD format!
date: 2020-02-27
labels:
  - Semantic UI
  - HTML
  - CSS
---

<img class="ui medium left floated rounded image" src="/images/semantic.jpeg">

  I’m a pretty visually oriented person. I like having visuals; I like having something to look at; I like to admire things that look nice to me. That’s why I was pretty excited to learn how to make websites. It seemed like something that would be right up my alley since it combines two of my interests–– art and computer science. But I have to admit, I was pretty underwhelmed with the results when I first started making sites using pure HTML and CSS. It was okay, but things could get a bit wonky depending and it was severely lacking in aesthetics. I wanted to make it better but I didn’t know how to start. 

  In come Semantic UI and making a nice-looking site becomes exponentially easier. Recreating the same site with Semantic UI results in a prettier website but at a fraction of the effort. What would have taken several lines of code in pure HTML and CSS could all be done by a few words with Semantic UI. Case in point: dropdown menus. Dropdown menus are a bit more interactive than a simple navigation bar, so they’re a bit more complicated to implement but Semantic UI does most of the heavy lifting for us. 

Making a simple dropdown menu with Semantic UI would generally look like so:

```javascript
<div class="ui dropdown">
 <div class="text">Example</div>
 <div class="menu">
   <div class="item">Item1</div>
   <div class="item">Item2</div>
   <div class=" item">Item3</div>
 </div>
</div>

<script>
$('.ui.dropdown')
  .dropdown()
;
</scrip>
```
Add there we have it–– a working dropdown menu that’s also pretty aesthetically pleasing from the get-go without needing any additional modifications in the stylesheet. 

If I were to implement a dropdown menu using only HTML and CSS, taking the code provided from w3schoools, it would look something like this:

```javascript
<div class="dropdown">
  <button onclick="myFunction()" class="dropbtn">Example</button>
  <div id="myDropdown" class="dropdown-content">
    <a href="#item1">Item1</a>
    <a href="#item2">Item2</a>
    <a href="#item3">Item3</a>
  </div>
</div>

<script>
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
</script>
```

Without Semantic UI, the code is twice as long and not nearly as neat and concise, not to mention the additional modifications it might need in CSS for it to look like its Semantic UI counterpart. Every feature that Semantic UI has can be done using only HTML and CSS, but why do all that extra work when there are already resources available that can cut the workload in half? There’s a saying that my project manager likes to use, that is, “Don’t reinvent the wheel,” which I feel that it’s pretty applicable here. 
