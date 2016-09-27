#List of features for VTHacks app
=================================

Web App, iOS App and Android app
--------------------------------
1. Landing
2. Registration
3. Schedule + Map
    ..* A view just for VTHacks team to update the schedule
    ..* PUSH notifications to everyone (?)
4. List of teams, their submissions + table number (Check if DevPost has an
   API)
    ..* Once you register have a section to create a team or join a team.
5. Help request system
6. Resume database (only for sponsors to see) __Only for the web app?__ 
7. Chat system (low priority)

    ..* Maybe we can have 4 and 5 as just one view.


API
---
1. User
..* Have ability to POST, GET, PATCH, DELETE its own content
..1. Name
..2. School
..3. Age (?)
..4. Gender
..5. Social media
..6. Resume
..7. Create/join team (no more than 4 ppl per team)
..8. Phone number (?)

2. Schedule
..* Have ability to GET, PATCH, DELETE the schedule
..* Flexibility to change times (?)

3. Teams
..* Ability to POST, GET, PATCH, DELETE a team
..1. Up to 4 ppl per team
..2. Generate a team number which will be their table number as well.
..3. Request help per team.

Contact: developers@vthacks.com
