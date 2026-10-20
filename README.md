# OllaCercana — Frontend (documentación)

Este repositorio contiene únicamente documentación del frontend: modelo de flujo de pantallas, prototipo, pantallas explicadas y manual de identidad. Aún no incluye código.

## Índice

1. [Prototipo](#1-prototipo)
2. [Modelo de flujo de pantallas](#2-modelo-de-flujo-de-pantallas)
3. [Pantallas por funcionalidad](#3-pantallas-por-funcionalidad)
   - [3.1 Nombre de la funcionalidad 1](#31-nombre-de-la-funcionalidad-1)
   - [3.2 Nombre de la funcionalidad 2](#32-nombre-de-la-funcionalidad-2)
   - [3.3 Nombre de la funcionalidad 3](#33-nombre-de-la-funcionalidad-3)
4. [Manual de identidad](#4-manual-de-identidad)
   - [4.1 Marca y voz](#41-marca-y-voz)
   - [4.2 Logo](#42-logo)
   - [4.3 Paleta de colores](#43-paleta-de-colores)
   - [4.4 Tipografía](#44-tipografía)
   - [4.5 Iconografía](#45-iconografía)
   - [4.6 Componentes de interfaz](#46-componentes-de-interfaz)
   - [4.7 Fotografía y personaje](#47-fotografía-y-personaje)
5. [Estructura del repositorio](#5-estructura-del-repositorio)

---

## 1. Prototipo

🔗 [Ver prototipo](PEGAR_LINK_AQUI)

---

## 2. Modelo de flujo de pantallas

![Flujo de pantallas](docs/flujo/flujo-general.png)

Breve descripción del flujo: desde dónde entra el usuario y cómo navega entre pantallas.

---

## 3. Pantallas por funcionalidad

### 3.1 Nombre de la funcionalidad 1

| Campo | Detalle |
|---|---|
| **Rol que la ve** | Cliente / Cocinera / Admin |
| **Responde a** | RF-XX, HU-XX |

**Happy path**

![Happy path](docs/pantallas/funcionalidad1-happy.png)

Qué hace el usuario y qué ve en el caso normal.

**Estado de error / vacío**

![Error o vacío](docs/pantallas/funcionalidad1-error.png)

Qué se muestra cuando falla algo o no hay datos.

---

### 3.2 Nombre de la funcionalidad 2

| Campo | Detalle |
|---|---|
| **Rol que la ve** | |
| **Responde a** | RF-XX, HU-XX |

**Happy path**

![Happy path](docs/pantallas/funcionalidad2-happy.png)

**Estado de error / vacío**

![Error o vacío](docs/pantallas/funcionalidad2-error.png)

---

### 3.3 Nombre de la funcionalidad 3

| Campo | Detalle |
|---|---|
| **Rol que la ve** | |
| **Responde a** | RF-XX, HU-XX |

**Happy path**

![Happy path](docs/pantallas/funcionalidad3-happy.png)

**Estado de error / vacío**

![Error o vacío](docs/pantallas/funcionalidad3-error.png)

---

## 4. Manual de identidad

Resumen del Manual de Identidad OllaCercana **v3.0** (Oct. 2026). Marca hogareña: la calidez de la cocina del conjunto hecha sistema visual.

> **Eslogan:** "Comida casera a un paso de tu puerta."

**Contenido de esta sección**
- [4.1 Marca y voz](#41-marca-y-voz)
- [4.2 Logo](#42-logo)
- [4.3 Paleta de colores](#43-paleta-de-colores)
- [4.4 Tipografía](#44-tipografía)
- [4.5 Iconografía](#45-iconografía)
- [4.6 Componentes de interfaz](#46-componentes-de-interfaz)
- [4.7 Fotografía y personaje](#47-fotografía-y-personaje)

### 4.1 Marca y voz

- **Nombre:** *Olla* = cocina tradicional, fuego lento, calor del hogar. *Cercana* = proximidad hiperlocal y coordinación vecinal.
- **Valores:** Cercanía, Confianza, Sostenibilidad, Comunidad.
- **Público:** Cocineras (personas que cocinan en casa y ofrecen platos a su zona) y Compradores (vecinos que buscan comida casera cercana).
- **Voz:** directa y cálida (frases cortas, español cotidiano, ej. "apartar porción") y honesta (no prometer precios/disponibilidad garantizados, ni dirección exacta antes de confirmar la reserva, ni pagos procesados por la plataforma).

### 4.2 Logo

| Versión | Archivo |
|---|---|
| Principal (full color) | ![Logo principal](docs/identidad/logo-principal.png) |
| Isotipo (la olla) | <img src="docs/identidad/isotipo.png" width="96" alt="Isotipo"> |

- Variantes oficiales: principal, isotipo y monocromático (escala de grises); versiones para fondo claro y oscuro.
- **Área de reserva:** 1X = altura del isotipo de la olla. Ningún texto ni elemento ajeno debe invadirla.

| Contexto | Versión | Tamaño mínimo (referencia) |
|---|---|---|
| Digital | Horizontal completa | 32 px de alto |
| Digital | Solo isotipo / favicon | 24 px de alto |
| Impresión | Horizontal completa | 15 mm de alto |
| Impresión | Solo isotipo | 8 mm de alto |

**Usos incorrectos:** deformar el logo · colores fuera de paleta · sombras o degradados · reordenar isotipo y tipografía · bajo contraste con el fondo · separar la olla del nombre fuera de las variantes oficiales.

### 4.3 Paleta de colores

**Colores de marca**

| Nombre | Hex | Uso |
|---|---|---|
| Naranja Olla | `#F0822D` | Primario / CTA / selección |
| Verde Cercana | `#62B869` | Éxito / disponible |
| Amarillo Cálido | `#F4C430` | Confianza / calificación |
| Vino Abuela | `#901C21` | Personaje / hero |
| Madera Cálida | `#8B5E34` | Tarjetas / contornos |
| Terracota Buscar | `#C84B31` | Foco / acentos / acción |
| Púrpura Admin | `#A855F7` | Rol administrador |
| Error | `#E5484D` | Estados de error |

**Color por rol:** Comprador → verde `#62B869` · Cocinera → naranja `#F0822D` · Admin → púrpura `#A855F7`.

**Colores de interfaz**

| Grupo | Colores |
|---|---|
| Fondos y superficies | `#000000` global · `#17130F` nocturno · `#2A1E17` mapa · `#CBA679` Libretón · `#28221B` panel nocturno · `#3A3025` panel oscuro del menú · `#EFE0C2` papel · `#FAF6F0` crema · `#F5E9D2` cabecera menú · `#F7EDDB` ficha clara · `#DCE4CE` verde claro · `#46513B` verde oscuro |
| Texto y bordes | `#F4F3EF` texto claro · `#F0E5D3` texto claro tema oscuro · `#2C241E` texto mapa · `#2B2117` tinta · `#5B4A38` texto secundario · `#52663D` texto verde · `#AA8B5E` borde cálido · `#705A40` / `#715A3E` bordes oscuros · `#71805D` borde verde · `#F0E3CE` texto menú oscuro |
| Señales | `#448A9C` azul del mapa / agua |

**Equivalencias de impresión (orientativas)**

| Color | RGB | CMYK | Pantone |
|---|---|---|---|
| Naranja Olla | 240,130,45 | 0,58,90,0 | PMS 151 C |
| Verde Cercana | 98,184,105 | 64,0,76,0 | PMS 7488 C |
| Amarillo Cálido | 244,196,48 | 4,22,92,0 | PMS 123 C |
| Vino Abuela | 144,28,33 | 23,98,93,20 | PMS 188 C* |
| Madera Cálida | 139,94,52 | 35,56,87,22 | PMS 7567 C* |
| Terracota Buscar | 200,75,49 | 15,83,90,5 | PMS 7607 C* |
| Púrpura Admin | 168,85,247 | 48,73,0,0 | PMS 2587 C* |

**Accesibilidad (WCAG AA):** no usar texto blanco sobre Amarillo Cálido; el naranja `#F0822D` requiere texto oscuro en texto normal. Verificar el contraste de cada combinación antes de publicar.

### 4.4 Tipografía

| Uso | Fuente | Peso |
|---|---|---|
| Display / H1 (titulares editoriales) | Playfair Display | 700 |
| H2 / etiquetas, navegación | Outfit | 700 |
| Cuerpo y formularios | Outfit | 400 |
| Precios, nombres de platos, citas (acento manuscrito) | Caveat | 700 |

- Caveat no se usa en párrafos largos ni formularios.
- **Contingencia:** Playfair → Georgia/Merriweather · Outfit → Open Sans/Helvetica/Arial · Caveat → Outfit Italic (nunca Comic Sans ni Brush Script).
- Fuentes de Google Fonts: Playfair Display, Outfit, Caveat.

### 4.5 Iconografía

- Estilo lineal y cálido, cuadrícula **24×24 px**, trazo **2 px**, terminales y uniones redondeadas, un solo color según el estado del componente.
- Set base: Chat, Reserva, Pago, Calificación, Ubicación, Tiempo, Aviso, Perfil, Cocina.
- Pilares: Alimentación, Cercanía, Comunidad.

### 4.6 Componentes de interfaz

- **Tarjetas** estilo papel kraft (`#EFE0C2`) con borde `#D8C39C`; contorno madera `#8B5E34` en tarjetas destacadas.
- **Pizarra** (fondo `#26332A`, marco de madera) para listados de platos con precios en Caveat amarillo.
- **Chips:** Reservar (naranja), Disponible (verde), Calificación (amarillo), Error (borde rojo).
- **Inputs:** fondo `#FBF3E7`, borde `#D9B68C`, texto `#4A3222`, placeholder `#A88B6F`.
- **Filtros de proximidad:** Todas, 500 m, 1 km, 1.5 km, 2 km y Abiertas.
- **Mapa:** anillos de 500 m y 1 km, pines ilustrados; la dirección exacta no se muestra hasta confirmar la reserva.

### 4.7 Fotografía y personaje

- **Fotografía:** luz natural lateral y difusa; cenital 90° para bandejas y picado 45° para sopas/cazuelas; menaje tradicional (ollas de barro, cucharas de madera, paños). Nunca acabados de alta cocina ni luz de estudio.
- **Personaje "La abuela de la cuadra":** ilustración 3D simbólica (no es la foto de una cocinera real). Rasgos fijos: gorro de cocinera, gafas redondas, cardigan vino, camisa a cuadros rojo/blanco, corbata azul a rayas, aretes de perla, sosteniendo la olla. Úsala en portada, onboarding y botón de ayuda; no como foto de perfil ni en lugar de fotos reales de comida.

![La abuela](docs/identidad/personaje-abuela.jpg)

---

## 5. Estructura del repositorio

```
repo-front/
├── README.md
└── docs/
    ├── flujo/
    ├── pantallas/
    └── identidad/
```
