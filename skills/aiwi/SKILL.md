---
name: aiwi
description: Installer ou adapter le système Markdown AIWI de gestion des Work Items et de leur recette dans un projet local. Utiliser pour intégrer le modèle dans un nouveau projet ou l’aligner sur ses conventions.
---

# Intégrer AIWI

1. Lire [le modèle source](../../_TEMPLATE.md) depuis le dossier de ce skill. Dans le projet cible, repérer les consignes locales et les éventuels WI, modèles ou dossiers de suivi existants.
2. Présenter le chemin et les adaptations proposées avant de modifier le projet. Réutiliser l’emplacement existant s’il convient ; sinon proposer `work-items/` à la racine. Si les règles locales sont incompatibles, demander un arbitrage plutôt que de créer un deuxième système de suivi.
3. Après accord, créer les éléments manquants : `_TEMPLATE.md` et les dossiers `todo/`, `to_validate/`, `done/` et `recette/`. Ajouter un `.gitkeep` aux nouveaux dossiers vides si le projet est versionné avec Git. Si un modèle existe déjà, appliquer uniquement les modifications convenues. Ne pas déplacer, réécrire ni supprimer les WI ou recettes existants.
4. Adapter le modèle local au vocabulaire, aux conventions de nommage et aux vérifications documentées du projet. Conserver les règles de cycle de vie du modèle source ; demander un arbitrage si une adaptation les remet en cause.
5. Ajouter une courte référence au modèle local dans `AGENTS.md` (ou dans le fichier de consignes équivalent), si elle n’existe pas déjà. Vérifier que le modèle, les quatre dossiers et le lien sont en place, puis résumer les choix retenus.
