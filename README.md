# Introduction

Nouvel arrivant sur un projet, 4 tâches vous ont été assigné.

Ces tâches doivent être réalisées dans l'ordre. 

Heureusement votre assistant IA et moi même sont à vos côtés pour vous aider :raising_hand:.

## Créer un projet React afin d'afficher un Hello World en local

- Initier un projet React basique (boilerplate).
- Par le biais d'une commande défini dans votre package json. Vous êtes en capacité d'afficher votre projet dans votre navigateur en l'executant en local.
- Exposer sous format texte un Hello World sur votre page HTML.

:heavy_check_mark: exercice validé si votre Hello World apparaît sur la page html

## Ajouter i18n à votre projet afin de traduire le Hello World en français

- Installer i18n (librairie de traduction) dans votre projet React.
- Configurer i18n afin de pouvoir traduire votre Hello World en Bonjour le monde.
- Selon la langue de votre browser votre page Web affichera la traduction correspondante.
- Bonus: Selon sa localisation votre page Web affichera la traduction correspondante initial. L'utilisateur aura dès lors la capacité de changer sa langue locale directement sur l'application.

## Créer un client http afin de communiquer avec Azure Open AI

- Créer un client http dans votre projet.
- Communiquer avec l'interface qu'on vous a fourni dans une spécification open api.
- Vous avez la possibilité d'importer cette interface dans swagger editor, afin de l'a visualiser et d'interagir en amont avec cette api ou d'utiliser ce lien: https://app.swaggerhub.com/apis/ZIANISAMI0/NeoAPI/1.0.0
- Bonus: Essayer de gérer le contexte en gérant la réponse de notre instance

- USE THIS Bearer: eyJ0eXAiOiJKV1QiLCJub25jZSI6IkM4OWdTbXpvTWUxYTFsZFZWRFhCay1jRENJaV9VSVkzVUFKYW1lNi1ZSmMiLCJhbGciOiJSUzI1NiIsIng1dCI6IjVCM25SeHRRN2ppOGVORGMzRnkwNUtmOTdaRSIsImtpZCI6IjVCM25SeHRRN2ppOGVORGMzRnkwNUtmOTdaRSJ9.eyJhdWQiOiIwMDAwMDAwMy0wMDAwLTAwMDAtYzAwMC0wMDAwMDAwMDAwMDAiLCJpc3MiOiJodHRwczovL3N0cy53aW5kb3dzLm5ldC9lOGI4OGYzZC0yMjJiLTRjZTUtYjlkMS00NmIwZmY5NDY2YTAvIiwiaWF0IjoxNzA1OTE2Mjk2LCJuYmYiOjE3MDU5MTYyOTYsImV4cCI6MTcwNTkyMTc3NCwiYWNjdCI6MCwiYWNyIjoiMSIsImFpbyI6IkFWUUFxLzhWQUFBQW9yZUJTc21uWGp5QWRqVTl3ejRXNEFtMmpHK1o5MHR2Vzl3bWNDTFM3aEIrZjV3MXhZbWFxNFF3MkRQRkN0bW8yMTc4RVl6OWFZMDVBdDFIdXBXdXNyTTIrNmJLQStqWHJsR2R3NHBIUGtBPSIsImFtciI6WyJwd2QiLCJtZmEiXSwiYXBwX2Rpc3BsYXluYW1lIjoiU1NPIElBLUdFTiBQUkVQUk9EIiwiYXBwaWQiOiIxMjUyMjNmMC0zMzUxLTQxN2ItYThkYy1jOWIxZmQyMmFjZjMiLCJhcHBpZGFjciI6IjAiLCJmYW1pbHlfbmFtZSI6IlpJQU5JIiwiZ2l2ZW5fbmFtZSI6IlNhbWkiLCJpZHR5cCI6InVzZXIiLCJpcGFkZHIiOiI4OS45MS41Ljc0IiwibmFtZSI6IlNhbWkgWklBTkkiLCJvaWQiOiI0NDZjNTg0NS0yNzVjLTQ3ZWMtYjRkMS00YTFmMDk3YTY0MTYiLCJvbnByZW1fc2lkIjoiUy0xLTUtMjEtMjY0MTUxMTQ0OC0xODM0MjkzMzY3LTYyMjU4NDU5NS02MDA5NSIsInBsYXRmIjoiMyIsInB1aWQiOiIxMDAzMjAwMjFCNzg2NEUwIiwicmgiOiIwLkFURUFQWS00NkNzaTVVeTUwVWF3XzVSbW9BTUFBQUFBQUFBQXdBQUFBQUFBQUFBeEFOay4iLCJzY3AiOiJVc2VyLlJlYWQgcHJvZmlsZSBvcGVuaWQgZW1haWwiLCJzaWduaW5fc3RhdGUiOlsiaW5rbm93bm50d2siLCJrbXNpIl0sInN1YiI6Imp0ZjllNUE5aDA1T1diaU45aFZ3dUJQUktublQyWWo0YnAwakFuaTdGWGciLCJ0ZW5hbnRfcmVnaW9uX3Njb3BlIjoiRVUiLCJ0aWQiOiJlOGI4OGYzZC0yMjJiLTRjZTUtYjlkMS00NmIwZmY5NDY2YTAiLCJ1bmlxdWVfbmFtZSI6InMuemlhbmlAZ3JvdXBlb25lcG9pbnQuY29tIiwidXBuIjoicy56aWFuaUBncm91cGVvbmVwb2ludC5jb20iLCJ1dGkiOiJFeElEYWptWmZrV21oUkVBb1dCVkFBIiwidmVyIjoiMS4wIiwid2lkcyI6WyJiNzlmYmY0ZC0zZWY5LTQ2ODktODE0My03NmIxOTRlODU1MDkiXSwieG1zX3N0Ijp7InN1YiI6IkJYazc4cmZRX1EteWJuU3h5TkY2TTVTUXNFUUl4TVk2c1J5ZkVabDZaM2cifSwieG1zX3RjZHQiOjE1MjcyNDQyNzUsInhtc190ZGJyIjoiRVUifQ.dy2D4ZCZIqC8dhrCWes15jtrBJvohIYKoWesrohghFml4oOZZZxDpzPF1nR0xc9-_DWPxxGwBwvBYfxpfMVhT7W0Y-op6sMf7vGyChvs6hGOJNuuvJ_TWzx_Pj_WJj5qqC7-H_Uf9PAUbBi-HUY795csFdI-bzLV2vS7Cy7vIk2_e3im3rny0C_E1TRTP3rr6aRED3btSDYFbF57sjObVAnExg2B_kTcv36JYb0IRPyc-erzPx6H9e94L2fS66lTL9-WD_dJebD8SYTJRS8kZEU9hOEWIEagqlL_joZP2UrYAYuJMfp_2vFhiljunerqj3itJddcLgLdhKviEattpA

Important: Un Bearer token est nécessaire, n'hésitez pas à nous le demander afin que l'on vous le communique.

Conseil: le contexte sur une instance d'IA Gen concerne l'historique de toutes les réponses et prompts généré par l'IA Gen. Sur mon premier prompt l'IA ne possède aucun contexte. Sur mon deuxième prompt il faut que ma communication avec l'IA Gen ait en mémoire mon premier prompt et sa première réponse.

## Interprétez les réponses de l'IA via du Markdown

- Sur votre front toutes réponses de l'IA contenant du Markdown doitvent s'afficher en conséquence (ex: les extraits de code sous fonds noir)

## Les réponses de l'IA sous forme de tableau

- Demandez à l'IA de produire un tableau avec des données d'exemple
- Réussir à présenter la réponse retournée par l'IA sous forme de tableau

## Possibilité de copier/coller

- Donnez la possibilité à l'utilisateur de copier les réponses de l'IA via un bouton

## Postez votre projet sur Github en privé et implémentez une CI/CD basique

- Configurez git sur votre projet et postez le sur Github
- Créez une CI/CD avec github actions

## Imaginer une application basée sur cette API

- Avec l'aide de chef de projet et de votre assistant essayez d'imaginer une application autour de ce boilerplate
- Vous disposez d'une totale liberté (amélioration de design, ajout de feature)




