# ICS 6030 PROGRAMACIÓN DE APP PARA DISPOSITIVOS MÓVILES
# TSASDS - 3º AÑO PROF. GERARDO RENÉ ROSALES
# TRABAJO PRÁCTICO Nº 1
### Fundamentos y Ecosistemas del Desarrollo Móvil
Realizar el siguiente trabajo práctico en el repositorio de github asignado para la
### actividad. 
Se deberán contestar las preguntas y subirlas como README.md
### 1 - ¿Cuáles son los principales sistemas operativos para dispositivos móviles en la
### actualidad?
### 2 - ¿Cuáles son las principales diferencias técnicas entre el desarrollo nativo para iOS y
### para Android en la actualidad?
### 3 - ¿A qué nos referimos cuando hablamos de desarrollo nativo en programación de
APP móviles? ¿Qué ventajas ofrece sobre el desarrollo multiplataforma?
### 4 - ¿Qué ventaja principal ofrece un Framework Multiplataforma (como Flutter o React
Native) frente al desarrollo nativo?
### 5 - En el contexto de la arquitectura móvil, ¿cuál es la función de una API REST importa
el sistema operativo desde el cuál se consuma la API o es indistinto?
### DESARROLLO
### 1 - ¿Cuáles son los principales sistemas operativos para dispositivos móviles en la
### actualidad?
La mayoría de los teléfonos inteligentes funcionan con unos pocos sistemas operativos principales para dispositivos móviles, incluidos Apple iOS, Google Android.
| Sistema Operativo | Caracteristicas | Desarrollo Nativo | Multiplataforma (Flutter) |Multiplataforma (Reac Native) |
| :---: | :--- | :--- | :--- | :--- |
| Andorid | 1. Código Abierto. (Open Source). | 1. Entorno Android studio | 1. Lenguaje Flutter/Dark + (Java y kotlin) | 1. Componentes Nativos Reales |
|         | 2. Multitarea Real. | 2. Lenguajes: Java/kotlin | 2. Renderizado Propio (Skia/Impeller) | 2. Basado en React y JavaScript |
|         | 3. Ecosistema Google Play. | 3. Ventaja clave: Acceso inmediato a las últimas funciones de Android en cuanto salen al mercado | 3. Compilación en Código Nativo | 3.Fast Refresh (Recarga instantánea) |
| IOS | 1. Codigo Cerrado         | 1. Lenguajes: Swift | 1. Rendimiento en iOS: Fluido  | 1. Arquitectura "Fabric" |
|     | 2. Seguridad y Privacidad | 2. (IDE): Xcode | 2. Compilación: a lenguaje binario | 2. Uso de "Hermes" optimizado |
|     | 3. App Store              | 3. Ventaja clave: Apple es muy estricto con la experiencia de usuario (UX). El desarrollo nativo te da acceso total a tecnologías exclusivas como FaceID, Apple Pay, y los últimos avances en realidad aumentada con ARKit. | 3. Renderizado: Motor Impeller | 3. CocoaPods Integrado |