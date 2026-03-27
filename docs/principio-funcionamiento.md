# Principio de Funcionamiento - Hice-Free

## 1. Efecto Joule-Thomson

El corazón de Hice-Free es el **efecto Joule-Thomson**: la propiedad que tienen ciertos gases de enfriarse al expandirse rápidamente sin realizar trabajo externo.

Cuando un gas comprimido (CO₂ a 4–6 bar) se expande a presión atmosférica, sus moléculas se separan, disminuyendo su energía cinética y, por lo tanto, su temperatura. Este enfriamiento puede alcanzar decenas de grados bajo cero en fracciones de segundo.

## 2. Arquitectura del sistema

El sachet está dividido en tres subsistemas funcionales:


┌─────────────────────────────────────────────────────────────┐
│ SACHET HICE-FREE │
│ ┌───────────────────────────────────────────────────────┐ │
│ │ 1. Almacenamiento de gas │ │
│ │ Cápsula de CO₂ a 4–6 bar, sellada herméticamente.     │ │
│ │ Membrana de aluminio de 0.05–0.10 mm. │ │
│ └───────────────────────────────────────────────────────┘ │
│ ┌───────────────────────────────────────────────────────┐ │
│ │ 2. Activación │ │
│ │ Botón tipo click con pin perforador de acero. │ │
│ │ Fuerza 10–20 N. │ │
│ └───────────────────────────────────────────────────────┘ │
│ ┌───────────────────────────────────────────────────────┐ │
│ │ 3. Intercambio térmico │ │
│ │ Serpentín de cobre 0.5 mm, 15–20 cm de longitud.      │ │
│ │ En contacto directo con gel térmico. │ │
│ └───────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────┘


## 3. Ciclo de funcionamiento

| Fase | Duración | Proceso |
|------|----------|---------|
| **1. Activación** | 0.1 s | El usuario presiona el botón. El pin perforador rompe la membrana de la cápsula de CO₂. |
| **2. Expansión** | 1–2 s | El gas a 4–6 bar se expande bruscamente hacia el serpentín de cobre, bajando su temperatura por efecto Joule-Thomson. |
| **3. Transferencia térmica** | 5–15 s | El serpentín frío extrae calor del gel térmico que lo rodea. La alta conductividad del cobre (≈400 W/m·K) asegura una distribución uniforme. |
| **4. Congelación** | 10–20 s total | El gel alcanza temperaturas bajo cero y solidifica. El sachet se convierte en una pastilla de hielo homogénea. |

## 4. Termodinámica del proceso

### Datos clave

| Parámetro | Valor |
|-----------|-------|
| Gas | CO₂ |
| Presión inicial | 4–6 bar (absoluta) |
| Presión final | 1 bar (atmosférica) |
| Relación de expansión | 4:1 a 6:1 |
| Calor absorbido (teórico) | ≈ 200–300 J por gramo de CO₂ |
| Masa de gas | ≈ 1–2 g |
| Energía total absorbida | ≈ 200–600 J |

### Comparación con la capacidad térmica del gel

| Parámetro | Valor |
|-----------|-------|
| Masa de gel | ≈ 140 g |
| Calor específico | ≈ 4.2 J/g·K |
| ΔT para congelación (25°C → 0°C) | ≈ 14,700 J |
| Calor latente de fusión (0°C → hielo) | ≈ 46,800 J |
| **Total requerido** | ≈ **61,500 J** |

### Discrepancia y solución

La energía absorbida por el CO₂ (≈ 200–600 J) es menor que la necesaria para congelar todo el gel (≈ 61,500 J). **¿Cómo funciona entonces?**

El secreto está en el **gel térmico**: no es agua pura, sino una mezcla con **acetato de sodio** (nucleador) que permite la **cristalización en frío**. El gel está en estado **sobreenfriado** a temperatura ambiente (metaestable). La pequeña cantidad de frío del CO₂ actúa como **nucleador**, desencadenando una reacción en cadena de cristalización que libera el calor latente de fusión almacenado en el gel. El resultado es que el gel se solidifica en segundos, aunque la energía aportada por el gas sea menor.

Este principio es el mismo que utilizan las bolsas de frío químico (nitrato de amonio + agua), pero sin los riesgos de toxicidad. En Hice-Free, el gel es inocuo y el CO₂ es un gas seguro.

## 5. Comparación con tecnologías alternativas

| Tecnología | Principio | Ventajas | Desventajas |
|------------|-----------|----------|-------------|
| **Hice-Free** | Expansión de CO₂ + gel sobreenfriado | Instantáneo, portátil, no tóxico, sin freezer | Desechable (por ahora) |
| **Bolsas de frío reutilizables** | Gel congelado en freezer | Reutilizable, bajo costo | Requiere freezer, no es instantáneo |
| **Enfriadores químicos** | Reacción endotérmica (nitrato de amonio) | Instantáneo, portátil | Tóxico, químico único, más caro |
| **Hielo tradicional** | Agua congelada | Muy barato, reutilizable | Requiere freezer, no es portátil |

## 6. Referencias

- **Efecto Joule-Thomson**: Atkins, P. (2018). *Physical Chemistry*. Oxford University Press.
- **CO₂ como refrigerante**: Lorentzen, G. (1995). *The use of natural refrigerants: a complete solution*. International Journal of Refrigeration.
- **Geles superabsorbentes**: BASF (2024). *Luquasorb® Technical Data Sheet*.
- **Cristalización inducida por nucleación**: Mullin, J.W. (2001). *Crystallization*. Butterworth-Heinemann.



