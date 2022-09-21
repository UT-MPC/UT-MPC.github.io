---
layout: page
title: Balance
description:
    "Balance is an autonomous thermostat control framework that balances a range of user comfort levels (i.e. temperature settings for heating and cooling) with a user-defined monthly budget for heating and air conditioning costs.
    <br>
    <br>
    Our work is motivated by the large percentage of residential energy usage that is consumed by heating and cooling (HVAC) needs. Many commercial and academic approaches have been developed for autonomous thermostat control to reduce unnecessary HVAC usage. Such systems typically reduce HVAC usage by adjusting the thermostat setting while the house is unoccupied, so as not to disrupt occupants' thermal comfort. We instead consider the balance of the financial burden of HVAC costs with occupants' comfort desires. Balance is an agent-based approach to autonomous thermostat control that is based on the idea that many people are comfortable in a range of temperatures (for example, 68 to 75 degrees Fahrenheit in the summer). Those wishing to meet a certain energy bill each month may wish to adjust the thermostat in order to save money, but mentally converting from the thermostat setting to dollars on an energy bill is challenging, due to the variable impact of weather and household activities on energy used.
    <br>
    <br>
    Our Balance agent therefore aims to meet the user's monetary HVAC budget by adjusting the thermostat setting within the range of temperatures the user finds comfortable. The agent has two constraints - to meet the user's budget and to stay within the user's comfort range; and one optimization - maximize the user's comfort within that range. To-date, we have implemented a simple agent that accomplishes this task in realistic simulated environments, using real-time HVAC consumption data and indoor and outdoor temperature data to determine thermostat settings at regular intervals throughout each day. Ongoing work on Balance includes: 1) improving the Balance agent's control strategy through reinforcement learning techniques; 2) deploying the Balance agent in the real world, using an Ecobee Smart Thermostat; and 3) investigating the use of feedback, for example if a user provides a budget that is simply not feasible with the user's comfort levels."
img: assets/img/projects/naiveagent_realworld_formpcsite.png
participants: Kate McArdle (Ph.D. student), Dr. Christine Julien (MPC director)
importance: 1
category: Previous Projects
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/naiveagent_realworld_formpcsite.png" title="Balance's Project Picture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>Project Participants: </b> 
{{ page.participants }}