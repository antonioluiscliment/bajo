# Cambio de uso — Bajo comercial a vivienda

Sitio web para plantear alternativas de distribución en planta, partiendo del
plano de planta del proyecto de referencia (vivienda ya distribuida).

## Estado actual

- [x] `index.html` — página de apertura, con el plano base, la Alternativa 1
      y la Alternativa 2 ya resueltas.
- [x] `css/styles.css` — estilos de la página.
- [x] `assets/planta-base.svg` — plano de planta original (proyecto de referencia).
- [x] `assets/planta-alt-01.svg` — Alternativa 1:
      garaje ampliado a 11,00 m; Dormitorio 2 reubicado al fondo (3,00 × 5,00 m);
      antiguo Dormitorio 2 integrado en el Estar (forma en L); accesos
      Garaje→Estar, Estar→Dormitorio 2, Estar→Dormitorio 1.
- [x] `assets/planta-alt-02.svg` — Alternativa 2 (sobre la 1):
      el eje garaje/Dormitorio 2 mantiene 3,00 m de ancho solo en los primeros
      6,00 m desde el frente; los 10,00 m restantes se reducen a 2,40 m.
      Dormitorio 2 pasa a 2,40 × 5,00 m. El Estar gana esos 0,60 m.
- [ ] Alternativa 3 (pendiente).

## Estructura de ficheros del repositorio

```
/
├── index.html                 # Apertura + Alternativa 1 + Alternativa 2 — LISTO
├── css/
│   └── styles.css             # Estilos globales — LISTO
├── assets/
│   ├── planta-base.svg        # Plano del proyecto de referencia — LISTO
│   ├── planta-alt-01.svg      # Alternativa 1 — LISTO
│   └── planta-alt-02.svg      # Alternativa 2 — LISTO
├── package.json                # Config. mínima para Vercel — LISTO
├── vercel.json                  # Fuerza despliegue estático — LISTO
│
│   # Pendiente de crear cuando se defina:
├── assets/
│   └── planta-alt-03.svg      # Alternativa 3 (por definir)
└── README.md                  # Este fichero
```

## Cómo continuar

1. Subir/actualizar estos ficheros en el repositorio.
2. Cuando se defina la Alternativa 3, añadir `assets/planta-alt-03.svg` y
   duplicar el bloque `<section>`/`<figure>` de la Alternativa 2 en
   `index.html`, sustituyendo el hueco `.alt-slot` nº 03.

