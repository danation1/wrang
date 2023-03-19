<style>
html {
    background-color: #f6f6f6;
    margin: 16px;
}
body {
    color: #333;
    font-family: "Open Sans", "Helvetica Neue", "Segoe UI", Helvetica, Arial, sans-serif;
}
ul {
    padding-left: 1.2rem;
}
li { margin: 2px; }
ul.topic {
    margin-top: 0;
    padding-left: 1.5rem;
}
ul.topic ul {
    margin: 0.2em 0;
}
h1 {
    font-size: 2.0rem;
    margin: 0;
}
h2 {
    color: #444;
    font-size: 1.4rem;
    margin: 1em 0 0.1em 0;
}
h3 {
    color: #666;
    font-size: 1.05rem;
    margin: 1em 0 0.25em 0.5em;
    font-weight: bold;
}
a {
    color: #000;
}
article { display: block; }
.release-date, .forum-link {
    font-size: 0.9rem;
    font-style: italic;
    color: #666;
}
</style>

<h1>Stable Channel Changelog</h1>

<article class="current">
<h2>3.2.2 (Build 3211)</h2>
<div class="release-date">1 October 2019</div>
<ul>
    <li>Mac: Added Notarization</li>
    <li>Fixed a performance regression when moving the caret upwards in large files</li>
    <li>Fixed a memory leak</li>
    <li>Fixed not being able to swap lines down with the last line if
