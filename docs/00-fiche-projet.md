 # Fiche projet — Équipe NN 22

> Livrable L2 · Jalon J1 (samedi 29 août 2026) · validée par l'encadreur référent.
> Aucune fabrication n'est autorisée avant la validation de ce jalon.

## 1. Détecteur de qualité de l'air et de température en Fablab et en classe (D22)

Le dispositif D22, est un dispositif qui permettra de mesurer la qualité de l'air et l'état de la température dans les Fablab et dans les salles de classe ou locaux hermetiquement fermé au seins de l'éablissement

## 2. Besoin et bénéficiaires
Dans les centres de formation technique et les écoles scientifiques, les salles de cours, laboratoires, ateliers et salles informatiques sont des espaces où il est utile de suivre les conditions ambiantes. Comment réaliser un dispositif simple, autonome et pédagogique permettant de surveiller la qualité de l’air, la température, l’humidité et la présence, tout en réduisant la consommation de l’affichage et en fournissant une alerte en cas de condition anormale ? 

## 3. Objectifs d'apprentissage

Le présent projet propose un prototype embarqué capable de mesurer plusieurs paramètres, de détecter la présence d’une personne, d’afficher les informations sur un écran OLED et de déclencher une alarme sonore lorsqu’un seuil programmé est dépassé. L’alimentation sur deux batteries 18650 permet de présenter un système autonome.

les objectifs observables rattachés au programme officiel, sont les suivants:

- Mesurer un indicateur de qualité de l’air avec le MQ-135.
- Mesurer la température et l’humidité avec le DHT22.
- Détecter une présence par mesure de distance avec le HC-SR04.
- Afficher les informations sur un OLED 0,96″ à interface I²C.
- Allumer l’affichage en présence et l’éteindre après une période d’absence.
- Déclencher un buzzer lorsque des seuils programmés sont dépassés.
- Assurer l’alimentation du prototype avec deux cellules 18650 de 3,7 V et 3000 mAh.
- Intégrer un interrupteur/bouton d’allumage et des résistances de protection/adaptation.


## 4. Description du dispositif

### Le dispositif permet de :
- Mesurer la concentration du dioxyde de carbone dans l'air
- Mesurer la température dans les salles.
- Afficher trois niveau d'alerte de concentration et pour le dioxyde de carbonne et pour la température
- Fonctionner hors réseau
 ###  L'élève peut :
 
 - Explioter les données pour ses prises de décision.
 · croquis ou esquisse annotée
(versée dans `docs/medias/`).

## 5. Architecture technique presenté

### a. Capteurs 
- Un capteur de dioxyde de carbone à mesure infra rouge non dispersive
- Un capteur de température
### b. actionneurs
- Les Leds
- Les bezzeurs 
- L'écran
### c· liaison 
- Le PCB
- Les cables
### d· application 
- Fusion 360
- Bambu studio
- Xtool
- Vs code
- mblock

### f· procédés de fabrication envisagés
- Conception 3d
- Impression additive
- Impression soustractive
- Impression traditionnelle
- cabalge
- Teste du dispositif
- l'application

(au moins trois procédés distincts, exigence ET-FAB-02).

## 6. Rôle des élèves

Position sur le continuum POUR / AVEC / PAR et extension PAR décrite (exigence EP-03).

## 7. Ancrage réseau et implantation

Lab de rattachement 
- CRIT
- Etablissement

lieu d'usage 
- Fablab et salle de Classe

conditions matérielles de la salle.
- Salle hermétiquement fermée

## 8. Périmètre

| | Contenu |
|---|---|
| Dans la v1.0  | (Boîtier Fonctionnel) |
| En option (Avancé / Expert):  | contrôle de la température, de l'aération et la notification automatique |
| Explicitement exclu  | La reprogrammation via le réseau|

## 9. Risques et parades

| Risque | Type | Parade |
|---|---|---|
| Défaut de capteur| technique | Teste et rédondance |
| Insuffisance de temps| calendrier | Faire des prototypes très simple|
| Manque de compétance | pédagogique | Sous traitance|

## 10. Budget matière estimé

Grandes masses en FCFA, au regard de la dotation : 60 000 FCFA

## 11. Licences et diffusion

Licences choisies et motivation
 : Open source
 
 Accord de l'équipe pour la mise en avant réseau : Poster sur Github public

## Exemptions demandées

- [ ] ET-FAB-06 (moulage) — justification :
- [ ] ET-MEC-01 (fonction motorisée) — justification :
