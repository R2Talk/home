---
layout: post
title: "Hight Performance!"
author: "Rodrigo Carvalho Santos"
date:   2023-05-24 16:27:39 -0300
categories: jekyll update
---

The 20th century witnessed a conscious investigation of organizational practices, from Taylor and his scientific management to references such as Peter Drucker and the Toyota Production System with its Lean approach. In the 21st century, we have advanced with the concept of Lean and Agile organizations, grappling with the significant impact of digitalization in all areas.

This article, based on the conclusions of the book *Accelerate* and other references, discusses critical factors for the dynamics and efficiency of high-performance organizations in digital solutions.

## Agility or Stability?

Before discussing critical factors for high performance, it is important to debunk the thesis that we need to choose between speed and stability. They are not exclusive options. Speed and stability need to go hand in hand as parameters for competitiveness. Segregating these two objectives as exclusive choices can lead to an organization with slow and unacceptable processes in the current competitive context, or innovations that generate problems and equally unacceptable unavailability.

We already have examples from Big Tech companies that demonstrate that speed and stability can and must coexist. The critical factors discussed here address both objectives.

## The Importance of Continuous Flow

*"All we are doing is looking at the timeline, from the moment the customer gives us an order until we collect the cash. And we are reducing that timeline by reducing the non-value-added wastes."* - Taiichi Ohno, *Toyota Production System: Beyond large-scale production*

Continuous flow is one of the fundamental principles of Lean organizations and involves maintaining uninterrupted demand flow until delivery. For organizations delivering digital solutions, it is mapped as Continuous Delivery.

Continuous Delivery can be defined as an approach that seeks to automate and simplify the process of delivering software to end users quickly, reliably, and frequently. This practice aims to reduce delivery cycles, enabling changes to proceed continuously and incrementally, rather than making significant changes spaced over time.

By adopting Continuous Delivery, the delivery process is automated from source code integration to production release, thereby reducing the risks and delays associated with manual implementations. Continuous Delivery goes beyond new features and also encompasses application data design changes, bug fixes, and experiments.

Among the benefits of Continuous Delivery are:

- **Speed:** Continuous deployments avoid long waiting times between changes, enabling the delivery of value to customers and users more rapidly.
- **Rapid feedback:** Delivering in small batches and with higher frequency allows for quick user feedback, enabling early identification of issues and immediate correction, thereby improving software quality and customer satisfaction.
- **Risk reduction:** Automation support minimizes human errors and facilitates incremental problem-solving.
- **Quality:** With automated testing and frequent integration, early detection of integration problems leads to more stable and reliable software.
- **Flexibility and adaptation:** Continuous Delivery provides companies with greater flexibility to respond to market changes and customer needs.
- **Efficiency and collaboration:** Continuous Delivery is supported by a collaborative culture among development, operations, and testing teams, advocated by the DevOps approach.

Research (see references) supports the conclusion that Continuous Delivery is associated with performance, not only in terms of delivery capability but also in terms of financial results and market share of companies.

The hypothesis reinforced in this brief article is that Continuous Delivery in a sustainable environment is the key characteristic of high-performance organizations.

To support Continuous Delivery, organizations must have the required culture, leadership, practices, and digital resources. The critical factors are discussed below.

## Critical Factors for Implementing Continuous Delivery

### Culture

*"Drive out fear and create trust so that everyone can work effectively."* - W. Edwards Deming

Unfortunately, many organizations are still classified as pathological, where control, suspicion, and fear dominate the environment. They ultimately generate an environment of low cooperation, where messengers are usually attacked, there is always someone to blame for failures, and new ideas are not even considered. In this type of culture, implementing continuous flow is not possible; on the contrary, we need to pursue the other end of the spectrum, which translates into a generative culture.

In a generative culture, people feel empowered to express their opinions, share their perspectives, and challenge the status quo without fear of retaliation. It is a culture that promotes creativity, innovation, collaboration, and continuous learning. The culture embraces change and is adaptable to new circumstances. It encourages flexibility, agility, and the ability to effectively respond to evolving market conditions and customer needs.

Although widely studied and recognized, culture is a complex process that depends on the local society, the organization's history, and its people. Experiences show that a successful path to adapt the culture lies in focusing on the organization's practices instead of attempting to impose a new way of thinking.

Two examples that support this conclusion can be seen in the Google research to identify what makes teams extraordinary and in John Shook's conclusion, a leadership figure at the Lean Enterprise Institute, based on his experience with cultural change in the joint venture between Toyota and GM in the United States at the NUMMI factory.

*"Who is on a team matters less than how the team members interact, structure their work, and view their contributions."* - Google Research

*"The way to change culture is not first to change how people think but to start by changing how people behave."* - John Shook

Although it is challenging to change people's way of thinking, local culture can be strongly influenced by adopting a way of working that naturally supports and encourages the desired direction.

By adopting Lean practices and automation that enable Continuous Delivery, the organization is taking a significant step towards cultural change. It would be doomed to failure if it were based solely on initiatives aimed at changing people's thinking.

### Leadership

Leadership is expected to establish and communicate goals, time to market, expected quality, and costs. They should invest in resources that empower people to solve problems and achieve objectives.

*"Management has no more critical role than motivating and engaging a large number of people to work together toward a common goal. Defining and explaining what the goal is, sharing a path to achieve it, motivating people to make the journey with you, and assisting them by removing obstacles - these are the reasons for management to exist."* - Jeffrey K. Liker, *The Toyota Way: 14 Management Principles From the World's Greatest Manufacturer*

Supporting teams with automated infrastructure and Lean practices enables Continuous Delivery and leads to extraordinary performance, which cannot be achieved through command and control alone.

### Lean Practices and Use of Digital Resources

Culture and leadership are critical factors for Continuous Delivery, but the complexity of digital solutions requires an appropriate solution architecture and process automation throughout the end-to-end flow. Without the support of these technical capabilities, Continuous Delivery is impossible. It's like having a workshop without a saw and hammer. It won't work.

Interruptions and synchronization of executions are major challenges that sabotage Continuous Delivery. Major changes that require long intervals between deliveries, regression testing that requires synchronization among multiple teams, time-consuming configuration of test and deployment environments, rework due to late identification of errors, bureaucratic change approval mechanisms, packaging to ensure simultaneous multiple versions, and other activities that come between the development team, who have the code ready (commit), and the client. Lean practices and systemic support for these practices are essential to overcome the daunting challenge of maintaining continuity with stability.

The following critical areas for implementing Continuous Delivery are mentioned:

## Architecture

- **Loosely coupled architecture:** A design with loose coupling increases the degree of freedom for evolutions, reducing the risk of side effects and the need for integration and testing with areas of the solution that should not be impacted. Examples of this trend can be found in the widespread use of microservices and environment virtualization.

## Lean Practices

- **Delivering in small batches instead of making big changes:** Systemic solutions that allow continuous evolution in small batches enable experts to quickly respond to customer demands and feedback with reasonable independence. Big changes guarantee bureaucratic processes and difficult integration, undermining the philosophy of continuity and high frequency required in high-performance organizations.

- **Light approval flows:** Approval committees are inefficient. It is important to evaluate how approval can follow a lighter process involving those who have the ability to assess impacts, such as the experts responsible for the change, supported by an integrated product vision.

- **Version control system:** In addition to code, test scripts, environment configuration, and version recovery should also be versioned and controlled.

- **Trunk-based development:** It is important to avoid the proliferation of solution versions as well as environment versions. Ideally, teams should reference a main version that is ready for deployment and work with few branches.

## Automation

- **Automated testing:** Testing is essential for solution stability. Regression tests should be automated, and change tests should be scheduled as part of the development cycle.

- **Pre-programmed security and compliance:** Security and compliance should be ensured by implementing orthogonal controls in the production environment (in the case of cloud solutions, on the platforms hosting the solution) as well as programmatically, with artifacts that are easily consumed by developers.

- **Delivery pipeline (automation of verification, configuration, and deployment activities):** The delivery process, from code release (commit) to availability for use, should follow a flow (pipeline) that ensures the necessary controls (e.g., verification, environment configuration, regression testing, integration, versioning, and communication of the change) with as many controls as possible automated.

## Conclusion

Continuous Delivery with stability and quality is an important mantra for organizations that deliver digital solutions. It has evolved from being merely a desirable factor to achieving extraordinary performance and is increasingly considered a prerequisite for competitiveness.

To achieve this status, in addition to a participative culture and leadership, organizations must have a low-coupling solution architecture; automated testing in the delivery flow; repositories for configuration control not only for code but also for environment configuration, deployment, and execution scripts; security and compliance addressed through native controls in platforms and programmable controls easily consumed by developers; and enable teams to work in small batches with maximum independence and high code release frequency (commits).

Implementing a high-productivity environment requires the use of automation technologies for each phase of the process and is only feasible with a competent technical team to configure and maintain the environment and automation. It is up to leadership to strategically envision this environment and enable it in collaboration with experts and other stakeholders in the organization.

To reflect: How is your organization connected to customer and user feedback, delivery frequency, and solution stability? Considering the critical factors for high performance, how much has been implemented?

*This article was originally written in Portuguese by Rodrigo Carvalho Santos and translated into English by ChatGPT.*

## References

- PHD, Nicole Forsgren; HUMBLE, Jez; KIM, Gene. Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations. USA: IT Revolution Press, 2018.

- RIES, Eric. The Lean Startup: How Today's Entrepreneurs Use Continuous Innovation to Create Radically Successful Businesses. São Paulo: Sextante, 2019.

- Shook, John. How to Change a Culture: Lessons from NUMMI. [Link](https://www.lean.org/downloads/35.pdf)

---

*About the Author:*
Rodrigo Carvalho Santos is the founder of R2Talk. With a deep passion for project management and digital solutions, he is dedicated to promoting effective team structures and project delivery practices. He believes in the power of teamwork and continuous improvement to drive successful outcomes.

*Note: This article is provided for informational purposes only and does not constitute professional advice. The author and publisher disclaim any liability for any actions taken based on the information provided in this article.*

