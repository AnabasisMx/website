# anabasis.mx

Sitio principal de Anabasis · Diseño de espacios de trabajo. Página estática servida con GitHub Pages.

## Archivos
| Archivo | Qué es |
|---|---|
| `index.html` | Sitio completo (HTML, CSS y JS en un solo archivo). |
| `logo.png`, `favicon-*.png` | Logotipo e íconos. |
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
