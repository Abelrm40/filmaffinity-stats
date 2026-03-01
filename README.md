# Filmaffinity Acción — Estadísticas y Buscador

Herramienta para explorar las **mejores películas de acción** según Filmaffinity (>1000 votos).

🔗 **[Abrir aplicación](https://Abelrm40.github.io/filmaffinity-stats/)**

---

## Funcionalidades

### Percentil → Nota
Mueve el slider o escribe un percentil (1–99) para ver qué nota separa ese porcentaje de películas del resto.

> *Ejemplo: el percentil 80 corresponde a una nota de 6.3 — el 80% de las películas tiene una nota inferior a 6.3.*

### Búsqueda inversa — Nota → Percentil
Introduce una nota para saber en qué percentil se encuentra dentro del catálogo.

> *Ejemplo: una nota de 7.0 está en el percentil 87 — supera al 87% de las películas.*

### Buscador de películas
Busca cualquier película por título y consulta su nota media, año de estreno y percentil dentro del ranking.

---

## Datos

- **Fuente:** [Filmaffinity](https://www.filmaffinity.com) — Top Acción ordenado por nota media
- **Filtro:** solo películas con más de 1000 votos
- **Total:** ~1967 películas (1900–2026)

---

## Ejecución local

```bash
pip install -r requirements.txt
python app.py
```

Abre la aplicación en Chrome en `http://localhost:8765` y despliega automáticamente a GitHub Pages.
