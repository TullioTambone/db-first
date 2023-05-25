| Col          | Tipologia     | Attributo                       | Primary       |
|--------------|---------------|---------------------------------|---------------|
| ID           | INT           | Auto_increment, notnull, unique | primary key   |
| MODELLO_ID   | VARCHAR(50)   | NOT NULL                        | secondary key |
| MARCA_ID     | VARCHAR(25)   | NOT NULL, UNIQUE                | INDEX         |
| NOME_CAR_ID  | VARCHAR(20)   | NOT NULL                        | secondary key |
| ATTRIBUTI_ID | VARCHAR(255)  | NOT NULL                        | secondary key |
| ANNO         | YEAR          | NOT NULL                        |               |
| KM-PERCORSI  | MEDIUMINT     | NOT NULL                        |               |
| PREZZO       | DECIMAL(10,2) | NOT NULL                        |               |
| CARROZZERIA  | VARCHAR(20)   | NULL                            |               |
| CARBURANTE   | VARCHAR(20)   | NOT NULL                        |      