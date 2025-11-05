# Proyecto Bazar Frontend

Aplicación frontend del proyecto PBazar desarrollada con Angular. Proporciona la interfaz de usuario para la interacción con los servicios del backend.

## Requisitos Previos

- Node.js (versión 14 o superior)
- npm o yarn
- Angular CLI instalado globalmente (opcional)

## Instalación

Ejecutar el siguiente comando para instalar las dependencias del proyecto:

```bash
npm install
```

## Desarrollo

Para iniciar el servidor de desarrollo, ejecutar:

```bash
ng serve
```

Una vez iniciado el servidor, la aplicación estará disponible en http://localhost:4200. La aplicación se recargará automáticamente cuando se realicen modificaciones en los archivos fuente.

## Compilación

Para compilar el proyecto para producción, ejecutar:

```bash
ng build
```

Los archivos compilados se generarán en el directorio `dist/`. La compilación de producción incluye optimizaciones de rendimiento y tamaño.

## Generación de Componentes

Angular CLI proporciona herramientas para generar componentes, servicios y otros elementos del proyecto:

```bash
ng generate component nombre-componente
```

Para ver la lista completa de elementos que se pueden generar:

```bash
ng generate --help
```

## Pruebas

Para ejecutar las pruebas unitarias:

```bash
ng test
```

Para ejecutar pruebas end-to-end, es necesario configurar un framework de pruebas adicional según los requisitos del proyecto.

## Tecnologías Utilizadas

- Angular 20.3.8
- TypeScript
- Angular CLI 20.3.8

## Estructura del Proyecto

- src/: Código fuente de la aplicación
- src/app/: Módulos y componentes principales
- angular.json: Configuración del proyecto Angular
- package.json: Dependencias y scripts del proyecto
