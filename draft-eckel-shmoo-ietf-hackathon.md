---
title: "Running an IETF Hackathon"
abbrev: "ietf-hackathon"
docname: draft-eckel-shmoo-ietf-hackathon
category: info

ipr: trust200902
area: General
workgroup: shmoo
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: C. Eckel
    name: Charles Eckel
    organization: Cisco Systems
    email: eckelcu@cisco.com

normative:
  RFC2119:

informative:



--- abstract

IETF Hackathons encourage developers to collaborate and develop utilities, ideas, sample code and solutions that show practical implementations of IETF standards. 
This document provides a set of practices for running IETF Hackathons.

--- middle

# Introduction

IETF Hackathons encourage developers to collaborate and develop utilities, ideas, sample code and solutions that show practical implementations of IETF standards. 
IETF Hackathons aim to:

* Advance the pace and relevance of IETF standards activities by bringing the speed and collaborative spirit of open source development into the IETF
* Bring developers and young people into IETF and get them exposed to and interested in IETF

IETF Hackathons are free to attend and open to everyone. They are collaborative events, not competitions. Any competitiveness among participants is friendly, and in the spirit of advancing the pace and relevance of new and evolving internet standards. 

This document provides a set of practices for running IETF Hackathons.

# Conventions and Definitions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 {{RFC2119}} {{!RFC8174}}
when, and only when, they appear in all capitals, as shown here.

# Roles and Responsibilities

## Hackathon Chair(s)

The role of a hackathon chair is similar to that of a working group chair. As with working groups, it is typically best to have co-chairs share responsibilities and workload. Key responsibilities include:

* Organize and deliver a hackathon at each IETF meeting, soliciting help from all other roles to do much of the heavy lifting
* Encourage and provide guidance to champions who volunteer to lead projects
* Maintain the hackathon wiki (e.g. https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon) and all of its child pages.
* Moderate hackathon@ietf.org email list
* Request sessions for hackathon opening and closing at IETF meeting (i.e. https://datatracker.ietf.org/secr/sreq/)
* Emcee the hackathon, including the opening and closing sessions and announcements in between
* Create and manage the GitHub repo used for each Hackathon (e.g. [https://github.com/IETF-Hackathon/ietf108-project-presentations](https://github.com/IETF-Hackathon/ietf108-project-presentations)
* Main point of contact for all Hackathon questions and concerns


## Secretariat

* Configure and manage Hackathon registration system
* Maintain web page for Hackathons https://www.ietf.org/how/runningcode/hackathons/
* Create web page for each Hackathon (e.g. https://www.ietf.org/how/runningcode/hackathons/109-hackathon/)
* Create wiki page for each Hackathon (e.g. https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon). This is initialized and updated at times by the Secretariat, but the Chair(s) are ultimately responsible for maintaining it.
* Handle venue logistics for Hackathon, Hackdemo Happy Hour, and Code Lounge (e.g. reserve room, food and beverages, AV, etc.)
* Internal IETF promotion (e.g. email messages to community)
* Assist with external outreach, as needed, including finding sponsors

## Sponsor

* Provide some funding to help offset costs of Hackathon (either per meeting or per year, depending on model)
* Optionally provide t-shirts or other giveaways
* Optionally provide support staff to assist with Hackathon


## Champions of Projects

Champions of projects are the key to a successful Hackathon. Key responsibilities for champions include:

* Volunteer to lead a project at the Hackathon
* Serve as primary contact for the project
* Add and manage information on the Hackathon wiki for the project
* Promote the project to appropriate groups inside IETF and outside as well
* Welcome and organize members of the team
* Provide focus, guidance, and leadership for the project

## IETF LLC, Director of Communications and Operations (was ISOC)

* External (outside world) promotion
* Outreach to local universities
* Provide photographer
* Laptop stickers 

## Judges

The first several hackathon involved judges who listened to summary presentations by teams at the closing of each hackathon and identified winning teams for an arbitrary number of project categories. Prizes were made available to members of winning teams. This was done as an incentive to participate in the Hackathon and present results, and  to provide a fun yet informative end to the Hackathon that could be appreciated by the entire IETF community. Judging and awarding of prizes led to confusion regarding the nature of the Hackathon, making it appear to some overly competitive. Procurement of appropriate prizes was financially and logistically challenging. Arrangement of judges, determination of winners, and awarding of prizes all became more time consuming, especially as the number of projects and participants grew. Ultimately, it was deemed best to eliminate judging, awards, and prizes entirely. Apparently the IETF community has an innate incentive to participate and present results in the Hackathon. 

# Funding

The Hackathon requires funding, and that funding increases with the number of participants. Participating has always been free; therefore, funding from other sources than participant fees is required.

## Sponsorship

The initial funding model was to have Hackathon sponsors that sign up to sponsor and fund the Hackathon for one year. As part of starting the Hackathon, Cisco volunteered to sponsor and fund the hackathon for its first year (i.e,. three hackathons, one at each IETF meeting during a calendar year). This sponsorship was to rotate. Huawei volunteered to sponsor the second year of the hackathon. After the second year, a sponsor for the 3rd year was not found. However, the hackathon had become a proven success. Consequently, the IETF decided to fund the hackathon as part of the IETF meeting, with hackathon sponsorship being on a best effort basis. 

## Expenses

The primary costs associated with the hackathon are for the meeting space and for food and beverage. It is often challenging to separate out the cost of the hackathon. 

### Space

The space for the hackathon is sometimes included as part of the overall contract. Other times, additional costs are incurred to secure a large enough space earlier than would otherwise have been required. Typically, the space is needed from Friday afternoon for setup until Sunday afternoon. The space is typically repurposed for the IETF Lounge. If the size of the Hackathon continue to increase, it might be necessary to use the same space as is used for the IETF plenary.

### Food and Beverage 

Some portion of the food and beverage cost is often included as part of a minimum spend the IETF is obligated to make. When a Hackathon sponsor is identified, the money is typically used to offset food and beverage costs, or to enhance the food and beverage that is made available versus what would have been made available if no sponsor existed. 

The minimum food and beverage for the hackathon has been,

* coffee, tea, and water Saturday and Sunday morning
* lunch Saturday and Sunday

Additional items, in order of importance, included when funding is available include,

* beer Saturday evening
* dinner Saturday evening
* continental breakfast Saturday and Sunday
* afternoon snacks Saturday and Sunday

### T-shirts

Hackathon t-shirts are an important part of the hackathon. They have been provided for all in-person hackathons and greatly appreciated by most participants. The also serve as great advertising for the IETF, the Hackathon, and sponsors. Cisco or other event sponsors have typically covered the cost of t-shirts. The current model is that the secretariat covers the costs using whatever funding is available.

TBD: include size and cost info?

### Stickers

Laptop stickers are popular with software developers. Stickers have been produced made available at the hackathon for those that want them. The cost of producing these and making them available has been covered by the IETF LLC, Director of Communications and Operations.

### Online meeting consideration

When the IETF meeting has been online only, all costs in this section are eliminated. 


# Timing

The first IETF Hackathon was held the weekend before the start of the IETF 92 meeting. The rationale was to avoid conflicts yet make it relatively convenient for those attending the IETF meeting to participate in the hackathon as well. Holding the hackathon on the weekend was also viewed as making it more accessible to non IETF meeting attendees, including students and working professionals who would have other commitments during the week. The weekend before was viewed as better than the weekend after such that things learned during the hackathon could be shared and discussed with the rest of the IETF community during working group sessions and the like. This worked well at IETF 92, was repeated at IETF 93, and quickly became an established norm with the IETF meeting being officially extended to include the hackathon at the start.

## Agenda 

The IETF Hackathon is a strenuous event. Though not a competition, participants want to make the most of their time together, much as with the IETF meeting in general. Competitive hackathons typically run non-stop for on the order of 40 hours. There is a strict deadline and teams are judged and winners declared at the end. Afterward everyone is wiped out and heads off to briefly celebrate or commiserate, but mainly to recuperate. As the IETF Hackathon serves as the start of the overall IETF meeting, we aim to strike a compromise that provides enjoy time to get valuable work accomplished without exhausting themselves before the main IETF meeting even starts. While some people participate in the hackathon only, the majority of people remain and plan to be actively engaged in the rest of the IETF meeting.

The typical agenda is as follows:

    Saturday before IETF meeting week
        08:30: Room open for setup by project champions
        09:00: Room open for all - Pastries and coffee provided
        09:30: Hackathon kickoff
        09:45: Form Teams
        12:30: Lunch provided
        15:30: Afternoon break - Snacks provided
        19:00: Dinner provided
        22:00: Room closes 

    Sunday before IETF meeting week
        08:30: Room opens - Pastries and coffee provided
        12:30: Lunch provided
        13:30: Hacking stops, prepare brief presentation of project
        14:00: Project presentations to other participants
        15:45: Closing remarks and opportunities for next time
        16:00: Hackathon ends
        17:00: Tear down complete 

The time on Saturday morning provides team champions time to setup and participants time to socialize and learn more about projects and team they might want to join. The kickoff presentation and formalities are kept to minimum to leave as much time as possible for team to work together with their team on their projects. The proximity of teams to each other fosters communication and collaboration across teams as well.

Lunch and dinner are provided as a convenience and an incentive to remain at the hackathon. Participants are free to come and go as they like. It is well understood and accepted that there are other things vying for time and that meeting with friends or colleagues outside of the hackathon is an entirely reasonable thing to do.

The room closes Saturday evening to give hotel staff unfettered access to the room and to encourage people to pace and take care of themselves. There are no rules against continuing work on hackathon projects outside of the hackathon room. Similarly, working on projects long before and after the hackathon is allowed and encouraged. 

The end of the Hackathon on Sunday is driven by other IETF meeting events. There typically are Newcomer events that start at 16:00. The IETF hackathon typically includes many newcomers in its list of participants. It is important to provide them time to participate in the Newcomer events. The opening reception typically start at 17:00, and we want to make it easy for all Hackathon participants to join that as well.

Hackdemo Happy Hour (ref) and the Code Lounge (ref) exist to facilitate ongoing discussion and work on projects beyond the official end of the hackathon weekend.

# Technology

The IETF Hackathon makes use of the same tooling used by the IETF community for its work and meetings. This includes a combination of the [Datatracker](https://datatracker.ietf.org/), [IETF Website](https://www.ietf.org/how/runningcode/), the [Meeting Wiki](https://trac.ietf.org/trac/ietf/meeting/wiki), [GitHub](https://github.com/ietf-hackathon), [Meetecho](https://www.meetecho.com/), [Webex](https://ietf.webex.com/webappng/sites/ietf/dashboard?siteurl=ietf), and [Gather](https://gather.town/).

## Datatracker

The [Datatracker](https://datatracker.ietf.org/) supports the notion of Teams that are not a part of the standards development process. The Hackathon exists as one such Team. From the Datatracker menu, navigate to "Other", "Active Teams", "hackathon". Here exists a Datatracker space for the Hackathon similar to what is available for working groups, including meeting materials, agendas, etc. Initially, there was some attempt to copy materials hosted in [GitHub](https://github.com/ietf-hackathon) to the Datatracker. Now this is done only when required for integration with other IETF tooling. Hackathon meeting requests and agendas are good examples.

## IETF Website

todo

## Meeting Wiki

todo

## GitHub

todo

## Meetecho

todo

## Webex

todo

## Gather

todo

## Network

Access to the IETF network is an important aspect of the Hackathon. The IETF network provides unfettered internet access that is not typical within many residential, corporate, and university environments. For many of IETF participants and projects, access to the internet and each other via the wireless access to the IETF network is sufficient. However, due to the nature of the work done in the IETF, wired access and special networking capabilities are often required. 

The NOC has graciously met the needs of the Hackathon since its inception and continues to add more capabilities over time. Champions are able to request in advance wired access and special networking functionality, including static IPv4 and IPv6 addresses, IPv6 only networking, a closed user group, NAT64, and IPv6PD. All of this, and the IETF network in general, is made available by the start of the Hackathon and in advance for setup to the extent possible.

### Remote Networking 

Online only meetings present not only a personal networking challenge but a computer networking challenge as well. The NOC came to the rescue with remote networking options to join the IETF network while attending the meeting remotely. With a [Raspberry Pi](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/) 2 or newer, or [MikroTik hAP mini](https://mikrotik.com/product/RB931-2nD), the NOC has a recipe that allow teams to be virtually connected to the IETF network with all the previously mentioned options. Best of all, this same remote networking capability can be used by remote and in-person participants of Hackathons at in-person meetings.

# Statistics and Metrics

todo

# Auxiliary Events

## Hackdemo Happy Hour

Hackdemo Happy Hour provides an opportunity for more in depth sharing and discussion than is possible within the time constraints of the result presentation that occur at the end of the hackathon. This opportunity is made available to all teams. As with the results presentation, participation is optional. 

Initially, we did something similar as part of Bits and Bites. This worked well for the hackathon but the Bits and Bites event was eventually abandoned for other reasons. Hackademo Happy Hour was created as a low cost, informal event to provide a venue for the IETF community to engage with the Hackathon teams in more in depth discussions related to their projects. 

Hackdemo Happy Hour is typically Monday evening, roughly from 18:00 - 19:30, often overlapping a bit with the last working group session of the day but continuing long enough to allow everyone an opportunity to join. The goal is to make it convenient to attend by not conflicting with other meetings but also no running too late into the night. 

Light snacks and non alcoholic beverages are provided, and a cash bar is available to align with the spirit of a happy hour.

## Code Lounge

Space for groups to gather and continue to collaborate on running code after the hackathon. It is typically in the IETF Lounge and open the same hours as the IETF Lounge.

## Code Sprint 

Some efforts were made to have the Hackathon and the Code Sprint work together or potentially be combined into a single event focusing on the development of IETF protocols and IETF internal tools. There is some concern that the events currently compete for resources. There is also a great deal of synergistic potential. Several Hackathon projects, such as those related to YANG model validation, involve the creation or modification of IETF tools.

The Code Sprint existed long before the Hackathon and has its own identity and way of doing things. The Code Sprint organizers are against combining the events and potentially losing this identity the benefits of a customized event. The practice that exists today is to locate the events physically close to each other to facilitate switching back and forth between the two events. 

# Online Only

IETF 107 Hackathon was originally scheduled to be the weekend at the start of the IETF meeting in Vancouver. When COVID-19 hit and it became clear the IETF meeting could not occur in person, the hackathon already had 23 projects and 176 registrations. With only 10 days until the anticipated start of the hackathon, a survey went out to the hackathon community, including all project champions and registered participants, to see if they wanted to participate in the hackathon exactly as planned except with everyone participating remotely rather than in person. A relatively small number of people expressed interest in participating, with even fewer wanting to continue to champion their projects. The fact that the hackathon was planned for the weekend before the IETF meeting and in the local time zone, both of which were historically very convenient and attractive to hackathon participants, suddenly became huge obstacles. Consequently, the IETF 107 Hackathon was cancelled.

We knew more advance that IETF 108 would be an online only meeting. We moved and expanded the schedule to run the entire work week before the rest of the IETF meeting. The hackathon kickoff was set for Monday, the closing for Friday, with all the time in between left for individual project teams to arrange to meet how and when was most convenient for them. The kickoff and closing sessions were schedule to align with the time frame established for the IETF 108 meeting. All of this was, of course, not ideal, and it worked much better for some people than for others, but at least everyone knew the plan and corresponding time commitment well in advance and had the ability to plan accordingly.

The response was great. We ultimately had 19 projects and almost 300 registrations. It is hard to say how many people actually participated and for how long, but many projects were able to get substantial work done. For the closing, 10 teams produced and shared presentations summarizing their findings and achievements. All presentations as well as the agenda and a recording of the closing session are available via the IETF 108 Hackathon [wiki]((https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon).

# Project Presentations

Project presentations are an important mechanism for capturing what each team accomplished and sharing this with the IETF community.

For the first few Hackathons, we had two very distinct types of presentations,

1. Presentation that served as project pitches at the start of the Hackathon
2. Presentations that summarizes results at the end of the Hackathon. 

## Project Pitches

The project pitches were 5-10 minute presentations by a champion of a project describing what they wanted to do and how they proposed to accomplish it. This gave everyone in the room a better understanding of all the projects and helped participants match themselves with appropriate projects. This was fantastic when we had a small number of projects, but it became unwieldy as the number of projects increased. As knowledge of the hackathon grew and advanced planning became more common, many participants knew exactly which team they planned to join and wanted to get to work as quickly as possible rather than spend a couple hours listening to presentations. Project pitches were dropped from the Hackathon. Champions are encouraged to share this type of information in advance via the Meeting Wiki instead.

## Results Summaries

The project presentations are brief summaries by each team of what problem they tried to solve, what they achieved, and highlights that include lessons learned, feedback to associated working groups, and collaboration with open source communities and other standards organizations. We also highlight individuals who are participating in their first IETF Hackathon or first IETF event to facilitate their introduction into the IETF community. The production and presentation of results summaries is optional. Fortunately, despite the lack of awards and prizes, most teams participate. 

As with the project pitches, results presentations can become unwieldy as the number of projects increases. The formula used is to limit the total time for all presentations to 2 hours and allocate time slots based on that. Time slots of minutes are typical.

All presentation are uploaded to a GitHub repo created specifically for each IETF Hackathon (e.g., [https://github.com/IETF-Hackathon/ietf108-project-presentations](https://github.com/IETF-Hackathon/ietf108-project-presentations).

The contents of this repo are used as the source for all project presentations at the end of the hackathon and remain as a reference after the hackathon. For portability, presentations are requested to be in PDF format.

One must be a member of the IETF-Hackathon GitHub org to upload a new presentation or update/replace an existing presentation.

To be added as a member, presenters are asked to

* include the name by which they are known in their GitHub profile
* enable two factor authentication (2FA)
* send your GitHub user name to the Chair(s)

Presenters are asked to do this at their earliest convenience as the Chair(s) typically get very busy as the start of presentations approaches.

### Presenting in person

Presentations are run from a shared ChromeBook at the front of the hackathon room. This Chromebook is provided by the Secretariat.

### Presenting Remotely 

Remote presenters are welcome to run their own presentations using the screen sharing functionality in Meetecho. Alternatively, the hackathon chairs can share the presentation and advance slides for the presenter. 

## IETF Survey Results

https://www.ietf.org/media/documents/survey-planning-possible-online-meetings-responses.pdf

(From L-R: Very important, Important, Neutral, Not important, Not at all important, Score (lower score is more important))
- Hackathon 6.73% 20.20% 40.65% 19.70% 12.72% 3.11

# Hackathon Survey results

tbd


# Security Considerations

Participant email addresses.


# IANA Considerations

This document has no IANA actions.



--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledgements.
