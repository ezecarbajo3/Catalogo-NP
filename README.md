# Catálogo NP — Base de investigación

Base de conocimiento acumulativa para el **Catálogo de Monedas Argentinas** (Numismática Popper). Todos los días, a las 19 h, una sesión de investigación toma la siguiente serie de monedas, busca información en fuentes oficiales, papers, subastas, foros y redes, y la registra acá con su fuente.

## Cómo se organiza

| Archivo / carpeta | Qué tiene |
|---|---|
| `indice.md` | La lista de las 44 series, en orden, con su estado. Muestra qué se hizo y qué sigue. |
| `monedas/` | Un archivo por serie, agrupados por sistema monetario. Es el contenido principal. |
| `temas/` | Información que afecta a varias series (leyes generales, Casa de Moneda, grabadores, fundiciones). |
| `fuentes.md` | Registro de todas las fuentes, cada una con su código `F-####`. |
| `bitacora.md` | Qué se hizo cada día, qué se encontró y qué se corrigió. Lo más reciente, arriba. |
| `documentos/` | Copias de documentos clave cuando se pueden guardar. |
| `PROTOCOLO.md` | Las reglas exactas que sigue cada sesión. |
| `CONTEXTO.md` | Resumen de la visión del catálogo que guía la investigación. |
| `plantillas/serie.md` | Estructura de cada archivo de serie. |

## Cómo leer un dato

```
- Parte de la emisión de 1883 se habría exportado a Europa y fundido. [F-0041] · probable
```

- `[F-0041]` → buscá ese código en `fuentes.md` para ver de dónde sale.
- `confirmado` → fuente oficial o varias fuentes sólidas que coinciden.
- `probable` → una fuente sólida no oficial, o varias comunitarias coincidentes.
- `a confirmar` → una sola fuente débil o fuentes en contradicción.

## Ritmo

Cada serie tiene sesiones de **investigación** (`i`) y una de **revisión** (`r`), que busca en lugares distintos para confirmar, corregir y limpiar redundancias. Las series cortas llevan `1i+1r` (2 días); las largas o con mucha historia, `2i+1r` (3 días). Primera ronda completa: 113 sesiones. Después, el ciclo sigue con revisiones de segunda ronda.

## Historial de cambios

Cada sesión queda como un cambio guardado (commit) con fecha. En GitHub, el botón **History** de cualquier archivo muestra cómo cambió cada dato y cuándo.
