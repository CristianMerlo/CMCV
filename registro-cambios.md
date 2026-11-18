# Registro de Cambios - Landing Page CV

**Fecha:** 17 de noviembre de 2026  
**Estado:** En progreso — pausado para continuar mañana

---

## Resumen del Trabajo Realizado

### Fase 1: Actualización de Contenido (Plan original)

#### ✅ Línea de tiempo — Mostaza
Se reemplazó el bloque de 2025 (Burger King) por **3 bloques nuevos** con las fases del rol en Mostaza:

1. **Mar 2025 – May 2025** — Jefe de Mantenimiento
   - Depósito, regiones 1-4, franquicias
   - Logros: organización del depósito, cobertura 4 regiones, procesos de trabajo, integración rápida

2. **May 2025 – Dic 2025** — Gerente de Mantenimiento Sur, Centro y Franquicias
   - Regiones Sur y Centro + franquicias
   - Logros: expansión de cobertura, integración de franquicias, indicadores unificados, mejora tiempos de respuesta

3. **Ene 2026 – Actualidad** — Gerente de Mantenimiento de Franquicias
   - Gestión integral para red de franquicias
   - Logros: consolidación de procesos, gestión de contratos, KPIs, optimización de costos

> **Nota:** Los logros son genéricos y pueden refinarse con más detalles del usuario.

#### ✅ Metadatos actualizados
- **Título:** "Cristian Merlo | Gerente de Mantenimiento - CV Profesional"
- **Descripción:** Incluye "Mostaza" y "Gerente de Mantenimiento"
- **Keywords:** "Cristian Merlo, CV, curriculum, mantenimiento, gerente, Mostaza, Burger King, Starbucks, franquicias"
- **Open Graph:** Agregados tags para compartir en redes sociales
- **Twitter Card:** Agregados tags

#### ✅ Intereses actualizados
- Cambiada la tarjeta "No Code y Automatización" por **"IA Aplicada"** (IA generativa y automatización inteligente) con icono de robot.
- Se mantuvieron ambas tarjetas de IA ("Inteligencia Artificial" e "IA Aplicada") según preferencia del usuario.

#### ✅ Capacitación rediseñada
- De lista plana `<ul>` a **cards con grid**
- Agrupada en dos secciones:
  - **Certificaciones Recientes** (2019 en adelante): 11 cards
  - **Formación Base** (antes de 2019): 6 cards
- Cada card muestra: año como badge, nombre de certificación, institución

#### ✅ Footer agregado
- Copyright: "© 2026 Cristian Merlo — Gerente de Mantenimiento"

#### ✅ Botones "Ver logros"
- Ahora cambian dinámicamente a "Ocultar logros" al expandir

#### ✅ Botón LinkedIn
- Mejorado con gradiente, glow y `target="_blank"`

---

### Fase 2: Rediseño "Tech pero elegante"

#### Decisiones de diseño tomadas por el usuario:
- **Estilo visual:** Tech pero elegante
- **Fondo:** Mantener los circuitos animados como están
- **Resumen profesional:** No agregar por ahora
- **Paleta de colores:** Oscuro con acento azul
- **Contacto:** Solo LinkedIn (mejorar botón existente)
- **Fechas de Mostaza:** Fechas específicas en cada bloque
- **Capacitación:** Cards con año e institución

#### ✅ Paleta de colores aplicada
| Elemento | Color | Uso |
|----------|-------|-----|
| Fondo | `#0f172a` | Fondo principal oscuro |
| Tarjetas | `#1e293b` | Cards de contenido |
| Texto principal | `#f1f5f9` | Títulos y texto claro |
| Texto secundario | `#cbd5e1` | Párrafos |
| Texto terciario | `#94a3b8` | Descripciones e instituciones |
| Acento principal | `#4d94ff` | Botones, badges, línea de tiempo |
| Acento hover | `#60a5fa` | Estado hover de botones |
| Acento oscuro | `#1e40af` | Gradientes |
| Footer | `#64748b` | Texto del footer |

#### ✅ Efectos visuales
- **Glow en hover:** Todos los elementos interactivos tienen `box-shadow` con `rgba(77, 148, 255, 0.X)`
- **Gradientes:** Botones y badges usan `linear-gradient(135deg, #4d94ff, #1e40af)`
- **Línea de tiempo:** Gradiente azul con glow, nodos con efecto hover
- **Fondo de circuitos:** Opacidad reducida a 0.15 para no competir con el contenido

---

## Estado Actual de los Archivos

### `index.html` (819 líneas)
- Estructura completa con todos los bloques actualizados
- Metadatos, Open Graph, Twitter Card
- 3 bloques de Mostaza + bloques históricos (2024-2002)
- 9 tarjetas de proyectos (Burger King/Starbucks)
- 8 tarjetas de intereses
- 17 cards de capacitación (11 recientes + 6 base)
- Botón LinkedIn mejorado
- Footer con copyright
- Scripts: toggleVisibility + circuit-bg animado

### `index.css` (575 líneas)
- Tema oscuro completo con acentos azules
- Todos los estilos actualizados para la nueva paleta
- Grid responsive para proyectos, intereses y capacitación
- Efectos hover con glow en todos los elementos interactivos
- Media queries para móvil (768px)

---

## Lo Pendiente

### Mejoras propuestas (de `propuesta-mejoras-diseno.md`, ya eliminado)
El usuario pidió ver una propuesta completa primero. Se creó el archivo con 14 recomendaciones, pero fue eliminado tras aplicar los cambios de prioridad crítica y alta.

**Lo que NO se implementó aún:**
1. **Resumen profesional** — El usuario dijo "no por ahora"
2. **Tipografía** — Roboto se mantiene, se propuso Inter o DM Sans
3. **Grid fijo en intereses** — Sigue siendo `auto-fit`
4. **Proyectos de Mostaza** — Sin proyectos por ahora
5. **Accesibilidad** — Sin `aria-labels` ni `aria-expanded`
6. **Performance** — Canvas animado sin `IntersectionObserver`
7. **Tags de impacto en proyectos** — Tags genéricos actuales

### Próximos pasos sugeridos
1. **Refinar los logros de Mostaza** con detalles específicos del usuario
2. **Agregar proyectos de Mostaza** cuando haya material
3. **Resumen profesional** — Reconsiderar agregar subtítulo debajo del nombre
4. **Tipografía** — Evaluar cambiar a Inter o DM Sans
5. **Accesibilidad** — Agregar `aria-labels` y mejorar contraste
6. **Performance** — Pausar animación del canvas cuando no es visible
7. **Nuevas capacitaciones** — Si hay certificaciones desde 2024
8. **Sección de contacto** — Solo LinkedIn por ahora, pero podría ampliarse

---

## Decisiones Clave Tomadas

| Decisión | Elección del usuario | Razón |
|----------|---------------------|-------|
| Estilo visual | Tech pero elegante | Mantener los circuitos pero con colores oscuros y acentos brillantes |
| Fondo | Dejarlo como está | No es prioridad, enfocarse en otras mejoras |
| Resumen profesional | No por ahora | Prefiere que el nombre sea lo primero |
| Paleta | Oscuro con acento azul | Estilo dashboard moderno |
| Contacto | Solo LinkedIn | Mejorar el botón actual sin agregar más datos |
| Fechas Mostaza | Fechas específicas | "Mar 2025 – May 2025", etc., en lugar de "2025" genérico |
| Capacitación | Cards con año e institución | Tarjetas pequeñas con año como badge |
| Proyectos Mostaza | Sin proyectos por ahora | Dejar la sección como está hasta tener más detalles |
| Doble tarjeta IA | Mantener ambas | Cubren aspectos diferentes |
| Intereses | Cambiar No Code a IA Aplicada | El tema evolucionó desde entonces |
| Capacitaciones nuevas | Sin nuevas | Dejar la sección como está con la última de 2024 |

---

## Notas Técnicas

- **Font Awesome:** Versión 5.15.4 (CDN)
- **Google Fonts:** Roboto (300, 400, 500, 700)
- **Canvas:** Animación de circuitos con `requestAnimationFrame`, 15 circuitos, opacidad 0.15
- **Responsive:** Media query a 768px para móvil
- **JavaScript:** `toggleVisibility()` para expandir/colapsar logros
