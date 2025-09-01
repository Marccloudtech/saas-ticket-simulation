🌐 Disponible en : [English](README.md) | [Français](README.fr.md)

<!-- ===== BADGES (HEADER) ===== -->
![Conception pédagogique](https://img.shields.io/badge/Conception%20p%C3%A9dagogique-Blue?style=for-the-badge&logo=bookstack)
![QA pédagogique](https://img.shields.io/badge/QA%20p%C3%A9dagogique-Red?style=for-the-badge&logo=checkmarx)
![Cadre de gestion de versions](https://img.shields.io/badge/Cadre%20de%20gestion%20de%20versions-Orange?style=for-the-badge&logo=git)
![Cohérence du contenu](https://img.shields.io/badge/Coh%C3%A9rence%20du%20contenu-Green?style=for-the-badge&logo=dependabot)
![Index de connaissances](https://img.shields.io/badge/Index%20de%20connaissances-FFD700?style=for-the-badge&logo=readthedocs)
![Systèmes Ctrl+F](https://img.shields.io/badge/Syst%C3%A8mes%20Ctrl%2BF-00C7C7?style=for-the-badge&logo=readthedocs)
![Simulations de scénarios](https://img.shields.io/badge/Simulations%20de%20sc%C3%A9narios-6A5ACD?style=for-the-badge&logo=playwright)
![Bilingue EN/FR](https://img.shields.io/badge/Bilingue-EN%2FFR-8A2BE2?style=for-the-badge&logo=googletranslate)

---

🧪 **Simulation de support SaaS – Aperçu (Portfolio ClarityFlow Mastery)**  
Empathie · Communication · Langage · Croissance · Conception pédagogique · Bilingue EN/FR · QA & Gestion de versions

---

Ce projet simule un ticket de support SaaS réel traité dans un outil comme Zendesk. Il inclut :  

- Une demande client d’exemple  
- Une note interne montrant comment je réfléchirais et résoudrais le problème  
- Une réponse client rédigée en exemple  
- Bonus : structure de dossiers et captures d’écran  

---

### 🎯 Scénario : Échec de réinitialisation du mot de passe avec « Jeton invalide »  

**Message du client (via Zendesk) :**  
> « Bonjour, j’essaie de réinitialiser mon mot de passe mais votre système m’indique toujours “Jeton invalide”. Pouvez-vous m’aider ? »

---

### 🧠 Notes internes (équipe uniquement)  
Étapes que je suivrais avant de répondre au client :  

✅ Rechercher l’adresse du client dans la base de données  
🔍 Vérifier si le jeton est expiré (ils expirent souvent en 15–60 minutes)  
🔁 Si expiré, déclencher manuellement un nouveau lien de réinitialisation  
🛠 Enregistrer l’erreur auprès de l’équipe technique si le problème est récurrent  
📝 Documenter toutes les étapes en interne  

👉 Voir dossier : `internal_notes/zendesk_internal_note_01.md`

---

### 💬 Réponse client (exemple)  
**Ton :** calme, rassurant et professionnel  
**Objectif :** rassurer le client et résoudre le problème clairement  

👉 Voir dossier : `customer_responses/zendesk_customer_reply_01.md`

---

### 📁 Structure des dossiers
saas-ticket-simulation/
├── ticket-001-login-issue.md # Description du ticket (EN/FR)
├── internal-notes-001.md # Notes internes techniques (EN/FR)
├── customer-response-001.md # Réponse client (EN/FR)
│ ├── internal_notes/
│ │ └── zendesk_internal_note_01.md # Modèle optionnel de note interne
│ ├── customer_responses/
│ │ └── zendesk_customer_reply_01.md # Modèle optionnel de réponse
│ ├── screenshots/
│ │ └── zendesk_ui_mockup.png
│ └── README.md # Aperçu du projet + documentation


---

### 🖼 Exemple de vue Zendesk  
Maquette visuelle d’un ticket Zendesk pour donner le contexte :  
👉 `screenshots/zendesk_ui_mockup.png`

---

### 🛠 Pile technique & outils simulés  
📨 Zendesk (ticketing)  
🗂 Documentation interne (style Notion)  
🧠 Compétences humaines : calme sous pression, écriture claire, empathie, raisonnement étape par étape

---

### 🎯 Ce que ce projet démontre  
- Communication de support client en conditions réelles (anglais + français)  
- Gestion simulée de tickets de support type Zendesk  
- Documentation technique interne  
- Réponses client bilingues et professionnelles  
- Organisation de projet GitHub et hygiène de commits

---

### 💼 Pertinence pour le portfolio  
Cette simulation est conçue pour refléter un rôle réel de support SaaS utilisant des outils comme Zendesk ou Intercom.  

Elle démontre ma capacité à :  
- Rédiger des réponses claires et empathiques  
- Documenter les étapes de dépannage technique  
- Communiquer professionnellement en anglais et en français  
- Rester calme sous pression lors de résolutions à distance

---

### 🔄 Leçons tirées / Réflexion  
- Simuler des cas de support développe la confiance en conditions réelles  
- Des notes internes claires évitent la confusion lors des passations  
- Les clients ne veulent pas seulement une solution : ils veulent **clarté et attention**

---

### 📄 Buyer Persona vs. ICP – Note interne de support  
Ressource supplémentaire :  
Découvrir comment les équipes SaaS définissent et utilisent les **Buyer Personas** et les **ICP (Ideal Customer Profiles)** pour améliorer le support et la communication.  

👉 Voir : `buyer-persona-vs-icp-fr.md`

---

### 🙋‍♂️ À propos de moi  
Je suis Marc, **concepteur pédagogique & créateur de contenu bilingue (EN/FR)** spécialisé dans les systèmes de formation SaaS.  

Je crée des simulations comme celle-ci pour :  
- Montrer comment des workflows techniques (notes internes, escalades, réponses clients) peuvent être transformés en **contenus de formation prêts à l’emploi**  
- Mettre en valeur la **communication bilingue** (anglais + français) dans des contextes de support réels  
- Appliquer des **cadres de conception pédagogique** (clarté, QA, cohérence) aux scénarios SaaS  

📌 Ce projet est un **aperçu** de mon cours *ClarityFlow Mastery* et de mon *Companion Bible de conception pédagogique*.  
Il ne contient pas l’intégralité du cours — seulement des exemples sélectionnés présentés ici comme pièces de portfolio.

---

### 💼 Contexte portfolio  
Cette simulation démontre ma capacité à concevoir des **workflows pédagogiques** autour de scénarios de support SaaS.  
D’autres simulations et modules structurés seront publiés prochainement dans le cadre de mon cours **ClarityFlow Mastery**.

---

### 📫 Contact  
[GitHub](https://github.com/Marccloudtech) · [LinkedIn](https://www.linkedin.com/in/marc-maisonneuve-6345b6373/) · **marc.m.saas@gmail.com**

---

## 🛠 Outils simulés  
![Zendesk Simulation](https://img.shields.io/badge/Zendesk-Simul%C3%A9-blue?style=for-the-badge&logo=zendesk)  
![Intercom Simulation](https://img.shields.io/badge/Intercom-Simul%C3%A9-darkblue?style=for-the-badge&logo=intercom)  
![Notion Documentation](https://img.shields.io/badge/Notion-Docs-lightgrey?style=for-the-badge&logo=notion)  
![GitHub Portfolio](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)  
