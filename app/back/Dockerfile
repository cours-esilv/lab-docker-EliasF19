# Étape 1: Image de base Python
FROM python:3.9

# Étape 2: Définir le répertoire de travail
WORKDIR /app/back

# Étape 3: Copier requirements.txt
COPY requirements.txt .

# Étape 4: Installer les dépendances
RUN pip install -r requirements.txt

# Étape 5: Copier le reste de l'application
COPY . .

# Étape 6: Exposer le port 5000
EXPOSE 5000

# Étape 7: Définir la commande par défaut
CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]
