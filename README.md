# 📄 Legal Texts – Documentación del Proyecto

Legal Texts es una aplicación web construida con [Astro](https://astro.build/) para mostrar y gestionar textos legales (políticas de privacidad, términos y condiciones, etc.) de forma centralizada y editable.

---

## ✨ ¿Qué es este proyecto?

Este proyecto permite:

- Visualizar textos legales en páginas web amigables.
- Gestionar fácilmente los contenidos legales en formato Markdown.
- Personalizar la estructura y el diseño usando Astro.

---

## 🚀 Guía Rápida de Inicio

1. **Instalación de dependencias**

   ```sh
   npm install
   ```

2. **Desarrollo local**

   ```sh
   npm run dev
   ```

   Accede a [http://localhost:4321](http://localhost:4321) en tu navegador.

3. **Construcción para producción**

   ```sh
   npm run build
   ```

4. **Vista previa de producción**
   ```sh
   npm run preview
   ```

---

## 🗂️ Estructura del Proyecto

```text
legal_texts/
├── public/                # Recursos estáticos (logos, iconos)
├── src/
│   ├── content/
│   │   └── docs/          # Textos legales en Markdown
│   ├── layouts/           # Layouts Astro
│   ├── pages/             # Páginas Astro (.astro)
│   └── styles/            # Estilos globales
├── package.json
├── astro.config.mjs
└── README.md
```

- **Textos legales**:
  - `src/content/docs/privacy_policy.md`
  - `src/content/docs/terms_conditions.md`
- **Páginas**:
  - `/privacy-policy`
  - `/terms-conditions`
  - `/docs/[slug]` (para textos adicionales)

---

## ✍️ ¿Cómo editar o agregar textos legales?

1. Edita los archivos Markdown en `src/content/docs/`.
2. Para agregar un nuevo texto legal:
   - Crea un archivo `.md` en `src/content/docs/`.
   - Añade la ruta correspondiente en `src/pages/docs/[slug].astro` si es necesario.

---

## 💡 Consejos de UX

- Navegación clara entre textos legales.
- Diseño responsive y accesible.
- Uso de layouts reutilizables para coherencia visual.

---

## 📚 Recursos útiles

- [Documentación Astro](https://docs.astro.build/)
- [Astro Discord](https://astro.build/chat)

---

## 🛠️ Scripts disponibles

| Comando           | Descripción                      |
| ----------------- | -------------------------------- |
| `npm install`     | Instala dependencias             |
| `npm run dev`     | Servidor de desarrollo           |
| `npm run build`   | Compila el sitio para producción |
| `npm run preview` | Vista previa de la build         |

---

## 📬 Contacto

¿Dudas o sugerencias? Abre un issue o contacta al responsable del repositorio.
