# Glitch.js 📀
<div align="center">

###### 🔥 I'm a WIP! 👩 🚒
</div>

🖇 A jQuery plugin intended for adding various "glitching" effects for visible text.

<img align="right" src=".github/glitch-js.gif?raw=true" height="340">

- Settings
- Highly configurable
- [Respects spaces](#git)
- [Demo](#manage-pre-releases)
- [Tiny footprint](#publish-to-npm) (2kb)
- [Changelog](#changelog)
- [Documentation](#github-releases)
</br></br></br>

</br>

## TLDR;
- It's a simple as calling `$("header").glitch();` to get started.
- Checkout effects & Settings

<details>
  <summary>
    <strong>Table of Contents ➡</strong> (click to expand)
  </summary>


  - [Installation](#Installation)
  - [Usage](#Usage)
  - [Configuration](#Configuration)
  - [Documentation](#Documentation)
  - [Versions / Changelog](#Changelog)
  - [Roadmap](URL)

  <div align="center">
    A TundraDawn project
  </div>

</details>


## Installation
`npm install glitch.js`
## Usage
```Javascript
<script type="text/javascript">
  $(document).ready(function(){
    $("h1.glitch").glitch();
  });
</script>

```
# Documentation
## Configuration
```Javascript
<script type="text/javascript">
  $(document).ready(function(){
    $("h1.glitch").glitch({
        speed: 100,
        timeDiff: 300,
        done: function(element){
          $(element).css("opacity","1");
        }
      });
  });
</script>
```
###### `speed` : [ms]
Adjust the speed of the overall animation time.
###### `timeDiff` : [ms]
Adjust the difference it takes per letter to resolve to it's original letter.
###### `done` : [function(element)]
Callback fired once the animation is done, the target element is passed back for further control.
## Changelog
###### Versions
### Roadmap
