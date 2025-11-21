## Descripción
En el último desafío, dominaste los números octales (base 8), decimales (base 10) y hexadecimales (base 16), ¡pero esta puerta de bóveda utiliza un cambio diferente de base y codificación de URL!El código fuente de esta bóveda está aquí: [VaultDoor5.java](https://challenge-files.picoctf.net/c_fickle_tempest/aee691634d8cfd4a10820634bdea6b80aa104301e4b83d01fd4d176098d69e99/VaultDoor5.java)
## Solución
`picoCTF{c0nv3rt1ng_fr0m_ba5e_64_ed0b4288}
## Notas adicionales
Para resolver el reto, se tomó la cadena Base64 que daba el programa y se aplicó el proceso inverso al que hace el código. Primero se realizó un Base64 decode para obtener una cadena con caracteres en formato URL (%xx). Luego se hizo el URL decode, convirtiendo cada valor hexadecimal en su carácter ASCII original. El resultado final de esta doble decodificación es la contraseña verdadera, y al colocarla dentro del formato picoCTF{…} se obtiene la bandera correcta.
## Referencias
