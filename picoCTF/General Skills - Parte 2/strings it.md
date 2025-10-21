## Descripción
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/94d00153b0057d37da225ee79a846c62/strings) without running it?

## Solución
`picoCTF{5tRIng5_1T_d66c7bb7}`

## Notas Adicionales
Al igual que en problemas anteriores se utilizo grep pero en esta ocasión "| grep" donde "grep" es para filtrar como ya lo habíamos visto y "|" funciona como redirección de la salida de un comando como entrada para otro, en este caso "| grep" se traduce como "Busca esto dentro de la salida del comando anterior." De esta forma se pudo obtener la bandera sin necesidad de correr el programa.

## Referencias
https://www.youtube.com/watch?v=WwMY-EHGt3k
