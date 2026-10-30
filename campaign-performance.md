# The Lange Firm — historial de campañas de Mailchimp

Transcrito de capturas del listado de campañas (oct 2026). Todas 2026,
enviadas 06:00 PM salvo indicación. "Engaged" = segmento de no-abridores
reenviado; "Estate" = segmento de estate planning; "Todos" = audiencia completa.

CTOR = clicks / opens. Es la métrica útil: mide qué pasa *después* de abrir,
sin que la deliverability contamine el número.

| Fecha | Campaña | Audiencia | Env. | Opens | Clicks | CTOR |
|---|---|---|---:|---:|---:|---:|
| Oct 20 | Your Title Changed. Your Job Didn't. *(link de texto, sin botón)* | Todos | 1498 | **25.2%** | **0.68%** | 2.7% |
| Oct 06 | Asked to sign today | Todos | 1271 | 17.8% | 0.48% | 2.7% |
| Sep 23 | Your Job Suddenly Feels Like They Want You Gone | Todos | 1281 | 22.1% | 0.32% | 1.4% |
| Sep 01 | Your Job Changed Suddenly. Should You Be Worried? | Todos | 1285 | 8.8% | 0.31% | 3.5% |
| Aug 18 | Employees Often Stay Quiet for This Reason | Todos | 1293 | 9.3% | 0.31% | 3.3% |
| Aug 04 | Is this just part of the job? | Todos | 1301 | 10.5% | 0.23% | 2.2% |
| Jul 24 | Resend: You Spend Too Much Time at Work to Ignore This | Engaged | 426 | 8.3% | 0.47% | 5.7% |
| Jul 21 | You Spend Too Much Time at Work to Ignore This | Todos | 1312 | 8.9% | 0.23% | 2.6% |
| Jul 07 | *(nombre cortado en la captura)* | Todos | 1324 | — | — | — |
| Jun 24 | Nobody Wants to Make Things Worse at Work - all audience | Todos | 1329 | 9.2% | 0.23% | 2.5% |
| Jun 23 | Nobody Wants to Make Things Worse at Work | Engaged | 236 | 6.9% | 0.43% | 6.2% |
| Jun 05 | Resend: Nobody Likes Being the Employee Who Complains | Engaged | 267 | 19.7% | 0.76% | 3.9% |
| Jun 02 | Nobody Likes Being the Employee Who Complains | Todos | 1346 | 23.1% | 0.52% | 2.3% |
| May 19 | A Lot of Employees Get Used to Things They Shouldn't | Todos | 1363 | 16.5% | 0.37% | 2.2% |
| May 06 | Resend: Your boss has more limits than you think | Engaged | 463 | 9.1% | 0.43% | 4.7% |
| May 04 | Your boss has more limits than you think | Todos | 1375 | 10.9% | 0.22% | 2.0% |
| Apr 21 | *(cortado)* | Todos | — | — | — | — |
| Apr 08 | Resend: Something at Work Feels Off? It Might Not Be Legal | Engaged | 351 | 11.7% | 0.00% | 0.0% |
| Apr 06 | Something at Work Feels Off? It Might Not Be Legal | Todos | 1415 | 22.9% | 0.71% | 3.1% |
| Mar 26 | Resend: What Happens If You Don't Have a Will in Texas? | Engaged | 557 | 7.8% | 0.18% | 2.3% |
| Mar 24 | What Happens If You Don't Have a Will in Texas? | Todos | 1429 | 8.7% | 0.21% | 2.4% |
| Mar 10 | 🕊️ Avoiding Probate in Texas: 3 Mistakes Families Make | Todos | 1444 | 10.8% | 0.14% | 1.3% |
| Feb 24 | 🕊️ Who's Really in Charge After Someone Dies in Texas? | Estate | 1273 | 17.7% | 0.24% | 1.4% |
| Feb 10 | 🕊️ How to Settle an Estate in Texas Without Losing Your Mind | Estate | 1283 | 24.6% | 0.40% | 1.6% |
| — | Resend: Maybe It's Not Just You | Engaged | — | 7.7% | 0.24% | 3.1% |
| — | Resend: You Might Be Getting Less Than You Should at Work | Engaged | — | 4.1% | 0.16% | 3.9% |

## CONFIRMADO: la pestaña de Gmail explica las aperturas

Verificado en una casilla real (oct 2026), buscando con `category:promotions`:

| Campaña | Pestaña | Opens |
|---|---|---:|
| Nobody **Likes** Being the Employee Who Complains (2 jun) | Principal | 23.1% |
| Nobody **Wants** to Make Things Worse at Work (24 jun) | Promociones | 9.2% |

Misma lista, construcción de asunto casi idéntica, tres semanas de
diferencia. La única variable que cambió fue la ubicación en bandeja.

**Consecuencia para leer toda la tabla de arriba:** la tasa de apertura
viene funcionando como un proxy de la pestaña, no de la calidad del asunto.
El grupo de ~17-25% son envíos que llegaron a Principal; el de ~9-11%, a
Promociones. Cualquier conclusión sobre redacción sacada de comparar esos
dos grupos está midiendo entrega, no copy.

## Lo que los datos SÍ sostienen (además de lo anterior)

**Las aperturas son bimodales.** Los envíos a la audiencia completa caen en
dos grupos: ~9-11% o ~17-25%. Casi nada en el medio. Una variable continua
(calidad del asunto) produciría una distribución pareja; una binaria, no.
Confirmado arriba: la causa es la ubicación en bandeja.

**La prueba más fuerte de eso:** "Nobody Likes Being the Employee Who
Complains" sacó 23.1% el 2 de junio. "Nobody Wants to Make Things Worse at
Work" sacó 9.2% el 24 de junio. Misma construcción, misma lista, tres
semanas de diferencia, 2.5x de brecha. El copy no explica eso.

**El CTOR es malo y parejo: 1.3%-3.9%.** No depende de la apertura. Dos
campañas con 22-23% de apertura dieron CTOR de 1.4% y 2.3%, por debajo de
otras que abrieron 9%. El cuello de botella está después del open.

**Estate planning abre bien pero convierte peor.** Los tres 🕊️ promedian
CTOR 1.4%, contra ~2.7% del contenido de employment.

**Los reenvíos a "Engaged" tienen el mejor CTOR** (5.7%, 6.2%, 4.7%) pese a
aperturas bajas. Audiencia chica pero la que realmente hace algo.

## Lo que los datos NO sostienen

Con los primeros 8 envíos parecía que "segunda persona + situación concreta"
le ganaba a "pregunta + tercera persona". **El historial completo lo
desmiente.** Dos de los tres mejores opens son justamente una pregunta
("Something at Work Feels Off? It Might Not Be Legal", 22.9%) y una
construcción en tercera persona ("Nobody Likes Being the Employee Who
Complains", 23.1%).

No hay evidencia de que la fórmula del asunto explique las aperturas.

## Prioridad de trabajo

1. **Apagar el tracking de clics.** Reescribe todos los links a un dominio
   de Mailchimp; es la señal de "envío masivo" más fuerte del mail. Costo:
   se pierde la métrica de clics, que con 3-10 clics por campaña no alcanza
   para concluir nada igual.
2. **Autenticar langefirm.com** en Mailchimp (registros CNAME en el DNS).
3. **From name de persona**, no del estudio. Reply-to a una casilla leída.
4. **Sacar el botón** del template: rectángulo navy con texto en mayúsculas
   es el patrón visual de promoción. Reemplazar por link de texto.

NO apagar el tracking de aperturas: es la única métrica que queda para
medir si lo anterior funciona.

## Pendiente de registrar

- Columna de pestaña (Principal/Promociones) en cada envío nuevo.
- Si el tracking de clics estuvo activo en todos los envíos del historial.

## Envío del 20 oct 2026 — Your Title Changed. Your Job Didn't.

Primero sobre la lista de 1500 y primero sin botón (CTA como link de texto).
Cifras a 10 días; al día siguiente marcaba 21.7% / 0.54% y siguió subiendo.

| Métrica | Valor | Lectura |
|---|---|---|
| Opens | **25.2%** | el más alto de todo el historial |
| Clicks | **0.68%** | 2º de todos los envíos a lista completa |
| CTOR | 2.7% | apenas sobre el promedio (~2.4%) |
| Bajas | 1.2% (17) | 2.6x el promedio histórico de 6.6 |
| Rebotes | 1.4% (21) | alto para lista trabajada |
| Abuse reports | 0 | |

Primer envío que queda en el top-2 de aperturas **y** de clics a la vez.

**Las aperturas maduran lentamente.** Hay que leer los reportes a 7-10 días,
no al día siguiente. Al día 1 este marcaba 21.7%; cerró en 25.2%.

**El tracking de clics seguía ENCENDIDO** y aun así fue la mejor apertura
registrada. Eso debilita la hipótesis de que el tracking de clics era lo que
empujaba a Promociones. No conviene tocarlo ahora: hay que repetir esta
configuración una vez más antes de cambiar nada.

**Los clics siguen sin ser medibles.** 0.68% sobre 1498 son ~10 clics. La
diferencia contra 0.48% son 3 clics. No alcanza para concluir que el link de
texto funcionó mejor que el botón.

**Bajas y rebotes siguen apuntando a los 428 de CallRail** (~4.9% de rebote
sobre direcciones nuevas, típico de lista fría).

## Plan de medición

El próximo envío es un **test de replicación**: misma plantilla, mismo CTA de
texto, misma configuración de tracking, mismo día y horario. Solo cambia el
tema. Si vuelve a dar ~25%, la configuración actual es la buena y recién ahí
conviene tocar una variable por vez.
