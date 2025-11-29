# Múltiples tablas

Una **"llave primaria"** es una columna que registra un identificador único en cada tabla, es un **ID** para cada registro...

```sql
CREATE TABLE artists(
  id INTEGER PRIMARY KEY,
  name TEXT
);
```

| id | nombre   | edad |
|----|-----------|------|
| 1  | Ana       | 23   |
| 2  | Roberto   | 31   |
| 3  | Mariana   | 27   |
