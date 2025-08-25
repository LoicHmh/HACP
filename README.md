# HACP ![Human 80%](https://img.shields.io/badge/Human-40%25-brightgreen) ![AI 20%](https://img.shields.io/badge/AI-60%25-blue)

A community-driven protocol for declaring the balance of Human and AI contributions in open source projects. Because transparency matters.  


## 🌍 What is HACP?
With AI becoming a common tool in coding, it’s increasingly hard to know *who* (or *what*) wrote the code.  
The **Human–AI Contribution Protocol (HACP)** is a simple, self-declared standard that lets maintainers show the proportion of human vs AI work in their projects.  

This is **not about gatekeeping AI**, but about promoting **transparency and trust** in the open-source ecosystem.


## 📊 How It Works

1. **Add a declaration file** `contribution.yaml` at the root of your repo:
   ```yaml
   contributions:
     human: 80
     ai: 20
   categories:
     idea: { human: 100, ai: 0 }
     code: { human: 90, ai: 10 }
     docs: { human: 60, ai: 40 }
   declared_by: "username"
   date: "2025-08-25"
   version: "1.0"

2.	Add badges to your README:
![Human 80%](https://img.shields.io/badge/Human-80%25-brightgreen)
![AI 20%](https://img.shields.io/badge/AI-20%25-blue)

3.	(Optional) Use the GitHub Action or CLI (coming soon 🚀) to auto-generate badges.


## 🎯 Why Join?
	•	Promote transparency in your open-source project.
	•	Help users and contributors understand the balance of human vs AI work.
	•	Be part of a new cultural shift: open-source with open contribution origins.

## 🧩 Roadmap
	•	✅ v1.0: Self-declaration format (YAML + badges)
	•	🔜 v1.1: GitHub Action + CLI for easy setup
	•	🚀 v2.0: Community registry & advanced visualization
