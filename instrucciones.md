
# Creando tu cuenta y tu primer repositorio

## Paso 1: Crea tu cuenta de GitHub

1. **Ve al sitio web:** Abre tu navegador y visita [GitHub.com](https://github.com).
2. **Regístrate:** Haz clic en el botón "Sign up" o "Registrarse".
3. **Completa la información:** Ingresa tu correo electrónico, contraseña y nombre de usuario.
   - 💡 *Consejo:* Elige un nombre de usuario profesional (ej. tu nombre y apellido o una variación).
4. **Verifica tu cuenta:** Sigue las instrucciones para verificar tu correo electrónico.

🎉 ¡Felicidades! Ya eres parte de la comunidad de GitHub.

---

## Paso 2: Instala y configura Git en tu computadora

Git es la herramienta que te permitirá interactuar con GitHub desde tu computadora.

1. **Descarga Git:** Ve a [git-scm.com/downloads](https://git-scm.com/downloads) y descarga el instalador para tu sistema operativo.
2. **Instala Git:** Ejecuta el instalador y sigue los pasos. Puedes dejar las opciones predeterminadas.
3. **Configura tu identidad en Git:** Abre tu terminal y ejecuta:

   ```bash
   git config --global user.name "Tu Nombre Completo"
   git config --global user.email "tu.email@ejemplo.com"
El --global aplica esta configuración a todos tus proyectos en esta computadora.

Verifica la configuración:

bash
git config --global --list
Paso 3: Crea tu primer repositorio en GitHub (usando la interfaz web)
Inicia sesión en GitHub.

Crea un nuevo repositorio: Haz clic en el signo de más (+) y selecciona "New repository".

Completa los detalles:

Repository name: Ej. mi-primer-proyecto-prepa

Description (opcional): Ej. "Un proyecto de ejemplo para aprender Git y GitHub"

Public/Private: Elige "Public" o "Private"

Initialize this repository with: Marca "Add a README file"

Crea el repositorio: Haz clic en "Create repository".

Modifica el archivo README.md: Añade tus datos generales y una foto en formato Markdown.

Crea el archivo instrucciones.md: Copia esta actividad en formato Markdown.

Paso 4: Clona tu repositorio en tu computadora
En tu repositorio en GitHub: Haz clic en el botón verde "Code".

Copia la URL HTTPS.

Abre tu terminal: Navega a la carpeta donde guardarás tus proyectos:

bash
cd Documents/Projects
Clona el repositorio:

bash
git clone https://github.com/tu-usuario/mi-primer-proyecto-prepa.git
Entra a la carpeta del proyecto:

bash
cd mi-primer-proyecto-prepa
Conceptos clave
Repositorio (repo): Espacio donde se guarda tu proyecto.

Rama (branch): Línea principal de desarrollo (usamos main).

Commit: Registro de cambios con mensaje descriptivo.

Clonar (clone): Descargar una copia del repositorio.

Push: Enviar cambios al repositorio remoto.

Pull: Recibir cambios desde GitHub.

README.md: Archivo que describe tu proyecto.

.gitignore: Lista de archivos que Git debe ignorar.

📁 ¡Listo! Tu repositorio contiene README.md y instrucciones.md, y está preparado para comenzar a trabajar en tus proyectos.

Código

¿Quieres que te ayude a crear el contenido del `README.md` también? Puedo ay
