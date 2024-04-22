# Descrizione esercizio

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Table name: used cars for sale

- id | INDEX | INT | NOTNULL | PRIMARY_KEY | AI
- brand | VARCHAR(20) | NOTNULL
- model | VARCHAR(20) | NOTNULL
- image | VARCHAR(255) | DEFAULT() | NULL
- price | SMALL / MEDIUMINT | NOTNULL
- kilometers | SMALL / MEDIUMINT | NULL 
- fuel | VARCHAR(10) | NULL
- max_seat | TINYINT | NULL
- license_plate | UNIQUE | VARCHAR(7) | NULL
- registration_year | YEAR | NULL
- note | TEXT | NULL