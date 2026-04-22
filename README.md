# 🎫 Tarjeta de Contacto Digital Profesional

> Una tarjeta de contacto moderna, elegante y completamente funcional. Perfecta para compartir tu contacto digitalmente en iPhone, Android, Mac o Windows.

![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

---

## 📱 ¿Qué es esto?

Una **tarjeta de contacto digital profesional** que puedes:

✅ **Compartir** - Enlace o código QR  
✅ **Guardar en contactos** - Descarga vCard (.vcf)  
✅ **Usar como app** - Añade a home screen en iPhone  
✅ **Personalizar** - Solo edita un archivo JS  
✅ **Hospedar gratis** - En GitHub Pages  
✅ **Ver en cualquier dispositivo** - Responsive 100%

---

## 🚀 Empieza en 3 pasos

### 1️⃣ Usa esta plantilla

Haz clic en el botón verde:
```
⭐ Use this template
```

Dale un nombre a tu repo:
```
mi-tarjeta-contacto
```

### 2️⃣ Edita tus datos

Abre el archivo `datos.js` y cambia los valores entre comillas:
```js
var datos = {
  "nombre": "Tu Nombre Completo",
  "email": "tuemail@ejemplo.com",
  "telefonoCompleto": "+34693500740",
  "empresa": "Tu Empresa",
  "puesto": "Tu Puesto",
  "ubicacion": "Tu Ciudad, País"
};
```

### 3️⃣ Obtén tu enlace

Ve a **Settings → Pages** y espera 2 minutos.

Tu URL será:
```
https://[tuusuario].github.io/[tunombrerepo]/
```

¡Listo! 🎉

---

## 📋 Instrucciones detalladas

### Para principiantes (sin experiencia en GitHub)

#### Paso 1: Copia esta plantilla

1. Ve a este repo
2. Haz clic en **"⭐ Use this template"** (botón verde)
3. En "Repository name" escribe: `mi-tarjeta-contacto`
4. Marca **"Public"**
5. Haz clic en **"Create repository from template"**

🎯 **Resultado:** Se crea tu propia copia

#### Paso 2: Personaliza tus datos

1. En tu nuevo repo, busca el archivo: **`datos.js`**
2. Haz clic en él
3. Haz clic en el icono de **edición (lápiz)** ✏️
4. **Cambia SOLO el texto entre comillas:**

```js
"nombre": "TU NOMBRE AQUÍ",
"email": "tuemail@ejemplo.com",
"telefonoCompleto": "+34693500740",
"telefonoMostrado": "+34 693 500 740",
"empresa": "TU EMPRESA AQUÍ",
"puesto": "TU PUESTO AQUÍ",
"ubicacion": "Tu Ciudad, País"
```

Todos los campos son opcionales excepto `nombre`. Puedes eliminar los que no necesites y la tarjeta se adapta sola.

**Opcional - Añade tus redes:**
```js
"redes": {
  "linkedin": "https://linkedin.com/in/tuusuario",
  "github": "https://github.com/tuusuario",
  "instagram": "@tuusuario",
  "twitter": "@tuusuario"
}
```

5. Abajo del todo, haz clic en **"Commit changes"**

🎯 **Resultado:** Tus datos se guardan automáticamente

#### Paso 3: Activa GitHub Pages

1. En tu repo, haz clic en **"Settings"** (pestaña arriba)
2. En el menú izquierdo, busca **"Pages"**
3. Bajo "Build and deployment":
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Haz clic en **"Save"**
5. **Espera 2-3 minutos** (GitHub genera tu sitio)

🎯 **Resultado:** Aparece tu URL en esa página

#### Paso 4: Abre en tu iPhone

1. Copia tu URL de GitHub Pages
2. Abre **Safari** en tu iPhone
3. Pega la URL en la barra de direcciones
4. ¡**Verás tu tarjeta!** 🎉

**Para que sea una app:**
1. Toca el icono de **Compartir** (cuadro con flecha)
2. Busca **"Add to Home Screen"**
3. Dale un nombre
4. Toca **"Add"**

✅ ¡Ya está en tu home screen!

---

## 📂 Estructura del proyecto

```
tu-repo/
├── index.html          ← La tarjeta (no toques)
├── datos.js            ← TUS DATOS (edita esto)
└── README.md          ← Este archivo
```

### `index.html`

- La página web que ve todo el mundo
- **NO LA EDITES** (a menos que quieras cambiar el diseño)
- Carga automáticamente los datos de `datos.js`
- Genera el QR automáticamente
- Botones para descargar y compartir

### `datos.js`

- **EDITA ESTE ARCHIVO** con tus datos
- Formato JavaScript simple (igual que JSON pero con `var datos = { ... };` alrededor)
- Solo texto, sin código
- Cambios se reflejan automáticamente en la tarjeta
- Funciona en todos los navegadores, incluyendo **Safari con archivos locales**

---

## 🎨 Personalización avanzada

### Cambiar colores

En `datos.js`, edita la sección `diseno`:

```js
"diseno": {
  "colorPrincipal": "#d4af37",    // Color principal (dorado por defecto)
  "colorFondo": "#1a1a1a",        // Color de fondo (oscuro por defecto)
  "colorAcento": "#764ba2"        // Color de acento
}
```

Los colores se aplican automáticamente a toda la tarjeta. Puedes usar cualquier valor hexadecimal (`#rrggbb`). Los campos de `diseno` son opcionales — si los eliminas se usan los colores por defecto.

**Ejemplos de paletas:**
```js
// Azul corporativo
"colorPrincipal": "#1e90ff",
"colorFondo": "#0d1b2a"

// Verde esmeralda
"colorPrincipal": "#50c878",
"colorFondo": "#0f1f0f"

// Rojo carmesí
"colorPrincipal": "#dc143c",
"colorFondo": "#1a0a0a"
```

### Añadir más información

Simplemente añade nuevos campos en `datos.json`:

```json
{
  "nombre": "...",
  "tuCampoNuevo": "tu valor aquí",
  "otroCampo": "otro valor"
}
```

---

## 🌐 Compartir tu tarjeta

Una vez activa, puedes compartirla de muchas formas:

### 1. Directamente el enlace
```
https://tuusuario.github.io/mi-tarjeta-contacto/
```

### 2. Código QR
- Otros pueden escanear el QR de tu tarjeta
- Se abre automáticamente en navegador

### 3. Como vCard descargable
- Botón "⬇️ Guardar" en tu tarjeta
- Descarga tu contacto como `.vcf`
- Importable en cualquier teléfono

### 4. En redes sociales
- LinkedIn bio → tu URL
- Instagram bio → tu URL
- Twitter → tu URL

### 5. En tarjetas impresas
- Imprime un QR grande
- La gente lo escanea con su teléfono
- Se abre tu tarjeta digital

---

## ❓ Preguntas frecuentes

### "¿Cómo cambio el diseño?"

El diseño está en `index.html`. Si quieres cambiarlo:

1. Abre `index.html`
2. Haz clic en ✏️ editar
3. Busca la sección `<style>` (estilos CSS)
4. Modifica lo que quieras
5. Commit

⚠️ **Cuidado:** Los cambios en HTML requieren entender un poco de código.

### "¿Por qué la tarjeta tarda en cargar?"

- Normalmente es inmediato
- A veces GitHub tarda 2-3 segundos
- Recarga la página (Cmd+R Mac / Ctrl+F5 Windows)

### "¿El QR qué contiene?"

El QR contiene un vCard (contacto) con todos tus datos:
- Nombre
- Teléfono
- Email
- Empresa
- Web
- Redes sociales

Cuando alguien escanea el QR, se descarga automáticamente tu contacto.

### "¿Puedo usar en Android?"

Sí, 100% compatible. Funciona en:
- ✅ iPhone (Safari)
- ✅ Android (Chrome, Firefox, etc.)
- ✅ Mac (Safari, Chrome)
- ✅ Windows (Edge, Chrome, Firefox)

### "¿Es gratis?

Sí, completamente gratis:
- ✅ GitHub account (gratis)
- ✅ GitHub Pages hosting (gratis)
- ✅ Este código (gratis - MIT License)

### "¿Puedo editar datos.js desde el móvil?"

Sí:
1. En tu repo, busca `datos.js`
2. Haz clic en él
3. Haz clic en el lápiz ✏️
4. Edita
5. Commit

---

## 🐛 Troubleshooting

### "No veo el QR"

```
1. Recarga la página (Ctrl+F5 o Cmd+R)
2. Abre en modo incógnito
3. Prueba otro navegador
4. Verifica que datos.json esté bien (sin errores)
```

### "El enlace no funciona"

```
1. Espera 3 minutos (GitHub genera el sitio)
2. Ve a Settings > Pages y verifica:
   - Source: "Deploy from a branch"
   - Branch: "main"
3. Si sigue sin funcionar: Recarga Settings > Pages
```

### "Los datos no se actualizan"

```
1. Verifica que hayas hecho "Commit changes"
2. Recarga la página del navegador (Ctrl+Shift+R)
3. Borra el caché: Settings > datos.js > edita > Commit
4. Espera 2 minutos
```

### "Aparecen errores en datos.js"

```
1. Verifica que NO BORRES:
   - La primera línea: var datos = {
   - La última línea: };
   - Comillas " " alrededor de cada valor
   - Comas , al final de cada línea (menos la última de cada bloque)

2. Si no sabes dónde está el error:
   - Copia todo el contenido de datos.js
   - Pégalo en: jsonlint.com (quita la primera y última línea)
   - Te dirá exactamente dónde está el error

3. Si tienes dudas, copia la plantilla original y edita solo el texto
```

### "No funciona en mi iPhone"

```
1. Usa WiFi, no datos móviles
2. Abre Safari, no Chrome en iPhone
3. Borra caché: Settings > Safari > Clear History
4. Abre de nuevo tu URL
5. Si sigue: Comparte el enlace por AirDrop
```

---

## 💡 Tips y trucos

### Actualizar tu tarjeta

Puedes actualizar tus datos en cualquier momento:

1. Edita `datos.js`
2. Commit
3. Los cambios aparecen automáticamente en tu tarjeta

### Crear tarjetas para tu equipo

1. Cada persona crea su propia copia del template
2. Editan su `datos.json` con sus datos
3. Todos comparten el mismo diseño ✨

### Versionar cambios

Git guarda el historial de cambios:
- Click en "Commits"
- Ves quién cambió qué y cuándo
- Puedes revertir cambios si quieres

### Colaborar

Si alguien quiere ayudarte:
1. Ellos hacen un "Fork"
2. Editan y hacen cambios
3. Hacen un "Pull Request"
4. Tú revisas y aceptas

---

## 📖 Referencias útiles

- [Documentación JSON](https://www.json.org/json-es.html)
- [GitHub Pages Guide](https://pages.github.com/)
- [vCard Specification](https://tools.ietf.org/html/rfc6350)
- [Validador JSON Online](https://jsonlint.com/)

---

## 🤝 Contribuir

¿Quieres mejorar este proyecto?

1. Haz un Fork
2. Crea una rama: `git checkout -b mejora/mi-mejora`
3. Haz cambios
4. Commit: `git commit -am 'Añado mi mejora'`
5. Push: `git push origin mejora/mi-mejora`
6. Abre un Pull Request

---

## 📄 Licencia

Este proyecto está bajo licencia **MIT**. 

Eres libre de:
- ✅ Usar para propósitos personales
- ✅ Modificar el código
- ✅ Distribuir
- ✅ Usar comercialmente

Solo debes mantener la licencia.

---

## 👨‍💻 Autor

Creado con ❤️ para estudiantes y profesionales.

**Versión actual:** 1.0  
**Última actualización:** 2024

---

## 📞 Soporte

¿Necesitas ayuda?

1. **Revisa el FAQ** arriba ↑
2. **Comprueba el Troubleshooting** arriba ↑
3. **Abre un Issue** si encuentras un bug
4. **Pide ayuda a tu profesor/a**

---

## 🎯 Próximos pasos

Una vez activa tu tarjeta:

1. ✅ Compartir en LinkedIn
2. ✅ Poner en bio de Instagram
3. ✅ Enviar a contactos
4. ✅ Imprimir QR en tarjetas
5. ✅ Usar en firma de email

---

## 🙏 Agradecimientos

Gracias por usar este proyecto.

Si te fue útil:
- ⭐ Dale una estrella en GitHub
- 📢 Comparte con otros
- 💬 Deja feedback

---

**Made with 💜 for everyone**

---

## Última cosa...

¿Tienes mejoras? Sugiere ideas, abre issues, o contribuye.

¡Esperamos tu feedback! 🚀

```
╔════════════════════════════════════╗
║    ¡Tu tarjeta está lista! 🎉     ║
║  Abre en Safari y comparte con    ║
║         tu comunidad              ║
╚════════════════════════════════════╝
```
