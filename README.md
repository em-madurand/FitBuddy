# FitBuddy – Prototype (Priorité 1)

Ce dépôt présente le **projet PI²** de notre équipe, dédié à la conception d’un prototype de capteur FitBuddy.  
Il couvre principalement :

- La **lecture** de l’IMU (LSM6DSOX) pour récupérer l’accélération et la rotation,  
- La **détection** des répétitions (nombre, temps par répétition, vitesse, amplitude, etc.),
- La **calibration** avec les modules UWB.
- Un **exemple** de transmission via BLE.  

---

## Table des Matières

1. [Contexte du Projet](#contexte-du-projet)  
2. [Structure du Dépôt](#structure-du-dépôt)  
3. [Prérequis](#prérequis)  
4. [Compilation et Flash](#compilation-et-flash)  
5. [Test et Utilisation](#test-et-utilisation)  
6. [Fonctionnalités Priorité 1](#fonctionnalités-priorité-1)  
7. [Évolutions Possibles](#évolutions-possibles)  
8. [Dépôt sur GitHub](#dépôt-sur-github)  
9. [Crédits et Contact](#crédits-et-contact)

---

## Contexte du Projet

Dans le cadre du projet **PI²**, notre équipe développe un capteur capable de s’adapter à diverses machines de musculation.  
**Objectif** : suivre les performances des utilisateurs en temps réel (répétitions, vitesse, temps de pause, etc.).

Ce prototype se concentre sur :
1. La **lecture** des données d’accélération (±2g à ±16g) et éventuellement de gyroscope,
2. La **calibration** avec les modules UWB du capteur. 
3. La **détection** basique des répétitions,  
4. L’**envoie** des données (BLE GATT, logs console).

---

## Structure du Dépôt.
├── README.md        
└── src/
    ├── main.cpp


- **`main.c`** : Point d’entrée du firmware (initialisation IMU, boucle principale). 

---

## Prérequis

---

## Compilation et Flash

1. **Cloner le dépôt** (en local) :  
   ```bash
   git clone https://github.com/Elias792/Projet-Pi2.git
   cd Projet-Pi2
