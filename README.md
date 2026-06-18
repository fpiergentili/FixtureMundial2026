# Fixture Mundial 2026 — Calendarios para Google Calendar

Calendarios en formato `.ics` con los partidos de la **Copa Mundial de la FIFA 2026** (Canadá, México y Estados Unidos · 11 jun – 19 jul 2026), con **todos los horarios convertidos a hora de España (Europe/Madrid, CEST / UTC+2)**.

Listos para importar en Google Calendar, Apple Calendar, Outlook o cualquier app compatible con iCalendar.

## Archivos

| Archivo | Contenido | Nº de eventos |
|---|---|---|
| `Mundial_2026_calendario_ES.ics` | Los 104 partidos del torneo (fase de grupos + eliminatorias) | 104 |
| `Mundial_2026_Argentina_ES.ics` | Solo los partidos de la selección de Argentina (Grupo J) | 3 |

Cada evento incluye los equipos, la fase, la sede/estadio y, en la descripción, la hora local del estadio junto a la hora de España.

## Cómo importar en Google Calendar

1. Abre [Google Calendar](https://calendar.google.com) en el navegador.
2. Pulsa ⚙️ **Configuración** → **Importar y exportar**.
3. En **Importar**, selecciona el archivo `.ics` que quieras.
4. Elige el calendario de destino y pulsa **Importar**.

> Consejo: crea antes un calendario nuevo (p. ej. *Mundial 2026*) para importar ahí los eventos y poder ocultarlos o borrarlos en bloque.

## Detalles técnicos

- **Zona horaria:** todos los eventos se anclan a `Europe/Madrid` mediante un bloque `VTIMEZONE`, por lo que se muestran en hora española independientemente de la zona del dispositivo.
- **Duración:** cada partido está fijado en 2 horas.
- **Fase de grupos:** equipos reales según el sorteo (5 dic 2025).
- **Eliminatorias:** los cruces (dieciseisavos en adelante) aparecen con marcadores provisionales (`1º Grupo E`, `2º Grupo C`, `Ganador P89`, etc.) porque dependen de los resultados. Los horarios de eliminatorias son los provisionales de la FIFA y pueden ajustarse.

## Partidos de Argentina (Grupo J) — hora de España

| Partido | Fecha y hora (España) | Sede |
|---|---|---|
| Argentina vs Argelia | 17 jun 2026, 03:00 | Arrowhead Stadium, Kansas City |
| Argentina vs Austria | 22 jun 2026, 19:00 | AT&T Stadium, Arlington |
| Jordania vs Argentina | 28 jun 2026, 04:00 | AT&T Stadium, Arlington |

## Fuentes

- [FIFA — Calendario oficial](https://www.fifa.com/en/tournaments/mens/worldcup/canadamexicousa2026/scores-fixtures)
- [Wikipedia — 2026 FIFA World Cup](https://en.wikipedia.org/wiki/2026_FIFA_World_Cup)

---

*Datos recopilados en junio de 2026. Horarios sujetos a posibles cambios por parte de la FIFA.*
