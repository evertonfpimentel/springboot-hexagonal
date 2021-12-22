
# Arquitetura Hexagonal
Padrão arquitetural que tem como objetivo organizar o código de uma forma que a camada de negócio fique isolada de fatores externos como banco de dados, APIS, mensageria
e integrações entre sistemas, é principio de IOC(inversão de controle) o dominio é responável apenas pela regra de de negócio.

![image](https://user-images.githubusercontent.com/59370831/147095053-f9e7cef0-7f4d-4eb9-a14f-c0e42d76f910.png)

Port: onde é feito a ligação com o centro do hexagono.

Adapter: são as entradas e saídas, para cada adapter temos uma porta.

Domain: onde ficam as regras de negócio.
