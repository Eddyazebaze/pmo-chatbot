# 🤖 PMO Chatbot – Projet Augmenté

Un chatbot expérimental développé avec **Botpress** pour tester la capacité d’un assistant à répondre de manière fiable et pédagogique sur le **PMO (Project Management Office)**.

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
  - Exactitude (0–4)  
  - Périmètre (0–3)  
  - Clarté (0–2)  
  - Sobriété (0–1)  

---

## ⚠️ Limites
- Ce bot est expérimental.  
- Ne couvre pas les cas spécifiques (RH, contrats, réglementations locales).  
- Pour toute précision métier → escalade vers un expert humain.  

---

## 📜 Licence
Projet sous licence **MIT** (à adapter selon ton choix).
