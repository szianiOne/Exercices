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
- Vous avez la possibilité d'importer cette interface dans swagger editor, afin de l'a visualiser et d'interagir en amont avec cette api ou d'utiliser ce lien: https://app.swaggerhub.com/apis/SZIANI/AZURE_OPEN_API_BY_ONEPOINT/1.0.0
- Bonus: Essayer de gérer le contexte en gérant la réponse de notre instance

- USE THIS Bearer: ```eyJ0eXAiOiJKV1QiLCJub25jZSI6IklySDNvLTNueXZDWW1vd1JVaFIyR1pDYXlpckphS2RfUnB6TzVfSjQ2YUEiLCJhbGciOiJSUzI1NiIsIng1dCI6IlQxU3QtZExUdnlXUmd4Ql82NzZ1OGtyWFMtSSIsImtpZCI6IlQxU3QtZExUdnlXUmd4Ql82NzZ1OGtyWFMtSSJ9.eyJhdWQiOiIwMDAwMDAwMy0wMDAwLTAwMDAtYzAwMC0wMDAwMDAwMDAwMDAiLCJpc3MiOiJodHRwczovL3N0cy53aW5kb3dzLm5ldC9lOGI4OGYzZC0yMjJiLTRjZTUtYjlkMS00NmIwZmY5NDY2YTAvIiwiaWF0IjoxNzAyMzExMzI1LCJuYmYiOjE3MDIzMTEzMjUsImV4cCI6MTcwMjMxNTcyOSwiYWNjdCI6MCwiYWNyIjoiMSIsImFpbyI6IkFWUUFxLzhWQUFBQVFSNHphVkF6bDlndXNHTkdZRVBER2MzeUU4Y24rOFNRa3lBbDN3d005TFV3Wm5jWElNL1picjVINHlaa2dNNjk5YjE3OFdJZTB2bktINlhrNU1wY0txQWZGZHZuTE5lWGVUYXI3UEpLMmJNPSIsImFtciI6WyJwd2QiLCJtZmEiXSwiYXBwX2Rpc3BsYXluYW1lIjoiU1NPIElBLUdFTiBQUkVQUk9EIiwiYXBwaWQiOiIxMjUyMjNmMC0zMzUxLTQxN2ItYThkYy1jOWIxZmQyMmFjZjMiLCJhcHBpZGFjciI6IjAiLCJmYW1pbHlfbmFtZSI6IlpJQU5JIiwiZ2l2ZW5fbmFtZSI6IlNhbWkiLCJpZHR5cCI6InVzZXIiLCJpcGFkZHIiOiI4OS44My4xMjYuMTM3IiwibmFtZSI6IlNhbWkgWklBTkkiLCJvaWQiOiI0NDZjNTg0NS0yNzVjLTQ3ZWMtYjRkMS00YTFmMDk3YTY0MTYiLCJvbnByZW1fc2lkIjoiUy0xLTUtMjEtMjY0MTUxMTQ0OC0xODM0MjkzMzY3LTYyMjU4NDU5NS02MDA5NSIsInBsYXRmIjoiMyIsInB1aWQiOiIxMDAzMjAwMjFCNzg2NEUwIiwicmgiOiIwLkFURUFQWS00NkNzaTVVeTUwVWF3XzVSbW9BTUFBQUFBQUFBQXdBQUFBQUFBQUFBeEFOay4iLCJzY3AiOiJVc2VyLlJlYWQgcHJvZmlsZSBvcGVuaWQgZW1haWwiLCJzdWIiOiJqdGY5ZTVBOWgwNU9XYmlOOWhWd3VCUFJLbm5UMllqNGJwMGpBbmk3RlhnIiwidGVuYW50X3JlZ2lvbl9zY29wZSI6IkVVIiwidGlkIjoiZThiODhmM2QtMjIyYi00Y2U1LWI5ZDEtNDZiMGZmOTQ2NmEwIiwidW5pcXVlX25hbWUiOiJzLnppYW5pQGdyb3VwZW9uZXBvaW50LmNvbSIsInVwbiI6InMuemlhbmlAZ3JvdXBlb25lcG9pbnQuY29tIiwidXRpIjoiTmlVUHFSaVNSMEdzazI4Q3d1QmZBQSIsInZlciI6IjEuMCIsIndpZHMiOlsiYjc5ZmJmNGQtM2VmOS00Njg5LTgxNDMtNzZiMTk0ZTg1NTA5Il0sInhtc19zdCI6eyJzdWIiOiJCWGs3OHJmUV9RLXliblN4eU5GNk01U1FzRVFJeE1ZNnNSeWZFWmw2WjNnIn0sInhtc190Y2R0IjoxNTI3MjQ0Mjc1LCJ4bXNfdGRiciI6IkVVIn0.NGUFr4BDG9rjvZ5Dqmj_iLgH7UHzpUYrzDiWzZWmqBHv3Pen1SC1Oo-un-H0s60oCODPGcx9dyOcbLdjxpDuquedUxgBCMoLEu3LRoWUJpZqa4Vv0kC3C4fQLCreHAG8KvXA8K7IDjesOFHzDsNmZUHiEn8WDyuUF0JJNm2pOE8AMl3_xVNwChzqag4uKBMpa0EhOvFSYSdQJxsA-YzgzN8iXlRg7g9zzRjHEaihdTSf0ToEYeSMI9iyMajZZCuldYP4ojZYsFQ9dzlJfhOPer20sHnoPPfJIr-Q2R6cFX6Sbog9Ak3PhXx3gaXy1BigCOPt7A_0N1kyc7ncsmA5fw```

Important: Un Bearer token est nécessaire, n'hésitez pas à nous le demander afin que l'on vous le communique.

Conseil: le contexte sur une instance d'IA Gen concerne l'historique de toutes les réponses et prompts généré par l'IA Gen. Sur mon premier prompt l'IA ne possède aucun contexte. Sur mon deuxième prompt il faut que ma communication avec l'IA Gen ait en mémoire mon premier prompt et sa première réponse.

## Imaginer une application basée sur cette API

- Avec l'aide de chef de projet et de votre assistant essayez d'imaginer une application autour de ce boilerplate
- Vous disposez d'une totale liberté (amélioration de design, ajout de feature)




