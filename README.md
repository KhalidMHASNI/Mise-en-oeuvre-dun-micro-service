# Micro services
1. Créer un projet Spring Boot avec les dépendances Web, Spring Data JPA, H2, Lombok

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/5727a414-a612-4f50-bcd7-ade1d245ff0b)

2. Créer l'entité JPA Compte

![Capture d'écran 2023-05-15 224940](https://github.com/oumaimabenaboud/micro_service/assets/120368654/3c2aec23-6ea3-4de5-b39e-2c647f12cbe4)


3. Créer l'interface CompteRepository basée sur Spring Data

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/944e246a-b229-46d5-990a-3153efbe9faf)



4. Tester la couche DAO

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/2cc5a24e-a91f-4908-8f23-983c7b7de887)
![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/ad740600-8484-4e2d-b175-3fb48fbd4bd1)


5. Créer le Web service Restful qui permet de gérer des comptes

- Liste des comptes

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/8c02d29b-01b6-46b1-9b6a-cf360f5eb9e9)

- Find account by Id (2da01067-e727-4dda-a3de-b4a8ab8afa19)

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/a640e2ca-7395-46fc-aead-32f5f630e80b)


6. Tester le web micro-service en utilisant un client REST comme Postman
- Liste des comptes

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/0416f624-e64c-4c6d-803b-862294c98293)

- Find account by Id

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/581a5a0a-0760-453c-81a2-3ebb2907f847)

- Save new account

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/44bc6a3a-4621-4898-93dd-74750c184ed2)

- Update account info

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/8245133d-3068-4a99-95a0-43e838670700)

7. Générer et tester la documentation Swagger du API Rest du Web service

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/2d1c6c44-f531-4a6f-be85-56bfc35f43aa)

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/978726a8-2933-4d71-8677-f7b3dd649b00)

- Importer la documentaion OpenAPI dans Postman

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/3ef5da8b-619c-45b7-ba2d-921462a6bbc0)

8. Exposer une API Restful en utilisant Spring Data Rest en exploitant des projections
- Utilisation de Spring Data Rest

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/bb3dc410-49a0-4ba1-ac6e-0c6d2b126a89)

- Search using "findByType"

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/47121705-253b-4945-b209-36caba5ae047)

- Projection

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/8e5ee2de-cbbd-42ef-b854-761d371e883f)

- Search using "byType"

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/f63076ed-b32e-4370-97a3-1ccf564328f4)

9. Créer les DTOs et Mappers
- Save new account using DTOs

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/1d282940-338b-439e-a080-9f030d5e35b6)
![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/7b3c80de-2230-4579-adc3-aff8eadb6f82)


- Save new account using Mappers

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/afea6b05-7969-4e58-a782-82905a2f9600)
![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/bed99d3d-7f4c-49de-b555-62c9678d6be4)

10. Créer la couche Service (métier) du micro service

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/3a4750d8-31c2-4ac0-a65c-07c3de568a1a)

11. Créer un Web service GraphQL pour ce micro-service
- Test du Webservice using GrahiQL : Liste des comptes

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/c6767638-6327-46c2-8be4-ffb7a1b3a4e4)

- Test du Webservice using GrahiQL : Find account by Id

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/721d4fe9-4bc5-49e7-be4c-75ea67d5b84e)

- Ajout de l'Exception Handler

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/1c95c936-8fe0-44e9-9322-9a825005a290)

- Test du Webservice using GrahiQL : Add new account

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/a559f274-7950-4a3e-b641-7a85fd796afa)
![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/006a517d-4b60-4597-8a66-fa3b28d15d1e)

- Test du Webservice using GrahiQL : Update account

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/2a08055e-e8b6-4482-956c-e2bb74d420d9)

- Test du Webservice using GrahiQL : Delete account

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/9d9132b1-d7b6-4397-9793-4782117eec2f)

- Ajout de l'entité Customer

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/6eab7b58-0e12-4ff1-9dcc-9c95403d88f4)

- Test du Webservice using GrahiQL : Liste des comptes avec noms de clients

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/f65cac28-3811-4611-8ad8-a59d313969da)

![image](https://github.com/KhalidMHASNI/Mise-en-oeuvre-dun-micro-service/assets/82038554/7646a7db-9ed7-4dac-ae1b-a1284c8bf406)

