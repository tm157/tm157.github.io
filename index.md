Hi! I am a Research Fellow at the [Simons Foundation](https://www.simonsfoundation.org/) working with [Polymathic AI](https://polymathic-ai.org/). I recently graduated with a PhD from the Machine Learning Department at Carnegie Mellon University co-advised by [Prof. Andrej Risteski](https://www.andrejristeski.org/) and [Prof. Zachary Lipton](https://www.zacharylipton.com/). Previously, I was masters student in the Robotics Institute at CMU and was a Siebel Scholar.

I work on the empirical and theoretical foundations of Machine Learning and its applications to scientific domains. My current interests are around generative modeling of scientific phenomena, inverse problems and building scientific agents. My ultimate goal is to develop ML algorithms and methods that help us accelerate the scientific process and enable scientific discovery. 

You can find my CV [here](https://drive.google.com/file/d/1MQy3slOq3f0MQNfDQQz8pzIEm2stY6zx/view?usp=sharing).

---
## Selected Publications
[CodePDE: An Inference Framework for LLM-driven PDE Solver Generation](https://arxiv.org/abs/2505.08783) \
Shanda Li, **Tanya Marwah**, Junhong Shen, Weiwei Sun, Andrej Risteski, Yiming Yang, Ameet Talwalkar \
**In Submission**

[Towards characterizing the value of edge embeddings in GNNs](https://arxiv.org/abs/2410.09867) \
Dhruv Rohatgi, **Tanya Marwah**, Zachary C. Lipton, Jianfeng Lu, Ankur Moitra, Andrej Risteski \
NeurIPS Mathematics of Modern Machine Learning Workshop, 2024 (Oral) \
International Conference on Machine Learning, 2025 (ICML)

[On the Benefits of Memory for Modeling Time-Dependent PDEs](https://arxiv.org/abs/2409.02313) \
Ricardo Buitrago Ruiz, **Tanya Marwah**, Albert Gu, Andrej Risteski \
International Conference on Learning Representations (ICLR), 2025 (Oral)


[UPS: Towards Foundation Models for PDE Solving via Cross-Modal Adaptation](https://arxiv.org/abs/2403.07187)\
Junhong Shen, **Tanya Marwah**, Ameet Talwalkar \
ICML AI4Science Workshop, 2024 (Spotlight) \
Transactions on Machine Learning Research (TMLR), 2024

[Deep Equilibrium Based Neural Operators for Steady-State PDEs](https://arxiv.org/abs/2312.00234)\
**Tanya Marwah<sup>\*</sup>**, Ashwini Pokle<sup>\*</sup>, J. Zico Kolter, Zachary C. Lipton, Jianfeng Lu, Andrej Risteski \
Neural Information Processing Systems (NeurIPS), 2023

[Neural Network approximations of PDEs Beyond Linearity: A Representational Perspective](https://arxiv.org/abs/2210.12101)\
**Tanya Marwah**, Zachary C. Lipton, Jianfeng Lu, Andrej Risteski \
International Conference on Machine Learning (ICML), 2023

[Disentangling the Mechanisms Behind Implicit Regularization in SGD](https://arxiv.org/abs/2211.15853)\
Zachary Novack, Simran Kaur, **Tanya Marwah**, Saurabh Garg, Zachary C. Lipton\
International Conference on Learning Representations (ICLR), 2023

[Parametric Complexity Bounds for Approximating PDEs with Neural Networks](https://arxiv.org/abs/2103.02138) \
**Tanya Marwah**, Zachary C. Lipton, Andrej Risteski \
Neural Information Processing Systems (NeurIPS), 2021 (Spotlight)

[Attentive Semantic Video Generation using Captions](https://openaccess.thecvf.com/content_ICCV_2017/papers/Marwah_Attentive_Semantic_Video_ICCV_2017_paper.pdf) \
**Tanya Marwah<sup>\*</sup>**, Gaurav Mittal<sup>\*</sup>, Vineeth N Balasubramanian \
IEEE International Conference on Computer Vision (ICCV), 2017


---
## Working Paper
[Chimera: State Space Models Beyond Sequences](https://drive.google.com/file/d/1W-E3K5QA2XyCRZm9iMuFeFs0SiP86xz7/view?usp=sharing) \
Aakash Lahoti<sup>\*</sup>, **Tanya Marwah<sup>\*</sup>**, Albert Gu \
*In Submission*

[Improving Zero-Shot Reasoning Using Dynamic Non-Verbal Tokens](https://drive.google.com/file/d/1y4hQ03PmEr2AW5VTsts7JJQoSPZywLaW/view?usp=sharing) \
**Tanya Marwah**, Zhili Feng, Lester Mackey, Nicolo Fusi, David Alvarez-Melis 


## Selected Publications

<div class="grid">
{% for category in site.ordered_categories %}
    <div class="unit span-grid">
        <ul class="projects">
        {% for post in site.categories[category] %}
            {% if post.featured %}
                {% capture url %}
                    {% if post.actual_url != null and post.actual_url != "" %}
                        {{ post.actual_url }}
                    {% else %}
                        {{ post.url }}
                    {% endif %}
                {% endcapture %}
                
                <li>
                {% if post.thumbnail %}
                    <img src="{{ post.thumbnail }}" width="180px">
                {% endif %}

                <div>
                <h4 class="projects-post">
                {% if post.metadata_only %}
                    <span markdown="1">{{ post.title }} - {{ post.links }}</span>
                {% else %}
                    <span markdown="1"><a href="{{ url }}" target="_blank">{{ post.title }}</a></span>
                {% endif %}
                </h4>
                <h6>
                {% if post.author %}
                    {{post.author}}
                {% endif %}
                </h6>
                {% if post.extra %}
                  &nbsp; &nbsp; <h6 class="extra"> {{ post.extra }}</h6>
                {% endif %}
                {% if post.abstract %}
                {% endif %}
                {% if post.bullets %}
                    {{ post.bullets | markdownify }}
                {% endif %}
                </div>
                </li>
            {% endif %}
        {% endfor %}
        </ul>
    </div>
{% endfor %}
</div>

---


## Working Papers

<div class="grid">
{% for category in site.project_categories %}
    <div class="unit span-grid">
        <ul class="projects">
        {% for post in site.categories[category] %}
            {% if post.featured %}
                {% capture url %}
                    {% if post.actual_url != null and post.actual_url != "" %}
                        {{ post.actual_url }}
                    {% else %}
                        {{ post.url }}
                    {% endif %}
                {% endcapture %}

                <li class="nothumb">
                {% if post.thumbnail %}
                    <img src="{{ post.thumbnail }}" width="180px">
                {% endif %}

                <div>
                <h4 class="projects-post">
                {% if post.metadata_only %}
                    <span markdown="1">{{ post.title }} {{ post.links }}</span>
                {% else %}
                    <span markdown="1"><a href="{{ url }}" target="_blank">{{ post.title }}</a></span>
                {% endif %}
                </h4>
                <h6>
                {% if post.author %}
                    {{post.author}}
                {% endif %}
                </h6>
                {% if post.extra %}
                  &nbsp; &nbsp; <h6 class="extra"> {{ post.extra }}</h6>
                {% endif %}
                {% if post.bullets %}
                    {{ post.bullets | markdownify }}
                {% endif %}
                </div>
                </li>
            {% endif %}
        {% endfor %}
        </ul>
    </div>
{% endfor %}
</div>