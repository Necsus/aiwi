# AIWI

Un modèle Markdown minimaliste pour suivre des Work Items et leur recette. Les [règles et le modèle de WI](_TEMPLATE.md) sont dans `_TEMPLATE.md`.

## Intégrer AIWI avec Pi

Garder une copie locale de ce dépôt. Depuis la racine du projet cible, lancer Pi en chargeant le [skill AIWI](skills/aiwi/SKILL.md) :

```sh
pi --skill /chemin/vers/aiwi/skills/aiwi/SKILL.md
```

Dans Pi, lancer `/skill:aiwi Intègre AIWI dans ce projet et adapte le modèle à ses conventions.`

Le skill propose d’abord un emplacement et des adaptations. Après accord, il installe le modèle dans le projet et y ajoute un lien depuis les consignes locales. Les WI existants restent intacts et le projet n’a pas besoin du skill pour continuer à utiliser le modèle.
