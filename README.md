# World Cup Database Project

Proyecto realizado como parte de **freeCodeCamp - Relational Database Certification**.  
El objetivo fue crear una base de datos en PostgreSQL para almacenar y consultar los resultados de los partidos de las últimas Copas del Mundo.

---

## Descripción

El proyecto incluye:
- Creación de la base de datos **worldcup**
- Tablas relacionales `teams` y `games` con llaves foráneas
- Inserción automática de datos desde `games.csv` con **Bash**
- Consultas SQL para obtener estadísticas y resultados

---

## 📁 Archivos

| Archivo | Descripción |
|----------|--------------|
| `insert_data.sh` | Script Bash que carga los datos desde el CSV a la base de datos |
| `queries.sh` | Contiene las consultas SQL que generan las estadísticas solicitadas |
| `worldcup.sql` | Dump completo de la base de datos con su estructura y datos |
| `games.csv` | Dataset con los partidos de las Copas del Mundo |

---

## ⚙️ Tecnologías utilizadas
- **PostgreSQL**
- **Bash**
- **Linux CLI**
- **freeCodeCamp VM**
