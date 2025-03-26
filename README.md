# Manejo Ramas

Este proyecto es una aplicación que maneja diferentes clases relacionadas con problemas y su gestión. En este archivo se explica cómo se estructuran las ramas en el repositorio, qué cambios se han realizado en cada rama, y cómo se afectan mutuamente las clases y el proyecto.

## Ramas y su Propósito

### Rama `main`
La rama `main` contiene el código base del proyecto. En esta rama se configuran los ajustes principales, como la configuración de `.gitignore` y otras configuraciones globales.

**Últimos commits:**
- **43cb487** - *Config .gitignore*: Configuración básica de `.gitignore` para ignorar archivos específicos del entorno de Eclipse.
- **fa9d299** - *Eliminar archivos específicos de Eclipse*: Eliminación de archivos generados por Eclipse que no deben ser versionados.
- **7a5f04a** - *guardar cambios*: Commit inicial para realizar una primera versión del proyecto.

### Rama `Problema1`
La rama `Problema1` se creó para implementar y realizar cambios relacionados con el "Problema 1". Se trabajó principalmente en la implementación de las clases necesarias para este problema.

**Últimos commits:**
- **32b5fe6** - *Clase 2*: Se agregó la clase 2 para gestionar los datos del "Problema 1".
- **192378c** - *Clase 1*: Se implementó la clase 1, que se encarga de la lógica principal para "Problema 1".
- **43cb487** - *Config .gitignore*: Aseguramos que los cambios en `.gitignore` se aplicaran correctamente también en esta rama.

**Impacto en el proyecto:**
- Esta rama introdujo cambios en las clases `Clase1.java` y `Clase2.java`, que son fundamentales para la resolución del "Problema 1". Estas clases manejan la entrada de datos y procesan la información específica del problema.

### Rama `Problema2`
La rama `Problema2` se creó para implementar y trabajar en el "Problema 2". Aquí se realizaron modificaciones similares pero para abordar un problema distinto dentro del proyecto.

**Últimos commits:**
- **d73179d** - *Clase 2*: Se añadió la clase 2, adaptada para manejar los requerimientos específicos del "Problema 2".
- **1f19828** - *Clase 1*: Implementación de la clase 1 para gestionar los datos y procesos asociados con el "Problema 2".
- **43cb487** - *Config .gitignore*: Los mismos cambios de `.gitignore` que en la rama `Problema1` se aplicaron aquí también.

**Impacto en el proyecto:**
- Las clases `Clase1.java` y `Clase2.java` se modificaron o se volvieron a implementar para adaptarse a los requisitos del "Problema 2". Estas modificaciones afectan el flujo de datos y el procesamiento que anteriormente se realizaba en la rama `Problema1`.

## ¿Cómo se afectan las ramas?

- **Rama `main`**: Sirve como la base para las ramas `Problema1` y `Problema2`. Las configuraciones iniciales, como el archivo `.gitignore`, se aplican en todas las ramas.
- **Rama `Problema1` y `Problema2`**: Ambas ramas se crearon a partir de `main` y contienen cambios específicos para resolver problemas distintos. Aunque ambas ramas tienen cambios en las clases `Clase1.java` y `Clase2.java`, sus implementaciones son diferentes para abordar problemas distintos.

## ¿Cómo afectan las ramas al código?
- Las ramas `Problema1` y `Problema2` tienen commits que afectan directamente las clases `Clase1` y `Clase2`. Aunque ambas ramas incluyen cambios en el archivo `.gitignore`, los cambios en el código son específicos a cada problema.
- La rama `main` se mantiene como la base y no contiene cambios específicos de los problemas, pero se encarga de la configuración global que afecta a todo el proyecto.

## Resumen
Cada rama en este proyecto tiene un propósito claro:
- **`main`** contiene la configuración global.
- **`Problema1`** y **`Problema2`** son ramas dedicadas a resolver problemas específicos con implementaciones diferentes de las clases principales.
