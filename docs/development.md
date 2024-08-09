# Documentação de Desenvolvimento

## Instalação das Dependências

Este repositório utiliza o [Poetry](https://python-poetry.org/) para gerenciar as dependências do projeto.

Para instalar o Poetry, execute:

``` bash
pip install poetry
```

Em seguida instale as dependências

``` bash
poetry install
```

## Executando o serviço

Preencha o .env com as seguintes variáveis:

|Variável|Descrição|Default|
|-|-|-|
|LOG_LEVEL|Nível dos logs (DEBUG, INFO, WARNING, ERROR)|INFO|
|ACCESS_TOKEN_USER|Token de usuário da sua conta do facebook, no momento de liberar as permissões é necessário marcar as páginas que devem ser rastreadas|-|
|DB_CONNECTION|Tipo de conexão que será utilizada, leia em [Configuração](configuration.md) mais detalhes sobre cada conexão|

Abra um shell do Poetry e execute o serviço com:

``` bash
poetry shell
make start
```