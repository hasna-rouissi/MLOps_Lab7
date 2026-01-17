# Lab 7 : Gestion du cycle de vie des modèles avec MLflow

## Étape 1 : Initialisation de l’environnement et installation de MLflow
<img width="945" height="479" alt="image" src="https://github.com/user-attachments/assets/4da8dac9-d9a0-40e4-9063-9f6b85909810" />

## Étape 2 : Création explicite de l’espace de stockage MLflow
<img width="945" height="242" alt="image" src="https://github.com/user-attachments/assets/595668f6-e873-4d51-9e83-6b89d7b916d1" />

## Étape 3 : Configuration du client MLflow
<img width="945" height="106" alt="image" src="https://github.com/user-attachments/assets/3d53c2bd-dee4-459c-9d38-1ceed446e6ba" />

## Étape 4 : Démarrage du serveur MLflow (tracking server)
<img width="945" height="406" alt="image" src="https://github.com/user-attachments/assets/83a62197-0fcd-410e-9b99-f6337b4b9d4b" />
<img width="441" height="103" alt="image" src="https://github.com/user-attachments/assets/5001effe-ed8e-4e93-898d-0408c56eeffd" />

## Étape 5 : Instrumentation réelle de train.py
<img width="945" height="439" alt="image" src="https://github.com/user-attachments/assets/a2cd71f2-6214-447f-ad9a-10cb4bfde81d" />

### 1) Ajout des imports MLflow
<img width="945" height="539" alt="image" src="https://github.com/user-attachments/assets/55020120-a70b-46ba-b972-faa164da9fec" />

### 2) Constante globale
<img width="945" height="333" alt="image" src="https://github.com/user-attachments/assets/06f204d0-5e50-4973-8c1b-40575415fb19" />

### 3) Insertion du bloc MLflow à l’endroit exact dans main()
<img width="945" height="491" alt="image" src="https://github.com/user-attachments/assets/5331a09c-ff0d-4ad5-8a2c-81f9dc8a530f" />

### 4) Exécution
<img width="945" height="231" alt="image" src="https://github.com/user-attachments/assets/88051c61-04e8-4cd2-9ab0-88e8e3488e9f" />

### 5) Résultat attendu
<img width="781" height="610" alt="image" src="https://github.com/user-attachments/assets/cd3afa59-24d5-4bd4-8600-46532e18634f" />
<img width="945" height="186" alt="image" src="https://github.com/user-attachments/assets/5952065d-76bf-4f20-ad11-a3c15e429a6d" />

## Étape 6 : Observation du registry MLflow
<img width="945" height="302" alt="image" src="https://github.com/user-attachments/assets/3ccf1b28-d532-4b99-90e5-6c47909415c4" />

## Étape 7 : Promotion d’un modèle (activation)
<img width="945" height="578" alt="image" src="https://github.com/user-attachments/assets/ca9c9d40-7121-480a-82e0-d93387419a38" />
<img width="945" height="79" alt="image" src="https://github.com/user-attachments/assets/cc9233d1-21f4-4c57-911c-096a8280cc7b" />
<img width="945" height="545" alt="image" src="https://github.com/user-attachments/assets/fbe1efc1-336d-4d4b-810e-fc55d4b29c2d" />

## Étape 8 : Rollback via MLflow Model Registry
<img width="945" height="79" alt="image" src="https://github.com/user-attachments/assets/4b9331d5-710e-478f-a105-e3a74b0ac710" />
<img width="945" height="78" alt="image" src="https://github.com/user-attachments/assets/52741f96-2da7-44c3-8e87-51a638e1bf81" />
<img width="945" height="609" alt="image" src="https://github.com/user-attachments/assets/67ebe99e-3ed2-4065-9979-7feba0adbfe8" />

## Étape 9 : API : chargement du modèle actif
<img width="945" height="609" alt="image" src="https://github.com/user-attachments/assets/8fbe46d3-9f4d-4704-b4ac-9f492fcb805e" />
<img width="945" height="429" alt="image" src="https://github.com/user-attachments/assets/d631731e-0c58-4be0-82b3-10a24217b961" />
<img width="905" height="256" alt="image" src="https://github.com/user-attachments/assets/6d5cf7b3-560c-4bd5-9232-32fde0127924" />
<img width="945" height="401" alt="image" src="https://github.com/user-attachments/assets/f8a20d5c-727a-473f-a3e3-a65419868328" />
<img width="945" height="126" alt="image" src="https://github.com/user-attachments/assets/1aca4588-f54f-4584-baed-ae0d806d88a3" />
<img width="945" height="525" alt="image" src="https://github.com/user-attachments/assets/698fe852-4748-416a-962e-754fb1897420" />






