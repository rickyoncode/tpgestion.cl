# tpgestion.cl

Sitio de Tatiana Pérez Cáceres — contabilidad, administración financiera y back-office.

Una sola página, sin build ni dependencias. `index.html` lleva el HTML, el CSS y el JS
dentro del mismo archivo; al lado van las imágenes.

```
index.html
tati.jpg                  retrato (hero y "Quién soy")
benjamin.jpg              reseña · Benjamín Martínez
ricardo.jpg               reseña · Ricardo Silva
francisca.jpg             reseña · Francisca Escobar
logo-miido.png            franja de clientes
logo-loadingplay.png
logo-codename.png
logo-mda.png
logo-kickass.png
```

Lo único externo son las tipografías de Google Fonts (Source Serif 4 e Inter).

## Para publicar

Sirve la carpeta tal cual. Con GitHub Pages basta con activar Pages sobre la rama
principal, raíz del repo, y apuntar el dominio en Settings → Pages → Custom domain.

## Valores que hay que tocar a mano

- **UF del cotizador:** constante `UF` al inicio del `<script>` del cotizador (hoy `40800`).
- **IVA:** constante `IVA` (hoy `0.19`).
- **Planes y topes:** objeto `PLANES`, y los mismos números repetidos en las tarjetas
  de la sección `#planes`. Si cambias uno, cambia el otro.
- **Descuento por entrar dos empresas:** constante `DUO` (hoy `0.10`).

## Pendiente

- Logo de Citylink en la franja de clientes.
- Reemplazar `logo-kickass.png` por una versión de mayor resolución.
