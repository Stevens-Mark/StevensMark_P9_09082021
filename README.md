![Billed](/src/assets/images/Billed.jpg)

[![Netlify Status](https://api.netlify.com/api/v1/badges/b1f7b14e-fecb-44d6-abb6-352f66b693b5/deploy-status)](https://app.netlify.com/sites/billed/deploys)

# OPENCLASSROOMS PROJECT 9 *(English)*

Open website at [Billed](https://billed.netlify.app/)

## Debug and test an HR SaaS

At Billed, a company that produces Saas solutions for human resources teams.


### Scenario
A colleague on the expense report feature team, has left the company before completing the application. In one week, the team has to show the working solution to the whole company. The lead developer of the feature team, asked for support to meet the deadline.
Feature description - There are two user paths on this feature: on the HR administrator side and on the employee side. The back-end is ready (in alpha version). On the front-end, the HR administrator path is complete, fully tested and debugged.

### Objective
- What remains to be done is to make the employee path more reliable and improve it.
- Fix the bugs identified in the bug report provided by Jest. (see the Kaban)
- Fix the bugs identified by Leila our QA on the employee route. (see the Kaban)
- Add unit and integration tests for the Bills and NewBill files: these tests will allow the elimination of these bugs and avoid any regression during the next evolution of the solution.
- Ensure 100% branch coverage (apart from calls to the firebase back-end: these are indicated as comments in the code). 
- E2E Test - Make an End-to-End test plan. Take inspiration from the End-to-End plan already written on the HR administrator path.


### Resources
- [Kaban](https://www.notion.so/a7a612fc166747e78d95aa38106a55ec?v=2a8d3553379c4366b6f66490ab8f0b90)
- Further information can be found in the folder `Project Briefs`

## Skills

- [x] Writing unit tests with JavaScript
- [x] Writing integration tests with JavaScript
- [x] Debug a web application with the Chrome Debugger
- [x] Write a manual end-to-end test plan



**How to launch the application locally** :

- Clone the project:

`git clone https://github.com/Stevens-Mark/StevensMark_P9_09082021.git`


- Go to the cloned repo:

`P9_stevens_mark`

- Install the npm packages : 


`$ npm install`


- Launch the application :

`$ live-server`


Then go to: `http://127.0.0.1:8080/`


**How to run all tests locally with Jest:**

`$ npm run test`

**How to run a single test:**

Install jest-cli:

```
$npm i -g jest-cli
$jest src/__tests__/your_test_file.js
```

**How to see the test coverage:**

`http://127.0.0.1:8080/coverage/lcov-report/`




# OPENCLASSROOMS PROJECT 9 *(Francais)*

Ouvrir le site web ?? [Billed](https://billed.netlify.app/)

## D??buggez et testez un SaaS RH

Chez Billed, une entreprise qui produit des solutions Saas destin??es aux ??quipes de ressources humaines.

### Sc??nario
Un coll??gue de l'??quipe charg??e de la fonctionnalit?? de rapport de d??penses a quitt?? l'entreprise avant d'avoir termin?? l'application. Dans une semaine, l'??quipe doit montrer la solution fonctionnelle ?? toute l'entreprise. Le d??veloppeur principal de l'??quipe charg??e de la fonctionnalit?? a demand?? de l'aide pour respecter le d??lai.
Description de la fonctionnalit?? - Il y a deux chemins d'acc??s ?? cette fonctionnalit?? : du c??t?? de l'administrateur RH et du c??t?? de l'employ??. Le back-end est pr??t (en version alpha). Sur le front-end, le chemin de l'administrateur RH est complet, enti??rement test?? et d??bogu??.

### Objectif
- Il reste ?? fiabiliser et am??liorer le parcours employ??.
- Corriger les bugs identifi??s dans le rapport de bug fourni par Jest. (voir le Kaban)
- Corriger les bugs identifi??s par Leila notre QA sur le parcours de l'employ??. (voir le Kaban)
- Ajouter des tests unitaires et d'int??gration pour les fichiers Bills et NewBill : ces tests permettront d'??liminer ces bugs et d'??viter toute r??gression lors de la prochaine ??volution de la solution.
- Assurer une couverture de branche ?? 100% (en dehors des appels au back-end de firebase : ceux-ci sont indiqu??s en commentaire dans le code). 
- Test E2E - R??alisez un plan de test End-to-End. Inspirez-vous du plan de bout en bout d??j?? ??crit sur le parcours de l'administrateur RH.

### Resources
- [Kaban](https://www.notion.so/a7a612fc166747e78d95aa38106a55ec?v=2a8d3553379c4366b6f66490ab8f0b90)
- Vous trouverez plus d'informations dans le dossier `Project Briefs`.

## Skills

- [x] Ecrire des tests unitaires avec JavaScript
- [x] Ecrire des tests d'int??gration avec JavaScript
- [x] D??bugger une application web avec le Chrome Debugger
- [x] R??diger un plan de test end-to-end manuel



**Comment lancer l'application localement** :

- Clonez le projet :

`git clone https://github.com/Stevens-Mark/StevensMark_P9_09082021.git`


- Allez dans le repo clon?? :

`P9_stevens_mark`

- Installez les paquets npm : 


`$ npm install`


- Lancez l'application :

`$ live-server`


Allez ensuite sur : `http://127.0.0.1:8080/`


**Comment ex??cuter tous les tests en local avec Jest:**

`$ npm run test`

**Comment ex??cuter un seul test :**

Installez jest-cli :

```
$npm i -g jest-cli
$jest src/__tests__/votre_fichier_test.js
```

**Comment voir la couverture des tests:**

`http://127.0.0.1:8080/coverage/lcov-report/`



