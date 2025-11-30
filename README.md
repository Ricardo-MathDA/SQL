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

| cliente            | pedido     | entrega          | relacion | regalo     | entregado | costo   |
|--------------------|------------|------------------|----------|------------|-----------|---------|
| Adel Rodríguez     | 26/01/2025 | 14/02/2025 18:38 | Anonimos | Rosas      | Si        | 1114.00 |
| Hugo González      | 12/01/2025 | 14/02/2025 20:19 | Familiar | Combo      |           | 731.00  |
| Abaigar Martínez   | 25/01/2025 | 14/02/2025 21:02 | Novios   | Rosas      | Entregado | 1040.00 |
| Adolf Fernández    | 03/02/2025 | 14/02/2025 13:50 | Amigos   | Capibaras  | Si        | 403.00  |
| Agostiño Pérez     | 25/12/2024 | 14/02/2025 18:38 | Amigos   | Chocolates | Entregado | 1140.00 |
| Aberbequeye García | 12/01/2025 | 14/02/2025 16:28 | Novios   | Rosas      | Si        | 840.00  |
| Aarón Silva        | 02/01/2025 | 14/02/2025 12:24 | Anonimos | Osos       | Entregado | 927.00  |
| Adonis López       | 28/12/2024 | 14/02/2025 12:52 | Anonimos | Chocolates | Claro     | 968.00  |
| Mateo Pereira      | 16/12/2024 | 14/02/2025 10:14 | Novios   | Ramos      |           | 666.00  |
| Adei Sosa          | 01/02/2025 | 14/02/2025 13:07 | Novios   | Combo      |           | 1272.00 |
| Adrià Flores       | 13/01/2025 | 14/02/2025 21:16 | Novios   | Capibaras  | Si        | 177.00  |
