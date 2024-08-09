# Configuração do Projeto

## Requisitos para Utilização

- **Conta Facebook:** Criação de um aplicativo no Meta Developers para recuperar o token de usuário.
- **Conta Instagram:** É necessário ter uma conta business do Instagram relacionada a uma página do Facebook.

## Conexões com Banco de Dados

O `integrador_sm` permite integração com os seguintes bancos de dados:

- **MySQL**
- **SQL Server**

### Configurações de Conexão

#### MySQL

Defina a variável de ambiente `DB_CONNECTION=mysql` e configure as seguintes variáveis:

- `MYSQL_USER`
- `MYSQL_PASSWORD`
- `MYSQL_HOST`
- `MYSQL_DATABASE`

- Inserir mais informações

#### SQL Server

Defina a variável de ambiente `DB_CONNECTION=sqlserver` e configure as seguintes variáveis:

- `SQLSERVER_USER`
- `SQLSERVER_PASSWORD`
- `SQLSERVER_HOST`
- `SQLSERVER_DATABASE`

## Limpeza de Cache

Para limpar o cache Python gerado durante a execução, utilize o script `scripts/cls_pycache.sh`:

```bash
bash scripts/cls_pycache.sh
```
