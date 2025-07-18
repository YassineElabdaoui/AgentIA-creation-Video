# Agent IA – Création de Vidéos à partir de Tendances de Blagues

Ce projet met en œuvre un **agent intelligent** capable de générer automatiquement des scripts vidéo humoristiques à partir des tendances de blagues (recherchées en ligne ou fournies par une base de données), et de créer des vidéos prêtes à être diffusées sur les réseaux sociaux.

## 🔍 Fonctionnalités principales

- 🔎 **Analyse de tendances** (API, scraping ou dataset) pour détecter les blagues populaires
- 🧠 **Génération de scripts** comiques avec un modèle IA (GPT, etc.)
- 🎬 **Création automatique de vidéos** avec voix off, visuels ou avatars
- 📤 **Export pour TikTok, Reels, YouTube Shorts, etc.**

## ⚙️ Technologies utilisées

- Langchain / OpenAI pour la génération de contenu
- API de tendances (Twitter, Reddit, TikTok, etc.)
- Outils de génération vidéo (par ex. D-ID, Pictory, HeyGen, RunwayML...)
- n8n pour l'orchestration des automatisations

## 📦 Structure du projet

- `trend_scraper/` : collecte des tendances et des blagues
- `script_generator/` : génération de scripts comiques
- `video_creator/` : conversion du script en vidéo animée
- `scheduler/` : automatisation et planification des publications

## ✅ Exemple de pipeline

1. Récupérer une blague tendance
2. Générer un script humoristique adapté au format court
3. Créer la vidéo avec voix, musique et fond visuel
4. Sauvegarder ou publier automatiquement

## 🛡️ Remarques

- Ce projet ne contient aucun identifiant d'API : merci de configurer vos propres clés OpenAI ou services de génération vidéo.
- Destiné à un usage créatif, humoristique et non offensant.

---

🚀 *Ce projet vise à automatiser la création de contenu humoristique en s’appuyant sur l’intelligence artificielle générative.*
