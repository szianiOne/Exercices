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

- USE THIS Bearer: ```eyJ0eXAiOiJKV1QiLCJub25jZSI6InBfT3NoekZJbDBqQzRqTnlyWnVsYTFDT3c1cWY4aDcwREdSa2MtRno1YkEiLCJhbGciOiJSUzI1NiIsIng1dCI6IlQxU3QtZExUdnlXUmd4Ql82NzZ1OGtyWFMtSSIsImtpZCI6IlQxU3QtZExUdnlXUmd4Ql82NzZ1OGtyWFMtSSJ9.eyJhdWQiOiIwMDAwMDAwMy0wMDAwLTAwMDAtYzAwMC0wMDAwMDAwMDAwMDAiLCJpc3MiOiJodHRwczovL3N0cy53aW5kb3dzLm5ldC9lOGI4OGYzZC0yMjJiLTRjZTUtYjlkMS00NmIwZmY5NDY2YTAvIiwiaWF0IjoxNzAyMzA3Mzc0LCJuYmYiOjE3MDIzMDczNzQsImV4cCI6MTcwMjMxMTM1NCwiYWNjdCI6MCwiYWNyIjoiMSIsImFpbyI6IkFWUUFxLzhWQUFBQWNjOVNkNTZicEZyMTBFZ1ZTdFo3Z3hkNzNsVVo2em1iZ2Q4bHZSM1ZOZG9RcFk2R3g3UDZVcVZ0aFpDK3VhcUJuNCthZkIxT05NQVJyZFdXazArRTB4cmcvZFBvUnlNS0J5MFU5cUR6bVEwPSIsImFtciI6WyJwd2QiLCJtZmEiXSwiYXBwX2Rpc3BsYXluYW1lIjoiU1NPIElBLUdFTiBQUkVQUk9EIiwiYXBwaWQiOiIxMjUyMjNmMC0zMzUxLTQxN2ItYThkYy1jOWIxZmQyMmFjZjMiLCJhcHBpZGFjciI6IjAiLCJmYW1pbHlfbmFtZSI6IlpJQU5JIiwiZ2l2ZW5fbmFtZSI6IlNhbWkiLCJpZHR5cCI6InVzZXIiLCJpcGFkZHIiOiIyMDAxOjRjMDg6MjAyNjoyOmExNmE6YmNjOTpmYjA1OjkwMjMiLCJuYW1lIjoiU2FtaSBaSUFOSSIsIm9pZCI6IjQ0NmM1ODQ1LTI3NWMtNDdlYy1iNGQxLTRhMWYwOTdhNjQxNiIsIm9ucHJlbV9zaWQiOiJTLTEtNS0yMS0yNjQxNTExNDQ4LTE4MzQyOTMzNjctNjIyNTg0NTk1LTYwMDk1IiwicGxhdGYiOiIzIiwicHVpZCI6IjEwMDMyMDAyMUI3ODY0RTAiLCJyaCI6IjAuQVRFQVBZLTQ2Q3NpNVV5NTBVYXdfNVJtb0FNQUFBQUFBQUFBd0FBQUFBQUFBQUF4QU5rLiIsInNjcCI6IlVzZXIuUmVhZCBwcm9maWxlIG9wZW5pZCBlbWFpbCIsInN1YiI6Imp0ZjllNUE5aDA1T1diaU45aFZ3dUJQUktublQyWWo0YnAwakFuaTdGWGciLCJ0ZW5hbnRfcmVnaW9uX3Njb3BlIjoiRVUiLCJ0aWQiOiJlOGI4OGYzZC0yMjJiLTRjZTUtYjlkMS00NmIwZmY5NDY2YTAiLCJ1bmlxdWVfbmFtZSI6InMuemlhbmlAZ3JvdXBlb25lcG9pbnQuY29tIiwidXBuIjoicy56aWFuaUBncm91cGVvbmVwb2ludC5jb20iLCJ1dGkiOiJYRXFoOWJpSkdVbXhhX1RQdUZaWUFBIiwidmVyIjoiMS4wIiwid2lkcyI6WyJiNzlmYmY0ZC0zZWY5LTQ2ODktODE0My03NmIxOTRlODU1MDkiXSwieG1zX3N0Ijp7InN1YiI6IkJYazc4cmZRX1EteWJuU3h5TkY2TTVTUXNFUUl4TVk2c1J5ZkVabDZaM2cifSwieG1zX3RjZHQiOjE1MjcyNDQyNzUsInhtc190ZGJyIjoiRVUifQ.W0sxNHb1EEauSAcO-bH7_cIhzzHv0oznickXq34rlu-_L3EuTQ7An9i2U25zFT3uak3tJpM8K3UKljOeCLld6Ph0KCdtU0KqFWrxXK286XpyvinnbfRMYxuJh2k2fIr9asl59AmrMWi9Y7xlDaHhzVVQ-E1mWR1UCYs99Fqw1NCZ_oIUS2W1j2MqQ2I9u_45L7DOIUelhdWLpW95geLQNGokiiG3p4oxf3Qaf2zmyG2GTqwBuNhIy8gHvsIFSVk9LNhKFjVQvoGVADGwsaY3nlIOFquRoZSdJAnGoxAaVcfib83tYiFFX-C27GxJVa7et_23ip40aiLYjWXyhr462g```

Important: Un Bearer token est nécessaire, n'hésitez pas à nous le demander afin que l'on vous le communique.

Conseil: le contexte sur une instance d'IA Gen concerne l'historique de toutes les réponses et prompts généré par l'IA Gen. Sur mon premier prompt l'IA ne possède aucun contexte. Sur mon deuxième prompt il faut que ma communication avec l'IA Gen ait en mémoire mon premier prompt et sa première réponse.

## Imaginer une application basée sur cette API

- Avec l'aide de chef de projet et de votre assistant essayez d'imaginer une application autour de ce boilerplate
- Vous disposez d'une totale liberté (amélioration de design, ajout de feature)




