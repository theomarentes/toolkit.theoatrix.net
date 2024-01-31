# Theoatrix Toolkit

Frontend Repository: https://github.com/theomarentes/theoatrix-toolkit-frontend

Backend Repository: https://github.com/theomarentes/theoatrix-toolkit-backend 

### Table Of Contents
[Website Description](https://github.com/theomarentes/toolkit.theoatrix.net#website-description)

[Dataflow Diagram](https://github.com/theomarentes/toolkit.theoatrix.net#dataflow-diagram)

[Application Architecture Diagram](https://github.com/theomarentes/toolkit.theoatrix.net#application-architecture-diagram)

[User Stories](https://github.com/theomarentes/toolkit.theoatrix.net#user-stories)

[Wireframes](https://github.com/theomarentes/toolkit.theoatrix.net#wireframes)

[Testing](https://github.com/theomarentes/toolkit.theoatrix.net#testing)

[Trello Board](https://github.com/theomarentes/toolkit.theoatrix.net#trello-board)



## Website Description
The Theoatrix Toolkit will allow users to solve complex calculations with the goal of improving their experience playing RuneScape.

### Purpose
In RuneScape, players control a single character, enduring long grinds to increase their skill levels and aquire top tier equipment. The Theoatrix Toolkit will make difficult skill level calculations easier, it will track the user’s progress in the game and track the prices of equipment, using 3 different APIs.

WiseOldMan API: https://docs.wiseoldman.net/

Wiki GE API: https://prices.runescape.wiki/api/v1/osrs

Official API: https://secure.runescape.com/m=hiscore_oldschool/

Our database will store information from these APIs with periodic and user triggered scrapes.

### App Structure
Account Tracker Page
- WiseOldMan API

Skill Guides Page
- Written Guides (already written)
- Videos Guides (already created)
  
Calculators Page
- gp/xp calculator (Wiki GE API)
- Time to Max (WiseOldMan API)
- Alch calculator (dynamic pages for each item) (Wiki GE API) 

Grand Exchange Page
- Wiki GE API
- Hourly scrapes to database
- One page per item (dynamic)
  
My Account Page
- User login
- Favourite calculators
- Favourite items
- Favourite guides

### Target Audience
The Theoatrix Toolkit targets RuneScape players & Theoatrix's fans. The toolkit is for RuneScape enthusiasts seeking an all-in-one solution to enhance their gameplay and stay informed about the dynamic world of RuneScape.

![2013-2024 RuneScape Player Count](docs/runescape_player_count.jpg)
Above: RuneScape's Concurrent Player Count (2013-2024)

From seasoned players looking for advanced strategies to newcomers eager to navigate the intricacies of the game, Theoatrix's toolkit aspires to be a gaming companion, empowering players at every level.

### Tech Stack
The upcoming Theoatrix RuneScape Toolkit will be developed using the MERN (MongoDB, Express.js, React, Node.js) stack.
MongoDB, a NoSQL database, will efficiently store diverse user and equipment data.
Express.js will facilitate backend development, integrating with Node.js for server-side execution.
The frontend will leverage React, ensuring a responsive user interface.
The MERN stack will enable real-time updates on in-game progress and item prices. As users explore Theoatrix's guide videos and written content, the MERN stack will give a dynamic experience. 

### Libraries Used
In the development and production of the Theoatrix Toolkit, x libraries were used.
| Library |     Description     |
|---------|---------------------|
| library |  long description   |


## Dataflow Diagram	
HD: Provides dataflow diagram(s) that strictly follow the standard convensions to clearly identify the processes within your application. Clearly depicts where data is coming from, where it is going and how it is being stored.


## Application Architecture Diagram
HD: Shows almost flawless understanding of the high level structure of the app

## User Stories
Provide UX/UI design documentation(user stories) that adequately show Agile methodology implementation.
HD: Provides multiple user stories that use ‘persona, what and why’ that outline meaningful features of project. Shows evidence of user story revision and refinement.


## Wireframes
for multiple standard screen sizes, created using industry standard software
Utilise an industry standard program for creation of wireframes
Provide UX/UI design documentation(wireframes) that adequately show Agile methodology implementation.
HD: Provides wireframes that show exceptional planning of project flow and structure including but not limited to space distribution, content prioritisation, intended actions, functions, relationships between screens.

## Testing
Development Testing
Production Testing

## Trello Board
Select and follow a commonly used planning methodology, such as Kanban, Trello, Jira, or Asana.
HD: Simple and clear standards for planning methodology chosen and adhered to

### 30th January (Initial Board)
Our initial board consisted of the tasks required to complete Part A.
![30-1-24 Trello Board](docs/30-1-2024.jpg)



