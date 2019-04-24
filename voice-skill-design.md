# Voice Skill Design
How to suggest, prepare, design a voice skill for Mycroft? For now, by using plain old text and a little bit of role play (1. user, 2. mycroft).

## Light Version – Suggest a Skill
The lighter version is like a one-page brief for a skill. The document consists of 8 sections:
1. Skill Name
2. User Stories
3. 3rd Party Services
4. Similar Skills
5. User Phrases
6. Mycroft Phrases
7. Skill Settings
8. Notes

The easiest way to understand it is to take a look at some examples:
- [Spotify Skill Example](https://community.mycroft.ai/t/music-spotify/2960)
- [Calendar Skill Example](https://community.mycroft.ai/t/productivity-calendar-skill/3788)

## Standard Version – Prepare a Skill
### 1. Create “Skill Name: Notes” Document
- To kick off the design process, think about:
  - In what situations, contexts will the skill be used
  - What is necessary for the skill to do for the user
  - What things need to be considered or figured out during the skill design process
- The document has therefore at least 3 sections:
  - Common Use Cases
  - Requirements
  - Issues to think about
  - Intent priorities can be added here or at point 3. below
- Brainstorming can be done solo or in a group
- Example: [Alarm Skill: Notes](https://docs.google.com/document/d/1quYjdNlZrUkS2sLUP25r_9Xu41hnZ0G67anUrxAiKw0/edit?usp=sharing)

### 2. Create “Skill Name: Dialog Sketches” Document
- Think of everything you want to ask your skill (exhaustive list)
  - Include multiple ways of asking the same thing
- Group utterances into Intents
- Add Mycroft responses
- Add error handling phrases
- Review document with teammates – developer, designer
- Example: [Alarm Skill: Dialog Sketches](https://docs.google.com/document/d/1A9xsX_kaUgSpyPVTx1uCvGn2JydLQY62JmFMO3qUUwQ/edit?usp=sharing)

### 3. Optional: Create “Skill Name: Intent Priority” Spreadsheet
- A simple spreadsheet that includes all intents with an assigned priority, assigned developer, and current status of the intent development
- Priority 1 is considered the MVP (minimum viable product) and gets built first
- Example: [Timer Skill: Intent Priority](https://docs.google.com/spreadsheets/d/14KHbjcarda-qhIpYpXX-81_tinPm6fzhECuR_qsjtTo/edit#gid=0)

### 4. Optional: Create “Skill Name: Job Stories” Spreadsheet
- Great for new feature discovery by analyzing users' “jobs to be done” (goals to be achieved)
- Unnecessary at MVP building stage
- Structure of a job story is defined but there is art to writing high quality job stories that lead to identifying real users' wants and needs
- Jobs to be done approach is a powerful framework, mindset for problem solving and innovation
- Example: [Music Skill: Job Stories](https://docs.google.com/spreadsheets/d/1lopz6eE0xVUPzPfCkQutfU07P7PxW0ebh0geAEkgHls/edit#gid=0)

### 5. Create “Skill Name: Review Notes” Document
- For saving notes while testing the developed skill (multiple iterations)
- This is part of the quality assurance process, and can be done through project and task management software or bug tracking software
- Review notes are grouped into Intents or other logical categories
- List of non-working features and unexpected behaviors goes through prioritization that is collectively agreed upon and gets fixed item by item by the skill developer
- Example: [Alarm Skill: Review Notes](https://docs.google.com/document/d/1ML2q4xYFoYOo_bvbqlqsvIxkYo2GSHcOX4YhE4bXtVI/edit)
