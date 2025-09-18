---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
---

{% assign cv_url = "/files/cv.pdf" | relative_url %}

{% include button.html text="Download CV (PDF)" icon="file-pdf" url=cv_url %}

<iframe src="{{ cv_url }}" width="100%" height="900" style="border:0"></iframe>

<p>若无法内嵌显示，请点击这里下载：
  <a href="{{ cv_url }}">Download CV (PDF)</a>
</p>

