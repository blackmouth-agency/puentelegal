# Puente Legal — puentelegal.com.co

Sitio estático. Se publica con GitHub Pages (rama `main`, raíz) y el archivo `CNAME`.

## Publicar
1. Crear repo en GitHub y hacer push de `main`.
2. Settings → Pages → Source: `main` / root. Custom domain: `puentelegal.com.co`. Activar *Enforce HTTPS*.
3. DNS en el registrador del dominio:
   - `A` @ → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `AAAA` @ → 2606:50c0:8000::153, 2606:50c0:8001::153, 2606:50c0:8002::153, 2606:50c0:8003::153
   - `CNAME` www → `<usuario>.github.io`
