# Proyecto Postman – Pruebas de API

Este repositorio contiene una colección de **Postman** y un reporte generado a partir de las pruebas realizadas sobre la API de productos.

## Contenido del repositorio

- **Products.postman_collection.json**  
  Archivo de colección de Postman que incluye los endpoints utilizados para realizar pruebas (GET, POST, PUT, DELETE).

- **Products-2025-08-19-00-26-56-819-0.html**  
  Reporte en formato HTML con los resultados de la ejecución de la colección en Postman/Newman.

- **.git/**  
  Carpeta de control de versiones de Git.

## Requisitos

- Tener instalado [Postman](https://www.postman.com/downloads/) o [Newman](https://www.npmjs.com/package/newman).
- Node.js (si deseas ejecutar con Newman desde la terminal).

## Uso

### 1. Importar colección en Postman
1. Abrir Postman.  
2. Seleccionar **Import**.  
3. Cargar el archivo `Products.postman_collection.json`.  

### 2. Ejecutar colección con Newman
```bash
newman run Products.postman_collection.json -r html
