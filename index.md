---
layout: default
---

<img src="/images/Tanya2.png" alt="Tanya Marwah" class="profile-photo">

### Hello!

I am a Researcher at Google DeepMind working on AI and Science. I work on building models and tools that enable scientists to use AI and advance science. I enjoy learning from experts across fields and collaborating with them to push the frontiers of our understanding!

Previously, I was a Research Fellow at the [Simons Foundation](https://www.simonsfoundation.org/) working with [Polymathic AI](https://polymathic-ai.org/). I recently graduated with a PhD from the Machine Learning Department at Carnegie Mellon University, co-advised by [Andrej Risteski](https://www.andrejristeski.org/) and [Zachary Lipton](https://www.zacharylipton.com/). Previously, I was a masters student in the Robotics Institute at CMU and was a Siebel Scholar.

During my PhD, I had the pleasure to intern at Microsoft Research, New England in 2024 with David Alvarez-Melis, Lester Mackey, and Nicolo Fusi. Furthermore, I interned with the Blueshift team at Google in 2022 with Jascha Sohl-Dickstein, Guy Gur-Ari, Behnam Neyshabur, and Yasaman Bahri, where I worked on understanding generalization capabilities of LLMs.

You can find my CV [here](https://drive.google.com/file/d/1MQy3slOq3f0MQNfDQQz8pzIEm2stY6zx/view?usp=sharing).

## Selected Publications

{% for pub in site.data.publications %}{% if pub.selected %}{% include pub.html %}{% endif %}{% endfor %}

<a href="/publications" class="section-link">All publications &rarr;</a>
