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

| cliente            | pedido     | entrega             | relación | regalo     | entregado | costo|
|--------------------|------------|---------------------|----------|------------|-----------|------|
| Adel Rodríguez     | 2025/01/26 | 2025/02/14 06:38 pm | Anonimos | Rosas      | Si        | 1114 |
| Hugo González      | 2025/01/12 | 2025/02/14 08:19 pm | Familiar | Combo      |           | 731  |
| Abaigar Martínez   | 2025/01/25 | 2025/02/14 09:02 pm | Novios   | Rosas      | Entregado | 1040 |
| Adolf Fernández    | 2025/02/03 | 2025/02/14 01:50 pm | Amigos   | Capibaras  | Si        | 403  |
| Agostiño Pérez     | 2024/12/25 | 2025/02/14 06:38 pm | Amigos   | Chocolates | Entregado | 1140 |
| Aberbequeye García | 2025/01/12 | 2025/02/14 04:28 pm | Novios   | Rosas      | Si        | 840  |
| Aarón Silva        | 2025/01/02 | 2025/02/14 12:24 pm | Anonimos | Osos       | Entregado | 927  |
| Adonis López       | 2024/12/28 | 2025/02/14 12:52 pm | Anonimos | Chocolates | Claro     | 968  |
| Mateo Pereira      | 2024/12/16 | 2025/02/14 10:14 am | Novios   | Ramos      |           | 666  |
| Adei Sosa          | 2025/02/01 | 2025/02/14 01:07 pm | Novios   | Combo      |           | 1272 |

