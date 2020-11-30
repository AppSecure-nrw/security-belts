# Security Belts

## Methodology

TODO

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

## Belts

- [White Belt](white/README.md)
- [Yellow Belt](yellow/README.md)
- [Orange Belt](orange/README.md)

## Credits

The Security Belts are based on the [OWASP DevSecOps Maturity Model](https://owasp.org/www-project-devsecops-maturity-model/) and partially inspired by [OWASP SAMM](https://owasp.org/www-project-samm/)
