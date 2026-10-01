# Mes projets

Étudiant en B1 Informatique à Ynov Campus Aix-en-Provence. Je conçois des applications web et mobiles en m'appuyant sur des outils d'IA pour coder plus vite.

Les quatre applications ci-dessous sont des **prototypes personnels** : des projets d'apprentissage pour tester une idée et une technologie, pas des produits en ligne. Chaque fiche indique ce qui fonctionne et ce qui reste à faire. Le code reste privé et je le montre volontiers sur demande.

---

## Weeko · emploi du temps de la semaine

> **Prototype personnel** · juin 2026 · le plus abouti, utilisable au quotidien

<p align="center"><img src="assets/weeko-jour.png" alt="Weeko, vue du jour" width="30%"> <img src="assets/weeko-activite.png" alt="Weeko, modifier une activité" width="30%"> <img src="assets/weeko-plannings.png" alt="Weeko, plannings et sauvegarde" width="30%"></p>

Une app pour organiser sa semaine sur téléphone, sans créer de compte. On place ses activités sur une grille horaire, on alterne semaine A et semaine B, on coche ce qui est fait, et le reste part dans une liste de tâches.

- Installable sur le téléphone et utilisable hors-ligne (PWA)
- Toutes les données restent sur l'appareil, sans serveur
- Plusieurs plannings, contrôle des chevauchements, sauvegarde et restauration par fichier

**Ce qui manque encore :** la synchronisation entre plusieurs appareils et des tests automatisés.

**Stack :** Next.js, React, TypeScript, Tailwind CSS, IndexedDB

---

## AmbientCare · compte-rendu médical assisté par IA

> **Prototype de démonstration** · juin 2026 · patients fictifs

<p align="center"><img src="assets/ambientcare-patients.png" alt="AmbientCare, liste des patients" width="30%"> <img src="assets/ambientcare-fiche.png" alt="AmbientCare, fiche patient" width="30%"><img width="300" height="598" alt="ambientcare-demo" src="https://github.com/user-attachments/assets/d0d22828-5241-46a4-a1d3-33034c39527d" />
</p>

Une maquette d'app mobile pour médecins hospitaliers. Le médecin enregistre la consultation, la transcription s'affiche en direct, puis une IA rédige un compte-rendu structuré que le médecin relit et valide avant que la famille soit prévenue.

- Parcours complet en 5 écrans
- Serveur relais qui protège la clé d'API
- Mode secours pour une démo fiable sans connexion à l'IA

**Ce qui manque encore :** l'enregistrement audio est simulé, sans vraie reconnaissance vocale. Ce n'est pas un outil médical et il n'est pas destiné à de vrais patients.

**Stack :** HTML, CSS, JavaScript, Node.js, API Claude

---

## MooveUp+ · app fitness pour athlètes hybrides

> **Prototype personnel** · octobre-novembre 2025 · le projet le plus ambitieux

<p align="center"><img src="assets/mooveup-banniere.png" alt="Logo MooveUp" width="400"></p>

<p align="center"><img src="assets/mooveup-dashboard.png" alt="MooveUp+, tableau de bord" width="800"></p>

<p align="center"><img src="assets/mooveup-programmes.png" alt="MooveUp+, programmes par compétence" width="49%"> <img src="assets/mooveup-pro.png" alt="MooveUp+, abonnement Pro" width="40%"></p>

Une application d'entraînement complète : programmes (dont certains générés par IA), suivi des séances, coach nutrition conversationnel, défis, badges, classement et fil social, avec abonnements payants.

- Une quarantaine d'écrans, en français et en anglais
- Paiement et abonnements, comptes utilisateurs, base de données sécurisée
- Export des données personnelles (RGPD), accessibilité, tests de bout en bout
- Travail produit en parallèle : specs, plan de lancement, modèle économique

**Ce qui manque encore :** l'app n'est pas en ligne et n'a pas de vrais utilisateurs. C'est un terrain d'essai pour une stack proche de la production.

**Stack :** Next.js, React, TypeScript, Supabase, Stripe, OpenAI, Three.js, Playwright

---

## Daily-Step · motivation au quotidien

> **Premier prototype** · octobre 2025

<p align="center"><img src="assets/daily-step.png" alt="Daily-Step, tableau de bord" width="800"></p>

Mon tout premier projet : une app de motivation avec citation du jour, défis par catégorie, séries de jours, points d'expérience, niveaux et badges, en français et en anglais.

**Ce qui manque encore :** pas de serveur ni de comptes, les données restent dans le navigateur, et les abonnements affichés ne sont pas branchés.

**Stack :** Next.js, React, TypeScript, Tailwind CSS, shadcn/ui

---

## Downfall of Gopher · projet d'école

> **Projet d'école terminé** · septembre 2026 · une semaine, en équipe de trois

<p align="center"><img src="assets/downfall-titre.png" alt="Downfall of Gopher, écran titre" width="600"></p>

<p align="center"><img src="assets/downfall-fika.png" alt="Downfall of Gopher, la boutique La Fika" width="45%"> <img src="assets/downfall-combat.png" alt="Downfall of Gopher, combat" width="30%"></p>

Jeu de rôle en ligne de commande écrit en Go pour le projet RED d'Ynov. On crée son personnage, on achète des objets à la boutique « La Fika », on fabrique de l'équipement et on combat jusqu'au boss, Gopher, la mascotte du langage Go. [Voir le dépôt](https://github.com/Juuuules83/Projet-RED-RAPH-ALEX-JULES)

**Ma part :** la création de personnage, la détection de la mort du joueur, la potion de poison, le README et la résolution des conflits Git.

**Stack :** Go
