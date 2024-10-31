# Completo
Math services: los dos algoritmos de busqueda funcionan y devuelven correctamente la respuesta. Repo de math services: https://github.com/bricenojuliana/AREP-parcial2 
Despliegue corriendo y funcionando de una instancia de math services: Se desplego correctamente una instancia del servicio en aws. URL de la maquina: http://ec2-54-173-0-46.compute-1.amazonaws.com
Servidor proxy funcionando: El servidor redirije las peticiones correctamente y esta implementado el algoritmo de round-robin, sin embargo solo esta reidijiendo a la unica instancia desplegada.}
Cliente web: En el servidor proxy esta disponible la cliente web con HTML y JS. Dado que el servidor aun no esta desplegado se accde a el a traves de http://localhost:8080/index.html




![image](https://github.com/user-attachments/assets/f5329035-27e5-4639-9cd9-71da4fecb861)



# Hace falta
Desplegar la otra instancia de math services y configurar la URL en el servidor proxy.
Permitir el round robin descomentando la linea que permite cambiar entre servidores.
Desplegar el servidor proxy.
