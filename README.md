# U4S8 — Pesqueira Gamez Manuel Angel

## Demo en vivo (producción)

https://u4s8-pesqueira-gamez-manuel-angel.onrender.com

## Qué hace este proyecto

Este proyecto es un sistema con login para registrar
servicios y costos de manera individual por usuario.

## Stack técnico
Django + MySQL (Aiven) + Tailwind CSS + Render

## Cómo se prueba el aislamiento por usuario
Se probo el aislamiento de la aplicación creando dos usuarios independientes al
super usuario. Creamos dos servicios en cada uno y verificamos que estos no
aparecieran en el servicio de otro usuario.

Tambien nos tratamos de saltar el aislamiento manualmente forzando la url sin embargo
recibimos un error 404 confirmando el total aislamiento por usuario.


## Historial de unidades

### Unidad 1: portafolio estático con HTML5 + Tailwind

En la unidad uno creamos un portafolio estatico con HTML5 + Tailwind
y los publicamos en render.

### Unidad 2: modelo Servicio migrado a MySQL, deploy dinámico en Render

En la unidad dos creamos un archivo con djando y MySQL, en esta usamos
render y aiven para desplegar y mantener activo la base de datos en la
nube.

### Unidad 3: CRUD completo con ModelForms + autenticación y sesiones

En la unidad tres creamos el CRUD completo de la aplicacion usando
el ModelForm y tambien verificamos y creamos aislamiento entre los
diferentes usuarios, tambien se mudo la interfaz de la de defecto
a una creada por nosotros.
