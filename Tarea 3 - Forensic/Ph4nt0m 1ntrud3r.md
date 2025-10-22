## Descripción
¡Un fantasma digital ha violado mis defensas y mis datos confidenciales han sido robados! 😱💻 Tu misión es descubrir cómo este intruso fantasma se infiltró en mi sistema y recuperar la bandera oculta.Para resolver este desafío, deberá analizar el archivo PCAP proporcionado y rastrear el método de ataque. El atacante ha ocultado hábilmente sus movimientos de manera oportuna. ¡Sumérgete en el tráfico de la red, aplica los filtros adecuados y muestra tu destreza forense y desenmascara al intruso digital!Encuentre el archivo PCAP aquí [Archivo PCAP de tráfico de red](https://challenge-files.picoctf.net/c_verbal_sleep/45a9df82c8f05fd74b8547d157ae6b1be6ba783a2bad55c6f8c664e4609d88ac/myNetworkTraffic.pcap) y trata de conseguir la bandera.
## Solución
`picoCTF{1t_w4snt_th4t_34sy_tbh_4r_f318db22}`
## Notas adicionales
Se utilizo el siguiente comando para sacar la bandera desde la terminal: `tshark -r myNetworkTraffic.pcap -Y "tcp.len==12 || tcp.len==4" -T fields -e frame.time -e tcp.segment_data | sort -k4 | awk '{print $6}' | xxd -p -r | base64 -d
## Referencias
https://youtu.be/_YKC5Smffeg