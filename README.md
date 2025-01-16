# Blueprints pour les challenges Hilo
Blueprint pour Home Assistant pour utiliser l'intégration Hilo facilement. Vous allez être en mesure d'automatiser la température cible de vos thermostats pour augmenter vos récompenses Hilo. Vous pouvez choisir de participer aux défis du matin et/ou aux défis du soir. Vous pourrez aussi controller votre chauffe-eau et d'autre équipement de type "switch" comme une laveuse, sécheuse ou chargeur de véhicule électrique. 

Ce blueprint est basé sur ceux de @Eradash.

## Configuration
### L'application Hilo
Pour un fonctionnement optimal, désactivez la prise en charge des thermostats pendant les défis dans l'application Hilo. Vous participerez tout de même aux défis et recevrez les récompenses. Il est également recommandé de ne pas avoir de scènes programmées. Cela s'applique également à tous les autres thermostats non-Hilo, qui pourraient être gérés par ces automatisations.

### Intégration Hilo
Vous allez avoir besoin de l'intégration [Hilo](https://github.com/dvd-dev/hilo) pour que ces Blueprints fonctionnent

**La période d'appréciation doit être de 3 heures si désiré. Vous pouvez le mettre dans la configuration de l'intégration Hilo**

**La période de refroidissement avant la période d'appréciation doit être de 1 heures si désiré. Vous pouvez le mettre dans la configuration de l'intégration Hilo**

### Installation des "Blueprints"
Installez le blueprints avec ces liens:

* Défi automatiques: [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Farim215%2Fha-hilo-blueprints%2Fsingle-file%2Fdefis_hilo_automatiques.yaml)


## Contribution

Si vous voulez améliorer, gênez-vous pas! Présentement, j'aimerais ajouter une manière de mieux contrôller une thermopompe, pour réduire les coûts liés au pré-chauffage. Cela doit être configurable avec une valeur limite de température extérieure.

**Contributeurs:**

* @Eradash
* @arim215
* @jrobichaud
* @jpbaril

## À faire:

Si vous avez des idées, partagez-les.

* Ajouter des notifications quand des défis sont planifiés/débutent/finissent