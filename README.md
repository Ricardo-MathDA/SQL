# Múltiples tablas

Una **"llave primaria"** es una columna que registra un identificador único en cada tabla, es un **ID** para cada registro, así aseguramos que en esa columna no se pueda duplicar su valor, ni tenga un valor `NULL`.  
Es importante porque este valor es el que usamos para conectar múltiples tablas.

```sql
CREATE TABLE artists (
  id INTEGER PRIMARY KEY,
  name TEXT
);

### Tabla artists

| ID | Artista           |
|----|-------------------|
| 1  | The Beatles       |
| 2  | Elvis Presley     |
| 3  | Michael Jackson   |

### Tabla albums

| ID | Álbum                | ID_Artista |
|----|----------------------|------------|
| 1  | Bad                  | 3          |
| 2  | A Hard Day's Night   | 1          |
| 3  | Thriller             | 3          |
