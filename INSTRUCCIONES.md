# 📱 INSTRUCCIONES DE INSTALACIÓN EN TABLET ANDROID

## Opción 1: Instalación Rápida (Recomendada)

### Paso 1: Subir los archivos a internet
Los archivos deben estar accesibles desde una URL. Puedes usar:
- **GitHub Pages** (gratis y fácil)
- **Netlify** (gratis)
- **Vercel** (gratis)
- Cualquier servidor web

### Paso 2: Abrir en Chrome
1. Abre **Google Chrome** en tu tablet Android
2. Ve a la URL donde subiste los archivos
3. Verás el horario funcionando

### Paso 3: Instalar la app
1. Toca el menú de Chrome (los 3 puntos arriba a la derecha)
2. Selecciona **"Añadir a pantalla de inicio"** o **"Instalar app"**
3. Confirma la instalación
4. ¡Ya tienes el icono en tu tablet! 📚

---

## Opción 2: Uso Local (Sin internet)

### Requisitos:
- Instalar una app de servidor local como **"Simple HTTP Server"** desde Google Play

### Pasos:
1. Copia los 3 archivos a una carpeta en tu tablet
2. Abre la app Simple HTTP Server
3. Selecciona la carpeta con los archivos
4. Inicia el servidor
5. Abre Chrome y ve a `localhost:8080/horario-app.html`

---

## 🎯 CÓMO USAR LA APLICACIÓN

### Editar una clase:
1. **Toca cualquier celda** del horario
2. Se abrirá un formulario con espacio para **3 alumnos**
3. Rellena la información de cada alumno:
   - Nombre
   - Asignatura
   - Curso (desde 1º ESO hasta 2º Bach)
4. **Selecciona un color** para clasificar la clase
5. Toca **"Guardar"**

### Sistema de colores:
- 🟢 **Verde claro**: 1º-2º ESO
- 🟠 **Naranja claro**: 3º-4º ESO  
- 🔵 **Azul claro**: 1º-2º Bachillerato
- 🟡 **Amarillo**: Matemáticas
- 🟣 **Lila**: Física/Química/Biología
- 🩷 **Rosa**: Lengua/Inglés

### Funciones adicionales:

#### 💾 Exportar Datos
- Guarda tu horario en un archivo JSON
- Útil para hacer copias de seguridad

#### 📥 Importar Datos
- Recupera un horario guardado previamente
- Útil para cambiar entre diferentes semanas

#### 🗑️ Limpiar Todo
- Borra todo el horario
- Te pedirá confirmación

### Ventajas de la app:
- ✅ **Guardado automático**: No necesitas guardar manualmente
- ✅ **Funciona sin internet**: Una vez instalada
- ✅ **Interfaz táctil**: Optimizada para tablet
- ✅ **Formularios fáciles**: No necesitas editar celdas complejas
- ✅ **Colores personalizables**: Organiza como prefieras
- ✅ **3 alumnos por clase**: Gestión perfecta para tu academia

---

## 🔧 ARCHIVOS NECESARIOS

Para que funcione, necesitas estos 3 archivos en la misma carpeta:
1. `horario-app.html` - La aplicación principal
2. `manifest.json` - Configuración para instalar
3. `sw.js` - Para funcionar sin internet

---

## ❓ PREGUNTAS FRECUENTES

**P: ¿Se borrarán mis datos si cierro la app?**
R: No, los datos se guardan automáticamente en tu tablet.

**P: ¿Puedo usar la app sin internet?**
R: Sí, una vez instalada funciona completamente offline.

**P: ¿Cómo hago una copia de seguridad?**
R: Usa el botón "Exportar Datos" para guardar un archivo JSON.

**P: ¿Puedo tener varios horarios diferentes?**
R: Sí, exporta cada horario con un nombre diferente y luego impórtalos cuando los necesites.

**P: ¿Funciona en iPad o iPhone?**
R: Sí, también funciona en iOS con Safari.

---

## 📞 SOPORTE

Si tienes algún problema, puedes:
1. Verificar que los 3 archivos estén juntos
2. Usar Chrome (navegador recomendado)
3. Borrar caché y cookies si hay problemas
4. Reinstalar la app desde Chrome

¡Disfruta de tu nueva app de horarios! 📚✨
