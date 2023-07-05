---
layout: post
title: "Start with the team!"
author: "Rodrigo Carvalho Santos"
date:   2023-07-05 16:27:39 -0300
categories: jekyll update
---

> "There's strength in unity." - Lieutenant Uhura.

Understanding team dynamics, particularly in organizations delivering digital solutions, is crucial. The team is the unit and driving force behind solution delivery, and if not structured consciously, it can become a counterforce to the organization's performance.

Authors Matthew Skelton and Manuel Pais conducted a well-regarded analysis in their book "Team Topologies," and this article addresses team structuring based on their reference. I will discuss this topic, considering five highly relevant points, taking into account DevOps practices, where the same team is responsible for the entire lifecycle of the solution, from demand to deployment, as well as post-monitoring and feedback evaluation.

### 1. Expected Competencies
> "I'm a doctor, not a mechanic." - Dr. McCoy

To understand structuring practices, it is essential to begin with what is expected of a team. Considering DevOps practices, the expectations for teams responsible for products and services are high. These expectations include:

- Understanding the business domain and strategy.
- Involvement throughout the demand-to-delivery process.
- Technical competence to deliver the complete solution.
- Monitoring and evaluating user feedback.
- Promptly responding to problems.
- Agility to evolve in response to feedback.

For teams with these competencies, whose work aligns with flows that meet business needs, Team Topologies defines the term "Stream Aligned."

It's important to remember that the focus is on the group, not the individual. Each team member must contribute their part to ensure the expected competencies are met. That's okay, Dr. McCoy!

### 2. Fundamental Types of Teams According to Team Topologies
> "I'm pleased to see that we have differences. May we together become greater than the sum of both of us." - Surak

Considering the following four fundamental types, structuring addresses complexity and maintains a focus on delivering value to the business.

#### Stream Aligned:
As explained earlier, this team is responsible for one or more processes in the value chain. Ideally, we would have only this type of team, and the others should work to support the work of this team, which directly serves the business.

#### Platform:
Being the product that enables other products or services, this team manages the platform so that the Stream Aligned team consumes services easily and with the assurance of platform operation and maintenance (version updates, technical monitoring, service SLAs, infrastructure maintenance, etc.).

This team should interact with the Stream Aligned team through simple APIs. The success of providing solutions-as-a-service is directly proportional to the reduction of the need for interaction. The platform team's priorities should not only be to maintain the platform but also to ensure that services are consumed correctly and with minimal effort.

At times, collaboration between the platform team and the Stream Aligned team will be more intense to ensure the necessary capacity for platform usage.

#### Enabler:
This team should empower and support Stream Aligned teams in executing activities orthogonal to the solution delivery cycle. Examples of supported activities include configuring and using deployment automation tools and knowledge domains such as regulatory and security.

The Enabler team acts as an expert consultant in automation tools, knowledge domains, and supports execution, minimizing the cognitive load on the Stream Aligned group.

#### Complicated Subsystems:
At times, highly complex topics that are not yet mastered by the Stream Aligned participants may arise. For example, imagine a scenario that requires the inclusion of Artificial Intelligence features in a service flow. Being a new andcomplex topic, this example may require the formation of a dedicated team to implement the Artificial Intelligence layer. The responsibility for addressing complex topics falls under the Complicated Subsystems type, which should provide low-coupling and user-friendly solutions.

One of the advantages of structuring teams according to the four fundamental types is the reduction of cognitive load on the teams when dealing with different topics. The Enabler, Platform, and Complicated Subsystems teams allow Stream Aligned teams, despite having end-to-end responsibility, to focus more on topics relevant to the business's value chain.

### 3. Team Size
> "Prejudices are eliminated when people get to know each other." - Kirk

A team is not just a group of people working toward a common purpose; the participants must have close and direct collaboration, agile communication, autonomy in action, and a sense of ownership over the topic.

This profile is not achieved with a large number of people. Best practices indicate that an ideal team size is between 5 and 9 people (like the famous "two pizzas team" - a team that can be fed with two pizzas - as mentioned by Amazon).

However, it is important to note that this is a best practice, not necessarily a restriction. The crucial factor is to critically evaluate whether the team, as an organizational unit, meets the expected communication, dynamics, and commitment.

In the early stages of a startup, a single team, usually including the founders, must handle all the expected competencies. But most organizations deal with multiple specialized processes in their value chain. A team that digitizes customer support will hardly have all the competencies to also handle the billing cycle. Therefore, in most cases, we need multiple Stream Aligned teams to meet business needs.

### 4. Interactions and Communication
> "Yes, sir. I'm trying to fill the awkward silence with irrelevant conversation." - Data

Communication is one of the pillars of management and development, but autonomy and focus on what is relevant should not be impacted by avoidable communication.

Structured communication interfaces should be kept to a minimum and intensified only when necessary to overcome difficulties.

It is important to assess how to automate processes and simplify interfaces to reduce the need for interactions and increase team autonomy.

The flow between demand and delivery will benefit if we eliminate interactions that hinder agility. Layers of managerial approval, change approval committees, synchronization between different teams, and other interactions largely focus on risk management and integrated validations. These objectives can also be addressed through automation and decoupled architecture.

> "The needs of the many outweigh the needs of the few, or the one." - Spock.

Decoupling and autonomy do not imply isolation. Teams with interfaces should be attentive to whether the product of their work is being used correctly and efficiently.

For example, if the Platform or Enabler teams identify difficulties in configuring and using APIs and tools, they should increase collaboration with the consuming Stream Aligned team. The aim is always to enable autonomy and avoid perpetuating dependence. It should be a proactive effort. Understanding usage and feedback from those with whom you have an interface triggers improvement by simplifying interfaces and taking actions to enhance capabilities, minimizing the need for interactions.

### 5. Solution Architecture and Conway's Law
Melvin Conway, in his paper "How do Committees Invent?," assessed that any organization developing systems (not just information systems) produces a design that is a copy of the organization's communication structure.

Considering Conway's Law, it is necessary to align the organization's structure with the desired solution architecture. If the teams are not organized effectively, it can hinder communication, collaboration, and the ability to deliver value to the business.

The goal is to create a structure that enables seamless communication and collaboration between teams, allowing them to deliver high-quality solutions efficiently. By aligning the team structure with the desired architecture, the organization can overcome communication silos and promote effective cross-functional teamwork.

### Conclusions

In conclusion, understanding the dynamics of teams is crucial for organizations delivering digital solutions. The team is the unit and driving force behind solution delivery, and if not structured consciously, it can impede organizational performance.

By considering the principles outlined in Team Topologies, such as defining expected competencies, identifying fundamental team types, determining appropriate team sizes, fostering effective interactions and communication, and aligning the solution architecture with the organization's structure, teams can work cohesively and efficiently to deliver value to the business.

In the fast-paced world of digital solutions, where agility, collaboration, and continuous delivery are paramount, a well-structured team can make a significant difference. So, let's embrace the power of effective team structuring and unleash the full potential of our organizations.

*This article was originally written in Portuguese by Rodrigo Carvalho Santos and translated into English by ChatGPT.*

### References


1. Skelton, Matthew; Pais, Manuel. *Team Topologies: Organizing Business and Technology Teams for Fast Flow*. Portland, Oregon. IT Revolution, 2019.

2. Sweller, John; Ayres, Paul; Kalyuga, Slava. *Cognitive Load Theory*. Explorations in the Learning Sciences, Instructional Systems and Performance Technologies. London. Springer, 2011.

3. Conway, Melvin. ["How do Committees Invent?"](https://www.melconway.com/Home/pdf/committees.pdf)

4. Skelton, Matthew; Pais, Manuel. ["Team Cognitive Load."](https://itrevolution.com/articles/cognitive-load/)

5. Skelton, Matthew; Pais, Manuel. ["Minimize Team Cognitive Load to Increase Flow."](https://itrevolution.com/articles/minimize-cognitive-load-of-teams/)

6. Bernstein, Ethan; Dhore, Jesse; Lazer, David. ["How Intermittent Breaks in Interaction Improve Collective Intelligence."](https://www.hbs.edu/faculty/Pages/item.aspx?num=54901)

---

*About the Author:*
Rodrigo Carvalho Santos is the founder of R2Talk. With a deep passion for project management and digital solutions, he is dedicated to promoting effective team structures and project delivery practices. He believes in the power of teamwork and continuous improvement to drive successful outcomes.

*Note: This article is provided for informational purposes only and does not constitute professional advice. The author and publisher disclaim any liability for any actions taken based on the information provided in this article.*

