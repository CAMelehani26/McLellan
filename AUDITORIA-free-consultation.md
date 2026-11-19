# Auditoría: lenguaje de "Free Consultation" en el sitio de MLG

**BORRADOR. Requiere revisión de un abogado antes de publicar** (reglas 7.1 y 5.3).

**Fecha:** 19 de noviembre de 2026
**Alcance:** las 66 páginas `.html` de la raíz del repo (el sitio). Además, 80 archivos de `duda-snippets/` repiten el mismo texto y hay que cambiarlos también, porque son lo que se pega en Duda.
**Detalle línea por línea:** `AUDITORIA-free-consultation-detalle.csv` (318 menciones: página, línea, tipo y texto).

## El problema

El sitio promete una consulta gratis **sin condiciones** en casi todas las páginas. En la práctica, la consulta inicial gratis es solo para los asuntos que califican. Así, el cliente llega esperando algo que el sitio le "prometió", y si no lo recibe siente que lo engañamos. Además del problema comercial, decir "free consultation" sin condiciones cuando no siempre se da puede considerarse una declaración engañosa bajo la regla 7.1 de las California Rules of Professional Conduct y el Bus. & Prof. Code § 6157.1.

**Mensaje que se busca:** *"Contáctenos para ver si su caso califica para una consulta inicial gratis."*

---

## Prioridad 1: frases que lo prometen de forma explícita y absoluta

Son las que más generan la expectativa de "me la tienen que dar".

| # | Texto actual | Dónde | Texto propuesto |
|---|---|---|---|
| 1 | **"Request Your One Free Initial Consultation."** (H1 del hero) | `contact.html:435` | "Request an Initial Consultation." + subtítulo: "Tell us about your situation and we'll let you know if it qualifies for a free initial consultation." |
| 2 | **"Get My One Free Initial Consultation →"** | `contact.html:438` | "See If I Qualify →" |
| 3 | Badge **"One Free Initial Consultation"** ("What You Can Expect") | `contact.html:485` | "Free Initial Consultation for Qualifying Matters" |
| 4 | Sección "Why us": título **"Free Consultation"** + **"We offer a complimentary initial consultation so you can understand your rights and options before making any commitment."** | 43 páginas (home, todas las de práctica, `blog-non-compete…`). Lista completa en el CSV | Título: "Free Initial Consultation, If You Qualify". Texto: "Reach out and tell us about your situation. If your matter qualifies, your initial consultation is free, so you can understand your options before making any commitment." |
| 5 | **"We offer a complimentary initial consultation so you can find the right plan…"** | `subscription-plans.html:529-530` | "Reach out to see if you qualify for a free initial consultation to find the right plan for your business." |
| 6 | **"Free consultation. No obligation. We respond within one business day."** | Las 6 páginas de abogados + `our-story.html` | "Tell us about your situation and we'll let you know if it qualifies for a free initial consultation. We respond within one business day." |
| 7 | **"We offer a free initial consultation. Many employee-side cases are handled on a contingency fee basis, meaning you pay nothing unless we recover…"** (FAQ visible + schema de Google) | `employment-law.html:57` y `:970` | "Contact us to see if your matter qualifies for a free initial consultation. Some employee-side cases may be handled on a contingency fee basis; fee terms are set out in a written agreement." ⚠️ Ver nota 1 |
| 8 | **"There is no charge for that conversation and no obligation after it."** | `business-litigation.html:1124`, `contract-disputes.html:1053`, `practice-areas.html:949` | "If your matter qualifies, that first conversation is free, and there is no obligation after it." |
| 9 | **"Submitting it starts a free, no-obligation review of your situation"** | `beneficiary-rights.html:872` | "Submitting it lets us review your situation and tell you whether it qualifies for a free initial consultation." |
| 10 | **"at no cost for your initial consultation"** | `blog-non-compete-agreements-california.html:703` | "Contact us to see if you qualify for a free initial consultation." |

## Prioridad 2: FAQs y texto que dan la consulta gratis por hecha

| Texto actual | Dónde | Texto propuesto |
|---|---|---|
| "…we will do that in a **free consultation**." | `breach-of-contract`, `breach-of-fiduciary-duty`, `business-fraud`, `business-litigation`, `business-torts`, `contract-disputes`, `llc-partnership-dissolution`, `membership-and-shareholder-disputes`, `real-estate-litigation`, `trust-probate` | "…we will do that in an **initial consultation**." |
| "…tell you honestly, in a **free consultation**, how we assess yours." | `financial-elder-abuse.html:1014` | "…in an **initial consultation**…" |
| "We will tell you in a **free consultation** whether your employer is covered…" (FAQ visible + schema) | `sexual-harassment.html:116, 790`; `workplace-discrimination.html:102, 752` | "…in an **initial consultation**…" (cambiarlo en los dos lugares de cada página) |
| "Contact us for a **free consultation**." | `appellate.html:621` | "Contact us to see if you qualify for a free initial consultation." |
| "Schedule a **free consultation** today." | `blog.html:685`, `blog-non-compete…:759` | "Contact us to see if you qualify for a free initial consultation." |

## Prioridad 3: botones y menú (en todas las páginas)

Por sí solos no prometen tanto, pero como se repiten en cada página refuerzan la idea de que la consulta es gratis para todos.

| Texto actual | Dónde | Texto propuesto |
|---|---|---|
| **"Free Consultation →"** (botón del menú superior) | Las 65 páginas | "Contact Us →" o "Request a Consultation →" |
| **"Request a Free Consultation →"** | ~45 páginas (CTA intermedio y final) | "Request a Consultation →" o "See If You Qualify →" |
| **"Get My Free Consultation →"** | home, páginas de abogados y landings principales | "See If I Qualify →" |
| **"Get a Free Consultation →"** / **"Free Case Evaluation →"** | `employment-law.html:1070, 939` | "See If You Qualify →" |

## Prioridad 4: lo que se ve en Google (meta descriptions)

Es lo primero que lee la gente en los resultados de búsqueda:

- `index.html:9`, `contact.html:9` y `:13` (og), `business-litigation.html:10`, `breach-of-fiduciary-duty.html:9`, `business-fraud.html:9`, `llc-partnership-dissolution.html:9`, `trust-probate.html:10`, `blog-non-compete…:7`: terminan en **"Free consultation."** o **"Free consult."**
- `breach-of-contract.html:9`, `contract-disputes.html:10`, `real-estate-litigation.html:10`: **"Free consultation, no obligation."**
- `wrongful-termination.html:9`: **"Get a free consultation…"**
- `financial-elder-abuse.html:10`: **"Free case evaluation."**

**Propuesta:** reemplazar por "See if you qualify for a free initial consultation." o quitar la frase. Google tarda semanas en actualizar el snippet después del cambio.

---

## Notas

1. **"You pay nothing unless we recover"** (`employment-law.html`) y el badge **"Contingency Options"** (`contact.html`) tienen el mismo problema que la consulta gratis. Si el cliente puede deber costos, o si no todos los casos son a contingencia, la frase puede ser engañosa (regla 7.1) y no coincidir con el fee agreement (Bus. & Prof. Code § 6147). Un abogado debe confirmar la redacción.
2. **No hay que tocar** `newsletter.html`: ahí "free" se refiere al newsletter, no a la consulta.
3. **Páginas del lado del empleador** (`wrongful-termination-defense`, `retaliation-defense`, `wage-hour-defense`, `paga-notice-response`, `hr-policies-handbooks`, `employment-contracts-severance`, `tier-1-starter-gc-plan`): solo tienen el botón del menú, así que se arreglan solas con el cambio global.
4. **Duda y Lawbrokr:** los botones llevan a `mclellanlawgroup.lawbrokr.com`. Conviene revisar que el formulario de intake de Lawbrokr y el video flotante no prometan también una consulta gratis. Están fuera de este repo y no los revisé.
5. Recomiendo que el formulario de intake incluya una pregunta o un aviso del tipo: "We'll review your submission and let you know if your matter qualifies for a free initial consultation."
