---
title: "Stereo-consistent Screen Space Reflection"
layout: publication
permalink: /publications/rilod25/
classes: wide
author_profile: false
---

# Reshadable Level of Detail Impostors for Fast Distant Objects Rendering
{: .text-center}

**Xiaolong Wu**, [Zheng Zeng](https://zheng95z.github.io/), [Junqiu Zhu\*](https://junqiuzhu.github.io/), [Lu Wang\*](https://wanglusdu.github.io/)
{: .text-center}

Computer Graphics Forum (Eurographics Symposium on Rendering 2025)
{: .text-center}

![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/images/RiLoD_teaser.png){: .align-center}


{% capture notice-2 %}
#### Abstract

We propose a new image-based representation for real-time distant objects rendering: Reshadable Impostors with Level-of-Detail (RiLoD). By storing compact geometric and material information captured from a few reference views, RiLoD enables reliable forward mapping to generate target views under dynamic lighting and edited material attributes. In addition, it supports seamless transitions across different levels of detail.
To support reshading and LoD simultaneously while maintaining a minimal memory footprint and bandwidth requirement, our key design is a compact yet efficient representation that encodes and compresses the necessary material and geometric information in each reference view. To further improve the visual fidelity, we use a reliable forward mapping technique combined with a hole-filling filtering strategy to ensure geometric completeness and shading consistency.
We demonstrate the practicality of RiLoD by integrating it into a modern real-time renderer. RiLoD delivers fast performance across a variety of test scenes, supports smooth transitions between levels of detail as the camera moves closer or farther, and avoids the typical artifacts of impostor techniques that result from neglecting the underlying geometry.
{% endcapture %}

<div class="notice">
  {{ notice-2 | markdownify }}
</div>

## Downloads
[Paper (20.9MB)](/assets/files/rilod25.pdf){: .btn .btn--primary}
[Supplementary video (145MB)](https://drive.google.com/file/d/1_iA8DDvX3cOiRk7J_boS2rR7LOxCYAok/view?usp=sharing){: .btn .btn--primary}
[Slides (Coming Soon)](){: .btn .btn--inverse}
## Videos
{% include video id="1_iA8DDvX3cOiRk7J_boS2rR7LOxCYAok" provider="google-drive" %}

## Cite

```html
Wait for being released...
```