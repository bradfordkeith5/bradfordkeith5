# Hi there, I'm Bradford! 👋

![Bradford's Banner](https://img.shields.io/badge/Salesforce%20Admin-DevOps%20Specialist-blue?style=for-the-badge)

## About Me 🚀

I'm a passionate **Salesforce Administrator & DevOps Specialist** with experience in **Agentforce, Sales Cloud and Service Cloud**. I love tackling complex problems, learning new skills, and collaborating with diverse teams to create innovative solutions.

- 🌱 Currently learning: **Advanced Salesforce Development & Cloud Architecture**
- 🔭 Working on: **Agentforce automation projects & DevOps pipelines**
- 🌍 Languages: **English (native), Learning Haitian Creole and French**
- 📫 How to reach me: **bradmkeith@gmail.com**
- ⚡ Fun fact: **I'm passionate about bridging the gap between admin and development teams**

## My Skills 🧠

![Salesforce](https://img.shields.io/badge/-Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Apex](https://img.shields.io/badge/-Apex-00A1E0?style=flat-square&logoColor=white)
![DevOps](https://img.shields.io/badge/-DevOps-FCC624?style=flat-square&logo=linux&logoColor=black)

*For more badges, visit [Badges4-README](https://github.com/alexandresanlim/Badges4-README.md-Profile).*

---

## ⚡ Quick Examples

### Salesforce Apex - Query Optimization
```apex
// Get accounts with related contacts efficiently
List<Account> accounts = [
    SELECT Id, Name, (SELECT Id, Email FROM Contacts)
    FROM Account 
    WHERE Industry = 'Technology'
    LIMIT 1000
];
