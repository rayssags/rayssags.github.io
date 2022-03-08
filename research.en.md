---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
order: 2
title: Research
permalink: en/research
lang: en
---

<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 18px;
  background-color: white;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
}

.collapsible:after {
  content: '\02795'; /* Unicode character for "plus" sign (+) */
  font-size: 13px;
  color: white;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2796"; /* Unicode character for "minus" sign (-) */
}

.accordion__button {
  display: block;
  width: 100%;
  padding: 15px;
  border: none;
  outline: none;
  cursor: pointer;
  background: #333333;
  color: #FFFFFF;
  text-align: left;
  transition: background 0.2s;
}

.accordion__button::after{
    content:'\25be'; /*Unicode carachter for the arrow*/
    float: right;
    transform: scale(1.5);
}

.accordion__active--active + .accordion__content { display: block }
.accordion__active--active { background: #55555555}
.accordion__active--active::after { content: '\25b4'}
.accordion__content {
    padding: 0 15px;
    background: #eeeeee;
    display: none;
    overflow: auto;
}
details summary > * { 
  display: inline;
}

details > summary::marker {
    display: none;
    content: "";
}

summary {
    outline: none;
    font-size: 1.15em;
    list-style-image: none;
    content: "";
    font-size:   20px;
}


summary::-webkit-details-marker {
    display: none
    content: "";
}

summary:after {
    background: transparent;
    border-color: #29989a;
    border-radius: 15px;
    content: '\02795';
    color: #f5f5f5;
    float: right;
    vertical-align:top;
    font-size: 20px;
    font-weight: bold;
    margin: -2px 10px 0 0;
    padding: 0 0 0 0;
    text-align: center;
    width: 30px;
}

details[open] > summary:after {
    background: transparent;
    border-color: #29989a;
    border-radius: 15px;
    content: none;/*'\2796'*/;
    color: #f5f5f5;
    float: right;
    vertical-align:top;
    font-size: 20px;
    font-weight: bold;
    margin: -2px 10px 0 0;
    padding: 0 0 0 0;
    text-align: center;
    width: 30px;
}

</style>


<details><summary><h2 class="post-title" itemprop="name headline">SMBHs signs in LBAs</h2>
<br>
Looking for signs of supermassive black hole growth in LBAs. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
</summary>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id.

<div style="background: #29989a; color: #f5f5f5; border-radius: 15px; font-size: 0.8em; padding: 2px 10px 2px 10px; text-align: center;">Testing read more button design</div>
</details>


<br>
<br>

<details><summary><h2 class="post-title" itemprop="name headline">PAHs in active regions</h2>
<br>
Using PAHs to distinguish AGN and star-formation in SINGS galaxies

The SINGS
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</summary>

{% include image.html src="/im/PAH_cubea.svg"
                      caption="Spectral cube of NGC1097"
                      style="float: left; width: 39%; margin-right: 10px; margin-bottom: 0px" %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.



{% include image.html src="/im/PAH_cubeb.svg"
                      caption="Spectral cube of NGC1097"
                      style="float: right; width: 39%; margin-left: 10px; margin-bottom: 0px" %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<br>

{% include image.html src="/im/nuclear_NGC1097_reg1_pahfit.svg"
                      caption="Nuclear spectrum of NGC1097"
                      style="float: right; width: 100%; margin-left: 10px; margin-bottom: 0px" %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% include image.html src="/im/extranuclear_NGC1097_01_reg1_pahfit.svg"
                      caption="Extranuclear spectrum of NGC1097"
                      style="float: right; width: 100%; margin-left: 10px; margin-bottom: 0px" %}
</details>


<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    }
  });
}
</script>


<script>
    document.querySelectorAll('.accordion__button').forEach(button => {
        button.addEventListener('click', () => {
            button.classList.toggle('accordion__button--active');
            });
    });
</script>
