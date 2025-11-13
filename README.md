# Guide pour cette matière

Guide rapide pour ce cours de ML for social sciences du master IREN. Ce guide servira à installer ce repo, lancer un environnement virtuel, installer les packages sur Mac et Windows, puis faire les premiers projets. Enjoy !

## 📋 Prérequis

- Python 3.12 (installer avec uv)
- uv (gestionnaire de versions Python et de packages)
- git (pour cloner le repository)

### Installation de uv

**Sur Mac/Linux** :
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Sur Windows** :
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### Installation de Python 3.12 avec uv

Une fois uv installé, installez Python 3.12 :

```bash
uv python install 3.12
```

Pour utiliser Python 3.12 par défaut dans votre projet :

```bash
uv python pin 3.12
```

Pour vérifier la version de Python utilisée :

```bash
uv python list
```

## 🚀 Installation

### Sur Mac

1. **Cloner le repository** (si ce n'est pas déjà fait) :
   ```bash
   git clone https://github.com/lwi00/machineLearningForSocialSciences.git
   cd machineLearningForSocialSciences
   ```

2. **Créer un environnement virtuel avec Python 3.12** :
   
   Avec uv (recommandé) :
   ```bash
   uv venv --python 3.12
   ```
   
   Ou avec Python standard :
   ```bash
   python3 -m venv venv
   ```

3. **Activer l'environnement virtuel** :
   
   **Mac/Linux** :
   ```bash
   source venv/bin/activate
   ```
   
   **Windows** :
   ```bash
   venv\Scripts\activate
   ```

4. **Installer les dépendances** :

   Avec uv (recommandé) :
   ```bash
   uv pip install -r requirements.txt
   ```
   
   Ou avec pip standard :
   ```bash
   pip install -r requirements.txt
   ```

### Sur Windows

1. **Cloner le repository** (si ce n'est pas déjà fait) :
   ```bash
   git clone https://github.com/lwi00/machineLearningForSocialSciences.git
   cd machineLearningForSocialSciences
   ```

2. **Créer un environnement virtuel avec Python 3.12** :
   
   Avec uv (recommandé) :
   ```bash
   uv venv --python 3.12
   ```
   
   Ou avec Python standard :
   ```bash
   python -m venv venv
   ```

3. **Activer l'environnement virtuel** :
   ```bash
   venv\Scripts\activate
   ```

4. **Installer les dépendances** :

   Avec uv (recommandé) :
   ```bash
   uv pip install -r requirements.txt
   ```
   
   Ou avec pip standard :
   ```bash
   pip install -r requirements.txt
   ```



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
- Si vous rencontrez des problèmes d'installation, vérifiez que vous utilisez Python 3.12
- Avec uv, vous pouvez utiliser `uv run` pour exécuter des commandes dans l'environnement virtuel sans l'activer manuellement