# 🎬 Day 3: Multimedia Integration in HTML

Welcome to Day 3 of my Web Development journey! Today, I explored how to bring a webpage to life by integrating audio and video elements directly using HTML5.

## 🚀 Live Demo
You can view the live project by clicking the button below:

<a href="https://itsdishayk.github.io/HTML-Media-Elements/">
  <img src="https://img.shields.io/badge/View%20Live%20Project-blue?style=for-the-badge&logo=github" alt="Live Demo Button" height="40">
</a>

---

## 🎧 What I Learned Today

### 1. Audio Element
Learned how to embed sound files using the `<audio>` tag.
* **Attributes:** Used `controls` to give users play/pause and volume options.
* **Source:** Used `<source>` to specify the file path and type.

### 2. Video Element
Learned how to embed video content using the `<video>` tag.
* **Sizing:** Set specific `width` and `height` to maintain layout consistency.
* **User Experience:** Added the `controls` attribute to ensure accessibility.

### 3. Semantic Tags
Continued using `<section>`, `<article>`, and `<aside>` to keep the code organized and SEO-friendly.

---

## 🛠️ Code Snippets Used

```html
<audio controls>
    <source src="horse.ogg" type="audio/ogg">
</audio>

<video width="320" height="240" controls>
    <source src="mov_bbb.mp4" type="video/mp4">
</video>
