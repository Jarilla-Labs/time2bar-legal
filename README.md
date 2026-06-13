# jarillalabs-legal

Documentos legales públicos de las apps de **Jarilla Labs**, servidos como sitio
estático vía GitHub Pages bajo `www.jarillalabs.com`.

## Estructura

```
/                              → index.html  (hub que lista todas las apps)
/time2bar/privacidad/          → Política de privacidad de Time2Bar
```

Las URLs son limpias (sin `.html`) porque cada documento es un `index.html` dentro
de su propia carpeta. Ejemplo de URL pública final:

```
https://www.jarillalabs.com/time2bar/privacidad/
```

## Añadir una nueva app

1. Crea la carpeta `nombre-app/privacidad/` con su `index.html`.
2. Añade un bloque `.app` en el `index.html` raíz enlazando al nuevo documento.

> Nota: aunque el repo se llamó originalmente `time2bar-legal`, ahora aloja los
> documentos legales de todas las apps. Conviene renombrarlo en GitHub a algo como
> `jarillalabs-legal` (Settings → Repository name). El dominio personalizado y Pages
> se conservan tras el renombrado.
