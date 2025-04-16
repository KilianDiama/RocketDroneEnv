# 🛸 RocketDroneEnv

**RocketDroneEnv** est un environnement de simulation pour drones propulsés, conçu pour l’entraînement par renforcement. L’objectif : apprendre à un drone à voler efficacement en consommant un minimum de carburant et en atteignant des objectifs précis.

---

## 🧠 À propos

Ce projet propose un environnement customisé où un agent (le drone) apprend à décoller, stabiliser son vol, monter/descendre, et optimiser sa trajectoire à l’aide de l’apprentissage par renforcement (RL).

Utilisé avec **Stable-Baselines3** et l’algorithme **PPO**, il permet de tester, visualiser et affiner des politiques de vol autonomes.

---

## ✨ Fonctionnalités

- 📈 Environnement gym-compatible
- 🧪 Implémentation PPO via Stable-Baselines3
- 🚀 Modèle physique simplifié (force, masse, carburant, gravité)
- 🎯 Objectif dynamique avec récompenses
- 🧬 Logging des performances pour analyse

---

## 🛠️ Tech Stack

- Python
- Gym (OpenAI)
- Stable-Baselines3
- NumPy
- Matplotlib (pour la visualisation)

---

## ⚙️ Installation

```bash
git clone https://github.com/KilianDiama/RocketDroneEnv.git
cd RocketDroneEnv
pip install -r requirements.txt
▶️ Utilisation
bash
Copier
Modifier
python train.py
Tu peux modifier les hyperparamètres dans train.py pour ajuster le comportement de ton agent.

Pour visualiser les performances du modèle, utilise plot_results.py après l'entraînement.

📊 Exemple de rendu
À venir : graphique de la récompense cumulée ou GIF de la trajectoire.

🔮 Améliorations futures
🌪️ Ajouter le vent et autres perturbations physiques

🌐 Intégration avec un moteur graphique (PyGame / Unity / Web)

🧠 Comparaison de plusieurs algorithmes (DQN, A2C, etc.)

📦 Packaging de l’environnement comme un module pip installable

📜 Licence


✍️ Par Diamajax
“Apprendre à voler, c’est d’abord apprendre à tomber. Mais bien.” – Diamajax
