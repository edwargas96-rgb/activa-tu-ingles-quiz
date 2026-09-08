# Activa tu Inglés — Quiz

Quiz gamificado en español (LATAM) que continúa después del video (nivel
fácil): pide nombre y motivo, sube por Nivel Medio y Nivel Difícil con
feedback inmediato por pregunta, y cierra con un diagnóstico de nivel
personalizado al motivo elegido antes de mostrar la oferta del kit
(300 mapas mentales, frases más usadas, jergas y plan de estudio de 30 días).

## Desarrollo

```bash
bun install
bun run dev
```

## Build

```bash
bun run build
```

## Pendiente antes de lanzar

- Reemplazar `CHECKOUT_URL` en `src/App.tsx` por el link real de checkout.
- Subir el logo real a `public/logo-activa-ingles.png` (cae de vuelta a un
  badge en CSS si el archivo no existe).
