## Workshop Angular
### Librairie externe et comment l'utiliser
•	Créer le projet « librairie » et le générer.  
  o	ng build test-library  
  o	cd dist/test-library  
  o	npm publish  
Puis, l’ajouter dans les dépendances package.json du projet ou nous voulons utiliser la librairie.  
>>>
 "dependencies": {  
        "@angular/animations": "^5.2.0",  
        "@angular/common": "^5.2.0",  
        "@angular/compiler": "^5.2.0",  
        "@angular/core": "^5.2.0",  
        ...,  
        "@test-library": "^0.1.0"  
  }, 
>>>

Et npm update

### Package Manager   
#### Npm
#### Yarn
### Testing
#### Tests unitaires
#### Tests end to end (e2e)
### Couverture du code
#### TSLint
#### SonarLint
### Exemples de code
#### Pipes
#### Directives
### Déploiement
ng build –prod -> --prod important car cela compresse les fichiers qui sont buildés.
