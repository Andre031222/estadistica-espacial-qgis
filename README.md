# Estadística Espacial con QGIS

> **Práctica Calificada 1** · Universidad Nacional del Altiplano — Puno

## Objetivo

Documentar la instalación y el uso inicial de **QGIS** para trabajar con datos espaciales, diferenciando una capa ráster de una capa vectorial.

## Entorno de trabajo

| Elemento | Detalle |
|---|---|
| Software SIG | QGIS Desktop |
| Sistema de referencia | EPSG:4326 / EPSG:3857 |
| Capa ráster | Teselas OpenStreetMap (XYZ) |
| Capa vectorial | Capa temporal de puntos |

## Evidencias

### 1. Instalación de QGIS

La aplicación QGIS se encuentra instalada y operativa en el equipo.

### 2. Capa ráster

Se agregó una capa de teselas **OpenStreetMap Raster** mediante una conexión XYZ. Este tipo de información se representa como una cuadrícula de píxeles o celdas.

### 3. Capa vectorial

Se creó la capa **Capa_Vectorial_Punto**, que representa entidades geográficas discretas mediante geometrías de puntos.

## Reproducibilidad

1. Abrir QGIS Desktop.
2. Para la capa ráster: ir a **Capa → Añadir capa → Añadir capa XYZ** y usar OpenStreetMap.
3. Para la capa vectorial: ir a **Capa → Crear capa → Nueva capa temporal** y elegir geometría de punto.
4. Registrar al menos una entidad en el lienzo del mapa.

## Estructura del repositorio

```text
.
├── README.md
└── evidencias/
    ├── instalacion_qgis.png
    ├── capa_raster.png
    └── capa_vectorial.png
```

---

**Autor:** Richar Andre Vilca Solorzano  
**Curso:** Estadística Espacial
