# Scraping des Classements des Pilotes de Formule 1  

Ce projet a pour objectif de scraper les classements annuels des pilotes de Formule 1 depuis 1950, de structurer ces données pour des analyses, et de les visualiser dans Power BI pour une meilleure interprétation.  

---

## 🏎️ **Description du Projet**  
La Formule 1 est une discipline sportive emblématique avec une riche histoire et des données bien structurées. Ce projet se concentre sur l'extraction des classements finaux des pilotes pour chaque saison depuis 1950, l'année de création du championnat du monde de F1.  

Les données collectées incluent :  
- L'année de la saison  
- Le rang du pilote dans le classement  
- Le nom du pilote  
- Le nombre de points accumulés  

Ces informations seront ensuite utilisées pour des visualisations interactives dans Power BI afin d'analyser les performances historiques des pilotes et des équipes.  

---

## 🚀 **Fonctionnalités**  
- **Recherche des sources de données** : Identifier et valider les sites web fiables contenant les classements de la F1 (par exemple, *formula1.com* ou *Wikipedia*).  
- **Scraping des classements** : Collecter les données des pilotes pour chaque saison depuis 1950.  
- **Structuration des données** : Organiser les informations dans un format tabulaire (CSV ou JSON).  
- **Visualisation dans Power BI** : Importer les données dans Power BI pour créer des rapports interactifs et des graphiques dynamiques.  

---

## 🛠️ **Prérequis**  

### **1. Logiciels et Outils**  
- **Java Development Kit (JDK 8 ou supérieur)**  
- **Power BI Desktop** (pour la visualisation)  
- Un IDE Java tel que IntelliJ IDEA, Eclipse ou VS Code (avec extensions Java)  

### **2. Bibliothèques Java nécessaires**  
Les bibliothèques requises pour ce projet sont :  
- **Jsoup** : pour effectuer le scraping des pages web.  
- **OpenCSV** : pour écrire les données dans un fichier CSV.  

Ajoutez-les à votre projet avec Maven ou Gradle :  

#### Maven  
```xml
<dependencies>
    <dependency>
        <groupId>org.jsoup</groupId>
        <artifactId>jsoup</artifactId>
        <version>1.15.4</version>
    </dependency>
    <dependency>
        <groupId>com.opencsv</groupId>
        <artifactId>opencsv</artifactId>
        <version>5.7.1</version>
    </dependency>
</dependencies>
