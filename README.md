# 📊 Piscine Pedago Data Science

<div align="center">

![42](https://img.shields.io/badge/42-School-000000?style=for-the-badge)
![Data Science](https://img.shields.io/badge/Data_Science-Piscine-1f6feb?style=for-the-badge)
![Status](https://img.shields.io/badge/Módulos_0–4-Completados-success?style=for-the-badge)

**42 Málaga** · sternero · Formación práctica en datos: de la base SQL al modelo que predice

[Módulos](#-módulos) · [Flujo](#-flujo-didáctico) · [Clonar](#-cómo-clonar) · [Estructura](#-estructura)

</div>

---

## 🎯 Qué es esta piscine

Recorrido **guiado** (pedago) por el oficio del dato:

| Fase | Qué aprendes |
|------|----------------|
| **Crear** | Bases PostgreSQL, Docker, tablas desde CSV |
| **Almacenar** | Warehouse, limpieza, unificación |
| **Visualizar** | Gráficos y lectura de distribuciones |
| **Explorar el presente** | Histogramas, correlación, escalas, split |
| **Predecir el futuro** | Métricas, features, árboles, KNN, voting |

Cada módulo es un **submódulo Git** con su propio README, guías (`python.md`, etc.) y scripts.

---

## 📚 Módulos

| # | Carpeta / repo | Tema | Estado |
|---|----------------|------|--------|
| **0** | [`data_science_0_creation_db`](https://github.com/STC71/42_data_science_0_creation_db) | Creation of a DB (PostgreSQL, Docker, CSV → tablas) | ✅ |
| **1** | [`data_science_1_data_warehouse`](https://github.com/STC71/42_data_science_1_data_warehouse) | Data Warehouse | ✅ |
| **2** | [`data_science_2_data_viz`](https://github.com/STC71/42_data_science_2_data_viz) | Data visualization | ✅ |
| **3** | [`data_science_3_the_present`](https://github.com/STC71/42_data_science_3_the_present) | The present (EDA, escalas, split) | ✅ |
| **4** | [`data_science_4_the_future`](https://github.com/STC71/42_data_science_4_the_future) | The future (clasificación Jedi/Sith) | ✅ |

---

## 🔄 Flujo didáctico

```text
M0  SQL + Docker          →  tener datos estructurados
M1  Warehouse             →  limpiar y consolidar
M2  Visualización         →  ver patrones
M3  The present           →  estadísticas, correlaciones, train/val
M4  The future            →  modelos y predicción
```

En M4 se reutilizan `Training_knight.csv` / `Validation_knight.csv` del M3.

---

## 📦 Cómo clonar

```bash
# Clonar monorepo + submódulos
git clone --recurse-submodules git@github.com:STC71/42_piscine_pedago_data_science.git
cd 42_piscine_pedago_data_science

# Si ya clonaste sin submódulos:
git submodule update --init --recursive
```

O clonar un módulo suelto:

```bash
git clone git@github.com:STC71/42_data_science_4_the_future.git
```

---

## 🗂 Estructura

```text
42_piscine_pedago_data_science/
├── data_science_0_creation_db/     # submódulo
├── data_science_1_data_warehouse/  # submódulo
├── data_science_2_data_viz/        # submódulo
├── data_science_3_the_present/     # submódulo
├── data_science_4_the_future/      # submódulo
├── .gitmodules
└── README.md                       # este fichero
```

Dentro de cada módulo: `ex00/`, `ex01/`, … con entrega, `README.md` y guías educativas.

---

## 🛠 Requisitos habituales

| Herramienta | Uso típico |
|-------------|------------|
| **Docker** | PostgreSQL (M0) |
| **Python 3** | Scripts, pandas, matplotlib, scikit-learn (M3–M4) |
| **psql / pgAdmin** | Consultas (M0–M1) |

Sigue el `README` de cada módulo para detalles (goinfre, sin sudo, etc.).

---

## 🔗 Enlaces

- [42 Outer Core](https://github.com/STC71/42_Outer_Core) — ecosistema completo  
- [Módulo 0](https://github.com/STC71/42_data_science_0_creation_db) · [1](https://github.com/STC71/42_data_science_1_data_warehouse) · [2](https://github.com/STC71/42_data_science_2_data_viz) · [3](https://github.com/STC71/42_data_science_3_the_present) · [4](https://github.com/STC71/42_data_science_4_the_future)

---

*Piscine Pedago Data Science · sternero – 42 Málaga – Octubre 2026*
