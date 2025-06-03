# Gestion de stock - Pharmacie

✅ Travail à faire

🔎 1. Normalisation des données

    Uniformise les noms des médicaments pour éviter les doublons dus à des variations (ex : "doliprane" vs "Doliprane").

    Standardise les formes (ex : "sirop", "Sirop", "Pommade", "Comprimé", etc.).

    Harmonise les noms des fournisseurs (majuscule, fautes de frappe éventuelles…).

📤 2. Suppression des doublons

    Identifie et supprime les doublons exacts ou quasi-identiques en te basant sur plusieurs colonnes (ex : Nom Médicament, Dosage, Forme, Code Produit).

🧮 3. Vérification des valeurs numériques

    Détecte et corrige les valeurs non numériques dans "Prix Unitaire (€)".

📅 4. Contrôle des dates

    Supprime ou corrige les lignes avec des dates de péremption erronées.

🟨 5. Création de nouvelles colonnes

    Crée une colonne "À Réapprovisionner" en fonction du stock et du seuil d’alerte.

    Extrait le mois de la date de péremption en format texte (ex : “Mars”, “Avril”…).

    Crée une colonne "Année Péremption" pour faciliter les tris chronologiques.

🗂️ 6. Traitement des observations

    Standardise les mentions comme “Promo” ou “Rupture partielle” pour faciliter les regroupements.

📊 7. Analyse exploratoire (facettes)

    Crée des facettes sur les prix, le stock, les dates, etc., pour repérer rapidement les valeurs aberrantes ou incohérentes.

    Identifie les médicaments dont la péremption est proche (facette par date)
![image](https://github.com/user-attachments/assets/75b8eca7-15aa-465b-af0f-66b561615dae)




