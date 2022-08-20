# Real MySQL 8.0

Repository to run codes from _<Real MySQL 8.0>_ from _Wikibooks_.

## How to Run

1. Extract `employees.zip` to the project root directory.

2. Create a MySQL container.

   ```bash
   $ docker compose up
   ```

3. Access MySQL shell.

   ```bash
   $ docker compose exec db mysql -u root -p
   ```

4. Enter password specified in `docker-compose.yml`.

5. Insert initial data.

   ```bash
   mysql> USE employees
   mysql> SOURCE /realmysql/employees.sql
   ```

6. Wait for a (long) while and you're ready to run some queries.

## REF

- [위키북스 Real MySQL 8.0](http://www.yes24.com/Product/Goods/103415627)

- [wikibook - Real MySQL 8.0 Repository](https://github.com/wikibook/realmysql80)
