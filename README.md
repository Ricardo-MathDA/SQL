# Múltiples tablas

<span style="color:#FF6B6B">► Llave primaria</span> → identificador único (nunca se repite ni es NULL)  
<span style="color:#4ECDC4">► Llave foránea</span> → puede repetirse y aceptar NULL

```sql
CREATE TABLE artists (
  id INTEGER PRIMARY KEY,   -- 🔴 PRIMARY KEY
  name TEXT
);
