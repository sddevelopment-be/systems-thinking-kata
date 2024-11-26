+++
title = "Project vs Product"
subtitle = "A Systems Thinking kata based on LeSS principles"
aliases=["kata", "project_vs_product"]
outputs = ['html', 'rss']
author = "Stijn Dejongh"
description = ""
summary="""
"""
further_exploration = [
  {type="raw", author="Edwin Burgers", year="2024", title="SoCraTesBE 2024 talk: Project or product?", link="https://socratesbe.org/", site="socrates.be"},
  {type="raw", author="The LeSS Company B.V.", year="2024", title="LESS: Architecture & Design", link="https://less.works/less/technical-excellence/architecture-design", site="LeSS company website"},
  {type="raw", author="McMaster University", year="2024", title="SPARK: Addressing Complexity Toolkit", link="https://spark.mcmaster.ca/", site="MC Master University"}
]
+++

# Systems Thinking Kata: Project vs Product

We will use the causal loop diagramming technique to investigate the impact of working in a "project" vs "product" mode on the business goal of
delivering as much value to our customers as possible. To achieve this, we will follow the reasoning of existing literature, and use them to
construct a model that represents the relationships between the different elements.

Participants will work in groups to discuss the relationships between the different elements, and will use the diagram to facilitate the
discussion. Our main learning objectives are two-fold:

* We want to understand the complexity of choosing an approach
* We want to learn how to use the causal loop diagramming technique to model complex systems.

## Structure

The session will be structured as a series of increments, working from a simple (provided) base system to a more complex model that includes a
plethora of elements. Ideally, the session can be conducted in a workshop setting, where participants can work in groups (up to 4 people) to
collaboratively build the diagram. The session will be facilitated by a person who is familiar with the technique, and who can guide the
participants through the process, providing context and explanations where necessary, and can be called upon to answer questions or make a judgement
call to "unblock" a group/participant and keep the session moving forward.

The session will progress in a series of steps, where we will add new elements to the diagram, and discuss how they interrelate with the existing
elements. After each step, people will have the opportunity to discuss their findings, reasoning, and any insights they have gained.
Afterwards, an "example solution" will be presented, based on the contents of various literature sources.
This will be used to compare and contrast the different approaches, and to highlight the intricacies of creating a model of a complex adaptive system.

In order for the sessions to be successful, participants are offered the opportunity to reset their diagram at any time, and to continue their
work on top of the existing example solution. This will allow them to explore different paths, while still having a reference point to fall back
to in case they get stuck or diverge too far from the provided example.

{{< tip text=`
**Remember the Guiding Principle of Models:**  
All models are wrong, some happen to be useful.` >}}

The existence of an "example solution" is not meant to be prescriptive, but rather to provide a reference point for participants to compare
their own reasoning and findings against. As mentioned in the first law of diagramming, the primary value in diagrams is in the discussions we
have while creating them. The example solution is meant to facilitate these discussions, and to provide a starting point for further exploration.
**They are not meant to be the final word on the subject, but rather a stepping stone to further understanding.**

## Background

## System modeling exercise

### **Step 1:** Identify the Base Elements

{{< info text=`We should have customer focus -- deliver as much value to our customers as possible.` >}}


The base elements are the core elements that are essential to the business goal of the organization. In this case, the core premise is that the
organization should have a customer focus and deliver as much value to their customers as possible. As such, we will identify the following key
elements that make up the base system:


* **Customer Satisfaction Rate:** The business goal of the organization.
* **Alignment between product and customer needs:** The degree to which the product meets the needs of the customer.
* **Length of the feedback loop:** The time it takes to get feedback from the customer.

{{< image src="/images/kata/base_elements_CONNECT-US.png" alt="Core elements" size="50%">}}

{{< exercise text=`
Using the provided base elements, create a causal loop diagram that shows the relationships between the
elements. Focus on the primary relationships between the elements, and aim to map out the key interactions between the elements.
` >}}


<details class="content pattern related">
<summary>Click here to view a potential solution</summary>

{{< image src="/images/kata/base_elements_CONNECTED.png" alt="Core elements" >}}
</details>

### **Step 2:** Add Organizational Elements

{{< info text="That's a lot of work, big impact... We need to organise that!" >}}

In this step, we will identify the organizational elements that impact the base system.
These elements are the organizational structures, processes, and practices that influence the delivery causal system.
Our goal is to indentify how these elements impact the existing system elements, i.e. whether they have a counteracting (Opposite) or
reinforcing (same) effect.


The organizational elements we will consider are:

* **Ability to rapidly change what we're working on:** The organization's ability to quickly change direction, also known as 'adaptability' or
  'business agility'.
* **Commited scope, agreement on batch size:** The organization's promise on what they will be delivering, and how large the increments will be.
* **Organisational Complexity:** The amount of different divisions within the company, the existence of prescriptive processes, and the
  decision-making mechanism that are in place.
* **# of Handovers:** The number of times a piece of work is handed over from one team to another.
* **Lead Time:** The time it takes to deliver a piece of work from start (concept) to finish (delivered value in hands of end-users).

{{< image src="/images/kata/organizational_elements_CONNECT-US.png" alt="Connect the organizational elements" size="100%" >}}

{{< exercise text=`
Add the organizational elements to the diagram and identify the relationships between the elements.
Focus on the primary relationships between the elements, and aim to map out the key interactions between the existing and new elements.
There are no right or wrong answers, but the goal is to have a conversation about how the organizational elements impact the base system.
` >}}



<details class="content pattern related">
<summary>Click here to view a potential solution</summary>

{{< image src="/images/kata/organizational_elements_CONNECTED.png" alt="Connected the organizational elements">}}

</details>

### **Step 3:** Add Timeliness Elements

{{< info text="We did finish what we agreed to! Once we deploy it in production, we just need to ..." >}}

Next to the organizational elements, deliveries are impacted by system elements that relate to the timeliness of producing and delivering
artefacts. In this step, we will identify the timeliness elements that impact the base system. 
These elements are the time-related factors that influence the delivery causal system. We will consider the following elements:

* **Time pressure:** A type of psychological stress that occurs when there is less (perceived) time available than is required to complete a task.
* **Quality:** The build quality of the delivered artifacts. (e.g. Maintainability, lack of technical debt, lack of defects)
* **Ownership:** The feeling of responsibility for the product by the team that is working on it.
* **Team Stability:** How fixed / temporary people are part of the team.
* **End-to-end agency:** Ability to deliver value independently.

{{< image src="/images/kata/timing_elements_CONNECT-US.png" alt="Connect the timeliness-based elements" size="100%" >}}

{{< exercise text=`
Add the timeliness elements to the diagram and identify the relationships between the elements.
Aim to map out the key interactions between the existing and new elements.
` >}}


<details class="content pattern related">
<summary>Click here to view a potential solution</summary>

{{< image src="/images/kata/timing_elements_CONNECTED.png" alt="Connected the timeliness elements">}}

</details>

### **Step 4:** Add Risk Mitigation Elements

{{< info text="No, we can't do that. It is out of scope, and we'd go over budget." >}}

We have now identified the base value proposition, and added both organizational, and time-related system interactions to our causal diagram.
The next step is to apply "risk mitigation" elements to the diagram. These elements represent how organizations typically deal with risks and 
potential issues that may arise during the delivery process. We will consider the following elements:

* **Number of Inspection Opportunities:** Amount of chances to validate the business cases the organization is working to support/enable.
* **Risk of overruns:** The risk of a delivery costing significantly more than what we were initially willing to invest in it. (Sunk Cost)
* **Risk Avoidance:** Focusing on avoiding risks, rather than delivering valuable features. Favouring output over outcome. (e.g. scope negotiation,
  risk management, politics, window dressing)
* **Onboarding / Offboarding cost:** Additional effort required to bring new team members up to speed, or to ensure a smooth transition when team
  members leave.

{{< image src="/images/kata/risk_elements_CONNECT-US.png" alt="Connect the risks and mitigation elements" size="100%" >}}

{{< exercise text=`
Add the risk mitigation elements to the diagram and identify the relationships between the elements.
Aim to map out the key interactions between the existing and new elements.` >}}

<details class="content pattern related">
<summary>Click here to view a potential solution</summary>

{{< image src="/images/kata/risk_elements_CONNECTED.png" alt="Connected the risk and mitigation elements">}}

</details>


## Round-Up

### Conclusions and Learnings

{{< stub >}}


### Next Steps?

{{< stub >}}
