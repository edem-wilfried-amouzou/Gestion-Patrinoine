# Gestion-Patrimoine
Application web développée avec Django, visant à permettre à un entreprise de pouvoir enregister ses parimoines.

## Fonctionalités
- Permettre une connexion sécurisé à l'application.
- Permettre à un utilisateur d'enregister le patrimoine et ses coordonnés GPX.

## Technologies utilisées
- Python v3.14.2
- Django v6.0.2
- MySQL v8.0.29

## Installation et configuration
### 1. Cloner le dépôt

```
git clone https://github.com/edem-wilfried-amouzou/Gestion-Patrimoine.git
cd Gestion-Parimoine

```
### 2. Créer et activer un environnement virtuel
#### Linux/Mac
```
python3 -m venv .venv

source .venv/bin/activate  #Linux/Mac

```
#### Windows(CMD)
```
python -m venv .venv

.venv\Scripts\activate

```
#### Windows (PowerShell)
```
python -m venv .venv

.venv\Scripts\Activate.ps1

```

> [!Warning]
> Si PowerShell bloque l’exécution (Error : Activate.ps1 cannot be loaded because running scripts is disabled)


```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
.venv\Scripts\Activate.ps1

```
### 3. Installer les dépendances
```
pip install -r requirement.txt

```
### 3. Lancer le serveur
```
python manage.py runserver

```
Accéder à l’application via :
http://127.0.0.1:8000
> [!Warning]
> L'adresse url est à verifier dans les logs issus du lancement du serveur.




