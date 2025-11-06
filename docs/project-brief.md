# AI Threat Modeling Case Study  
*Author: Ratnesh Bhattacharya*  
*Date: [insert today’s date]*  

## 🎯 Objective
Analyze a generative AI system (LLM-based chatbot or assistant) using threat modeling frameworks to identify potential risks and propose mitigations.

## 🧩 Scope
- In scope:  
  - Prompt processing, retrieval, embedding storage, and LLM response flows  
  - AWS-native services (API Gateway, Lambda, DynamoDB, S3)  
  - Security data from GuardDuty, Security Hub, Macie, and Detective  

- Out of scope:  
  - Non-AWS or offline components  
  - Production-grade monitoring or SOC integration  

## ⚙️ Assumptions
- Region: `us-east-1`  
- All services running within AWS Free Tier or 30-day trial limits  
- IAM user `AITM-Admin` with AdministratorAccess (MFA-enabled)  
- Single-user project; no external collaborators  

## 🛠️ Deliverables
- Context and Data Flow Diagrams (Draw.io)  
- Threat Model (STRIDE + OWASP Top 10 for LLMs)  
- Mitigation Recommendations & Final Security Architecture Diagram  
- Executive Summary report (PDF)  

## 🗓️ Timeline
30 days (1 hour/day) following the structured plan:
- Week 1: Setup & Architecture  
- Week 2: AWS Security Enablement  
- Week 3: Threat Modeling  
- Week 4: Mitigation & Reporting  

## 📈 Success Criteria
- Working minimal AWS deployment  
- Security findings captured in Security Hub and GuardDuty  
- Documented threat model with clear mitigations  
- Completed teardown checklist with $0 post-trial billing  

## 📚 References
- MITRE ATLAS: [https://atlas.mitre.org/matrices/ATLAS](https://atlas.mitre.org/matrices/ATLAS)  
- OWASP Top 10 for LLMs  
- AWS Security Hub CIS Foundations Benchmark  
