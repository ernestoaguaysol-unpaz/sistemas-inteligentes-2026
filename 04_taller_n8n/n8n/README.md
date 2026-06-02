# n8n con PostgreSQL y Worker

Inicia n8n con PostgreSQL como base de datos, y el Worker como un contenedor separado.

## Iniciar

Para iniciar n8n simplemente iniciar docker-compose ejecutando el siguiente comando en la carpeta actual.

**IMPORTANTE:** ¡Antes cambia los usuarios y contraseñas por defecto en el archivo [`.env`](.env)!

```
docker compose up -d
```

Para detenerlo ejecutar:

```
docker compose stop
```

## Configuración

El nombre predeterminado de la base de datos, el usuario y la contraseña para PostgreSQL se pueden cambiar en el archivo [`.env`](.env) en el directorio actual.