---
layout: sasha_page
title: Sasha
subtitle: Creative Goal-Oriented Reasoning in Smart Homes With Large Language Models
description: Smart home assistants function best when user commands are direct–e.g., "turn on the kitchen light"—or when there are hard-coded routines in place to specify the right responses. However, more natural human communication is much less constrained, allowing us to describe goals (e.g., "make it cozy in here") rather than specific actions. Current smart homes cannot understand such commands since they require creative reasoning about devices and settings as they relate to human situations. We approach this problem using large language models (LLMs), exploring their potential to control devices and create automation routines in response to under-specified user commands. We analyze the quality and failure modes of LLM-created action plans in the base case and introduce a key metric–target relevance–for evaluating a model's performance at the task. Finally, we introduce Sasha, a smarter smart home assistant. Sasha responds to commands like "make it cozy" or "help me sleep better" by executing plans to achieve user goals—e.g., setting a mood with available devices, or devising automation routines. We demonstrate Sasha in a real-world implementation and user study, showing its capabilities and limitations when faced with unconstrained user-generated scenarios.
img: assets/img/projects/sasha.jpg
participants: Evan King (Ph.D. student), Haoxiang (Steven) Yu (Ph.D. student), Sangsu Lee (Ph.D. student), Dr. Christine Julien (MPC director)
importance: 0
category: Current Projects
no_header: true
---

<style>
    hr {
        border-color: #ddd;
        padding-bottom: 1em;
    }

    .post-description {
        font-size: large;
    }

    .abstract {
        padding-bottom: 1em;
    }

    .sasha-profile {
        width: 165px;
        height: 165px;
        border-radius: 50%;
        object-fit: cover; /* use the one you need */
    }

    .sasha-profile-link {
        color: black;
    }

    footer {
        display: none;
    }
</style>

<p class="abstract"> Smart home assistants function best when user commands are direct—e.g., "turn on the kitchen light"—or when there are hard-coded routines in place to specify the right responses. However, more natural human communication is much less constrained, allowing us to describe goals (e.g., "make it cozy in here") rather than specific actions. Current smart homes cannot understand such commands since they require creative reasoning about devices and settings as they relate to human situations. We approach this problem using large language models (LLMs), exploring their potential to control devices and create automation routines in response to under-specified user commands. We analyze the quality and failure modes of LLM-created action plans in the base case and introduce a key metric—target relevance—for evaluating a model's performance at the task. Finally, we introduce Sasha, a smarter smart home assistant. Sasha responds to commands like "make it cozy" or "help me sleep better" by executing plans to achieve user goals—e.g., setting a mood with available devices, or devising automation routines. We demonstrate Sasha in a real-world implementation and user study, showing its capabilities and limitations when faced with unconstrained user-generated scenarios. </p>

---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/vibrant.mp4" class="img-fluid z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            "Make it vibrant and colorful in here"
        </div>
    </div>

    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/movie+popcorn.mp4" class="img-fluid z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            "I want to watch a movie and have some popcorn"
        </div>
    </div>

    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/popcorn%20burning.mp4" class="img-fluid z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            "I think the popcorn is burning"
        </div>
    </div>

</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/boring%20movie_1.mp4" class="img-fluid z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            "This movie is pretty boring"
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/chinese_1.mp4" class="img-fluid z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            "請幫我再多準備一點咖啡" <br>
            "Please help me prepare more coffee"
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/korean_1.mp4" class="img-fluid z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            "커튼 밖의 세상이 보고 싶어" <br>
            "I want to see the world outside the curtains"
        </div>
    </div>
</div>

---
<div class="row">
    <div class="col-6 col-sm-3" style="text-align: center;">
        {% include figure.html path="assets/img/members/evan.jpeg" title="Evan King" class="img-fluid z-depth-1 sasha-profile" %}
        <div class="caption">
            <a class="sasha-profile-link" href="https://evanking.io">Evan King</a>
        </div>
    </div>
    <div class="col-6 col-sm-3" style="text-align: center;">
        {% include figure.html path="assets/img/members/haoxiang_yu.jpg" title="Haoxiang (Steven) Yu" class="img-fluid z-depth-1 sasha-profile" %}
        <div class="caption">
            <a class="sasha-profile-link" href="https://www.stevenyu.xyz">Haoxiang (Steven) Yu</a>
        </div>
    </div>
    <div class="col-6 col-sm-3" style="text-align: center;">
        {% include figure.html path="assets/img/members/img_1789.jpg" title="Sangsu Lee" class="img-fluid z-depth-1 sasha-profile" %}
        <div class="caption">
            <a class="sasha-profile-link" href="https://leesangsu.com">Sangsu Lee</a>
        </div>
    </div>
    <div class="col-6 col-sm-3" style="text-align: center;">
        {% include figure.html path="assets/img/members/photo.jpg" title="Christine Julien" class="img-fluid z-depth-1 sasha-profile" %}
        <div class="caption">
            <a class="sasha-profile-link" href="https://users.ece.utexas.edu/~julien/">Christine Julien</a>
        </div>
    </div>
</div>

---

<div class="row">
    <div class="col-sm mt-3" style="padding-bottom: 1em;">
    <div style="position: relative; overflow: hidden; height: 0; padding-bottom: 56.25%;">
        <iframe src="https://www.youtube.com/embed/ZX_sc_EloKU?si=23LXnW3jjcUJo2iR" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; max-width: 100%; border: none;"></iframe>
    </div>
    </div>
</div>

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <h4>Publications</h4>
        <p>Evan King, Haoxiang Yu, Sangsu Lee, Christine Julien. "Sasha: creative goal-oriented reasoning in smart homes with large language models" arXiv preprint <a href="https://arxiv.org/abs/2305.09802">arXiv:2305.09802</a> (2023).</p>
        <p>Evan King, Haoxiang Yu, Sangsu Lee, Christine Julien. "Get ready for a party: Exploring smarter smart spaces with help from large language models" arXiv preprint <a href="https://arxiv.org/abs/2303.14143">arXiv:2303.14143</a> (2023).</p>
    </div>
</div>