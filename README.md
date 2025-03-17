# Application d'Analyse des Releases Copado

Cette application Salesforce est conçue pour analyser et comparer les dépendances entre les releases Copado dans un environnement Salesforce.

## Fonctionnalités

- Analyse détaillée des dépendances entre les releases Copado
- Interface utilisateur Lightning Web Component responsive
- Visualisation des relations entre les différents composants d'une release
- Support pour les objets standard Copado Release (`copado__Release__c`)

## Structure du Projet

- `force-app/main/default/classes/` : Contient la logique Apex qui gère l'analyse des dépendances
  - `CopadoReleasesDependancies.cls` : Classe principale pour l'analyse des dépendances
  - `CopadoReleasesDependanciesTest.cls` : Tests unitaires pour la classe principale
  
- `force-app/main/default/lwc/` : Contient les composants Lightning Web Components
  - `copadoReleasesDependancieslwc` : Interface utilisateur pour visualiser les dépendances


## Utilisation

Ce composant peut être ajouté aux pages suivantes:
- Pages d'enregistrement de Release Copado
- Pages d'application Lightning
- Pages d'accueil Lightning

## Configuration

Dans le générateur d'applications Lightning, vous pouvez configurer:
- **Enable HTML Links in Table**: Activez cette option pour permettre des liens HTML cliquables dans les tableaux de résultats

## Développement

Pour contribuer au développement:

1. Configurez votre environnement Salesforce DX
2. Effectuez vos modifications dans une branche dédiée
3. Exécutez les tests: `npm run test:unit`
4. Soumettez une pull request

## Support et Maintenance

Pour toute question ou problème concernant cette application, veuillez contacter l'équipe de développement Salesforce.