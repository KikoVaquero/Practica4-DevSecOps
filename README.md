# Practica4-DevSecOps

## 1. Crear una imagen desde PHP

- Crear un `Dockerfile` que:
  - Parta de una imagen PHP oficial.
  - Copie una aplicación en PHP a un directorio dentro del contenedor.
    - La aplicación debe copiarse directamente desde un directorio del anfitrión.
    - Debe ser una aplicación sencilla que **no utilice bases de datos** (para evitar instalar MySQL).

## 2. Crear una imagen desde Ubuntu

- Crear un `Dockerfile` que:
  - Parta de una imagen Ubuntu.
  - Instale Apache y exponga el puerto 80.
  - Instale PHP.
  - Copie una aplicación web en PHP al directorio de Apache.
    - La aplicación debe descargarse automáticamente (por ejemplo, usando `git clone` o `curl`).
    - Debe ser sencilla y **no requerir bases de datos**.

## 3. Crear y probar contenedores

- Crear un contenedor para **cada una de las imágenes anteriores**.
- Verificar que funcionan correctamente.
- Parar y borrar los contenedores una vez comprobado.

## 4. Lanzar múltiples contenedores

- Usar un comando para lanzar **20 contenedores** de la segunda imagen.
  - Cada contenedor debe estar **mapeado a un puerto distinto** del anfitrión.
- Verificar que todos funcionan correctamente.
- Parar y borrar todos los contenedores.

---

# Git

- Mantener un **repositorio público en Git** con:
  - Una **memoria** de la práctica.
  - El fichero `Dockerfile`.
