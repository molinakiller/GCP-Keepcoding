# GCP-Keepcoding

--- PROJECT INFORMATION ---

Nombre del proyecto : pedro-molina
Número del proyecto : 15085041231
ID de proyecto : pedro-molina

--- END PROJECT INFORMATION ---

--- FIRST PART ---

![diagram](https://user-images.githubusercontent.com/32618431/151517903-c5a37c58-8b65-4f28-b599-39feb5bffa70.png)

--- SECOND PART ---

Con unos simples clicks podemos implementar un SQL en la nube, además de proporcionarnos copias de seguridad sin tener que depender de entrar por SSH a la máquina que tenga el SQL instalado y ejecutar mysqldump. Por si fuera poco, las copias de seguridad se pueden automatizar, se acabaron los cronjobs para hacer backups.
Con SQL cloud disponemos de todas las características de SQL con los beneficios de la nube con unos simples clicks.

Siguiendo las indicaciones de la práctica se ha descalado al mínimos de recursos (1vCPU + 3,75GB RAM)
 
---  THIRD ---

Creando una imágen de una instancia, podemos crear una plantilla para crear tantas máquinas iguales como creamos oportuno.
Nos otorga la capacidad de escalar las instancias según los criterios que le indiquemos (CPU/RAM...)

La máquina attacker es la encargada de atacar al grupo de instancias, haciendo que esta escale según nuestras indicaciones. Únicamente habría que acceder a la instancia vía SSH y ejecutar el script con el siguiente comando.

```
sh attack.sh
```

--- FOURTH --- 

Con Google App Engine nos permite versionar, escalar y ejecutar nuestro código con una gran rápidez.
En el caso de la práctica utilizamos código para implementar una conexión a la base de datos que hemos creado en la segunda parte.
Generamos dos versiones y además dividimos el tráfico.
