## Descripción
¡Conéctese a este servidor PostgreSQL y encuentre la bandera!
Habrá detalles adicionales disponibles después de iniciar su instancia de desafío.
## Solución
`picoCTF{L3arN_S0m3_5qL_t0d4Y_21c94904}`
## Notas adicionales
Iniciamos la instancia, utilizamos `\dt` para observar las tablas existentes y luego utilizamos la sentencia `select * from flags;` pa solicitar la información de la tabla, donde encontramos la bandera.
## Referencias