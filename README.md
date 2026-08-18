# Presupuesto Fer

App web de presupuesto personal estilo YNAB/Actual Budget, preparada para desplegar en GitHub + Vercel y usar como PWA en iPhone.

## Funciones iniciales

- Presupuesto mensual.
- Gastos Fijos y Gastos Variables.
- Edición del presupuesto tocando el monto.
- Saldos positivos en globa verde, negativos en rojo y $0 en gris muy claro.
- Registro de gastos desde Débito, Pesos o Tickets.
- Validación: si un gasto supera el saldo de la categoría, la app pregunta de dónde sacar la diferencia antes de permitir el movimiento.
- Guardado automático en el navegador.
- Diseño responsive para iPhone.
- Manifest PWA para agregar a pantalla de inicio.

## Datos iniciales cargados

- Débito Itaú: $18.612
- Pesos: $800
- Tickets Alimentación: $8.046
- Total disponible: $27.458
- Para presupuestar: $575

## Ejecutar

```bash
npm install
npm run dev
```

Abrir la URL local que muestra Vite.

## Deploy

El proyecto se puede subir a GitHub y luego importar directamente desde Vercel.

## iPhone

Una vez desplegado en Vercel, abrir la URL en Safari → Compartir → Agregar a pantalla de inicio.
