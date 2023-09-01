# Calculadora de Propinas

Este proyecto es una calculadora de propinas que utiliza un archivo JSON para acceder a los datos y precios de los platos de comida, permitiéndote calcular el precio total, cantidades y propinas de manera sencilla.

## Requisitos Previos

Antes de ejecutar la calculadora de propinas, asegúrate de tener instalada la extensión `json-server`, la cual es necesaria para cargar los datos desde un archivo JSON. Puedes instalarla utilizando el siguiente comando:

```bash
npm install -g json-server
```
# Instrucciones de Uso
1. Abre una terminal o consola de comandos en la ubicación donde has clonado este repositorio.

2. Ejecuta el siguiente comando para iniciar json-server y cargar los datos desde el archivo __db.json__:

```bash
json-server --watch db.json --port 4000
```

Asegúrate de que estás ubicado en la carpeta raíz del proyecto para que __json-server__ pueda acceder al archivo __db.json__.

1. Con __json-server__ en funcionamiento, podrás utilizar la calculadora de propinas abriendo el archivo __index.html__ en tu navegador web.

#Contribuciones 
Si deseas contribuir a este proyecto, ¡siéntete libre de abrir una solicitud de extracción (Pull Request)!

¡Disfruta calculando tus propinas con esta calculadora de propinas simple pero útil!

__Readme creado con chatGPT__
