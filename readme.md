# Threads API no oficial

1. **Descripción del proyecto:**
2. **Instrucciones de instalación**
3. **Guía de uso**
4. **Estructura del proyecto:**
5. **Requisitos y dependencias:**
6. **Contribución:**
7. **Licencia:**
8. **Contacto:**

<div align="center">
  <small>Para fines educativos</small>
</div>

1. Descripción del proyecto: se trata de una **API NO OFICIAL** para la nueva red social desarrollada por META llamada Threads el objetivo de este (enlace video youtube una vez subido)[**curso**] es el aprendizaje. Se obtienen las calls los datos de los servidores de meta. Y entragamos los datos depurados a partir de los datos obtenidos. La api ha sido desarrollado con (https://bun.sh/)[bun]
2. **Instrucciones del instalación del proyecto y desplegar de manera local.** 

2.1. Se clona el proyecto
```bash 
git clone https://github.com/midudev/threads-api
```
2.2. Se instala bum (https://bun.sh/docs/installation)[**instalación**] y descargamos los paquetes.
```bash
bum install
```
2.3. Ejecutar de manera local el proyecto.
```bash
bum run
```
3. **Guía de uso**


4. **Estructura del proyecto:**
- src
  - api 
  - lib
  - types

En `api` se ocupara de la parte del routing 
En `lib` estan las diferentes constantes, variables de entorno, fetch y mapping
En `type` se almacenaran los tipos personalizados.  
5.

6.

7. Licencia GPL

8.

## Primeras pruebas con Curl

2.

```sh
curl 'https://www.threads.net/api/graphql' \
  -H 'content-type: application/x-www-form-urlencoded' \
  -H 'sec-fetch-site: same-origin' \
  -H 'user-agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36' \
  -H 'x-ig-app-id: 238260118697367' \
  --data 'variables={ "userID": "8242141302" }' \
  --data doc_id=23996318473300828
```
