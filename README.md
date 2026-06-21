# 🌐 LumoTranslate

Traductor web open source. Traduce texto y páginas web con LibreTranslate. Sin tracking, sin servidores propios.

## ✨ Características

- **Traducción de texto** vía LibreTranslate API (open source, sin API keys)
- **Traducción de páginas web** — escribís una URL y se abre en Google Translate / Bing / Yandex
- **Detección automática de idioma** con badge visual
- **Botón intercambiar idiomas** con swap de texto
- **Dark/Light mode** con persistencia en localStorage
- **Síntesis de voz** para escuchar traducciones
- **Configuración de API** — usá tu propia instancia de LibreTranslate
- **100% open source** — single-file, sin dependencias, sin tracking

## 🚀 Uso

Abrí `index.html` en tu navegador. No necesita servidor.

## ⚙️ Configuración de API

Por defecto usa `translate.fedilab.app`. Podés configurar tu propia instancia:

1. Hacé click en el ícono ⚙️
2. Ingresá la URL de tu instancia de LibreTranslate
3. Asegurate de tener habilitado `--enable-cors`

## 📦 Despliegue

### GitHub Pages
1. Subí el repo a GitHub
2. Ve a Settings → Pages
3. Seleccioná la rama `main` y carpeta `/ (root)`
4. Tu traductor estará en `https://tu-usuario.github.io/LumaTranslator/`

### Cualquier hosting estático
Solo necesitás subir el archivo `index.html`. No hay build step.

## 🤝 Contribuir

1. Fork el repo
2. Creá una branch (`git checkout -b feature/nueva-funcionalidad`)
3. Hacé commit (`git commit -m 'Agregar nueva funcionalidad'`)
4. Push (`git push origin feature/nueva-funcionalidad`)
5. Abrí un Pull Request

## 📄 Licencia

MIT License — ver [LICENSE](LICENSE) para detalles.

## 🔗 Créditos

- [LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) — motor de traducción open source
- Powered by liblaper
