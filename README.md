# 🤖 PMO Chatbot - Projet Augmenté

Un chatbot expérimental développé avec **Botpress** pour tester la capacité d’un assistant à répondre de manière fiable et pédagogique sur le **PMO (Project Management Office)**.

![Status](https://img.shields.io/badge/status-experimental-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Botpress](https://img.shields.io/badge/Botpress-v12-blue)

---

## 🎯 Objectifs
- Évaluer la robustesse des réponses sur le rôle du PMO.  
- Tester la capacité du bot à éviter les **hallucinations**.  
- Fournir une **base de connaissances pédagogique et structurée** en Markdown.  

---

## 📂 Structure du projet
- `kb/KB_PMO_Chatbot.md` → Knowledge Base complète.  
- `kb/HighLevel_Instructions_PMO.md` → Instructions haut-niveau pour Botpress.  
- `tests/QA_Test_Set.md` → Jeu de tests (33 questions).  

---

## 🧪 Protocole de test
- **20 questions factuelles** → doivent obtenir une réponse claire.  
- **10 questions pièges** → doivent générer un refus clair.  
- **3 questions bonus** → robustesse supplémentaire.  
- **Critères de succès** : ≥ 8/10 par réponse  
  - Exactitude (0-4)  
  - Périmètre (0-3)  
  - Clarté (0-2)  
  - Sobriété (0-1)  

---

## 🛠️ Stack utilisée
- [Botpress](https://botpress.com/) – plateforme low-code pour chatbots  
- **Markdown** – structuration de la KB  
- **GitHub** – gestion de version et documentation  

---

## 🚀 Roadmap
- [ ] Ajouter la version enrichie de la KB (livrables + cas concrets).  
- [ ] Déployer une démo publique du bot.  
- [ ] Ajouter des scénarios de test automatisés.  
- [ ] Créer un tableau de suivi (GitHub Projects) pour tracer les évolutions.  

---

## ⚠️ Limites
- Ce bot est expérimental.  
- Ne couvre pas les cas spécifiques (RH, contrats, réglementations locales).  
- Pour toute précision métier → escalade vers un expert humain.  

---

## 👤 Auteur
- **Nom :** Eddy AZEBAZE  
- **LinkedIn :** [linkedin.com/in/eddy-azebaze-034a20226](https://www.linkedin.com/in/eddy-azebaze-034a20226)  
- **Email :** *eddy.azebaze@proton.me*  

---

## 📜 Licence
Projet sous licence **MIT** - libre pour usage et adaptation, avec attribution.  


