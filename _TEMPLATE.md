# Work Items (WI)

1. **Création.** Remplir le modèle ci-dessous et enregistrer le WI dans `todo/` sous un nom unique, par exemple `WI-001-titre.md`. Dès sa création, ne plus modifier son contenu ni son nom.
2. **Statut.** Seul le dossier du WI indique son statut : `todo/` (à faire), `to_validate/` (à valider) ou `done/` (terminé). Déplacer le fichier sans le dupliquer.
3. **Recette.** Au passage dans `to_validate/`, créer dans `recette/` un livre de recette du même nom que le WI. Écrire une ligne par contrôle : action et résultat attendu. Exemple : `- Enregistrer le profil : le nom saisi s’affiche après rechargement.`
4. **Validation.** Une fois la recette créée, ne rien ajouter ni modifier. La personne qui valide supprime uniquement les lignes dont le résultat attendu est confirmé. Si un contrôle échoue, sa ligne reste et le WI reste dans `to_validate/`. Si l’IA constate qu’un contrôle déjà validé ne passe plus, elle le signale au responsable du projet, qui décide de la suite.
5. **Clôture.** Quand toutes les lignes ont été validées, supprimer le livre de recette vide, puis déplacer le WI dans `done/`.
6. **Obsolescence.** Supprimer tout WI devenu obsolète et sa recette s’il en reste une. Ne rien archiver.

## Modèle à copier

```markdown
# Titre du WI

## Objectif

Résultat attendu.

## Périmètre

Ce qui est inclus, exclu et les prérequis éventuels.

## Validation

Vérifications techniques et critères observables pour la recette.
```
