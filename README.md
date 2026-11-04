# anabasis.mx

Sitio principal de Anabasis · Diseño de espacios de trabajo. Página estática servida con GitHub Pages.

## Archivos
| Archivo | Qué es |
|---|---|
| `index.html` | Sitio completo (HTML, CSS y JS en un solo archivo). |
| `privacidad.html` | Aviso de privacidad (falta razón social y domicilio del responsable). |
| `assets/` | Imágenes (renders ilustrativos), logotipos e íconos. |
| `robots.txt`, `sitemap.xml` | Indexación en buscadores. |
| `nuevo/` | Redirección a la portada (fue la vista previa). |
| `logo.png`, `favicon-*.png` (raíz) | Archivos del sitio anterior; se conservan por si algún enlace externo los usa. |
| `CNAME` | Dominio personalizado: `anabasis.mx`. |

## Publicación
- GitHub Pages: Settings › Pages › Deploy from a branch › `main` / `(root)`; Custom domain `anabasis.mx`; Enforce HTTPS.
- DNS (Cloudflare, zona anabasis.mx): registros apex hacia GitHub Pages (A 185.199.108.153, .109.153, .110.153, .111.153) o CNAME aplanado a `anabasismx.github.io`; `www` → `anabasismx.github.io`.

## Subdominios
- `crm.anabasis.mx` → repositorio `crm` (interno, con acceso).
- `pro.anabasis.mx` → repositorio `pro` (landing de campaña).

## Reglas de contenido
- No publicar certificaciones específicas de producto; las garantías y certificaciones se especifican en cada propuesta.
- Términos de marca: "mobiliario de alto desempeño", "estación de hidratación", "propuesta de proyecto", "solución integral".

## Enlaces y medición
- Todos los botones "Envía fotos de tu oficina" llevan a `https://pro.anabasis.mx/` con `utm_source=sitio` y `utm_medium` según la sección (nav, menu, hero, transformacion, cierre, footer).
- "Agenda tu brief" abre WhatsApp 52 81 8461 3223 con mensaje prellenado.
