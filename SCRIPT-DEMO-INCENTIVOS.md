# 🎤 Script Demo Incentivos — SUID + Ministerio
**Tono:** profesional, cercano, con pausas naturales.
**Duración estimada:** 12–15 min + Q&A.
**URL demo:** https://naowee-tech.github.io/naowee-test-incentivos/

> 💡 **Tips de entrega:**
> - Respira antes de cada bloque nuevo.
> - Donde dice `[pausa]`, espera 2 segundos reales.
> - Usa esto como guía, no como lectura.
> - Si te trabas, retoma con "bueno, retomando…" y sigue.

---

## 🎬 APERTURA (2–3 min)

> Buenas tardes a todos. *[sonrisa, contacto visual]*
>
> Primero que todo, **muchas gracias por el espacio**. Hoy les voy a presentar el **módulo de Incentivos**, uno de los componentes que hemos venido desarrollando dentro de la plataforma Naowee.
>
> Antes de entrar a la herramienta, déjenme contextualizar rápidamente de qué se trata. *[pausa]*
>
> Miren, este módulo lo diseñamos para resolver una necesidad muy puntual: **cómo desde Ministerio o desde SUID pueden gestionar la entrega de beneficios, premios y reconocimientos** — becas, kits, bonos, inscripciones, transporte — a deportistas y a su personal de apoyo, con **trazabilidad completa**: qué se entregó, a quién, cuándo, y con **evidencia de respaldo verificable** — certificados, comprobantes o documentos firmados.
>
> ¿Por qué le dimos esa importancia a la trazabilidad? Porque cuando se entrega un incentivo siempre puede surgir la duda de si efectivamente llegó y a la persona correcta. Este módulo elimina esa duda. **Todo queda auditado y respaldado documentalmente.**
>
> Un detalle importante que conviene mencionar de entrada: el módulo contempla que los incentivos **no solo van a deportistas, sino también a su personal de apoyo** — entrenadores, coaches, preparadores físicos — porque son parte integral del proceso deportivo.
>
> Listo, entonces… el módulo está pensado para **dos perfiles** principales:
>
> El primero es el **gestor administrativo** — del lado de Ministerio o SUID — la persona que **crea los programas**, **define el rubro presupuestal**, **carga los códigos** y **supervisa la operación**.
>
> El segundo es el **operador de campo** — la persona que está en territorio entregando los incentivos a los beneficiarios, capturando la evidencia y registrando cada entrega.
>
> A continuación voy a mostrarles el flujo completo de ambos perfiles. Empezamos con el gestor administrativo, que cubre toda la parametrización, y cerramos con la vista del operador, que es donde realmente se materializa la entrega. ¿Listo? Vamos.

---

## 🎬 PARTE 1 — PERFIL GESTOR ADMINISTRATIVO (8–10 min)

### 🟦 Login (incentivo-01)
> Arrancamos. *[click pantalla 01]*
>
> Este es el ingreso al sistema mediante **SUID**. Ustedes ya conocen el flujo de autenticación con sus credenciales institucionales, así que no me voy a detener mucho aquí. *[click "Ingresar"]*

### 🟦 Dashboard (incentivo-02)
> Y bien, llegamos al **dashboard principal**. *[pausa para que lo vean]*
>
> Fíjense que arriba tenemos un saludo personalizado y un resumen muy directo de la operación: en este caso, *"Tienes 3 programas activos y 47 asignaciones hoy"*.
>
> Luego tenemos los **indicadores clave** en tiempo real: **inventario disponible**, **asignaciones del día**, **reversiones del día** y la **ejecución del rubro 2026**. Es decir, una **fotografía ejecutiva** del estado nacional del módulo.
>
> Más abajo encontramos la sección de **programas activos** con sus tarjetas correspondientes, la **actividad reciente** del sistema, y la **distribución geográfica de asignaciones** del año en curso, que permite ver dónde se está concentrando la entrega.

### 🟦 Programas (incentivo-03)
> Pasemos ahora al **listado completo de programas**. *[click sidebar]*
>
> Aquí pueden visualizar todos los programas creados. Arriba tenemos los **indicadores consolidados**: rubro total, ejecutado, inventario y revertidos.
>
> Y más abajo, una **vista de conteo por estado**: programas totales, activos, borradores y cerrados.
>
> La tabla muestra cada programa con su **estado, rubro/ejecución, códigos, vigencia y acciones disponibles**. Pueden **filtrar por estado**, **exportar el listado** o, por supuesto, **crear un programa nuevo**. Vamos a crear uno para mostrarles el wizard, que es uno de los puntos fuertes del módulo — son **cinco pasos guiados** que cubren todo el ciclo de definición del programa.

### 🟦 Crear Programa — Wizard (incentivo-04)
> *[click Nuevo programa]*
>
> **Presten atención a esto, que es un punto clave.** *[pausa]*
>
> En lugar de un formulario extenso, optamos por un **wizard de cinco pasos**.
>
> ---
>
> **Paso 1 — Datos del programa.** *[muestra el primer pane]*
>
> Acá definimos los datos básicos: **nombre del programa**, una **descripción breve**, el **evento o categoría asociado** — por ejemplo "Juegos Nacionales 2025", "Olimpiadas Indígenas 2026" — y el **responsable**.
>
> Más abajo: la **vigencia** desde y hasta, y la **cobertura territorial**, que puede ser Nacional o por departamentos específicos como Atlántico, Cundinamarca, Antioquia, Valle, Santander.
>
> *[click Continuar]*
>
> ---
>
> **Paso 2 — Rubro presupuestal.**
>
> Acá se define **el monto asignado por el ministerio** a este programa. El sistema descontará automáticamente de este rubro por cada asignación realizada.
>
> Capturamos el **rubro total en pesos colombianos**, la **fuente presupuestal** — Ministerio del Deporte, recursos de regalías, esquema mixto — y una **justificación opcional** que típicamente referencia la resolución de soporte.
>
> Importante: **un programa solo puede tener un rubro**. Si posteriormente el ministerio amplía el presupuesto, se aumenta este mismo rubro y se cargan códigos adicionales.
>
> *[click Continuar]*
>
> ---
>
> **Paso 3 — Tipos de incentivo.**
>
> Acá definimos **qué se va a entregar**. Puede ser un único tipo o varios combinados.
>
> Para cada incentivo capturamos: **nombre**, **categoría** — Bono, Beca, Kit, Transporte, Inscripción, Descuento, Pase o acceso, Dinero — y el **tipo de incentivo**:
>
> - **Cualitativo con valor monetario** — nombre descriptivo y un valor asociado.
> - **Sólo monetario** — valor puro sin categoría descriptiva.
> - **Sólo cualitativo** — sin valor monetario explícito, y **no se descuenta del rubro**.
>
> Finalmente, **valor unitario** y **cantidad estimada** de beneficiarios.
>
> *[click Continuar]*
>
> ---
>
> **Paso 4 — Condiciones de elegibilidad.**
>
> Este paso es uno de los más potentes del módulo. Acá se parametrizan **las reglas que debe cumplir un beneficiario para aparecer en los resultados del operador** al momento de asignar.
>
> Tenemos un **constructor de reglas** que permite combinar condiciones con **AND** y **OR**, organizándolas en grupos.
>
> Las variables disponibles son: **edad, género, estrato, disciplina, categoría deportiva, zona, logros, matrícula** — con operadores como igual, mayor o igual, entre rangos, pertenece a un conjunto.
>
> Y observen este detalle: abajo tienen siempre una **vista previa de la regla** en lenguaje claro. Por ejemplo: *"edad mayor o igual a 18, y categoría prejuvenil o superior, O logros incluyen oro o plata"*. Esto evita confusiones al armar criterios complejos.
>
> *[click Continuar]*
>
> ---
>
> **Paso 5 — Códigos y revisión.**
>
> Y para cerrar: la **revisión final** antes de activar el programa. Acá ven el resumen consolidado y deciden si **guardan como borrador** o si **activan el programa**, lo que lo deja disponible para que los operadores empiecen a asignar incentivos en campo.
>
> *[click Activar programa]*
>
> Y listo, el programa queda **operativo**.

### 🟦 Detalle del Programa (incentivo-05)
> Una vez creado, podemos entrar al **detalle del programa**. *[click en un programa del listado]*
>
> Esta vista funciona como la **ficha completa** y se organiza en pestañas: **Resumen, Condiciones, Códigos, Asignaciones e Historial**.
>
> Arriba ven los mismos indicadores clave del programa: rubro total, ejecutado, inventario, revertidos.
>
> Y un detalle importante que vale la pena resaltar: **únicamente los Bonos manejan códigos canjeables**. Los demás tipos — beca, kit, inscripción, transporte — se cargan como **cantidad de cupos disponibles**, sin código asociado. Esto refleja cómo funcionan realmente en operación.

### 🟦 Cargar Códigos (incentivo-06)
> Cuando un programa contempla la entrega de bonos, **es necesario cargar los códigos al inventario**. *[click en Cargar códigos]*
>
> Tenemos dos modalidades: **carga masiva por Excel o CSV**, o **carga manual uno por uno**.
>
> En la carga masiva, el sistema **valida cada código** y lo marca como: **Válido**, **Duplicado — ya existe en inventario** o **Inválido — formato incompleto**. Esto permite corregir antes de confirmar.
>
> Y si necesitan la **plantilla oficial**, está disponible en el botón "**Descargar plantilla .xlsx**" para que el cargue salga limpio desde el principio.
>
> Un ejemplo típico: el ministerio amplía el rubro y se necesitan 50 códigos adicionales. Acá se cargan, se validan y quedan disponibles.

### 🟦 Inventario de Códigos (incentivo-07)
> Tenemos también una **vista consolidada del inventario de códigos** de todos los programas. *[click sidebar]*
>
> Arriba, los indicadores: **códigos totales, disponibles, asignados, revertidos**.
>
> Y la tabla permite **filtrar por estado, tipo y programa**, o buscar por código o beneficiario específico. Cada fila muestra el código, programa, estado, beneficiario, operador, fecha, valor y las acciones disponibles.
>
> Si por algún motivo se requiere **revertir un código** desde acá, se abre el modal correspondiente donde se captura el **motivo de la reversión**, el **solicitante** y la **justificación**. Todo queda registrado en el historial.

---

## 🎬 PARTE 2 — PERFIL OPERADOR DE CAMPO (4–5 min)

> Bien, hasta acá toda la parte administrativa. **Ahora vamos al flujo del operador**, que es quien efectivamente entrega los incentivos en territorio.

### 🟦 Asignar — Buscar Beneficiario (incentivo-08)
> *[click Asignar incentivo]*
>
> El flujo arranca buscando al beneficiario. **Se ingresa el tipo y número de documento** — cédula, tarjeta de identidad, según el caso — y el sistema **valida automáticamente** si esa persona cumple las condiciones de algún programa activo.
>
> Vale la pena recordar lo que mencioné al inicio: **el sistema reconoce tanto deportistas como personal de apoyo** — entrenadores, coaches, preparadores. Si la persona aplica, aparece en los resultados; si no cumple condiciones, el sistema lo indica.
>
> Tenemos varios casos de demostración para ilustrar los escenarios posibles: *"deportista aplica"*, *"1 de 2 ya asignado"*, *"todos ya asignados"*, *"deportista no cumple"*, *"entrenador aplica"*, *"entrenador no fue el primero"* y *"sin registro"*. Esto cubre toda la casuística que puede aparecer en campo.
>
> *[selecciona un caso que aplica]*

### 🟦 Seleccionar Incentivo y Código (incentivo-10)
> Beneficiario validado. Pasamos a **seleccionar el incentivo aplicable**. *[muestra pantalla]*
>
> Acá el operador ve los incentivos disponibles para este beneficiario según su elegibilidad — por ejemplo: Becas 2026, Kit Atlántico, Bono nutrición. Cada uno marcado con su tipo: **Monetario**, **Cualitativo + Monetario**, según corresponda.
>
> Una vez elegido el incentivo, el operador **selecciona el código del inventario** que va a entregar. Si es un Bono, escoge el código canjeable; si es otro tipo, simplemente confirma el cupo.
>
> *[click Continuar a evidencia]*

### 🟦 Evidencia de Entrega (incentivo-09)
> Y llegamos al paso que mencioné al inicio: **la evidencia de entrega**.
>
> Acá el operador **adjunta un archivo de respaldo** que sustente la entrega — puede ser un **certificado firmado**, un **comprobante** o cualquier **documento de respaldo** que valide que el incentivo se entregó efectivamente al beneficiario.
>
> Adicionalmente, puede capturar **observaciones del operador**, que son opcionales pero útiles para anotar cualquier detalle relevante del momento de la entrega.
>
> Este respaldo queda almacenado y vinculado a la asignación. En una eventual auditoría, **la evidencia está disponible inmediatamente**.
>
> *[click Completar entrega]*

### 🟦 Confirmación de Entrega (incentivo-11)
> Y… *[pausa]* **¡Incentivo entregado con éxito!**
>
> El sistema confirma la operación y genera un **comprobante de entrega** que puede **imprimirse**, descargarse o consultarse después. El código quedó marcado como **Asignado** y el valor **se descontó automáticamente del rubro del programa**.
>
> Desde acá, el operador puede iniciar una **nueva asignación**, **imprimir el comprobante** o ir al **historial**.

### 🟦 Mis Asignaciones — Vista Personal del Operador (incentivo-14)
> Y un detalle importante para el perfil operador: tiene una **vista personal** llamada **"Mis asignaciones"**.
>
> *[click sidebar]*
>
> Acá el operador ve **únicamente las entregas que él o ella ha realizado** en campo. Es decir, **sus métricas personales**: cuántos incentivos otorgó, el valor total entregado, cuántos deportistas únicos atendió y cuántas reversiones tuvo.
>
> Tiene filtros por período — **Hoy, 7 días, 30 días, Todo** — y por estado. Y la tabla detalla cada entrega con fecha, deportista, código, programa, valor y estado.
>
> Esto le permite al operador **tener visibilidad de su propia gestión** y, si lo requiere, **exportar sus entregas**.

---

## 🎬 PARTE 3 — VISTAS TRANSVERSALES (2–3 min)

### 🟪 Historial Consolidado (incentivo-12)
> Para cerrar la parte operativa, déjenme mostrarles el **historial consolidado de asignaciones**, que está disponible para el perfil gestor. *[click sidebar]*
>
> Esta es la vista de auditoría completa. Arriba: **asignaciones totales, del día, de la semana y revertidas**.
>
> Y la tabla detalla **cada entrega del sistema** con fecha, deportista, código, programa, operador, región y estado. Los filtros permiten cortar la información por **programa, región o estado**.
>
> Desde acá también es posible **revertir una asignación** si se requiere. Y cuando eso ocurre, el sistema genera una pantalla de **confirmación de reversión** que documenta el cambio: el código vuelve al inventario, el valor regresa al rubro, y todo queda registrado con timestamp, motivo y datos del gestor que realizó la acción. **La auditoría es completa.**

### 🟪 Reportería (incentivo-15)
> Y para rematar: el módulo de **reportería**. *[click sidebar]*
>
> Acá el gestor puede **consolidar programas, bonos e incentivos entregados**, filtrar por **año, mes y programa**, **previsualizar el resultado** antes de descargar, y generar el reporte final para **auditoría y rendición de cuentas**.
>
> Esto cierra el ciclo: desde la creación del programa hasta el reporte ejecutivo.

---

## 🎬 CIERRE (1–2 min)

> Y bien… ese es el módulo en su conjunto. *[pausa, contacto visual]*
>
> Como lo mencioné al inicio: el objetivo es que **la entrega de incentivos sea trazable, auditable y completamente controlada** desde SUID y Ministerio — desde la creación del programa hasta el detalle de quién recibió qué, cuándo y con qué evidencia de respaldo.
>
> Quiero precisar que lo que les mostré es la **demostración funcional**. Quedan pendientes la integración con el backend productivo, la conexión con sus sistemas de beneficiarios y los **ajustes que ustedes nos retroalimenten** a partir de esta sesión. Pero el **flujo, la arquitectura y la lógica del módulo están definidos** y listos para avanzar.
>
> Quedo atento a sus preguntas, comentarios y observaciones. *[pausa larga]*
>
> **Muchas gracias por su atención.**

---

## 📋 Cheat sheet — orden de tabs

Abre estas pestañas en orden antes de arrancar:

1. `incentivo-01-login.html`
2. `incentivo-02-dashboard.html`
3. `incentivo-03-programas.html`
4. `incentivo-04-programa-crear.html` *(wizard 5 pasos)*
5. `incentivo-05-programa-detalle.html`
6. `incentivo-06-codigos-carga.html`
7. `incentivo-07-codigos.html`
8. `incentivo-08-asignar-buscar.html`
9. `incentivo-10-asignar-tipo.html`
10. `incentivo-09-validar-foto.html` *(evidencia de entrega)*
11. `incentivo-11-asignar-exito.html`
12. `incentivo-14-mis-asignaciones.html` *(vista personal operador)*
13. `incentivo-12-asignaciones.html` *(historial consolidado)*
14. `incentivo-13-revertir.html`
15. `incentivo-15-reporteria.html`

---

## 🆘 Frases de respaldo (si algo no carga o necesitas retomar)

- *"Mientras carga la pantalla, déjenme adelantarles que…"*
- *"Ese es un detalle visual que estamos puliendo, pero la lógica funcional es la que les expliqué."*
- *"Excelente pregunta, permítanme tomar nota y la abordamos al cierre."*
- *"Ese punto lo ajustaremos con base en la retroalimentación que ustedes nos den."*
- *"Para efectos de esta demostración trabajamos con data de prueba. En el ambiente productivo, esto se conectará con sus sistemas reales."*

---

## ✅ Datos clave verificados contra la demo live

- ✔️ Wizard de **5 pasos**: Datos → Rubro → Tipos → Condiciones → Códigos y revisión
- ✔️ Pantalla 09 = **"Evidencia de entrega"** (no solo foto: certificado, comprobante o documento)
- ✔️ Pantalla 14 = **vista del operador** (no del beneficiario): sus entregas en campo
- ✔️ Solo **Bonos** manejan códigos canjeables; resto son cupos
- ✔️ Carga **Excel o CSV** con validación Válido / Duplicado / Inválido
- ✔️ Aplica a **deportistas + personal de apoyo** (entrenadores, coach, preparadores)
- ✔️ Reversión devuelve **código al inventario** + **valor al rubro**

¡Éxitos mañana, Doug! 🚀
