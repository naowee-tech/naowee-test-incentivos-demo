# Módulo de Incentivos — Resumen de cambios aplicados

**Para:** Danna · Daniel
**Demo:** https://naowee-tech.github.io/naowee-test-incentivos-demo/incentivo-08-asignar-buscar.html
**Versión actual:** v1.1.2

Hola Danna 👋 Acá está el resumen de **todo lo que se aplicó** a partir de tus anotaciones (Slack + los dos audios). Todo está en vivo en el demo del link de arriba. Abajo te dejo, por cada punto, **lo que pediste** y **lo que se hizo**.

> 💡 **Para probarlo:** entra al demo, en *"Tipo de beneficiario"* elige el tipo y usa estos documentos de prueba:
> - **Deportista:** `1001234567`
> - **Paradeportista:** `1090345678`
> - **Personal de apoyo:** `1050987654`
> - **Institución educativa:** NIT `800.214.553-7`

---

## 1. Grado escolar en los datos del deportista
- **Lo que pediste:** agregar el grado escolar en los datos del deportista.
- **Lo que se hizo:** se añadió la fila **"Grado escolar"** en *Datos del deportista*. Aplica a deportistas y paradeportistas.

## 2. Datos de contacto editables antes de asignar
- **Lo que pediste:** que nombre, teléfono y correo se puedan editar, porque a veces la inscripción trae la info mal puesta — y antes de asignar.
- **Lo que se hizo:** se agregó el bloque **"Datos de contacto"** con un botón **Editar**. El operador puede corregir **nombre, teléfono y correo** antes de asignar, con validación y confirmación. (Teléfono y correo no existían; se agregaron.)

## 3. Tipos de beneficiario (instituciones, paradeportistas, personal de apoyo)
- **Lo que pediste:** por tipo de usuario, poder agregar el de la institución y el otro rol; e incluir a los paradeportistas.
- **Lo que se hizo:** se agregó el selector **"Tipo de beneficiario"** con cuatro opciones: **Deportista · Paradeportista · Personal de apoyo · Institución educativa**. Cada tipo cambia la búsqueda (la institución se busca por **NIT**) y muestra sus propios datos e incentivos.

## 4. Regla de las instituciones = ranking de medallero (solo el 1er lugar)
- **Lo que pediste (audio):** los incentivos de instituciones son un **ranking** (1°, 2°, 3°) pero **solo se le da al primero**. El desempate es: **más medallas de oro** en la final nacional → si empatan, **plata** → si empatan, **bronce** → si empatan, **más deportistas clasificados** a la final nacional. Esto por colegio.
- **Lo que se hizo:** la institución se evalúa por ese ranking. En el demo, el colegio aparece como **1er lugar (#1 de 36)** y las condiciones reflejan el desempate (oro → plata → bronce → deportistas clasificados).

## 5. El código asignado fuera de los resúmenes (seguridad)
- **Lo que pediste:** quitar el código asignado de los resúmenes/comprobantes, porque es el código que se va a redimir y por seguridad no debe quedar a la vista.
- **Lo que se hizo:** el **código redimible ya no aparece** en ningún resumen ni comprobante (selección de incentivo, evidencia de entrega, comprobante de entrega y comprobante de reversión). El operador igual lo selecciona internamente en el inventario, pero **no se imprime ni se muestra** como comprobante.

---

## Mejoras adicionales aplicadas
- **Flujo completo enlazado:** ahora el beneficiario que eliges (deportista, paradeportista, personal de apoyo o institución) **se mantiene en todas las pantallas** del proceso (buscar → seleccionar incentivo → evidencia → comprobante). Antes mostraba siempre a la misma deportista de ejemplo.
- **Selector más claro:** el "Tipo de beneficiario" quedó como **botones de selección única** (radio), más entendible.

---

## ⚠️ Pendiente de tu confirmación
Para dejarlo 100% fiel al reglamento necesito que me confirmes:
1. **El nombre exacto del "otro rol"** que mencionaste — por ahora lo dejé como **"Personal de apoyo"**.
2. **Los criterios/umbrales reales** de la regla institucional (en el demo usé valores de ejemplo: #1 de 36, 14 oros, etc.).
3. Si los **paradeportistas** tienen reglas de elegibilidad propias o usan las mismas que los deportistas.

> Nota: los nombres, montos y medalleros del demo son **datos de prueba** solo para mostrar cómo se ve; se reemplazan con la información real al conectar el sistema.

¡Quedo atento a tus comentarios! 🙌
