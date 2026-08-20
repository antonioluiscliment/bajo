# Cambio de uso — Bajo comercial a vivienda

Sitio web para plantear alternativas de distribución en planta, partiendo del
plano de planta del proyecto de referencia (vivienda ya distribuida).

## Estado actual

- [x] `index.html` — página de apertura, con el plano base y la Alternativa 1
      ya resuelta.
- [x] `css/styles.css` — estilos de la página.
- [x] `assets/planta-base.svg` — plano de planta original (proyecto de referencia).
- [x] `assets/planta-alt-01.svg` — Alternativa 1, versión final:
      garaje ampliado a 11,00 m; Dormitorio 2 reubicado al fondo (3,00 × 5,00 m);
      antiguo Dormitorio 2 integrado en el Estar (forma en L); accesos
      Garaje→Estar, Estar→Dormitorio 2, Estar→Dormitorio 1.
- [ ] Alternativa 2 (pendiente).
- [ ] Alternativa 3 (pendiente).

## Estructura de ficheros del repositorio

```
/
├── index.html                 # Página de apertura + Alternativa 1 — LISTO
├── css/
│   └── styles.css             # Estilos globales — LISTO
├── assets/
│   ├── planta-base.svg        # Plano del proyecto de referencia — LISTO
│   └── planta-alt-01.svg      # Alternativa 1 (versión final) — LISTO
├── package.json                # Config. mínima para Vercel — LISTO
├── vercel.json                  # Fuerza despliegue estático — LISTO
│
│   # Pendientes de crear a medida que se definan las alternativas:
├── assets/
│   ├── planta-alt-02.svg      # Alternativa 2 (por definir)
│   └── planta-alt-03.svg      # Alternativa 3 (por definir)
└── README.md                  # Este fichero
```

## Cómo continuar

1. Subir/actualizar estos ficheros en el repositorio (ver lista de cambios
   más abajo si ya tienes el repo creado).
2. Cuando se defina la Alternativa 2, añadir `assets/planta-alt-02.svg` y
   duplicar el bloque `<section class="plan-section">` de la Alternativa 1
   en `index.html`, sustituyendo el hueco `.alt-slot` nº 02.

