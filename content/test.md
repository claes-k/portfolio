---
Title: Test
Description: This is a test page.
---

<style>
/* * {
  box-sizing: border-box;
  margin: 0 auto;
  padding: 0;
} */

li, li a {
  color: purple;
}

li:first-child, li:first-child a {
  color: red;
}

li:last-child, li:last-child a {
  color: pink;
}

li:hover, li:hover a {
  color: green;
}

li:visited, li:visited a {
  color: orange;
}

div {
  color: white;
}

.first-box {
  box-sizing: content-box;
  width: 600px;
  height: 100px;
  background-color: black;
}

.second-box {
  box-sizing: content-box;
  width: 100%;
  height: 100px;
  background-color: blue;
}

.third-box {
  box-sizing: border-box;
  width: 50vw;
  height: 100px;
  background-color: red; 
}

.fourth-box {
  box-sizing: border-box;
  width: 100%;
  height: 100px;
  background-color: green;
}
</style>

<ul>
  <li><a href="#">Test link</a></li>
  <li><a href="#">Test link</a></li>
  <li><a href="#">Test link</a></li>
  <li><a href="#">Test link</a></li>
  <li><a href="#">Test link</a></li>
</ul>

<div class="first-box">600px</div>
<div class="second-box">100%</div>
<div class="third-box">50vw</div>
<div class="fourth-box">100%</div>