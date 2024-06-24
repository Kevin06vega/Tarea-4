# Tarea 4: Documentación de Código y Git

El propósito de esta tarea es practicar los conceptos de control de versiones bajo la implementación de Git y la creación de documentos de referencia utilizando MkDocs. El resultado final es un enlace (URL) que incluye la documentación, utilizando tu cuenta de GitHub como host para la página web.

## Instrucciones

### Objetivo

Documentar tres funciones que se utilizan para resolver EDOs (ecuaciones diferenciales ordinarias): `euler`, `rk2` y `rk4` del laboratorio de la Semana 13 "ODE.ipynb". Las tres funciones se deben encontrar en un archivo `ode.py` contenido en un directorio `ode`.

### Requisitos

1. **Repositorio en GitHub**:
   - Crea un nuevo repositorio en GitHub, por ejemplo, `ode-documentation`.
   - Clona el repositorio en tu máquina local.

2. **Estructura del Proyecto**:
   - Crea la siguiente estructura de directorios:
     ```
     ode-documentation/
     ├── docs/
     │   ├── index.md
     │   ├── reference.md
     ├── ode/
     │   ├── __init__.py
     │   ├── ode.py
     ├── mkdocs.yml
     ```

3. **Implementación de Funciones**:
   - Escribe las funciones `euler`, `rk2` y `rk4` en el archivo `ode/ode.py`, asegurándote de incluir docstrings para cada una siguiendo el estándar PEP 257.

4. **Documentación con MkDocs**:
   - Configura `mkdocs.yml` para definir el sitio de documentación.
   - En `docs/index.md`, escribe una introducción a los métodos.
   - En `docs/reference.md`, usa `mkdocstrings` para generar automáticamente la documentación de los docstrings.

5. **Generar y Desplegar la Documentación**:
   - Genera la documentación con `mkdocs build`.
   - Despliega la documentación en GitHub Pages con `mkdocs gh-deploy`.

### Entrega

Debes entregar un URL con el cual se acceda de manera pública a tu página web que contiene la documentación del código.

## Recursos

Para más información sobre cómo generar documentación con MkDocs, puedes seguir este [tutorial](https://realpython.com/python-project-documentation-with-mkdocs/).

## Contacto

Si tienes alguna duda, puedes contactar a:
- Marlon Brenes (marlon.brenes@utoronto.ca)

