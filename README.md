# Parking-Spot
Uma API de administração de vagas de estacionamento para condomínios, criada utilizando SpringBoot, Spring Data JPA, Spring Rest, Spring Validation

# Como Utilizar
Após fazer o clone por meio do `git clone`, você deverá alterar as configurações no arquivo `resources/application.properties`. Lá, você deverá alterar as variáveis de conexão ao Banco de Dados, caso estejam diferentes das suas.

Além disso, é preciso criar uma `database` do PostgreSQL no seu computador, com o nome colocado nas configurações ditas acima.

# Testando

Para testar o projeto, basta utilizar o `Postman` ou o `Insomnia`, para envio de dados à API. Como exemplo de criação de dados, utilizando o método `POST`, temos:
```
{
  "parkingSpotNumber": "205A",
  "licensePlateCar": "RR50562",
  "brandCar": "audi",
  "modelCar": "q5",
  "colorCar": "black",
  "responsibleName": "Carlos Daniel",
  "apartment": "205",
  "block": "A",
}
```
Agora, divirta-se!
