## Descripción
Encontramos una filtración de las credenciales de inicio de sesión de un sitio web del mercado negro. ¿Puedes encontrar el contraseña del usuario `cultiris` ¿y descifrarlo con éxito?Descarga la fuga [aquí](https://artifacts.picoctf.net/c/151/leak.tar).El primer usuario en `usernames.txt` corresponde a la primera contraseña en `passwords.txt`. El segundo usuario corresponde a la segunda contraseña, y así sucesivamente.
## Solución
`picoCTF{C7r1F_54V35_71M3}`
## Notas adicionales
Buscamos la palabra culturis en usernames el cual estaba en la linea 378, despues buscamos el password de la misma linea y nos aparecio la bandera cifrada, la tuvimos de decifrar con ROT13 Brute Force.
## Referencias