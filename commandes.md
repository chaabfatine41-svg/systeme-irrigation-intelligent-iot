# Commandes du système d’irrigation intelligent IoT

## 1. Vérifier Python
```bash
python --version
```

## 2. Vérifier Git
```bash
git --version
```

## 3. Préparer le dossier du projet
```bash
mkdir systeme-irrigation-iot
cd systeme-irrigation-iot
```

## 4. Éléments du système
- Capteur d’humidité du sol : mesure l’humidité.
- Microcontrôleur : traite les mesures.
- Pompe à eau : assure l’irrigation.
- Programme de contrôle : décide quand démarrer et arrêter la pompe.

## 5. Logique de fonctionnement
1. Lire la valeur du capteur.
2. Comparer cette valeur au seuil d’humidité choisi.
3. Si le sol est sec, activer la pompe.
4. Si l’humidité est suffisante, arrêter la pompe.

**Remarque :** ces commandes et étapes sont indicatives. Elles ne prouvent pas que le système a été monté ou testé.
