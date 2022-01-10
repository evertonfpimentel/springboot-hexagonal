
# Arquitetura Hexagonal
Padrão arquitetural que tem como objetivo organizar o código de uma forma que a camada de negócio fique isolada de fatores externos como banco de dados, APIS, mensageria
e integrações entre sistemas, é principio de IOC(inversão de controle) o dominio é responável apenas pela regra de de negócio.

![image](https://user-images.githubusercontent.com/59370831/148806833-d8b1e5de-853f-4120-927e-122b74b5e6f0.png)

Port: onde é feito a ligação com o centro do hexagono.

Adapter: são as entradas e saídas, para cada adapter temos uma porta.

Domain: onde ficam as regras de negócio.
