# Lab_BDA
# BDA – Prácticas SQL (Oracle)

Repositorio con mis **consultas SQL** para las prácticas de **Bases de Datos**.  
Incluye soluciones comentadas y listas para ejecutarse en **Oracle** (SQL*Plus / SQLcl / SQL Developer).  
También encontrarás variantes equivalentes con `GROUP BY + HAVING` cuando aporta claridad o eficiencia.

---

## 📦 Contenido del repositorio

- `practicas_bda.sql` – Script con todas las consultas (numeradas y comentadas).
- `ABOUT.md` – Contexto del proyecto y objetivos de aprendizaje.
- `README.md` – Este archivo: instrucciones de uso, ejecución y notas.

> Si tu dataset se carga con scripts del profesorado, ejecútalos antes de correr `practicas_bda.sql`.

---

## 🧰 Requisitos

- **Oracle** (SQL*Plus, SQLcl o SQL Developer).
- Esquema docente con tablas: `ACTOR`, `ACTOR_E`, `MOVIE`, `GENRE`, `CLASSIFICATION`.

Comprobación rápida del esquema:
```sql
DESC ACTOR;
DESC ACTOR_E;
DESC MOVIE;
DESC GENRE;
DESC CLASSIFICATION;
