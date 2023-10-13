# Cars Database

## Table Name

- cars


## Table Columns

- id | PK, BIGINT, AUTO_INCREMENT, UNIQUE, NOT NULL
- model_name | VARCHAR(20), NOT NULL
- category | VARCHAR(20), NULL
- exterior_color | VARCHAR(20), NULL
- interior_color | VARCHAR(20), NULL
- model_years | VARCHAR(20), NULL
- production_country | VARCHAR(20), NULL
- price | DECIMAL(12, 2), NOT NULL
- km | MEDIUMINT, NULL
- image | VARCHAR(255), NULL
- description | TEXT, NULL
- is_available | TINYINT, DEFAULT(0)
- seats | TINYINT, DEFAULT(0)
- engine | VARCHAR(20), NULL
- notes | TEXT, NULL
- shipping | TINYINT, DEFAULT(0)