---
layout: post
title: Sequence (draft)
date: 2020-03-21 08:00:00 +0300
img: userjourney.jpg # Add image post (optional)
fig-caption: Photo by Mantas Hesthaven on Unsplash # Add figcaption (optional)
tags: [Eingabe]
---

# Base variant
Neither labs nor health authority participates

<div class="mermaid">
graph TD
     1[Lab identifies covid-patient]
     2[Fax to Health authority]
     3[Covid-patient gets notified by lab]
     4[Software-info to physician]
     1-->2
     1-->3
     1-->4
     5[Health authority contacts covid-patient]
     6[Covid-patient enters I have covid]
     7[Physicians informs patient]
     2-->5
     3-->6
     4-->7
     7-->6
     6-->8A[Contact A]
     6-->8B[Contact B]
     6-->8C[Contact C]
     6-->8D[Contact D]
     6-->8E[Contact E]
     5-->9[Covid-patient remembers contacts A,B,C]
     9-->8A
     9-->8B
     9-->8C


</div>