# Youth Camp Registration & Analytics Dashboard

**English / [Français](#francais)**

---

## English Version <a name="english"></a>

### Objective
Build a complete digital system to collect, centralize, and visualize youth camp registration data.

### Context
Before this project, registrations were done manually on paper, leading to errors and slow processing. The goal was to streamline the workflow for multiple churches participating in the summer 2024 youth program.

### Project Timeline & Workflow
1. **Data Collection:**  
   Participants were registered via a custom KoboToolbox form over a 2-week period.
2. **Data Export:**  
   After the registration period, the data was exported in CSV format.
3. **Data Cleaning:**  
   Python scripts were used to preprocess, standardize, and anonymize the dataset, handling missing values, encoding issues, and duplicates.
4. **Google Sheets Transformation:**  
   Cleaned data was imported into Google Sheets for intermediate storage and minor manipulations.
5. **Dashboard Creation:**  
   Interactive dashboards were built with Looker Studio to visualize age groups, gender ratios, church participation, and session attendance.
6. **Delivery:**  
   Final dashboards were provided to church leaders for easy monitoring of camp participation.

### Technologies Used
- [KoboToolbox](https://www.kobotoolbox.org/) for structured data collection
- [Google Sheets](https://www.google.com/sheets/about/) for intermediate storage
- [Looker Studio](https://lookerstudio.google.com/) for dashboarding
- Python for data cleaning and validation

### Results
- 50% reduction in registration processing time  
- Real-time data visualization for organizers  
- Enhanced data reliability and easy shared access

### Key Features
- **Structured Data Collection:** Clean, validated, uniform input via KoboToolbox.  
- **Automated Data Cleaning:** Python scripts handled missing values, encoding, duplicates, and anonymization.  
- **Interactive Visual Dashboard:** Looker Studio dashboards provided insights on age, gender, church participation, and attendance.  
- **Privacy-Preserving Synthetic Dataset:** Original data replaced with synthetic values for confidentiality.

### Links
- 🌐 [KoboToolbox Form](https://ee.kobotoolbox.org/x/8fort8cA)  
- 📊 [Looker Studio Dashboard](https://lookerstudio.google.com/reporting/78e4dbfe-1ee5-4dc0-8d80-fd33e0355545)  
- 📄 [Full Report (PDF)](./docs/rapport_complet_EN.pdf)  

### Preview

#### Form
![Form](./images/colonie_3.png)

#### Dashboard
![Dashboard](./images/colonie_2.png)

### Lessons Learned
- Structuring an end-to-end data pipeline from collection to visualization  
- Training non-technical users to interact with digital tools  
- Presenting data in a way that is operationally actionable

---

## Français <a name="francais"></a>

**Français / [English](#english)**

### Objectif
Mettre en place un système numérique complet pour collecter, centraliser et visualiser les données d'inscription des campeurs.

### Contexte
Avant ce projet, les inscriptions étaient réalisées manuellement sur papier, générant des erreurs et ralentissant l'organisation. L'objectif était de fluidifier le processus pour plusieurs églises participant au programme jeunesse de l'été 2024.

### Timeline & Workflow
1. **Collecte des données :**  
   Les participants ont été inscrits via un formulaire KoboToolbox sur une période de 2 semaines.
2. **Export des données :**  
   À la fin de la période d’inscription, les données ont été exportées en CSV.
3. **Nettoyage des données :**  
   Scripts Python pour prétraitement, standardisation, anonymisation, gestion des valeurs manquantes, encodages et doublons.
4. **Transformation en Google Sheets :**  
   Les données nettoyées ont été importées dans Google Sheets pour un stockage intermédiaire et quelques manipulations.
5. **Création du tableau de bord :**  
   Tableaux de bord interactifs construits avec Looker Studio pour visualiser les groupes d’âge, le ratio hommes/femmes, la participation des églises et la fréquentation des sessions.
6. **Livraison :**  
   Les tableaux de bord finaux ont été remis aux responsables pour faciliter le suivi des participants.

### Technologies utilisées
- [KoboToolbox](https://www.kobotoolbox.org/) pour la collecte des données
- [Google Sheets](https://www.google.com/sheets/about/) pour le stockage intermédiaire
- [Looker Studio](https://lookerstudio.google.com/) pour le dashboard
- Python pour le nettoyage et la validation des données

### Résultats
- Réduction de 50% du temps de traitement des inscriptions  
- Visualisation des données en temps réel pour les organisateurs  
- Meilleure fiabilité et accès partagé aux données

### Fonctionnalités clés
- **Collecte structurée des données :** Formulaire KoboToolbox pour des saisies propres et uniformes  
- **Nettoyage automatisé :** Scripts Python gérant valeurs manquantes, encodages, doublons et anonymisation  
- **Tableau de bord interactif :** Loocker Studio fournit des informations sur l’âge, le sexe, la participation des églises et la fréquentation  
- **Données synthétiques pour la confidentialité :** Les données originales ont été remplacées pour protéger la vie privée

### Liens
- 🌐 [Formulaire KoboToolbox](https://ee.kobotoolbox.org/x/8fort8cA)  
- 📊 [Dashboard Looker Studio](https://lookerstudio.google.com/reporting/78e4dbfe-1ee5-4dc0-8d80-fd33e0355545)  
- 📄 [Rapport complet (PDF)](./docs/rapport_complet_FR.pdf)  

### Aperçu

#### Formulaire
![Formulaire](./images/colonie_3.png)

#### Dashboard
![Dashboard](./images/colonie_2.png)

### Enseignements
- Structurer un flux de données de la collecte à la visualisation  
- Former des utilisateurs non techniques à un outil numérique  
- Adapter la présentation des données aux besoins opérationnels
