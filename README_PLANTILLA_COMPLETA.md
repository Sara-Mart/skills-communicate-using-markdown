# 🚀 Nombre del proyecto

> Plantilla completa de `README.md` para proyectos de GitHub.

Breve descripción del proyecto. Explica **qué es**, **para qué sirve** y
**qué problema resuelve**.

![Status](https://img.shields.io/badge/status-in%20development-yellow)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

------------------------------------------------------------------------

## 📑 Índice

-   [📖 Descripción](#-descripción)
-   [✨ Características](#-características)
-   [🛠️ Tecnologías](#️-tecnologías)
-   [📋 Requisitos](#-requisitos)
-   [📦 Instalación](#-instalación)
-   [▶️ Uso](#️-uso)
-   [📁 Estructura del proyecto](#-estructura-del-proyecto)
-   [🌐 API](#-api)
-   [📸 Capturas](#-capturas)
-   [🎥 Demo](#-demo)
-   [🔐 Variables de entorno](#-variables-de-entorno)
-   [🏗️ Arquitectura](#️-arquitectura)
-   [🧪 Tests](#-tests)
-   [🐛 Problemas conocidos](#-problemas-conocidos)
-   [🤝 Contribuciones](#-contribuciones)
-   [📚 Documentación](#-documentación)
-   [👩‍💻 Autora](#-autora)
-   [📄 Licencia](#-licencia)

------------------------------------------------------------------------

## 📖 Descripción

Explicación detallada del proyecto.

Puedes usar **negrita**, *cursiva*, ***negrita y cursiva*** y ~~texto
tachado~~.

También puedes utilizar `código dentro de una frase`, por ejemplo
`npm install`.

> 💡 Consejo: utiliza esta sección para explicar rápidamente el objetivo
> del proyecto.

> \[!NOTE\] Esta es una nota importante.

> \[!TIP\] Este es un consejo útil.

> \[!IMPORTANT\] Información especialmente relevante.

> \[!WARNING\] Ten cuidado con esta parte.

> \[!CAUTION\] Esta acción puede provocar problemas.

------------------------------------------------------------------------

## ✨ Características

### Lista normal

-   Característica 1
-   Característica 2
-   Característica 3

### Lista ordenada

1.  Primera característica
2.  Segunda característica
3.  Tercera característica

### Lista con subelementos

-   Frontend
    -   HTML
    -   CSS
    -   JavaScript
-   Backend
    -   Java
    -   Spring Boot
-   Base de datos
    -   MySQL

### Checklist

-   [x] Crear proyecto
-   [x] Crear estructura
-   [x] Añadir frontend
-   [ ] Añadir backend
-   [ ] Añadir autenticación
-   [ ] Publicar proyecto

------------------------------------------------------------------------

## 🛠️ Tecnologías

  Tecnología     Versión              Uso
  ------------- --------- ---------------
  HTML              5          Estructura
  CSS               3              Diseño
  JavaScript       ES6             Lógica
  Angular          20            Frontend
  Java             21             Backend
  Spring Boot      3.x           API REST
  MySQL             8       Base de datos

### Badges de tecnologías

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring
Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

------------------------------------------------------------------------

## 📋 Requisitos

Antes de comenzar necesitas tener instalado:

-   Git
-   Node.js
-   npm
-   Angular CLI
-   Java 21
-   MySQL

Puedes comprobar las versiones:

``` bash
git --version
node --version
npm --version
java --version
```

------------------------------------------------------------------------

## 📦 Instalación

### 1. Clonar el repositorio

``` bash
git clone https://github.com/usuario/nombre-proyecto.git
```

### 2. Entrar en la carpeta

``` bash
cd nombre-proyecto
```

### 3. Instalar dependencias

``` bash
npm install
```

### 4. Configurar la base de datos

Crea una base de datos:

``` sql
CREATE DATABASE nombre_base_datos;
```

### 5. Configurar el proyecto

Copia el archivo de configuración:

``` bash
cp .env.example .env
```

Después modifica los valores necesarios.

------------------------------------------------------------------------

## ▶️ Uso

Para iniciar el proyecto:

``` bash
npm start
```

O, si utilizas Angular:

``` bash
ng serve
```

Después abre:

``` text
http://localhost:4200
```

### Ejemplo

``` javascript
const mensaje = "Hola GitHub";

console.log(mensaje);
```

### Java

``` java
public class Main {

    public static void main(String[] args) {
        System.out.println("Hola GitHub");
    }
}
```

### JSON

``` json
{
  "nombre": "Sara",
  "proyecto": "Mi proyecto",
  "version": "1.0.0"
}
```

### Bash

``` bash
npm install
npm run build
npm start
```

------------------------------------------------------------------------

## 📁 Estructura del proyecto

``` text
nombre-proyecto/
├── src/
│   ├── components/
│   ├── services/
│   ├── models/
│   └── pages/
├── public/
├── images/
│   ├── home.png
│   └── login.png
├── tests/
├── .env.example
├── .gitignore
├── package.json
└── README.md
```

------------------------------------------------------------------------

## 🌐 API

Si el proyecto tiene una API REST:

  Método   Endpoint            Descripción
  -------- ------------------- --------------------
  GET      `/api/users`        Obtener usuarios
  GET      `/api/users/{id}`   Obtener usuario
  POST     `/api/users`        Crear usuario
  PUT      `/api/users/{id}`   Actualizar usuario
  DELETE   `/api/users/{id}`   Eliminar usuario

### Ejemplo de petición

``` bash
curl http://localhost:8080/api/users
```

### Ejemplo de respuesta

``` json
[
  {
    "id": 1,
    "nombre": "Sara"
  }
]
```

------------------------------------------------------------------------

## 📸 Capturas

### Página principal

![Página principal](./images/home.png)

### Login

![Login](./images/login.png)

### Imágenes centradas

```{=html}
<p align="center">
```
`<img src="./images/home.png" width="45%" alt="Página principal">`{=html}
`<img src="./images/login.png" width="45%" alt="Login">`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## 🎥 Demo

[▶️ Ver demostración del proyecto](https://www.youtube.com/)

También puedes utilizar una imagen como enlace:

[![Demo del
proyecto](./images/video-preview.png)](https://www.youtube.com/)

------------------------------------------------------------------------

## 🔐 Variables de entorno

Crea un archivo `.env`:

``` env
DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=
DB_NAME=nombre_base_datos
```

> \[!WARNING\] Nunca subas contraseñas, API keys, tokens u otros
> secretos reales a GitHub.

Añade `.env` al `.gitignore`:

``` gitignore
.env
```

------------------------------------------------------------------------

## 🏗️ Arquitectura

``` text
┌──────────────┐
│   Frontend   │
│   Angular    │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│   API REST   │
│ Spring Boot  │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│   Database   │
│    MySQL     │
└──────────────┘
```

------------------------------------------------------------------------

## 🧪 Tests

Ejecutar los tests:

``` bash
npm test
```

Ejemplo de resultado:

``` text
Tests: 15 passed
Tests: 0 failed
```

------------------------------------------------------------------------

## 🐛 Problemas conocidos

Actualmente pueden existir los siguientes problemas:

-   Problema 1
-   Problema 2
-   Problema 3

### Soluciones

> \[!NOTE\] Añade aquí soluciones o workarounds para problemas
> conocidos.

------------------------------------------------------------------------

## ❓ FAQ

```{=html}
<details>
```
```{=html}
<summary>
```
¿Qué tecnologías utiliza el proyecto?
```{=html}
</summary>
```
Angular, TypeScript, Java, Spring Boot y MySQL.

```{=html}
</details>
```
```{=html}
<details>
```
```{=html}
<summary>
```
¿Cómo se instala?
```{=html}
</summary>
```
Clona el repositorio y ejecuta `npm install`.

```{=html}
</details>
```
```{=html}
<details>
```
```{=html}
<summary>
```
¿Dónde puedo encontrar la documentación?
```{=html}
</summary>
```
Puedes consultar la sección de documentación de este README.

```{=html}
</details>
```

------------------------------------------------------------------------

## 🔗 Enlaces

-   [GitHub](https://github.com/)
-   [Angular](https://angular.dev/)
-   [Spring Boot](https://spring.io/projects/spring-boot)
-   [Java](https://www.java.com/)
-   [MySQL](https://www.mysql.com/)

### Enlace a otro archivo del repositorio

[📚 Ver documentación](./docs/documentacion.md)

------------------------------------------------------------------------

## 🤝 Contribuciones

Las contribuciones son bienvenidas.

1.  Haz un fork del proyecto.
2.  Crea una rama:

``` bash
git checkout -b feature/nueva-funcionalidad
```

3.  Realiza tus cambios.
4.  Haz commit:

``` bash
git add .
git commit -m "Añadir nueva funcionalidad"
```

5.  Haz push:

``` bash
git push origin feature/nueva-funcionalidad
```

6.  Abre un Pull Request.

------------------------------------------------------------------------

## 📚 Documentación

-   [Documentación oficial de Angular](https://angular.dev/)
-   [Documentación oficial de Spring
    Boot](https://spring.io/projects/spring-boot)
-   [Documentación de Java](https://docs.oracle.com/en/java/)
-   [Documentación de MySQL](https://dev.mysql.com/doc/)

------------------------------------------------------------------------

## 👩‍💻 Autora

**Nombre Apellido**

-   GitHub: [@usuario](https://github.com/usuario)
-   Portfolio: [Mi portfolio](https://example.com)
-   Email: ejemplo@email.com

------------------------------------------------------------------------

## 📄 Licencia

Este proyecto está bajo la licencia MIT.

Consulta el archivo [LICENSE](./LICENSE) para más información.

------------------------------------------------------------------------

## 📝 Citas

> "Una frase o cita relacionada con el proyecto."

También puedes hacer citas anidadas:

> Primera cita.
>
> > Cita dentro de otra cita.

------------------------------------------------------------------------

## 📊 Tabla de ejemplo

  Elemento   Descripción           Estado
  ---------- --------------------- --------
  Frontend   Interfaz de usuario   ✅
  Backend    API REST              🚧
  Database   Base de datos         ✅
  Tests      Pruebas               ❌

------------------------------------------------------------------------

## 🔽 Contenido desplegable

```{=html}
<details>
```
```{=html}
<summary>
```
Mostrar información adicional
```{=html}
</summary>
```
Este contenido permanece oculto hasta que el usuario pulsa sobre el
título.

Puedes incluir:

-   Texto
-   Listas
-   Código
-   Imágenes

```{=html}
</details>
```

------------------------------------------------------------------------

## 🖼️ HTML dentro de Markdown

Markdown permite utilizar HTML en GitHub.

### Texto centrado

```{=html}
<p align="center">
```
Texto centrado.
```{=html}
</p>
```
### Título centrado

```{=html}
<h1 align="center">
```
🚀 Mi proyecto
```{=html}
</h1>
```
### Imagen con tamaño personalizado

`<img src="./images/logo.png" width="300" alt="Logo">`{=html}

### Texto pequeño

`<small>`{=html}Texto secundario.`</small>`{=html}

### Subíndice

H`<sub>`{=html}2`</sub>`{=html}O

### Superíndice

X`<sup>`{=html}2`</sup>`{=html}

------------------------------------------------------------------------

## 🎨 Elementos de texto

**Negrita**

*Cursiva*

***Negrita + cursiva***

~~Tachado~~

`Código inline`

------------------------------------------------------------------------

## ➖ Separadores

------------------------------------------------------------------------

------------------------------------------------------------------------

------------------------------------------------------------------------

## 💬 Comentarios ocultos

```{=html}
<!--
Este comentario NO será visible en GitHub.
Puedes utilizarlo para dejarte notas mientras editas el README.
-->
```

------------------------------------------------------------------------

## 🔣 Caracteres especiales

Puedes escapar caracteres Markdown utilizando `\`:

``` markdown
\*Esto no será cursiva\*
\# Esto no será un título
```

Resultado:

\*Esto no será cursiva\*

\# Esto no será un título

------------------------------------------------------------------------

## 📌 Enlaces internos

Puedes enlazar directamente a una sección:

[Ir a tecnologías](#️-tecnologías)

[Ir a instalación](#-instalación)

[Ir a autora](#-autora)

------------------------------------------------------------------------

## 🗂️ Checklist final del README

Antes de publicar el proyecto:

-   [ ] El título es claro
-   [ ] La descripción explica qué hace el proyecto
-   [ ] He añadido las tecnologías
-   [ ] He explicado la instalación
-   [ ] He explicado cómo ejecutarlo
-   [ ] He añadido capturas
-   [ ] He añadido una demo si existe
-   [ ] No hay contraseñas ni secretos
-   [ ] Los enlaces funcionan
-   [ ] El README no contiene información incorrecta
-   [ ] He añadido licencia si corresponde
-   [ ] He revisado la ortografía

------------------------------------------------------------------------

# 🧰 Chuleta rápida de Markdown

  Quiero escribir     Markdown
  ------------------- -----------------------
  Título              `# Título`
  Subtítulo           `## Título`
  Negrita             `**texto**`
  Cursiva             `*texto*`
  Tachado             `~~texto~~`
  Código              `` `código` ``
  Enlace              `[texto](URL)`
  Imagen              `![alt](URL)`
  Lista               `- elemento`
  Lista ordenada      `1. elemento`
  Checkbox            `- [ ] tarea`
  Checkbox marcado    `- [x] tarea`
  Cita                `> texto`
  Línea               `---`
  Código multilínea   ```` ```lenguaje ````
  Comentario HTML     `<!-- comentario -->`

------------------------------------------------------------------------

# 🚀 FIN DE LA PLANTILLA

Puedes copiar este archivo y eliminar las secciones que no necesites
para cada proyecto.

```{=html}
<!--
NOTA PARA LA AUTORA:
No es necesario utilizar todas las secciones.
Un README profesional debe ser claro y útil, no necesariamente enorme.
-->
```
