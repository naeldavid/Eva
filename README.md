<p align="center">
  <img src="eva.png" width="350">
</p>

<h1 align="center">Eva</h1>

<p align="center">
L'assistante IA faite <b>PAR et POUR</b> les étudiants du curriculum français
</p>

Eva est une assistante IA éducative conçue *spécifiquement* pour les élèves du système éducatif français (collège et lycée). Elle les aide à approfondir leur compréhension des concepts plutôt que de simplement leur fournir les réponses.

## Présentation

Eva est basée sur `gemma4:31b-cloud` et optimisée pour les interactions pédagogiques. Elle adapte ses explications au niveau scolaire de l'élève et suit le programme scolaire français.

### Détails du modèle

- **Modèle de base** : gemma4:31b-cloud
- **Température** : 0,3 (précision plutôt que créativité)
- **Fenêtre de contexte** : 16 384 tokens
- **Langue** : Français (par défaut)

### Fonctionnalités

- Explique les concepts étape par étape
- S'adapte au niveau de l'élève (de la 6e à la Terminale)
- Couvre toutes les matières du programme scolaire français
- Guide le raisonnement sans donner de réponses directes
- Analyse les images des devoirs/exercices (lorsqu'elles sont envoyées)

### Niveaux pris en charge

| Cycle | Niveaux | Objectif |
|-------|--------|-----------|
| Collège | 6e, 5e, 4e, 3e | Brevet des collèges |
| Lycée | 2e, 1ère, Terminale | Baccalauréat |

### Utilisation

`ollama pull naeldv/Eva

ollama run naeldv/Eva`

### Approche pédagogique

- **Échafaudage pédagogique** : Construction progressive des connaissances
- **Questionnement socratique** : Découverte guidée
- **Métacognition** : Développement de la conscience de l’apprentissage
- **Rétroaction formative** : Amélioration continue

### Matières couvertes

#### Collège
- Mathématiques : Nombres, Géométrie, Statistiques
- Français : Grammaire, Littérature, Expression écrite
- Histoire-Géographie : Programme national
- Sciences : Biologie, Géologie, Écologie
- Langues : Anglais, Espagnol, Allemand

#### Lycée
- Spécialités scientifiques : Mathématiques, Physique-Chimie, Sciences de la vie
- Spécialités littéraires : Lettres, Philosophie, Langues
- Économie : Économie sociale et sociale, Gestion
- Options : Arts, Musique, Informatique

### Options de configuration

```bash
ollama run Eva --temperature 0.2 "Pour restreindre les hallucinations possibles"
ollama run Eva --num_ctx 8192 "Questions Longues"
ollama run Eva --system "Étudiant Terminale Spé SVT" "Explique la photosynthèse"
```

### Collaboration

Je serais ravis de recevoir vos contributions pour :

* Ajouter des exemples pédagogiques
* Améliorer les explications spécifiques à chaque matière
* Élargir le programme d’études
* Avoir des traductions pour les élèves apprenants du système français.
