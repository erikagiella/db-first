# Database Schema 

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Table name: cars

- id        PK      BIGINT                      NOTNULL     INDEX   UNIQUE  AI
- model             VARCHAR(50)                 NOTNULL     INDEX 
- brand             VARCHAR(50)                 NOTNULL     INDEX 
- description       TEXT                        NULL
- year              YEAR                        NOTNULL
- km                MEDIUMINT       UNSIGNED    NOTNULL
- condition         VARCHAR(20)                 NULL
- fuel              VARCHAR(20)                 NOTNULL
- transmission      VARCHAR(10)                 NULL
- emission_class    CHAR(5)                     NOTNULL 
- price             MEDIUMINT       UNSIGNED    NOTNULL
- picture           VARCHAR(255)
- car_code          VARCHAR(255)    UNIQUE
- date              DATETIME                    NOTNULL
- horsepower        SMALLINT        UNSIGNED    NULL
- engine_size       SMALLINT        UNSIGNED    NOTNULL