# Simulation numérique 3D de la pollution atmosphérique liée au trafic routier

## 📌 Description du projet

Ce dépôt contient le code source de notre **simulation numérique 3D** visant à modéliser la dispersion de la pollution atmosphérique liée au trafic routier en milieu urbain dense.

Le projet s’inscrit dans un contexte de recherche sur **la qualité de l’air en zone urbaine**, où le trafic routier constitue l’une des principales sources d’émissions polluantes (notamment le NO₂).  
L’objectif est de développer un **modèle 3D dynamique** capable de prédire la dispersion des polluants en intégrant les **variations spatio-temporelles du vent** et les effets urbains complexes (effet canyon, cisaillement du vent).

---

## 🎯 Objectifs

- Simuler la dispersion 3D des polluants atmosphériques en milieu urbain
- Prendre en compte :
  - la densité du trafic routier
  - la source de pollution associée
  - la dynamique du vent (Navier–Stokes)
  - l’advection et la diffusion des polluants
- Étudier l’impact du **cisaillement du vent** et de la géométrie urbaine
- Fournir une **cartographie spatio-temporelle** des concentrations polluantes

---

## 🧠 Modèle physique et mathématique

Le modèle repose sur un **couplage spatio-temporel 3D** comprenant :

- Équations de Navier–Stokes (air incompressible)
- Équation d’advection–diffusion pour le transport des polluants
- Source d’émission liée au trafic routier
- Prise en compte des effets 3D :
  - hauteur des bâtiments
  - effet canyon urbain
  - cisaillement vertical du vent

Le polluant étudié est le **NO₂**.

---

## 🛠️ Méthodes numériques et outils

- **Méthode des éléments finis**
- Résolution des équations couplées sur un maillage 3D tétraédrique
- Logiciel utilisé : **FreeFem++**
  - Basé sur le C++
  - Open source
  - Adapté aux géométries urbaines complexes et aux simulations 3D

---

## 🌍 Zone d’étude

- Milieu urbain dense
- Type : rue canyon
- Exemple étudié : **Boulevard Haussmann (Paris)**
- Hauteur moyenne des bâtiments : ~20 m

---

## 📁 Contenu du dépôt

- Code de simulation FreeFem++  
- Scripts de résolution numérique  
- Fichiers de paramètres (géométrie, vent, trafic, polluant)  
- Résultats de simulation (selon avancement du projet)

---

## 🚀 Vision finale

À terme, ce projet vise à fournir :
- Des **simulations 3D dynamiques réalistes** de la pollution urbaine
- Une aide à l’identification des **zones à fort risque de pollution**
- Un outil d’aide à la décision pour des **stratégies d’urbanisme** et de gestion de la qualité de l’air

---

## 👥 Équipe

- Annabelle Fautrad  
- Clara Mourot  
- Marie Léona Nomo Ngah  
- Jade Parrilla  
- Cécilia Zhu  

---

## 📚 Références et ressources

Les principales références scientifiques et techniques utilisées sont détaillées dans la présentation du projet et incluent :
- Modèles CFD urbains
- Études sur la dispersion des polluants en rue canyon
- Documentation officielle FreeFem++

---

## 📄 Licence

Projet académique – usage pédagogique et scientifique.
