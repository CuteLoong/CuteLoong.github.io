---
title: "Stereo-consistent Screen Space Reflection"
layout: publication
permalink: /publications/scssr24/
classes: wide
author_profile: false
---

# Stereo-consistent Screen Space Reflection
{: .text-center}

**Xiaolong Wu**, Yanning Xu, [Lu Wang\*](https://wanglusdu.github.io/)
{: .text-center}

Computer Graphics Forum (Eurographics Symposium on Rendering 2024)
{: .text-center}

![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/images/scssr_teaser.png){: .align-center}


{% capture notice-2 %}
#### Abstract

Screen Space Reflection (SSR) can reliably achieve highly efficient reflective effects, significantly enhancing users' sense of realism in real-time applications. However, when directly applied to stereo rendering, popular SSR algorithms lead to inconsistencies due to the differing information between the left and right eyes. This inconsistency, invisible to human vision, results in visual discomfort. This paper analyzes and demonstrates how screen-space geometries, fade boundaries, and reflection samples introduce inconsistent cues. Considering the complementary nature of screen information, we introduce a stereo-aware SSR method to alleviate visual discomfort caused by screen space disparities. By contrasting our stereo-aware SSR with conventional SSR and ray-traced results, we showcase the effectiveness of our approach in mitigating the inconsistencies stemming from screen space differences while introducing affordable performance overhead for real-time rendering.
{% endcapture %}

<div class="notice">
  {{ notice-2 | markdownify }}
</div>

## Downloads
[Paper (5.17MB)](/assets/files/scssr24.pdf){: .btn .btn--primary}
[Slides (PPT, 90.3MB)](/assets/files/scssr_slide.pptx){: .btn .btn--primary}
[Supplementary video (145MB)](https://drive.google.com/file/d/1icTdxxT-4HsdN3RgxB9RYD81lFp5-3sO/view?usp=drive_link){: .btn .btn--primary}
[Shader code](/assets/files/scssr.zip){: .btn .btn--primary}
## Videos
{% include video id="1icTdxxT-4HsdN3RgxB9RYD81lFp5-3sO" provider="google-drive" %}

## Cite

```html
@inproceedings{wu2024stereo,
  title={Stereo-consistent Screen Space Reflection},
  author={Wu, X and Xu, Yanning and Wang, Lu},
  booktitle={COMPUTER GRAPHICS forum},
  volume={43},
  number={4},
  year={2024}
}
```