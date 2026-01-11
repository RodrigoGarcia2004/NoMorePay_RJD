# NoMorePay — Gestor de suscripciones y pruebas gratis

NoMorePay es una app Android pensada para ayudar a no pagar de más: organiza **suscripciones**, **pruebas gratis** y **promociones**, y permite llevar un control para recordar cuándo pueden empezar a cobrarte.
## Autores
- Javier Escudero Garcia
- Diego 
- Rodrigo 

## Introducción y objetivos
El objetivo del proyecto es crear una app funcional con varias pantallas y navegación, aplicando buenas prácticas de desarrollo en Android.  
En esta primera fase se prioriza tener una app **navegable**, con interfaz cuidada y datos de ejemplo para validar el flujo.

## Estado del proyecto 
- Categorías superiores: Suscripciones, Pruebas gratis, Promociones, Apps, Servicios. 
- Pantalla principal con lista de servicios (ejemplo: Netflix, Spotify, Amazon Prime, etc.). 
- Botón principal “Empezar”.

## Decisiones clave de diseño/desarrollo
- Interfaz base con diseño tipo home (header + chips/categorías + lista). 
- Listado de elementos con tarjetas (Cards) para cada servicio.
- Navegación preparada para ampliar a:
  - Alta/edición de una suscripción
  - Vista de detalle
  - Alertas/recordatorios (fases posteriores)

## Requisitos técnicos
- Android Studio + Kotlin
- Jetpack Compose 
- Navigation Compose

## Cómo ejecutar
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/TU_REPO.git

## Conclusiones
En esta fase se ha conseguido una app navegable y estable con las pantallas mínimas requeridas, dejando preparada la base para añadir MVVM, persistencia y red en fases posteriores.
