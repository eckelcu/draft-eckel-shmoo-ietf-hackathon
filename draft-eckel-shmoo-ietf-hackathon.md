---
title: "Running an IETF Hackathon"
abbrev: "ietf-hackathon"
docname: draft-eckel-shmoo-ietf-hackathon-02
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

IETF Hackathons encourage the IETF community to collaborate on running code related to existing and evolving Internet standards. This document provides a set of practices for running IETF Hackathons.

--- middle

# Introduction

IETF Hackathons encourage the IETF community to collaborate on running code related to existing and evolving Internet standards. IETF Hackathons aim to:

* Advance the pace and relevance of IETF standards activities by bringing the speed and collaborative spirit of open source development into the IETF
* Bring developers and young people into IETF and get them exposed to and interested in the IETF

IETF Hackathons are free to attend and open to everyone. Software developers are the primary audience, but participation by subject matter experts who are not necessary developers is encouraged and very important as well. Similarly, while the Hackathon is meant to attract newcomers and those who do not typically view themselves as standards people, long time IETF contributors, including Internet-Draft authors, working group chairs, and subject matter experts, are key participants as well. Group dynamics and blending of skillsets and perspectives are extremely valuable aspects of IETF Hackathons. 

In addition to the running code created and improved as a result of each Hackathon, the exchange or ideas, extensions of human networks, and establishment of trust, respect, and friendships are some of the most valuable outputs of each Hackathon. Code written in a programming language can be more illustrative and less confrontational than opinions expressed during a meeting or in an email. Working together to find common understanding of proposals, concerns, and solutions that result in improvements to evolving Internet standards is as important as the development of running code that implements or validates the correctness of these same proposals. 

Consequently, IETF Hackathons are collaborative events, not competitions. Any competitiveness among participants is friendly and in the spirit of advancing the pace and relevance of new and evolving Internet standards.  

This document provides a set of practices for running IETF Hackathons.

# Conventions and Definitions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 {{RFC2119}} {{!RFC8174}}
when, and only when, they appear in all capitals, as shown here.


# Funding

The Hackathon requires funding, and that funding increases with the number of participants. Participating has always been free; therefore, funding from other sources than participant fees is required.

## Sponsorship

The initial funding model was to have Hackathon sponsors that sign up to sponsor and fund the Hackathon for one year. As part of starting the Hackathon, Cisco volunteered to sponsor and fund the Hackathon for its first year (i.e., three Hackathons, one at each IETF meeting during a calendar year). This sponsorship was to rotate. Huawei volunteered to sponsor the second year of the Hackathon. After the second year, a sponsor for the 3rd year was not found. However, the Hackathon had become a proven success. Consequently, the IETF decided to fund the Hackathon as part of the IETF meeting, with Hackathon sponsorship being on a best effort basis. 

## Expenses

The primary costs associated with the Hackathon are for the meeting space and for food and beverage. It is often challenging to separate out the cost of the Hackathon. 

### Space

The space for the Hackathon is sometimes included as part of the overall contract. Other times, additional costs are incurred to secure a large enough space earlier than would otherwise have been required. Typically, the space is needed from Friday afternoon for setup until Sunday afternoon. The space is typically repurposed for the IETF Lounge. If the size of the Hackathon continue to increase, it might be necessary to use the same space as is used for the IETF plenary.

### Food and Beverage 

Some portion of the food and beverage cost is often included as part of a minimum spend the IETF is obligated to make. When a Hackathon sponsor is identified, the money is typically used to offset food and beverage costs, or to enhance the food and beverage that is made available versus what would have been made available if no sponsor existed. 

The minimum food and beverage for the Hackathon has been,

* coffee, tea, and water Saturday and Sunday morning
* lunch Saturday and Sunday

Additional items, in order of importance, included when funding is available include,

* beer Saturday evening
* dinner Saturday evening
* continental breakfast Saturday and Sunday
* afternoon snacks Saturday and Sunday

### T-shirts

Hackathon t-shirts are an important part of the Hackathon. They have been provided for all in-person Hackathons and greatly appreciated by most participants. The also serve as great advertising for the IETF, the Hackathon, and sponsors. Cisco or other event sponsors have typically covered the cost of t-shirts. The current model is that the secretariat covers the costs using whatever funding is available.

TBD: include size and cost info?

### Stickers

Laptop stickers are popular with software developers. Stickers have been produced made available at the Hackathon for those that want them. The cost of producing these and making them available has been covered by the IETF LLC, Director of Communications and Operations.

### Online only

When the IETF meeting has been online only, all costs in this section are eliminated. Some potential costs associated with running the Hackathon online an entire week before the rest of the IETF meeting include the following:

* Meetecho: costs associated with Hackathon kickoff and closing sessions on Monday and Friday.
* Gather: costs associated with premium service, required to enable more than 50 concurrent users. This has not been necessary, but will almost certainly be if Gather becomes a valuable way for Hackathon participants to meet within and across teams.
* Webex: IETF Webex accounts are made available to champions for the duration of the Hackathon and some period beyond that encompasses at least the rest of the IETF meeting. These accounts are at present available at no additional cost to the IETF.
* Network: the IETF network, and remote access to it, need to be available an additional week.

Online only Hackathons, and increased remote participating in general, result in increased cloud infrastructure requirements that make Hackathon sponsorship more attractive to cloud infrastructure providers. 

# Timing

The first IETF Hackathon was held the weekend before the start of the IETF 92 meeting. The rationale was to avoid conflicts yet make it relatively convenient for those attending the IETF meeting to participate in the Hackathon as well. Holding the Hackathon on the weekend was also viewed as making it more accessible to non IETF meeting attendees, including students and working professionals who would have other commitments during the week. The weekend before was viewed as better than the weekend after so that things learned during the Hackathon could be shared and discussed with the rest of the IETF community during working group sessions and the like. This worked well at IETF 92, was repeated at IETF 93, and quickly became an established norm with the IETF meeting being officially extended to include the Hackathon at the start. An additional benefit of this timing noted and appreciated by participants is that it serves as a more informal and social way to physically and mentally acclimate to changes in time zones, surroundings, and subject matter.  

## Agenda 

The IETF Hackathon is a strenuous event. Though not a competition, participants want to make the most of their time together, much as with the IETF meeting in general. Competitive Hackathons typically run non-stop for on the order of 40 hours. There is a strict deadline and teams are judged and winners declared at the end. Afterward everyone is wiped out and heads off to briefly celebrate or commiserate, but mainly to recuperate. As the IETF Hackathon serves as the start of the overall IETF meeting, we aim to strike a compromise that provides enjoy time to get valuable work accomplished without exhausting themselves before the main IETF meeting even starts. While some people participate in the Hackathon only, the majority of people remain and plan to be actively engaged in the rest of the IETF meeting.

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

Lunch and dinner are provided as a convenience and an incentive to remain at the Hackathon. Participants are free to come and go as they like. It is well understood and accepted that there are other things vying for time and that meeting with friends or colleagues outside of the Hackathon is an entirely reasonable thing to do.

The room closes Saturday evening to give hotel staff unfettered access to the room and to encourage people to pace and take care of themselves. There are no rules against continuing work on Hackathon projects outside of the Hackathon room. Similarly, working on projects long before and after the Hackathon is allowed and encouraged. 

The end of the Hackathon on Sunday is driven by other IETF meeting events. There typically are Newcomer events that start at 16:00. The IETF Hackathon typically includes many newcomers in its list of participants. It is important to provide them time to participate in the Newcomer events. The opening reception typically start at 17:00, and we want to make it easy for all Hackathon participants to join that as well.

Hackdemo Happy Hour (ref) and the Code Lounge (ref) exist to facilitate ongoing discussion and work on projects beyond the official end of the Hackathon weekend.

## Hackdemo Happy Hour

Hackdemo Happy Hour provides an opportunity for more in depth sharing and discussion than is possible within the time constraints of the result presentation that occur at the end of the Hackathon. This opportunity is made available to all teams. As with the results presentation, participation is optional. 

Initially, we did something similar as part of Bits and Bites. This worked well for the Hackathon but the Bits and Bites event was eventually abandoned for other reasons. Hackdemo Happy Hour was created as a low cost, informal event to provide a venue for the IETF community to engage with the Hackathon teams in more in depth discussions related to their projects. 

Hackdemo Happy Hour is typically Monday evening, roughly from 18:00 - 19:30, often overlapping a bit with the last working group session of the day but continuing long enough to allow everyone an opportunity to join. The goal is to make it convenient to attend by not conflicting with other meetings but also no running too late into the night. 

Light snacks and non alcoholic beverages are provided, and a cash bar is available to align with the spirit of a happy hour.

## Code Lounge

The Code Lounge provides space for groups to gather and continue to collaborate on running code after the Hackathon. It is typically in the IETF Lounge and open the same hours as the IETF Lounge. Champions are encouraged to look at the final agenda and determine time slots best suited to ensure successful attendance of Code Lounge sessions as well as any traditional working group sessions. It is okay for multiple teams to sign up for the same time slots. This is in fact encouraged for work that spans multiple working groups or projects.

## Code Sprint 

Some efforts were made to have the Hackathon and the Code Sprint work together or potentially be combined into a single event focusing on the development of IETF protocols and IETF internal tools. There is some concern that the events currently compete for resources. There is also a great deal of synergistic potential. Several Hackathon projects, such as those related to YANG model validation, involve the creation or modification of IETF tools.

The Code Sprint existed long before the Hackathon and has its own identity and way of doing things. The Code Sprint organizers are against combining the events and potentially losing this identity the benefits of a customized event. The practice that exists today is to locate the events physically close to each other to facilitate switching back and forth between the two events. 

## Online Only

The IETF 107 Hackathon was originally scheduled to be the weekend at the start of the IETF meeting in Vancouver. When COVID-19 hit and it became clear the IETF meeting could not occur in person, the Hackathon already had 23 projects and 176 registrations. With only 10 days until the anticipated start of the Hackathon, a survey went out to the Hackathon community, including all project champions and registered participants, to see if they wanted to participate in the Hackathon exactly as planned except with everyone participating remotely rather than in person. A relatively small number of people expressed interest in participating, with even fewer wanting to continue to champion their projects. The fact that the Hackathon was planned for the weekend before the IETF meeting and in the local time zone, both of which were historically very convenient and attractive to Hackathon participants, suddenly became huge obstacles. Consequently, the IETF 107 Hackathon was cancelled.

We knew more in advance that IETF 108 would be an online only meeting. We moved and expanded the schedule to run the entire work week before the rest of the IETF meeting. The Hackathon kickoff was set for Monday, the closing for Friday, with all the time in between left for individual project teams to arrange to meet how and when was most convenient for them. The kickoff and closing sessions were schedule to align with the time frame established for the IETF 108 meeting. All of this was, of course, not ideal, and it worked much better for some people than for others, but at least everyone knew the plan and corresponding time commitment well in advance and had the ability to plan accordingly.

The response was great. We ultimately had 19 projects and almost 300 registrations. It is hard to say how many people actually participated and for how long, but many projects were able to get substantial work done. For the closing, 10 teams produced and shared presentations summarizing their findings and achievements. All presentations as well as the agenda and a recording of the closing session are available via the IETF 108 Hackathon [wiki](https://trac.ietf.org/trac/ietf/meeting/wiki/108hackathon).

Hackdemo Happy Hour and the Code Lounge are not applicable for online only Hackathons. 

# Project Presentations

Project presentations are an important mechanism for capturing what each team accomplished and sharing this with the IETF community.

For the first few Hackathons, we had two very distinct types of presentations,

1. Presentation that served as project pitches at the start of the Hackathon
2. Presentations that summarizes results at the end of the Hackathon. 

## Project Pitches

The project pitches were 5-10 minute presentations by a champion of a project describing what they wanted to do and how they proposed to accomplish it. This gave everyone in the room a better understanding of all the projects and helped participants match themselves with appropriate projects. This was fantastic when we had a small number of projects, but it became unwieldy as the number of projects increased. As knowledge of the Hackathon grew and advanced planning became more common, many participants knew exactly which team they planned to join and wanted to get to work as quickly as possible rather than spend a couple hours listening to presentations. Project pitches were dropped from the Hackathon. Champions are encouraged to share this type of information in advance via the Meeting Wiki instead.

## Results Summaries

The project presentations are brief summaries by each team of what problem they tried to solve, what they achieved, and highlights that include lessons learned, feedback to associated working groups, and collaboration with open source communities and other standards organizations. We also highlight individuals who are participating in their first IETF Hackathon or first IETF event to facilitate their introduction into the IETF community. The production and presentation of results summaries is optional. Fortunately, despite the lack of awards and prizes, most teams participate. 

As with the project pitches, results presentations can become unwieldy as the number of projects increases. The formula used is to limit the total time for all presentations to 2 hours and allocate time slots based on that. Time slots of 3-5 minutes are typical.

All presentation are uploaded to a GitHub repo created specifically for each IETF Hackathon (e.g., [https://github.com/ietf-hackathon/ietf108-project-presentations](https://github.com/ietf-hackathon/ietf108-project-presentations)). The contents of this repo are used as the source for all project presentations at the end of the Hackathon and remain as a reference after the Hackathon. 

A project results presentation template in PPTX format provides guidance on what to cover and is available for those that want to use it. For portability, presentations are requested to be uploaded in PDF format. PDF is not ideal for uploading to GitHub and version control. HTML and Markdown are alternative formats worth considering. TODO - Provide a template in Markdown as well. TODO - Investigate GitHub's [template mode](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/).

One must be a member of the IETF-Hackathon GitHub org to upload a new presentation or update/replace an existing presentation.

To be added as a member, presenters are asked to

* include the name by which they are known in their GitHub profile
* enable two factor authentication (2FA)
* send your GitHub user name to the Chair(s)

Presenters are asked to do this at their earliest convenience as the Chair(s) typically get very busy as the start of presentations approaches.

### Presenting in person

Presentations are run from a shared ChromeBook at the front of the Hackathon room. This Chromebook is provided by the Secretariat.

### Presenting Remotely 

Remote presenters are welcome to run their own presentations using the screen sharing functionality in Meetecho. Alternatively, the Hackathon chairs can share the presentation and advance slides for the presenter.

# Tooling

The IETF Hackathon makes use of the same tooling used by the IETF community for its work and meetings.

## Datatracker

The [datatracker](https://datatracker.ietf.org/) supports the notion of Teams that are not a part of the standards development process. The Hackathon exists as one such Team. From the datatracker menu, navigate to "Other" -> "Active Teams" -> "Hackathon". Here exists a datatracker space for the Hackathon similar to what is available for working groups, including meeting materials, agendas, etc. Initially, there was some attempt to copy materials hosted in [GitHub](https://github.com/ietf-hackathon) to the datatracker. Now this is done only when required for integration with other IETF tooling, including:

* requesting [sessions](https://datatracker.ietf.org/secr/sreq/) for the Hackathon kickoff and closing, and for Hackdemo Happy Hour
* posting [agendas](https://datatracker.ietf.org/meeting/agenda/)

## IETF Website

### Hackathon Webpage

The IETF website includes a dedicated page for the Hackathon [webpage](https://www.ietf.org/how/runningcode/hackathons/). This page contains information about the Hackathon in general as well as links to past, present, and future Hackathons. The relevant links are updated after each IETF meeting. Other content on the page is updated on a more ad hoc basis. 

### Meeting Webpage

Each IETF meeting [webpage](https://www.ietf.org/how/meetings/) contains information about the corresponding Hackathon, including the dates of the Hackathon in the header, a link to the Hackathon webpage in the "Additional Events" section.


## Registration

Registration for the Hackathon is through the IETF [meeting registration](https://registration.ietf.org) system. Participant registration for the Hackathon is 

* independent of participation registration for the meeting
* free
* required

As with meeting registration, registrants for the Hackathon acknowledge the [Note Well](https://ietf.org/about/note-well/) during the registration process. 

### Attendees List

An active list of all registered attendees (e.g., [https://registration.ietf.org/109/participants/hackathon/](https://registration.ietf.org/109/participants/hackathon/)) is maintained by the Secretariat. Important information displayed for each registrants include the set of projects and technologies in which each participant is interested and an email address. This information is optional at the time of registration and may be updated or removed by editing ones registration.


### Caps on Registrations

Registrations were capped for the first several Hackathons. This was done both for space and costs considerations. The cap was hit multiple times, each time resulting in temporary confusion and frustration among would be registrants, followed by the cap being increased. Currently, there are no caps enforced by the registration system.

## Wiki

The meeting wiki serves as the primary source of information for each Hackathon. 

### Hackathon

A page within the wiki (e.g., [https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon](https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon)) is created by the Secretariat for each Hackathon and initialized with information that is based largely on the information from the previous Hackathon. Once created, the Hackathon Chairs update and moderate the wiki. Champions are requested and responsible for adding information about projects for which they are a champion. 

Anyone can edit the wiki by logging in using their datatracker login credentials. Credentials can be obtained by [requesting](https://datatracker.ietf.org/accounts/create/) a new datatracker account.

### Lost and Found

A Lost and Found wiki page (e.g., [https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon/lost&found](https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon/lost&found)) is created by the Chairs for each Hackathon. Participants looking for a team are encouraged to add themselves to the "Skills to Offer" table, providing some information about their skills and interests. This will help others with matching needs and/or interests find them. Champions wanting help on their projects are encouraged to add their teams to the "Skills Needed" table, providing some information about the skills they seek.

### Results Presentation Schedule

A Results Presentation Schedule wiki page (e.g., [https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon/resultspresentationschedule](https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon/resultspresentationschedule)) is created by the Chairs for each Hackathon. Hackathon teams are welcome and encouraged to present their results during the Hackathon Closing. Hackathon teams add the name of their project and the name of the presenter to the table at the bottom of this page.


### In Person Only

The following wiki pages are applicable for in-person Hackathons only.

#### Hackdemo Happy Hour

A Hackdemo Happy Hour wiki page (e.g., [https://trac.ietf.org/trac/ietf/meeting/wiki/106hackdemo](https://trac.ietf.org/trac/ietf/meeting/wiki/106hackdemo)) is created by the Chairs for each Hackathon. Champions are welcome and encouraged to add their project by entering the project name/acronym and a contact name and email address in the table displayed on the page.

#### Code Lounge

A Code Lounge wiki page (e.g., [https://trac.ietf.org/trac/ietf/meeting/wiki/106codelounge](https://trac.ietf.org/trac/ietf/meeting/wiki/106codelounge)) is created by the Chairs for each Hackathon. Champions are welcome and encouraged to add their project by entering the project name/acronym and a contact name and email address in the table displayed on the page.

### Online Only

The following wiki pages are applicable for online only Hackathons only.

#### Team Schedule

A Team Schedule wiki page (e.g., [https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon/teamschedule](https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon/teamschedule)) is created by the Chairs for each online only Hackathon. Online only Hackathons take place globally for an entire week. It is up to individual project teams to determine the preferred dates, times, and ways to meet to work on their project within the context of that week (e.g., Zoom, Webex, Slack). This page is meant to help facilitate coordination of schedules within and across teams.

## Mailing List

The Hackathon mail list, [hacakthon@ietf.org](https://www.ietf.org/mailman/listinfo/Hackathon), is used for all email communication and announcement related to the Hackathon. All registrants and given the option to subscribe to the list. Anyone interested in staying up to date on the Hackathon is able to subscribe at any time.

## GitHub

The [IETF-Hackathon](https://github.com/ietf-hackathon) is used to share code, presentations, and other artifacts at IETF Hackathons. The Hackathon Chairs are responsible for administering the GitHub org. 

Code for Hackathon projects often exist elsewhere, which is perfectly fine. Anyone needing a place to host code for the Hackathon can request the creating of a repository for their project.

A repository is created and maintained by the Chairs for each Hackathon (e.g., [https://github.com/ietf-hackathon/ietf109-project-presentations](https://github.com/ietf-hackathon/ietf109-project-presentations)). This repo is for  participants to upload project presentations. The contents of this repo are used as the source for all project presentations at the end of the Hackathon and remain as a reference after the Hackathon.

## Meetecho

[Meetecho](https://www.meetecho.com/) is used for the kickoff and closing sessions of the Hackathon. This provides many capabilities, including the following:

* allows participants to join Hackathon sessions in person or remotely
* validate registration of participants at time of joining Hackathon sessions
* enable remote presentations of project results
* capture recording of Hackathon sessions

## Network

Access to the IETF network is an important aspect of the Hackathon. The IETF network provides unfettered Internet access that is not typical within many residential, corporate, and university environments. For many of IETF participants and projects, access to the Internet and each other via wireless access to the IETF network is sufficient. However, due to the nature of the work done in the IETF, wired access and special networking capabilities are often required. 

The NOC has graciously met the needs of the Hackathon since its inception and continues to add more capabilities over time. Champions are able to request in advance wired access and special networking functionality, including static IPv4 and IPv6 addresses, IPv6 only networking, a closed user group, NAT64, and IPv6PD. All of this, and the IETF network in general, is made available by the start of the Hackathon and in advance for setup to the extent possible.

### Remote Networking 

Online only meetings present not only a personal networking challenge but a computer networking challenge as well. The NOC came to the rescue with remote networking options to join the IETF network while attending the meeting remotely. With a Raspberry Pi 2B, 3B, or 4B, the NOC has a recipe that allow teams to be virtually connected to the IETF network with all the previously mentioned options. Best of all, this same remote networking capability can be used by remote and in-person participants of Hackathons at in-person meetings.

## Online Only 

The following tooling is applicable for online only Hackathons only.

### Webex

Webex accounts are applicable for online only Hackathons only.

Champions can request a [Webex account](https://ietf.webex.com/webappng/sites/ietf/dashboard?siteurl=ietf) they can use to schedule meetings for their team. These are similar to the Webex accounts allocated to working group chairs to be used for virtual interim meetings. An account can be requested by a team champion at any time. Accounts remain active and available throughout the duration of the Hackathon and the associated IETF meeting. A project name may be used in place of "Working Group Name" in the request form.

### Gather

[Gather](https://gather.town/) is applicable for online only Hackathons. A dedicated area of the space is created by the Secretariat. The area includes tables, identified by letters of the alphabet, that teams are free to self assign and use as and when they like. Eight to ten seats around each table facilitate group discussions within the team. A whiteboard or shared notes tablet (via CodiMD) at tables facilitates sharing of information within the team. The tables also facilitate collaboration across teams. One cautionary note, Gather has relative high network bandwidth and CPU requirements, and as such may not be well suited for some Hackathon participants.

# Statistics and Metrics

Metrics have been captured for each Hackathon. Adding these metrics is on the todo list. 

## IETF Survey Results

https://www.ietf.org/media/documents/survey-planning-possible-online-meetings-responses.pdf

(From L-R: Very important, Important, Neutral, Not important, Not at all important, Score (lower score is more important))
- Hackathon 6.73% 20.20% 40.65% 19.70% 12.72% 3.11

## Hackathon Survey results

todo

### Online Only

todo

# Roles and Responsibilities

TODO - Should this info be in its own section or inline within other sections?
It is known to be incomplete and a mix of own section and inline at the moment.

## Hackathon Chair(s)

The role of a Hackathon chair is similar to that of a working group chair. As with working groups, it is typically best to have co-chairs share responsibilities and workload. The Chairs work very closely with the Secretariat on all responsibilities. Key responsibilities include:

* Organize and deliver a Hackathon at each IETF meeting, soliciting help from all other roles to do much of the heavy lifting
* Encourage and provide guidance to champions who volunteer to lead projects
* Maintain the Hackathon wiki (e.g., [https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon](https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon)) and all of its child pages.
* Moderate Hackathon@ietf.org email list
* Request sessions for Hackathon opening and closing at IETF meeting (i.e., [https://datatracker.ietf.org/secr/sreq/](ttps://datatracker.ietf.org/secr/sreq/))
* Emcee the Hackathon, including the opening and closing sessions and announcements in between
* Create and manage the GitHub repo used for each Hackathon (e.g., [https://github.com/ietf-hackathon/ietf108-project-presentations](https://github.com/ietf-hackathon/ietf108-project-presentations))
* Main point of contact for all Hackathon questions and concerns
 
## Secretariat

Key responsibilities include:

* Configure and manage Hackathon registration system
* Maintain Hackathon [web page](https://www.ietf.org/how/runningcode/hackathons/)
* Create and maintain web page for each Hackathon (e.g., [https://www.ietf.org/how/runningcode/hackathons/109-hackathon/](https://www.ietf.org/how/runningcode/hackathons/109-hackathon/))
* Create wiki page for each Hackathon (e.g., [https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon](https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon)). This is initialized and updated at times by the Secretariat, but the Chair(s) are ultimately responsible for maintaining it.
* Handle venue logistics for Hackathon, Hackdemo Happy Hour, and Code Lounge (e.g., reserve room, food and beverages, AV, etc.)
* Internal IETF promotion (e.g., email messages to community)
* Assist with external outreach, as needed, including finding sponsors

## Sponsor

Key responsibilities include:

* Provide some funding to help offset costs of Hackathon (either per meeting or per year, depending on model)
* Optionally provide t-shirts or other giveaways
* Optionally provide support staff to assist with Hackathon

Key benefits include:

* TODO

## Champions of Projects

Champions of projects are the key to a successful Hackathon. Key responsibilities for champions include:

* Volunteer to lead a project at the Hackathon
* Serve as primary contact for the project
* Add and manage information on the Hackathon wiki for the project
* Promote the project to appropriate groups inside IETF and outside as well
* Welcome and organize members of the team
* Provide focus, guidance, and leadership for the project

## IETF LLC, Director of Communications and Operations (was ISOC)

Key responsibilities include:

* External (outside world) promotion
* Outreach to local universities
* Provide photographer
* Laptop stickers 

## Judges

The first several Hackathon involved judges who listened to summary presentations by teams at the closing of each Hackathon and identified winning teams for an arbitrary number of project categories. Prizes were made available to members of winning teams. This was done as an incentive to participate in the Hackathon and present results, and  to provide a fun yet informative end to the Hackathon that could be appreciated by the entire IETF community. Judging and awarding of prizes led to confusion regarding the nature of the Hackathon, making it appear to some overly competitive. Procurement of appropriate prizes was financially and logistically challenging. Arrangement of judges, determination of winners, and awarding of prizes all became more time consuming, especially as the number of projects and participants grew. Ultimately, it was deemed best to eliminate judging, awards, and prizes entirely. Apparently the IETF community has an innate incentive to participate and present results in the Hackathon. 

# Security Considerations

None.

## Private Considerations

Participant email addresses are displayed publicly. Registrants optionally include these are part of their registrations. 

The email addresses of individual champions are often shared publicly by the champions on the wiki.

The email addresses of the Chairs are shared publicly by the Chairs on the wiki and via GitHub. It would probably be better to use an email alias.


# IANA Considerations

This document has no IANA actions.



--- back

# Acknowledgments
{:numbered="false"}

Michael Richardson and Benson Muite provided valuable contributions to this document.
