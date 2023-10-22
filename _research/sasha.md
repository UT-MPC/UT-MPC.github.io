---
layout: sasha_page
title: Sasha
subtitle: A Smarter Smart Home Assistant
description: Smart home assistants function best when user commands are direct—e.g., "turn on the kitchen light"—or when there are hard-coded routines in place to specify the right responses. However, more natural human communication tends to be less constrained, allowing us to describe goals (e.g., "make it cozy in here") rather than specific actions. Current smart homes cannot understand such commands since they require creative reasoning about devices and settings as they relate to human situations. We approach this problem using large language models (LLMs), exploring their potential to control devices and create automation routines in response to under-specified user commands. We analyze the quality and failure modes of LLM-created action plans in the base case using a diverse N=20 user survey. We then introduce a key metric–target relevance–for evaluating model performance at the task, reporting results for several foundation LLMs. Finally, we introduce Sasha, a smarter smart home assistant. Sasha responds to commands like "make it cozy" or "help me sleep better" by executing plans to achieve user goals—e.g., setting a mood with available devices, or devising automation routines. We evaluate Sasha in a hands-on user study, showing its capabilities and limitations when faced with unconstrained user-generated scenarios.
img: assets/img/projects/sasha.jpg
participants: Evan King (Ph.D. student), Haoxiang (Steven) Yu (Ph.D. student), Sangsu Lee (Ph.D. student), Dr. Christine Julien (MPC director)
importance: 0
category: Current Projects
no_header: true
---

<p> Every smart home user interaction has an explicit or implicit goal. Existing home assistants easily achieve explicit goals, e.g., “turn on the light”. In more natural communication, however, humans tend to describe implicit goals. We can, for example, ask someone to “make it cozy” rather than describe the specific steps involved. Current systems struggle with this ambiguity since it requires them to relate vague intent to specific devices. We approach this problem of flexibly achieving user goals from the perspective of general-purpose large language models (LLMs) trained on gigantic corpora and adapted to downstream tasks with remarkable flexibility. We explore the use of LLMs for controlling devices and creating automation routines to meet the implicit goals of user commands. In a user-focused study, we find that LLMs can reason creatively to achieve challenging goals, while also revealing gaps that diminish their usefulness. We address these gaps with Sasha, a system for creative, goal-oriented reasoning in smart homes. Sasha responds to commands like “make it cozy” or “help me sleep better” by executing plans to achieve user goals—e.g., setting a mood with available devices, or devising automation routines. We demonstrate Sasha in a real smart home.</p>

<b>Demos: </b>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/vibrant.mp4" class="img-fluid rounded z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            Vibrant
        </div>
    </div>

    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/movie+popcorn.mp4" class="img-fluid rounded z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            Movie Popcorn
        </div>
    </div>

    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/popcorn%20burning.mp4" class="img-fluid rounded z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            popcorn burning
        </div>
    </div>

</div>


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/boring%20movie_1.mp4" class="img-fluid rounded z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            Boring Movie
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/chinese_1.mp4" class="img-fluid rounded z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            Chinese
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.stevenyu.xyz/assets/sasha/korean_1.mp4" class="img-fluid rounded z-depth-1" controls=false loop=true autoplay=true muted=true%}
        <div class="caption">
            Korean
        </div>
    </div>
</div>


<b>Project Participants: </b> 

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/members/evan.jpeg" title="Evan King" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Evan King
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/members/haoxiang_yu.jpg" title="Haoxiang (Steven) Yu" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Haoxiang (Steven) Yu
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/members/img_1789.jpg" title="Sangsu Lee" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Sangsu Lee
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/members/photo.jpg" title="Dr. Christine Julien" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Dr. Christine Julien
        </div>
    </div>
</div>

<b>Example Video: </b>
<div class="row">
    <div style="width: 100%;">
    <div style="position: relative; overflow: hidden; height: 0; padding-bottom: 56.25%;">
        <iframe src="https://www.youtube.com/embed/ZX_sc_EloKU?si=23LXnW3jjcUJo2iR" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; max-width: 100%;"></iframe>
    </div>
    </div>
</div>


<b>Publications: </b>
<ol>
  <li>Evan King, Haoxiang Yu, Sangsu Lee, Christine Julien. "Sasha: creative goal-oriented reasoning in smart homes with large language models" arXiv preprint arXiv:2305.09802 (2023).</li>
  <li>Evan King, Haoxiang Yu, Sangsu Lee, Christine Julien. "Get ready for a party: Exploring smarter smart spaces with help from large language models" arXiv preprint arXiv:2303.14143 (2023).</li>
</ol>