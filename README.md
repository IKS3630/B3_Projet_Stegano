# B3_Projet_Stegano 🚀

Un projet de **stéganographie & stéganalyse**, développé dans le cadre du projet tuteuré de B3 cybersécurité, permettant de **cacher des messages dans des images** puis de **les récupérer/détecter**.

## 🧩 Contexte & Objectifs

- **Pourquoi ce projet ?**  
  Explorer les techniques de stéganographie (caché d’informations) et de stéganalyse (détection/extraction) appliquées aux images numériques.
- **Principales fonctionnalités :**  
  - Insertion de messages secrets dans des images PNG/JPG  
  - Extraction des messages cachés  
  - Analyse/statistiques pour évaluer la discrétion (robustesse, qualité, ratio)

## ⚙️ Tech Stack

| Composant         | Technologie           |
|------------------|-----------------------|
| Langages         | Python, Jupyter Notebook |
| Bibliothèques    | Pillow, NumPy, éventuellement `stegano` |
| Visualisations   | Matplotlib / Seaborn (pour montrer les résultats) |

## 🛠️ Installation

**Prérequis :**
- Python 3.8+
- pip

```bash
git clone https://github.com/IKS3630/B3_Projet_Stegano.git
cd B3_Projet_Stegano
pip install -r requirements.txt
