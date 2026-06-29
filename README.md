# SERGAS · Landings

Sitios estáticos para captar consultas de obra. Cada carpeta es una landing independiente:

- `gas/` → landing dedicada a red de gas (campañas de gas)
- `general/` → landing general (todos los servicios)

## Deploy (Netlify, sin build)
Cada landing se publica como un sitio de Netlify enlazado a este repo:
- Build command: *(vacío)*
- Publish directory: `gas` (o `general`)

Cada push a la rama principal republica automáticamente.
