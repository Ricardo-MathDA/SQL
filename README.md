# Múltiples tablas

Una **"llave primaria"** es una columna que registra un identificador único en cada tabla, es un **ID** para cada registro, así aseguramos que en esa columna no se pueda duplicar su valor, ni tenga un valor `NULL`.  
Es importante porque este valor es el que usamos para conectar múltiples tablas.

```sql
CREATE TABLE artists (
  id INTEGER PRIMARY KEY,
  name TEXT
);

### Resultado de la consulta

| id  | nombre      | edad |
|-----|-------------|------|
| 1   | Ana         | 28   |
| 2   | Luis        | 34   |
| 3   | Carmen      | 22   |
