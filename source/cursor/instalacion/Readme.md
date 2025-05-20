# Curso Introductorio de CURSOR (Editor con IA)

---

## 🔧 Bloque 2: Instalación y Configuración

### Requisitos previos:

* Cuenta activa en GitHub.
* Node.js (recomendado LTS): [https://nodejs.org](https://nodejs.org)
* Git: [https://git-scm.com](https://git-scm.com)
* Conexión a internet estable.

---

### Requisitos previos:

* Cuenta activa en GitHub.
* Node.js (recomendado LTS): [https://nodejs.org](https://nodejs.org)
* Git: [https://git-scm.com](https://git-scm.com)
* Conexión a internet estable.

---

### Instalación en Windows:

1. Accede a [https://cursor.so/](https://cursor.so/) y descarga la versión para Windows.
2. Ejecuta el archivo `.exe` descargado.
3. Sigue las instrucciones del instalador (siguiente > siguiente > instalar).
4. Abre CURSOR desde el menú de inicio. 🟡 *La primera vez puede tardar unos segundos en cargar completamente.*
5. Inicia sesión con tu cuenta de GitHub cuando se te solicite.

---

### Instalación en macOS:

1. Descarga el archivo `.dmg` desde [https://cursor.so/](https://cursor.so/).
2. Arrastra el icono de CURSOR a la carpeta de Aplicaciones.
3. Abre CURSOR (si aparece advertencia de seguridad, haz clic derecho > "Abrir").
4. Inicia sesión con tu cuenta de GitHub.

---

### Instalación en Linux:

1. Descarga el archivo `.AppImage` o `.deb` desde el sitio oficial.
2. Da permisos de ejecución al archivo (en terminal):

   ```bash
   chmod +x cursor-x.y.z.AppImage
   ```
3. Ejecuta el archivo desde terminal:

   ```bash
   ./cursor-x.y.z.AppImage
   ```
4. O instala con:

   ```bash
   sudo dpkg -i cursor-x.y.z.deb
   ```
5. Abre CURSOR desde tu menú de aplicaciones e inicia sesión con GitHub. 🟡 *Puede tardar unos segundos la primera vez.*

---

### Verificaciones iniciales

* ✅ Verifica que puedes abrir proyectos locales o carpetas.
* ✅ Confirma que el botón "Ask Cursor" aparece en la parte superior.
* ✅ Haz una prueba: selecciona un bloque de código y presiona `Ctrl + K` / `Cmd + K`.

---

### Configuración inicial sugerida

* Ve a **Preferences > Theme** y elige un tema oscuro o claro según tu preferencia.
* Activa el modelo GPT-4 (si está disponible) desde el panel lateral.
* Conecta tu cuenta de GitHub para sincronizar proyectos si usas control de versiones.

---

### 🧪 Práctica guiada

1. Instala CURSOR en tu equipo.

2. Crea una carpeta llamada `mi-primer-cursor`.

3. Abre CURSOR y selecciona esa carpeta como proyecto.

4. Crea un archivo `index.js` con el contenido:

   ```js
   console.log("Hola desde CURSOR!");
   ```

5. Selecciona la línea y presiona `Ctrl + K` para preguntarle a la IA:
   “¿Qué hace esta línea?”

---

### Solución de problemas comunes

| Problema                              | Solución                                                                     |
| ------------------------------------- | ---------------------------------------------------------------------------- |
| No se abre CURSOR tras instalación    | Reinicia el sistema o ejecuta como administrador.                            |
| No inicia sesión con GitHub           | Asegúrate de que tu navegador predeterminado esté correctamente configurado. |
| No aparece el botón "Ask Cursor"      | Cierra y vuelve a abrir el proyecto o reinicia CURSOR.                       |
| El AI no responde o se queda cargando | Verifica tu conexión y que tienes acceso al modelo (GPT-4 o default).        |
| Error en terminal o consola integrada | Revisa los permisos del sistema o reinstala Node.js y Git.                   |

---
