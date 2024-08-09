# Controle de Migração

## Gerar uma Nova Migração

Após editar alguma entidade existente, gere uma nova migração usando o comando abaixo, alterando a mensagem de migração:

=== "make"
    ```bash
    make autogenerate message="mensagem da migration"
    ```

=== "alembic"
    ```bash
    alembic revision --autogenerate -m "mensagem da migration"
    ```

!!! warning "Verificação de migrations"

    Revise a migração criada no diretório alembic/versions/. Ela é gerada automaticamente, mas deve ser revisada para garantir que todas as mudanças estejam corretas.


## Executar migrações

Após revisar a migração, execute-a com:

=== "make"
    ```
    make migrate
    ```

=== "alembic"
    ```
    alembic upgrade head
    ```

