---
layout: about
title: Seongwon Seo
permalink: /
subtitle: 

profile:
  align: right
  image: false #prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: false

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

<div id="intro-video-block" class="intro-video-wrapper">
  <video class="intro-video" autoplay muted loop playsinline>
    <source src="{{ '/assets/video/traininthecity.mp4' | relative_url }}" type="video/mp4">
  </video>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const video = document.getElementById("intro-video-block");
    const header = document.querySelector(".post-header");

    if (video && header) {
      header.parentNode.insertBefore(video, header);
    }
  });
</script>

I am an M.Sc. student in <a href="https://grizzly-fog-aed.notion.site/Applied-Machine-Learning-Lab-201ea12da6c880e3a329ef1057819d2a">Applied Machine Learning Lab</a> at Hanyang University in Seoul, South Korea, advised by Prof. Young-Min Kim. My current research focuses on improving the noise robustness of large language models in Retrieval-Augmented Generation. I am also interested in LLM attacks that exploit multi-turn interactions or emotional persuasion. I hope to study defense methods against such attacks through representation engineering.

I am an early-stage researcher with much to learn, and I hope to keep growing through research. I am always open to research-related discussions.

Email: <a href="mailto:finale22@hanyang.ac.kr">finale22@hanyang.ac.kr</a>