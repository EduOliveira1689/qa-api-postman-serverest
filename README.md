# QA API Testing - ServeRest

Projeto de testes de API desenvolvido utilizando Postman na API pública ServeRest.

## Objetivo

Validar endpoints REST utilizando testes manuais e automatizados, garantindo integridade dos dados, autenticação e comportamento esperado da API.

---

## Tecnologias utilizadas

- Postman
- REST API
- JavaScript
- JWT Authentication

---

## Funcionalidades testadas

### Login
- Autenticação de usuário
- Captura dinâmica de token JWT

### Usuários
- Listagem de usuários

### Produtos
- Cadastro de produtos
- Listagem de produtos
- Edição de produtos
- Remoção de produtos

### Carrinhos
- Cadastro de carrinho
- Listagem de carrinho
- Busca por ID
- Cancelamento de compra

---

## Recursos utilizados

- Collections organizadas por módulos
- Variáveis de ambiente
- Captura automática de token
- Reutilização de autenticação Bearer Token
- Scripts de validação
- Organização de endpoints REST

---

## Estrutura do projeto

```bash
collections/
environments/
README.md
```

---

## Como executar

1. Importar a collection no Postman
2. Importar o environment
3. Selecionar o environment "Serverest"
4. Executar os endpoints desejados

---

## Autor

Eduardo Oliveira
