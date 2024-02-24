# Simple Bank

### Setup infrastructure

- Start postgres container:

    ```bash
    make postgres
    ```

- Create simple_bank database:

    ```bash
    make createdb
    ```

- Run db migration:

    ```bash
    make migrateup
    ```

### How to run

- Run test:

    ```bash
    make test
    ```