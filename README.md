# 🚀 Laboratorio 0: Configuración de Entorno y Git
## Curso: ELO320 - Estructuras de Datos y Algoritmos (2026-1)

¡Bienvenida/o al curso! Esta es tu primera actividad oficial. No te preocupes, no evaluaremos código complejo aún. El objetivo es que domines las herramientas que usaremos todo el semestre para entregar tus proyectos: **Git y GitHub Classroom**.

---

## 🎯 Objetivos de Aprendizaje
1. Configurar tu identidad local de Git.
2. Clonar un repositorio privado generado por **GitHub Classroom**.
3. Practicar el flujo básico: `add` -> `commit` -> `push`.
4. Aprender sintaxis básica de **Markdown** para documentación.

---

## 🛠️ Paso 1: Configuración Inicial
Antes de empezar, asegúrate de que Git sepa quién eres. Abre tu terminal y ejecuta:

```bash
git config --global user.name "Tu Nombre Real"
git config --global user.email "tu-correo-institucional@ejemplo.com"
```
## 📂 Paso 2: Clonar el Repositorio

Copia la URL de este repositorio (botón verde Code) y clónalo en tu computadora:
```bash
git clone <URL_DE_TU_REPOSITORIO>
cd lab-0-git-tu-usuario
```
## ✍️ Paso 3: Crear tu Perfil

En este curso, la documentación es tan importante como el código. Sigue estos pasos:

* Ve a la carpeta llamada /estudiantes.
* Crea un nuevo archivo llamado perfil-tuusuario.md (reemplaza "tuusuario" por tu nombre de usuario de GitHub).
* Dentro del archivo, escribe lo siguiente usando Markdown:
  * Un título principal (#) con tu nombre.
  * Un subtítulo (##) que diga "Intereses en EDA".
  * Una lista con viñetas de 3 estructuras de datos o algoritmos que quieras aprender (ej. Árboles Binarios, Algoritmo de Dijkstra, Pilas).
  * Una frase en negrita sobre por qué decidiste estudiar computación.

## 📤 Paso 4: Subir tu Trabajo (El flujo de Git)

Una vez guardado tu archivo, ejecuta los siguientes comandos en orden:

Staging: Prepara el archivo para el envío.
```bash
git add estudiantes/perfil-tuusuario.md
```
Commit: Crea un "punto de control" con un mensaje descriptivo.
``` Bash
git commit -m "Añadiendo perfil de [Tu Nombre]"
```
Push: Sube tus cambios a GitHub.
```Bash
git push origin main
```
## ✅ ¿Cómo sé si terminé?

Refresca la página de este repositorio en tu navegador.

Si ves tu archivo dentro de la carpeta /estudiantes, ¡lo lograste! 🥳

GitHub Classroom detectará automáticamente tu envío.

## 📚 Recursos Útiles

    Guía rápida de Markdown

    ¿Qué es un Commit?

    Documentación de GitHub Classroom






¿Te gustaría que prepare también el archivo `.gitignore` estándar para el curso o pasamos a definir los criterios de éxito de esta actividad?
