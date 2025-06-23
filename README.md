# B3_Projet_Stegano 🚀

Un projet de **stéganographie**, développé dans le cadre du projet tuteuré de B3 cybersécurité, permettant de **cacher des messages dans des fichiers numériques** puis de **les récupérer/extraire**.

## 🧩 Contexte & Objectifs

- **Pourquoi ce projet ?**  
  Explorer les techniques de stéganographie (cacher de l’information) appliquées aux fichiers numériques.
- **Principales fonctionnalités :**  
  - Insertion de messages secrets dans des fichiers
  - Extraction des messages cachés  

## 📦 Types de stéganographie prises en charge

Ce projet permet de cacher du texte dans plusieurs types de fichiers :

| Format          | Technique utilisée                                              |
|----------------|------------------------------------------------------------------|
| `.txt`         | Caractères Unicode invisibles (`\u200b`, `\u200c`)               |
| `.png`         | Bit de poids faible (LSB) sur les pixels RVB                     |
| `.wav`         | LSB sur les échantillons audio                                   |
| `.pdf`         | Métadonnées du document (`/SteganoSecret`)                      |
| `.docx/.pptx/.xlsx` | Insertion dans le contenu textuel des paragraphes ou cellules |
| `.mp4`         | Ajout d’un fichier secret en fin de fichier vidéo binaire        |


## ⚙️ Tech Stack

| Composant       | Technologie                                                 |
|-----------------|-------------------------------------------------------------|
| Langages        | Python, HTML                                   |
| Bibliothèques   | Flask, Pillow, NumPy, PyPDF2, python-docx, openpyxl, etc... |
| Visualisations  | Serveur de prod : Gunicorn , Serveur de test : Flask |


## 🛠️ Installation
**Prérequis :**
- Python 
- requirements.txt


```bash
git clone https://github.com/IKS3630/B3_Projet_Stegano.git
cd B3_Projet_Stegano
pip install -r requirements.txt
py app.py #or python app.py
```

---

Made with ❤️ by Quentin - Karl - Bruce

