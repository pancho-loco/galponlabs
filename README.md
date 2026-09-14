# Galpón Labs — sitio público

Sitio público de **Galpón Labs** (estudio de software, Argentina). Se publica con GitHub Pages en
**https://galponlabs.com**.

## Contenido

- `index.html` — página de inicio: qué es Galpón Labs y qué hace.
- `privacidad.html` — Política de Privacidad (incluye la cláusula de *Limited Use* de las APIs de Google).
- `CNAME` — dominio personalizado para GitHub Pages (`galponlabs.com`).

## Por qué existe

Google exige, para publicar una app OAuth en producción, una **homepage** y una **política de privacidad**
alojadas en un **dominio registrable propio** (no sirven `*.github.io`, `*.vercel.app`, etc.), y ese dominio
debe estar cargado en *Authorized domains* de la consola de Google Cloud.

## DNS (Porkbun)

| Tipo  | Host  | Valor                          |
|-------|-------|--------------------------------|
| A     | @     | 185.199.108.153                |
| A     | @     | 185.199.109.153                |
| A     | @     | 185.199.110.153                |
| A     | @     | 185.199.111.153                |
| CNAME | www   | pancho-loco.github.io          |

Opcional (IPv6): `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`.
