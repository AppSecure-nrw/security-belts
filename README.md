# Security Belts

> The maturity model *Security Belts* structures activities of the secure software development and, thus, offers development teams a good opportunity to address the topic and to build up necessary competencies to ensure the software security of their products. Thereby, the maturity model supports development teams that are overwhelmed with the duty to take over much more responsibility without having sufficient competencies in the team.

**Table of Contents**
- [Introduction](#introduction)
- [The Concept](#the-concept)
- [Belt Activities](#belt-activities)
- [Roles](#roles)
  * [Security Champion](#security-champion)
  * [Security Champion Guild](#security-champion-guild)
- [Rituals](#rituals)
  * [Weekly Review](#weekly-review)
  * [Belt Assessment](#belt-assessment)
  * [Yearly Refresh](#yearly-refresh)
- [The Belts and their Activities](#the-belts-and-their-activities)
  * [Prerequisites](#prerequisites)
  * [Belts](#belts)
- [Getting Started](#getting-started)
- [Credits](#credits)

## Introduction

Due to the increasing requirements on the security of software products and new evolving development methodologies, development teams have to take much more responsibility for the software security of their product. However, as recent studies and security incidents indicate, development teams are overwhelmed with this duty. The typical main reasons are that the teams do not have sufficient awareness and knowledge concerning software security.

The maturity model *Security Belts* pursues the idea of providing development teams reasonable activities to improve software security without overwhelming them with the complexity of the topic. The maturity model conveys values that are based on [The Five Ideals Of DevOps](https://itrevolution.com/five-ideals-of-devops/), which we believe are essential to successfully deliver secure software products. In the maturity model, the individual degrees of maturity are represented as belts, which are known from various martial arts such as judo.

By applying the maturity model, the development teams continuously improve themselves and build up the necessary knowledge for the topic by earning the belts. Furthermore, they are requested to deal with software security early on and continuously in the software development process and, thereby, they minimize the risk of insecure releases and security incidents during operation. As a consequence, Security Belts build confidence on the subject of software security towards customers, management, product owners, and the team itself.

On an organizational level, it is crucial that software security is not the task of a centralized team or department but that each development teams is responsible for the software security of its products. In addition, the organization must be aware of the software security requirements for each of its products and the skills needed to meet those requirements. Based on these requirements, the organization can deduce for each product (e.g., via a risk analysis), which belt the development team must at least have. As a consequence, not every team has to achieve the highest belt.

## The Concept

A belt comprises several activities from different areas, whereby each activity contributes to the improvement of software security. Within the maturity model, the belts are tailored so that they can be achieved within a quarter of year.

The white belt - with its activities - is our starting point and shall lay the organizational basis for the improvement of your software security. All other belts (yellow, orange, etc.) directly improve the team and its product. The activities with the best benefit to cost ratio are assigned to early belts (yellow, etc.). Therefore, activities in later security belts have a reduced benefit to cost ratio. Nevertheless, they are still worthwile if the product has critical software security requirements.

At the moment benefit and cost values are based on expert judgment. In the future, we seek to measure these
values, so that the maturity model gets more accurate and profound. Furthermore, each belt follows the
following rules, which we consider useful.
1. Each Security Belt improves transparency to help the team to better understand and communicate to their stakeholders how well it ensures software security.
2. Each Security Belt supports the team to automate and standardize their new security tasks by introducing at least one new tool.

## Belt Activities

The belt activities serve as a checklist for the team and give additional information to accomplish these activities. In particular, they consist of:
- a brief task description for the team,
- a list of further readings to learn more about this topic,
- references to related activities (if necessary),
- the benefits of this activity, and
- a checklist for the assessment of the belt.

## Roles

Security Belts depend on the existence of several roles from the Agile methodology such as developer and product owner. Developers, product owner, and optionally a scrum master, form the so-called *team*.

### Security Champion

The maturity model Security Belts adds the role of the Security Champion to the Agile methodology. The Security Champion ...
  - is a developer, who is also part of the team.
  - has profound security knowledge but is not necessarily a security expert.
  - empowers the team such that they can ensure the security of their software products by themselves.
  - enables the team to improve themselves concerning software security and raises the importance of security within the team (developers and product owner) as well as towards the management.

Security Champions must attend a thorough training. They need an overview of the complete security development lifecycle (SDLC), theoretical background,
practical knowledge, and the necessary soft skills to fulfill its role. Examplary trainings are:
- [Fraunhofer IEM - Security Champion Training](https://www.iem.fraunhofer.de/de/academy/schulungsangebot/security-champion-training.html)
- *suggestions welcome*

### Security Champion Guild

The Security Champion Guild is a guild as known from the [Spotify model](https://www.atlassian.com/agile/agile-at-scale/spotify). Security Champions participate to get feedback on security-related topics from outside their teams such as individual questions, second opinions, and code/concept reviews.

The main task of the guild is to spread the Security Belts in the organization. The guild conducts belt assessments and actively improves the maturity model.

All Security Champions and only these are part of the guild. Otherwise, the champions would not learn from each other and the quality of the guild's outcome is at risk as Security Champions have a dedicated training, which other developers have not. If a central security department exists within the company, then the guild and this department need to collaborate.

## Rituals

The Security Belts define the following list of rituals that shall be held such that the goals of our model can be accomplished.

### Weekly Review

The Security Champion Guild organizes a review every week with one representative of each team working on achieving a Security Belt. If the team does not have a Security Champion yet, then the representative does not have to be a Security Champion.

The weekly is set up like a daily standup in Scrum. Everyone presents the progress of their implementation of the Security Belt activity they are currently working on.

This meeting allows teams to get early feedback and to give the Security Champion Guild transparency about the progress the teams are making with their Security Belts.

### Belt Assessment

There is an assessment for each security belt to ensure that the team has performed the required activities and, thus, has matured concerning software security.

The team has to request the assessment through the guild. Since the Security Belts are intended to empower a team and not only the Security Champion, the whole team has to attend the assessment. The guild organizes the assessors. There should be at least two Security Champions that already achieved the Security Belt that the assessment is about. If there are not enough suitable assessors, the whole guild and additional security experts of the organization attend the assessment and function as assessors.

The assessment consists of all the assessment points described in the belt activities of the respective Security Belt. The team has to present its implementation for each belt activity in the Security Belt they want to achieve. The assessors should also select some activities of previous belts - the team has already achieved - to check if the team is still applying what it has learned.

If the assessment is passed, the belt is awarded to the team by the assessors. Do not forget to celebrate with the team and the guild.
<!-- Optionally, the guild can buy real judo belts and hand them over to the teams. -->

### Yearly Refresh

Over time, teams are changing: members join and leave and the priority of the teams' work, as well as the security requirements of their product, may vary. Consequently, the guild should regularly check whether the team is still actively applying the activities of a Security Belt.

The Security Champion Guild performs a refresh meeting every year for each team that achieved a Security Belt. At least two members of a team are invited together with two Security Champions (the assessors), which also achieved the belt under assessment. If there are no suitable candidates, proceed in the same manner as during the belt assessment.

In the refresh meeting, all belt activities - from all achieved Security Belts - are tested whether the team is still applying it.
- If all activities are still performed, celebrate this with the team and the guild.
- If some activities are not performed anymore, the team has to revive the activity and assess it again.
- If most of the activities are not performed anymore, the team loses the corresponding Security Belts. It has to execute all failed belt activities again, in order to reassess the lost Security Belts.

## The Belts and their Activities

### Prerequisites
Before any team can achieve a specific belt, the Security Champion Guild needs to lay the prerequisites for the teams accordingly.

- [Prerequisites](prerequisites/README.md)


### Belts
Working on the belts is a continuous effort. Start with the first belt, the white one, and keep working on them, until you achieve the desired belt for your team. Activities of later belts often relate to activities introduced in previous belts. In this case, the previous relevant belt activities will be highlighted for the belt activity.

- [1 - White Belt](white/README.md)
- [2 - Yellow Belt](yellow/README.md)
- [3 - Orange Belt](orange/README.md)
- [4 - Green Belt [work in progress]](green/README.md)
- [5 - Purple Belt [work in progress]](purple/README.md)

## A Getting Started for Developers 

- Become familiar with our security belts concepts such that you can explain them to your colleagues using our slides.
- Identify colleagues (developers, product owners, managers) in your company that already want to improve the secure software development. They can discuss with you how to implement security belts in your company.
- Convince your product owner to spend some time to roughly assess the current security of your product (e.g., collecting all security-related incidents and bugs).
- Persuade your PO and team to start working on the belts by showing the results of your assessment.
- Let your PO be proud: He/She shall report to the top-management that you improve your software security.

## Credits

The Security Belts are based on the [OWASP DevSecOps Maturity Model](https://owasp.org/www-project-devsecops-maturity-model/) and partially inspired by [OWASP SAMM](https://owasp.org/www-project-samm/)

This work is part of the research project "AppSecure.nrw - Security-by-Design of Java-based Applications". The project is funded by the European Regional Development Fund (ERDF-0801379). 
<br/>
  <br/><img src="https://github.com/AppSecure-nrw/funding-notice/blob/main/Logo_48_lang_Zeichenfl%C3%A4che%201.png" alt="AppSecure.nrw Logo" height="50"/>
  
<img src="https://github.com/AppSecure-nrw/funding-notice/blob/main/EFRE_Foerderhinweis_englisch_farbig.jpg" alt="EFRE Logo" height="50"/> <img src="https://github.com/AppSecure-nrw/funding-notice/blob/main/Ziel2NRW_RGB_1809_jpg.jpg" alt="Ziel2NRW Logo" height="50"/>
