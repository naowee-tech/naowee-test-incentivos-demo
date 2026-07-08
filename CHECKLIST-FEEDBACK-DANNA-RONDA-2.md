# Checklist — Feedback Danna (Ronda 2: Video + Audio)

> Fuentes verificadas: `WhatsApp Video 2026-06-22 at 4.57.14 PM.mp4` + `WhatsApp Audio 2026-06-22 at 5.25.37 PM (1).ogg`
> Transcripciones locales · Estado del demo: **v1.1.2** ([live](https://naowee-tech.github.io/naowee-test-incentivos-demo/incentivo-08-asignar-buscar.html))

---

## 🎥 Del VIDEO

> *"Lo que él decía era que en los reglamentos ellos estipulaban de que, al igual que los deportistas [y] personal de apoyo, iban a entregar incentivos también destinados a las **instituciones educativas**, también a los **personales de apoyo** que asisten a los deportistas, a los **paradeportistas**. […] Habría que, **por tipo de usuario**, colocarle aquí cómo añadirle el de la institución y el del otro rol, que no sé qué nombre va a poner, que creo que es el mismo personal de apoyo, ¿no? Bueno, igual te confirmo. Habría que colocarlo aquí. Y la regla de las instituciones es, por ejemplo, que tenga la mayor cantidad de medallas de oro recibidas, de plata y así."*

- [x] **Añadir tipo "Institución educativa"** con búsqueda por NIT
- [x] **Añadir tipo "Paradeportista"** (chip demo `1090345678 · paradeportista aplica`)
- [x] **Añadir "el otro rol" para personal de apoyo** (agregado como "Personal de apoyo")
- [x] **Regla institución: mayor cantidad de oros / platas / …** (base implementada)
- [ ] ⚠️ **Confirmar nombre exacto del "otro rol"** — Danna dijo *"igual te confirmo"*. Provisional: **"Personal de apoyo"**.

## 🔊 Del AUDIO ("desglose de incentivos para entidades")

> *"Elkin, de los incentivos de las instituciones educativas es un ranking, saca primero, segundo y tercero **aunque solo la vamos a dar al primero**. En deportes convencionales, el que más medallas de oro tengan en la final nacional; si empatan, en medalla de plata; si empatan, medalla de bronce; y si empatan, el que más número de deportistas clasificados a la final nacional hayan tenido. **Eso por colegio.** Le vamos a dejarlo por colegio. Y **lo mismo para deportes, para medallería**. Y eso va en el módulo de incentivos."*

- [x] **Ranking 1°/2°/3° pero solo el primero recibe**
- [x] **Desempate: oro → plata → bronce → # deportistas clasificados a la final nacional**
- [x] **Por colegio** (agrupación institucional)
- [ ] ❓ **"Lo mismo para deportes, para medallería"** — no aplicado aún. Puede significar:
  - (a) que también se aplica un ranking/medallero al **deportista individual** para ciertos incentivos, o
  - (b) que la regla del colegio se calcula sumando el medallero de sus deportistas.
  - **Pendiente aclarar con Danna.**

---

## ➕ Cosas colaterales aplicadas esta ronda (no de Danna, pero relevantes)

- [x] **Código redimible fuera de resúmenes** (pantallas 09, 10, 11) — seguridad.
- [x] **Código fuera del comprobante de reversión** (pantalla 13) — seguridad.
- [x] **Tabs → radio buttons canónicos** para "Tipo de beneficiario" (mejor UX).
- [x] **Flujo enlazado por beneficiario** (08 → 10 → 09 → 11) — fix del bug que apareció al probar institución.
- [x] **Copy del éxito genérico** ("perfil del beneficiario" en lugar de "deportista") — coherente con los nuevos tipos.

---

## ⏳ Pendientes reales que necesito de Danna

1. **Nombre del "otro rol"** — ¿es *Personal de apoyo* o le van a poner otro nombre?
2. **"Lo mismo para deportes, para medallería"** — ¿se aplica una regla de ranking/medallero también al **deportista individual**? ¿O es la regla del colegio que agrega el medallero de sus deportistas?
3. **Criterios / umbrales reales de la regla institucional** — mis valores son de ejemplo (14 oros, 9 platas, 6 bronces, 48 clasificados). ¿Se calculan de una tabla oficial?
4. **Reglas de elegibilidad de paradeportistas** — ¿usan las mismas condiciones que los deportistas o tienen las suyas (categorías paralímpicas, discapacidad certificada, etc.)?

Cuando me confirmes estos 4 puntos, aplicamos y bumpeamos a `v1.2.0`.
