# Bitácora — Semana 48 (26–30 nov 2026)

## Corrida del 26-nov-2026 (tarea programada "completar a 3/día")

**Objetivo del día:** subir cada página a 3 publicaciones de feed/día + 1-2 historias
para la semana en curso (26–30 nov), agregando solo lo que falte sin duplicar.

### Resultado: NO se pudo programar contenido nuevo — corrida bloqueada

La sesión programada corre en la nube, aislada, y **no tiene a la mano las
herramientas de diseño ni los insumos** que la tarea necesita:

- No está el kit de diseño ni los `render.py` por página
  (se esperaban en `/mnt/user-data/outputs/mgm/diseno/kit`).
- No está el script de ganchos (`render_gancho.py`).
- No están los catálogos de precios (`/mnt/user-data/outputs/mgm/catalogos`).
- Las carátulas del kit viven en la PC del usuario
  (`C:\Users\porte\OneDrive\Escritorio\portadas-export`) y esta corrida
  programada **no tiene puente al equipo**, así que no se pueden obtener.

Esos archivos vivían en `/mnt/user-data/outputs/…`, que es **almacenamiento
efímero de sesión y no sobrevive entre corridas**. El repositorio solo guarda
las imágenes/videos finales, no los generadores ni las carátulas ni los
catálogos, por lo que una corrida nueva arranca sin ellos.

Crear piezas "a mano" implicaría **inventar carátulas y precios** y salirse de
los diseños aprobados — lo que rompe reglas duras del encargo (solo carátulas
del kit, nunca inventar precios, conservar el diseño aprobado, verse orgánico,
cuidado con Meta). Por eso se optó por **no publicar nada no conforme** y dejar
registro, en lugar de arriesgar las páginas.

### Lo que YA quedó programado esta semana (base del lunes, no se tocó)

| Página      | Día programado | Feed | Historia |
|-------------|----------------|------|----------|
| Mario Games | 26-nov 11:00   | 1 (Silksong/Noticia) | 1 (11:05) |
| Mario Games | 27-nov 11:00   | 1 (más pedidos)      | 1 (17:00) |
| MARIO 2     | 28-nov 12:20   | 1 (más pedidos)      | 1 (17:40) |
| LUIGI 1     | 29-nov 13:40   | 1 (diversión)        | 1 (19:10) |
| Nintenderos | 26-nov 13:10   | 1 (clásicos)         | 1 (19:20) |
| LUIGI 2 (FB)| 28-nov 14:40   | 1 (más pedidos)      | 1 (20:00) |
| MOBA        | 27-nov 12:40   | 1 (arma tu reta)     | 1 (18:50) |
| Hyrule      | 30-nov 15:40   | 1 (¿buscas juegos?)  | 1 (20:10) |
| Coloso      | 30-nov 12:10   | 1 (arsenal del mes)  | 1 (18:20) |

Cada página tiene contenido **en un solo día** de la semana (1 feed + 1 historia).
Los demás días de 26–30 están vacíos.

### Faltante para llegar a la meta (3 feed/día + 1-2 historias)

- Meta: 8 páginas × 5 días × 3 feed = **120 feed**; programadas: **8** →
  **faltan ~112 publicaciones de feed** + ~32 historias.
- Prioridad acordada si no alcanza: primero 26, 27, 28 y las páginas con Instagram.

### Qué se necesita para destrabarlo (recomendación)

1. **Versionar el kit y los catálogos en el repo** (o en un lugar durable),
   para que cada corrida programada los tenga sin depender de la PC ni de
   almacenamiento efímero. Incluir: plantillas/`render.py` por página,
   `render_gancho.py`, carátulas del kit y catálogos de precios.
2. Mientras tanto, la subida a 3/día conviene correrla desde una sesión con
   la **PC conectada** (para alcanzar las carátulas) o con el kit ya cargado.

> Registrado automáticamente por la corrida del 26-nov. La base del lunes queda intacta.
