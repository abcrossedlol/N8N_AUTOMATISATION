# 🛡️ Automatisations n8n — Portfolio SSI

Collection de workflows n8n

## 📋 Workflows

### 🔍 CVE_VEILLE
Veille automatique des CVE critiques (CVSS ≥ 7) via l'API NVD.
Trie les vulnérabilités par techno (Windows, Linux, Apache, Cisco) 
et envoie des alertes dans des salons Discord dédiés chaque jour à 8h.
<img width="1621" height="857" alt="image" src="https://github.com/user-attachments/assets/e49ab2fd-b615-4bf3-b6f1-566ddc980524" />

### 📰 SSI
Veille SSI quotidienne via 4 flux RSS (CERT-FR, ANSSI, Graham Cluley, Krebs on Security).
Résumés automatiques en français par IA (Groq) envoyés sur Discord.

### 🤖 AGENT_SSI
Bot Discord qui répond aux questions cybersécurité avec la commande `!ssi`.
Propulsé par Groq (LLaMA 3.1) avec un prompt expert SSI/ISO 27001.
<img width="1507" height="217" alt="image" src="https://github.com/user-attachments/assets/f41698c5-81e3-40c7-8260-cbb963f6dd33" />

### 🏍️ METEO-MOTO
Rapport météo quotidien pour 3 villes (Saint-Xandre, Niort, Surgères).
Conditions moto (température, vent, pluie) envoyées sur Discord matin et soir.

### 💾 BACKUP_N8N
Sauvegarde automatique de tous les workflows n8n vers ce repo GitHub.
<img width="822" height="223" alt="image" src="https://github.com/user-attachments/assets/a674b12c-14b9-485b-8048-bfc0856998cc" />

### 🔎 RECHERCHE_ALTERNANCE
Recherche automatisée d'offres d'alternance via JSearch, SerpAPI et Hunter.io.
Enrichissement des contacts avec Hunter.io et export vers Google Sheets.

## 🛠️ Stack technique
- n8n (self-hosted via Docker)
- Groq API (LLaMA 3.1)
- Discord Webhooks & Bot API
- NVD API, Open-Meteo API, GitHub API
- CERT-FR, ANSSI, Krebs on Security (flux RSS)

## 👤 Auteur
abcross
