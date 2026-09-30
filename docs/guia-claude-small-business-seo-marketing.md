# Guía de uso: Claude for Small Business para SEO y marketing

Fuente: [Claude for Small Business](https://www.anthropic.com/news/claude-for-small-business) (Anthropic, mayo de 2026).

## 1. Qué es (según el anuncio)

Un paquete que integra Claude en las herramientas que ya usa un negocio pequeño: **15 flujos de trabajo agénticos** y **15 skills de tareas repetibles**, con **aprobación humana antes de ejecutar cualquier acción**. Cubre finanzas, operaciones, ventas, marketing, RR. HH. y atención al cliente.

Conectores mencionados: **HubSpot, Canva, Google Workspace, Microsoft 365, QuickBooks, PayPal y DocuSign**.

> El anuncio no publica precios. La lista completa de skills y conectores está en la página de soluciones de Anthropic.

## 2. Activación

No es algo que se instale con un comando: se activa desde la interfaz.

1. Abre **Claude Cowork**.
2. Activa el toggle **Claude for Small Business**.
3. Conecta tus herramientas (para marketing: **HubSpot, Canva, Google Workspace o Microsoft 365**).
4. Elige los flujos que quieres usar.
5. Revisa y aprueba el plan de Claude antes de que ejecute.

Seguridad: Claude respeta los permisos existentes (no ve lo que tú no puedes ver en Drive o QuickBooks) y, en planes Team y Enterprise, no entrena con tus datos por defecto.

## 3. Flujos del anuncio útiles para marketing

| Flujo | Qué hace | Uso SEO/marketing |
|---|---|---|
| Ejecución de campañas | Detecta huecos de ingresos, analiza el rendimiento en HubSpot, redacta estrategia y genera piezas en Canva | Campañas estacionales, promociones, lanzamientos |
| Estrategia de contenido | Planifica contenido | Calendario editorial y clústeres de temas |
| Triaje de leads | Prioriza contactos en HubSpot | Separar leads de SEO por intención y calidad |
| Business pulse | Panel de caja, ventas, pipeline y compromisos semanales | Reporte semanal de qué canales traen ingresos |
| Insights de clientes (HubSpot) | Atribución de campañas y datos de clientes | Saber qué contenido y campañas convierten |

## 4. Rutina recomendada (sugerencia, no parte del anuncio)

### Semanal (30–45 min)
1. **Pulso del negocio**: pide a Claude el resumen de ventas, pipeline y leads de la semana.
2. **Atribución**: qué campañas y páginas generaron leads en HubSpot.
3. **Contenido**: 1–2 piezas nuevas o actualizaciones (ver prompts abajo).
4. **Diseño**: Claude genera los assets en Canva; tú apruebas.

### Mensual
- Revisión de las páginas que más y menos convierten.
- Actualizar el calendario editorial con base en lo que funcionó.
- Reseñas y ficha de Google (si tienes negocio local): responder y pedir nuevas.

### Trimestral
- Auditoría de SEO técnico y de contenido (ver checklist).
- Revisar competidores y huecos de palabras clave.

## 5. Prompts listos para usar

Reemplaza los corchetes con tus datos.

**Estrategia de contenido SEO**
> Soy [tipo de negocio] en [ciudad/país]. Mi cliente ideal es [perfil]. Con los datos de HubSpot y mi sitio, propón 10 temas de contenido agrupados en 3 clústeres, con la intención de búsqueda de cada uno (informativa, comparativa, transaccional) y qué página existente reforzarían. No publiques nada; muéstrame el plan.

**Brief de artículo**
> Crea un brief para un artículo sobre "[palabra clave]": intención de búsqueda, título (máx. 60 caracteres), meta descripción (máx. 155), H1–H3, preguntas frecuentes a responder, enlaces internos sugeridos y llamada a la acción.

**Optimización de una página existente**
> Revisa esta página: [URL o texto]. Dame título, meta descripción, encabezados, mejoras de contenido, enlaces internos y datos estructurados (schema) recomendados. Ordena los cambios por impacto y esfuerzo.

**SEO local**
> Redacta 8 publicaciones para mi ficha de Google Business Profile y 5 respuestas modelo a reseñas (positivas, neutras y negativas) con el tono de [marca].

**Campaña completa**
> Analiza en HubSpot las ventas de los últimos 90 días, identifica el producto o servicio con mayor hueco frente a la meta, propón una campaña de 4 semanas (canales, mensajes, calendario) y genera en Canva 3 publicaciones y 1 banner. Espera mi aprobación antes de crear nada.

**Email a partir de contenido**
> Convierte este artículo en un email de 150 palabras para mi lista, con 3 asuntos alternativos y un solo CTA.

**Visibilidad en respuestas de IA**
> Reescribe las primeras 100 palabras de esta página para que respondan directamente la pregunta "[pregunta]" y añade un bloque de preguntas frecuentes de 5 ítems.

## 6. Checklist de SEO rápido

- [ ] Cada página tiene un título único (≤ 60 caracteres) y una meta descripción (≤ 155).
- [ ] Un solo H1 con la palabra clave principal.
- [ ] URLs cortas y descriptivas; sitemap enviado a Search Console.
- [ ] Velocidad y Core Web Vitals revisados (PageSpeed Insights).
- [ ] Versión móvil correcta.
- [ ] Enlaces internos entre páginas relacionadas.
- [ ] Imágenes comprimidas y con texto alternativo.
- [ ] Datos estructurados (Organization, LocalBusiness, FAQ, Product) donde apliquen.
- [ ] Ficha de Google Business Profile completa y con datos NAP idénticos al sitio.
- [ ] Seguimiento de conversiones configurado (GA4 + HubSpot).
- [ ] Opcional: un archivo `llms.txt` que resuma tu sitio para asistentes de IA (tema central de este repositorio).

## 7. Buenas prácticas y límites

- **Aprueba siempre** antes de que Claude publique, envíe o gaste dinero.
- **Verifica los datos**: Claude no sustituye a Search Console ni a Analytics; pásale exportaciones reales en lugar de pedirle cifras de tráfico.
- **Aporta tu voz**: comparte 2–3 ejemplos de tu mejor contenido y una guía de tono.
- **Aporta experiencia real** (casos, fotos, precios, opiniones): es lo que distingue tu contenido del genérico.
- **No generes páginas en masa sin revisión**: el contenido de bajo valor daña el posicionamiento.
- No compartas datos de clientes fuera de las herramientas conectadas.

## 8. Recursos del anuncio

- Curso gratuito **"AI Fluency for Small Business"** (con PayPal), disponible bajo demanda.
- Talleres presenciales gratuitos en 10 ciudades de EE. UU. desde el 14 de mayo de 2026 (incluyen un mes de Claude Max).
