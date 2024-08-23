# TP6 de Programación Multimedial 4: Dockerizando

|                        |                                 |
| ---------------------- | ------------------------------- |
| Integrantes por grupo: | 2                               |
| Se aprueba con         | 6                               |
| Fecha de entrega       | Miércoles 05 de septiembre, 23:59 hs |
| Fecha de re-entrega    | Miércoles 11 de septiembre, 23:59 hs |

## Metodología

### Objetivos

- Aprender a deployar una aplicación full-stack en Docker
- Entender mejor Docker

### Comentarios

Tengan presente que este TP es muy apto para que se lo copien entre ustedes. O para que lo haga ChatGPT.

Recuerden que, por lo general, la solución más simple es la mejor.

----

## Entrega

### Mail

Por favor, mándenme un email a <me@diegofreijo.com> cuando tengan todo listo. 

En el mail agreguen:

- El link a la etiqueta `tp6`
- La URL del frontend
- La URL del backend

### Defensa de entrega

No hay oral 😀

----

## Grupos

Mantuve el Integrante 1 del TP3 y el otro fue pseudo aleatorio para que no se repitan parejas.

| Aplicación | Integrante 1 | Integrante 2 |
|---|---|---|
|App1|Freijo, Diego|Olguin, Manuel|
|App2|Franco, Victoria|Miramont, Rocio|
|App3|Pacio, Noeli|Rozenberg, Lucas|
|App4|Zapolski, Jimena|Bragazzi, Belen|
|App5|Gullerian, Anush|Franco, Martina|
|App6|Borsa, Agustin|Rodrigues, Agustin|

----

## Requerimientos

Hoy se terminan de convertir en ✨ `Full-Stack Developers` ✨. Para ello van a hacer un deploy del stack que les toco en AWS usando Docker.

El objetivo es simple: tienen que deployar la App que les toco, completa, en docker.

### Lista aproximada de cosas que deberían hacer para lograr el TP

- Crear una Imagen para cada servicio (frontend y backend)
- Crear un Docker Compose que junte ambos servicios
- Instalar Docker en la instancia de EC2 que tienen de AWS
	- No hace falta que usen AWS si quieren usar otro proovedor. Pero ya lo tienen corriendo y configurado, y es gratis 🤷‍♂️
	- https://docs.docker.com/engine/install/ubuntu/
- Matar todo servicio que tengan corriendo en el servidor
- Clonar el repo en el servidor
- Levantar la orquesta
- Asegurarse que este todo andando
- Asegurarse que la orquesta vuelva a ser armada aun si el servidor se reinicia.

### Código

Les recomiendo que hagan un nuevo repo para este TP. Pero si quieren reutilizar el del TP3 o TP4, no hay problema.

Agreguen una `tag` en el repositorio que se llame `tp6`. Ese commit es el que voy a corregir.

### Reporte

No va a haber oral en esta entrega. Así que las cosas que necesito que me cuenten me las van a agregar a un `README.md` en el repo. **Esto no es un reporte a-la-TP2**. No espero una hermosa redacción en prosa. Solamente espero información técnica, corta y simple, de las siguientes cosas:

- Como organizaron las carpetas entre todos los proyectos. Si no es obvia la solución que eligieron, agreguen una mini-justificación.
- Como hicieron para armar las imágenes y el `docker-compose.yaml`. Por ejemplo, si usaron ChatGPT, googlearon, la escribieron desde cero, etc.
- Como hicieron para que el servicio siga andando aun si se reinicia el servidor.
- Cualquier problema interesante que hayan tenido. Especialmente si consideran que fue un problema propio de la app que les tocó.
