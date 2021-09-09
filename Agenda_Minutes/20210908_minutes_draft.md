[MINUTES IN DRAFT - Details still to be added]

# 2021.09.08 Minutes.  
Time 1700 PM (BST)

- Chair – [Pierre Lagarde](https://www.linkedin.com/in/pierlag/) (Microsoft) 
- Co-Chair - [Dan Lewis-toakley ](https://www.linkedin.com/in/danlewistoakley/) (Thoughtworks)
- Convener – [Sean Mcilroy](https://www.linkedin.com/in/sean-mcilroy-bb3b5548/) (Linux Foundation)
  
## Roll call 
Sean Mcilroy - LF<br>
Asim Hussain - MS<br>
Antonino Fisichella - MS<br>
Arelys Alvarez - TW<br>
Cameron Casher - TW<br>
Pierre Lagarde - MS<br>
Cameron Casher - TW<br>
Chiara Giglio - Intesa Sanpaolo<br>
Dan Lewis-Toakley - TW<br>
Lopez Dominguez - Globant<br>
Henry Richards - WT<br>
Mark Leveck - MS<br>
Mihaela Turturean - Intesa Sanpaolo<br>
Navveeen Balani - Accenture<br>
Paraskevi Zerva - MS<br>
Santiago Fontanarrosa - Globant<br>
Tammy McClellan - MS<br>
Taylor Prewitt - MS<br>
Vaughan Knight- MS<br>
Wadood Daoud - MS<br>
Matt Kotsenas - MS<br>
Mihaela Turturean - Intesa Sanpaolo<br>
  
## Antitrust Policy
Linux Foundation meetings involve participation by industry competitors, and it is the intention of the Linux Foundation to conduct 
all of its activities in accordance with applicable antitrust and competition laws. 
It is therefore extremely important that attendees adhere to meeting agendas, and be aware of, and not participate in, any activities 
that are prohibited under applicable US state, federal or foreign antitrust and competition laws.

Examples of types of actions that are prohibited at Linux Foundation meetings and in connection with Linux Foundation activities are 
described in the Linux Foundation Antitrust Policy available at http://www.linuxfoundation.org/antitrust-policy. 
If you have questions about these matters, please contact your company counsel, or if you are a member of the Linux Foundation, 
feel free to contact Andrew Updegrove of the firm of Gesmer Updegrove LLP, which provides legal counsel to the Linux Foundation.
  
## Agenda Approval (decision) 
2021.09.08 Agenda
> Sean Mcilroy reviews the agenda. Asim moves to adopt the agenda. All are in favour. The agenda is agreed
  
## Approval of previous meeting minutes (decision)
[2021.08.25_Minutes](https://github.com/Green-Software-Foundation/innovation_wg/blob/main/Agenda_Minutes/20210825_Minutes.md)
> Vaughan Knight moves to approve the minutes 2021.08.25_Minutes. All are in favour. The Minutes are agreed

## Review project presentation (decision)
Asim Hussain

Asim started the converstion by providing an overview of the [GSF Handbook](https://docs.google.com/document/d/162LCoTTHbsvlIT0CDggkiKCo5JPXHuFY9nawgYvd-GM/edit#heading=h.unejr3ik7vmp) and highlighted the following information;

Each GSF Project must:
- Belong to one GSF Working Group and follow the patent/IP and copyright agreement of that working group.
- Has at least one project lead.
- Has at least 3 team members, two of which must be from different organizations.
- Have consensus agreement to launch, and continue functioning, from its working group.
- Have a one page project summary document covering these topics [template here](https://docs.google.com/document/d/1WxbtbO_FCrOBa0Lw7ti8Vr2-Dd5KdLW8FMwdgKgt26o/edit):
- Project scope:
  - Why does the project help GSF meet its mission?
  - How will the project be structured and managed?
  - What resources are required?
  - What are the deliverables and rough timeline?

Pierre outlined the Scaling for the project approval process --> 1 week to present project proposal --> 2nd week Q&A's --> 3rd week Working Group decision

## Carbon-Aware API (presentation)
[William Buchanan - Deliverable: OSS carbon-aware ML platform](https://github.com/Green-Software-Foundation/innovation_wg/issues/4) 

William started by presenting 
Deliverable: OSS carbon-aware ML API via Green Software Foundation
Core Scenarios:
1) Retrospective analysis: analyze benefits of load shifting/compare methodologies 2) Regional carbon-intensity exploration
3) Workload scheduling: shift jobs (time/region) to optimize emissions
4) Carbon counterfactual: quantify carbon savings from usage telemetry
Roadmap
[Aug] Internal MVP pilots/usage (MSAI, MSR, Substrate)
[Sept] Open Source development through Green Software Foundation (funding/support needed) [early Oct] Case studies & Hackathon (region picker?)
[mid-Oct] Marketing
[Jan ‘22] OSS launch

Pierre asked if other organisations wanted to support this project - Globant indicated they'd like to offer their support.
Asim requested for Will to submit this proposal in the current GSF project submission doc.
Will indiated that the repo for this project is currently private but it will be made public today.

> Action Item - Will to submit this project proposal in the current GSF project template.
> Action Item - Will to notify members when the project repo is public

## Carbon Aware Orchestration (presentation)
Vaughan Knight - [Github Builds](https://docs.google.com/document/d/19_Pe0q9zcuqKkBTjhBBNWywwIpjnFn1L64XhIbCgflE/edit#)

Vaughan Knight

a. Project: [Carbon Aware Github Actions Workflows](https://docs.google.com/document/d/19_Pe0q9zcuqKkBTjhBBNWywwIpjnFn1L64XhIbCgflE/edit#heading=h.vf8eis1osru9)

Vaughan started by reviewing the project submission for the Carbon Aware Github Actions Workflows - Carbon Aware Github Actions Workflows is a project focused on creating carbon-aware build pipelines in GitHub actions.  Specifically, workflows can trigger self-hosted runners that can be located anywhere in the world, and many build jobs can occur often with time flexibility.  As such this project will be focusing on triggering these build workloads in preferred low emission locations, and accommodating for flexible timeframes to further reduce emissions.

Vaughan highlighted that anyone can use this on a selfhosted server.
Pierre asked if it's possbile to have the validation from GitHub for these projects? Vaughan indicated that it is the intention to have Github involved in validating these projects.

> Action Item - Vaughan to submit links into the Innovation Slack Channel.

b. Project: [Carbon Aware Azure Devops Pipeline](https://docs.google.com/document/d/1jI4vQnJmmhHJdKLvs6kjp-EUoTIKsw6D59-5SPBCkd0/edit#)

- Vaughan Knight
Vaughan started the discussion by reviewing the project submission - Carbon Aware Azure Devops Self Hosted Build Agent a project focused on creating carbon-aware build pipelines in Azure Devops actions.  Specifically, self-hosted build agents can be located anywhere in the world, and many build jobs can occur often with time flexibility.  As such this project will be focusing on triggering these build workloads in preferred low emission locations, and accommodating for flexible timeframes to further reduce emissions. This project will also have a focus on telemetry and reporting.  One of the biggest drivers of change is understanding, and the build agent will also track emissions information.  In addition, builds can compete with warnings if emissions levels are beyond a desired threshold, and similarly builds can be designed to fail based on emissions thresholds.

c. Project: [Karbonetes](https://docs.google.com/document/d/1ZH3yRPAX7h88WNTCgKIuv21i69Q3XhGIHqAgzFdRKgc/edit#heading=h.vf8eis1osru9)

- Vaughan Knight
Vaughan started the discussion by reviewing the project submission. Karbonetes is a project focused on the carbon-aware orchestration of kubernetes workloads to drive.  This is not specifically relating to the kubernetes source itself, but also concepts such as carbon aware orchestration architectural patterns, kubernetes operators, and intelligent routing to route workloads to locations with lower carbon emissions. A large portion of the world’s high scale/intensive workloads can run at different times and/or can run anywhere in the world.  This software is often triggered by orchestrators.   Many of these orchestrated workloads can be converted to carbon aware workloads through putting the carbon aware intelligence into the orchestrator, with the underlying software requiring minimal or no change.  As such, putting this intelligence into an orchestrator such as Kubernetes can have a significant impact on carbon emissions for modern software practices without having to change modifying a workload's underlying code base.


d. Project: [Carbon Aware Cron](https://docs.google.com/document/d/1UWGHIWYk8BYGtUAHXlLf-_ZphLai4kmBieyC9Imd8Po/edit#heading=h.vf8eis1osru9)

- Vaughan Knight
Vaughan started the discussion by reviewing the project submission. The Carbon Aware Cron project is a set of patterns, practices, and scripts providing the ability to reduce the emissions from scheduled jobs, specifically targeting cron.  It also is designed to reduce the software carbon index related to scheduled jobs, Capabilities would include shifting the time a job runs within a window to reduce carbon emissions, or stopping a job running completely based on thresholds.

Will indicated there is some overlap with his proposed project and requested to colaborate, which Vaughan agreed to do.

## Review - [Awesome Green Software](https://github.com/Green-Software-Foundation/awesome-green-software) (DEFERRED)

## WG Meeting Schedule
Pierre Lagarde next 2 schedules
- 15 September @ 1700 BST
- 29 September @ 1700 BST [preview agenda](20210922_Agenda.md)

> WG agreed to add the 2 new meeting schedules
> Action Item - Sean to update the WG calendar to include these meetings

## Dictionary Document (DEFFERED)
Sean Mcilroy
- Review Dictionary Document 

## Any Other Business
Dan requested for the WG to confirm the Innovation repo should be public.
> WG Agreed to make the Innovation repo public
> Action - Sean to make the Innovation repo public

## Adjournment
Will motions to adjorun. No objections. Meeting closed @ 1804
