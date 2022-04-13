<style>

:root{
 --accent: #2293fa;
}

*::selection{
 background: var(--accent);
 color: white;
}

@font-face {
  font-family: "Quicksand normal";
  src: url(https://chill31.github.io/assets/fonts/quicksand/Quicksand-Regular.ttf);
}

@font-face {
  font-family: "Jetbrains Mono";
  src: url(https://chill31.github.io/assets/fonts/CODE-FONTS/Jetbrains-Mono.ttf);
}

*{
 font-family: 'Quicksand normal', sans-serif;
}

code{
 font-family: 'Jetbrains Mono', Consolas;
}

.dead{
height: 100vh;
width: 100vw;
background: #f0f0f0;
border-radius: 1rem;
border: solid 5px black;
}

.dev-json{
 background: rgba(0, 0, 0, .5); color: white; border-radius: 1rem; padding: .5rem;
}

li a{
 color: var(--accent) !important;
}

li a:hover{
 text-decoration: underline !important;
}

button{
 padding: .75em 1.25em;
 background: var(--accent);
 border: solid 1px black;
 border-radius: .5em;
 cursor: pointer;

 position: relative;
 top: 1rem;

 transition: background 500ms ease;
}

button:hover{
 background: #5865f2;
}

button::before{
 content: '';
 opacity: 0;
 height: 0;
 width: 0;

 transition: 250ms ease;
 transition-property: height, width, opacity;
}

button::after{
 content: '';
 opacity: 0;
 height: 0;
 width: 0;

 transition: 250ms ease;
 transition-property: height, width, opacity;
}

button:hover::before{
 content: 'My Website';

 opacity: 1;

 height: inherit;
 width: inherit;
 position: absolute;
 top: -3.5em;
 padding: .5em 1em;
 background: var(--accent);
}

button:hover::after{
 content: '';
 position: absolute;
 top: -1.75em;
 left: 50%;
 transform: translate(-50%);

 opacity: 1;

 border-left: 1em solid transparent;
 border-right: 1em solid transparent;
  
 border-top: 1em solid var(--accent);
}

</style>

# Read Me: Chill31.github.io


###### this website is for chill31, a normal web developer with experience in js and html, css.

<br>
<br>

Basic:: (my website):

- Website with many animations and advanced css / styling features.
- Made by a 13 year old kid lol
- Has about 20 projects, maybe more in the future, most of them are useful, others are just there.

<a href="https://chill31.github.io/"><button>Visit My Website!</button></a>

<br>
<br>

More:

I have:

<ul>
<li> <a href="https://discord.com/">Discord</a> </li>
<li> <a href="https://www.youtube.com/channel/UCtH_hO_5HDAni7FC_x-hxDA">Youtube</a> </li>
<li>Maybe Instagram, idk.</li>
</ul>

I like to code a lot, I come home from school, study for 3 hours, take rest, code for 1 hour, play a little (outdoorsy sport) then rest, then do my homework...

I like/dislike github for a few reasons:

| Pros | Cons |
| ----------- | ----------------- |
| Free hosting | Long and annoying process of commiting and pushing code. |
| saving process of code so if you make unwanted changes, you can delete them | Hosting does not work unless a repository is public | 

> github is good, do not get me wrong here.

[the name was not real of course.];

Well, that's about it, see ya..

<a href="#surprise">Surprise!</a>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<img src="https://chill31.github.io/assets/img/deadserver.gif" class="dead" id="surprise">
