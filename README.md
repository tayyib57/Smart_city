# Smart City Traffic Detection

This project utilizes AI for real-time traffic detection and analysis.

## Installation

```bash
git clone https://github.com/tayyib57/Smart_city.git
cd Smart_city
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
./setup.sh
python script.py \
--source_weights_path data/model4.pt \
--source_video_path data/output.mov \
--confidence_threshold 0.3 \
--iou_threshold 0.5 \
--target_video_path data/output_result.mov



### Explication des sections :

- **Header** : Donne un titre significatif au projet.

- **Description** : Explique brièvement le but du projet.

- **Installation** : Instructions de clonage du repository, configuration de l'environnement Python, installation des dépendances, et téléchargement des fichiers nécessaires.

- **Usage** : Commande pour exécuter le système de détection de trafic avec les arguments nécessaires.

- **Demo Video** : Intègre la vidéo de démonstration `trafic_detection.mov` directement dans le README.md avec un lien permettant aux utilisateurs de visualiser la vidéo en cliquant dessus.

- **License** : Indique la licence sous laquelle le projet est distribué.

### Processus de mise à jour du repository

Une fois que vous avez remplacé `trafic_detection.mov` par le nom réel de votre vidéo et mis à jour le fichier README.md :

1. Enregistrez les modifications.

2. Utilisez `git add .` pour ajouter toutes les modifications au suivi de Git.

3. Utilisez `git commit -m "Ajouter README complet avec vidéo de démonstration"` pour créer un nouveau commit avec votre message descriptif.

4. Utilisez `git push origin main` (ou la branche que vous utilisez) pour pousser les modifications vers votre repository GitHub.

Assurez-vous que la vidéo spécifiée est correctement hébergée à la racine de votre repository et que le lien dans le fichier README.md est correctement configuré pour que les utilisateurs puissent la visionner en cliquant dessus.
