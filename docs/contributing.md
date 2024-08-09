# Detalhes de Contribuição

Este projeto adota um processo de contribuição estruturado para garantir a qualidade e a consistência do código. Antes de contribuir, certifique-se de seguir as práticas descritas abaixo.

## Padrões de Commit

Utilizamos o padrão [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) para mensagens de commit. Este padrão ajuda a manter um histórico de commits consistente e fácil de entender. Os commits são verificados automaticamente usando hooks de pre-commit.

### Exemplo de Mensagem de Commit

```bash
feat: adiciona suporte para integração com o Twitter
fix: corrige erro na autenticação do Instagram
docs: atualiza documentação de configuração do MySQL
```


## Configuração de Pre-commits

Para garantir a qualidade do código, utilizamos hooks de pre-commit em Python. Esses hooks verificam o código antes de cada commit, ajudando a evitar erros comuns e a manter a consistência do estilo.

Instale os hooks definidos no arquivo do pre-commits:

```bash
pre-commit install
```
Agora, os hooks serão executados automaticamente antes de cada commit. Se algum hook falhar, o commit será bloqueado até que os problemas sejam corrigidos.

## Releases e Versionamento

Para gerenciar versões e gerar tags automaticamente, siga os passos abaixo:

Instale o standard-version:

```bash
npm install --save-dev standard-version
```

Para criar uma nova tag, execute:

```bash
standard-version patch
standard-version minor
standard-version major
```

Envie as tags para o repositório:

```bash
git push origin main --follow-tags
```

## Makefile

O projeto inclui um makefile para auxílio na execução dos comandos, execute o comando `make` para verificar os possíveis comandos.