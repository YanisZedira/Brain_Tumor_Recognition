# 🧠 Détection Automatique de Tumeurs Cérébrales via Deep Learning

**Projet de recherche réalisé par Yanis Zedira**  
**Date : 2025**  

---

## 📚 Résumé du projet

Ce projet vise à automatiser la détection de tumeurs cérébrales sur des images IRM grâce à l'Intelligence Artificielle et aux réseaux neuronaux de type YOLOv8.  
L'objectif est d'assister le corps médical en fournissant une aide au diagnostic rapide et fiable.

---

## 🩺 Contexte Médical

Les tumeurs cérébrales comme les gliomes, méningiomes et adénomes hypophysaires présentent des challenges de détection précoces en imagerie médicale.  
Une bonne reconnaissance permet une meilleure prise en charge thérapeutique.

---

## 🛠️ Technologies utilisées

- Python 3.10
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- OpenCV
- NumPy, Matplotlib
- Google Colab (Environnement d'entraînement)

---

## 🗂️ Dataset

- **Source :** [Kaggle - Brain Tumor Detection Dataset](https://www.kaggle.com/code/pkdarabi/brain-tumor-detection-with-yolov8)
- **Classes :** Gliome, Méningiome, Adénome Hypophysaire, Pas de Tumeur.

---

## 🧪 Méthodologie

- Prétraitement des IRM et augmentation de données (rotation, flips, zooms...).
- Annotation des images pour détection d'objet.
- Entraînement d'un modèle YOLOv8 sur les IRM.
- Validation et évaluation avec métriques médicales : Précision, Rappel, mAP50, mAP50-95.

---

## 📈 Résultats

- **Précision globale :** ≈ 91%
- **mAP50 (Mean Average Precision) :** ≈ 93%
- **mAP50-95 (IoU 0.5 à 0.95) :** ≈ 72%

Le modèle démontre une excellente capacité à détecter les tumeurs sur IRM dans des conditions variées.

---

## 🔍 Comment tester le modèle

1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/TON_USERNAME/TON_REPO.git


2. Installer les dépendances :

pip install -r requirements.txt

Lancer le notebook brain_tumor_detection_yanis_zedira.ipynb sur Google Colab ou en local.

Utiliser votre propre image IRM pour tester la détection automatique avec le modèle best.pt.

📄 Rapport complet

Le rapport complet (mini-thèse) sur la problématique, l'approche scientifique et les résultats expérimentaux est disponible dans ce dépôt sous forme de fichier .ipynb ou PDF.
🤝 Remerciements

    Dataset initial : Kaggle - Brain Tumor Detection Dataset

    Framework YOLOv8 : Ultralytics

    Plateforme d'entraînement : Google Colab.

📬 Contact
Yanis Zedira
LinkedIn Profil : https://www.linkedin.com/in/yaniszedira/
