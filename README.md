# Security Belts

> The maturity model *Security Belts* structures activities of the secure software development and, thus, offers development teams a good opportunity to address the topic and to build up necessary competencies to ensure the software security of their products. Thereby, the maturity model supports development teams that are overwhelmed with the duty to take over much more responsibility without having sufficient competencies in the team.

## Introduction

Due to the increasing requirements on the security of software products and new evolving development methodologies, development teams have to take much more responsibility for the software security of their product. However, as recent studies and security incidents indicate, development teams are overwhelmed with this duty, since they are not aware of the topic and do not have sufficient competencies.

The maturity model *Security Belts* pursues the idea of providing development teams reasonable activities to improve software security without overwhelming them with the complexity of the topic. The maturity model conveys values that are based on [The Five Ideals Of DevOps](https://itrevolution.com/five-ideals-of-devops/), which we believe are essential to successfully deliver secure software. In the maturity model, the individual degrees of maturity are represented as belts, which are known from various martial arts such as judo.

By applying the maturity model, the development teams continuously improve themselves and build up the necessary knowledge for the topic. Furthermore, they are requested to deal with software security early on and continuously in the software development process and, thereby, they minimize the risk of insecure releases and security incidents during operation.

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

The belt activities serve as a checklist for the team and give additional information to accomplish these activitites. In particular, they consist of:
- a brief task description the team,
- a list of further readings to learn more about this topic,
- references to related activities (if necessarry),
- the benefits of this activity, and
- a checklist for the asssessment of the belt.

## Roles

### Security Champion

The Security Belts model depends on the existence of several roles from the Agile methodology such as Developer, Product Owner (PO), and Scrum Master who together form the so called *team*. Security Belts adds the role of the Security Champion.

The Security Champion is a developer with profound security knowledge that consults the team and explains the importance and complexity of security. Security Champions do need dedicated time to implement belt activities within their teams.

Security Champions must attend qualified training such as:
- [Fraunhofer IEM - Security Champion Training](https://www.iem.fraunhofer.de/de/academy/schulungsangebot/security-champion-training.html)
- TODO

The role of the Security Champion is important in order that the team is able to take over responsibility for software security for their product and to improve themselves.

### Security Champion Guild

The Security Champion Guild is a guild as known from the [Spotify model](https://www.atlassian.com/agile/agile-at-scale/spotify). Security Champions can participate to get feedback on security related topics from outside their teams such as individual questions, second opinions, and code/concept reviews.

The main task of the guild is to spread the Security Belts model in the organization. The guild conducts belt exams and actively improves the model.

All Security Champions and only these are part of the guild otherwise champions are not learning from each other as well as the quality of outcome is reduced.

## Rituals

### Weekly Review

The Security Champion Guild organizes a review on a weekly basis with one representative of each team working on achieving a Security Belt. The representative does not have to be a Security Champion.

The weekly is set up like a daily standup in Scrum, where everyone presents the progress of their implementation of the Security Belt activity their currently working on.

This meeting gives teams the opportunity to get early feedback and to give the Security Champion Guild transparency about the progress the teams are making with their Security Belts.

### Belt Exam

The team has to pass a belt exam in order to obtain a Security Belt. Since the Security Belts are intended to empower a team, the whole team - not only the Security Champion - has to attend to the exam.

The belt exam can be requested by the Security Champion Guild. The guild then organizes some examiners. These should be Security Champions which already achieved the Security Belt that the exam is about. If there are not enough suitable examiners a collective of the whole guild together with other security experts of the organization attend the exam and function as examiners.

The exam consists of all the assessment points described in the belt activities of the respective Security Belt. The team has to present its implementation for each belt activity in the Security Belt they want to achieve. The examiners should also select some activities of previous belts - the team has already achieved - to check if the team is still applying what it has learned.

If the exam is passed, the belt is awarded to the team by the examiners. Do not forget to celebrate with the team and the guild.

### Yearly Refresh

Responsibility for security within a team requires self-improvement and trust, which both can be earned with the Security Belts. But over time teams are changing. Members are exchanged and the priority of the work varies. To continue to trust a team, it makes sense to regularly check whether the team is still actively applying the activities of a Security Belt.

The Security Champion Guild performs a refresh meeting on a yearly basis for each team which achieved a Security Belt. At least two members of a team are invited together with two Security Champions which also achieved the belt to be tested. If there are no suitable candidates, proceed like with the examiners for the belt exam.

In the refresh meeting, all belt activities - from all by the team achieved Security Belts - are tested wether the team is still applying it.
- If all activities are still performed, celebrate this with the team and the guild.
- If some activities are no more performed, the team has to revive the activity and prove it.
- If most of the activities are not performed anymore, the team looses the corresponding Security Belts and must take and pass the exam again.

## The Belts and their Activities

### Prerequisites
Before any team can achieve a specific belt, the Security Champion Guild needs to lay the prerequisites for the teams accordingly.

- [Prerequisites](prerequisites/README.md)


### Belts
Working on the belts is a continuous effort. Start with the first belt, the white one, and keep working on them, until you achieve the desired belt for your team. Activities of later belts often relate to activities introduced in previous belts. In this case, the previous relevant belt activities will be highlighted for the belt activity.

- [1 - White Belt](white/README.md)
- [2 - Yellow Belt](yellow/README.md)
- [3 - Orange Belt](orange/README.md)

## Credits

The Security Belts are based on the [OWASP DevSecOps Maturity Model](https://owasp.org/www-project-devsecops-maturity-model/) and partially inspired by [OWASP SAMM](https://owasp.org/www-project-samm/)
