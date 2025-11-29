# Múltiples tablas

Una <span style="color:#E63946">**llave primaria**</span> es una columna que registra un identificador único → no se repite y nunca es NULL.  
Una <span style="color:#2A9D8F">**llave foránea**</span> puede repetirse y aceptar valores nulos.

```sql
CREATE TABLE artists (
  id INTEGER <span style="color:#E63946">PRIMARY KEY</span>,
  name TEXT
);