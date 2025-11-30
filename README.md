# Múltiples tablas

Una **"llave primaria"** es una columna que registra un identificador único en cada tabla, es un **ID** para cada registro...

```sql
create table PedidosFebrero(
cliente varchar(60),
pedido date,
entrega datetime2,
relacion varchar(60),
regalo varchar(60),
entregado varchar(60),
costo money);
```

| id | nombre   | edad |
|----|-----------|------|
| 1  | Ana       | 23   |
| 2  | Roberto   | 31   |
| 3  | Mariana   | 27   |
