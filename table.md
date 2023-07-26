# CONCESSIONARIO

| colonna               | tipo        | attributo                  |
| --------------------- | ----------- | -------------------------- |
| id                    | bigint      | primary_key auto_increment |
| marca                 | varchar(50) | not null                   |
| proprietario          | varchar(50) | not null                   |
| anno immatricolazione | year        | null                       |
| modello               | varchar(50) | not null                   |
| km percorsi           | float(7,1)  | null                       |
| cilindrata            | smallint    | null                       |
| n°posti               | tinyint     | null                       |
| prezzo                | float(7,2)  | null                       |
| targa                 | varchar(7)  | not null                   |
| tipologia             | varchar(25) | null                       |
| stato                 | tinyint(1)  | not null default(1)        |
