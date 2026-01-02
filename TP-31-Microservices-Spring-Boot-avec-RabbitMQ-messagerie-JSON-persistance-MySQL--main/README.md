## TP 31 : Microservices Spring Boot avec RabbitMQ (messagerie JSON + persistance MySQL)
## Objectifs 
- Déclarer dynamiquement un exchange, une queue et un binding depuis Spring Boot.
- Publier un message via REST (Producer) et consommer via @RabbitListener (Consumer).
- Observer les échanges et compteurs dans l’interface RabbitMQ.
- Sérialiser/désérialiser en JSON avec Jackson2JsonMessageConverter.
- Persister un message consommé dans MySQL via Spring Data JPA.
  
## Mini-projet 1 (messagerie JSON)
- Structure projet Producer
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/5f95d5e1-6178-4605-9237-7c6efd9d8b37" />

- capture :
  <img width="1470" height="919" alt="Capture d’écran 2025-12-20 à 09 26 57" src="https://github.com/user-attachments/assets/70752679-f2a8-4275-949a-0525ad69cfbf" />
  <img width="1539" height="945" alt="Capture d’écran 2025-12-20 à 09 25 13" src="https://github.com/user-attachments/assets/99ea25b7-d85a-4d80-a884-8d915e0cb270" />
  
## Mini-projet 2 (messagerie + MySQL)

- Structure du  projet
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/80c5a4cd-a66b-4635-a347-7890cb6a903a" />

- capture :  
https://github.com/user-attachments/assets/11a234a7-634e-4a1f-bad7-2db7e124b524

#### Capture du RabbitMQ :
<img width="1470" height="919" alt="Capture d’écran 2025-12-20 à 09 44 14" src="https://github.com/user-attachments/assets/2a150ebb-a78d-4138-a889-18c8a3afdd44" />
<img width="2940" height="1838" alt="image" src="https://github.com/user-attachments/assets/ae9379eb-e275-4a30-ac56-7a0111b18ef8" />
