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
### *1**. ¿Cuáles son los principales sistemas operativos para dispositivos móviles en la
### actualidad?

La mayoría de los teléfonos inteligentes funcionan con unos pocos sistemas operativos principales para dispositivos móviles, incluidos Apple iOS, Google Android.
| **Sistema Operativo** | **Caracteristicas** | **Desarrollo Nativo** | **Multiplataforma (Flutter)** |**Multiplataforma (Reac Native)** |
| :---: | :--- | :--- | :--- | :--- |
| **Andorid** | 1. Código Abierto. (Open Source). | 1. Entorno Android studio | 1. Lenguaje Flutter/Dark + (Java y kotlin) | 1. Componentes Nativos Reales |
|         | 2. Multitarea Real. | 2. Lenguajes: Java/kotlin | 2. Renderizado Propio (Skia/Impeller) | 2. Basado en React y JavaScript |
|         | 3. Ecosistema Google Play. | 3. Ventaja clave: Acceso inmediato a las últimas funciones de Android en cuanto salen al mercado | 3. Compilación en Código Nativo | 3.Fast Refresh (Recarga instantánea) |
| **IOS** | 1. Codigo Cerrado         | 1. Lenguajes: Swift | 1. Rendimiento en iOS: Fluido  | 1. Arquitectura "Fabric" |
|     | 2. Seguridad y Privacidad | 2. (IDE): Xcode | 2. Compilación: a lenguaje binario | 2. Uso de "Hermes" optimizado |
|     | 3. App Store              | 3. Ventaja clave: Apple es muy estricto con la experiencia de usuario (UX). El desarrollo nativo te da acceso total a tecnologías exclusivas como FaceID, Apple Pay, y los últimos avances en realidad aumentada con ARKit. | 3. Renderizado: Motor Impeller | 3. CocoaPods Integrado 

---

### **2**. ¿Cuáles son las principales diferencias técnicas entre el desarrollo nativo para iOS y
### para Android en la actualidad?

### Diferencias Técnicas: iOS Nativo vs. Android Nativo

| **Característica** | **Desarrollo Nativo iOS** | **Desarrollo Nativo Android** |
| :--- | :--- | :--- |
| **Lenguaje** | Swift / Objective-C | Kotlin / Java |
| **IDE (Editor)** | Xcode | Android Studio |
| **Sistema Operativo Base** | Exclusivo de macOS | Windows, macOS, Linux |
| **Interfaz (UI)** | SwiftUI / UIKit | Jetpack Compose / XML |
| **Gestión de Memoria** | ARC (Automatic Reference Counting) | Garbage Collector |
| **Fragmentación** | Baja (Ecosistema cerrado) | Alta (Múltiples marcas y modelos) |

---

### **3**. Desarrollo Nativo: Definición y Ventajas

| **Concepto / Ventaja** | **Descripción** |
| :--- | :--- |
| **Definición** | Desarrollo usando lenguajes y SDKs oficiales de cada fabricante (Apple/Google). |
| **Rendimiento** | Máximo, al ejecutarse directamente sobre el hardware sin capas intermedias. |
| **Acceso a Hardware** | Acceso total e inmediato a nuevas funciones (sensores, biometría, cámara). |
| **UX / UI** | Cumplimiento total de las guías de diseño (Human Interface vs. Material Design). |
| **Estabilidad** | Menor riesgo de errores por dependencias de terceros. |

---

### **4**. Ventaja del Desarrollo Multiplataforma (Flutter / React Native)

| **Factor** | **Ventaja Multiplataforma** |
| :--- | :--- |
| **Base de Código** | **Código único:** Se programa una vez y funciona en iOS y Android. |
| **Costos** | Reducción significativa (un solo equipo de desarrollo). |
| **Tiempo (Time-to-market)** | Lanzamiento simultáneo en ambas tiendas más rápido. |
| **Mantenimiento** | Actualizaciones y correcciones centralizadas en un solo repositorio. |
| **Hot Reload** | Permite ver cambios en el código casi instantáneamente en el dispositivo. |

---

### **5**. API REST en la Arquitectura Móvil

| **Aspecto** | **Función y Compatibilidad** |
| :--- | :--- |
| **Función Principal** | Comunicación entre el cliente (App) y el servidor (Base de datos). |
| **Formato de Datos** | Generalmente JSON (estándar universal). |
| **Dependencia del SO** | **Indistinto:** El sistema operativo no afecta el consumo de la API. |
| **Protocolo** | HTTP / HTTPS. |
| **Universalidad** | Una misma API sirve para iOS, Android, Web y Desktop simultáneamente. |

---

### Videos Explicativos Sobre Android/IOS

[![Que es IOS](v=rZmAfuo70PY)](https://www.youtube.com/watch?v=rZmAfuo70PY)