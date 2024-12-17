# Teste backend

Utilizando NodeJS (com ou sem framework, o que achar necessário) junto com Mysql ou Sqlite, crie os seguintes endpoints:

------------------------------------------------------------------------------------------------------------------------

## Obrigatório
```Cadastrar```
Cadastro simples de usuário com email e senha.

```Login```
Autenticação via JSON utilizando e-mail e senha. O sistema deverá retornar alguns dados do usuário junto com um token `jwt`.

```Buscar dados do usuário```
Um endpoint autenticado para buscar os dados do usuário autenticado. A autenticação deverá ser feita com o token `jwt` retornado pela autenticação.



## Bonus

```Logout```
Endpoint consumido por um usuário autenticado para deslogar e adicionar o `jwt` na blacklist (proibir futuras requisições autenticadas com o token de usuário)

```Web```
Parte web simples com login e logout

------------------------------------------------------------------------------------------------------------------------

# Entrega
- Gravar um vídeo de até 5 minutos mostrando a API em funcionamento:
    - Sugestão: Loom
- Compartilhar código fonte no github ou gitlab
