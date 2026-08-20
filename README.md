# Cambio de uso — Bajo comercial a vivienda

Sitio web para plantear alternativas de distribución en planta, partiendo del
plano de planta del proyecto de referencia (vivienda ya distribuida).

## Estado actual

- [x] `index.html` — página de apertura, con el plano de planta del proyecto
      de referencia como punto de partida.
- [x] `css/styles.css` — estilos de la página de apertura.
- [x] `assets/planta-base.svg` — plano de planta original (copiado desde el
      proyecto de referencia).
- [ ] Planos de las alternativas (pendiente).
- [ ] Páginas o secciones de comparación entre alternativas (pendiente).

## Estructura de ficheros del repositorio

```
/
├── index.html                 # Página de apertura (plano base) — LISTO
├── css/
│   └── styles.css             # Estilos globales — LISTO
├── assets/
│   └── planta-base.svg        # Plano del proyecto de referencia — LISTO
│
│   # Pendientes de crear a medida que se definan las alternativas:
├── assets/
│   ├── planta-alt-01.svg      # Alternativa 1 (por definir)
│   ├── planta-alt-02.svg      # Alternativa 2 (por definir)
│   └── planta-alt-03.svg      # Alternativa 3 (por definir)
├── alternativas.html          # Página comparativa de alternativas (por crear)
└── README.md                  # Este fichero
```

## Cómo continuar

1. Subir este directorio tal cual al nuevo repositorio.
2. Cuando se definan las distribuciones alternativas, añadir cada plano en
   `assets/planta-alt-0X.svg` y sustituir los bloques `.alt-slot` de
   `index.html` (o crear `alternativas.html`) por el contenido real.
