# 🌱 HydroCalc NFT — Nutrient Calculator

Calculadora de nutrientes paso a paso para sistemas hidropónicos NFT (Nutrient Film Technique).

## 🚀 Abrir la App

👉 **[Abrir HydroCalc](https://TUUSUARIO.github.io/hydrocalc/)**

*(Reemplaza `TUUSUARIO` con tu nombre de usuario de GitHub)*

## 📱 Instalar en tu Teléfono

1. Abre el link en Chrome (Android) o Safari (iPhone)
2. **Android:** Menú ⋮ → "Añadir a pantalla de inicio"
3. **iPhone:** Botón compartir ↑ → "Añadir a pantalla de inicio"
4. ¡Listo! Se abre como una app nativa

## ✨ Características

- **Wizard paso a paso** — Te guía por cada nutriente
- **Corrección en tiempo real** — Si el PPM queda corto, te dice cuánto más añadir usando el divisor real
- **Auto-calibración** — Guarda los divisores reales y los usa en la próxima sesión
- **Etapas de crecimiento** — Presets para Establecimiento, Crecimiento, Pre-Cosecha y Cosecha
- **Volumen ajustable** — Base 25 galones, ajusta a cualquier cantidad
- **Historial** — Últimas 10 sesiones guardadas en tu dispositivo
- **Privado** — Todos los datos se guardan localmente en tu teléfono

## 🧮 Fórmulas

```
Mg siempre = 70 PPM
Restante se divide Ca:NPK en ratio 2:1

Mg (g) = PPM ÷ divisor × (volumen ÷ 25)
Ca (g) = PPM ÷ divisor × (volumen ÷ 25)  
NPK (g) = PPM ÷ divisor × (volumen ÷ 25)

Divisores por defecto: Mg=4.54 · Ca=6.10 · NPK=5.28
```

## 📊 Etapas de Crecimiento

| Etapa | Semana | PPM Total |
|-------|--------|-----------|
| Establecimiento | 1 | 710 |
| Crecimiento | 2-3 | 820 |
| Pre-Cosecha | 4 | 840 |
| Cosecha | Final | 850 |

## 🔒 Privacidad

Todos los datos (divisores, historial) se guardan en el `localStorage` de tu navegador. Nada se envía a ningún servidor. Cada persona ve solo sus propios datos.
