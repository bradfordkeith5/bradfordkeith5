# Hi there, I'm Bradford! 👋

![Bradford's Banner](https://img.shields.io/badge/Salesforce%20Admin-DevOps%20Specialist-blue?style=for-the-badge)

## About Me 🚀

I'm a passionate **Salesforce Administrator & DevOps Specialist** with experience in **Agentforce, Sales Cloud and Service Cloud**. I love tackling complex problems, learning new skills, and collaborating with diverse teams to create innovative solutions.

- 🌱 Currently learning: **AWS Cloud Practioner Certification, SQL Database Query & Google Data Analytics Certification**
- 🔭 Working on: **Agentforce automation projects & GITHUB portfolio building**
- 🌍 Languages: **English (native), Learning Haitian Creole and French**
- 📫 How to reach me: **bradfordmkeith@outlook.com**
- ⚡ Fun fact: **I'm passionate about bridging the gap between admin and development teams**

## My Skills 🧠

![ChatGPT.js](https://img.shields.io/badge/ChatGPT-74aa9c?style=flat-square&logo=openai&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=Jira&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white)
![OneDrive](https://img.shields.io/badge/OneDrive-white?style=flat-square&logo=Microsoft%20OneDrive&logoColor=0078D4)
![Salesforce](https://img.shields.io/badge/-Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Apex](https://img.shields.io/badge/-Apex-00A1E0?style=flat-square&logoColor=white)
![DevOps](https://img.shields.io/badge/-DevOps-FCC624?style=flat-square&logo=linux&logoColor=black)

*For more badges, visit [Badges4-README](https://github.com/alexandresanlim/Badges4-README.md-Profile).*

---

## ⚡ Quick Examples
[![forthebadge](https://forthebadge.com/images/badges/made-with-crayons.svg)](http://forthebadge.com)
### Salesforce Apex - Query Optimization
```apex
// Get accounts with related contacts efficiently
List<Account> accounts = [
    SELECT Id, Name, (SELECT Id, Email FROM Contacts)
    FROM Account 
    WHERE Industry = 'Technology'
    LIMIT 1000
];

### SQL Database JOIN Query
//Find the list of all buildings that have employees
SELECT DISTINCT building, capacity FROM employees
    JOIN buildings
        ON building_name = building;
