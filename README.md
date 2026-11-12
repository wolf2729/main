
# Sistema de Reserva de Horas Médicas

## Descripción

Proyecto académico desarrollado para la asignatura DevOps.
Consiste en una página web estática que simula un sistema
de reserva de horas médicas.

La aplicación utiliza HTML, CSS, Nginx y Docker.

## Requisitos

- Git.
- Docker Desktop.
- Docker Compose.
- Navegador web.

## Instalación

Clonar el repositorio:

git clone URL_DEL_REPOSITORIO

Ingresar a la carpeta:

cd proyecto-devops

Crear el archivo de variables:

Copiar .env.example y renombrarlo como .env.

## Ejecución

Construir y levantar el servicio:

docker compose up -d --build

## Verificación

Abrir el navegador:

http://localhost:8080

Consultar el estado:

docker compose ps

Revisar los registros:

docker compose logs web

Consultar recursos:

docker stats reservas-medicas

## Detención

docker compose down

## Seguridad

El proyecto no utiliza datos reales de pacientes,
contraseñas ni credenciales de servicios externos.

El archivo .env está excluido del repositorio
mediante .gitignore.