# 🌸 Tutoriel Florence-2 — Détection, Description et Segmentation d’Objets avec l’IA de Microsoft

Bienvenue dans ce tutoriel pratique et accessible pour apprendre à utiliser **Florence-2**, un modèle avancé développé par **Microsoft** pour la **vision par ordinateur** et le **traitement du langage naturel**.

Florence-2 permet de détecter, décrire et segmenter des objets dans une image à partir de phrases naturelles — tout cela grâce à l’intelligence artificielle !

---

## 📚 Contenu du tutoriel

Ce dépôt contient :

- ✅ Un **notebook Colab** prêt à l’emploi
- 🧠 Du code commenté ligne par ligne
- 🖼️ Des exemples pour détecter et décrire des objets dans des images
- 🧰 Une démonstration simple pour les débutants

---

## 🚀 Débuter en 3 étapes simples

### 1. Ouvrir le notebook Colab

Clique ici pour commencer :
[![Ouvrir dans Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<votre-utilisateur>/<nom-du-depot>/blob/main/florence2_tutoriel.ipynb)

> Remplace `<votre-utilisateur>` et `<nom-du-depot>` par ton identifiant GitHub et le nom du dépôt.

---

### 2. Télécharger une image

Téléverse une image (par exemple : `car.png`) dans le notebook ou dans Google Colab via l’onglet « Fichiers ».

---

### 3. Lancer les cellules une par une

Tu verras :
- La détection des objets automatiquement
- La génération de descriptions (ex. : “une voiture verte stationnée devant un bâtiment jaune”)
- La possibilité de segmenter des zones précises dans l’image
- L’interprétation d’une phrase (ex. : “où est le panneau stop ?”)

---

## 🎓 Exemple de tâches prises en charge

| Tâche                         | Description                                                             |
|------------------------------|-------------------------------------------------------------------------|
| Détection d’objets           | Trouver et nommer les objets dans l’image                               |
| Description de régions       | Générer une légende pour une zone précise                               |
| Segmentation d’objets        | Colorier la forme exacte d’un objet (masque de segmentation)            |
| Interprétation de phrase     | Trouver la zone correspondant à une phrase ("une voiture rouge")        |
| Cascade complète             | Description → détection → segmentation automatique                      |

---

## 📦 Dépendances

Tu n’as rien à installer sur ton ordinateur ! Le notebook utilise :

- [Hugging Face Transformers](https://huggingface.co/docs/transformers/)
- `timm`, `einops`, `flash_attn`
- `PIL`, `matplotlib`

---

## 💡 À propos de Florence-2

Florence-2 est un modèle **vision-language** développé par Microsoft pour unifier les tâches de compréhension visuelle et textuelle dans une seule architecture puissante.

🔗 Référence officielle : [microsoft/Florence-2-large sur HuggingFace](https://huggingface.co/microsoft/Florence-2-large)

---

## 🤝 Contribuer

Tu peux proposer :
- de nouveaux exemples d’images 🖼️
- des extensions (webcam, interface Streamlit…) ⚙️
- une version avec ton propre dataset 💾

Forke le repo, ajoute tes améliorations, et fais une Pull Request 🙌

---

## 📜 Citation recommandée

Si tu utilises ce code ou Florence-2 dans un article, merci de citer Microsoft comme source du modèle original, et ce tutoriel comme guide d’implémentation :

> Tutoriel pédagogique basé sur Florence-2 de Microsoft, avec adaptation pour débutants par [houenagnon].

---

## 📬 Contact

Créé avec ❤️ pour démocratiser l'IA visuelle.  
Pour toute question : [merveilhouenagnon@gmail.com] ou ouvre une *issue*.

---

