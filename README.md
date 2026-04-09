# Dashboard Fitness con Astro

Proyecto estatico realizado para la actividad diagnostico de Frontend.

## Explicacion del proyecto

El proyecto es un dashboard fitness que centraliza seguimiento semanal de entrenamiento.
Incluye una pagina principal con secciones semanticas y comportamiento en cliente con JavaScript.

Secciones principales:

- Hero de contexto del panel
- Resumen de metricas
- Progreso de sesiones semanales (meta de 6 entrenamientos)
- Rutina por dia en formato Push / Pull / Legs
- Motivacion diaria con consejos aleatorios en espanol
- Seguimiento de peso con analisis de tendencia

## Funcionalidades interactivas

- Boton Entrene hoy para subir el contador semanal y la barra de progreso
- Boton Reiniciar para volver el contador a cero
- Selector de dia para ver la rutina correspondiente
- Consejos de motivacion en espanol al presionar Nuevo consejo
- Cambio de tema claro/oscuro con persistencia
- Analisis de peso (inicial vs actual) que muestra si subiste, bajaste o te mantuviste

Todos los datos interactivos se guardan en localStorage para mantener el estado al recargar.

## Herramientas usadas

- Astro
- HTML semantico
- CSS moderno y responsive
- JavaScript vanilla (eventos, manipulacion de DOM y localStorage)

## Requisitos de la consigna cubiertos

- 1 pagina principal
- 3 o mas secciones
- Responsive basico para mobile y desktop
- Comportamiento JavaScript (contador, rutinas dinamicas, consejos y analisis de peso)

Extras implementados:

- Componente reutilizable (Card.astro)
- Sistema de consejos en espanol
- Dark mode con persistencia en localStorage
- Seguimiento de peso corporal con tendencia

## Instrucciones para ejecutarlo

1. Instalar dependencias:

```bash
npm install
```

2. Ejecutar en desarrollo:

```bash
npm run dev
```

3. Build de produccion:

```bash
npm run build
```

4. Preview del build:

```bash
npm run preview
```
Martin Biosca 5toE
