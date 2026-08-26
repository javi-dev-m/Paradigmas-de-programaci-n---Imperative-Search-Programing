# Paradigmas-de-programación---Imperative-Search-Programing

# Introducción

Este programa fue desarrollado con motivos académicos, con el objetivo de describir los paradigmas de programación vigentes y cómo estos orientan la resolución de un problema.

**Caso de estudio:** Implementa un sistema de asignación de salas que procesa un flujo de solicitudes. La entrada tiene dos partes: un catálogo fijo de salas, cada una con capacidad y equipamiento, y una secuencia de solicitudes que llegan una tras otra, cada una con franja horaria, número de asistentes y equipamiento requerido. Para cada solicitud, el sistema determina la primera sala del catálogo que satisface las tres restricciones y que no está ocupada en esa franja, la asigna y continúa con la siguiente solicitud. Si ninguna sala sirve, registra el rechazo y su motivo. Al terminar el flujo, informa las asignaciones aceptadas y las rechazadas.

**Paradigma:** Programación imperativa con búsqueda

**Herramienta de implementación:** Icon

---

## Instalación y Compilación de Icon

Para ejecutar el programa es necesario tener instalado el lenguaje de programación **Icon** y disponer del compilador `icont`.

### 1. Descargar e instalar Icon

Descargue e instale Icon desde su sitio oficial:

https://www2.cs.arizona.edu/icon/

Una vez instalado, se recomienda comprobar que el compilador `icont` esté disponible desde la terminal.

En Windows, abra una ventana de **CMD** y ejecute:

```text
icont
