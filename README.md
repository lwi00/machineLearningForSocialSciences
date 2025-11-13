# Guide pour cette matière

Guide rapide pour ce cours de ML for social sciences du master IREN. Ce guide servira à installer ce repo, lancer un environnement virtuel, installer les packages sur Mac et Windows, puis faire les premiers projets. Enjoy !

## 📋 Prérequis

- Python >= 3.13 (installer avec uv)
- pip (généralement inclus avec Python)
- git (pour cloner le repository)

## 🚀 Installation

### Sur Mac

1. **Cloner le repository** (si ce n'est pas déjà fait) :
   ```bash
   git clone https://github.com/lwi00/machineLearningForSocialSciences.git
   cd machineLearningForSocialSciences
   ```

2. **Créer un environnement virtuel** :
   ```bash
   python3 -m venv venv
   ```

3. **Activer l'environnement virtuel** :
   mac/Linux:
   
   ```bash
   source venv/bin/activate
   ```

4. **Installer les dépendances** :

   ```bash
   pip install -r requirements.txt
   ```

### Sur Windows

1. **Cloner le repository** (si ce n'est pas déjà fait) :
   ```bash
   git clone <url-du-repo>
   cd machineLearning
   ```

2. **Créer un environnement virtuel** :
   ```bash
   python -m venv venv
   ```

3. **Activer l'environnement virtuel** :
   ```bash
   venv\Scripts\activate
   ```

4. **Installer les dépendances** :
   ```bash
   pip install -e .
   ```
   ou
   ```bash
   pip install -r requirements.txt
   ```
   (si vous avez un fichier requirements.txt)



### Désactiver l'environnement virtuel

Quand vous avez terminé de travailler sur le projet :

**Sur Mac/Linux** :
```bash
deactivate
```

**Sur Windows** :
```bash
deactivate
```

## 📁 Structure du projet

```
machineLearning/
├── main.py              # Point d'entrée principal
├── pyproject.toml       # Configuration du projet et dépendances
└── README.md           # Ce fichier
```

## 🔧 Développement

Pour contribuer ou développer de nouvelles fonctionnalités :

1. Assurez-vous d'avoir activé l'environnement virtuel
2. Installez les dépendances de développement si nécessaire
3. Créez une nouvelle branche pour vos modifications
4. Testez vos changements avant de les commiter

## 📚 Ressources

- [Documentation scikit-learn](https://scikit-learn.org/stable/)
- [Documentation Python](https://docs.python.org/)

## 💡 Notes

- N'oubliez pas d'activer votre environnement virtuel à chaque fois que vous travaillez sur le projet
- Si vous rencontrez des problèmes d'installation, vérifiez que vous utilisez Python >= 3.13