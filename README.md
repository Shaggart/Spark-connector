# Домашнее задание - Написание коннекторов для Spark

## Задача


[Оригинальный репозиторий с кодом](https://github.com/Gorini4/spark_datasource_example)

Доработайте код в файле src/main/scala/org/example/datasource/postgres/PostgresDatasource.scala так, чтобы тест в файле src/test/scala/org/example/PostgresqlSpec.scala при выполнении читал таблицу users не в одну партицию, а в несколько.