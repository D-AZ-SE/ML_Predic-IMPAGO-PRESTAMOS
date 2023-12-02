🏦 DETECCION IMPAGO PRESTAMOS

📑 Introducción
En este proyecto, desarrollaremos una comprensión básica de la analítica de riesgos en banca y servicios financieros y entenderemos cómo se utiliza la información para minimizar el riesgo de pérdida de dinero en la concesión de prestamos a clientes. Mediante el Análisis Exploratorio de Datos (EDA) y el Aprendizaje Automático, crearemos unos modelos que determinen el riesgo de impago que poseen dichos clientes y se realizará una comparación entre lo mismos, para evaluar el modelo de mejores resultados.

📝 Comprensión del Negocio
Nos situamos entidad bancaria o empresa especializada en otorgar diversos tipos de préstamos a clientes. Cuando la empresa recibe una solicitud de préstamo, debe tomar una decisión sobre la aprobación del préstamo basada en el perfil del solicitante.

Hay dos tipos de riesgos asociados con la decisión del banco:

Si el solicitante es probable que devuelva el préstamo, no aprobar el préstamo resulta en una pérdida de negocio para la empresa.
Si el solicitante "no" es probable que devuelva el préstamo, es decir, es probable que incumpla, aprobar el préstamo puede resultar en una pérdida financiera para la empresa.
Los datos proporcionados contienen información sobre solicitantes de préstamos anteriores y si han "incumplido" o no. El objetivo es identificar patrones que indiquen si una persona es propensa a incumplir, lo que se puede utilizar para tomar acciones como negar el préstamo, reducir la cantidad del préstamo, prestar (a solicitantes riesgosos) a una tasa de interés más alta, etc.

Cuando una persona solicita un préstamo, existen dos tipos de decisiones que la empresa podría tomar:

1. Préstamo aceptado
Si la empresa aprueba el préstamo, hay 3 escenarios posibles descritos a continuación:

Pagado completamente: El solicitante ha pagado completamente el préstamo (el principal y la tasa de interés).
Actual: El solicitante está en proceso de pagar las cuotas, es decir, el plazo del préstamo aún no ha finalizado. Estos candidatos no se etiquetan como "incumplidos".
Cobrado como pérdida: El solicitante no ha pagado las cuotas a tiempo durante un largo período, es decir, ha incumplido el préstamo.
2. Préstamo rechazado
La empresa ha rechazado el préstamo (porque el candidato no cumple con sus requisitos, etc.). Dado que el préstamo fue rechazado, no hay historial de transacciones de esos solicitantes con la empresa y, por lo tanto, estos datos no están disponibles en la empresa, ni consecuentemente, en su conjunto de datos.

🎯 Objetivos del Negocio
Otorgar préstamos a solicitantes "con riesgo" es la fuente más grande de pérdida financiera (llamada "pérdida de crédito"). La pérdida de crédito es la cantidad de dinero perdida por el prestamista, como consecuencia del incumplimiento de pago del prestatario. En este caso, los clientes etiquetados como "cobrados como pérdida" son los "incumplidos".

Si uno puede identificar a estos solicitantes de préstamos con riesgo elevado, entonces se pueden reducir tales préstamos, reduciendo así la cantidad de pérdida de crédito. La identificación de tales solicitantes utilizando EDA y el aprendizaje automático es el objetivo de este estudio.

En otras palabras, la empresa quiere comprender los factores determinantes (o variables clave) detrás del incumplimiento del préstamo, es decir, las variables que son indicadores sólidos de incumplimiento, para poder utilizar este conocimiento para fijar criterios con su cartera de clientes y su evaluación de riesgos.
