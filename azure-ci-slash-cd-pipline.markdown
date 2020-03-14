---
title: Azure CI/CD Pipline
date: 2020-03-13 14:55:00 +01:00
---

# This is my first blog

Azure est un cloud de pointe  qui permet d’héberger des machines virtuelles exécutant Windows et Linux. Que vous utilisiez ASP.NET, Java, Node.js ou PHP pour développer des applications, vous devez disposer d’un pipeline d’intégration continue et de déploiement continu pour envoyer automatiquement vos modifications à ces machines virtuelles.

Azure DevOps fournit le pipeline d’intégration continue et de déploiement continu. Celui-ci inclut un dépôt Git pour la gestion du code source de votre application et du code d’infrastructure (modèles ARM), un système de génération pour la production de packages et d’autres artefacts de génération, ainsi qu’un système de gestion des mises en production pour la configuration d’un pipeline afin de déployer vos modifications via les environnements de développement, de test et de production. Le pipeline utilise des modèles ARM pour provisionner ou mettre à jour votre infrastructure si nécessaire dans chaque environnement, puis déploie le build mis à jour. Vous pouvez également utiliser les laboratoires Azure Dev/Test pour supprimer automatiquement les ressources de test qui ne sont pas utilisées.