# # Sobre o projeto 

Este é um sistema de eventos e cidades com uma relação N-1 entre eles.
Neste sistema, somente as rotas de leitura (GET) de eventos e cidades são públicas (não precisa de login). Usuários CLIENT podem também inserir (POST) novos eventos. Os demais acessos são permitidos apenas a usuários ADMIN.

Validações de City:
- Nome não pode ser vazio

Validações de Event:
- Nome não pode ser vazio
- Data não pode ser passada
- Cidade não pode ser nula

## Modelo conceitual
![Modelo Conceitual](https://github.com/igor-lourenco/bds04/blob/main/assets/Screenshot.png)

## Padrão camadas
![Modelo Conceitual](https://github.com/igor-lourenco/projeto-spring-react-vendas/blob/main/frontend/src/assets/img/padrao_camadas.png)

# Tecnologias utilizadas
## Back end
- Java 11
- Spring Boot
- Spring Cloud
- JWT
- OAuth2
- JPA / Hibernate
- Maven

# Autor

Igor Lourenço Dos Santos

https://www.linkedin.com/in/igor-lourenco-santos
