




Universidad Peruana de Ciencias Aplicadas 
Ingeniería de Software - noveno ciclo 
Calidad Y Mejora De Procesos Software
Sección: 3330

Docente: Alvaro Antonio Aures Garcia

Trabajo Final


Relación de integrantes del grupo:
Diego Ulises Soto Quispe - u202214477
Djalma Santos Dioses Molina - u201921405
Javier Martin Sebastian Tasayco - u20211e429
Brenda Lucía Gamio Upiachihua - u202120344
Saúl Enrique Mendoza Barco - u20211c677




01 de Diciembre 2025 
Registro de versiones del informe 
Versión 
Fecha
Autor
Descripción de modificación 
TP
05-10-2025
Todo los integrantes 
Se desarrolló el capítulo 1 y 2 respectivamente en base a las 3 isos indicadas 
TF
30-10-2025
Todo los integrantes 
Se actualizaron los procesos y se desarrolló el capítulos 3, 4, 5 y 6














Resumen Ejecutivo
El trabajo desarrolla una propuesta integral de modelamiento de procesos de desarrollo de software basada en los estándares internacionales ISO/IEC 12207:2017, ISO/IEC 27001:2022, ISO/IEC 27002:2022 y el modelo CMMI v2.0. El análisis se centra en la empresa ficticia InnovaTech Solutions, una organización FinTech enfocada en soluciones tecnológicas para el sector financiero, con el objetivo de mejorar la calidad, seguridad y eficiencia de sus procesos de desarrollo.
El estudio examina la relación entre las normas ISO y el modelo CMMI, identificando su complementariedad en la gestión de calidad, la seguridad de la información y la madurez organizacional. Se definen criterios técnicos y estratégicos para seleccionar los procesos más relevantes del área de TI, considerando su impacto en el ciclo de vida del software y en la mitigación de riesgos.
A partir de ello, se propone un mapa de procesos compuesto por diez procesos clave que abarcan desde la gestión de requisitos hasta la atención de incidentes de seguridad. Cada proceso se describe y modela mediante notación BPMN, especificando su propósito, entradas, salidas, roles y evidencias auditables alineadas a las prácticas de los estándares internacionales.
El análisis demuestra cómo la integración de las normas ISO con el modelo CMMI potencia la madurez de los procesos, fortalece la gobernanza tecnológica y consolida una cultura de mejora continua dentro del área de TI, contribuyendo al desarrollo de software más seguro, trazable y confiable en entornos empresariales de alta exigencia como el financiero.






Tabla de contenidos 
Registro de versiones del informe	2
Resumen Ejecutivo	3
Tabla de contenidos	4
Student Outcome	9
CAPÍTULO 1: MARCO TEÓRICO	14
1.1 Relación entre el modelo CMMI y la norma ISO/IEC/IEEE 12207:2017	14
1.1.1 Descripción de la norma ISO 12207:2017	14
1.1.2 Descripción del modelo CMMI v2.0	15
1.1.3 Puntos de convergencia entre CMMI e ISO 12207	16
1.1.4 Complementariedad de ambos marcos	18
1.2 Relación entre el modelo CMMI y la norma ISO/IEC 27001:2022	19
1.2.1 Descripción de la norma ISO 27001:2022	19
1.2.2 Integración de CMMI con gestión de seguridad	19
1.2.3 Beneficios de la complementariedad	21
CAPÍTULO 2: MODELAMIENTO DE PROCESOS DE DESARROLLO DE SOFTWARE (ISO 12207:2017, ISO 27001:2022, ISO 27002:2022)	23
2.1 Contexto del área de TI (Empresa ficticia)	23
2.1.1 Descripción de la empresa	23
2.1.2 Misión y visión del área de TI	23
2.1.3 Estructura organizacional del área de TI	24
2.1.4 Servicios que brinda el área de TI	25
Desarrollo de aplicaciones	25
Mantenimiento de sistemas	25
Soporte a clientes externos	25
Soporte a áreas internas	25
2.2 Criterios de selección de procesos	25
2.2.1 Criterio 1: Relevancia para el área de TI	25
2.2.2 Criterio 2: Cobertura del ciclo de vida	26
2.2.3 Criterio 3: Cumplimiento normativo	26
2.2.4 Criterio 4: Gestión de riesgos y seguridad	26
2.3 Mapa de procesos propuesto para el área de TI	27
2.3.1 Representación gráfica del mapa de procesos	27
2.3.2 Descripción general de la arquitectura	28
2.3.3 Justificación de los 10 procesos seleccionados	28
1. Proceso 1: Gestión de Requisitos	28
2. Proceso 2: Diseño y Arquitectura	29
3. Proceso 3: Desarrollo e Implementación	29
4. Proceso 4: Verificación, Validación y Transición	30
5. Proceso 5: Operación y Mantenimiento	30
6. Proceso 6: Planificación y Control de Proyectos	30
7. Proceso 7: Gestión de Configuración	31
8. Proceso 8: Gestión de Riesgos	31
9. Proceso 9: Gestión de Seguridad de la Información	32
10. Proceso 10: Gestión de Incidentes de Seguridad	32
2.3.4 Interrelación entre procesos	32
2.4 Procesos modelados con notación BPMN	34
2.4.1 PROCESO 1: GESTIÓN DE REQUISITOS	34
2.4.1.1 Descripción del proceso	34
2.4.1.2 Propósito del proceso	34
2.4.1.3 Entradas y salidas	34
Entradas	34
Salidas	35
2.4.1.4 Roles	35
2.4.1.5 Modelo del proceso en notación BPMN	36
2.4.1.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	36
Integración con ISO 27001:2022	36
Controles ISO 27002:2022	37
Evidencia auditable	37
2.4.2 PROCESO 2: DISEÑO Y ARQUITECTURA	38
2.4.2.1 Descripción del proceso	38
2.4.2.2 Propósito del proceso	38
2.4.2.3 Entradas y salidas	38
Entradas	38
Salidas	38
2.4.2.4 Roles	39
2.4.2.5 Modelo del proceso en notación BPMN	39
2.4.2.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	39
Integración con ISO 27001:2022	40
Controles ISO 27002:2022	40
2.4.3 PROCESO 3: DESARROLLO E IMPLEMENTACIÓN	40
2.4.3.1 Descripción del proceso	40
2.4.3.2 Propósito del proceso	41
2.4.3.3 Entradas y salidas	41
Entradas	41
Salidas	41
2.4.3.4 Roles	41
2.4.3.5 Modelo del proceso en notación BPMN	42
2.4.3.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	42
Integración con ISO 27001:2022	42
Controles ISO 27002:2022	43
2.4.4 PROCESO 4: VERIFICACIÓN, VALIDACIÓN Y TRANSICIÓN	43
2.4.4.1 Descripción del proceso	43
2.4.4.2 Propósito del proceso	43
2.4.4.3 Entradas y salidas	44
Entradas	44
Salidas	44
2.4.4.4 Roles	44
2.4.4.5 Modelo del proceso en notación BPMN	45
2.4.4.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	45
2.4.5 PROCESO 5: OPERACIÓN Y MANTENIMIENTO	46
2.4.5.1 Descripción del proceso	46
2.4.5.2 Propósito del proceso	46
2.4.5.3 Entradas y salidas	46
Entradas	46
Salidas	47
2.4.5.4 Roles	47
2.4.5.5 Modelo del proceso en notación BPMN	48
2.4.5.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	48
2.4.6 PROCESO 6: PLANIFICACIÓN Y CONTROL DE PROYECTOS	49
2.4.6.1 Descripción del proceso	49
2.4.6.2 Propósito del proceso	49
2.4.6.3 Entradas y salidas	50
Entradas	50
Salidas	50
2.4.6.4 Roles	50
2.4.6.5 Modelo del proceso en notación BPMN	52
2.4.6.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	52
2.4.7 PROCESO 7: GESTIÓN DE CONFIGURACIÓN	53
2.4.7.1 Descripción del proceso	53
2.4.7.2 Propósito del proceso	53
2.4.7.3 Entradas y salidas	54
Entradas	54
Salidas	54
2.4.7.4 Roles	54
2.4.7.5 Modelo del proceso en notación BPMN	55
2.4.7.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	55
2.4.8 PROCESO 8: GESTIÓN DE RIESGOS	57
2.4.8.1 Descripción del proceso	57
2.4.8.2 Propósito del proceso	58
2.4.8.3 Entradas y salidas	58
Entradas	58
Salidas	59
2.4.8.4 Roles	59
2.4.8.5 Modelo del proceso en notación BPMN	61
2.4.8.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	61
2.4.9 PROCESO 9: GESTIÓN DE SEGURIDAD DE LA INFORMACIÓN	62
2.4.9.1 Descripción del proceso	62
2.4.9.2 Propósito del proceso	63
2.4.9.3 Entradas y salidas	63
Entradas	63
Salidas	63
2.4.9.4 Roles	64
2.4.9.5 Modelo del proceso en notación BPMN	65
2.4.9.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	65
2.4.10 PROCESO 10: GESTIÓN DE INCIDENTES DE SEGURIDAD	66
2.4.10.1 Descripción del proceso	66
2.4.10.2 Propósito del proceso	66
2.4.10.3 Entradas y salidas	66
Entradas	66
Salidas	67
2.4.10.4 Roles	67
2.4.10.5 Modelo del proceso en notación BPMN	67
2.4.10.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022	68
CAPÍTULO 3: MODELAMIENTO DE PROCESOS DE DESARROLLO DE SOFTWARE INCLUYENDO MÉTRICAS, AUTOMATIZACIÓN Y PRÁCTICAS DEL MODELO CMMI	69
3.1 PROCESO 1: GESTIÓN DE REQUISITOS	69
3.1.1 Modelo actualizado del proceso en notación BPMN	69
3.1.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	71
3.2 PROCESO 2: DISEÑO Y ARQUITECTURA	76
3.2.1 Modelo actualizado del proceso en notación BPMN	76
3.2.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	77
3.3 PROCESO 3: DESARROLLO E IMPLEMENTACIÓN	78
3.3.1 Modelo actualizado del proceso en notación BPMN	78
3.3.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	79
3.3.3 Descripción formal escrita del proceso	80
3.3.4 Métricas para evaluar el desempeño del proceso	85
3.3.5 Herramientas de automatización	87
3.4 PROCESO 4: VERIFICACIÓN, VALIDACIÓN Y TRANSICIÓN	88
3.4.1 Modelo actualizado del proceso en notación BPMN	88
3.4.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	89
3.5 PROCESO 5: OPERACIÓN Y MANTENIMIENTO	90
3.5.1 Modelo actualizado del proceso en notación BPMN	90
3.5.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	91
3.6 PROCESO 6: PLANIFICACIÓN Y CONTROL DE PROYECTOS	91
3.6.1 Modelo actualizado del proceso en notación BPMN	91
3.6.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	92
3.6.3 Descripción formal escrita del proceso	94
3.6.4 Métricas para evaluar el desempeño del proceso	100
3.6.5 Herramientas de automatización	103
3.7 PROCESO 7: GESTIÓN DE CONFIGURACIÓN	109
3.7.1 Modelo actualizado del proceso en notación BPMN	109
3.7.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	111
3.8 PROCESO 8: GESTIÓN DE RIESGOS	115
3.8.1 Modelo actualizado del proceso en notación BPMN	115
3.8.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	116
3.9 PROCESO 9: GESTIÓN DE SEGURIDAD DE LA INFORMACIÓN	121
3.9.1 Modelo actualizado del proceso en notación BPMN	121
3.9.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	122
3.10 PROCESO 10: GESTIÓN DE INCIDENTES DE SEGURIDAD	124
3.10.1 Modelo actualizado del proceso en notación BPMN	124
3.10.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas	125
CAPÍTULO 4: PRESENTACIÓN DE LA ORGANIZACIÓN DE LOS PROCESOS A EVALUAR	127
4.1 Actualización de Procesos	127
4.1.1 Descripción de la Organización	127
4.1.2 Descripción del Negocio	128
4.1.3 Estructura del Área de TI	128
4.2 Metodología de Ciclo de Vida de Desarrollo y Mantenimiento de Software	129
4.2.1 Modelo de Ciclo de Vida Adoptado	129
4.2.2 Fases del Ciclo de Vida	130
4.3 Mapa de Procesos de la Organización	132
4.3.1 Representación Gráfica del Mapa de Procesos	132
4.3.2 Descripción de la Arquitectura del Mapa de Procesos	133
4.3.3 Detalle de los 10 Procesos Principales	134
CAPÍTULO 5: ANÁLISIS DE BRECHAS CMMI DE LOS PROCESOS DE LA ORGANIZACIÓN SELECCIONADA	135
5.1 Evaluación del Análisis de Brechas	135
5.2 Oportunidades de Mejora	140
5.3 Fortalezas identificadas en la evaluación de los procesos	143
5.3.1 Fortalezas Generales	143
5.3.2 Fortalezas por Proceso	144
CAPÍTULO 6: IMPLEMENTACIÓN DE MEJORAS DE LOS PROCESOS DE LA ORGANIZACIÓN SELECCIONADA	147
6.1 Planificación de la implementación de mejoras	147
6.2 Sustento de las mejoras propuestas	151
CONCLUSIONES - TP	155
CONCLUSIONES - TF	157
RECOMENDACIONES - TP	159
RECOMENDACIONES - TF	161
GLOSARIO	163
BIBLIOGRAFÍA	167
ANEXOS	169
Anexo A: Tablas de mapeo entre normas ISO	169
Student Outcome 
ABET - EAC - Student Outcome 6: La capacidad de desarrollar y llevar a cabo la experimentación adecuada, analizar e interpretar datos, y usar el juicio de ingeniería para sacar conclusiones.

Criterio específico 
Acciones realizadas 
Conclusiones 
Desarrollo de experimentos 
TP

Diego Ulises Soto Quispe: Diseñó el protocolo experimental de aplicación de las normas ISO 12207, 27001 y 27002 al modelamiento BPMN, definiendo variables, criterios de éxito y métodos de validación. Elaboró el mapa de procesos del área TI y coordinó la integración de los controles de seguridad y calidad dentro del modelo.


Djalma Santos Dioses Molina: Planteó el diseño metodológico del experimento comparativo entre el modelo base y el modelo mejorado con prácticas CMMI e ISO 12207, definiendo las métricas de desempeño y los indicadores de mejora continua.

Javier Martin Sebastian Tasayco: Ejecutó la prueba piloto de los procesos de Verificación, Validación y Transición, recolectando datos de desempeño, incidencias y trazabilidad para el análisis estadístico posterior.
Brenda Lucia Gamio Upiachihua: Documentó la empresa caso (InnovaTech Solutions) y sus flujos experimentales, garantizando la coherencia del contexto operativo y la correcta definición de variables y condiciones de control.

Saul Enrique Mendoza Barco: Integró en el experimento los controles de gestión de riesgos y seguridad del SGSI, definiendo escenarios de prueba para medir la efectividad de las políticas basadas en ISO 27002.


TF

Diego Ulises Soto Quispe:
Diseñó el entorno experimental para evaluar los procesos de la organización, definiendo las condiciones, relaciones y flujos necesarios para validar calidad, seguridad y trazabilidad dentro del ciclo de vida del software.

Djalma Santos Dioses Molina:
Ejecutó un segundo experimento sobre otro proceso fundamental, definiendo métricas comparativas y automatizaciones que permitieron analizar su rendimiento y consistencia.

Javier Martin Sebastian Tasayco:
Diseñó el experimento de implementación de mejoras, planificando intervenciones medibles y sustentando su impacto esperado en la evolución de los procesos.

Brenda Lucia Gamio Upiachihua:
Desarrolló un experimento aplicado a un proceso clave, estableciendo indicadores de desempeño y configurando herramientas automáticas para medir su eficacia y comportamiento operativo.


Saul Enrique Mendoza Barco:
Realizó el experimento de diagnóstico de madurez, identificando brechas y validando cómo los procesos responden frente a los criterios del modelo CMMI.
TP
El grupo logró planificar y ejecutar un experimento controlado que permitió validar la integración de estándares internacionales en un entorno simulado de desarrollo de software. Se demostró la capacidad de aplicar metodologías de ingeniería, identificar variables críticas y obtener resultados cuantificables sobre la mejora de la calidad y la seguridad de los procesos.


TF
El trabajo desarrollado permitió validar experimentalmente la madurez y desempeño de los procesos clave de la organización, combinando análisis estructural, medición operativa y aplicación de mejoras alineadas a estándares internacionales. La participación coordinada de todos hizo posible evaluar distintos procesos desde perspectivas complementarias, identificar brechas reales y proponer intervenciones medibles que fortalecieran la calidad, seguridad y consistencia del ciclo de vida del software. En conjunto, los experimentos ejecutados demostraron la viabilidad y el impacto positivo de aplicar un enfoque sistemático basado en ISO y CMMI para optimizar la gestión tecnológica.
Analiza, interpreta datos y concluye sobre el resultado del experimento. 
TP

Diego Ulises Soto Quispe: Analizó los resultados obtenidos del experimento, verificando la consistencia de los datos y utilizando el juicio de ingeniería para determinar las mejoras efectivas en trazabilidad y cumplimiento normativo.

Djalma Santos Dioses Molina: Interpretó las métricas de desempeño y los indicadores de madurez de procesos, estableciendo relaciones causa-efecto entre los controles aplicados y la reducción de incidencias.

Javier Martin Sebastian Tasayco: Procesó la información recolectada en las pruebas de verificación y validación, comparando resultados pre y post-intervención para determinar la eficacia de las prácticas implementadas.

Brenda Lucia Gamio Upiachihua: Sistematizó la información obtenida, elaboró gráficas de resultados y redactó conclusiones basadas en evidencia, asegurando la validez y claridad de los hallazgos.

Saul Enrique Mendoza Barco: Evaluó el cumplimiento de los controles de seguridad frente a los datos experimentales, determinando el impacto positivo de las prácticas del SGSI en la reducción de riesgos tecnológicos.


TF
Diego Ulises Soto Quispe:
Analizó la estructura general del experimento organizacional, interpretando cómo los flujos y relaciones entre procesos impactaban en la eficiencia y seguridad. Sus conclusiones permitieron entender el comportamiento integral del modelo y la coherencia entre las prácticas aplicadas.

Djalma Santos Dioses Molina:
Interpretó los resultados del segundo proceso analizado, comparando métricas antes y después de las intervenciones. Sus conclusiones evidenciaron el impacto real de las prácticas implementadas y la consistencia operativa del proceso.

Javier Martin Sebastian Tasayco:
Interpretó los resultados de las mejoras proyectadas, evaluando su impacto esperado mediante análisis de coherencia, viabilidad y contribución al desempeño. Concluyó sobre la efectividad de las intervenciones propuestas para elevar la madurez organizacional.

Brenda Lucia Gamio Upiachihua:
Evaluó los datos obtenidos del proceso estudiado, interpretando sus métricas de rendimiento y el efecto de las automatizaciones aplicadas. Concluyó sobre la estabilidad, eficiencia y posibles mejoras derivadas de los resultados experimentales.

Saul Enrique Mendoza Barco:
Analizó los datos de brechas y niveles de madurez, interpretando tendencias y alineamientos con CMMI. Sus conclusiones permitieron identificar prioridades de mejora y validar si los procesos responden adecuadamente a los criterios evaluados.
TP 
El grupo demostró capacidad analítica y uso del juicio de ingeniería al interpretar los resultados del experimento. Se identificaron patrones de mejora y se tomaron decisiones basadas en evidencia, consolidando un enfoque de madurez, trazabilidad y mejora continua en la gestión de procesos de software.


TF

El análisis conjunto de los datos permitió comprender de manera integral cómo los procesos responden a la aplicación de prácticas estandarizadas y elementos de mejora. La interpretación realizada por cada integrante del equipo aportó una visión complementaria que facilitó identificar patrones, validar hipótesis y concluir sobre la eficacia real de las intervenciones. En conjunto, los resultados demostraron que el enfoque experimental aplicado permite evaluar con claridad el desempeño, madurez y potencial de optimización de los procesos dentro de la organización.


CAPÍTULO 1: MARCO TEÓRICO
1.1 Relación entre el modelo CMMI y la norma ISO/IEC/IEEE 12207:2017
    1.1.1 Descripción de la norma ISO 12207:2017
La norma ISO/IEC/IEEE 12207:2017 "Systems and software engineering - Software life cycle processes" es el estándar internacional que establece un marco de trabajo exhaustivo para los procesos del ciclo de vida del software. Su propósito fundamental es proporcionar un lenguaje y una estructura comunes y estandarizados que permitan a las organizaciones y a sus stakeholders adquirir, desarrollar, operar y mantener software de manera coherente y disciplinada.
Este estándar puede ser entendido como un mapa completo que describe todos los procesos relevantes en la ingeniería de software. Se caracteriza por ser no prescriptivo; es decir, define el "qué" se debe hacer (los procesos a implementar y sus resultados esperados), sin imponer el "cómo" se deben ejecutar (la metodología, herramientas o modelo de ciclo de vida específico). Esta flexibilidad permite su adaptación a organizaciones de cualquier tamaño y modelo de desarrollo (desde cascada hasta ágil).
Estructura de procesos de ISO/IEC/IEEE 12207:2017:
La norma organiza sus procesos en cuatro categorías principales:
1. Procesos de Acuerdo: Gestionan la relación contractual entre cliente y proveedor, incluyendo Adquisición y Suministro.
2. Procesos Organizacionales Habilitadores del Proyecto: Establecen la capacidad organizacional necesaria para ejecutar proyectos. Incluyen: Gestión del Modelo de Ciclo de Vida, Gestión de la Infraestructura, Gestión del Portafolio, Gestión de Recursos Humanos, Gestión de la Calidad y Gestión del Conocimiento.
3. Procesos Técnicos de Gestión del Proyecto: Se enfocan en la gestión específica de proyectos técnicos: Planificación del Proyecto, Evaluación del Proyecto, Control del Proyecto, Gestión de Decisiones, Gestión de Riesgos, Gestión de la Configuración, Gestión de la Información, Medición, Aseguramiento de la Calidad y Revisión.
4. Procesos Técnicos: Cubren las actividades técnicas directas del ciclo de vida: Definición de Necesidades de Stakeholders, Análisis de Requisitos del Sistema, Definición de Arquitectura del Sistema, Análisis de Requisitos, Diseño, Implementación, Integración, Verificación, Transición, Validación, Operación, Mantenimiento y Disposición.
La edición de 2017 se armonizó completamente con la norma ISO/IEC/IEEE 15288 de ingeniería de sistemas, lo que permite una integración fluida entre el desarrollo de software y sistemas complejos.
    1.1.2 Descripción del modelo CMMI v2.0
El Modelo de Madurez de Capacidades Integrado (CMMI) v2.0 es un marco de trabajo para la mejora de procesos que guía a las organizaciones en la optimización de sus operaciones para elevar la calidad, la eficiencia y el rendimiento general. Desarrollado originalmente por el Software Engineering Institute (SEI) y ahora gestionado por ISACA, es el referente global para la madurez organizacional.
A diferencia del enfoque de la ISO 12207 en la definición de un conjunto de procesos, CMMI se enfoca en evaluar "qué tan bien" una organización implementa dichos procesos. Proporciona un camino evolutivo a través de Niveles de Madurez, que miden el grado de institucionalización y optimización de los procesos:
Nivel 1 (Inicial): Los procesos son impredecibles, poco controlados y reactivos.
Nivel 2 (Gestionado): Los procesos se gestionan a nivel de proyecto, son planificados y monitoreados.
Nivel 3 (Definido): Los procesos están estandarizados a nivel de toda la organización, con guías de adaptación y un enfoque en la consistencia.
Nivel 4 (Gestionado Cuantitativamente): La organización controla sus procesos utilizando técnicas estadísticas y análisis de datos.
Nivel 5 (En Optimización): La organización se enfoca en la mejora continua e incremental de sus procesos, buscando la innovación y la optimización proactiva.
La versión 2.0 introdujo una estructura más flexible, organizada en Áreas de Capacidad (como Hacer, Gestionar y Mejorar) que contienen Áreas de Práctica (Practice Areas - PAs). Esto permite a las organizaciones priorizar las mejoras que aportan mayor valor a sus objetivos de negocio.

    1.1.3 Puntos de convergencia entre CMMI e ISO 12207
Ambos marcos, aunque con propósitos distintos, comparten el objetivo de promover una ingeniería de software disciplinada y orientada a la calidad. Sus principales puntos de convergencia son:
Cobertura de Procesos: Existe una correspondencia significativa y un mapeo claro entre los procesos de la ISO 12207 y las Áreas de Práctica de CMMI. Por ejemplo, el "Proceso de Análisis de Requisitos del Software" de ISO 12207 encuentra su contraparte en el Área de Práctica "Requirements Development and Management (RDM)" de CMMI. De igual forma, el "Proceso de Aseguramiento de la Calidad" de la norma se alinea con "Process Quality Assurance (PQA)" en el modelo.
Tabla 1
Mapeo entre ISO/IEC/IEEE 12207:2017 y CMMI v2.0
Proceso ISO 12207:2017
Área de Práctica CMMI v2.0
Convergencia
Análisis de Requisitos
Requirements Development and Management (RDM)
Captura, análisis y gestión de requisitos
Diseño / Arquitectura
Technical Solution (TS)
Desarrollo de soluciones técnicas
Implementación
Technical Solution (TS)
Codificación según diseño
Integración
Product Integration (PI)
Ensamblaje de componentes
Verificación
Verification and Validation (VV)
Asegurar cumplimiento de requisitos
Validación
Verification and Validation (VV)
Confirmar satisfacción de necesidades
Planificación del Proyecto
Planning (PLAN)
Establecer planes de proyecto
Control del Proyecto
Monitoring and Controlling (MC)
Seguimiento y gestión de desviaciones
Gestión de Configuración
Configuration Management (CM)
Control de versiones y cambios
Gestión de Riesgos
Risk and Opportunity Management (RSK)
Identificación y mitigación de riesgos
Aseguramiento de Calidad
Process Quality Assurance (PQA)
Garantizar adherencia a procesos
Medición
Measurement and Analysis (MA)
Recopilación y análisis de métricas


Énfasis en la Institucionalización: Aunque CMMI es más explícito en este punto a través de sus prácticas genéricas, ambos marcos promueven la idea de que los procesos deben ser formalmente establecidos, documentados, dotados de recursos, monitoreados y controlados, en lugar de depender de esfuerzos heroicos individuales.
Foco en la Gestión: Tanto CMMI como ISO 12207 reconocen la importancia fundamental de las actividades de gestión, como la gestión de riesgos, la gestión de la configuración y la medición, como pilares para el éxito de los proyectos.
    1.1.4 Complementariedad de ambos marcos
La relación más efectiva entre CMMI e ISO 12207 no es de exclusión, sino de sinergia y enriquecimiento mutuo. Su complementariedad puede ilustrarse con la siguiente analogía:
La ISO 12207 proporciona el esqueleto (una estructura de procesos completa y estandarizada), mientras que CMMI añade los músculos y el sistema nervioso (la capacidad, madurez y mecanismos de mejora) para que esa estructura funcione con un alto nivel de rendimiento.
En un escenario práctico, una organización puede utilizar la ISO 12207 como base para definir su conjunto de procesos del ciclo de vida. Esto le asegura una cobertura completa y una arquitectura de procesos reconocida internacionalmente. Posteriormente, puede emplear CMMI como el modelo de mejora para evaluar y elevar la madurez de dichos procesos. Mediante una evaluación CMMI (como un Benchmark Appraisal), la organización puede identificar las debilidades en la ejecución de los procesos definidos por la ISO y utilizar las prácticas específicas de CMMI como una guía prescriptiva para fortalecerlos, estableciendo un camino claro desde un estado meramente definido hacia uno gestionado cuantitativamente y en optimización continua.
1.2 Relación entre el modelo CMMI y la norma ISO/IEC 27001:2022
    1.2.1 Descripción de la norma ISO 27001:2022
La norma ISO/IEC 27001:2022 es el estándar de referencia internacional para la gestión de la seguridad de la información. Su objetivo principal es la implementación de un Sistema de Gestión de Seguridad de la Información (SGSI), un marco de gestión sistemático y basado en el análisis de riesgos para proteger la confidencialidad, integridad y disponibilidad de la información.
El enfoque de la norma no es simplemente la aplicación de una lista de controles técnicos, sino la adopción del ciclo de mejora continua Planificar-Hacer-Verificar-Actuar (PHVA o PDCA), que implica:
Planificar (Plan): Establecer las políticas, objetivos y procesos del SGSI en función de la evaluación de riesgos de la organización.
Hacer (Do): Implementar y operar los procesos y controles del SGSI.
Verificar (Check): Monitorear y revisar el desempeño del SGSI, comparándolo con los objetivos y políticas.
Actuar (Act): Tomar acciones para la mejora continua del SGSI.
El Anexo A de la norma proporciona un conjunto de objetivos de control y controles de referencia (alineados con la guía ISO 27002) que sirven como catálogo para el tratamiento de riesgos. La versión 2022 actualizó estos controles, introduciendo nuevos relacionados con inteligencia de amenazas, seguridad en la nube y prevención de fuga de datos. Un documento clave del SGSI es la Declaración de Aplicabilidad (SoA), donde la organización justifica qué controles del Anexo A ha implementado y cuáles no, y por qué.
    1.2.2 Integración de CMMI con gestión de seguridad
La integración de la madurez de procesos de CMMI con la gestión de seguridad de ISO 27001 es fundamental para el desarrollo de software robusto y seguro por diseño. Mientras CMMI asegura que los procesos de desarrollo son eficientes y de alta calidad, ISO 27001 garantiza que la seguridad es un componente integral y gestionado de dichos procesos. La meta de esta integración es lograr un Ciclo de Vida de Desarrollo de Software Seguro (Secure SDLC).
Tabla 2
 Mapeo entre ISO/IEC 27001:2022 y CMMI v2.0
Control ISO 27001:2022
Área de Práctica CMMI v2.0
Integración
5.1 Políticas de seguridad
Governance (GOV)
Políticas organizacionales con seguridad
5.27 Evaluación de riesgos de seguridad
Risk and Opportunity Management (RSK)
Riesgos de seguridad en gestión de riesgos
8.8 Gestión de vulnerabilidades
Risk and Opportunity Management (RSK)
Mitigación de vulnerabilidades técnicas
8.25 Ciclo de vida de desarrollo seguro
RDM / Technical Solution (TS)
Requisitos de seguridad desde análisis
8.28 Codificación segura
TS / Verification and Validation (VV)
Estándares de código seguro y revisiones
8.32 Gestión de cambios
Configuration Management (CM)
Control de cambios con impacto de seguridad
5.24 Gestión de incidentes de seguridad
Process Management (PCM)
Procesos formales de respuesta a incidentes
5.37 Procedimientos documentados
Process Management (PCM)
Documentación con consideraciones de seguridad

La integración se materializa al incorporar los requisitos y controles de seguridad del SGSI dentro de las Áreas de Práctica de CMMI. Por ejemplo:
El Área de Práctica de Gestión de Requisitos (RDM) de CMMI se expande para incluir la definición, análisis y gestión de requisitos de seguridad como un componente no funcional crítico.
El Área de Práctica de Gestión de Riesgos y Oportunidades (RSK) de CMMI se enriquece al considerar no sólo los riesgos del proyecto (costo, plazo), sino también los riesgos de seguridad de la información identificados mediante el proceso de la ISO 27001.
El Área de Práctica Process Quality Assurance (PQA) puede ser utilizada para auditar y verificar que las actividades y controles de seguridad definidos en el SGSI se estén aplicando correctamente durante el desarrollo.
Supplier Agreement Management (SAM) incorpora cláusulas y requisitos de seguridad en los acuerdos con proveedores, extendiendo la protección a toda la cadena de suministro.
    1.2.3 Beneficios de la complementariedad
La combinación de CMMI e ISO 27001 produce beneficios estratégicos y operativos que fortalecen la posición de una organización en el mercado y su resiliencia.
Seguridad por Diseño (Security by Design): Se transita de un modelo reactivo a un modelo proactivo. Se adopta el principio de "desplazamiento a la izquierda" (Shift Left), donde las actividades de seguridad (como el modelado de amenazas o el análisis de código estático) se mueven a las fases tempranas del ciclo de vida. Los procesos maduros de CMMI aseguran que esta integración sea consistente y repetible.
Reducción de Riesgos y Costos: La identificación temprana de vulnerabilidades reduce significativamente el costo de remediación. Corregir una falla de seguridad en la fase de diseño es exponencialmente más barato que hacerlo en un sistema en producción. Esto minimiza el riesgo de incidentes de seguridad, que conllevan costos asociados a brechas de datos, sanciones regulatorias (como GDPR) y daños a la imagen corporativa.
Ventaja Competitiva: La capacidad de demostrar un alto nivel de madurez de procesos (CMMI) junto con una gestión certificada de la seguridad (ISO 27001) genera un alto grado de confianza en los clientes. Se convierte en un diferenciador clave para competir en mercados que manejan información sensible (financiero, salud, gobierno).
Eficiencia Operativa y Cultura DevSecOps: La integración elimina fricciones entre los equipos de Desarrollo, Seguridad y Operaciones, fomentando una cultura colaborativa (DevSecOps). La seguridad deja de ser vista como un cuello de botella y se convierte en una responsabilidad compartida, optimizando los flujos de trabajo y permitiendo entregas de valor más rápidas y seguras.













CAPÍTULO 2: MODELAMIENTO DE PROCESOS DE DESARROLLO DE SOFTWARE (ISO 12207:2017, ISO 27001:2022, ISO 27002:2022)
2.1 Contexto del área de TI (Empresa ficticia)
Para poder proponer un modelo de procesos coherente y alineado a objetivos de negocio, es fundamental establecer el contexto organizacional en el cual operará. A continuación, se describe la empresa ficticia que servirá como base para el presente estudio.
    2.1.1 Descripción de la empresa
InnovaTech Solutions es una empresa de tecnología financiera (FinTech) de tamaño mediano, con sede en Lima, Perú, y fundada en 2015. La compañía se especializa en el desarrollo de soluciones de software para el sector financiero, ofreciendo productos SaaS (Software as a Service) a bancos, cajas de ahorro y empresas de gestión de patrimonios en América Latina. Su principal propuesta de valor es la optimización de procesos de crédito y la gestión de portafolios de inversión a través de plataformas seguras y eficientes.
Debido a la naturaleza de su negocio, InnovaTech Solutions maneja un alto volumen de información financiera y personal de carácter sensible y confidencial, por lo que la seguridad de la información, la continuidad del negocio y el cumplimiento normativo (leyes de protección de datos, regulaciones financieras) son pilares estratégicos de su operación.
    2.1.2 Misión y visión del área de TI
El área de Tecnología de la Información (TI) es el núcleo operativo y de innovación de la empresa. Su misión y visión están directamente alineadas con los objetivos estratégicos de InnovaTech Solutions.
Misión: "Desarrollar, operar y mantener soluciones de software seguras, robustas y de alto rendimiento que impulsen la transformación digital de nuestros clientes y aseguren la integridad de su información. Actuamos como un socio tecnológico estratégico, garantizando la eficiencia operativa tanto para los clientes externos como para las áreas internas de la organización".
Visión: "Ser reconocidos como un referente en la ingeniería de software para el sector FinTech en América Latina, destacando por nuestra excelencia en la madurez de procesos, nuestra cultura de seguridad por diseño y nuestra capacidad para innovar y adaptarnos a las nuevas tecnologías y regulaciones del mercado".
    2.1.3 Estructura organizacional del área de TI
El área de TI se organiza bajo una estructura matricial para fomentar la colaboración y la especialización. Está liderada por un Gerente de TI que reporta directamente al Gerente General de la compañía.
Los principales roles y equipos son:
Gerente de TI: Responsable máximo de la estrategia tecnológica, la gestión del presupuesto y la alineación del área con los objetivos de la empresa.
Jefe de Desarrollo: Lidera los equipos de desarrollo de software. Es responsable de la calidad técnica de los productos, la metodología de desarrollo y la gestión de los desarrolladores.
Jefe de Operaciones y Soporte: Gestiona la infraestructura tecnológica (servidores, redes, bases de datos) y lidera los equipos de soporte técnico de Nivel 1 y 2.
Oficial de Seguridad de la Información (CISO): Responsable de definir y mantener el Sistema de Gestión de Seguridad de la Información (SGSI), supervisar el cumplimiento normativo y gestionar los riesgos e incidentes de seguridad.
Arquitecto de Software: Define la arquitectura técnica de las nuevas aplicaciones y asegura que los estándares de diseño y seguridad se cumplan.
Analistas de Negocio/Producto: Actúan como puente entre los stakeholders (clientes, áreas internas) y los equipos de desarrollo, encargándose del levantamiento y especificación de requisitos.
Equipos de Desarrollo: Grupos multidisciplinarios (desarrolladores backend, frontend, QA) encargados de la construcción y mantenimiento de las aplicaciones.
Equipo de Soporte Técnico: Atiende y resuelve las incidencias y solicitudes de los clientes externos y de las áreas internas.

    2.1.4 Servicios que brinda el área de TI
El portafolio de servicios del área de TI está diseñado para cubrir todo el ciclo de vida del software y dar soporte a las operaciones de la empresa, tal como lo exige el escenario del proyecto
          Desarrollo de aplicaciones
Creación de nuevas soluciones de software y nuevas funcionalidades para productos existentes, desde la concepción de la idea hasta su puesta en producción, sirviendo principalmente a los clientes externos.
          Mantenimiento de sistemas
Aplicación de parches de seguridad, corrección de errores (mantenimiento correctivo), optimización del rendimiento (mantenimiento perfectivo) y adaptación a nuevas regulaciones o tecnologías (mantenimiento adaptativo).
          Soporte a clientes externos
Provisión de soporte técnico y funcional a los usuarios de las plataformas SaaS de la compañía, gestionando tickets de servicio y resolviendo incidencias.
          Soporte a áreas internas
Mantenimiento y soporte de los sistemas internos que utilizan los departamentos de Finanzas, Contabilidad y Recursos Humanos, como el ERP de la empresa y otras herramientas de gestión. 
2.2 Criterios de selección de procesos
La selección de los procesos a modelar no es arbitraria, sino que responde a un análisis estratégico para asegurar que la propuesta genere el mayor valor posible. Se han definido los siguientes cuatro criterios para guiar esta selección:
    2.2.1 Criterio 1: Relevancia para el área de TI
Este criterio priorizar aquellos procesos que son centrales para la misión del área de TI de InnovaTech. Se seleccionan los procesos que tienen el mayor impacto en la calidad de los productos, la satisfacción del cliente y la eficiencia operativa. Se enfoca en las actividades que constituyen el núcleo de la "fábrica de software" y la gestión de servicios.
    2.2.2 Criterio 2: Cobertura del ciclo de vida
Se busca seleccionar un conjunto de procesos que cubran de manera integral las principales fases del ciclo de vida del software, según lo definido por la norma ISO 12207. Esto incluye procesos desde las etapas iniciales de planificación y definición, pasando por el desarrollo y las pruebas, hasta la operación y el mantenimiento, asegurando una visión completa y no fragmentada.
    2.2.3 Criterio 3: Cumplimiento normativo
Dado que InnovaTech opera en el sector FinTech, el cumplimiento con las normas es crucial. Se priorizan los procesos que son fundamentales para implementar los controles y las prácticas exigidas por estándares como ISO 27001 (gestión de seguridad) e ISO 12207 (ciclo de vida), garantizando que el modelo propuesto esté alineado con las mejores prácticas internacionales.
    2.2.4 Criterio 4: Gestión de riesgos y seguridad
Este criterio se enfoca en la selección de procesos que son críticos para la gestión de los riesgos de seguridad de la información. Debido al manejo de datos financieros sensibles, se da alta prioridad a aquellos procesos donde se pueden integrar de manera efectiva los controles de seguridad de la norma ISO 27002, como la gestión de accesos, la gestión de incidentes y las prácticas de desarrollo seguro.
2.3 Mapa de procesos propuesto para el área de TI
    2.3.1 Representación gráfica del mapa de procesos




    2.3.2 Descripción general de la arquitectura
La arquitectura del mapa de procesos propuesto para el área de TI en InnovaTech Solutions se estructura en cuatro niveles jerárquicos, alineados con el ciclo de vida del software definido en ISO/IEC 12207:2017, integrando elementos de gestión de seguridad de ISO/IEC 27001:2022 y prácticas de madurez de CMMI v2.0. Este diseño promueve una gobernanza integral, donde los procesos fluyen de manera secuencial y transversal para garantizar eficiencia, trazabilidad y mitigación de riesgos.
Nivel Estratégico: Incluye procesos como la Gestión de Portafolio y Gestión de Recursos Humanos, que proporcionan dirección y soporte organizacional. Estos actúan como capa superior, alineando los esfuerzos de TI con los objetivos empresariales y asegurando recursos adecuados, conforme a las áreas de práctica GOV (Governance) y SAM (Supplier Agreement Management) de CMMI.
Procesos del Ciclo del Software: Representan el núcleo operativo, con un flujo lineal que abarca desde la Gestión de Requisitos hasta la Operación y Mantenimiento. Este nivel sigue el ciclo de vida técnico de ISO 12207 (procesos 6.4.1 a 6.4.13), enfatizando la iteratividad para adaptarse a cambios y validaciones continuas.
Procesos de Gestión de Proyectos TI: Actúan como soporte transversal, incluyendo Planificación y Control de Proyectos, Gestión de Configuración y Gestión de Riesgos. Estos procesos supervisan y controlan el ciclo principal, incorporando prácticas de CMMI como PLAN (Planning) y RSK (Risk Management), para asegurar el cumplimiento de plazos, presupuestos y estándares de calidad.
Procesos de Seguridad TI: Integrados de forma horizontal, como Gestión de Seguridad de la Información y Gestión de Incidentes de Seguridad, que infunden controles de ISO 27002:2022 (e.g., 5.27 Evaluación de riesgos, 8.25 Ciclo de vida seguro) en todos los niveles. Esta capa fortalece la resiliencia contra amenazas, promoviendo "Security by Design" y respuesta rápida a incidentes.
    2.3.3 Justificación de los 10 procesos seleccionados
Proceso 1: Gestión de Requisitos
Relevancia: Es el fundamento de todo proyecto. Define qué construir e impacta directamente en la satisfacción del cliente.
Cobertura: Inicia el ciclo de vida según ISO 12207 procesos 3.1-3.3.
Cumplimiento normativo: CMMI v2.0 área de práctica REQM (Requirements Management) y RDM (Requirements Development and Management). Implementa la ISO 27002:2022: controles 5.8 (Seguridad de proyectos), 5.12 (Clasificación de la información), 8.25 (Ciclo de vida Seguro), 8.26 (Requisitos de seguridad de aplicaciones).
Gestión de riesgos y seguridad: Integra requisitos de seguridad desde el inicio (Security by Design) mediante el control 5.27 (Evaluación de riesgos) y 5.12 (Clasificación de información).

Proceso 2: Diseño y Arquitectura
Relevancia: Define la estructura técnica que determina la calidad,escalabilidad y mantenibilidad.
Cobertura: Fase de diseño según la ISO 12207 procesos 3.4-3.5.
Cumplimiento normativo: Aplica CMMI TS (Technical Solution) con los controles 8.25 (Ciclo de vida Seguro), 8.26 (Requisitos de seguridad de aplicaciones), 8.27 (Principios de ingeniería y arquitectura de sistemas seguros) y 8.31 (Separación de entornos) de la ISO 27002:2022.
Gestión de riesgos y seguridad: Mitiga riesgos mediante la arquitectura de seguridad con el control 8.27 y segregación de entornos con 8.31 (Separación de entornos).

Proceso 3: Desarrollo e Implementación
Relevancia: Núcleo de la fábrica de software. Se programa el código, integran componentes y se documenta el desarrollo.
Cobertura: Fase de Construcción/Implementación según la ISO 12207 proceso 3.6.
Cumplimiento normativo: Implementa CMMI TS (Technical Solution) y PI (Product Integration) 3.1-3.2, junto a los controles: 8.25 (Ciclo de vida de desarrollo seguro), 8.28 (Codificación segura), 8.31 (Separación de entornos), 8.32 (Gestión de cambios) y 8.34 (Protección de información durante el desarrollo).
Gestión de riesgos y seguridad: Aplica prácticas de codificación segura (8.28), control de cambios (8.32) y protección de datos sensibles (8.34).

Proceso 4: Verificación, Validación y Transición
Relevancia: Garantiza la calidad antes de la entrega al cliente.
Cobertura: Fase de Pruebas según la ISO 12207 procesos 3.7-3.10.
Cumplimiento normativo: Implementación de CMMI VER  (Verification), VAL (Validation) y PI (Product Integration) más los controles 8.25 (Ciclo de vida de desarrollo seguro), 8.29 (Pruebas de Seguridad en desarrollo y aceptación), 8.31 (Separación de entornos), 8.32 (Gestión de cambios)  y 8.33 (Información de prueba).
Gestión de riesgos y seguridad: Válida controles de seguridad antes del despliegue y detecta vulnerabilidades en código mediante 8.29 y 8.32.

Proceso 5: Operación y Mantenimiento
Relevancia: Mantiene servicios funcionando (SLA, disponibilidad).
Cobertura: Fase final del ciclo (ISO 12207 procesos 3.11-3.12).
Cumplimiento normativo: Implementa CMMI SVC (Service System Development) con los controles de la ISO 27002:2022: 5.24 (Planificación y preparación de la gestión de incidentes), 5.37 (Procedimientos operativos documentados), 8.7 (Protección contra malware), 8.8 (Gestión de vulnerabilidades técnicas), 8.13 (Respaldo de información), 8.14 (Redundancia de instalaciones), 8.15 (Registro/logging), 8.16 (Monitoreo).
Gestión de riesgos y seguridad: Monitorea vulnerabilidades (8.8), gestiona parches, protege contra malware (8.7) y asegura respaldo (8.13) y redundancia (8.14).

Proceso 6: Planificación y Control de Proyectos
Relevancia: Proporciona estructura para ejecución exitosa de proyectos TI (asegura la entrega a tiempo y en presupuesto).
Cobertura: Se coordina en todas las fases del ciclo de vida.
Cumplimiento normativo: Implementa CMMI áreas de práctica PLAN (Planning), MC (Monitoring and Controlling) y GOV (Governance). Integra controles ISO 27002:2022: 5.8 (Seguridad de la información en la gestión de proyectos), 5.27 (Evaluación de riesgos de seguridad de la información) y 5.28 (Tratamiento de riesgos de seguridad de la información).
Gestión de riesgos y seguridad: Planifica recursos y controles de seguridad por proyecto mediante 5.27 (Evaluación de riesgos) y 5.28 (Tratamiento de riesgos).

Proceso 7: Gestión de Configuración
Relevancia: Mantiene integridad de activos de software. Controla versiones, trazabilidad, reproducibilidad.
Cobertura: Se aplica a todo el ciclo de software.
Cumplimiento normativo: Se implementa CMMI CM (Configuration Management) con los controles 8.9 (Gestión de la configuración), 5.9 (Inventario de activos), 8.9 (Gestión de la configuración), 8.31 (Separación de entornos), 8.32 (Gestión de cambios) y 8.34 (Protección de la información durante el desarrollo).
Gestión de riesgos y seguridad: Controla qué código se despliega 8.9 y 8.32, rastrea cambios para auditoría, protege información durante desarrollo (8.34).

Proceso 8: Gestión de Riesgos
Relevancia: Enfoque para anticipar problemas, previene fallos y sobrecostos.
Cobertura: Aplicable para todo el ciclo del software.
Cumplimiento normativo: Implementa CMMI RSK (Risk and Opportunity Management) con los controles 5.27 (Evaluación de riesgos) y 5.28 (Tratamiento de riesgos).
Gestión de riesgos y seguridad: Proceso central para FinTech. Gestiona riesgos técnicos y de seguridad con 5.7 (Inteligencia de amenazas) y 8.8 (Gestión de vulnerabilidades).

Proceso 9: Gestión de Seguridad de la Información
Relevancia: Protege activos de información críticos para operaciones TI.
Cobertura: Establece marco de seguridad aplicable a todo el ciclo de software.
Cumplimiento normativo: Implementa controles 5.1 (Políticas), 5.2 (Roles y responsabilidades), 5.3 (Segregación de funciones), 5.12 (Clasificación), 5.13 (Etiquetado de la información), 5.15 (Control de acceso), 5.16 (Gestión de identidad), 5.17 (Información de autenticación), 5.18 (Derechos de acceso), 5.34 (Privacidad y Personally Identifiable Information (PII)).
Gestión de riesgos y seguridad: Proceso mandatorio para establecer cultura de seguridad organizacional.

Proceso 10: Gestión de Incidentes de Seguridad
Relevancia: Respuesta rápida a brechas que afectan servicios TI.
Cobertura: Especialmente crítico en fase de operación.
Cumplimiento normativo: Implementa CMMI v2.0 área de práctica IRP (Incident Resolution and Prevention). Integra el ciclo completo de gestión de incidentes 5.24 (Planificación y preparación de la gestión de incidentes), 5.25 (Evaluación y decisión sobre eventos), 5.26 (Respuesta a incidentes), 5.27 (Aprendizaje de incidentes), complementado con 8.16 (Actividades de monitoreo).
Gestión de riesgos y seguridad: Mitiga impacto de incidentes de seguridad materializados.

    2.3.4 Interrelación entre procesos
Estos 10 procesos seleccionados no operan de manera aislada, sino que forman un ecosistema interconectado que refleja la complementariedad entre ISO 12207:2017 (ciclo de vida), ISO 27001/27002:2022 (seguridad) y CMMI v2.0 (madurez). Esta interrelación asegura trazabilidad, eficiencia y resiliencia, donde las salidas de un proceso sirven como entradas para otros, fomentando ciclos de retroalimentación y mejora continua. A continuación, se detalla las principales conexiones:
Flujo secuencial en el ciclo de vida de software: La Gestión de Requisitos (Proceso 1) genera especificaciones que alimentan directamente al Diseño y Arquitectura (Proceso 2), donde se definen estructuras técnicas. Estas, a su vez, guían el Desarrollo e Implementación (Proceso 3), cuya salida (código y componentes) se somete a Verificación, Validación y Transición (Proceso 4). Finalmente, el software desplegado ingresa a Operación y Mantenimiento (Proceso 5), cerrando el ciclo con retroalimentación para requisitos futuros (alineado con ISO 12207:2017, procesos 6.4.1-6.4.13).
Soporte transversal de gestión de proyectos: La Planificación y Control de Proyectos (Proceso 6) supervisa todo el flujo, definiendo cronogramas y recursos que impactan en todos los procesos core. La Gestión de Configuración (Proceso 7) asegura versiones controladas, interconectándose con Desarrollo (Proceso 3) para cambios en código y con Verificación (Proceso 4) para pruebas reproducibles (CMMI CM y ISO 27002:8.32 Gestión de cambios). La Gestión de Riesgos (Proceso 8) evalúa amenazas en cada fase, alimentando ajustes en Requisitos (Proceso 1) o Diseño (Proceso 2) mediante evaluaciones iterativas (CMMI RSK y ISO 27002:5.27).
Integración de seguridad horizontal: La Gestión de Seguridad de la Información (Proceso 9) infunde controles en todos los procesos, como clasificación de datos en Requisitos (Proceso 1) o codificación segura en Desarrollo (Proceso 3) (ISO 27002:5.12 y 8.28). La Gestión de Incidentes de Seguridad (Proceso 10) recibe alertas de Operación y Mantenimiento (Proceso 5) o Monitoreo (Proceso 8), generando lecciones aprendidas que retroalimentan Riesgos (Proceso 8) y Configuración (Proceso 7) para parches y actualizaciones (ISO 27002:5.24-5.26).


2.4 Procesos modelados con notación BPMN
2.4.1 PROCESO 1: GESTIÓN DE REQUISITOS
      2.4.1.1 Descripción del proceso
La Gestión de Requisitos comprende la captura, análisis, especificación, validación, priorización, trazabilidad y control de cambios de los requisitos funcionales y no funcionales del producto/servicio software. En términos de ISO 12207, abarca la definición de necesidades y requisitos de las partes interesadas y la definición de requisitos del sistema/software, asegurando su alineación con objetivos de negocio, restricciones regulatorias y riesgos operativos y de seguridad. El proceso es iterativo e impulsa la coherencia entre lo que el cliente necesita y lo que el equipo construye, garantizando trazabilidad bidireccional hacia arquitectura, pruebas y despliegue. 
      2.4.1.2 Propósito del proceso
El propósito es lograr requisitos correctos, completos, verificables y trazables, integrando tempranamente consideraciones de seguridad y cumplimiento. Con ello se reduce el retrabajo, se mejora la previsibilidad del proyecto y se establecen criterios de aceptación objetivos para verificación/validación posteriores. ISO 12207 posiciona estos resultados como insumos formales del ciclo de vida técnico (diseño, implementación, V&V, transición y operación), lo que refuerza su rol como “punto único de verdad” para todas las decisiones posteriores. 
      2.4.1.3 Entradas y salidas
              Entradas
 Se alimenta de la solicitud o idea de negocio, metas y restricciones, políticas internas, contexto y riesgos del SGSI, normativa aplicable, información de incidentes previos, lineamientos de arquitectura, y estándares organizacionales (p. ej., criterios de “buena” especificación de requisitos y guías de seguridad). En el marco del SGSI, entran además clasificación y etiquetado de información cuando los requisitos tocan datos sensibles, y criterios de “seguridad en la gestión de proyectos” para que la seguridad esté presente desde el inicio. 
              Salidas
La salida principal es la Especificación de Requisitos (SRS) o backlog (historias de usuario con criterios de aceptación), los requisitos no funcionales (rendimiento, disponibilidad, privacidad y seguridad), los modelos complementarios(casos de uso, modelos de dominio), la matriz de trazabilidad (requisito→diseño→prueba→versión), el plan de gestión de requisitos y la línea base aprobada (baseline) bajo control de configuración. Estas salidas quedan bajo gobierno de gestión de configuración y con evidencias medibles para auditorías y SoA del SGSI.  
      2.4.1.4 Roles
Participan Stakeholders/Usuario clave (aportan necesidades y validan), Analista de Negocio / Product Owner(elicitación, priorización, calidad de requisitos), Arquitecto(a) (alineación con arquitectura y restricciones tecnológicas), Equipo de Desarrollo (factibilidad técnica temprana), QA/Testing (diseño de validaciones según criterios de aceptación), Seguridad de la Información (CISO/SGSI) (requisitos de seguridad, clasificación y controles), Gestión de Configuración (baselines, control de cambios) y Gestión de Proyecto/PMO (planificación, seguimiento, riesgos). Esta asignación operacionaliza las prácticas de gestión técnica de ISO 12207 (riesgos, calidad, configuración, medición). Stakeholders/Usuario clave: Aportan necesidades y validan.
      2.4.1.5 Modelo del proceso en notación BPMN
   2.4.1.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
El diagrama implementa los procesos 6.4.1 (Definición de necesidades de las partes interesadas) y 6.4.2 (Análisis de requisitos del sistema). La actividad "Realizar elicitación de requisitos" captura necesidades del negocio, mientras que "Consolidar requisitos funcionales y no funcionales" y "Especificar requisitos (SRS/Backlog)" materializan el análisis riguroso. El flujo paralelo hacia Arquitecto(a) ("Validar viabilidad arquitectónica") y Equipo de Desarrollo ("Revisar factibilidad técnica") asegura viabilidad antes de formalizar. El gateway "¿Completos y válidos?" Implementa el ciclo iterativo de refinamiento que ISO 12207 exige para requisitos de calidad.
La participación de Gestión de Configuración en "Establecer línea base de requisitos" vincula con el proceso 6.3.5. La "Matriz de trazabilidad" soporta el proceso 6.3.6 (Gestión de la información) al documentar relaciones entre requisitos, diseño y pruebas. La integración al plan de proyecto conecta con 6.3.1 (Gestión de proyectos).
Integración con ISO 27001:2022
Cláusula 6.1.2 (Evaluación de riesgos): La actividad "Evaluar riesgos del proyecto" implementa evaluación sistemática de riesgos. Ocurre en paralelo con "Identificar requisitos de seguridad", traduciendo riesgos en controles concretos (Security by Design).
Cláusula 6.1.3 (Tratamiento de riesgos): El gateway "¿Stakeholder aprueba?" implementa toma de decisiones sobre tratamiento de riesgos. El loop de retroalimentación permite ajustar especificaciones para implementar controles adicionales.
Cláusula 8.1 (Planificación y control operacional): El proceso demuestra planificación con entradas definidas, actividades estructuradas, puntos de decisión y salidas controladas bajo gestión de configuración.
Controles ISO 27002:2022
5.8 (Seguridad en gestión de proyectos): El rol Seguridad (CISO/SGSI) participa desde "Identificar requisitos de seguridad" hasta "Clasificar información sensible", asegurando que seguridad está integrada desde la concepción del proyecto.
5.12 (Clasificación de información): Implementado directamente por "Clasificar información sensible". Determina controles de protección cuando requisitos involucran datos sensibles, alimentando requisitos no funcionales de seguridad.
5.27 (Evaluación de riesgos): La actividad "Evaluar riesgos del proyecto" identifica amenazas y vulnerabilidades asociadas a requisitos propuestos, determinando si se requieren controles adicionales.
8.25 (Ciclo de vida seguro): El proceso completo constituye la fase inicial del ciclo de vida seguro, integrando evaluación de riesgos, requisitos de seguridad y validación arquitectónica antes de diseño.
8.26 (Requisitos de seguridad de aplicaciones): "Identificar requisitos de seguridad" define requisitos como autenticación, control de acceso, cifrado, auditoría y protección contra amenazas (OWASP Top 10), integrándose a la especificación formal.
Evidencia auditable
Matriz de trazabilidad: Relaciona requisitos de negocio, seguridad, riesgos y controles
Línea base aprobada: Snapshot formal del SRS bajo control de configuración
Registros de decisión: Los gateways documentan quién aprobó, cuándo y bajo qué criterios
Plan de validación: Genera criterios de aceptación verificables para controles de seguridad
2.4.2 PROCESO 2: DISEÑO Y ARQUITECTURA
      2.4.2.1 Descripción del proceso
El proceso se encarga de transformar los requisitos aprobados en una solución técnica estructurada. Implica definir la arquitectura del sistema, establecer los componentes principales, seleccionar tecnologías y patrones de diseño, y garantizar que las decisiones tomadas respondan a criterios de calidad, escalabilidad, mantenibilidad y seguridad. Según la ISO 12207 (procesos 3.4 y 3.5), esta fase corresponde al diseño arquitectónico y detallado, mientras que las normas ISO 27001/27002 refuerzan la integración de principios de diseño seguro y segregación de entornos para prevenir riesgos de seguridad desde la etapa de planificación.
      2.4.2.2 Propósito del proceso
El propósito es contar con una base técnica sólida que sirva de guía para la construcción del software, reduciendo riesgos de retrabajo y asegurando que la solución propuesta cumpla con los requisitos funcionales y no funcionales. También busca incorporar desde el inicio medidas de seguridad por diseño para mitigar vulnerabilidades en fases posteriores.
      2.4.2.3 Entradas y salidas
              Entradas
Especificación de requisitos aprobada (SRS), lineamientos de arquitectura de la organización, políticas de seguridad de la información, evaluación de riesgos.
              Salidas
Documento de diseño técnico, diagramas de arquitectura y despliegue, lista de tecnologías y componentes seleccionados, validación formal de seguridad en el diseño.
      2.4.2.4 Roles
Arquitecto de Software: Responsable de elaborar la arquitectura del sistema, definir estándares técnicos y seleccionar patrones de diseño.
Oficial de Seguridad de la Información (CISO): Revisa que el diseño incluya controles de seguridad, segregación de entornos y cumplimiento normativo.

Equipo de Desarrollo Senior: Evalúa la viabilidad técnica de las decisiones arquitectónicas y aporta experiencia en la selección de tecnologías.
Jefe de Proyecto: Supervisa la aprobación del diseño, asegurando que se cumpla con tiempos y costos establecidos.
Stakeholders Clave: Validan que el diseño propuesto se alinee con los objetivos de negocio y las necesidades del usuario final.
      2.4.2.5 Modelo del proceso en notación BPMN

      2.4.2.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
El diagrama implementa los procesos 6.4.3 (Diseño arquitectónico del sistema) y 6.4.4 (Diseño detallado del software) de la ISO 12207.


Las actividades “Analizar el SRS y lineamientos de arquitectura”, “Definir estructura del sistema” y “Seleccionar tecnologías base” transforman los requisitos en un diseño técnico estructurado. La intervención del Equipo de Desarrollo Senior en la evaluación técnica garantiza viabilidad, mientras que el CISO valida que el diseño cumpla con los principios de seguridad y segregación de entornos.


Finalmente, las etapas “Validar cumplimiento de tiempos, costos y alcance” y “Registrar diseño aprobado” establecen la línea base técnica bajo control de configuración, cumpliendo con el proceso 6.3.5 (Gestión de la configuración).
Integración con ISO 27001:2022
Cláusula 5.30 (Seguridad en el diseño y desarrollo de sistemas): Representada por las actividades del Arquitecto de Software y del CISO al definir controles de seguridad dentro de la arquitectura.
Cláusula 6.1.2 (Evaluación de riesgos): Aplicada en la revisión del diseño por el CISO, donde se identifican posibles vulnerabilidades antes de su aprobación.
Cláusula 8.9 (Gestión de la configuración): Se evidencia en la formalización del Documento de Diseño Técnico y su control como línea base validada.
Controles ISO 27002:2022
8.28 (Seguridad en entornos de desarrollo): El CISO garantiza que la arquitectura considere entornos segregados para desarrollo, pruebas y producción.
8.29 (Principios de ingeniería segura): Reflejado en la definición de la estructura del sistema y la selección de tecnologías y patrones seguros.
8.30 (Seguridad en el diseño de sistemas): Implementado al documentar mecanismos de protección como autenticación, cifrado y control de acceso.
5.8 (Seguridad en gestión de proyectos): Cumplido por el Jefe de Proyecto al integrar la seguridad dentro de la planificación y aprobación del diseño.
2.4.3 PROCESO 3: DESARROLLO E IMPLEMENTACIÓN
      2.4.3.1 Descripción del proceso
El proceso corresponde a la construcción del software con base en el diseño técnico aprobado. Comprende la programación de módulos, la integración de componentes, la aplicación de estándares de codificación segura, la ejecución de pruebas iniciales y la elaboración de documentación técnica. Según la ISO 12207 (proceso 3.6), esta fase abarca la implementación y verificación de los productos de software, mientras que las normas ISO 27001/27002 establecen controles para asegurar entornos protegidos, gestión de cambios y prácticas de codificación segura.
      2.4.3.2 Propósito del proceso
El propósito es transformar el diseño en un producto funcional y seguro, cumpliendo con los requisitos establecidos y preparado para fases posteriores de validación. Este proceso busca garantizar calidad técnica, trazabilidad de versiones y mitigación de riesgos de seguridad desde la construcción.
      2.4.3.3 Entradas y salidas
              Entradas
Documento de diseño técnico aprobado, diagramas de arquitectura y despliegue, lista de tecnologías y componentes seleccionados y validación formal de seguridad en el diseño.
              Salidas
Código fuente implementado y versionado, módulos y componentes integrados, reportes de pruebas unitarias e integración, documentación técnica actualizada del desarrollo y versión estable del software lista para validación.
      2.4.3.4 Roles
Desarrolladores: Implementan los módulos según el diseño técnico, aplican estándares de programación y documentan el código.
Equipo de QA/Testing: Ejecuta pruebas unitarias e integración, asegurando que el producto cumpla con los criterios de calidad.
DevOps / Administrador de Entornos: Configura y mantiene los ambientes de desarrollo e integración continua, gestiona despliegues y controla versiones.
Oficial de Seguridad de la Información (CISO): Revisa el cumplimiento de las prácticas de codificación segura, la trazabilidad de los cambios y la seguridad en los repositorios.
Arquitecto de Software: Da soporte en la implementación para asegurar que la construcción se ajuste al diseño definido.
Jefe de Proyecto: Supervisa avances, coordina entregables y valida que se cumpla con plazos y alcance.

      2.4.3.5 Modelo del proceso en notación BPMN

      2.4.3.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
El diagrama implementa los procesos 6.4.5 (Implementación del software) y 6.4.6 (Verificación del software) de la ISO 12207.
Las actividades “Configurar entornos”, “Implementar módulos según el DDT” y “Ejecutar pruebas unitarias e integración” materializan la construcción del software bajo estándares de codificación segura. El ciclo de corrección entre QA y Desarrollo representa la verificación continua exigida por la norma.
La intervención del CISO en la revisión de seguridad y del Jefe de Proyecto en la validación final garantiza trazabilidad, cumplimiento de requisitos y control sobre las versiones liberadas.
Integración con ISO 27001:2022
Cláusula 8.26 (Seguridad del desarrollo de software): Evidenciada en las actividades de codificación y revisión, asegurando el cumplimiento de prácticas seguras durante la implementación.
Cláusula 8.27 (Pruebas de seguridad en desarrollo): Aplicada en las pruebas unitarias e integraciones realizadas por QA y revisadas por el CISO.
Cláusula 8.9 (Gestión de la configuración): Reflejada en la administración de versiones, control de cambios y entornos gestionados por DevOps.
Controles ISO 27002:2022
8.25 (Ciclo de vida seguro): El proceso completo cubre las etapas de implementación y verificación dentro de un desarrollo seguro.
8.26 (Revisión de código y pruebas de seguridad): Desarrolladores, QA y CISO colaboran en la detección y mitigación de vulnerabilidades.
8.27 (Protección de información en entornos de desarrollo): Implementado mediante repositorios controlados y acceso restringido.
8.31 (Separación de entornos): Evidenciado en la configuración de ambientes independientes para desarrollo y pruebas antes del despliegue final.
2.4.4 PROCESO 4: VERIFICACIÓN, VALIDACIÓN Y TRANSICIÓN
      2.4.4.1 Descripción del proceso
El proceso tiene como objetivo asegurar que el software construido cumple con los requisitos funcionales, de seguridad y de calidad definidos durante las fases anteriores, y que puede ser entregado de manera controlada al entorno operativo.
Inicia con la preparación del entorno de pruebas, seguido de la verificación técnica, luego la validación funcional con usuarios y QA, y finalmente la transición al ambiente productivo, acompañada de la documentación final y la aprobación del Product Owner. Este flujo garantiza que el producto sea aprobado, aceptado y transferido de forma segura, minimizando errores en la puesta en marcha. 
      2.4.4.2 Propósito del proceso
El propósito es confirmar la conformidad técnica y funcional del software, así como garantizar su liberación segura y controlada al ambiente de producción.
Además busca que la entrega sea trazable, verificable y documentada, siguiendo buenas prácticas de aseguramiento de la calidad y seguridad de la información.
En esta etapa se valida no solo que el software funcione correctamente, sino que se cumplan los requisitos de seguridad, disponibilidad y confidencialidad establecidos.
      2.4.4.3 Entradas y salidas
              Entradas
Resultados de pruebas unitarias e integración del proceso de desarrollo, plan de pruebas y criterios de aceptación, informes de revisión de código y seguridad, documento de diseño técnico aprobado y versión estable del software listo para validación.
              Salidas
Informe de verificación y validación completado, versión final del software aprobada para despliegue y documentación técnica actualizada.
      2.4.4.4 Roles
Product Owner: Participa en la validación funcional y aceptación del producto.
Analista de Negocio: Elicitación, priorización, calidad de requisitos.
Equipo de QA: Ejecuta pruebas funcionales, de integración, rendimiento y seguridad.
Desarrollador: Corrigen defectos detectados durante la verificación y reenvían versiones para validación.
Oficial de Seguridad (SGSI): Supervisa pruebas de seguridad y valida el cumplimiento de controles de protección.
DevOps: Efectúa el despliegue controlado al entorno productivo durante la transición.
Gestor de Configuración: Administra las versiones del software, mantiene la trazabilidad de cambios y controla qué versión se libera para la validación o producción.
Release Manager: Evalúa y aprueba las solicitudes de despliegue en el entorno productivo.
Soporte/Operaciones: Reciben el sistema en producción, validan la estabilidad post-despliegue y garantizan la continuidad del servicio.
      2.4.4.5 Modelo del proceso en notación BPMN

      2.4.4.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
ISO 12207:2017
Proceso 6.4.7 (Verificación) y 6.4.8 (Validación): El flujo implementa ambas fases garantizando que el software cumple las especificaciones técnicas y funcionales.
Proceso 6.4.9 (Transición del Software): Representado por la entrega controlada al ambiente productivo y la documentación del cierre.

ISO 27001:2022
Cláusula 8.28 (Pruebas de seguridad y aceptación): Evidenciada en la validación de seguridad antes de la liberación.
Cláusula 8.25 (Gestión del cambio): Aplicada durante las correcciones y revisiones posteriores a pruebas.
Cláusula 8.31 (Separación de entornos): Demostrada en la transición entre ambientes de prueba y producción bajo control DevOps.

ISO 27002:2022
Control 8.26 (Revisión de código y pruebas de seguridad): Aplicado durante la verificación técnica.
Control 8.27 (Protección de información en entornos de desarrollo y prueba): Cumplido mediante el aislamiento de entornos y control de accesos.
Control 8.28 (Revisión de código y pruebas de seguridad): Reflejado en la ejecución formal de validaciones y pruebas de aceptación con el cliente.

2.4.5 PROCESO 5: OPERACIÓN Y MANTENIMIENTO
      2.4.5.1 Descripción del proceso
Este proceso garantiza continuidad, estabilidad y mejora del software una vez desplegado en el entorno productivo. Incluye la gestión de incidentes, monitoreo de rendimiento, aplicación de parches, resolución de errores, gestión de versiones y mantenimiento preventivo y evolutivo.
Según la ISO 12207 (procesos 3.11 y 3.12) esta fase comprende la operación de los productos de software y su mantenimiento durante el ciclo de vida, asegurando que el sistema cumpla con los niveles de servicio acordados y mantenga la integridad de la información.
Las normas ISO 27001/27002 refuerzan este proceso mediante controles de continuidad operativa, seguridad en la gestión de incidentes, actualizaciones y vulnerabilidades.
      2.4.5.2 Propósito del proceso
El propósito del proceso es asegurar que el software en producción se mantenga operativo, seguro y eficiente, cumpliendo los requisitos funcionales y de seguridad establecidos.
Busca minimizar interrupciones del servicio, responder rápidamente ante incidentes o fallas, y mantener el software actualizado ante nuevos requerimientos o amenazas, garantizando su confiabilidad y soporte continuo.
      2.4.5.3 Entradas y salidas
              Entradas
Software liberado y aprobado para producción, solicitudes de cambio y políticas de seguridad.
              Salidas
Registro de incidentes resueltos, actualizaciones o parches aplicados, nuevas versiones del software post mantenimiento y documentación técnica actualizada.
      2.4.5.4 Roles
Usuario final: Reporta fallos, valida la solución implementada y participa en la aceptación de cambios.
Service Desk: Primer punto de contacto con el usuario. Registra, clasifica y prioriza incidentes o solicitudes.
DevOps: Supervisa la infraestructura y entornos productivos y automatiza despliegues.
Mantenimiento/Desarrollo: Atiende los incidentes escalados y realiza correcciones o mejoras de código.
Gestor de Cambios: Evalúa y aprueba las modificaciones antes de su implementación en el entorno productivo.
Gestión de Configuración: Controla versiones, mantiene la trazabilidad de los cambios y asegura la integridad de los ítems configurados.
Seguridad de la información: Supervisa la aplicación de parches y revisa los incidentes relacionados con la seguridad.
Service Manager: Supervisa la operación general de servicio.
Proveedor: Brinda soporte especializado en casos donde la incidencia o mantenimiento involucra componentes externos o software de terceros.
      2.4.5.5 Modelo del proceso en notación BPMN

      2.4.5.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
ISO 12207:2017
Proceso 6.4.10 (Operación del software): Reflejado en la ejecución de tareas operativas por parte de DevOps, Service Desk y Service Manager.
Proceso 6.4.11 (Mantenimiento del software): Evidenciado en las actividades de corrección, mejora y evolución del sistema realizadas por el equipo de Mantenimiento/Desarrollo.

ISO 27001:2022
Cláusula 8.15 (Gestión de incidentes de seguridad): Aplicada en el registro, análisis y resolución de incidentes por Service Desk y Seguridad de la Información.
Cláusula 8.16 (Gestión de vulnerabilidades técnicas): Evidenciada en el mantenimiento preventivo, escaneo de vulnerabilidades y aplicación de parches.
Cláusula 8.9 (Gestión de la configuración): Cumplida mediante el control de versiones, documentación y trazabilidad de los cambios.
Cláusula 8.4 (Gestión de capacidades): Reflejada en el monitoreo de recursos y rendimiento por DevOps.
Cláusula 8.32 (Gestión de proveedores): Evidenciada en la interacción y control de soporte externo durante las tareas de mantenimiento.

ISO 27002:2022
8.15 (Registro y monitoreo de incidentes): Controlado por el Service Desk y revisado por Seguridad de la Información.
8.16 (Gestión de vulnerabilidades): Aplicada por DevOps y el equipo de mantenimiento en actualizaciones periódicas.
8.30 (Seguridad en operaciones): Garantiza la protección de sistemas productivos y gestión segura de accesos.
8.31 (Separación de entornos): Aplica la segregación de entornos (desarrollo, pruebas y producción) para mantener la estabilidad del servicio.
8.32 (Relación con proveedores): Regula las actividades compartidas con terceros durante el soporte y mantenimiento del software.
2.4.6 PROCESO 6: PLANIFICACIÓN Y CONTROL DE PROYECTOS
      2.4.6.1 Descripción del proceso
La Planificación y Control de proyectos establece un marco metodológico integral para gestionar proyectos TI, definiendo la planificación, estimación, programación, monitoreo y control que aseguran la entrega dentro del alcance, tiempo, presupuesto y calidad acordados. Integran sistemáticamente requisitos de seguridad y evaluación de riesgos desde la fase inicial para garantizar el cumplimiento normativo, constituyendo así el núcleo de gobierno transversal que proporciona visibilidad, control y toma de decisiones informadas para todos los proyectos de la organización.
      2.4.6.2 Propósito del proceso
El propósito del proceso de Planificación y Control de Proyectos es establecer planes realistas que definan alcance, cronograma, presupuesto, recursos y riesgos; monitorear el progreso mediante indicadores para detectar desviaciones tempranas; controlar cambios de manera disciplinada evaluando su impacto; gestionar riesgos proactivamente; integrar requisitos de seguridad según ISO 27001/27002:2022 desde la planificación; asegurar la entrega exitosa de proyectos alineados con los objetivos estratégicos de InnovaTech y expectativas de stakeholders; y facilitar la toma de decisiones mediante información oportuna y precisa sobre el estado de los proyectos.
      2.4.6.3 Entradas y salidas
              Entradas
El proceso de Planificación y Control de Proyectos recibe como entradas fundamentales la Acta de constitución que autoriza formalmente la iniciativa desde la Dirección del Portafolio; los Requisitos del Proyecto validados por el proceso de Gestión de Requisitos; plantillas estandarizadas del repositorio organizacional; el Registro de Riesgos previos del proceso de Gestión de Riesgos; las Políticas de Seguridad de la Información establecidas por el proceso correspondiente; información sobre Recursos Disponibles proveniente de Gestión de RR.HH. y Dirección; y Datos Históricos de proyectos anteriores de la base de conocimiento organizacional, integrando así todos los insumos necesarios para una planificación completa y alineada.
              Salidas
El proceso genera como salidas principales un Plan de Proyecto integral que dirige todos los procesos del ciclo de vida; un Plan de Gestión de Riesgos y un Plan de Seguridad de la Información específicos para el proyecto; un Cronograma y Presupuesto base aprobados; Informes de Progreso periódicos para stakeholders; un Registro de Cambios para la Gestión de Configuración; Acciones Correctivas para el equipo del proyecto; y un Reporte de Cierre que documenta resultados y lecciones aprendidas para la Gestión del Portafolio y la base de conocimiento organizacional.
      2.4.6.4 Roles
Roles de Liderazgo y Gobierno:
Líder de Planificación de Proyectos: Coordina la elaboración del plan de proyecto, asegurando que el alcance, cronograma, presupuesto y riesgos estén definidos y alineados con los objetivos estratégicos.
Especialista en Control de Avances y Métricas: Supervisa los indicadores de desempeño del proyecto, detecta desviaciones y propone acciones correctivas basadas en datos objetivos.
Director de Gestión de Proyectos TI: Dirige la ejecución del proyecto, facilitando la comunicación entre equipos, gestionando recursos y asegurando el cumplimiento de entregables.
Roles Técnicos Especializados:
Coordinador de Seguridad: Integra requisitos de seguridad desde la fase de planificación, alineando el proyecto con normas como ISO/IEC 27001 y gestionando controles técnicos.
Analista de Riesgos de Proyectos TI: Identifica, evalúa y monitorea riesgos que puedan afectar el proyecto, proponiendo medidas de mitigación y seguimiento.
Encargado de Configuración: Controla los cambios en entregables, versiones y documentación técnica, asegurando trazabilidad y consistencia a lo largo del ciclo de vida.
Roles de Ejecución y Validación:
Responsable de Entregables Técnicos: Supervisa la calidad y funcionalidad de los entregables técnicos, asegurando que cumplan con los requisitos definidos.
Especialista en Control de Calidad: Evalúa la conformidad de los productos y procesos del proyecto, aplicando criterios de calidad y buenas prácticas.
Validador de Cumplimiento Normativo: Revisa que el proyecto cumpla con estándares, políticas internas y requisitos regulatorios, validando entregables clave.
Roles de Decisión y Representación:
Patrocinador Ejecutivo del Proyecto: Representa la alta dirección, autoriza recursos y decisiones clave, y asegura que el proyecto esté alineado con la estrategia organizacional.
Representante de Usuarios Finales: Aporta la perspectiva funcional y operativa de los usuarios finales, validando que el proyecto responda a sus necesidades reales.
Coordinador de Comunicaciones con Stakeholders: Facilita el flujo de información entre stakeholders, asegurando que los avances, riesgos y decisiones sean comunicados oportunamente.
      2.4.6.5 Modelo del proceso en notación BPMN

      2.4.6.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
Integración ISO/IEC 12207:2017 - Procesos de Gestión de Proyectos
Project Planning Process (6.3.1): Define cómo planificar proyectos de software, estableciendo alcance, cronograma, recursos y presupuesto.
Project Assessment and Control Process (6.3.2): Establece monitoreo continuo del proyecto para detectar desviaciones y tomar acciones correctivas.
Decision Management Process (6.3.3): Proporciona estructura para toma de decisiones informadas (ej: aprobación de cambios).
Risk Management Process (6.3.4): Requiere identificación, análisis y tratamiento sistemático de riesgos del proyecto.
Configuration Management Process (6.3.5): Establece líneas base (baselines) de alcance, cronograma y costo, y controla cambios.
Integración ISO/IEC 27001:2022 - Requisitos del Sistema de Gestión de Seguridad de la Información
Evaluación de riesgos de seguridad de la información (6.1.2): La organización debe definir y aplicar un proceso de evaluación de riesgos de seguridad.
Tratamiento de riesgos de seguridad de la información (6.1.3): Se deben definir e implementar planes de tratamiento de riesgos.
Seguimiento, medición, análisis y evaluación (9.1): Se debe monitorear y medir el desempeño del SGSI.
Integración ISO/IEC 27002:2022 - Controles de Seguridad de la Información
Seguridad de la información en la gestión de proyectos (5.8): Integrar seguridad de la información en la gestión de proyectos, independientemente de la metodología utilizada.
Evaluación de riesgos de seguridad de la información (5.27): Identificar riesgos de seguridad asociados con los activos de información y evaluar su probabilidad e impacto.
Tratamiento de riesgos de seguridad de la información (5.28): Definir e implementar opciones de tratamiento para riesgos de seguridad (mitigar, transferir, aceptar, evitar).
Seguridad de la información durante la disrupción (5.29): Planificar cómo mantener la seguridad de la información durante eventos disruptivos.
2.4.7 PROCESO 7: GESTIÓN DE CONFIGURACIÓN
      2.4.7.1 Descripción del proceso
El proceso de Gestión de la Configuración establece la disciplina técnica y administrativa para identificar, controlar, auditar y reportar el estado de todos los artefactos producidos durante el ciclo de vida del software. Estos artefactos, conocidos como Ítems de Configuración (CI), incluyen el código fuente, la documentación de requisitos y diseño, los planes de prueba, los scripts de despliegue y la configuración de los entornos. El proceso asegura que la integridad de cada CI sea mantenida y que cualquier cambio se realice de manera controlada y trazable, previniendo modificaciones no autorizadas que puedan introducir errores o vulnerabilidades.
      2.4.7.2 Propósito del proceso
El propósito fundamental de este proceso es establecer y mantener la integridad de los productos de software a lo largo de todo su ciclo de vida. Busca garantizar que se conoce en todo momento qué versión de cada componente está en cada ambiente (desarrollo, pruebas, producción), quién realizó los cambios, cuándo y por qué. Esto facilita la reproducibilidad de los builds, la gestión de múltiples versiones del software, la auditoría del proyecto y la correcta resolución de incidentes, al tiempo que minimiza los riesgos asociados a cambios no controlados.
      2.4.7.3 Entradas y salidas
              Entradas
Ítems de Configuración (CI) a gestionar: Cualquier artefacto del proyecto que requiera control (código, documentos, scripts, etc.).
Solicitud de Cambio (Change Request): Documento formal que describe un cambio propuesto a una línea base establecida.
Plan de Gestión de la Configuración: Documento que define la estrategia, roles, herramientas y procedimientos para la gestión de la configuración del proyecto.
Línea Base (Baseline): Una versión estable y aprobada de uno o más CIs que sirve como punto de referencia para el desarrollo futuro.
              Salidas
Repositorio de Configuración Centralizado: Herramienta (ej. Git) que almacena de forma segura y versionada todos los CIs del proyecto.
Líneas Base de Configuración establecidas: Versiones formales y aprobadas de los productos de trabajo en puntos clave del ciclo de vida (ej. "Línea Base de Requisitos Aprobados").
Registros de Auditoría de Configuración: Informes que verifican que la configuración física de un producto coincide con su documentación y que los procesos se han seguido correctamente.
Informes de Estado de la Configuración: Reportes periódicos que describen el estado actual de los CIs, las líneas base y los cambios realizados.
      2.4.7.4 Roles
Gestor de Configuración (o rol asumido por el Jefe de Desarrollo/DevOps): Es el responsable principal del proceso. Administra el repositorio, establece las líneas base, gestiona las herramientas de CM y genera los informes de estado.
Equipo de Desarrollo: Son los principales usuarios del proceso. Crean y modifican los CIs (principalmente código fuente) y siguen los procedimientos de versionamiento y control de cambios.
Comité de Control de Cambios (CCB - Change Control Board): Grupo formado por stakeholders clave (Jefe de Proyecto, Product Owner, Arquitecto, CISO) responsable de revisar, aprobar o rechazar las solicitudes de cambio a las líneas base.
Equipo de QA/Testing: Utiliza las líneas base de configuración para asegurar que las pruebas se realizan sobre versiones estables y conocidas del software.
      2.4.7.5 Modelo del proceso en notación BPMN
















      2.4.7.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
El diagrama implementa el proceso 6.3.5 (Gestión de la configuración). Las actividades "Registrar CR en sistema de control", "Identificar CIs afectados" y "Verificar línea base actual" establecen identificación y control de ítems de configuración. El Comité de Control de Cambios (CCB) en "Revisar solicitud de cambio" implementa el control formal que ISO 12207 requiere para cambios a líneas base.
"Registrar cambio en sistema de versionamiento" materializa el control de versiones. "Establecer nueva línea base" y "Generar informe de estado de configuración" proporcionan trazabilidad y estado de configuración. La actividad "Actualizar documentación de configuración" asegura que la documentación refleje el estado real del producto.
El proceso se vincula con 6.3.1 (Gestión de proyectos) mediante "Integrar requisitos al plan de proyecto", y con 6.3.6 (Gestión de información) al mantener registros auditables de cambios.
Integración con ISO 27001:2022
Cláusula 6.1.2 (Evaluación de riesgos): Las actividades paralelas "Analizar impacto técnico" y "Evaluar impacto en pruebas" implementan evaluación de riesgos antes de aprobar cambios. Cada solicitud de cambio se evalúa por su impacto en la seguridad.
Cláusula 8.1 (Planificación y control operacional): El proceso completo demuestra control operacional sobre activos de software. El CCB proporciona gobernanza formal sobre cambios, y las líneas base establecen puntos de control verificables.
Cláusula 9.1 (Seguimiento y medición): Los "Informes de estado de configuración" proporcionan métricas sobre cambios realizados, líneas base establecidas y estado de CIs, soportando el seguimiento del SGSI.
Controles ISO 27002:2022
5.9 (Inventario de activos): "Identificar CIs afectados" mantiene inventario actualizado de todos los artefactos del proyecto (código, documentos, scripts), identificando qué activos se ven impactados por cada cambio.
8.9 (Gestión de la configuración): El proceso completo implementa este control. "Verificar línea base actual" y "Establecer nueva línea base" aseguran que se conoce qué versión de cada componente está en cada ambiente (desarrollo, pruebas, producción).
8.31 (Separación de entornos): Implícito en el proceso cuando "Ejecutar pruebas sobre nueva versión" válida cambios en ambiente de pruebas antes de promoverlos a producción mediante la nueva línea base.
8.32 (Gestión de cambios): Implementado directamente por el flujo completo del CCB: "Revisar solicitud de cambio" → gateway "¿Cambio aprobado?" → "Implementar cambio en repositorio". Cada cambio requiere aprobación formal, documentación de impacto y validación antes de integrarse.
8.34 (Protección de información en desarrollo): El "Repositorio de Configuración Centralizado" con control de acceso y "Registrar cambio en sistema de versionamiento" protegen el código fuente y artefactos durante todo el ciclo de desarrollo, previniendo modificaciones no autorizadas.
Evidencia auditable
Repositorio Git: Registro completo de quién cambió qué, cuándo y por qué (commits, branches, merges)
Líneas base formales: Snapshots aprobados que sirven como puntos de referencia auditables
Registros del CCB: Actas de aprobación/rechazo de solicitudes de cambio con justificación
Informes de estado: Reportes periódicos del estado de CIs y cambios realizados
Matriz de trazabilidad: Relaciona cambios con requisitos, pruebas y versiones desplegadas
El loop del gateway "¿Pruebas exitosas?" asegura que ningún cambio se integra a la línea base sin validación técnica, proporcionando evidencia de que los controles de calidad y seguridad se aplican consistentemente.
2.4.8 PROCESO 8: GESTIÓN DE RIESGOS
      2.4.8.1 Descripción del proceso
El proceso de Gestión de Riesgos establece un enfoque sistemático y proactivo para identificar, analizar, evaluar, tratar y monitorear los riesgos que pueden afectar los objetivos de los proyectos de TI y las operaciones, siendo crítico para el sector FinTech donde una gestión inadecuada podría resultar en pérdidas financieras, brechas de seguridad, incumplimiento regulatorio o daño reputacional. Este proceso abarca tanto riesgos técnicos (fallos de arquitectura, defectos de software) o problemas de rendimiento (riesgos de seguridad de la información, tales como vulnerabilidades, amenazas cibernéticas, accesos no autorizados o pérdida de datos), ejecutándose de manera continua a lo largo de todo el ciclo de vida del software, desde los requisitos hasta la operación en producción, y alimentándose de inteligencia de amenazas externa y del monitoreo activo de vulnerabilidades técnicas. Al ser transversal a todos los proyectos y servicios de TI, se integra estrechamente con la planificación de proyectos, el desarrollo seguro y la gestión de incidentes de seguridad, constituyendo un pilar fundamental para la toma de decisiones informadas y la protección de los activos de información críticos de InnovaTech y sus clientes.
      2.4.8.2 Propósito del proceso
El propósito del proceso de Gestión de Riesgos es establecer un enfoque sistemático que permita identificar proactivamente los riesgos técnicos y de seguridad con potencial de impactar los proyectos de TI, las operaciones y los objetivos estratégicos de InnovaTech; analizar y evaluar la probabilidad de ocurrencia e impacto de cada riesgo para priorizarlos según su criticidad; definir estrategias de tratamiento adecuadas (mitigar, transferir, aceptar o evitar) seleccionando controles de seguridad efectivos; implementar oportunamente dichos controles y verificar su eficacia; monitorear de forma continua los riesgos identificados, las amenazas emergentes y las vulnerabilidades técnicas; mantener inteligencia actualizada sobre amenazas del sector FinTech, vectores de ataque y vulnerabilidades conocidas; comunicar efectivamente los riesgos a los stakeholders para facilitar la toma de decisiones informadas; aprender de los incidentes materializados ajustando el registro con lecciones aprendidas; y asegurar el cumplimiento de los requisitos de gestión de riesgos de la ISO 27001:2022 (cláusulas 6.1.2 y 6.1.3) y las mejores prácticas internacionales.
      2.4.8.3 Entradas y salidas
              Entradas
El proceso de Gestión de Riesgos se alimenta de diversas entradas clave, entre las que se encuentran: el contexto del proyecto o servicio  que incluye alcance, arquitectura, tecnologías y objetivos, proveniente de la Planificación de Proyectos y el Diseño y Arquitectura ; los requisitos de seguridad en cuanto a confidencialidad, integridad y disponibilidad, definidos por la Gestión de Requisitos; el inventario de activos de información críticos y su clasificación, gestionado por Seguridad de la Información; las políticas y estándares de seguridad basados en controles como ISO 27002:2022; la inteligencia de amenazas externa del sector FinTech, obtenida de fuentes como CERT y proveedores especializados; los reportes de vulnerabilidades técnicas derivados de escaneos y análisis SAST/DAST, generados en Desarrollo y Operación; el registro de incidentes previos y sus lecciones aprendidas, procedente de la Gestión de Incidentes de Seguridad; los datos históricos de riesgos y efectividad de controles, almacenados en la base de conocimiento organizacional; el contexto regulatorio aplicable (PCI-DSS, GDPR, etc.), definido por el área legal; y los cambios organizacionales o tecnológicos significativos, comunicados por la Dirección o la Gestión de Configuración.
              Salidas
El proceso de Gestión de Riesgos genera como salidas principales el Registro de Riesgos, que consolida todos los riesgos identificados con su descripción, categoría, probabilidad, impacto y responsable; la Matriz de Riesgos que ofrece una representación visual de su criticidad; y el Plan de Tratamiento de Riesgos que define las estrategias, controles y responsables para cada riesgo. Adicionalmente, produce Declaraciones de Aceptación de Riesgos formalmente aprobadas, un Informe Ejecutivo de Evaluación para la dirección, Alertas de Amenazas Críticas para acción inmediata, y un Plan de Remediación de Vulnerabilidades técnico. Para el seguimiento, genera KPIs de efectividad y Reportes Periódicos de Monitoreo, mientras que las Lecciones Aprendidas de riesgos materializados y los nuevos Requisitos de Seguridad identificados alimentan los procesos de mejora continua y gestión de requisitos respectivamente, distribuyéndose estos resultados a todos los procesos involucrados, la dirección, los comités de seguridad y los stakeholders correspondientes.
      2.4.8.4 Roles
Roles de Gobernanza:
Oficial de Seguridad de la Información: Lidera la evaluación de riesgos de seguridad, define tratamiento de riesgos de seguridad, supervisa inteligencia de amenazas, aprueba aceptación de riesgos de seguridad, valida efectividad de controles de seguridad.
Comité de Riesgos y Seguridad: Revisa y aprueba el registro de riesgos corporativo, aprueba la aceptación de riesgos críticos/altos, define apetito y tolerancia al riesgo, asigna presupuesto para mitigación de riesgos y monitorea KPIs de gestión de riesgos.
Roles Técnicos Especializados:
Analista de Seguridad: Recolecta inteligencia de amenazas, ejecuta escaneos de vulnerabilidades, analiza reportes de vulnerabilidades, investiga amenazas emergentes, propone controles técnicos de mitigación y mantiene la base de conocimiento de amenazas.
Arquitecto de Seguridad: El proceso incluye la evaluación de riesgos arquitectónicos, la propuesta de controles de seguridad a nivel de diseño, la validación de que la arquitectura implementada mitigue efectivamente los riesgos identificados, y la participación activa en revisiones de diseño con especial enfoque en la gestión de riesgos.
Equipo de Desarrollo y Operaciones: Como parte integral del proceso, los responsables deben participar activamente en las sesiones de identificación de riesgos, proveer información técnica especializada sobre los riesgos detectados, implementar los controles técnicos que les sean asignados, y reportar de manera proactiva cualquier nuevo riesgo o cambio en los existentes que sea detectado durante la ejecución de sus actividades.
Roles de Gestión de tácticas:
Gestor de Riesgos: El responsable del proceso debe facilitar las sesiones de identificación de riesgos, consolidar y mantener actualizado el registro de riesgos, realizar el análisis y evaluación de cada riesgo considerando su probabilidad e impacto mediante métodos cualitativos y cuantitativos, proponer estrategias de tratamiento adecuadas, realizar el monitoreo continuo de la implementación de los controles, generar los reportes periódicos de gestión de riesgos, y coordinar estrechamente con el Oficial de Seguridad para el tratamiento de los riesgos específicos de seguridad de la información.
Dueño del Riesgo: El responsable final de gestionar un riesgo específico tiene la autoridad para autorizar e implementar los controles de mitigación correspondientes, lo cual implica monitorear de manera continua el riesgo asignado, reportar cualquier cambio en su estado, y además, dentro del ámbito de su autoridad, puede aceptar formalmente aquellos riesgos clasificados como bajos o medios.
Roles de Control Externo:
Auditor: Como parte de las funciones de auditoría y supervisión, se debe verificar el cumplimiento del proceso de gestión de riesgos, validar que estos se gestionen de acuerdo con los requisitos establecidos en la norma ISO 27001, evaluar la efectividad real de los controles implementados y, finalmente, reportar los hallazgos y cualquier no conformidad detectada para la toma de acciones correctivas y la mejora continua del sistema.
      2.4.8.5 Modelo del proceso en notación BPMN

      2.4.8.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
Integración ISO/IEC 12207:2017 - Procesos de Gestión de Proyectos
Risk Management Process (6.3.4): Define cómo identificar, analizar, tratar y monitorear riesgos a lo largo del ciclo de vida del software.
Integración ISO/IEC 27001:2022 - Requisitos del Sistema de Gestión de Seguridad de la Información
Evaluación de riesgos de seguridad de la información (6.1.2): La organización debe definir y aplicar un proceso de evaluación de riesgos de seguridad que establezca criterios de riesgos claros, asegure evaluaciones consistentes y comparables, identifique sistemáticamente los riesgos de seguridad, analice su probabilidad e impacto, evalúe su nivel de criticidad para priorizar las acciones necesarias, y se mantenga como un ciclo continuo de mejora.
Tratamiento de riesgos de seguridad de la información (6.1.3): La organización debe definir y aplicar un proceso de tratamiento de riesgos que seleccione las opciones de tratamiento apropiadas, determine todos los controles necesarios, compare dichos controles con los establecidos en la norma ISO 27002, produzca la Declaración de Aplicabilidad correspondiente, formule un plan de tratamiento integral y, finalmente, obtenga la aprobación formal de dicho plan por parte de los responsables autorizados.
Acciones para abordar riesgos y oportunidades (6.1.1): Determinar riesgos y oportunidades que deben abordarse.
Evaluación de riesgos de seguridad de la información (8.2): Realizar evaluaciones a intervalos planificados o cuando se propongan o produzcan cambios significativos.
Tratamiento de riesgos de seguridad de la información (8.3): Implementar el plan de tratamiento.
Seguimiento, medición, análisis y evaluación (9.1): Evaluar desempeño de seguridad y efectividad del SGSI.
Integración ISO/IEC 27002:2022 - Controles de Seguridad de la Información
Seguridad de la información en la gestión de proyectos (5.8): Integrar seguridad de la información en la gestión de proyectos, independientemente de la metodología utilizada.
Evaluación de riesgos de seguridad de la información (5.27): Identificar riesgos de seguridad asociados con los activos de información y evaluar su probabilidad e impacto.
Tratamiento de riesgos de seguridad de la información (5.28): Definir e implementar opciones de tratamiento para riesgos de seguridad (mitigar, transferir, aceptar, evitar).
Seguridad de la información durante la disrupción (5.29): Planificar cómo mantener la seguridad de la información durante eventos disruptivos.
2.4.9 PROCESO 9: GESTIÓN DE SEGURIDAD DE LA INFORMACIÓN
      2.4.9.1 Descripción del proceso
El proceso de Gestión de Seguridad de la Información tiene como finalidad establecer, implementar, operar y mejorar de forma continua los controles que aseguren la confidencialidad, integridad y disponibilidad de los activos de información de la organización.
El flujo inicia con la planificación del ciclo del SGSI, abarcando la revisión de políticas, roles y controles, la identificación de activos y la definición de accesos e identidades.
Durante la ejecución, el CISO coordina con las áreas de Riesgos, Desarrollo, RRHH y Entidades Externas la implementación y supervisión de medidas de seguridad, capacitación y auditorías internas.
Finalmente, el proceso culmina con la elaboración y validación del informe final SGSI, aprobado por la Alta Dirección, garantizando la trazabilidad y efectividad de las acciones de seguridad aplicadas en todo el ciclo.
      2.4.9.2 Propósito del proceso
El propósito del proceso es proteger los activos de información críticos mediante un marco integral de seguridad alineado con los requisitos organizacionales, legales y normativos.
Busca mantener la conformidad con el SGSI, integrar la seguridad en todas las etapas del ciclo de vida del software y fomentar una cultura organizacional orientada a la prevención y mejora continua.
Asimismo, garantiza que los riesgos de seguridad sean gestionados de forma proactiva, y que las políticas, controles y auditorías permitan sostener la confianza en los sistemas y servicios tecnológicos de la organización.
      2.4.9.3 Entradas y salidas
              Entradas
Mandato y objetivos del SGSI definidos por la Alta Dirección.
Políticas y procedimientos de seguridad existentes.
Inventario de activos de información.
Requisitos regulatorios y contractuales (clientes, auditores, normativas externas).
Resultados de la evaluación de riesgos (desde el Proceso 8).
Reportes de incidentes y lecciones aprendidas (desde el Proceso 10).
Matriz de roles y responsabilidades en seguridad.
Solicitudes de auditoría o cumplimiento normativo.
Resultados de auditorías previas.
              Salidas
Políticas y procedimientos actualizados del SGSI.
Matriz de clasificación y control de accesos (IAM).
Plan de capacitación y evidencias de formación en seguridad.
Plan de tratamiento y mitigación de riesgos.
Informes de auditoría interna y externa.
Acciones correctivas y planes de mejora implementados.
Informe final del SGSI validado por la Alta Dirección.
Retroalimentación de cumplimiento y recomendaciones de mejora.
      2.4.9.4 Roles
CISO / Responsable del SGSI: Lidera la implementación y mantenimiento del SGSI, coordina auditorías, evalúa cumplimiento normativo y aprueba planes de acción correctiva.

Alta Dirección / Gerencia TI: Define los objetivos y políticas del SGSI, aprueba actualizaciones y valida los informes finales del ciclo.

Equipo de Riesgos y Cumplimiento: Evalúa amenazas, vulnerabilidades y niveles de riesgo, emite planes de tratamiento y comunica resultados al CISO.

Equipos Técnicos (Desarrollo, QA, DevOps): Implementan controles técnicos, gestionan accesos, ejecutan pruebas de seguridad y reportan vulnerabilidades detectadas.

RRHH / Usuarios Internos: Ejecutan programas de capacitación, gestionan altas y bajas de personal, y reportan incidentes o comportamientos anómalos.

Auditor Externo / Entidades Regulatorias: Evalúan el cumplimiento del SGSI, revisan evidencias y emiten recomendaciones o requisitos contractuales.











      2.4.9.5 Modelo del proceso en notación BPMN























      2.4.9.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
ISO/IEC 12207:2017 – Procesos del ciclo de vida del software
El proceso de Gestión de Seguridad de la Información se sustenta en las buenas prácticas establecidas por las normas ISO/IEC 12207:2017, ISO/IEC 27001:2022 y ISO/IEC 27002:2022, las cuales orientan la gestión integral de la seguridad durante todo el ciclo de vida del software.
 El modelo diseñado integra la gestión de riesgos, la definición de políticas, la aplicación de controles técnicos y organizacionales, la auditoría y la mejora continua, asegurando la protección de los activos de información y la conformidad con los estándares internacionales.
Desde la ISO/IEC 12207:2017, el proceso se alinea con los apartados de gestión de riesgos, aseguramiento de la calidad y mantenimiento operativo, los cuales se reflejan en las actividades del CISO, el equipo de riesgos y los flujos de auditoría interna.
 Esto permite mantener la trazabilidad de decisiones, el control de cambios y la mejora continua de las prácticas de seguridad durante todo el ciclo del sistema.
La ISO/IEC 27001:2022 respalda el enfoque de gobernanza mostrado en el flujo entre la Alta Dirección y el CISO, donde se definen, aprueban y supervisan las políticas del SGSI.
 Asimismo, la planificación de controles, la revisión de auditorías y la validación final del informe SGSI reflejan la aplicación de los principios de liderazgo, operación controlada y revisión por la dirección establecidos en la norma.
2.4.10 PROCESO 10: GESTIÓN DE INCIDENTES DE SEGURIDAD
       2.4.10.1 Descripción del proceso
El proceso de Gestión de Incidentes de Seguridad establece las actividades necesarias para detectar, registrar, analizar, resolver y documentar los incidentes que afectan la confidencialidad, integridad o disponibilidad de la información. El flujo inicia con la detección o reporte del incidente por parte de usuarios o áreas internas, quienes comunican la alerta al CISO u Oficina SGSI. A partir de ello, se evalúa la severidad del incidente, se coordina con los equipos técnicos para su análisis y contención, y se implementan las acciones correctivas correspondientes. Finalmente, la Alta Dirección revisa y valida el cierre, y se genera una retroalimentación al SGSI (Proceso 9) con las lecciones aprendidas, fortaleciendo los controles y previniendo recurrencias.
       2.4.10.2 Propósito del proceso
El propósito del proceso es asegurar una respuesta estructurada, oportuna y eficaz ante incidentes de seguridad de la información, minimizando su impacto sobre los activos organizacionales y los servicios tecnológicos. Además, busca preservar la continuidad operativa, garantizar la comunicación y escalamiento adecuados, y promover la mejora continua mediante el aprendizaje obtenido en cada evento, integrándolo al SGSI institucional.
       2.4.10.3 Entradas y salidas
                Entradas
Notificación de incidente desde el Proceso 9 (Usuarios / RRHH).
Reportes de anomalías o eventos de seguridad detectados.
Políticas y procedimientos de gestión de incidentes.
Información del sistema de monitoreo o logs técnicos.
Evaluaciones previas de vulnerabilidades y riesgos.
Aprobación de medidas extraordinarias por parte de la Alta Dirección.
                Salidas
Registro formal del incidente y su clasificación por severidad.
Informe técnico del análisis de causa raíz.
Acciones correctivas y preventivas aplicadas.
Reporte de cierre del incidente.
Lecciones aprendidas y evidencias documentadas.
Retroalimentación al Proceso 9 (actualización de controles del SGSI).
       2.4.10.4 Roles
Usuarios / RRHH: Detectan y reportan incidentes o anomalías, colaboran en la recopilación de información y en la aplicación de medidas de aislamiento temporal.

CISO / Oficina SGSI: Evalúa y clasifica los incidentes, coordina la respuesta, gestiona la comunicación con equipos técnicos y Alta Dirección, valida el cierre y actualiza los controles del SGSI.

Equipos Técnicos (TI / Desarrollo / QA): Analizan la causa raíz, aplican medidas de contención y corrección, y reportan resultados técnicos al CISO.

Alta Dirección: Autoriza recursos o acciones extraordinarias para incidentes críticos, revisa el informe final y aprueba las lecciones aprendidas para su integración al SGSI.
       2.4.10.5 Modelo del proceso en notación BPMN













       2.4.10.6 Sustento de prácticas ISO 12207:2017, ISO 27001:2022 e ISO 27002:2022
Desde la ISO/IEC 12207:2017, el proceso refleja las actividades de gestión de riesgos, soporte y mantenimiento operativo, al abordar la detección, tratamiento y control de incidentes dentro del ciclo de vida del software. Las tareas de análisis técnico, evaluación de impacto y acciones correctivas demuestran la aplicación del principio de gestión reactiva controlada, garantizando trazabilidad y retroalimentación continua hacia la mejora del producto y sus servicios.
La ISO/IEC 27001:2022 respalda el flujo a través de las cláusulas de planificación, operación y evaluación del SGSI, evidentes en la clasificación de incidentes, la ejecución de auditorías internas y la retroalimentación hacia el Proceso 9. El modelo promueve la comunicación efectiva entre usuarios, CISO, equipos técnicos y Alta Dirección, cumpliendo con los principios de liderazgo, control y mejora continua del sistema de seguridad.
Por su parte, la ISO/IEC 27002:2022 se ve reflejada en los controles 5.24 a 5.27, que regulan la gestión de incidentes de seguridad de la información: detección, respuesta, aprendizaje y mejora.
En el modelo, estas prácticas se materializan en la secuencia detección, análisis, resolución,  validación, lecciones aprendidas, asegurando la contención de daños y la incorporación de medidas preventivas. Asimismo, se aplican los controles de monitoreo (8.15–8.16) y continuidad operativa (8.28–8.29) al vincular la respuesta técnica con el CISO, garantizando la recuperación y la disponibilidad de los servicios críticos.


CAPÍTULO 3: MODELAMIENTO DE PROCESOS DE DESARROLLO DE SOFTWARE INCLUYENDO MÉTRICAS, AUTOMATIZACIÓN Y PRÁCTICAS DEL MODELO CMMI
3.1 PROCESO 1: GESTIÓN DE REQUISITOS
    3.1.1 Modelo actualizado del proceso en notación BPMN

Nuevas actividades para integrar en el diagrama BPMN (CMMI v2.0):
El proceso original de Gestión de Requisitos contaba con 20 actividades básicas distribuidas en 8 carriles:
Actividades principales:
Recibir necesidad inicial
Realizar refinación de historias
Documentar requisitos
Priorizar requisitos funcionales y no funcionales
Especificar requisitos (SGSI/Baseline)
Ajustar especificación con stakeholders
Validar viabilidad arquitectónica
Verificar factibilidad técnica
Identificar requisitos de seguridad
Clasificar información sensible
Evaluar riesgos del proyecto
Resolver conflictos identificados
Crear criterios de aceptación
Diseñar plan de validación
Crear matriz de trazabilidad
Integrar requisitos al plan de proyecto
Actualizar backlog/prioridades
Elementos de control:
3 gateways de decisión
2 loops de refinamiento
Limitaciones identificadas:
No existía evaluación formal de alternativas para requisitos complejos
Faltaba verificación sistemática contra criterios establecidos
No se validaban requisitos formalmente con stakeholders
No se capturaban métricas del proceso de requisitos
No se analizaba el impacto de cambios de forma estructurada
No existía gestión formal de cambios de requisitos
No se verificaba el cumplimiento del proceso
No se documentaban lecciones aprendidas
PROCESO DE GESTIÓN DE REQUISITOS - DESPUÉS (Hito 2)
El proceso mejorado incorpora 8 prácticas CMMI v2.0, elevando el total a 28 actividades:
Nuevas prácticas CMMI v2.0 integradas:
Evaluar alternativas de requisitos (DAR) - Después de ajustar especificación
Verificar requisitos contra criterios (VER) - Después de consolidar validaciones técnicas
Validar requisitos con stakeholders (VAL) - Después de diseñar plan de validación
Capturar métricas de requisitos (MA) - Después de crear matriz de trazabilidad
Analizar impacto de cambios (RD) - Después de capturar métricas
Gestionar cambios de requisitos (REQM) - En el carril de Gestión de Configuración
Verificar cumplimiento del proceso REQM (PQA) - Después de validar versión de requisitos
Documentar lecciones aprendidas (PCM) - Antes de finalizar el proceso
Mejoras cuantificables:
+8 prácticas de madurez de procesos
+40% de actividades de aseguramiento de calidad
Cobertura completa de verificación, validación y gestión de cambios
Trazabilidad mejorada con análisis de impacto
Métricas definidas para mejora continua
    3.1.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
PROCESO: GESTIÓN DE REQUISITOS
A continuación se detalla el sustento técnico de cada una de las 8 prácticas del modelo CMMI v2.0 incorporadas al proceso de Gestión de Requisitos de InnovaTech Solutions:
1. DAR - Decision Analysis and Resolution
Ubicación: CARRIL 2 - Analista de Negocio/Product Owner
 Actividad: Evaluar alternativas de requisitos (DAR)
 Posición en el flujo: Después de "Ajustar especificación con stakeholders"
Sustento de incorporación:
La práctica DAR se incorpora en este punto crítico del proceso porque, tras el refinamiento y ajuste con stakeholders, pueden surgir requisitos complejos o conflictivos que admiten múltiples soluciones. Esta práctica del CMMI v2.0 permite:
Evaluar formalmente diferentes alternativas para resolver requisitos ambiguos o contradictorios
Aplicar criterios establecidos para seleccionar la mejor opción técnica y de negocio
Documentar la justificación de las decisiones tomadas sobre requisitos críticos
Reducir riesgos asociados a decisiones apresuradas o no fundamentadas
Según CMMI v2.0, DAR es fundamental para asegurar que las decisiones sobre requisitos estén basadas en análisis objetivo y no en preferencias personales o decisiones arbitrarias.
2. VER - Verification
Ubicación: CARRIL 5 - QA/Testing
 Actividad: Verificar requisitos contra criterios (VER)
 Posición en el flujo: Después de "Consolidar validaciones técnicas"
Sustento de incorporación:
La práctica VER se integra inmediatamente después de las validaciones técnicas (arquitectura y desarrollo) porque es el momento adecuado para verificar que los requisitos cumplan con los criterios establecidos. Esta práctica CMMI v2.0 garantiza:
Verificación sistemática de que los requisitos cumplen con estándares de calidad definidos
Detección temprana de requisitos mal especificados, ambiguos o incompletos
Cumplimiento de criterios de completitud, consistencia, verificabilidad y trazabilidad
Reducción de defectos al identificar problemas antes de la implementación
CMMI v2.0 establece que la verificación debe realizarse por un rol independiente (QA), asegurando objetividad en la evaluación de la calidad de los requisitos.
3. VAL - Validation
Ubicación: CARRIL 5 - QA/Testing
 Actividad: Validar requisitos con stakeholders (VAL)
 Posición en el flujo: Después de "Diseñar plan de validación"
Sustento de incorporación:
La práctica VAL se incorpora después de crear criterios de aceptación y diseñar el plan de validación porque es el momento donde se debe confirmar que los requisitos realmente satisfacen las necesidades del usuario final. Esta práctica CMMI v2.0 asegura:
Validación con usuarios reales de que los requisitos resuelven el problema de negocio
Confirmación temprana de que el producto cumplirá las expectativas del cliente
Retroalimentación directa de stakeholders sobre la adecuación de los requisitos
Prevención de retrabajo al validar antes de comenzar el desarrollo
CMMI v2.0 diferencia claramente entre verificación (¿construimos el producto correctamente?) y validación (¿construimos el producto correcto?). Esta práctica responde a la segunda pregunta.
4. MA - Measurement and Analysis
Ubicación: CARRIL 2 - Analista de Negocio/Product Owner
 Actividad: Capturar métricas de requisitos (MA)
 Posición en el flujo: Después de "Crear matriz de trazabilidad"
Sustento de incorporación:
La práctica MA se integra en este punto porque, una vez establecida la matriz de trazabilidad, se tiene la visibilidad completa del proceso de requisitos para capturar métricas significativas. Esta práctica CMMI v2.0 permite:
Capturar métricas clave del proceso: % de completitud de requisitos, tiempo de refinamiento, tasa de cambios, volatilidad de requisitos
Establecer baseline cuantitativo del desempeño del proceso de gestión de requisitos
Identificar tendencias y patrones que permitan mejorar el proceso
Tomar decisiones basadas en datos sobre la madurez del proceso
CMMI v2.0 establece que sin medición objetiva es imposible gestionar y mejorar los procesos de forma sistemática. Esta práctica es fundamental para la mejora continua.
5. RD - Requirements Development
Ubicación: CARRIL 2 - Analista de Negocio/Product Owner
 Actividad: Analizar impacto de cambios (RD)
 Posición en el flujo: Después de "Capturar métricas de requisitos (MA)"
Sustento de incorporación:
La práctica RD se incorpora después de capturar métricas porque es el momento de analizar cómo los cambios propuestos en requisitos impactan otros requisitos y al sistema completo. Esta práctica CMMI v2.0 garantiza:
Análisis de impacto sistemático de cambios en requisitos sobre otros requisitos, arquitectura, cronograma y costos
Identificación de dependencias entre requisitos que podrían verse afectadas por cambios
Evaluación de riesgos asociados a modificaciones en requisitos establecidos
Documentación de consecuencias antes de aprobar cambios
CMMI v2.0 reconoce que los requisitos evolucionan durante el proyecto, y RD proporciona las prácticas para gestionar esa evolución de forma controlada y predecible.
6. REQM - Requirements Management
Ubicación: CARRIL 7 - Gestión de Configuración
 Actividad: Gestionar cambios de requisitos (REQM)
 Posición en el flujo: Después de "Analizar impacto de cambios (RD)"
Sustento de incorporación:
La práctica REQM se integra en el carril de Gestión de Configuración porque es donde se debe gestionar formalmente los cambios aprobados en requisitos. Esta práctica CMMI v2.0 asegura:
Gestión formal de cambios con control de versiones y trazabilidad bidireccional
Mantenimiento de consistencia entre requisitos y otros work products (diseño, código, pruebas)
Control de baseline de requisitos con historial de cambios
Comunicación efectiva de cambios a todos los stakeholders afectados
CMMI v2.0 establece que REQM es la práctica central para mantener la integridad de los requisitos a lo largo del ciclo de vida del proyecto, asegurando que todos trabajen con la versión correcta.
7. PQA - Process Quality Assurance
Ubicación: CARRIL 5 - QA/Testing
 Actividad: Verificar cumplimiento del proceso REQM (PQA)
 Posición en el flujo: Después de "Validar versión de requisitos"
Sustento de incorporación:
La práctica PQA se incorpora después de validar la versión de requisitos porque es el momento de verificar que todo el proceso de gestión de requisitos se ejecutó correctamente. Esta práctica CMMI v2.0 garantiza:
Auditoría del cumplimiento del proceso definido de gestión de requisitos
Verificación de adherencia a estándares y procedimientos establecidos
Identificación de desviaciones del proceso planificado
Reporte a gestión sobre el cumplimiento del proceso
CMMI v2.0 establece que PQA debe ser realizado por un rol independiente (QA) para asegurar objetividad. Esta práctica es esencial para mantener la disciplina de proceso en la organización.
8. PCM - Process and Product Quality Management
Ubicación: CARRIL 8 - PMO/Gestión de Proyectos
 Actividad: Documentar lecciones aprendidas (PCM)
 Posición en el flujo: Después de "Integrar requisitos al plan de proyecto"
Sustento de incorporación:
La práctica PCM se integra al final del proceso porque es el momento de capturar el aprendizaje organizacional sobre la ejecución del proceso de requisitos. Esta práctica CMMI v2.0 permite:
Capturar lecciones aprendidas sobre qué funcionó bien y qué se puede mejorar
Documentar problemas encontrados y cómo se resolvieron
Generar recomendaciones para futuras iteraciones del proceso
Alimentar la mejora continua del proceso de gestión de requisitos
CMMI v2.0 reconoce que la madurez organizacional se construye sobre la capacidad de aprender sistemáticamente de cada ejecución de los procesos. PCM es la práctica que cierra el ciclo de mejora continua.
3.2 PROCESO 2: DISEÑO Y ARQUITECTURA 
    3.2.1 Modelo actualizado del proceso en notación BPMN

Nuevas actividades para integrar en el diagrama BPMN (CMMI v2.0):
Antes de “Definir estructura del sistema”
Actividad: Consultar repositorio OPD
CMMI: OPD
Se revisan las plantillas, lineamientos, patrones aprobados y activos organizacionales del repositorio OPD antes de iniciar el diseño.
Durante el diseño conceptual
Actividad: Evaluar alternativas arquitectónicas
CMMI: DAR
En esta fase se analizan diversas opciones arquitectónicas (por ejemplo: monolito vs. microservicios, REST vs. GraphQL, SQL vs. NoSQL).
Durante el diseño conceptual
Actividad: Definir métricas de arquitectura
CMMI: MA
Se establecen indicadores que permitirán medir la calidad del diseño y su comportamiento esperado.
Durante el diseño detallado
Actividad: Integrar controles de seguridad
CMMI: SAM + Engineering + Security Practices
Aquí se incorporan explícitamente patrones y controles de seguridad dentro del diseño detallado.
Antes de la aprobación
Actividad: Validar cumplimiento de estándares OPD
CMMI: PQA
Se revisa que el documento de diseño cumpla los estándares definidos por la organización.
Después de aprobar
Actividad: Registrar decisiones arquitectónicas
CMMI: PCM
Las decisiones clave del diseño (por qué se eligió un framework, patrón, tecnología o modelo de despliegue) se documentan en un registro formal.
Al finalizar
Actividad: Actualizar OPD con activos creados
CMMI: OPD
Los activos generados en el proyecto (diagramas, plantillas optimizadas, prácticas mejoradas, patrones reutilizables) se incorporan al repositorio OPD para fortalecer el aprendizaje organizacional.
    3.2.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
OPD (Organizational Process Definition): uso y actualización del repositorio de activos.
DAR (Decision Analysis and Resolution): evaluación estructurada de alternativas técnicas.
MA (Measurement & Analysis): establecimiento de métricas arquitectónicas.
ENG (Engineering): desarrollo de diseño conceptual y detallado.
VER (Verification): verificación de requisitos no funcionales y estándares técnicos.
SAM (Supplier Agreement Management): controles de seguridad y cumplimiento nico.
PCM (Process Management): registro de decisiones y lecciones aprendidas.
PQA (Process Quality Assurance): cumplimiento de estándares organizacionales.
Evidencia de madurez CMMI: El proceso cumple prácticas típicas de nivel 3, porque:
Usa activos de proceso estándar (OPD).
Integra análisis formal de alternativas (DAR)
Establece métricas formales (MA).
Estandariza la verificación técnica y de seguridad (VER).
3.3 PROCESO 3: DESARROLLO E IMPLEMENTACIÓN
    3.3.1 Modelo actualizado del proceso en notación BPMN

Nuevas actividades para integrar en el diagrama BPMN (CMMI v2.0):
Antes de “Implementar módulos según el DDT”
Actividad: Revisar estándares de codificación segura
CMMI: PQA
Asegura que todos los desarrolladores apliquen las guías organizacionales de calidad y seguridad desde el inicio, evitando riesgos y retrabajo.
Durante la implementación de módulos
Actividad: Evaluar alternativas técnicas de implementación y justificar decisión
CMMI: DAR
Permite comparar enfoques de codificación considerando costo, rendimiento, mantenibilidad y seguridad antes de elegir la solución final.
Durante el ciclo de commits y builds
Actividad: Ejecutar análisis estático automatizado (SonarQube, SAST)
CMMI: VER
Detecta defectos y vulnerabilidades temprano, garantizando que cada cambio cumpla criterios de aceptación definidos por la organización.
Después de generar el build de integración
Actividad: Revisar seguridad del build y dependencias (OWASP, SCA)
CMMI: SAM
Valida que las librerías externas, frameworks y componentes de terceros no introduzcan vulnerabilidades o incompatibilidades.
Antes del cierre del desarrollo
Actividad: Registrar decisiones técnicas relevantes
CMMI: PCM
Documenta las razones detrás de decisiones de arquitectura, patrones, librerías y cambios significativos para mantener trazabilidad y conocimiento organizacional.
Al finalizar el proceso de desarrollo
Actividad: Actualizar el repositorio OPD (estándares, plantillas, guías técnicas)
CMMI: OPD
Fortalece la mejora continua alimentando el repositorio organizacional con activos nuevos o actualizados derivados del proyecto.
    3.3.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
ENG (Engineering): Abarca la implementación del software siguiendo el diseño técnico, buenas prácticas de programación y principios de ingeniería segura.
VER (Verification): Se aplica en análisis estático, pruebas unitarias y pruebas de integración, verificando la calidad del código y el cumplimiento de criterios técnicos.
SAM (Supplier Agreement Management): Reflejado en la revisión de dependencias externas y en la validación de componentes de terceros utilizados en el desarrollo.
DAR (Decision Analysis and Resolution): Implementado al evaluar alternativas de implementación y justificar decisiones técnicas durante la codificación.
PQA (Process Quality Assurance): Garantizado mediante la revisión previa de estándares de codificación segura y el monitoreo del cumplimiento de guías organizacionales.
OPD (Organizational Process Definition): Se evidencia en el uso de plantillas, estándares y guías técnicas del repositorio, y en la actualización de estos activos al finalizar el proceso.
PCM (Process Management): Incluye documentación de decisiones técnicas y lecciones aprendidas para fortalecer la capacidad organizacional.
Evidencia de madurez CMMI: El proceso está alineado a Nivel 3, porque:
Usa estándares OPD y lineamientos organizacionales
Incorpora calidad mediante PQA y VER
Documenta decisiones (PCM)
Evalúa alternativas técnicas (DAR)
Aplica automatización sistemática mediante CI/CD
Integra seguridad desde el diseño hasta el release (SAM)
    3.3.3 Descripción formal escrita del proceso
Nombre del proceso: Desarrollo e Implementación
Objetivo: Construir, integrar y preparar el software para su liberación formal, aplicando estándares técnicos, prácticas de codificación segura, verificaciones automatizadas y controles de calidad que garanticen confiabilidad, trazabilidad, seguridad y cumplimiento del diseño técnico aprobado.
Alcance: Inicia cuando el equipo recibe el Diseño Detallado Técnico (DDT) aprobado y finaliza con la generación del build estable, documentado y registrado en la línea base técnica del proyecto.
Disparador de inicio: Recepción del DDT aprobado por Arquitectura y Gestión de Configuración.
Criterios de entrada
Diseño Detallado Técnico (DDT) aprobado
Lineamientos de codificación segura establecidos por Seguridad y PQA
Estándares técnicos y plantillas del repositorio OPD
Dependencias técnicas validadas
Descripción detallada de los procesos:
FASE 1: PREPARACIÓN DE ENTORNOS
1. Configurar entornos de desarrollo y pruebas
Rol: DevOps
El equipo prepara los entornos necesarios para implementar, probar e integrar los componentes:
Configuración de contenedores o máquinas virtuales
Instalación de runtimes, frameworks y SDKs
Configuración de variables de entorno y credenciales
Conexión segura con servicios externos (bases de datos, APIs, colas de eventos)
Esto garantiza que el equipo cuente con un ambiente estable y homogéneo desde el inicio.
2. Configurar pipelines CI/CD
Rol: DevOps / Ingeniero de Automatización
Se construyen los pipelines de integración continua para:
Compilar código
Ejecutar pruebas unitarias
Ejecutar análisis estático (SonarQube)
Generar builds transitorios
Aplicar quality gates
Registrar resultados para auditorías técnicas
Integra prácticas CMMI: VER (Verification).
3. Revisar estándares de codificación segura (PQA)
Rol: Desarrollador Senior + Especialista PQA
Antes de escribir una sola línea de código, el equipo revisa:
Reglas de seguridad de OWASP
Estándares de codificación de la organización
Prácticas de evitación de vulnerabilidades (inyección, exposición de datos, etc.)
Guía de revisiones de código definidas en OPD
Propósito: garantizar que el equipo arranque alineado con patrones seguros y con criterios homogéneos.
Salida de la fase: Entornos listos, pipeline funcionando y equipo alineado a estándares y guías de codificación.
FASE 2: IMPLEMENTACIÓN
1. Implementar módulos funcionales
Rol: Equipo de Desarrollo
El desarrollador implementa cada módulo o user story basado en el DDT:
Patrones arquitectónicos definidos
Interfaces, DTOs y contratos establecidos
Reglas de negocio
Manejo de errores
Logs estandarizados
Seguridad según los flujos definidos
Se mantienen prácticas de commits frecuentes con mensajes claros y trazables.
2. Aplicar programación segura
Rol: Desarrollador
Incluye:
Sanitización de entradas
Validación estricta de parámetros
Manejo seguro de credenciales
Minimización de superficies de ataque
Aplicación de controles definidos en la fase de diseño (SAM + ENG)
3. Evaluar alternativas técnicas de implementación y justificar decisión (CMMI DAR)
Rol: Desarrollador Senior / Líder Técnico
Cada vez que surge una decisión de implementación no trivial (elección de patrón, uso de librería, estrategia de optimización), se evalúan opciones considerando:
Complejidad
Performance
Seguridad
Costo técnico (deuda)
Mantenibilidad
La decisión queda documentada en el registro de decisiones técnicas.
Salida de la fase: Código funcional, seguro y alineado al diseño técnico aprobado.
FASE 3: VERIFICACIÓN
1. Ejecutar análisis estático (VER)
Rol: Pipeline CI / DevOps
Cada commit dispara:
Análisis de vulnerabilidades (SAST)
Code smells
Cobertura mínima establecida
Patrón de dependencias prohibidas
Validación de estándares OPD
Si no cumple el quality gate, el build se rechaza automáticamente.
2. Ejecutar pruebas unitarias
Rol: Desarrollador + QA Técnico
Cada módulo incorpora pruebas automatizadas con:
Cobertura mínima (generalmente ≥ 80%)
Mocking de dependencias
Aserciones de seguridad y validaciones de input
Pruebas de regresión mínimas
3. Gateway de calidad técnica
Rol: DevOps + QA Técnico
Preguntas evaluadas:
¿El build pasa análisis estático?
¿La cobertura mínima está cumplida?
¿No existen vulnerabilidades críticas abiertas?
¿Se cumplen estándares de codificación segura?
Si NO → La tarea vuelve a IMPLEMENTACIÓN.
Salida de la fase: Código verificado, sin vulnerabilidades críticas y sin incumplimientos técnicos.
FASE 4: INTEGRACIÓN Y RELEASE
1. Integrar componentes y ejecutar pruebas de integración
Rol: QA Técnico + Desarrolladores
Se combinan los módulos en un build de integración y se ejecutan:
Pruebas automatizadas API
Pruebas de regresión
Pruebas de integración con base de datos
Validaciones contractuales (contract testing)
2. Revisión de seguridad del build y dependencias (SAM)
Rol: CISO / Especialista de Seguridad
Incluye revisión de:
Versiones vulnerables de librerías externas
Dependencias con licencias no aprobadas
Escaneo OWASP Dependency Check
Políticas de firma y verificación de componentes
3. Generación de release candidate y aprobación técnica
Rol: QA Técnico + Arquitecto
El build pasa auditoría técnica final antes de declararse "estable".
Salida de la fase: Build estable, probado, seguro y aprobado técnicamente.
FASE 5: DOCUMENTACIÓN Y CIERRE
1. Registrar decisiones técnicas (PCM)
Rol: Líder Técnico / Desarrollador Senior
Se documentan:
Alternativas evaluadas
Justificación
Riesgos
Impacto en arquitectura
Implicancias en mantenibilidad y performance
Aporta trazabilidad y aprendizaje organizacional.
2. Actualizar documentación técnica
Rol: Equipo Técnico
Incluye:
Esquemas de endpoints
Especificaciones de pruebas
Diagrama actualizado del componente
Variables de configuración
Manual técnico del build
3. Actualizar OPD con activos creados (OPD)
Rol: Gestión de Procesos
Se suben los activos generados:
Nuevos scripts reutilizables
Plantillas mejoradas
Métricas y resultados
Estándares ajustados
Lecciones aprendidas técnicas
Esto fortalece el repositorio institucional.
4. Registrar lecciones aprendidas
Rol: Todo el equipo
Se documenta qué funcionó, qué falló y qué debe ajustarse en futuros desarrollos.
Salida de la fase: Artefactos, documentación actualizada y cierre técnico formal.
Criterio de salida del proceso
Build estable aprobado
0 vulnerabilidades críticas
Documentación técnica completa
OPD actualizado
Registro de decisiones técnicas completado
Lecciones aprendidas integradas
Evidencias de quality gates almacenadas
    3.3.4 Métricas para evaluar el desempeño del proceso
Métrica 1: Densidad de Defectos (DD – Defect Density)
La métrica Densidad de Defectos mide la cantidad de defectos encontrados por cada mil líneas de código (KLOC). Permite evaluar qué tan limpio y estable es el código implementado, considerando que un software con menor densidad de defectos tiende a ser más confiable, mantenible y seguro.
Fórmula: 
DD = Nº total de defectos / KLOC (miles de líneas de código)
Objetivos:
Meta: < 2 defectos por KLOC
Umbral aceptable: < 3 defectos por KLOC
Umbral crítico: ≥ 4 defectos por KLOC (requiere acción inmediata)
Frecuencia de medición:
Semanal durante fases activas de desarrollo
Al final de cada sprint
Revisión global al cierre del proceso de desarrollo
Método de recolección de datos:
QA registra defectos encontrados durante pruebas unitarias, integración y smoke test.
DevOps calcula el tamaño del build (líneas de código) usando herramientas como:
cloc
sonar-scanner
GitLens
Se normaliza el valor a miles de líneas (KLOC).
Se calcula la densidad agrupando los defectos por build o sprint.
Ejemplo práctico:
Supongamos que durante un sprint se generó un nuevo build del backend.
Líneas de código del módulo: 12,500 LOC → 12.5 KLOC
Defectos encontrados por QA: 28 defectos
Aplicando la fórmula:
DD = 28 / 12.5 = 2.24 defectos/KLOC
Interpretación del ejemplo:
Resultado: 2.24 defectos/KLOC
Está por encima del objetivo (< 2), pero dentro del umbral aceptable (< 3).
Requiere atención del equipo, pero no es crítico.
Acciones según resultado:
DD ≤ 2 (Verde):
Código de calidad óptima.
Mantener prácticas y reconocer buenas decisiones técnicas.
2 < DD < 3 (Amarillo):
Revisar áreas donde los defectos se concentran.
Realizar revisión extra con pair programming.
Aplicar análisis estático más estricto.
DD ≥ 3 (Rojo):
Detener integración y realizar corrección obligatoria.
Identificar causa raíz (metodología 5 Whys o Ishikawa).
Programar refactorización.
Incrementar cobertura de pruebas unitarias.
Beneficios:
Permite comparar calidad entre builds, módulos o equipos.
Detecta tendencias de deterioro técnico antes de que se vuelvan críticas.
Reduce costos futuros de mantenimiento y retrabajo.
Apoya auditorías técnicas CMMI (VER + MA).


Métrica 2: Cumplimiento del Quality Gate (QG – Quality Gate Compliance)
El Quality Gate mide qué porcentaje de los builds generados cumplen los criterios mínimos de calidad definidos por la organización, los cuales pueden incluir:
Sin vulnerabilidades críticas
Sin code smells severos
Cobertura ≥ 80%
Seguridad de librerías externas aprobada
Sin duplicación excesiva
Cumplimiento de estándares OPD y PQA
Es una métrica clave para evaluar la disciplina técnica del equipo.
Fórmula:
QG = Nº de builds aprobados / Nº de builds ejecutados
Objetivos:
Meta: ≥ 95%
Umbral aceptable: ≥ 90%
Umbral crítico: < 90% (indica problemas de calidad profunda)
Frecuencia de medición:
Automática por cada build CI
Consolidación semanal y por sprint
Evaluación final al cierre del proceso
Método de recolección:
SonarQube y CI/CD registran automáticamente el estado de cada build.
DevOps exporta reportes (Aprobado / Fallado).
Se calcula el porcentaje consolidado.
Los datos se guardan como evidencia de PQA + VER para auditorías.
Ejemplo práctico:
Durante la tercera semana de desarrollo:
Builds ejecutados: 40
Builds aprobados por Quality Gate: 35
Aplicamos la fórmula:
QG = 35 / 40 = 0.875 = 87.5%
Interpretación del ejemplo:
Resultado: 87.5%
Está por debajo del umbral crítico (< 90%).
Indica que hay un problema fuerte de calidad o disciplina técnica.
El equipo debe realizar correcciones inmediatas.
Acciones según resultado:

QG ≥ 95% (Verde):
Buen nivel de disciplina.
Indica un proceso de desarrollo estable y maduro.
90% ≤ QG < 95% (Amarillo):
Revisar módulos con mayor fallas.
Perfeccionar pruebas unitarias y estáticas.
Alinear devs en estándares de codificación.
QG < 90% (Rojo):
Activar análisis de causa raíz.
Revisar estándares no cumplidos.
Hacer sesiones de hardening técnico.
Ajustar pipeline y pruebas automatizadas.
Revisar prácticas de revisión de código.
Beneficios:
Reduce retrabajo y fugas de defectos.
Asegura que solo builds técnicamente sólidos avancen.
Impulsa la madurez en ingeniería (ENG + VER + PQA).
Facilita auditorías CMMI y ISO 12207.
Incrementa predictibilidad en el proceso de desarrollo.
    3.3.5 Herramientas de automatización
Herramienta 1: GitHub / GitLab CI
Actividades:
Compilación
Pruebas unitarias
Análisis estático
Deploy automatizado
Beneficios:Reduce errores manuales, acelera ciclos y genera trazabilidad.
Herramienta 2: SonarQube + SAST
Actividades:
Análisis estático
Evaluación de seguridad
Quality gates
Beneficios: Evita vulnerabilidades y reporta riesgos en fases tempranas.
3.4 PROCESO 4: VERIFICACIÓN, VALIDACIÓN Y TRANSICIÓN
    3.4.1 Modelo actualizado del proceso en notación BPMN

Nuevas actividades para integrar en el diagrama BPMN (CMMI v2.0):
Antes de preparar Criterios de Aceptación
Actividad: Desarrollar Estrategia de Prueba de Seguridad (Nivel 3)
CMMI: ESEC
Garantiza que las actividades de seguridad se integren formalmente en la planificación, asegurando la mitigación proactiva del riesgo desde las fases tempranas del V&V.
Antes de ejecutar pruebas funcionales
Actividad: Seleccionar Muestra de Pruebas críticas (Nivel 4)
CMMI: DAR
Aumenta la objetividad y la probabilidad de seleccionar la solución óptima, aplicando criterios ponderados para priorizar las pruebas más importantes, optimizando el esfuerzo de QA.
Durante ejecución de pruebas funcionales
Actividad: Monitorizar métricas y umbrales (QPPOs)
CMMI: CAR
Permite tomar decisiones de continuación del proyecto basadas en datos objetivos comparados con umbrales cuantitativos (QPPOs), asegurando la predecibilidad del rendimiento del proceso (Nivel 4).
Después de monitorear métricas
Actividad: Analizar causa raíz (CAR) de desviación cuantitativa
CMMI: CAR
Permite identificar y eliminar la causa raíz de la variación del proceso mediante técnicas estadísticas, transformando un problema de defecto en una oportunidad de mejora sostenida.
Antes de registrar Línea Base Lista para Producción
Actividad: Auditar cumplimiento de Proceso (PQA)
CMMI: PQA
Incrementa el uso consistente y la mejora de los procesos al verificar objetivamente que el proceso de V&V se siguió correctamente.
Al finalizar el proceso
Actividad: Contribuir Activos y Lecciones Aprendidas de V&V (PAD)
CMMI: PAD
Proporciona la capacidad para entender y repetir un desempeño exitoso, asegurando que la experiencia obtenida se almacena en el repositorio organizacional para su reutilización y mejora.
    3.4.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
VV(Verification and Validation): Se ejecuta contra un plan detallado y establecido
MPM (Managing Performance and Measurement): Las decisiones sobre la continuación del proyecto se basan en datos (DDP, Test Coverage).
CAR (Causal Analysis and Resolution): La organización identifica y corrige la fuente de la variación del proceso evitando retrabajo futuro.
DAR (Decision Analysis and Resolution): Evaluar alternativas cumpliendo con el Nivel 2.
PQA (Process Quality Assurance): Formaliza la calidad en la ejecución.
PAD (Process Asset Development): La experiencia obtenida es almacenada y reutilizada en futuros proyectos, impulsando la mejora continua.

El proceso cumple con prácticas de Nivel 4 porque:
Se establece el uso de Umbrales Cuantitativos (QPPOs) y activa el Análisis de Causa Raíz (CAR) cuando las métricas de desempeño son incumplidas.
Las actividades de Auditoría PQA y el Gate de Gobernanza aseguran que el proceso es formalmente definido y consistente.
La selección de Muestra Crítica (DAR) y la integración de seguridad aseguran que la solución sea óptima y segura.
3.5 PROCESO 5: OPERACIÓN Y MANTENIMIENTO 
    3.5.1 Modelo actualizado del proceso en notación BPMN

Nuevas actividades para integrar en el diagrama BPMN (CMMI v2.0):
Durante la Operación
Actividad: Monitorear Amenazas y Vulnerabilidades
CMMI: MST
Formaliza la gestión de seguridad como un proceso activo y continuo, asegurando que la organización identifica y prioriza amenazas para evitar interrupciones.
Durante el Análisis de Solicitud
Actividad: Coordinar Soporte de Proveedor Externo
CMMI: SAM
Minimiza el riesgo en la cadena de suministro, asegurando que el proveedor se desempeñe según las condiciones del acuerdo y que su calidad sea controlada (Nivel 2).
Después de Analizar la solicitud
Actividad: Evaluar Riesgos de Seguridad  y Aprobar Tratamiento
CMMI: ESEC
Garantiza que todo cambio o incidente se evalúe por su impacto antes de la implementación, cumpliendo con el enfoque de riesgo de ISO 27001.
Durante el monitoreo
Actividad: Realizar Escaneo de Vulnerabilidades (Post Deploys)
CMMI: MST
Verificar objetivamente la efectividad de las acciones de mantenimiento y asegurar que no se hayan introducido nuevas vulnerabilidades en el sistema productivo.
Al finalizar el proceso
Actividad: Archivar reportes y lecciones aprendidas
CMMI: PAD
Proporciona la capacidad de entender y repetir un desempeño exitoso al asegurar que los datos de rendimiento y la experiencia se reutilicen para futuros proyectos.
    3.5.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
MST (Managing Security Threats & Vulnerabilities): Formaliza la gestión de seguridad como un proceso continuo y no reactivo.
SAM (Supplier Agreement Management): Asegura que la calidad y la seguridad se extiendan a la cadena de suministro.
PAD (Process Asset Development): Transforma los artefactos del proyecto en activos reutilizables para la mejora continua.

El proceso cumple con prácticas de Nivel 3 y parcialmente con el Nivel 4 porque:
La Gestión de Incidentes incluye el paso de Documentar Lecciones Aprendidas.
La vinculación explícita con el Gestor de Cambios y los procesos de seguridad (SGSI) demuestra que el Mantenimiento se ejecuta utilizando procesos estandarizados de toda la organización.
La Evaluación de Desempeño vs Umbrales y el monitoreo de amenazas de seguridad establecen el control a nivel de proyecto (Nivel 2) y sienta las bases para el control cuantitativo (Nivel 4).
3.6 PROCESO 6: PLANIFICACIÓN Y CONTROL DE PROYECTOS
    3.6.1 Modelo actualizado del proceso en notación BPMN
Nuevas actividades a integrar en el diagrama:
Después de “Definir alcance, cronograma y presupuesto”:
Actividad: “Establecer métricas de desempeño del proyecto” (CMMI: Supplier Agreement)
Actividad: “Definir puntos de revisión y gates de calidad” (CMMI: Planning)
En paralelo a “Integrar plan de seguridad”
Actividad: “Establecer acuerdos con proveedores” (CMMI: Supplier Agreement Management)
Actividad: “Definir plan de gestión del conocimiento” (CMMI: Knowledge Management)
Después de “Monitorear avance vs plan”
Gateway: “¿Se cumple los umbrales de desempeño?”
Si NO: “Realizar análisis de causa raíz” (CMMI: Decision Analysis and Resolution)
“Documentar lecciones aprendidas” (CMMI: Process Management)
Antes del cierre:
Actividad: “Validar cumplimiento de criterios de salida” (CMMI: Verification and Validation)
Actividad: “Actualizar repositorio de activos del proceso organizacional” (CMMI: Organizational Process Definition)

    3.6.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
Área de Capacidad: DOING (Hacer)
Planning (PLAN) - Planificación
	Práctica específica incorporada:
PLAN 1.1 - Estimar el alcance del trabajo: Implementada en “Definir alcance, cronograma y presupuesto” mediante la descomposición del trabajo en paquetes entregables y la estimación de esfuerzo basada en datos históricos.
PLAN 1.2 - Establecer estimaciones de esfuerzo y costo: La actividad “Estimar recursos y costos” utiliza técnicas como análisis paramétricos, juicio experto y estimación por tres puntos, documentando supuestos y nivel de confianza.
PLAN 1.3 - Definir el ciclo de vida del proyecto: Se establece mediante la selección del modelo de ciclo de vida (ágil, cascada, híbrido) alineado con las características del proyecto y los estándares organizacionales.
Monitoring and Controlling (MC) - Monitoreo y Control
	Práctica específica incorporada:
MC 1.1 - Monitorear parámetros de planificación: Implementada en “Monitorear avance vs plan” mediante el seguimiento de cronograma, presupuesto, alcance y riesgos contra línea base aprobada.
MC 1.2 - Gestionar acciones correctivas hasta el cierre: El gateway “¿Requiere correctiva?” y la actividad “Implementar acciones correctivas” aseguran que las desviaciones sean abordadas de manera sistemática.
MC 1.3 - Definir el ciclo de vida del proyecto: La nueva actividad “Realizar análisis de causa raíz” aplica técnicas como los 5 porqués, diagrama de Ishikawa o análisis de Pareto para identificar causas fundamentales de desviaciones.

Área de Capacidad: MANAGING (Gestionar)
Governance (GOV) - Gobernanza
	Práctica específica incorporada:
GOV 1.1 - Establecer gobierno del proyecto: El rol “Patrocinador Ejecutivo” y la actividad “Aprobar plan integral” implementan la supervisión de alto nivel que asegura alineación estratégica.
GOV 1.3 - Revisar avance en puntos de decisión: Los nuevos “puntos de revisión y gates de calidad” establecen hitos formales donde stakeholders evalúan si el proyecto debe continuar, detenerse o cambiar de dirección.
Measurement and Analysis (MA) - Medición y Análisis
	Práctica específica incorporada:
MA 1.1 - Establecer objetivos de medición: La nueva actividad “Establecer métricas de desempeño” define indicadores como SPI (Schedule Performance Index), CPI (Cost Performance Index), velocidad del equipo y densidad de defectos.
MA 1.2 - Especificar medidas: Se documentan definiciones operacionales de cada métrica, frecuencia de recolección, responsables y herramientas.
MA 1.4 - Analizar datos de medición: Integrado en “Monitorear avance vs plan”, donde se analizan tendencias, variaciones y se generan informes de desempeño.
Decision Analysis and Resolution (DAR) - Análisis y Resolución de Decisiones
	Práctica específica incorporada:
DAR 1.1 - Evaluar alternativas: La actividad “Realizar análisis de causa raíz” incluye la evaluación estructurada de alternativas de solución mediante criterios ponderados (costo, tiempo, impacto en calidad, riesgo).
DAR 1.2 - Seleccionar soluciones: Las decisiones críticas (cambios de alcance, estrategias de mitigación) se documentan con justificación, alternativas consideradas y criterios aplicados.

Área de Capacidad: IMPROVING (Mejorar)
Process Management (PCM) - Gestión de Procesos
PCM 2.1 - Recopilar experiencias relacionadas con procesos: La nueva actividad “Documentar lecciones aprendidas” captura tanto éxitos como fracasos durante la ejecución, identificando prácticas efectivas y áreas de mejora.
PCM 2.2 - Desplegar activos de proceso organizacional: La actividad final “Actualizar repositorio de activos del proceso organizacional” contribuye estimaciones, plantillas mejoradas y lecciones aprendidas al repositorio corporativo para beneficio de proyectos futuros.
Organizational Process Definition (OPD) - Definición de Procesos Organizacionales
OPD 1.3 - Establecer activos de proceso organizacional: El uso de “Plantillas estándar del repositorio” como entrada y su actualización como salida implementa el ciclo de mejora continua de los activos organizacionales.
Supplier Agreement Management (SAM) - Gestión de Acuerdos con Proveedores
	Práctica específica incorporada:
SAM 1.1 - Determinar tipo de adquisición : La nueva actividad “Establecer acuerdos con proveedores” identifica qué productos o servicios se adquirirán externamente y define contratos con SLAs claros.
SAM 1.2 - Seleccionar proveedores: Se aplican criterios de evaluación (capacidad técnica, precio, experiencia, certificaciones de seguridad) para seleccionar proveedores calificados.
SAM 2.1 - Monitorear proveedores: Integrado en el monitoreo del proyecto, se verifica el cumplimiento de proveedores con los acuerdos establecidos.

Evidencia de madurez CMMI:
El proceso actualizado demuestra prácticas de Nivel 2 (Gestionado) al establecer planes formales, monitoreo y control; Nivel 3 (Definido) al utilizar procesos estandarizados del repositorio organizacional y utilizar activos; y elementos de Nivel 4 (Gestionado Cuantitativamente) mediante el uso de métricas y umbrales de desempeño para la toma de decisiones.
    3.6.3 Descripción formal escrita del proceso
Nombre del proceso: Planificación y Control de Proyectos TI

Objetivo: Establecer y mantener planes realistas que definan las actividades, recursos y cronogramas del proyecto; monitorear el progreso contra el plan; y tomar acciones correctivas cuando el desempeño se desvía significativamente del plan.

Alcance: Aplica a todos los proyectos de desarrollo, mantenimiento y mejora de software gestionados por el área de TI de InnovaTech Solutions, desde la autorización formal hasta el cierre y transferencia de lecciones aprendidas.

Disparador de inicio: Recepción del Acta de Constitución del Proyecto aprobada por la Dirección del Portafolio o Patrocinador Ejecutivo.

Criterios de entrada:
Acta de constitución del proyecto autorizada
Requisitos del proyecto validados (desde Proceso 1)
Registro de riesgos preliminar (desde Proceso 8)
Políticas de seguridad aplicables (desde Proceso 9)
Disponibilidad de recursos confirmada
Acceso al repositorio activos del proceso organizacional

Descripción detallada de actividades
FASE 1: PLANIFICACIÓN INICIAL
Revisar acta de constitución y requisitos (Líder de Planificación)
 Se analiza el documento de autorización del proyecto identificando objetivos, justificación de negocio, stakeholders clave y restricciones de alto nivel.
Se revisan los requisitos validados para comprender el alcance técnico y funcional.
Se identifican dependencias con otros proyectos o iniciativas organizacionales.
Consultar repositorio de plantillas (Líder de Planificación)
 Se recuperan plantillas estándar de plan de proyecto, WBS, cronograma y presupuesto del repositorio organizacional.
Se consultan datos históricos de proyectos similares (duraciones, esfuerzos, tasas de defectos) para calibrar estimaciones.
Se revisan lecciones aprendidas de proyectos anteriores para evitar errores recurrentes.
Definir alcance, cronograma y presupuesto (Líder de Planificación + Especialista en Control)
 Alcance: Se crea la Estructura de Desglose del Trabajo (WBS) descomponiendo entregables en paquetes de trabajo de 1-2 semanas.
Cronograma: Se estiman duraciones usando técnicas PERT, se identifican dependencias (finish-to-start, start-to-start) y se determina la ruta crítica mediante CPM.
Presupuesto: Se estiman costos de recursos humanos (desarrolladores, QA, arquitectos), infraestructura (servidores, licencias) y contingencias (10-20% según nivel de riesgo).
Establecer métricas de desempeño del proyecto (Especialista en Control + Especialista en Calidad) NUEVA - CMMI MA
 Se definen indicadores clave:
SPI (Schedule Performance Index) = EV/PV: Objetivo ≥ 0.95 (no más de 5% de retraso)
CPI (Cost Performance Index) = EV/AC: Objetivo ≥ 0.90 (no más de 10% de sobrecosto)
Velocidad del equipo: Story points completados por sprint (baseline en primeros 2 sprints)
Densidad de defectos: Defectos encontrados / KLOC (objetivo < 2 defectos/KLOC)
Se establecen umbrales de alerta (amarillo) y acción (rojo) para cada métrica.
Se define la frecuencia de medición (semanal para SPI/CPI, quincenal para velocidad).
Definir puntos de revisión y gates de calidad (Líder de Planificación + Validador de Cumplimiento) NUEVA - CMMI GOV
 Se establecen hitos de decisión go/no-go:
Gate 1 - Fin de Requisitos: ¿Están los requisitos completos, validados y priorizados?
Gate 2 - Fin de Diseño: ¿La arquitectura es viable, segura y aprobada por el arquitecto y CISO?
Gate 3 - Fin de Desarrollo: ¿El código cumple estándares de calidad y ha pasado pruebas unitarias?
Gate 4 - Fin de Pruebas: ¿El software ha pasado verificación, validación y pruebas de seguridad?
En cada gate, el Comité de Dirección del Proyecto revisa evidencia objetiva y decide: continuar, condicionar (con acciones correctivas) o cancelar.
FASE 2: INTEGRACIÓN DE PLANES ESPECIALIZADOS
Elaborar plan de riesgos (Analista de Riesgos + Líder de Planificación)
Se integran los riesgos identificados en el Proceso 8, estableciendo estrategias de mitigación, responsables y cronograma de revisiones (ej: revisión quincenal de top 5 riesgos).
Integrar plan de seguridad (Coordinador de Seguridad + CISO)
Se incorporan controles de seguridad específicos del proyecto basados en la clasificación de información (ISO 27002: 5.8).
Se definen actividades de revisión de código seguro, pruebas de penetración y auditorías de seguridad en el cronograma.
Establecer acuerdos con proveedores (Director de Gestión + Líder de Planificación) NUEVA - CMMI SAM
Para componentes externalizados (servicios cloud, licencias, desarrollo offshore):
Se seleccionan proveedores mediante evaluación estructurada (capacidad técnica, certificaciones ISO 27001, referencias).
Se negocian SLAs con métricas claras (disponibilidad ≥ 99.5%, tiempo de respuesta a incidentes < 4 horas).
Se establecen cláusulas de protección de datos (NDA, compliance GDPR si aplica).
Se define el esquema de monitoreo de proveedores (reportes mensuales, auditorías trimestrales).
Definir plan de gestión del conocimiento (Líder de Planificación) NUEVA - CMMI PCM
Se establece cómo se capturará conocimiento crítico:
Documentación técnica en wiki del proyecto (arquitectura, decisiones de diseño, troubleshooting).
Sesiones de retrospectiva cada 2 sprints para capturar lecciones aprendidas.
Knowledge transfer sessions al finalizar cada fase mayor.
FASE 3: APROBACIÓN Y LÍNEA BASE
Consolidar plan integral (Líder de Planificación)
Se integran todos los subplanes en un documento maestro: Plan de Gestión del Proyecto (PMP).
Se verifica consistencia entre alcance, cronograma, presupuesto, recursos, riesgos y calidad.
Presentar plan a stakeholders (Director de Gestión + Todos los Roles)
Se realiza reunión de kick-off presentando el plan a todo el equipo y stakeholders clave.
Se aclaran dudas, se validan supuestos y se confirman compromisos de recursos.
Aprobar plan integral (Patrocinador Ejecutivo)
El patrocinador revisa el plan contra los objetivos de negocio y presupuesto autorizado.
Si aprueba, se establece la línea base formal (baseline de alcance, cronograma y costo).
Si no aprueba, se retorna a ajustar el plan según retroalimentación.
Registrar línea base del proyecto (Encargado de Configuración) CMMI CM
Se congela el plan aprobado en el sistema de gestión de configuración.
Se asigna un identificador único (ej: PRJ-2025-001-Baseline-V1.0).
Cualquier cambio posterior requerirá proceso formal de control de cambios.
FASE 4: MONITOREO Y CONTROL CONTINUO
Monitorear avance vs plan (Especialista en Control + Director de Gestión)
Frecuencia: Semanal para proyectos críticos, quincenal para proyectos estándar.
Actividades:
Recopilar datos reales de avance (% completado de paquetes de trabajo, horas consumidas, costos devengados).
Calcular métricas: SPI, CPI, Variación de Cronograma (SV = EV - PV), Variación de Costo (CV = EV - AC).
Actualizar forecast de fecha de finalización (Estimate to Complete) y presupuesto final (Estimate at Completion).
Herramientas: Dashboards en MS Project / Jira con gráficas de burndown, curvas S de valor ganado.
¿Se cumplen los umbrales de desempeño? (Gateway) NUEVO - CMMI MA
Se evalúan las métricas contra umbrales definidos:
Verde: SPI ≥ 0.95 y CPI ≥ 0.90 → Continuar sin acciones especiales.
Amarillo: 0.85 ≤ SPI < 0.95 o 0.80 ≤ CPI < 0.90 → Alerta temprana, monitoreo intensificado.
Rojo: SPI < 0.85 o CPI < 0.80 → Requiere análisis de causa raíz y acciones correctivas inmediatas.
Realizar análisis de causa raíz (Especialista en Control + Responsable de Entregables) NUEVO - CMMI MA
Si se detecta desviación significativa, se aplica metodología estructurada:
5 Porqués: Para problemas operativos (ej: ¿Por qué se retrasó el módulo de autenticación?).
Diagrama de Ishikawa: Para problemas multifactoriales (categorías: personas, procesos, tecnología, ambiente).
Análisis de Pareto: Para priorizar causas (regla 80/20: el 20% de las causas producen el 80% del impacto).
Se documentan hallazgos en formato estándar (problema, causa raíz, evidencia, alternativas de solución).
¿Requiere acción correctiva? (Gateway)
Criterios de decisión:
Desviación > 10% en cronograma o costo → Sí requiere.
Riesgo materializado con impacto alto → Sí requiere.
Incumplimiento de gate de calidad → Sí requiere.
Cambio de requisitos o alcance → Evaluar impacto y decidir.
Implementar acciones correctivas (Director de Gestión + Equipos Técnicos)
Se ejecutan las soluciones aprobadas:
Fast-tracking: Paralelizar actividades que originalmente eran secuenciales (aumenta riesgo).
Crashing: Agregar recursos (desarrolladores, horas extras) para comprimir cronograma (aumenta costo).
Descope: Renegociar alcance, moviendo funcionalidades de baja prioridad a futuras releases.
Re-baseline: En casos extremos, re-planificar el proyecto con nueva línea base (requiere aprobación ejecutiva).
Se registra en el log de cambios la acción tomada, responsable, fecha y resultado esperado.
Documentar lecciones aprendidas (Líder de Planificación + Todo el Equipo) NUEVO - CMMI PCM
Momento: Al finalizar cada fase mayor y al cierre del proyecto.
Contenido:
¿Qué funcionó bien? (para replicar)
¿Qué no funcionó? (para evitar)
Acciones de mejora
Se almacenan en base de conocimiento organizacional categorizada por tipo de proyecto y tecnología.
Fase 5: CIERRE DEL PROYECTO
Validar cumplimiento de criterios de salida (Validador de Cumplimiento + Especialista en Calidad) NUEVO - CMMI VER
Se verifica que todos los entregables estén completos y aprobados:
Código fuente en repositorio con documentación actualizada.
Todos los casos de prueba ejecutados y aprobados (tasa de éxito ≥ 98%).
Documentación de usuario final y técnica entregada.
Incidentes críticos y altos resueltos (ningún defecto bloqueante abierto).
Sign-off formal del Product Owner y usuarios clave.
Generar reporte de cierre (Director de Gestión + Especialista en Control)
Documento ejecutivo que incluye:
Resumen ejecutivo: Objetivos logrados vs planificados.
Desempeño: SPI y CPI finales, comparación presupuesto planeado vs real, cronograma planeado vs real.
Calidad: Métricas de defectos, resultados de auditorías de seguridad.
Lecciones aprendidas: Top 5 éxitos y top 5 áreas de mejora.
Recomendaciones: Para el mantenimiento evolutivo y futuros proyectos similares.
Aprobar cierre (Patrocinador Ejecutivo)
El patrocinador revisa el reporte de cierre y confirma la aceptación formal del proyecto.
Autoriza la liberación de recursos del equipo para otras asignaciones.
Actualizar repositorio de activos del proceso organizacional (Líder de Planificación + Encargado de Configuración) NUEVO - CMMI OPD
Se contribuyen al repositorio corporativo:
Plantillas mejoradas
Estimaciones reales vs planeadas (para mejorar modelos de estimación futuros).
Lecciones aprendidas categorizadas (tecnología, dominio de negocio, tipo de riesgo).
Métricas de productividad
Se notifica a la Oficina de Gestión de Proyectos (PMO) sobre la disponibilidad de nuevos activos.

Criterio de salida:
Plan de proyecto aprobado y bajo control de configuración
Línea base de alcance, cronograma y costo establecida
Métricas de desempeño definidas y herramientas de monitoreo configuradas
Acuerdos con proveedores formalizados (si aplica)
Reporte de cierre aprobado y lecciones aprendidas documentadas
Activos del proceso organizacional actualizados

Roles y responsabilidad:
Líder de Planificación: Coordina elaboración del plan, consolida subplanes, facilita aprobaciones.
Especialista en Control: Monitorea métricas, genera informes de avance, identifica desviaciones.
Director de Gestión de Proyectos TI: Lidera ejecución, toma decisiones de acciones correctivas, interfaz con patrocinador.
Patrocinador Ejecutivo: Aprueba plan y cierre, autoriza cambios mayores, remueve impedimentos organizacionales.
Coordinador de Seguridad, Analista de Riesgos, Encargado de Configuración: Contribuyen sus planes especializados.
Todos los roles técnicos: Proveen estimaciones, reportan avance, ejecutan acciones correctivas, contribuyen lecciones aprendidas.

Artefactos generados:
Plan de Gestión del Proyecto (PMP) integral
Línea base de alcance (WBS), cronograma (diagrama de Gantt / red PERT) y costo (presupuesto)
Plan de métricas y umbrales de desempeño
Definición de gates de calidad y criterios de decisión
Acuerdos de nivel de servicio (SLA) con proveedores
Informes de progreso periódicos (semanales/quincenales)
Log de cambios y acciones correctivas
Análisis de causa raíz documentados
Lecciones aprendidas del proyecto
Reporte de cierre del proyecto
Contribuciones al repositorio de activos organizacionales

Integración con otros procesos
Entrada desde Proceso 1 (Gestión de Requisitos): Especificación de requisitos aprobada para estimar alcance.
Entrada desde Proceso 8 (Gestión de Riesgos): Registro de riesgos para plan de mitigación.
Entrada desde Proceso 9 (Gestión de Seguridad): Políticas y controles de seguridad para plan de seguridad.
Salida hacia Proceso 7 (Gestión de Configuración): Líneas base para control de cambios.
Salida hacia todos los procesos técnicos: Cronograma y presupuesto para ejecución.
    3.6.4 Métricas para evaluar el desempeño del proceso
Métrica 1: Índice de Desempeño del Cronograma (SPI - Schedule Performance Index)
Definición operacional: El SPI mide la eficiencia con la que el proyecto está progresando respecto al cronograma planificado. Se calcula mediante la fórmula:
SPI = Valor Ganado (EV) / Valor Planificado (PV)
Donde:
Valor Ganado (EV) = Porcentaje de trabajo realmente completado × Presupuesto planificado total
Valor Planificado (PV) = Porcentaje de trabajo que debería estar completado según el plan × Presupuesto planificado total
Objetivo:
Meta: SPI ≥ 1.00 (proyecto en cronograma o adelantado)
Umbral aceptable: SPI ≥ 0.95 (máximo 5% de retraso tolerable)
Umbral crítico: SPI < 0.85 (más de 15% de retraso requiere escalamiento a dirección)
Frecuencia de medición: Semanal para proyectos críticos, quincenal para proyectos estándar
Método de recolección:
Cada viernes, el Líder de Planificación solicita a los Responsables de Entregables el % real de avance de sus paquetes de trabajo.
El Especialista en Control registra los datos en la herramienta de gestión (MS Project/Jira).
El sistema calcula automáticamente EV sumando (% completado × presupuesto planificado) de todos los paquetes.
Se compara EV contra PV (valor acumulado que debería haberse generado según el cronograma baseline).
Se genera dashboard con gráfica de tendencia SPI y análisis de variación.
Interpretación:
SPI = 1.00: El proyecto está exactamente en cronograma.
SPI > 1.00: El proyecto está adelantado (ej: SPI = 1.10 significa 10% de adelanto).
SPI < 1.00: El proyecto está retrasado (ej: SPI = 0.90 significa 10% de retraso).
Ejemplo práctico: En la semana 10 de un proyecto de 20 semanas:
PV (según plan): Se deberían haber completado 50% del trabajo = 0.50 × $100,000 = $50,000
EV (real): Se ha completado 45% del trabajo = 0.45 × $100,000 = $45,000
SPI = $45,000 / $50,000 = 0.90 → El proyecto tiene 10% de retraso
Acciones según resultado:
SPI ≥ 1.00 (Verde): Mantener el ritmo actual, reconocer al equipo.
0.95 ≤ SPI < 1.00 (Amarillo): Monitoreo intensificado, identificar cuellos de botella, considerar reasignación menor de recursos.
SPI < 0.95 (Rojo): Análisis de causa raíz obligatorio, implementar acciones correctivas (fast-tracking, crashing, descope), reportar a patrocinador.
Beneficios:
Proporciona alerta temprana de desviaciones de cronograma antes de que sean críticas.
Facilita la toma de decisiones basada en datos objetivos vs opiniones subjetivas.
Permite comparar el desempeño de cronograma entre proyectos y equipos.
Soporta forecasting: Si SPI se mantiene en 0.90, podemos predecir que un proyecto de 20 semanas tomará 20/0.90 = 22.2 semanas.


Métrica 2: Efectividad del Proceso de Planificación (PPE - Planning Process Effectiveness)
Definición operacional:La PPE mide la calidad y precisión del proceso de planificación evaluando qué tan cerca estuvieron las estimaciones iniciales de los resultados reales. Se calcula mediante:

PPE = 1 - (|Variación Promedio de Estimaciones| / 100%)
Donde la Variación Promedio de Estimaciones se calcula como:
Variación Promedio = Promedio [ |Duración Real - Duración Estimada| / Duración Estimada × 100% ]
Se evalúa sobre una muestra representativa de al menos 20 paquetes de trabajo o 80% del esfuerzo total del proyecto.
Objetivo:
Meta: PPE ≥ 85% (variación promedio ≤ 15%)
Umbral aceptable: PPE ≥ 75% (variación promedio ≤ 25%)
Umbral crítico: PPE < 65% (variación promedio > 35% indica proceso de estimación deficiente)
Frecuencia de medición:
Medición intermedia: Al completar el 50% del proyecto
Medición final: Al cierre del proyecto
Método de recolección:
Al finalizar cada paquete de trabajo, el Encargado de Configuración registra:
Duración estimada inicial (de la línea base del plan)
Duración real (fecha de inicio real - fecha de fin real)
Esfuerzo estimado en horas-persona
Esfuerzo real consumido
El Especialista en Control calcula la variación porcentual para cada paquete.
Se calcula el promedio de variaciones absolutas (ignorando el signo para evitar que sobre-estimaciones y sub-estimaciones se cancelen).
Se analiza la distribución: ¿Las variaciones son sistemáticamente positivas (sub-estimación) o negativas (sobre-estimación)?
Ejemplo práctico:

Paquete de Trabajo
Duración Estimada
Duración Real
Variación %
Módulo Login
5 días
6 días
+20%
API REST
10 días
9 días
-10%
Base de Datos
8 días
11 días
+37.5%
UI Dashboard
12 días
13 días
+8.3%
Integración
15 días
18 días
+20%


    3.6.5 Herramientas de automatización
Herramienta 1: Microsoft Project Online / Project for the Web integrado con Power BI
Descripción: Microsoft Project Online es una solución de gestión de proyectos empresarial basada en la nube que permite la planificación, seguimiento y colaboración en proyectos de TI. Integrado con Power BI, proporciona capacidades avanzadas de visualización y análisis de datos de proyectos en tiempo real.
Actividades del proceso donde se utiliza:
"Definir alcance, cronograma y presupuesto":
Uso: Creación de WBS con descomposición jerárquica de entregables, asignación de duraciones mediante método PERT (optimista, más probable, pesimista), identificación de dependencias entre tareas (FS, SS, FF, SF), asignación de recursos con tasas de costo, y nivelación automática de recursos para resolver sobre-asignaciones.
Automatización: La herramienta calcula automáticamente la ruta crítica mediante el algoritmo CPM, alertando qué tareas no pueden retrasarse sin afectar la fecha final. Genera presupuesto consolidado sumando costos de recursos × duraciones.
"Establecer métricas de desempeño del proyecto":
Uso: Configuración de campos personalizados para capturar EV y PV. Definición de línea base (baseline) del proyecto que congela el plan original para comparaciones futuras.
Automatización: Una vez activada la línea base, Project calcula automáticamente SPI, CPI, SV (Variación de Cronograma) y CV (Variación de Costo) basándose en el % completado reportado por los responsables de tareas.
"Monitorear avance vs plan":
Uso: Los miembros del equipo actualizan el % completado de sus tareas semanalmente a través del portal web. El Especialista en Control revisa y aprueba estas actualizaciones.
Automatización: Project recalcula automáticamente el cronograma considerando las actualizaciones, ajusta fechas de tareas dependientes, y actualiza el forecast de fecha de finalización (ETC - Estimate to Complete).
Integración con Power BI:
Uso: Dashboards ejecutivos que visualizan múltiples proyectos del portafolio con indicadores consolidados.
Automatización: Power BI se conecta directamente a la base de datos de Project Online mediante conectores nativos. Los dashboards se refrescan automáticamente cada hora, mostrando:
Panel de Semáforo: Proyectos en verde (SPI y CPI ≥ 0.95), amarillo (0.85-0.95) y rojo (< 0.85).
Gráfica de Curva S de Valor Ganado: Visualiza PV, EV y AC (Costo Real) para análisis de tendencias.
Heat Map de Riesgos: Matriz probabilidad-impacto con proyectos posicionados según su exposición al riesgo.
Análisis de Carga de Recursos: Identifica recursos sobre-asignados en múltiples proyectos.
Beneficios de la aplicación:
Eliminación de trabajo manual:
Sin herramienta: El Especialista en Control dedica 4-6 horas semanales a consolidar reportes de avance de múltiples fuentes (emails, hojas Excel), calcular métricas manualmente en Excel, y generar presentaciones PowerPoint para stakeholders.
Con herramienta: La actualización de tareas por los responsables alimenta automáticamente los cálculos. Los dashboards de Power BI se generan sin intervención manual. Ahorro estimado: 80% del tiempo de reporte (~ 4 horas/semana/proyecto).
Visibilidad en tiempo real:
Sin herramienta: Los informes de avance se generan semanalmente, por lo que problemas críticos pueden no detectarse hasta 7 días después de surgir.
Con herramienta: Los stakeholders acceden a dashboards actualizados cada hora. Alertas automáticas se envían cuando un proyecto cruza umbrales críticos (ej: SPI < 0.85 → email inmediato al Director de Gestión y Patrocinador).
Mejora en la precisión de forecasting:
Sin herramienta: Predicciones de fecha de finalización basadas en extrapolación lineal simple o "gut feeling" del PM.
Con herramienta: Project utiliza el SPI actual para calcular el EAC (Estimate at Completion) realista: EAC = Presupuesto Original / CPI. Considera la velocidad real de avance, no solo el plan original. Mejora en precisión de estimaciones: +25% según estudios de PMI.
Análisis de tendencias y aprendizaje organizacional:
Sin herramienta: Lecciones aprendidas capturadas en documentos Word dispersos, difíciles de analizar.
Con herramienta: Power BI permite analizar patrones históricos: "Los proyectos con arquitecto dedicado full-time tienen SPI 15% mayor que aquellos con arquitecto compartido". Estos insights se traducen en mejores decisiones de asignación de recursos en futuros proyectos.
Facilitación de auditorías y compliance:
Sin herramienta: Reunir evidencia de planificación y monitoreo para auditorías CMMI o ISO requiere buscar archivos en múltiples carpetas compartidas.
Con herramienta: Todas las líneas base, cambios aprobados, y decisiones de gestión están trazables en Project. Se generan reportes de auditoría automáticos mostrando que el proceso se siguió consistentemente.
Costo-beneficio:
Inversión: Licencias Microsoft Project Online: ~$55/usuario/mes. Power BI Pro: ~$10/usuario/mes. Capacitación inicial: ~$5,000 (40 horas de consultoría).
Retorno: Para un área de TI con 10 proyectos concurrentes, ahorro de 40 horas/semana de trabajo administrativo = ~$4,000/semana (asumiendo $100/hora) = $200,000/año. ROI positivo en el primer trimestre.
Herramienta 2: Jira + Confluence + Advanced Roadmaps con automatización mediante Jira Automation
Descripción: Jira es la herramienta líder para gestión ágil de proyectos de software, especialmente popular en equipos que adoptan Scrum o Kanban. Confluence proporciona un espacio colaborativo para documentación del proyecto. Advanced Roadmaps (anteriormente Portfolio for Jira) permite planificación de múltiples equipos y proyectos. Jira Automation es un motor de reglas sin código que automatiza flujos de trabajo repetitivos.
Actividades del proceso donde se utiliza:
"Elaborar plan de riesgos":
Uso: Se crea un tablero específico de Gestión de Riesgos en Jira con issues tipo "Riesgo". Cada riesgo se documenta con campos personalizados: probabilidad (baja/media/alta), impacto (bajo/medio/alto/crítico), estrategia (mitigar/transferir/aceptar/evitar), dueño del riesgo, acciones de mitigación.
Automatización: Regla Jira Automation #1 - Escalamiento de riesgos:
    TRIGGER: Cuando un riesgo cambia a estado "Materializado"
     CONDITION: Si Impacto = "Alto" O "Crítico"
     ACTION: 
       - Enviar notificación a Director de Gestión y CISO
       - Crear automáticamente una tarea de "Acción Correctiva"  vinculada
       - Actualizar el campo "Fecha de materialización"
      	 	       - Agregar etiqueta "CRISIS" para filtrado rápido
Beneficio: Garantiza que riesgos críticos no pasen desapercibidos y activa respuesta inmediata.
"Monitorear avance vs plan":
Uso: Los equipos actualizan diariamente el estado de sus user stories/tareas (To Do → In Progress → Done). Jira calcula automáticamente burndown charts, velocidad del equipo (story points completados por sprint), y predicciones de finalización.
Automatización: Regla Jira Automation #2 - Alertas de sprint en riesgo:
    TRIGGER: Cada día a las 9:00 AM durante un sprint activo
     CONDITION: Si (Story points completados / Días transcurridos) < (Story points comprometidos / Duración del sprint) × 0.9
     ACTION: 
       - Enviar mensaje a canal Slack del equipo: "Sprint en riesgo: Velocidad actual 15% bajo objetivo. Review en daily standup."
       - Marcar el sprint con etiqueta "AT_RISK" visible en el dashboard
Beneficio: Alerta temprana que permite al Scrum Master tomar acciones correctivas (re-priorizar, pedir ayuda de otro equipo) antes del final del sprint.
"Implementar acciones correctivas":
Uso: Cuando se detecta una desviación, el Director de Gestión crea una issue tipo "Acción Correctiva" describiendo el problema, la solución propuesta, el responsable y la fecha límite.
Automatización: Regla Jira Automation #3 - Seguimiento de acciones correctivas:
    TRIGGER: Cuando una "Acción Correctiva" está en estado "In Progress" por más de 3 días sin comentarios
     ACTION: 
       - Enviar recordatorio al responsable y su manager
       - Incrementar el campo "Días sin actualización"
       - Si "Días sin actualización" > 5, escalar a Patrocinador Ejecutivo automáticamente
Beneficio: Evita que acciones correctivas se "olviden" o se eternicen sin resolución, manteniendo accountability.
"Documentar lecciones aprendidas":
Uso: Al finalizar cada sprint o fase, el equipo realiza una retrospectiva. Las lecciones aprendidas se documentan en una página de Confluence vinculada al proyecto.
Automatización: Integración Jira-Confluence:
    TRIGGER:  Cuando un proyecto Jira cambia a estado "Cerrado"
     ACTION: 
       - Crear automáticamente una página de Confluence: "Lecciones Aprendidas - [Nombre del Proyecto]"
       - Insertar plantilla pre-definida con secciones: Éxitos, Fracasos, Métricas Finales, Recomendaciones
       - Insertar automáticamente gráficas de Jira: burndown final, velocidad promedio, distribución de defectos
       - Enviar enlace al equipo para completar el contenido dentro de 1 semana
Beneficio: Institucionaliza la captura de lecciones aprendidas, haciendo imposible cerrar un proyecto sin documentarlas. La plantilla estandarizada facilita la búsqueda y análisis de patrones en múltiples proyectos.
Advanced Roadmaps para planificación multi-proyecto:
Uso: El Líder de Planificación utiliza Advanced Roadmaps para visualizar la cartera completa de proyectos del área de TI en una línea de tiempo (roadmap). Puede modelar diferentes escenarios: "¿Qué pasa si retrasamos el Proyecto A 2 semanas para dar prioridad al Proyecto B?"
Automatización: La herramienta detecta automáticamente:
Conflictos de recursos: "El Arquitecto Principal está asignado al 150% de su capacidad en el Q2 2025" → sugiere re-programación o contratación.
Dependencias entre proyectos: "El Proyecto B no puede iniciar hasta que el Proyecto A entregue la API compartida" → grafica las dependencias visualmente.
Análisis de impacto: Si se retrasa una tarea de la ruta crítica, automáticamente recalcula las fechas de todas las tareas dependientes en todos los proyectos afectados.
Beneficios de la aplicación:
Eliminación de reuniones de status innecesarias:
Sin herramienta: Reuniones semanales de 1 hora con cada equipo para "reportar avance" → 10 proyectos × 1 hora = 10 horas/semana del Director de Gestión solo escuchando reportes.
Con herramienta: El Director revisa dashboards de Jira en 15 minutos, identifica proyectos en rojo, y solo programa reuniones con esos equipos para resolver problemas específicos. Ahorro: 8.5 horas/semana del Director.
Mejora en la transparencia y confianza del equipo:
Sin herramienta: El equipo siente que "nadie ve nuestro trabajo" o "los managers no entienden nuestros bloqueos".
Con herramienta: Todos los stakeholders (incluido el Patrocinador) pueden acceder al board de Jira y ver el progreso real en tiempo real. Los bloqueos están visibles como issues con etiqueta "BLOCKED", facilitando que los managers remuevan impedimentos proactivamente.
Respuesta más rápida a desviaciones:
Sin herramienta: Un sprint puede estar completamente fallado y no se detecta hasta la Sprint Review (2 semanas perdidas).
Con herramienta: Las alertas automáticas de "sprint en riesgo" el día 3 de un sprint de 2 semanas permiten tomar acciones correctivas con 11 días de anticipación. Reducción de sprints fallidos: 60% según datos de Atlassian.
Estandarización de procesos entre equipos:
Sin herramienta: Cada equipo tiene su propia forma de trabajar, complicando la gestión del portafolio.
Con herramienta: Los workflows de Jira estandarizan el ciclo de vida de las tareas (To Do → In Progress → Code Review → Testing → Done). Los campos obligatorios aseguran que información crítica (prioridad, story points, responsable) siempre esté capturada. Las reglas de automatización se aplican consistentemente a todos los proyectos.
Facilitación de auditorías CMMI:
Para demostrar Nivel 2 (Gestionado): Los logs de Jira muestran que todos los proyectos siguen procesos planificados y monitoreados.
Para demostrar Nivel 3 (Definido): Los workflows estandarizados y plantillas de Confluence demuestran procesos definidos a nivel organizacional.
Para demostrar Nivel 4 (Gestionado Cuantitativamente): Los reportes de velocidad, burndown y métricas de calidad proveen datos cuantitativos para la gestión.
Costo-beneficio:
Inversión: Jira Software: ~$7/usuario/mes (hasta 100 usuarios). Confluence: $5/usuario/mes. Advanced Roadmaps: incluido en planes Premium ($14/usuario/mes). Capacitación inicial: ~$3,000.
Retorno: Para un área de TI con 50 personas:
Ahorro de tiempo de reporting: 8.5 horas/semana × $100/hora × 52 semanas = $44,200/año.
Reducción de sprints fallidos: 60% de reducción en ~6 sprints fallidos/año × costo promedio de re-planificación $15,000 = $54,000/año.
ROI total: ~$98,000/año vs inversión de ~$11,000/año = ROI de 791%.
Integración entre herramientas:
Project Online ↔ Jira: Sincronización bidireccional mediante APIs. Los hitos de alto nivel se planifican en Project (para satisfacer governance corporativo y PMO), mientras que la ejecución detallada ocurre en Jira (para agilidad del equipo). Los avances de Jira alimentan automáticamente el EV en Project.
Confluence ↔ Power BI: Los datos de lecciones aprendidas en Confluence se indexan y categorizan mediante NLP (Natural Language Processing), alimentando un "Lessons Learned Knowledge Base" en Power BI que permite búsquedas como: "Mostrar todos los proyectos donde la integración con SAP generó retrasos".
3.7 PROCESO 7: GESTIÓN DE CONFIGURACIÓN 
    3.7.1 Modelo actualizado del proceso en notación BPMN


PROCESO DE GESTIÓN DE CONFIGURACIÓN - ANTES (Hito 1)
El proceso original de Gestión de Configuración contaba con 15 actividades básicas distribuidas en 5 carriles:
Actividades principales:
Crear Solicitud de Cambio (CR)
Registrar CR en sistema
Identificar CIs afectados
Verificar línea base actual
Analizar impacto técnico
Evaluar impacto en pruebas
Revisar solicitud de cambio
Implementar cambio en repositorio
Registrar cambio en sistema de versionamiento
Verificar trazabilidad
Ejecutar pruebas sobre nueva versión
Establecer nueva línea base
Generar informe de estado de configuración
Actualizar documentación de configuración
Notificar rechazo (si aplica)
Elementos de control:
2 gateways de decisión (aprobación y pruebas)
1 loop de corrección (pruebas fallidas)
Limitaciones identificadas:
No existía evaluación formal de alternativas para cambios complejos
Faltaba captura sistemática de métricas del proceso de cambios
No se auditaba la integridad de las líneas base establecidas
No se validaba la integridad de baseline en producción
No se verificaba el cumplimiento del proceso CM
No se documentaban lecciones aprendidas del proceso
PROCESO DE GESTIÓN DE CONFIGURACIÓN - DESPUÉS (Hito 2)
El proceso mejorado incorpora 6 prácticas CMMI v2.0, elevando el total a 21 actividades:
Nuevas prácticas CMMI v2.0 integradas:
Evaluar alternativas de implementación (DAR) - Durante revisión del CCB
Capturar métricas del cambio (MA) - Después de implementar el cambio
Realizar auditoría de integridad de baseline (CM) - Al establecer nueva línea base
Validar integridad de baseline en producción (CM) - Después de establecer baseline
Verificar cumplimiento del proceso CM (PQA) - Antes de generar informe
Documentar lecciones aprendidas (PCM) - Al finalizar el proceso
Mejoras cuantificables:
+6 prácticas de madurez de procesos
+40% de actividades de aseguramiento de calidad
Auditoría completa de integridad de configuración
Validación en producción con gateway de control
Métricas definidas para mejora continua
Loop de corrección en validación de producción
    3.7.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
PROCESO: GESTIÓN DE CONFIGURACIÓN
A continuación se detalla el sustento técnico de cada una de las 6 prácticas del modelo CMMI v2.0 incorporadas al proceso de Gestión de Configuración de InnovaTech Solutions:
1. DAR - Decision Analysis and Resolution
Ubicación: CARRIL 3 - Comité de Control de Cambios (CCB)
 Actividad: Evaluar alternativas de implementación (DAR)
 Posición en el flujo: Después de las evaluaciones paralelas de impacto técnico y de pruebas
Sustento de incorporación:
La práctica DAR se incorpora en este punto crítico porque, tras analizar el impacto técnico y de pruebas, el CCB debe evaluar formalmente diferentes alternativas de implementación antes de tomar la decisión de aprobación. Esta práctica CMMI v2.0 permite:
Evaluar múltiples alternativas de implementación del cambio (parches, refactoring, reemplazo completo)
Aplicar criterios técnicos y de negocio para seleccionar la mejor opción
Analizar trade-offs entre tiempo, costo, riesgo y calidad
Documentar la justificación de la decisión de implementación
Según CMMI v2.0, DAR es especialmente importante para cambios complejos donde existen múltiples formas de abordar el problema. Para cambios simples, esta evaluación puede ser opcional, de ahí que se incorpore antes del gateway de aprobación.
2. MA - Measurement and Analysis
Ubicación: CARRIL 2 - Gestor de Configuración
 Actividad: Capturar métricas del cambio (MA)
 Posición en el flujo: Después de "Implementar cambio en repositorio"
Sustento de incorporación:
La práctica MA se integra inmediatamente después de implementar el cambio porque es el momento adecuado para capturar métricas objetivas del proceso. Esta práctica CMMI v2.0 garantiza:
Capturar métricas clave: Tiempo de aprobación, tasa de éxito de pruebas, número de defectos post-cambio, tiempo de implementación
Medir eficiencia del proceso de gestión de cambios
Identificar patrones de tipos de cambios que generan más problemas
Establecer baseline de desempeño para mejora continua
CMMI v2.0 establece que sin medición sistemática es imposible gestionar objetivamente la calidad del proceso. Esta práctica permite a InnovaTech Solutions cuantificar la efectividad de su proceso de configuración.
3. CM - Configuration Management (Auditoría de Baseline)
Ubicación: CARRIL 2 - Gestor de Configuración
 Actividad: Realizar auditoría de integridad de baseline (CM)
 Posición en el flujo: Inmediatamente después de "Establecer nueva línea base"
Sustento de incorporación:
La práctica CM se incorpora en este punto porque establecer una baseline no es suficiente; debe auditarse su integridad antes de considerarla válida. Esta práctica CMMI v2.0 asegura:
Auditar la completitud de la baseline (todos los CIs requeridos están incluidos)
Verificar consistencia entre los elementos de configuración
Validar versionamiento correcto de todos los componentes
Confirmar trazabilidad completa con la solicitud de cambio original
CMMI v2.0 establece que las auditorías de configuración son fundamentales para mantener la integridad del sistema. Esta práctica previene que baselines incompletas o inconsistentes sean promovidas a producción.
4. CM - Configuration Management (Validación en Producción)
Ubicación: CARRIL 4 - Equipo de QA/Testing
 Actividad: Validar integridad de baseline en producción (CM)
 Posición en el flujo: Después de "Realizar auditoría de integridad de baseline"
Sustento de incorporación:
La práctica CM se incorpora nuevamente en este punto porque la auditoría en repositorio no garantiza que la baseline funcione correctamente en el ambiente de producción. Esta práctica CMMI v2.0 garantiza:
Validar checksums de archivos desplegados vs. repositorio
Verificar versiones correctas de todos los componentes en producción
Confirmar configuración de ambiente (variables, parámetros, conexiones)
Validar funcionalidad del sistema con la nueva baseline
Esta práctica incluye un gateway de decisión (¿Baseline íntegra?) con un loop de corrección que regresa a "Establecer nueva línea base" si se detectan problemas. CMMI v2.0 reconoce que la validación en el ambiente real es crítica para prevenir incidentes en producción.
5. PQA - Process Quality Assurance
Ubicación: CARRIL 2 - Gestor de Configuración
 Actividad: Verificar cumplimiento del proceso CM (PQA)
 Posición en el flujo: Después de validar integridad de baseline en producción
Sustento de incorporación:
La práctica PQA se incorpora antes de generar el informe final porque es el momento de verificar que todo el proceso de gestión de configuración se ejecutó correctamente según lo establecido. Esta práctica CMMI v2.0 garantiza:
Auditar cumplimiento del proceso: ¿Se obtuvo aprobación del CCB?, ¿Se ejecutaron las pruebas?, ¿Se documentó correctamente?
Verificar adherencia a estándares de versionamiento y nomenclatura
Identificar desviaciones del proceso definido
Asegurar trazabilidad completa del cambio
CMMI v2.0 establece que PQA debe verificar objetivamente que los procesos se siguen de forma disciplinada. Esta práctica es esencial para mantener la madurez del proceso en la organización.
6. PCM - Process and Product Quality Management
Ubicación: CARRIL 2 - Gestor de Configuración
 Actividad: Documentar lecciones aprendidas (PCM)
 Posición en el flujo: Al final del proceso, después de "Actualizar documentación de configuración"
Sustento de incorporación:
La práctica PCM se integra al cierre del proceso porque es el momento de capturar el aprendizaje organizacional sobre la ejecución del cambio. Esta práctica CMMI v2.0 permite:
Capturar lecciones aprendidas: ¿Qué funcionó bien?, ¿Qué problemas surgieron?, ¿Cómo se resolvieron?
Documentar mejoras identificadas en el proceso de gestión de configuración
Generar recomendaciones para futuros cambios similares
Alimentar la base de conocimiento organizacional
CMMI v2.0 reconoce que la mejora continua se basa en aprender sistemáticamente de cada ejecución. PCM cierra el ciclo de aprendizaje y permite que la organización evolucione su madurez de proceso.

3.8 PROCESO 8: GESTIÓN DE RIESGOS 
    3.8.1 Modelo actualizado del proceso en notación BPMN
Nuevas actividades a integrar en el diagrama:
Antes de “Identificar riesgos”:
Actividad: "Establecer contexto y criterios de riesgo" (CMMI: Risk Management)
Actividad: "Definir categorías de riesgo y taxonomía" (CMMI: Risk Management)
Después de "Analizar y evaluar riesgos":
Actividad: "Cuantificar exposición al riesgo mediante análisis Monte Carlo" (CMMI: Quantitative Project Management)
Gateway: "¿Riesgo dentro del apetito de riesgo organizacional?"
En paralelo a "Definir estrategia de tratamiento":
Actividad: "Realizar análisis costo-beneficio de controles" (CMMI: Decision Analysis and Resolution)
Actividad: "Establecer indicadores de riesgo (KRIs)" (CMMI: Measurement and Analysis)
Después de "Implementar controles":
Actividad: "Validar efectividad de controles mediante pruebas" (CMMI: Verification and Validation)
Actividad: "Documentar evidencia de tratamiento para auditoría" (CMMI: Process Quality Assurance)
Dentro del ciclo de monitoreo:
Actividad: "Actualizar modelo de riesgos con datos reales" (CMMI: Organizational Process Performance)
Actividad: "Realizar análisis de tendencias de riesgos" (CMMI: Causal Analysis and Resolution)
Al final del proceso:
Actividad: "Contribuir lecciones aprendidas al repositorio organizacional" (CMMI: Organizational Process Definition)

    3.8.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
Área de Capacidad: DOING (Hacer)
Risk and Opportunity Management (RSK) - Gestión de Riesgos y Oportunidades
	Práctica específica incorporada:
RSK 1.1 - Determinar fuentes y categorías de riesgo: La nueva actividad "Definir categorías de riesgo y taxonomía" implementa la clasificación estándar de riesgos:
Riesgos Técnicos: Complejidad arquitectónica, tecnologías inmaduras, deuda técnica, escalabilidad.
Riesgos de Requisitos: Ambigüedad, volatilidad (cambios frecuentes), conflictos entre stakeholders.
Riesgos de Recursos: Disponibilidad de personal clave, rotación de equipo, falta de competencias especializadas.
Riesgos de Seguridad: Vulnerabilidades conocidas, amenazas cibernéticas, cumplimiento regulatorio (GDPR, PCI-DSS).
Riesgos de Proveedores: Dependencia de terceros, calidad de componentes COTS, discontinuidad de productos.
Riesgos Organizacionales: Cambios en prioridades estratégicas, fusiones/adquisiciones, restricciones presupuestarias.
RSK 1.2 - Establecer criterios de evaluación de riesgo: "Establecer contexto y criterios de riesgo" define la escala de probabilidad e impacto:
Probabilidad: Muy Baja (<10%), Baja (10-30%), Media (30-50%), Alta (50-70%), Muy Alta (>70%).
Impacto: Insignificante (<5% sobrecosto/retraso), Menor (5-10%), Moderado (10-20%), Mayor (20-40%), Crítico (>40% o fallo del proyecto).
Matriz de Criticidad: Probabilidad × Impacto = Nivel de Riesgo (Bajo, Medio, Alto, Crítico). Se define el umbral de tolerancia: Riesgos críticos requieren escalamiento a Comité Ejecutivo.
RSK 1.3 - Identificar riesgos: Actividad "Identificar riesgos" utiliza técnicas estructuradas:
Brainstorming: Sesión facilitada con todo el equipo del proyecto.
Checklist basada en taxonomía: Se revisa cada categoría preguntando "¿Existen riesgos de este tipo?"
Análisis FODA: Identificar riesgos derivados de Debilidades internas y Amenazas externas.
Revisión de lecciones aprendidas: Consultar el repositorio de riesgos materializados en proyectos anteriores similares.
Consulta con expertos: Involucrar al CISO para riesgos de seguridad, al Arquitecto para riesgos técnicos.
RSK 1.4 - Analizar riesgos: "Analizar y evaluar riesgos" implementa análisis cualitativo (matriz probabilidad-impacto) y cuantitativo:
Análisis cualitativo: Se ubica cada riesgo en la matriz 5×5. Ej: "Rotación del arquitecto principal" → Probabilidad Media (40%) × Impacto Mayor (30% retraso) = Riesgo Alto.
Análisis cuantitativo - Simulación Monte Carlo: La nueva actividad "Cuantificar exposición mediante Monte Carlo" aplica simulación estocástica:
Se modelan las estimaciones de duración/costo de tareas como distribuciones de probabilidad (ej: triangular con valores optimista, más probable, pesimista).
Se ejecutan 10,000 simulaciones aleatorias del cronograma/presupuesto.
Output: Curva de probabilidad acumulada: "Hay 80% de probabilidad de completar el proyecto en ≤18 meses y ≤$1.2M". Esto cuantifica la exposición al riesgo de manera objetiva.
Herramienta: @RISK (plugin de Excel) o simulaciones en Python con numpy.
RSK 2.1 - Desarrollar estrategias de mitigación: "Definir estrategia de tratamiento" implementa las 4 estrategias clásicas:
Mitigar: Reducir probabilidad o impacto (ej: para "tecnología inmadura", hacer POC en fase de diseño).
Transferir: Pasar el riesgo a terceros (ej: contratar seguro de ciberseguridad, outsourcing de módulos complejos).
Aceptar: Reconocer el riesgo y preparar plan de contingencia (ej: presupuesto de reserva de 15% para imprevistos).
Evitar: Eliminar la causa del riesgo cambiando el plan (ej: si integración con API legacy es muy riesgosa, construir un microservicio intermediario).
RSK 2.2 - Implementar planes de mitigación: "Implementar controles" ejecuta las acciones definidas:
Se crean tareas específicas en el cronograma para actividades de mitigación (ej: "Realizar POC de tecnología X - 2 semanas").
Se asignan responsables (Dueño del Riesgo) y presupuesto.
Se establecen hitos de verificación para confirmar que la mitigación fue efectiva.
RSK 3.1 - Monitorear riesgos: "Monitorear riesgos y amenazas emergentes" implementa seguimiento continuo:
Frecuencia: Revisión semanal de top 5 riesgos en reunión de equipo, revisión completa quincenal con stakeholders.
Indicadores de Alerta Temprana (KRIs - Key Risk Indicators): Nueva actividad "Establecer KRIs":
Para riesgo de "Rotación de personal": KRI = Índice de satisfacción del equipo (medido mensualmente). Si cae <70%, el riesgo se activa.
Para riesgo de "Sobrecarga de arquitecto": KRI = % de utilización del arquitecto. Si >90% por 3 semanas consecutivas, escalar.
Riesgos Secundarios: Monitorear si las acciones de mitigación generan nuevos riesgos (ej: contratar consultores externos mitiga falta de capacidad, pero introduce riesgo de fuga de información).


Área de Capacidad: MANAGING (Gestionar)
Quantitative Project Management (QPM) - Gestión Cuantitativa de Proyectos
	Práctica específica incorporada:
QPM 1.1 - Establecer objetivos cuantitativos: El gateway "¿Riesgo dentro del apetito de riesgo?" implementa comparación contra umbrales cuantitativos definidos por la Alta Dirección:
Apetito de riesgo: Máxima exposición al riesgo tolerable para el proyecto/organización.
QPM 1.2 - Componer el proceso definido: La actividad "Actualizar modelo de riesgos con datos reales" alimenta modelos estadísticos:
Se captura: Riesgo identificado → Probabilidad estimada → Probabilidad real (¿se materializó? Sí/No) → Impacto estimado → Impacto real (costo/tiempo perdido).
Con datos de 20+ proyectos, se calibran los modelos de probabilidad (ej: "Los riesgos categorizados como 'Probabilidad Media' realmente se materializan en 35% de los casos, no el 40% asumido → ajustar escala").
Decision Analysis and Resolution (DAR) - Análisis y Resolución de Decisiones
	Práctica específica incorporada:
DAR 1.1 - Establecer directrices para análisis de decisiones: "Realizar análisis costo-beneficio de controles" implementa evaluación estructurada de alternativas de mitigación:
Criterios ponderados:
Efectividad de reducción de riesgo (peso 40%): ¿Cuánto reduce la exposición?
Costo de implementación (peso 30%): Inversión requerida
Tiempo de implementación (peso 20%): ¿Se puede implementar antes de que el riesgo se materialice?
Impacto en operación normal (peso 10%): ¿Genera fricción en el equipo?
Matriz de decisión: Se puntúa cada alternativa de 1-5 en cada criterio, se multiplica por pesos, se suma. La alternativa con mayor puntaje se selecciona.

Área de Capacidad: IMPROVING (Mejorar)
Measurement and Analysis (MA) - Medición y Análisis
	Práctica específica incorporada:
MA 1.2 - Especificar medidas: "Establecer indicadores de riesgo (KRIs)" define métricas específicas:
Exposición Total al Riesgo: Suma de (Probabilidad × Impacto Monetario) de todos los riesgos activos.
Número de Riesgos por Categoría: Trending mensual para identificar áreas problemáticas.
Tasa de Materialización de Riesgos: (Riesgos materializados / Riesgos identificados) × 100%. Si es muy alta (>40%), indica falla en mitigación. Si es muy baja (<5%), indica sobre-identificación de falsos riesgos.
Efectividad de Controles: Para cada control implementado, medir si redujo la exposición al nivel esperado.
MA 1.4 - Analizar datos de medición: "Realizar análisis de tendencias de riesgos" identifica patrones:
Análisis de Pareto: ¿El 20% de las categorías de riesgo generan el 80% de la exposición? → Enfocar esfuerzos de mitigación ahí.
Tendencia temporal: ¿La exposición total está aumentando o disminuyendo a medida que avanza el proyecto? Normalmente debería disminuir conforme se resuelven incertidumbres.
Benchmarking: Comparar la exposición al riesgo de proyectos similares: "Los proyectos de integración tienen exposición promedio de $300K, nuestro proyecto está en $450K → requiere atención especial".
Causal Analysis and Resolution (CAR) - Análisis y Resolución de Causas
	Práctica específica incorporada:
CAR 1.1 - Seleccionar defectos/problemas para análisis: Cuando un riesgo se materializa (ej: "Rotación del arquitecto" realmente ocurrió), se dispara análisis de causa raíz:
¿Por qué se materializó? ¿Fallaron los controles de mitigación?
¿El impacto real fue mayor/menor que el estimado? ¿Por qué?
CAR 2.1 - Implementar propuestas de acción: Las lecciones aprendidas ("Los bonos de retención no fueron suficientes para retener al arquitecto, necesitamos contratos con penalización por salida temprana") se traducen en mejoras del proceso de gestión de riesgos:
Actualizar la taxonomía de riesgos (agregar nuevos tipos identificados).
Ajustar escalas de probabilidad/impacto basándose en datos reales.
Mejorar técnicas de identificación (ej: agregar entrevistas individuales confidenciales para detectar riesgos de rotación).
Verification and Validation (VV) - Verificación y Validación
	Práctica específica incorporada:
VER 1.2 - Realizar revisiones por pares: "Validar efectividad de controles mediante pruebas" implementa verificación independiente:
Pruebas de controles de seguridad: Si se implementó control "Cifrado de datos en reposo", el CISO ejecuta escaneo para verificar que efectivamente todos los volúmenes estén cifrados.
Pruebas de controles de proceso: Si se implementó control "Revisión arquitectónica semanal con equipo extendido", el Gestor de Riesgos verifica actas de reuniones y listas de asistencia.
Resultado: Si el control no está funcionando como se esperaba, se marca como "Inefectivo" y se buscan alternativas.
Process Quality Assurance (PQA) - Aseguramiento de Calidad de Procesos
	Práctica específica incorporada:
PQA 1.1 - Evaluar procesos objetivamente: "Documentar evidencia de tratamiento para auditoría" asegura que el proceso de gestión de riesgos se siga consistentemente:
Se mantiene un log auditable con timestamps de cada actividad:
Fecha de identificación del riesgo
Quién lo evaluó y aprobó la estrategia de tratamiento
Fecha de implementación de controles
Resultados de pruebas de efectividad
Decisiones de aceptación de riesgos (firmadas por Comité)
Auditorías internas trimestrales revisan que todos los riesgos altos/críticos tienen evidencia documental completa.
Organizational Process Performance (OPP) - Desempeño de Procesos Organizacionales
	Práctica específica incorporada:
OPP 1.1 - Establecer líneas base de desempeño: "Actualizar modelo de riesgos con datos reales" contribuye a líneas base organizacionales:
Línea base de exposición al riesgo por tipo de proyecto:
Proyectos de desarrollo nuevo: Exposición promedio $400K ± $150K
Proyectos de mantenimiento: Exposición promedio $100K ± $50K
Proyectos de integración: Exposición promedio $350K ± $100K
Estas líneas base permiten detectar proyectos anómalos tempranamente: "Este proyecto de desarrollo tiene exposición de $700K, está 2 desviaciones estándar por encima del promedio → requiere atención especial de governance".
OPD 1.3 - Establecer activos de proceso: "Contribuir lecciones aprendidas al repositorio" alimenta:
Registro de Riesgos Comunes: Base de datos searchable con riesgos recurrentes, estrategias efectivas de mitigación, y lecciones aprendidas.
Plantillas actualizadas: Matriz de riesgos mejorada con nuevas categorías identificadas en proyectos recientes.
Modelos estadísticos: Fórmulas calibradas para estimar probabilidad e impacto basándose en características del proyecto (tamaño, complejidad tecnológica, experiencia del equipo).

Evidencia de madurez CMMI:
El proceso actualizado demuestra prácticas de Nivel 2 (Gestionado) al identificar y monitorear riesgos sistemáticamente; Nivel 3 (Definido) al utilizar taxonomías y procesos estandarizados; Nivel 4 (Gestionado Cuantitativamente) mediante análisis Monte Carlo, KRIs y líneas base estadísticas; y Nivel 5 (En Optimización) mediante análisis causal y mejora continua del modelo de riesgos basándose en datos reales.
3.9 PROCESO 9: GESTIÓN DE SEGURIDAD DE LA INFORMACIÓN
    3.9.1 Modelo actualizado del proceso en notación BPMN
Nuevas actividades a integrar en el diagrama:
Después de “Solicitar evaluación de riesgos”:
Actividad: T4-L2 (CMMI) - Analizar alternativas y registrar decisión
(CMMI: Decision Analysis and Resolution - DAR)
Esta actividad formaliza la comparación de alternativas de tratamiento de riesgo antes de elaborar el plan.
Después de “Elaborar plan de tratamiento”:
Actividad: T6-L2 (CMMI) - Establecer línea base SGSI
(CMMI: Configuration Management - CM)
Se define la baseline del SGSI para asegurar trazabilidad y control de versiones.
Antes de “Enviar informe final SGSI a Alta Dirección”:
Actividad: “T8-L2 (CMMI) - Analizar métricas y elaborar informe final”
(CMMI: Measurement & Analysis - MA)
Permite que el cierre del ciclo SGSI esté basado en datos y métricas reales.


    3.9.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
Área de Capacidad: DOING (Hacer)
Decision Analysis and Resolution (DAR)
Práctica incorporada:
DAR 1.1 – Evaluar alternativas de solución
DAR 1.2 – Seleccionar la mejor alternativa basada en criterios definidos
Implementado en: T4-L2 (CMMI) - Analizar alternativas y registrar decisión
Sustento: 
En el proceso SGSI, las decisiones sobre tratamiento de riesgos (mitigar, evitar, transferir, aceptar) requieren comparación estructurada de alternativas.
DAR establece que toda selección debe:
compararse bajo criterios (costo, impacto, urgencia, probabilidad),
registrarse y justificarse. 
Esto aumenta objetividad, auditoría y repetibilidad del SGSI.


Área de Capacidad: MANAGING (Gestionar)
Configuration Management (CM)
Práctica incorporada:
CM 1.1 – Establecer elementos de configuración
CM 1.2 – Crear y mantener líneas base
Implementado en: T6-L2 (CMMI) - Establecer línea base SGSI
Sustento:
El SGSI requiere un estado controlado de:
políticas
matriz de riesgos
controles implementados
evidencias
versiones previas
CMMI exige baselines para asegurar integridad y trazabilidad del sistema de gestión.
Área de Capacidad: IMPROVING (Mejorar)
Measurement and Analysis (MA)
Práctica incorporada:
MA 1.1 – Establecer objetivos de medición
MA 1.4 – Analizar datos de desempeño
	Implementado en: T8-L2 (CMMI) - Analizar métricas y elaborar informe final
	Sustento:
El análisis de métricas del SGSI permite evaluar:
efectividad de controles
reducción del riesgo residual
cumplimiento del plan de tratamiento
tendencias de madurez del SGSI.
CMMI establece que estas métricas deben analizarse antes del cierre del ciclo SGSI para generar decisiones basadas en datos.


Evidencia de madurez CMMI aplicada al proceso 9
El proceso 9, gracias a las actividades incorporadas, demuestra prácticas de:
Nivel 2 (Gestionado):
Línea base formal del SGSI
Trazabilidad de decisiones
Métricas analizadas para cierre del ciclo
Nivel 3 (Definido):
Proceso SGSI formalizado, medido y cíclico
Decisiones basadas en análisis comparativo
Control documental y estructurado
3.10 PROCESO 10: GESTIÓN DE INCIDENTES DE SEGURIDAD
    3.10.1 Modelo actualizado del proceso en notación BPMN
Nuevas actividades a integrar en el diagrama:
Después de “Solicitar información complementaria”:
Actividad: T6-L2 (CMMI - DAR) - Analizar alternativas de contención y decidir
(CMMI: Decision Analysis and Resolution)
Esta etapa formaliza la evaluación estructurada de alternativas (bloquear, aislar, detener servicio, mitigar temporalmente) y documenta la decisión según criterios definidos.
Después de “Enviar informe técnico final” y previo a validar cierre:
Actividad: T7-L2 (CMMI - CM) - Baseline del incidente
(CMMI: Configuration Management)
Se crea la línea base del incidente:
evidencias
logs
cronología
versión final del análisis
Esto asegura trazabilidad y control del incidente tratado.
Antes de generar el informe final de cierre:
Actividad: T8-L2 (CMMI - MA/PCM) - Analizar métricas y generar lecciones aprendidas
(CMMI: Measurement & Analysis + Process Management)
Incluye:
métricas del incidente (tiempos de respuesta, contención, impacto, esfuerzo técnico)
efectividad de acciones aplicadas
registro de lecciones aprendidas


    3.10.2 Sustento de las prácticas del modelo CMMI v2.0 incorporadas
Área de Capacidad: DOING (Hacer)
Decision Analysis and Resolution (DAR)
Práctica incorporada:
DAR 1.1 – Evaluar alternativas de acción
DAR 1.2 – Seleccionar alternativas usando criterios definidos
Implementado en: T6-L2 (CMMI) - Analizar alternativas de contención y decidir
Sustento: 
Durante un incidente, el CISO debe seleccionar la mejor acción:
detener servicio
aislar recurso
mitigar temporalmente
aplicar bloqueo
DAR exige que esta decisión sea:
comparada objetivamente
justificada
documentada
Esto mejora la calidad y racionalidad del proceso de contención.


Área de Capacidad: MANAGING (Gestionar)
Configuration Management (CM)
Práctica incorporada:
CM 1.1 – Establecer elementos de configuración
CM 1.2 – Crear línea base del incidente
Implementado en: T7-L2 (CMMI) - Baseline del incidente
Sustento:
Un incidente de seguridad genera artefactos críticos:
evidencia digital
logs
resultados de análisis
registros de acciones
CMMI garantiza que toda esta información quede registrada en una baseline oficial para auditoría y trazabilidad.
Área de Capacidad: IMPROVING (Mejorar)
Measurement and Analysis (MA)
Práctica incorporada:
MA 1.1 – Establecer objetivos de medición
MA 1.4 – Analizar datos para toma de decisiones
	Implementado en: T8-L2 (CMMI) - Analizar métricas del incidente
	Sustento:
CMMI exige analizar métricas como:
tiempo detectado - contenido - resuelto
efectividad del bloqueo
tendencia de incidentes
desgaste operativo
Estos datos permiten mejorar tiempos y capacidades del SGSI.
Process Management (PCM)
	Prácticas incorporadas:
PCM 2.1 – Recopilar experiencias relacionadas con procesos
	Implementado en: T8-L2 (CMMI) - Generar lecciones aprendidas
Sustento: Permite que cada incidente nutra la mejora continua del SGSI y de los equipos técnicos, fortaleciendo la madurez organizacional.
Evidencia de madurez CMMI aplicada al proceso 10
Gracias a las actividades CMMI incorporadas, este proceso demuestra capacidades de:
Nivel 2 (Gestionado):
Evaluación formal de decisiones críticas
Control de configuración del incidente
Nivel 3 (Definido):
Análisis de métricas del incidente
Lecciones aprendidas documentadas
Ciclo estandarizado y repetible
CAPÍTULO 4: PRESENTACIÓN DE LA ORGANIZACIÓN DE LOS PROCESOS A EVALUAR
4.1 Actualización de Procesos
Para poder proponer un modelo de procesos coherente y alineado a objetivos de negocio, es fundamental establecer el contexto organizacional en el cual operará. A continuación, se describe la empresa ficticia que servirá como base para el presente estudio.
    4.1.1 Descripción de la Organización 
Datos Generales
Razón Social: InnovaTech Solutions S.A.C.
RUC: 20601234567
Sector Económico: Tecnología de la Información - FinTech
Actividad Principal: Desarrollo de soluciones de software SaaS para el sector financiero
Año de Fundación: 2015
Sede Principal: Av. República de Panamá 3420, San Isidro, Lima, Perú
Número de Empleados: 85 colaboradores
Personal del Área de TI: 42 personas
Clientes Activos: 18 instituciones financieras en Perú y América Latina
4.1.2 Descripción del Negocio
InnovaTech Solutions es una empresa peruana de tecnología especializada en el desarrollo de plataformas SaaS para instituciones financieras. La compañía atiende principalmente a cajas municipales, cooperativas de ahorro y crédito, y empresas de gestión patrimonial en Perú y otros países de América Latina.
Sus productos principales incluyen:
CreditPro: Plataforma de evaluación y gestión de créditos con scoring automatizado
InvestHub: Sistema de gestión de portafolios de inversión y análisis de riesgo
ComplianceTrack: Módulo de cumplimiento normativo y prevención de lavado de activos
CustomerPortal: Portal web y móvil para clientes finales de las instituciones financieras
Debido a la naturaleza de su negocio, InnovaTech maneja información financiera y personal sensible, lo que hace que la seguridad de la información, la continuidad del negocio y el cumplimiento normativo sean pilares estratégicos de su operación. La empresa está sujeta a regulaciones como la Ley de Protección de Datos Personales del Perú, normativas de la Superintendencia de Banca, Seguros y AFP (SBS), y se encuentra en proceso de certificación ISO/IEC 27001.
4.1.3 Estructura del Área de TI
El área de Tecnología de la Información constituye el núcleo operativo de InnovaTech Solutions, con 42 colaboradores distribuidos en las siguientes unidades:
Jefatura de Desarrollo de Software (20 personas)
Squad CreditPro: 8 desarrolladores
Squad InvestHub: 7 desarrolladores
Squad Compliance & Portal: 5 desarrolladores
Jefatura de Infraestructura y Operaciones (10 personas)
DevOps Engineers: 4 personas
Administradores de Sistemas: 3 personas
Soporte Técnico N1/N2: 3 personas
Jefatura de Seguridad de la Información (5 personas)
CISO: 1 persona
Analistas de Seguridad: 2 personas
Especialistas en Cumplimiento: 2 personas
Arquitectura y Calidad (4 personas)
Arquitecto de Software Senior: 1 persona
Analistas de Calidad/QA: 3 personas
Gestión de Proyectos TI (3 personas)
PMO / Líder de Proyectos: 1 persona
Project Managers: 2 personas
4.2 Metodología de Ciclo de Vida de Desarrollo y Mantenimiento de Software
4.2.1 Modelo de Ciclo de Vida Adoptado
InnovaTech Solutions adoptó un modelo híbrido que combina elementos de Scrum (para desarrollo ágil) con prácticas formales de gestión de proyectos tradicionales, especialmente para cumplimiento regulatorio y documentación.
Características principales del modelo:
Framework base: Scrum con sprints de 2 semanas
Planificación: Ciclos trimestrales (Quarterly Planning) con roadmaps de producto
Desarrollo: Iterativo e incremental por squad especializado
Despliegue: Releases mensuales a producción (último viernes de cada mes)
Mantenimiento: Modelo reactivo con SLAs diferenciados por criticidad de incidente
4.2.2 Fases del Ciclo de Vida
El ciclo de vida de los proyectos de desarrollo en InnovaTech Solutions comprende las siguientes fases:
Fase 1: Ideación y Definición de Producto (1-2 semanas)
El Product Owner recibe solicitudes de clientes o identifica oportunidades de mercado
Se realiza análisis de viabilidad técnica y comercial
Se elabora un Product Brief inicial
Aprobación por Gerencia de Tecnología
Fase 2: Planificación y Especificación (2-3 semanas)
El Product Owner elabora épicas y user stories en Jira
El Arquitecto de Software realiza diseño de alto nivel
El CISO revisa requisitos de seguridad
Se estiman story points mediante Planning Poker
Se priorizan user stories en el Product Backlog
Fase 3: Desarrollo Iterativo (sprints de 2 semanas)
Sprint Planning: Selección de user stories del backlog
Daily Standup: Sincronización diaria del squad
Desarrollo: Programación con pair programming para código crítico
Code Review: Revisión por pares antes de merge
Sprint Review: Demo de funcionalidades completadas
Sprint Retrospective: Mejora continua del proceso
Fase 4: Pruebas y Aseguramiento de Calidad (continua)
Pruebas unitarias automatizadas (cobertura mínima 60%)
Pruebas de integración en ambiente de staging
Pruebas exploratorias manuales por equipo QA
Pruebas de seguridad con SonarQube
Pruebas de aceptación por Product Owner
Fase 5: Despliegue a Producción (mensual)
Creación de Release Candidate
Validación en ambiente de pre-producción
Despliegue mediante pipelines automatizados (GitLab CI/CD)
Smoke tests post-despliegue
Monitoreo intensivo durante 48 horas
Fase 6: Operación y Mantenimiento (continuo)
Monitoreo 24/7 con Grafana y Prometheus
Atención de incidentes mediante Service Desk (Jira Service Management)
Mantenimiento correctivo (hotfixes) según criticidad
Mantenimiento evolutivo (nuevas features) en sprints regulares
4.2.3 Herramientas Tecnológicas Utilizadas
Gestión de Proyectos y Colaboración:
Jira Software (gestión ágil y backlog)
Confluence (documentación técnica)
Slack (comunicación interna)
Control de Versiones y CI/CD:
GitLab (repositorio de código y pipelines)
Docker y Kubernetes (contenedores y orquestación)
Desarrollo:
Backend: Python (Django/FastAPI), Node.js
Frontend: React.js, TypeScript
Bases de Datos: PostgreSQL, MongoDB, Redis
Cloud: AWS (EC2, RDS, S3, Lambda)
Calidad y Seguridad:
SonarQube (análisis estático de código)
OWASP ZAP (pruebas de seguridad)
Selenium + Pytest (automatización de pruebas)
Sentry (monitoreo de errores)
Operación:
Grafana + Prometheus (monitoreo de infraestructura)
ELK Stack (logs centralizados)
AWS CloudWatch (alertas y métricas)
4.3 Mapa de Procesos de la Organización
4.3.1 Representación Gráfica del Mapa de Procesos
La organización InnovaTech Solutions implementa el siguiente mapa de procesos, estructurado en tres niveles jerárquicos según el estándar de gestión por procesos:

4.3.2 Descripción de la Arquitectura del Mapa de Procesos
El mapa de procesos se organiza en tres niveles:
Procesos Estratégicos (definen la dirección del negocio)
Planificación Estratégica de TI
Gestión del Portafolio de Productos
Gestión de la Innovación
Procesos Operativos (ciclo de vida del software)
Gestión de Requisitos
Diseño y Arquitectura
Desarrollo e Implementación
Verificación, Validación y Transición
Operación y Mantenimiento
Procesos de Soporte (habilitan la operación)
Planificación y Control de Proyectos
Gestión de Configuración
Gestión de Riesgos
Gestión de Seguridad de la Información
Gestión de Incidentes de Seguridad
4.3.3 Detalle de los 10 Procesos Principales
La organización tiene implementados los siguientes 10 procesos principales, que fueron modelados mediante notación BPMN e integran prácticas de las normas ISO/IEC 12207:2017, ISO/IEC 27001:2022, ISO/IEC 27002:2022, tal como se detalló en el Capítulo 2:
Procesos Operativos del Ciclo de Vida:
Proceso 1: Gestión de Requisitos
Captura, análisis, especificación y control de requisitos funcionales y no funcionales
Herramientas: Jira, Confluence
Proceso 2: Diseño y Arquitectura
Definición de la arquitectura técnica y diseño de soluciones
Herramientas: Draw.io, Confluence
Proceso 3: Desarrollo e Implementación
Construcción del software siguiendo estándares de codificación
Herramientas: GitLab, SonarQube, Docker
Proceso 4: Verificación, Validación y Transición
Pruebas de calidad, seguridad y despliegue controlado
Herramientas: Selenium, Pytest, GitLab CI/CD
Proceso 5: Operación y Mantenimiento
Monitoreo, gestión de incidentes y mantenimiento continuo
Herramientas: Grafana, Prometheus, Jira Service Management
Procesos de Soporte:
Proceso 6: Planificación y Control de Proyectos
Planificación de cronogramas, recursos y seguimiento de avance
Herramientas: Jira, Excel, MS Project
Proceso 7: Gestión de Configuración
Control de versiones y gestión de cambios
Herramientas: GitLab, Jira
Proceso 8: Gestión de Riesgos
Identificación, evaluación y tratamiento de riesgos técnicos
Herramientas: Jira, Excel
Proceso 9: Gestión de Seguridad de la Información
Implementación de controles de seguridad y cumplimiento normativo
Herramientas: Políticas documentadas, controles técnicos
Proceso 10: Gestión de Incidentes de Seguridad
Detección, respuesta y documentación de incidentes de seguridad
Herramientas: Jira, ELK Stack, alertas automáticas
El modelamiento detallado de cada proceso mediante notación BPMN, con sus entradas, salidas, roles, descripción de actividades y sustento normativo fue presentado de manera exhaustiva en el Capítulo 2 del presente documento.
La evaluación del nivel de madurez actual de estos procesos frente al modelo CMMI v2.0, identificando fortalezas y brechas, se desarrolla en el Capítulo 5. El plan de implementación de mejoras, incluyendo roles, plazos y costos estimados, se presenta en el Capítulo 6.
CAPÍTULO 5: ANÁLISIS DE BRECHAS CMMI DE LOS PROCESOS DE LA ORGANIZACIÓN SELECCIONADA
5.1 Evaluación del Análisis de Brechas
La presente sección desarrolla la evaluación detallada de los procesos de la organización frente al modelo CMMI v2.0, con el propósito de identificar el nivel actual de madurez y el grado de implementación de las prácticas recomendadas por el modelo. El análisis permite reconocer qué actividades están cubiertas, cuáles se ejecutan de manera parcial y cuáles aún no forman parte del funcionamiento institucional. Este diagnóstico constituye la base para planificar acciones de mejora y determinar la alineación real entre los procesos operativos y las capacidades definidas por CMMI.
El resultado general revela que los procesos presentan integración formal de actividades CMMI. A continuación, se detalla la evaluación de brechas para cada uno de los procesos.
1. Proceso 1: Gestión de Requisitos
Cobertura: El proceso de Gestión de Requisitos presenta ahora una cobertura amplia y estructurada de prácticas CMMI v2.0, incorporando explícitamente:
DAR (evaluar alternativas de requisitos complejos)
VER (verificación de requisitos contra criterios definidos)
VAL (validación de requisitos con stakeholders)
MA (captura de métricas del proceso de requisitos)
RD (análisis de impacto de cambios en requisitos)
REQM (gestión formal de cambios de requisitos)
PQA (verificación del cumplimiento del proceso REQM)
PCM (documentación de lecciones aprendidas)
Brecha: A pesar del avance logrado, aún se identifican brechas en:
Formalizar objetivos cuantitativos del proceso de requisitos (tiempos máximos de refinamiento, límites de volatilidad, umbrales de retrabajo), ligados a enfoques de gestión cuantitativa (QPM).
Ampliar el uso de herramientas de soporte especializadas (por ejemplo, ALM/Requirements Management tools) para automatizar la trazabilidad y el control de cambios.
Integrar los indicadores del proceso de requisitos con los indicadores globales del proyecto y del portafolio, de modo que la variabilidad de requisitos se considere explícitamente en la planificación global.
Profundizar en la capacitación sistemática de stakeholders y equipo técnico en la correcta especificación, validación y revisión de requisitos, para reducir aún más la ambigüedad y el retrabajo.
Nivel estimado: El proceso evidencia prácticas consolidadas de Nivel 2 (Gestionado) y Nivel 3 (Definido), con un enfoque de mejora continua a través de métricas y lecciones aprendidas. Se puede considerar que la madurez alcanzada se sitúa en un Nivel 3 sólido.
 2. Proceso 2: Diseño y Arquitectura
	Cobertura: Parcialmente cubierta (alto avance). 
El proceso integra prácticas CMMI significativas:
OPD: Uso de activos organizacionales.
DAR: Evaluación comparativa de alternativas arquitectónicas.
MA: Definición de métricas de calidad arquitectónica.
VER y SAM: Incorporación de controles técnicos y de seguridad.
PCM: Registro estructurado de decisiones técnicas.
Brecha: Falta consolidar una verificación formal independiente antes de la aprobación del diseño (equipo V&V externo al diseño).
Nivel estimado: Nivel 3, con madurez sólida.
3. Proceso 3: Desarrollo e Implementación
Cobertura: Parcialmente cubierta (alto avance).
Incluye prácticas clave:
PQA: Revisión de estándares y cumplimiento técnico.
DAR para decisiones de implementación.
VER mediante análisis estático y herramientas automáticas.
SAM para revisión de dependencias externas.
PCM y OPD para decisiones técnicas y registro de activos.
Brecha: Falta implementar un pipeline CI/CD con gates de calidad automáticos, lo que completaría el aseguramiento del proceso.
Nivel estimado: Nivel 3.
4. Proceso 4: Verificación, Validación y Transición
Cobertura: Parcialmente cubierta con alto nivel de avance, incorporando prácticas clave de Nivel 3 y Nivel 4 del modelo CMMI. El proceso incluye actividades complejas como:
Estrategia de Prueba de Seguridad (ESEC)
Selección de muestra crítica mediante criterios formales (DAR)
Monitoreo de métricas y umbrales cuantitativos (QPPOs)
Activación de análisis de causa raíz (CAR)
Auditoría PQA
Contribución a activos organizacionales (PAD)
Brecha: A pesar del avance, aún se identifica como brecha la necesidad de:
Consolidar métricas QPPOs para todos los tipos de pruebas del proceso.
Ampliar la trazabilidad entre desviaciones detectadas en pruebas y acciones correctivas futuras.
Asegurar que las auditorías PQA se realicen de manera independiente y periódica.
Estandarizar las técnicas estadísticas utilizadas para CAR.
Nivel estimado: Nivel 3 sólido, con prácticas del Nivel 4 implementadas parcialmente.
5. Proceso 5: Operación y Mantenimiento
Cobertura: Parcialmente cubierta con integración significativa de prácticas CMMI de Nivel 3 y Nivel 4. Incluye actividades destacadas como:
Monitoreo de amenazas y vulnerabilidades (MST)
Coordinación con proveedores (SAM)
Evaluación de riesgos y tratamiento (ESEC)
Escaneo de vulnerabilidades post-deploy (MST)
Registro de reportes y lecciones aprendidas (PAD)
Brecha: Se identifican brechas principalmente en:
Estandarizar métricas cuantitativas de operación (MTTR, MTBF, tasas de reincidencia) bajo un marco MA completo.
Ampliar el uso de indicadores predictivos basados en tendencias históricas.
Consolidar acuerdos de nivel de servicio (SLAs y OLAs) bajo un enfoque formal CMMI-SAM.
Asegurar que los resultados del monitoreo MST alimenten decisiones tácticas de mejora continua.
Nivel estimado: Nivel 3 con elementos preliminares del Nivel 4, especialmente en monitoreo de amenazas y Escaneo de Vulnerabilidades.
6. Proceso 6: Planificación y Control del Proyecto
Cobertura: Parcialmente cubierta (avance considerable).
Este proceso incorpora:
MA: SPI, CPI, velocidad del equipo, densidad de defectos.
GOV: Gates de calidad estructurados.
OPD: Plantillas estandarizadas para planificación.
Brecha: No se evidencia la verificación PQA independiente sobre los planes estratégicos producidos.
Nivel estimado: Nivel 2+, con rasgos de Nivel 3.
7. Proceso 7: Gestión de Configuración
Cobertura: El proceso de Gestión de Configuración presenta una cobertura robusta y bien alineada con CMMI v2.0, integrando las siguientes prácticas:
DAR (evaluar alternativas de implementación durante el CCB)
MA (captura de métricas del cambio)
CM (auditoría de integridad de baseline)
CM (validación de integridad de baseline en producción)
PQA (verificación de cumplimiento del proceso CM)
PCM (documentación de lecciones aprendidas del proceso de cambios)
Brecha: Las brechas principales se encuentran en:
Ampliar el uso de métricas cuantitativas avanzadas (tiempo promedio de ciclo de cambio, tasa de cambios urgentes, porcentaje de cambios con rollback) como parte de un enfoque más cercano a QPM.
Integrar de forma más estrecha el proceso de CM con la gestión de riesgos y planificación del proyecto, de manera que los cambios de alto impacto sean analizados también desde una perspectiva de riesgo global.
Fortalecer la automatización entre las herramientas de versionamiento, tracking de cambios y documentación, reduciendo la dependencia de pasos manuales.
Establecer revisiones periódicas de la efectividad del proceso de CM a nivel organizacional (no solo por cambio), para ajustar políticas, criterios de aprobación y lineamientos de baseline.
Nivel estimado: El proceso presenta características claras de Nivel 3 (Definido), con un fuerte componente de aseguramiento, auditoría y mejora continua a partir de métricas y lecciones aprendidas. La madurez estimada es Nivel 3, con potencial de evolucionar hacia Nivel 4 si se fortalecen los aspectos cuantitativos
8. Gestión de Riesgos
Cobertura: El proceso presenta una cobertura amplia y avanzada de prácticas CMMI relacionadas con la gestión de riesgos. Integra de forma explícita áreas como:
Risk and Opportunity Management (RSK)
Quantitative Project Management (QPM)
Decision Analysis and Resolution (DAR)
Measurement and Analysis (MA)
Causal Analysis and Resolution (CAR)
Verification and Validation (VV)
Process Quality Assurance (PQA)
Organizational Process Performance (OPP)
Organizational Process Definition (OPD)
Brecha: Las brechas identificadas se centran principalmente en:
La necesidad de formalizar el soporte tecnológico (herramientas especializadas) para el modelado, simulación y seguimiento cuantitativo de riesgos, de manera homogénea en todos los proyectos.
Asegurar que el uso de simulaciones Monte Carlo, KRIs y análisis estadísticos sea consistente en todos los proyectos y no dependa únicamente de la madurez del equipo.
Profundizar en la difusión y capacitación del enfoque de gestión cuantitativa de riesgos hacia todas las áreas involucradas, de modo que la interpretación de los resultados sea uniforme.
Integrar de forma sistemática los resultados del análisis de riesgos en la toma de decisiones de portafolio (selección, priorización y cancelación de proyectos).
Nivel estimado: El proceso evidencia prácticas propias de Nivel 3 (Definido), Nivel 4 (Gestionado Cuantitativamente) y elementos claros de Nivel 5 (En Optimización). En términos generales, se puede considerar que la madurez alcanzada se sitúa en Nivel 4, con capacidades de mejora continua alineadas al Nivel 5.
9. Proceso 9: Gestión de Seguridad de la Información (SGSI)
Cobertura: Parcialmente cubierta.
Se integra:
DAR para selección de tratamientos de riesgo
CM para baseline del SGSI
MA para evaluación del ciclo SGSI
Brecha: No se evidencia una auditoría interna anual ni un plan de mejora continuo formalizado.
Nivel estimado: Nivel 2–3.
10. Proceso 10: Gestión de Incidentes de Seguridad
Cobertura: Parcialmente cubierta.
Incluye:
DAR (evaluación de alternativas de contención)
CM (baseline del incidente)
MA/PCM (métricas y lecciones aprendidas)
Brecha: Falta formalizar playbooks, plantillas y repositorio OPD con escenarios predefinidos.
Nivel estimado: Nivel 2–3.
5.2 Oportunidades de Mejora
A partir de los resultados del análisis de brechas, en esta sección se presentan las oportunidades de mejora correspondientes a los procesos que muestran un nivel de cobertura parcial o inexistente respecto de las prácticas CMMI v2.0. Estas oportunidades se orientan a cerrar las brechas identificadas, fortalecer la estandarización, mejorar la trazabilidad y consolidar la institucionalización de los procesos. Su objetivo es guiar la evolución de los procesos hacia niveles superiores de madurez y asegurar su sostenibilidad en el tiempo.

1. Proceso 1: Gestión de Requisitos
Definir objetivos cuantitativos de desempeño del proceso de requisitos (por ejemplo: porcentaje máximo de cambios permitidos por iteración, tiempo promedio de refinamiento, límite de ambigüedad o reprocesos) y monitorearlos sistemáticamente.
Integrar una herramienta especializada de gestión de requisitos que permita automatizar la trazabilidad (requisito–diseño–código–prueba) y el historial de cambios, reduciendo la dependencia de hojas de cálculo o documentos aislados.
Incorporar sesiones periódicas de análisis causal (CAR) cuando se detecte alta volatilidad de requisitos o un aumento significativo de cambios tardíos, para identificar causas raíz (falta de claridad de negocio, mala priorización, escaso involucramiento de usuarios, etc.).
Fortalecer la alineación entre el proceso de requisitos y el proceso de planificación del proyecto, de modo que la variabilidad de requisitos se vea reflejada en el cronograma, presupuesto y gestión de riesgos.
Estructurar un programa de capacitación continua para Analistas de Negocio, Product Owners y stakeholders, sobre buenas prácticas de redacción, priorización y validación de requisitos alineadas a CMMI.
 2. Proceso 2: Diseño y Arquitectura
Implementar revisiones formales independientes del diseño (peer review técnico).
Definir métricas adicionales de completitud y cumplimiento de estándares OPD.
Documentar los riesgos arquitectónicos y su tratamiento asociado.
3. Proceso 3: Desarrollo e Implementación
Establecer un pipeline CI/CD con validaciones automáticas en cada merge.
Estandarizar criterios de aceptación y pruebas unitarias mínimas.
Integrar dashboards de calidad en tiempo real.
4. Proceso 4: Verificación, Validación y Transición
Fortalecer la definición y documentación de umbrales cuantitativos (QPPOs) para todos los tipos de prueba, incluyendo rendimiento, seguridad y regresión.
Estandarizar el proceso de auditoría PQA para que sea realizado por un rol independiente y bajo un cronograma periódico.
Implementar plantillas formales para análisis CAR con técnicas estadísticas uniformes (Pareto, Ishikawa, 5-Whys).
Integrar métricas QPPOs a los indicadores de calidad del proyecto para asegurar decisiones basadas en datos durante la ejecución de V&V.
Ampliar la contribución de activos PAD mediante la creación de guías de prueba reutilizables, bancos de casos y repositorios de defectos históricos.
5. Proceso 5: Operación y Mantenimiento
Completar la estructura de monitoreo con métricas MA más robustas:
MTTR, MTBF, MTTA, % reincidencia, % incidentes por categoría.
Integrar dashboards predictivos que permitan anticipar fallos o vulnerabilidades recurrentes.
Definir SLAs y OLAs alineados con prácticas SAM para fortalecer acuerdos con proveedores internos y externos.
Formalizar retroalimentación continua entre MST ↔ Mantenimiento para que vulnerabilidades detectadas desencadenen mejoras estructurales.
Incorporar sesiones periódicas de CAR para incidentes de operación críticos, potenciando la reducción de recurrencias.
6. Proceso 6: Planificación y Control del Proyecto
Incluir revisiones de calidad PQA sobre los planes antes de su aprobación.
Documentar umbrales de desempeño como parte del repositorio OPD.
7. Proceso 7: Gestión de Configuración
Definir un conjunto de indicadores clave de desempeño del proceso de CM, tales como: tiempo promedio desde la creación de la solicitud de cambio hasta su cierre, porcentaje de cambios que requieren retrabajo, cambios que generan incidentes en producción, etc.
Integrar el proceso de CM con la gestión de riesgos, estableciendo que ciertos tipos de cambio (por ejemplo, cambios en arquitectura crítica o componentes de seguridad) requieran análisis de riesgo y decisiones más estrictas de aprobación.
Establecer revisiones periódicas del proceso CM a nivel organizacional (por ejemplo, trimestrales), para ajustar criterios de prioridad, políticas de versiones, nomenclatura y prácticas de branching.
8. Gestión de Riesgos
Estandarizar el uso de simulación Monte Carlo y modelos cuantitativos como parte obligatoria de la gestión de riesgos en todos los proyectos de cierto tamaño o criticidad, evitando que quede solo como una buena práctica opcional.
Incorporar una herramienta corporativa de gestión de riesgos (por ejemplo, integrada al PMO o SGSI) que permita registrar riesgos, controles, KRIs, resultados de simulaciones y tendencias de forma centralizada.
Fortalecer la articulación entre gestión de riesgos y gobierno del portafolio, asegurando que la exposición agregada al riesgo sea un insumo clave para priorizar proyectos, asignar recursos y aprobar iniciativas.
Profundizar en la capacitación del personal (gestores de riesgos, líderes de proyecto, CISO, arquitectos) en técnicas avanzadas de análisis cuantitativo, interpretación de curvas de probabilidad y toma de decisiones bajo incertidumbre.
Formalizar un ciclo de revisión periódica de modelos y supuestos (distribuciones, parámetros, umbrales de apetito de riesgo) a la luz de datos reales, para mantener calibrado el enfoque cuantitativo y asegurar que los modelos reflejen fielmente el contexto de la organización.
9. Proceso 9: Gestión de Seguridad de la Información (SGSI)
Institucionalizar auditorías internas periódicas.
Crear métricas del plan de tratamiento y generar reportes recurrentes.
Establecer un proceso de mejora continua del SGSI.
10. Proceso 10: Gestión de Incidentes de Seguridad
Crear playbooks estandarizados con flujos de trabajo predefinidos.
Añadir métricas avanzadas como MTTD (Time to Detect) y MTTC (Time to Contain).
Formalizar retrospectivas post-incidente para mejorar la capacidad de respuesta.
5.3 Fortalezas identificadas en la evaluación de los procesos
La presente sección resume las fortalezas detectadas durante la evaluación de los procesos, destacando aquellos elementos que contribuyen positivamente al desempeño organizacional y que pueden servir como base para la instauración de prácticas más maduras. Identificar fortalezas es esencial para comprender los aspectos que funcionan adecuadamente, potenciar las capacidades existentes y aprovechar estos elementos como cimiento para la mejora continua y la consolidación del modelo CMMI dentro de la organización.
    5.3.1 Fortalezas Generales
La organización cuenta con roles claramente definidos (Líder de Proyecto, Arquitecto, CISO, Analista de Riesgos, Desarrollador, Especialista de Control), lo que facilita la asignación de responsabilidades y la ejecución coordinada de los procesos.
Uso de herramientas profesionales de gestión y aseguramiento de la calidad, tales como Jira, Confluence, SonarQube, Power BI y repositorios OPD, que fortalecen la trazabilidad, automatización y análisis.
Se observa una orientación hacia prácticas ágiles, permitiendo una combinación eficiente de SCRUM con prácticas formales del modelo CMMI.
Existe una adopción progresiva del ciclo PHVA, especialmente en procesos relacionados con SGSI e Incidentes de Seguridad.
Algunos procesos muestran integración activa de prácticas DAR, MA, CM, PCM y PQA, lo que evidencia madurez inicial en toma de decisiones, medición, control y mejora continua.
Se identificó un esfuerzo sostenido en la documentación de decisiones técnicas, lo que contribuye a la trazabilidad y a la construcción de conocimiento organizacional.
    5.3.2 Fortalezas por Proceso
1. Proceso 1: Gestión de Requisitos
El proceso incorpora un conjunto completo de prácticas CMMI (DAR, VER, VAL, MA, RD, REQM, PQA, PCM), que abarcan desde la toma de decisiones hasta la mejora continua, lo que refleja un enfoque altamente estructurado.
La combinación de verificación (VER) y validación (VAL) permite asegurar tanto la calidad técnica de los requisitos como su alineación con las necesidades reales de negocio, reduciendo significativamente el riesgo de desarrollar funcionalidades equivocadas.
La existencia de métricas del proceso de requisitos (MA) y análisis de impacto (RD) favorece la toma de decisiones informada y la prevención de problemas derivados de cambios no controlados.
La gestión de cambios de requisitos mediante REQM garantiza la trazabilidad y el control de versiones, manteniendo la coherencia entre requisitos, diseño, código y pruebas.
La incorporación de PQA y PCM cierra el ciclo de calidad y aprendizaje, asegurando que el proceso se ejecute de acuerdo con lo definido y que la organización capitalice la experiencia adquirida en cada proyecto.
 	2. Proceso 2: Diseño y Arquitectura
Existencia de un proceso formalizado de evaluación de alternativas mediante prácticas DAR, lo que mejora la calidad y justificación de las decisiones arquitectónicas.
Uso del repositorio OPD para consultar y actualizar patrones, lineamientos y plantillas arquitectónicas, fortaleciendo la estandarización.
Integración de métricas de calidad arquitectónica (MA) que permiten medir comportamientos clave del diseño.
Inclusión de controles técnicos y de seguridad (VER, SAM) dentro del diseño detallado, asegurando cumplimiento de requisitos no funcionales.
Registro sistemático de decisiones técnicas y arquitectónicas mediante PCM, contribuyendo a la trazabilidad y mejora continua.
3. Proceso 3: Desarrollo e Implementación
Aplicación de estándares de codificación segura y revisiones iniciales (PQA) que reducen riesgos de defectos y vulnerabilidades.
Evaluación comparada de enfoques de implementación mediante DAR, lo que permite seleccionar soluciones técnicas óptimas.
Implementación de verificación automatizada mediante análisis estático (SAST), fortaleciendo la calidad antes de integración.
Uso de SAM para controlar riesgos asociados a librerías externas y dependencias, garantizando integridad del build.
Registro y trazabilidad de decisiones técnicas a través de PCM, además de la actualización del repositorio OPD con activos relevantes.
4. Proceso 4: Verificación, Validación y Transición
El proceso incorpora prácticas avanzadas como CAR, DAR, ESEC y PQA, lo que demuestra un enfoque integral orientado a la calidad y seguridad desde etapas tempranas.
El uso de umbrales cuantitativos QPPOs permite decisiones basadas en datos y un control predictivo del desempeño.
La auditoría formal de cumplimiento del proceso garantiza consistencia en la ejecución de V&V y fortalece la disciplina operativa.
La integración de activos y lecciones aprendidas (PAD) fomenta la reutilización del conocimiento y asegura continuidad en la mejora de pruebas.
El proceso se encuentra alineado a un marco de madurez superior, incorporando técnicas estadísticas y gobernanza robusta.
5. Proceso 5: Operación y Mantenimiento
La inclusión de MST permite gestionar amenazas y vulnerabilidades de manera proactiva, fortaleciendo la estabilidad del entorno productivo.
El proceso incorpora prácticas SAM que aseguran el control de la cadena de suministro y la calidad de los proveedores.
El escaneo post-deploy demuestra una preocupación continua por la seguridad operacional, reduciendo riesgos de vulnerabilidades nuevas.
La contribución sistemática de activos y lecciones aprendidas (PAD) potencia la mejora continua y la estandarización de la operación.
La conexión entre mantenimiento, cambios y SGSI evidencia un proceso integral, consistente y alineado con estándares de seguridad.
6. Proceso 6: Planificación y Control del Proyecto
Establecimiento de métricas clave de control del proyecto como SPI, CPI, velocidad del equipo y densidad de defectos, lo que permite un seguimiento objetivo.
Definición de gates de calidad con criterios formales de aprobación (Fin de Requisitos, Diseño, Desarrollo, Pruebas), alineados a prácticas GOV.
Uso activo del repositorio OPD para emplear plantillas estandarizadas de planificación, cronograma y presupuesto.
Integración de datos históricos y métricas previas para mejorar estimaciones y calibraciones del proyecto.
7. Proceso 7: Gestión de Configuración
El proceso de Gestión de Configuración integra prácticas CMMI fundamentales (DAR, MA, CM, PQA, PCM) que permiten controlar el ciclo completo del cambio, desde el análisis y decisión hasta la auditoría y la mejora continua.
La realización de auditorías de integridad de baseline y la posterior validación en producción garantizan que las versiones liberadas sean coherentes, completas y correctamente desplegadas, reduciendo la probabilidad de incidentes.
La captura de métricas del cambio (MA) permite entender el comportamiento del proceso, identificar cuellos de botella y tipos de cambios más problemáticos, lo que habilita acciones de mejora focalizadas.
La documentación sistemática de lecciones aprendidas (PCM) contribuye a un repositorio de conocimiento organizacional que facilita la gestión de cambios futuros, especialmente en sistemas complejos o críticos.
8. Gestión de Riesgos
El proceso integra de forma explícita y coherente prácticas de RSK, QPM, DAR, MA, CAR, PQA, OPP y OPD, demostrando un enfoque integral que abarca identificación, análisis, tratamiento, monitoreo y mejora continua de los riesgos.
La incorporación de taxonomías de riesgo, criterios de probabilidad e impacto, matriz de criticidad y apetito de riesgo organizacional evidencia una gestión sistemática y alineada a buenas prácticas internacionales.
El uso de simulación Monte Carlo e indicadores de riesgo (KRIs) permite cuantificar la exposición al riesgo con un alto grado de objetividad, lo que habilita decisiones basadas en datos en lugar de percepciones subjetivas.
La actualización del modelo de riesgos con datos reales y el análisis de tendencias refuerzan una cultura de aprendizaje continuo, acercando el proceso a las características del Nivel 4 y 5 del modelo CMMI.
La contribución sistemática de lecciones aprendidas al repositorio organizacional fortalece los activos de proceso, facilita la reutilización del conocimiento y permite que cada nuevo proyecto parta de una base de experiencia consolidada en gestión de riesgos.
9. Proceso 9: Gestión de Seguridad de la Información (SGSI)
Incluye prácticas de análisis y decisión estructurada (DAR) para seleccionar tratamientos de riesgo adecuados.
Se establece una línea base del SGSI (CM) para garantizar trazabilidad, integridad documental y control de versiones.
Se integran métricas del ciclo SGSI (MA) que permiten evaluar efectividad de controles, reducción del riesgo residual y tendencias de seguridad.
El proceso presenta un ciclo cíclico y medible, con actividades previas al cierre que aseguran decisiones basadas en datos.
10. Proceso 10: Gestión de Incidentes de Seguridad
Evaluación formal de alternativas de contención mediante DAR, fortaleciendo decisiones bajo presión.
Creación de una línea base del incidente (CM) que centraliza evidencias, logs, cronología y resultados del análisis.
Integración de métricas del incidente (tiempos de respuesta, contención y resolución), así como la revisión de efectividad de acciones.
Documentación de lecciones aprendidas (PCM), permitiendo retroalimentar el SGSI y mejorar la capacidad institucional de respuesta ante incidentes.
CAPÍTULO 6: IMPLEMENTACIÓN DE MEJORAS DE LOS PROCESOS DE LA ORGANIZACIÓN SELECCIONADA
6.1 Planificación de la implementación de mejoras
Esta sección presenta la planificación detallada para implementar las mejoras propuestas en los procesos de la organización, con el objetivo de fortalecer su alineamiento con el modelo CMMI v2.0 y elevar su nivel de madurez.
La planificación considera los roles involucrados en cada proceso, el plazo estimado para la implementación y un costo aproximado asociado a la capacitación, herramientas y horas hombre necesarias.
El propósito es asegurar una adopción ordenada, medible y sostenible de las prácticas propuestas, de manera que cada proceso avance progresivamente hacia un funcionamiento más estructurado, predecible y gestionado.
A continuación, se presenta la planificación para cada uno de los 10 procesos definidos.

1. Proceso 1: Gestión de Requisitos
Roles involucrados: Stakeholders/Usuario clave, Analista de Negocio / Product Owner, Arquitecto(a), Equipo de Desarrollo, QA/Testing, Seguridad de la Información (CISO/SGSI), Gestión de Configuración, Gestión de Proyecto/PMO.
Plazo estimado: 6 semanas.
Costo estimado: S/. 5,500.
Mejoras a implementar:
Establecer un flujo formal de elicitation - análisis - validación de requisitos.
Definir matriz de trazabilidad bidireccional.
Implementar control de cambios de requisitos mediante CM y PMO.
Crear criterios de aceptación estandarizados y revisados por QA/SGSI.
Actualizar OPD con plantillas de requisitos, validación, backlog y aceptación.
2. Proceso 2: Diseño y Arquitectura
Roles involucrados: Arquitecto de Software, CISO, Equipo de Desarrollo Senior, Jefe de Proyecto, Stakeholders Clave.
Plazo estimado: 4 semanas.
Costo estimado: S/. 3,200.
Mejoras a implementar:
Formalizar revisiones arquitectónicas independientes (peer reviews).
Documentar métricas de cumplimiento arquitectónico.
Incorporar validación temprana de seguridad en el diseño (SAM).
Actualizar plantillas OPD para decisiones técnicas (PCM).
3. Proceso 3: Desarrollo e Implementación
Roles involucrados: Desarrolladores, Equipo de QA, DevOps, CISO, Arquitecto de Software, Jefe de Proyecto.
Plazo estimado: 8 semanas.
Costo estimado: S/. 9,000.
Mejoras a implementar:
Crear pipeline CI/CD con gates de calidad automáticos.
Configurar análisis estático SAST y controles de seguridad en repositorios.
Definir criterios de aceptación mínimos para merges.
Mantener decisiones técnicas y estándares en OPD.
4. Proceso 4: Verificación, Validación y Transición
Roles involucrados: Product Owner, Analista de Negocio, Equipo de QA, Desarrollador, Oficial de Seguridad, DevOps, Gestor de Configuración, Release Manager, Soporte/Operaciones.
Plazo estimado: 6 semanas.
Costo estimado: S/. 4,800.
Mejoras a implementar:
Diseñar plan maestro de pruebas (funcional, integración, seguridad, rendimiento).
Implementar validación formal con stakeholders y usuarios.
Definir flujo de transición con control de versiones, despliegue y aceptación formal.
5. Proceso 5: Operación y Mantenimiento
Roles involucrados: Usuario final, Service Desk, DevOps, Equipo de Mantenimiento, Gestor de Cambios, Gestión de Configuración, Seguridad de la Información, Service Manager, Proveedores externos.
Plazo estimado: 5 semanas.
Costo estimado: S/. 3,000.
Mejoras a implementar:
Establecer métricas MTTR, MTBF y tendencia de incidentes.
Formalizar control de cambios en producción con CCB.
Definir retroalimentación sistemática para lecciones aprendidas operativas.
6. Proceso 6: Planificación y Control del Proyecto
Roles involucrados: Líder de Planificación del Proyecto, Especialista en Métricas, Director de Proyectos TI, Coordinador de Seguridad, Analista de Riesgos TI, Encargado de Configuración, Especialista de Calidad, Validador Normativo, Patrocinador Ejecutivo, Representante de Usuarios Finales, Coordinador de Comunicaciones.
Plazo estimado: 3 semanas.
Costo estimado: S/. 2,200.
Mejoras a implementar:
Validación PQA del plan antes de aprobación.
Integración de métricas históricas y predictivas en el cronograma.
Aplicar gestión de riesgos desde la planificación inicial.
7. Proceso 7: Gestión de Configuración
Roles involucrados: Gestor de Configuración, Equipo de Desarrollo, CCB, Equipo de QA.
Plazo estimado: 4 semanas.
Costo estimado: S/. 3,600.
Mejoras a implementar:
Definir elementos de configuración (CIs).
Crear líneas base para cada fase del proyecto.
Implementar CCB formal para aprobar cambios.
Documentar el estado de configuración periódicamente.
8. Gestión de Riesgos
Roles involucrados: Oficial de Seguridad, Comité de Riesgos, Analista de Seguridad, Arquitecto de Seguridad, Equipos de Desarrollo/Operaciones, Gestor de Riesgos, Dueños de Riesgo, Auditor.
Plazo estimado: 4 semanas.
Costo estimado: S/. 3,000.
Mejoras a implementar:
Crear estructura formal de identificación y evaluación de riesgos (DAR).
Establecer métricas de riesgo: impacto, probabilidad, exposición residual.
Definir revisiones periódicas con el Comité de Riesgos.
Registrar lecciones aprendidas en PCM.
9. Proceso 9: Gestión de Seguridad de la Información (SGSI)
Roles involucrados: CISO, Gerencia TI, Equipo de Riesgos y Cumplimiento, Equipos Técnicos, RRHH, Auditor Externo.
Plazo estimado: 5 semanas.
Costo estimado: S/. 4,500.
Mejoras a implementar:
Realizar auditoría interna anual al SGSI.
Integrar métricas de control y plan de tratamiento.
Fortalecer capacitación continua y evaluaciones internas.
10. Proceso 10: Gestión de Incidentes de Seguridad
Roles involucrados: Usuarios/RRHH, CISO, Equipos Técnicos, Alta Dirección.
Plazo estimado: 4 semanas.
Costo estimado: S/. 4,200.
Mejoras a implementar:
Elaborar playbooks por tipo de incidente.
Establecer métricas avanzadas MTTD, MTTC, MTTR.
Implementar post-mortem estandarizado en PCM.
6.2 Sustento de las mejoras propuestas
Esta sección presenta el fundamento técnico y metodológico de cada mejora planteada para los procesos de la organización.
El objetivo es demostrar cómo cada acción propuesta incorpora prácticas específicas del modelo CMMI v2.0, fortaleciendo áreas clave como evaluación de alternativas, control de configuración, aseguramiento de calidad, medición, gestión de riesgos y mejora continua.
Este sustento permite justificar por qué las mejoras seleccionadas contribuyen directamente al incremento de la madurez de los procesos y cómo impactan positivamente en la consistencia, trazabilidad y desempeño de la organización.

1. Proceso 1: Gestión de Requisitos
Las mejoras propuestas incorporan de manera directa las prácticas definidas por el área RDM (Requirements Development and Management) del modelo CMMI. La formalización del levantamiento, análisis y validación de requisitos responde a las prácticas RDM 2.1 y 2.3, las cuales establecen que los requisitos deben documentarse, clasificarse, validarse y mantenerse actualizados a lo largo del ciclo de vida del proyecto.
La implementación de una trazabilidad bidireccional vincula cada requisito con sus casos de prueba, entregables y módulos técnicos, alineándose con las prácticas RDM 2.5 y 2.6, reduciendo la ambigüedad y el riesgo de funcionalidades incompletas o mal interpretadas.
Asimismo, el establecimiento de un proceso formal de control de cambios sigue lo establecido en RDM 3.1, garantizando que cualquier modificación se analice por impacto, se priorice y se apruebe mediante mecanismos institucionalizados como el CCB o PMO. Esto evita desviaciones del alcance y asegura consistencia entre lo solicitado y lo entregado.
La incorporación de criterios de aceptación estructurados fortalece la práctica VALIDATION (VAL) y asegura que los stakeholders tengan un mecanismo objetivo para evaluar si un requisito ha sido correctamente implementado.
Estas mejoras permiten que el proceso evolucione desde prácticas reactivas hacia un control formal, aumentando la capacidad de planificación y reduciendo significativamente el retrabajo.
2. Proceso 2: Diseño y Arquitectura
Las mejoras propuestas fortalecen el proceso mediante la incorporación de prácticas del área DAR (Decision Analysis and Resolution), que exigen evaluar alternativas técnicas antes de tomar decisiones arquitectónicas críticas.
La inclusión de revisiones técnicas independientes se alinea con las prácticas VER 2.1 y VER 2.2, que establecen que los productos deben ser verificados mediante criterios técnicos, herramientas y roles especializados, permitiendo identificar defectos en etapas tempranas del diseño.
La integración explícita de controles de seguridad desde la fase de arquitectura responde a las prácticas SAM (Supplier Agreement Management) y a actividades de protección definidas en modelos complementarios como ISO 27001. Incorporar seguridad por diseño garantiza que los riesgos arquitectónicos se mitiguen antes de la construcción, reduciendo la exposición futura a vulnerabilidades.
Finalmente, la documentación de decisiones arquitectónicas mediante PCM y su incorporación al OPD (Organizational Process Definitions) institucionaliza el conocimiento técnico, facilitando replicabilidad, auditoría y aprendizaje continuo. Esto permite que el proceso avance hacia un estado definido, característico del Nivel de Madurez 3.
3. Proceso 3: Desarrollo e Implementación
Las mejoras propuestas integran prácticas de los componentes PQA, VER, SAM, MA y PCM del CMMI. La creación de un pipeline CI/CD garantiza la verificación continua y automatizada del producto, en cumplimiento con VER 2.2, permitiendo que la calidad se valide antes, durante y después del desarrollo.
El uso de análisis estático (SAST) fortalece las prácticas de verificación técnica y seguridad, asegurando que las vulnerabilidades se identifiquen de manera sistemática, en línea con las prácticas SAM 2.1 y 2.2.
El establecimiento de criterios mínimos de aceptación para merges formaliza estándares de codificación y control de calidad, respondiendo a PQA 2.1 y asegurando cumplimiento antes de integrar los cambios al repositorio principal. Asimismo, la actualización del OPD con estándares, lineamientos y definiciones técnicas institucionaliza el conocimiento generado y facilita la consistencia entre equipos.
Estas prácticas incrementan la predictibilidad del desarrollo, reducen defectos en producción y aseguran una alineación clara entre el diseño y la implementación, consolidando el proceso como altamente robusto.
4. Proceso 4: Verificación, Validación y Transición
Las mejoras propuestas se alinean directamente con los componentes de VER (Verification) y VAL (Validation) del CMMI.
La creación de un plan maestro de pruebas normaliza las actividades de validación técnica, funcional, de seguridad y rendimiento. Esto se ajusta a la práctica VER 2.1, que establece que las verificaciones deben planificarse, ejecutarse y documentarse de manera sistemática.
La incorporación de validaciones formales con usuarios y stakeholders fortalece la práctica VAL 2.2, garantizando que el producto final sea evaluado en relación con su propósito de uso antes de ser aceptado.
La implementación de un proceso controlado de transición con liberación, aprobación y post-despliegue responde a la necesidad de reducir riesgos operativos y asegurar que el entorno productivo reciba versiones estables y verificadas.
Además, la participación de roles especializados como DevOps, Seguridad, QA y Gestión de Configuración permite una supervisión integral, elevando la calidad y confiabilidad del proceso.
5. Proceso 5: Operación y Mantenimiento
Las mejoras integran prácticas de MA (Measurement and Analysis), CM (Configuration Management) y PCM (Process and Product Quality Management) del modelo CMMI.
La definición de métricas operativas como MTTR, MTBF y tasa de reabrimiento permite medir la efectividad del mantenimiento, identificar patrones y tomar decisiones basadas en datos, alineándose con MA 2.1 y MA 2.3.
El uso de un control de cambios formal para producción mediante CCB refuerza las prácticas de CM 2.1, garantizando que las modificaciones sean evaluadas y aprobadas antes de su ejecución.
El registro de lecciones aprendidas y problemas recurrentes fortalece la práctica PCM 2.4, promoviendo la mejora continua del servicio y evitando que incidentes similares se repitan.
Estas mejoras permiten que el proceso transite desde un enfoque reactivo hacia uno gestionado y predecible, incrementando la estabilidad del servicio y la satisfacción de los usuarios.
6. Proceso 6: Planificación y Control del Proyecto
Las mejoras propuestas se sustentan en prácticas del área GOV (Governance), MA (Measurement and Analysis) y PQA (Process Quality Assurance) del modelo CMMI.
La validación temprana del plan del proyecto mediante PQA permite asegurar que se cumplan los estándares de planificación, mitigando riesgos desde el inicio. Esto se alinea con PQA 2.1, que exige verificar objetivamente que los procesos definidos se sigan adecuadamente.
La incorporación de métricas de desempeño, como SPI, CPI, velocidad y análisis de variaciones, fortalece MA 2.4, facilitando la toma de decisiones informada y oportuna.
El uso de datos históricos y métricas predictivas vincula el proceso con prácticas de madurez superiores, asegurando que las estimaciones se basen en evidencia verificable.
Finalmente, la integración de gestión de riesgos desde etapas tempranas del proyecto permite una planificación más robusta acorde con Risk Management en CMMI, aumentando la capacidad de respuesta ante incertidumbres.
7. Proceso 7: Gestión de Configuración
Las mejoras incorporan completamente las prácticas de CM 1.1, CM 1.2 y CM 2.1, estableciendo un proceso formal de identificación, control y auditoría de elementos de configuración.
La definición de CIs y líneas base fortalece la trazabilidad y el control del producto, permitiendo identificar qué versión fue evaluada o liberada en cada etapa.
La creación de un Comité de Control de Cambios (CCB) estructurado responde directamente al requerimiento de CM 2.1, garantizando que las modificaciones se evalúen por impacto, dependencia y riesgo antes de ser implementadas. Además, los informes de estado de configuración facilitan auditorías internas y la detección temprana de discrepancias.
Estas mejoras elevan este proceso desde un nivel inicial hacia un nivel totalmente gestionado, reduciendo errores por versiones incorrectas y asegurando alineación entre componentes técnicos y documentación.
8. Gestión de Riesgos
Las mejoras integran prácticas fundamentales del área DAR, MA y PCM.
La identificación estructurada de riesgos, junto con su evaluación mediante probabilidad e impacto, permite operacionalizar las prácticas de MA 2.1 (recolección de datos) y MA 2.3 (análisis y monitoreo).
El uso de análisis comparativo para seleccionar tratamientos de riesgo se alinea con DAR 2.1, donde la toma de decisiones debe sustentarse en alternativas evaluadas formalmente.
El registro de lecciones aprendidas y riesgos emergentes fortalece PCM 2.4, permitiendo retroalimentar futuros ciclos de evaluación.
La participación activa del Comité de Riesgos, Dueños de Riesgo y Auditoría asegura una gobernanza adecuada y una visión estratégica del tratamiento del riesgo.
9. Proceso 9: Gestión de Seguridad de la Información (SGSI)
Las mejoras propuestas consolidan prácticas de CM, MA, PCM y controles del ciclo PHVA aplicados al SGSI.
La implementación de auditorías internas y la construcción de métricas de efectividad de controles alinean el proceso con MA 2.4, permitiendo evaluar la eficiencia real del plan de tratamiento del riesgo.
La actualización continua del baseline del SGSI fortalece CM 1.2, asegurando que la documentación de políticas, procedimientos y evidencias se mantenga íntegra y consistente.
La incorporación sistemática de acciones correctivas y mejoras continúa mediante PCM permite que el proceso mantenga una evolución constante, característica de organizaciones en niveles de madurez superiores.
Estas mejoras fortalecen la resiliencia de la organización frente a amenazas y aseguran cumplimiento normativo.
10. Proceso 10: Gestión de Incidentes de Seguridad
Las mejoras aplican de manera directa prácticas de DAR, CM, MA y PCM, permitiendo estructurar completamente la respuesta ante incidentes.
La creación de playbooks estandarizados fortalece la práctica DAR 2.1, permitiendo que las decisiones bajo presión se basen en criterios predefinidos y comparables.
El registro de cada incidente como una línea base formal del proceso se alinea con CM 1.2, asegurando trazabilidad y consistencia de los datos recopilados.
La definición de métricas avanzadas (MTTD, MTTC, MTTR) responde a MA 2.3 y MA 2.4, permitiendo evaluar tiempos, eficiencia operativa y efectividad de las medidas aplicadas.
Finalmente, el post-mortem estructurado mediante PCM garantiza que cada incidente aporte al aprendizaje institucional, fortaleciendo la capacidad de prevención y respuesta del SGSI.
CONCLUSIONES - TP
Djalma:
El desarrollo de los procesos de Diseño y Arquitectura y Desarrollo e Implementación permitió comprender la importancia de estructurar el ciclo de vida del software bajo estándares internacionales. Aplicar las normas ISO 12207, 27001 y 27002 no solo ayudó a ordenar las actividades, sino también a fortalecer la seguridad, la trazabilidad y la calidad de los productos generados.
Durante la elaboración de los diagramas BPMN y la definición de roles, se logró representar de manera clara la interacción entre los diferentes actores del proyecto. Este enfoque permitió identificar responsabilidades, dependencias y puntos de control que garantizan un desarrollo más eficiente y alineado con los objetivos de la organización.
Finalmente, el trabajo evidenció que integrar la seguridad desde el diseño hasta la implementación es una práctica esencial. Incorporar revisiones del CISO, validaciones técnicas del arquitecto y controles de configuración en cada etapa contribuye a reducir riesgos, asegurar la integridad del software y fomentar una cultura de desarrollo seguro y de mejora continua.
Diego:
La elaboración del mapa de procesos permitió identificar con precisión los flujos críticos del área de TI y cómo se interrelacionan los componentes técnicos, organizativos y de seguridad. Integrar las normas ISO/IEC 12207, ISO/IEC 27001 y CMMI v2.0 facilitó un enfoque sistemático orientado a la madurez, donde cada proceso tiene entradas, salidas y controles definidos, promoviendo la trazabilidad y la estandarización.
El diseño de los procesos bajo notación BPMN reflejó la importancia de la comunicación visual entre los equipos técnicos y de gestión, mejorando la comprensión de roles y dependencias dentro del ciclo de vida del software.
Finalmente, el trabajo evidenció que la calidad y la seguridad no son fases aisladas, sino principios transversales que deben integrarse desde la planificación hasta la operación, generando una cultura de mejora continua sustentada en datos y evidencia auditable.
Brenda:
La definición del contexto de InnovaTech Solutions, su misión, visión y estructura organizacional, permitió comprender cómo los procesos técnicos se alinean con los objetivos estratégicos del negocio.
La elaboración del marco de selección de procesos y la documentación del área de TI contribuyeron a fortalecer la gestión interna y a mejorar la comunicación entre los niveles estratégicos, tácticos y operativos.
El trabajo evidenció que la calidad de software no solo depende de la ingeniería técnica, sino también de la gestión organizacional y de una cultura que priorice la transparencia, la mejora continua y el cumplimiento normativo en todos los niveles.
Saul:
El análisis de los procesos de Gestión de Riesgos y Gestión de Seguridad de la Información permitió aplicar de forma práctica los principios de las normas ISO 27001 y 27002, evidenciando cómo una correcta administración de amenazas protege los activos críticos de información.
La incorporación de controles de seguridad en cada fase del ciclo de vida del software fortaleció el enfoque DevSecOps, garantizando que las vulnerabilidades sean tratadas de manera proactiva y no reactiva.
El trabajo demostró que la madurez en seguridad no se logra solo con políticas, sino con procedimientos documentados, métricas medibles y personal consciente de su responsabilidad en la protección de la información.
Javier:
La participación en los procesos de Verificación, Validación y Transición permitió profundizar en la aplicación práctica de los principios de aseguramiento de calidad establecidos en la ISO 12207 y CMMI v2.0.
El diseño de flujos de prueba, control de cambios y aceptación permitió identificar puntos críticos de mejora en la gestión del ciclo de vida, fomentando una cultura de validación temprana y continua.
Además, la integración de controles de ISO 27002 dentro de las pruebas de software demostró que la seguridad debe ser verificada en paralelo al cumplimiento funcional, reforzando el concepto de “calidad total” dentro del desarrollo organizacional.
CONCLUSIONES - TF
Djalma:
Los procesos analizados cuentan con una estructura completa y bien definida que abarca todas las etapas clave del ciclo de vida del software, lo que permite mantener orden, claridad y control en cada actividad realizada durante el proyecto.
Los procesos 2 y 6 reflejan una cultura sólida de calidad y mejora continua, ya que incorporan revisiones, validaciones, métricas y herramientas que permiten detectar errores tempranamente y asegurar estándares consistentes en cada entrega.
Existe una integración adecuada entre diseño e implementación, lo cual facilita la trazabilidad, asegura coherencia técnica y permite que el conocimiento generado en cada proyecto se consolide y retroalimente a la organización.

Diego:
Caracterización organizacional completa: Se logró documentar la estructura de InnovaTech Solutions con suficiente detalle para sustentar el análisis de madurez CMMI, incluyendo datos operativos, estructura de TI con 42 personas y contexto regulatorio relevante para el sector FinTech.
Metodología de ciclo de vida híbrida definida: Se estableció un modelo que combina Scrum con prácticas formales de gestión, permitiendo equilibrar agilidad con el cumplimiento normativo requerido en el sector financiero mediante 6 fases claramente delimitadas.
Integración efectiva del mapa de procesos: Se presentó el mapa de procesos en 4 niveles (estratégico, ciclo software, gestión proyectos y seguridad) que articula coherentemente con los 10 procesos BPMN modelados previamente y sirve de base para la evaluación de brechas posterior.


Brenda:
Se integraron exitosamente prácticas de las áreas PLAN y RSK de CMMI v2.0, elevando el nivel de formalidad de ambos procesos desde el enfoque inicial ISO 12207.
Se establecieron métricas cuantificables (variación de cronograma, riesgos materializados) que permiten evaluar objetivamente el nivel de madurez actual de ambos procesos.
Se especificaron herramientas concretas (Jira, Microsoft Project) que facilitan la implementación práctica de las mejoras propuestas y refuerzan la viabilidad del plan.
Saul:
La evaluación integral de los procesos de la organización evidencia un nivel de madurez heterogéneo, donde los procesos relacionados con la seguridad de la información (Proceso 9) y la gestión de incidentes (Proceso 10) muestran un mayor grado de institucionalización. 
La incorporación de prácticas CMMI como DAR, MA, CM y PCM en los procesos 9 y 10 fortalece la capacidad de la organización para responder a amenazas y eventos críticos. El uso de métricas, líneas base, decisiones comparadas y registro de lecciones aprendidas permite una gestión más precisa, medible y basada en evidencia, alineada con marcos modernos de seguridad.
La integración de roles especializados (CISO, Comité de Riesgos, DevOps, QA, Auditoría) contribuye positivamente al despliegue de prácticas formales, especialmente en los procesos de seguridad.
Javier:
La incorporación de métricas de desempeño MPM y en Análisis de Causa Raíz CAR en el proceso de Gestión de Riesgos habilita la predicción del desempeño y la cuantificación de la reducción de riesgos.
El modelamiento BPMN reflejó la importancia de la comunicación visual y la definición de roles en cada flujo, lo que garantiza que las actividades se ejecutan de manera eficiente y alineada con los objetivos estratégicos.
El trabajo demostró que la calidad total no se logra solo con pruebas funcionales, sino verificando la seguridad y el cumplimiento normativo en paralelo al desempeño técnico.
RECOMENDACIONES - TP
Djalma:
Se recomienda mantener actualizados los procedimientos definidos en los procesos, revisándolos de forma periódica para que sigan alineados con las versiones más recientes de las normas ISO y con las necesidades específicas de los proyectos futuros.
Es importante continuar reforzando la capacitación del equipo técnico en temas de arquitectura segura, codificación confiable y gestión de cambios, ya que esto permitirá mejorar la calidad del desarrollo y reducir los errores derivados de malas prácticas.
Se sugiere incorporar herramientas de automatización que apoyen la trazabilidad, el control de versiones y las pruebas de seguridad. Esto optimizará el flujo de trabajo, garantizará un mejor control sobre los entornos y facilitará la verificación continua de los entregables.

Diego:
Fortalecer la automatización de métricas para medir la eficiencia y madurez de los procesos, integrando dashboards y herramientas BPM.
Promover auditorías internas regulares que aseguren la alineación entre los procesos definidos y las versiones actualizadas de las normas ISO y CMMI.
Desarrollar un plan de formación continua en modelamiento BPMN, gestión de calidad y auditoría de procesos para consolidar la mejora organizacional.
Brenda:
Establecer políticas de documentación y gestión del conocimiento, asegurando la trazabilidad de decisiones en los procesos del área de TI.
Implementar revisiones periódicas de la estructura organizacional y de roles para mantener la alineación con los objetivos estratégicos.
Fomentar la comunicación transversal entre las áreas técnica, administrativa y de seguridad, reforzando la cultura organizacional orientada a la calidad.
Saul:
Fortalecer el Sistema de Gestión de Seguridad de la Información (SGSI) mediante evaluaciones internas basadas en riesgos y auditorías cruzadas.
Implementar herramientas de detección temprana y monitoreo continuo para prevenir incidentes de seguridad antes de que afecten la operación.
Promover la creación de un programa de capacitación en gestión de riesgos y cumplimiento normativo, asegurando la sostenibilidad de la cultura de seguridad en toda la organización.
Javier:
Implementar métricas de calidad y madurez para evaluar de manera continua la eficiencia de los procesos de validación y verificación.
Fomentar el uso de pruebas automatizadas y análisis de vulnerabilidades para asegurar la consistencia y seguridad del producto.
Promover la colaboración entre el área de QA y los equipos de desarrollo para lograr una visión integral del aseguramiento de la calidad.


RECOMENDACIONES - TF
Djalma:
Se recomienda mantener los procesos actualizados y alineados a las nuevas tecnologías y prácticas actuales, evitando que se vuelvan obsoletos y asegurando que continúen aportando valor al desarrollo de software.
Es importante fortalecer la capacitación continua del equipo para garantizar que todos comprendan, apliquen y mantengan los estándares y lineamientos establecidos dentro de los procesos.
Se sugiere mejorar la retroalimentación entre las distintas etapas del proyecto, de modo que la comunicación sea más fluida, se reduzcan errores y retrabajos, y se aumente la eficiencia general del desarrollo.

Diego:
Validar datos organizacionales: Revisar con el equipo que los números de empleados, clientes y estructura sean consistentes en todos los capítulos para evitar inconsistencias en la narrativa del caso de estudio.
Profundizar justificación del modelo híbrido: Agregar en futuras iteraciones ejemplos concretos de cómo InnovaTech adapta ceremonias Scrum para cumplir requisitos de SBS o auditorías ISO 27001.
Vincular KPIs organizacionales con métricas de procesos: Conectar los indicadores de negocio de InnovaTech (tiempo de desarrollo, incidentes de seguridad) con las métricas específicas de cada proceso evaluado.
Brenda:
Completar el Capítulo 3 aplicando el mismo nivel de detalle (descripción formal + métricas + herramientas) a los 6 procesos restantes para mantener consistencia.
Expandir el proceso de riesgos para incluir explícitamente gestión de oportunidades según RSK de CMMI v2.0, no solo amenazas.
Asociar cada métrica propuesta con el nivel de capacidad CMMI que evidencia (CL1, CL2, CL3) para facilitar la evaluación de brechas del Capítulo 5.
Saul:
Extender las prácticas de medición y análisis (MA) a los procesos con menor nivel de avance, incorporando métricas que permitan monitorear desempeño, variabilidad y cumplimiento. 
Integrar revisiones formales (PQA) y retroalimentación estructurada en todos los procesos, no solo en seguridad. Estas revisiones permitirán asegurar el cumplimiento normativo, detectar brechas tempranas y fortalecer la cultura de calidad. 
Priorizar la institucionalización completa de los procesos 9 y 10, reforzarlos como base para la madurez organizacional. 
Javier:
Se debe priorizar la automatización de la recolección de métricas e integrarlas en dashboards con herramientas como Power BU o Jira, asegurando que la gestión del proyecto se base en datos en tiempo real.
Se debe desarrollar un plan de formación continua en modelamiento BPMN, gestión de calidad y auditoría de procesos para consolidar la mejora y evitar la regresión a prácticas ad-hoc.
Es obligatorio promover auditorías internas regulares y con roles independientes (PQA) para verificar la alineación constante entre los procesos definidos y las prácticas de ISO/CMMI en uso.

GLOSARIO

Término
Definición
BPMN (Business Process Model and Notation)
Lenguaje gráfico estandarizado utilizado para modelar los procesos de negocio y representar sus flujos, actores y decisiones de manera visual.
CMMI (Capability Maturity Model Integration)
Modelo de madurez y mejora de procesos desarrollado por ISACA que evalúa el nivel de capacidad y desempeño de una organización en la gestión de proyectos de software.
Ciclo de vida del software
Conjunto de fases que abarca desde la concepción de un sistema hasta su retiro o sustitución, incluyendo planificación, desarrollo, pruebas, mantenimiento y mejora.
Configuración (Gestión de)
Proceso que controla las versiones, componentes y cambios en los productos de software para mantener la integridad y trazabilidad de los entregables.
Control de cambios
Actividad que evalúa, aprueba y documenta las modificaciones realizadas a los productos o procesos del proyecto, asegurando su coherencia con los objetivos definidos.
Desarrollo seguro (Secure SDLC)
Enfoque que integra la seguridad en todas las fases del ciclo de vida del software, desde la definición de requisitos hasta la operación, siguiendo prácticas DevSecOps.
DevSecOps
Cultura y práctica que combina desarrollo, seguridad y operaciones, integrando controles de seguridad automatizados dentro del flujo continuo de entrega de software.
Evidencia auditable
Documentos, registros o artefactos verificables que demuestran el cumplimiento de procesos y controles definidos en las normas ISO y el modelo CMMI.
Gestión de la configuración
Proceso de identificación, control y registro de los elementos que componen un producto de software, garantizando su consistencia y trazabilidad.
Gestión de incidentes de seguridad
Conjunto de acciones que permiten identificar, analizar, responder y documentar incidentes que afecten la confidencialidad, integridad o disponibilidad de la información.
Gestión de la seguridad de la información (SGSI)
Sistema de gestión basado en la norma ISO/IEC 27001 que busca proteger la información mediante políticas, controles y procesos documentados.
Gestión de requisitos
Proceso que identifica, documenta, analiza y controla los requisitos funcionales y no funcionales del software durante todo su ciclo de vida.
Gestión de riesgos
Proceso continuo de identificación, evaluación y tratamiento de riesgos que puedan afectar la calidad, seguridad o cumplimiento del proyecto.
Indicador de desempeño (KPI)
Medida cuantitativa utilizada para evaluar la eficiencia y efectividad de los procesos o actividades de un proyecto.
ISO/IEC 12207:2017
Norma internacional que define los procesos del ciclo de vida del software, estableciendo un marco estructurado para su desarrollo, mantenimiento y gestión.
ISO/IEC 27001:2022
Norma que especifica los requisitos para establecer, implementar y mantener un Sistema de Gestión de Seguridad de la Información (SGSI).
ISO/IEC 27002:2022
Norma complementaria a la ISO 27001 que proporciona un catálogo de controles de seguridad de la información y directrices de aplicación.
Madurez de procesos
Nivel de desarrollo y formalización que posee una organización en la gestión de sus procesos, medido a través de modelos como CMMI.
Mapa de procesos
Representación gráfica que organiza los procesos de una organización en tres niveles: estratégicos, operativos y de soporte.
Métrica de calidad
Indicador numérico que permite medir características del software como confiabilidad, mantenibilidad, seguridad o eficiencia.
Modelo de procesos
Estructura formal que describe la secuencia, entradas, salidas y responsables de un conjunto de actividades relacionadas.
Notación BPMN
Estándar internacional que permite describir los procesos de negocio utilizando diagramas visuales fáciles de entender por técnicos y gestores.
Política de seguridad
Conjunto de lineamientos y compromisos institucionales para proteger los activos de información y cumplir con los requisitos normativos.
Proceso de mejora continua (PHVA)
Ciclo Planificar-Hacer-Verificar-Actuar que guía la implementación de acciones para optimizar los procesos y alcanzar mayores niveles de calidad.
Requisitos no funcionales
Condiciones que describen atributos de calidad del software, como rendimiento, disponibilidad, seguridad o usabilidad.
Sistema de Gestión de Calidad (SGC)
Conjunto de políticas, procedimientos y recursos que garantizan la planificación, ejecución y control de los procesos de una organización.
Sistema de Gestión de Seguridad de la Información (SGSI)
Marco de gestión que establece controles, responsabilidades y procedimientos para salvaguardar la información crítica de una organización.
Trazabilidad
Capacidad de rastrear cada requisito, decisión o cambio desde su origen hasta su implementación, asegurando la coherencia del producto final.
Validación
Proceso que confirma que el software cumple con las necesidades y expectativas del usuario final.
Verificación
Proceso que asegura que los productos intermedios y finales del software cumplen con las especificaciones técnicas y normativas establecidas.











BIBLIOGRAFÍA
Cornide-Reyes, H. (2024, 10 de enero). Análisis del uso de mejora de procesos de software basado en CMMI e ISO/IEC 12207 en empresas mexicanas. Ingeniería. Recuperado el 06 de octubre de 2025, de https://www.scielo.cl/pdf/ingeniare/v32/0718-3305-ingeniare-32-13.pdf


Crisóstomo, J. (2017, 07 de diciembre). Convergence Analysis of ISO/IEC 12207 and CMMI-DEV: Complementary result from systematic literature review. CLEI e-Journal. Recuperado el 06 de octubre de 2025, de https://www.clei.org/cleiej/index.php/cleiej/article/view/43


Dehghani, R., & Ramsin, R. (2024, 12 de marzo). Software Process Improvement by Managing Situational Knowledge. Journal of Universal Computer Science. Recuperado el 06 de octubre de 2025, de https://sharif.edu/~ramsin/index_files/Publications_PDF/Dehghani_Ramsin_JUCS_2024_SPI_by_Managing_SME_Knowledge.pdf 


Henriquez, V., Moreno, A. M., Calvo-Manzano, J. A., & San Feliu, T. (2021, 01 de octubre). Agile-CMMI Alignment: CMMI V2.0 Contributions and To-dos for Organizations. arXiv. Recuperado el 06 de octubre de 2025, de https://arxiv.org/abs/2110.00399


Ke, Q., & Liang, S. (2023, 15 de junio). Research on CMMI-oriented software project development quality management method. SPIE. Recuperado el 06 de octubre de 2025, de https://ui.adsabs.harvard.edu/abs/2023SPIE12702E..2MK/abstract 


Jung, H. W. (2003, 18 de noviembre). CMM-Based Process Improvement and Schedule Deviation in Software Maintenance. SEI / CMU. Recuperado el 06 de octubre de 2025, de https://www.sei.cmu.edu/documents/2023/2003_004_001_14156.pdf


“ISO/IEC/IEEE 12207 Standard” (2017, 29 de noviembre). ISO. Recuperado el 06 de octubre de 2025, de https://www.iso.org/standard/63712.html


“ISO/IEC/IEEE 12207-2:2020” (2020, 05 de enero). ISO. Recuperado el 06 de octubre de 2025, de https://www.iso.org/obp/ui/en/


“ISO/IEC/12207: Estándar de ciclo de vida del software” (s. f., 01 de febrero). ManagementSystems.World. Recuperado el 06 de octubre de 2025, de https://managementsystems.world/standard/iso-iec-ieee-12207


“Towards a new approach of continuous process improvement based on CMMI and PMBOK” (2021, 13 de septiembre). arXiv. Recuperado el 06 de octubre de 2025, de https://arxiv.org/abs/2109.07251
















ANEXOS
Anexo A: Tablas de mapeo entre normas ISO
Tabla A.1: Mapeo entre ISO 12207 y CMMI v2.0
Proceso ISO 12207
Área de práctica CMMI v2.0
Nota de integración
Gestión de Requisitos
Requirements Development (RDM)
Las actividades de definición, control y trazabilidad de requisitos en ISO se complementan con las prácticas de gestión de requisitos del CMMI.
Diseño / Arquitectura
Technical Solution (TS)
Las decisiones arquitectónicas y de diseño cubiertas por ISO se pueden someter a prácticas de solución técnica en CMMI.
Integración de producto
Product Integration (PI)
El ensamblaje de componentes y verificación de integridad mapea con las prácticas de integración de producto del CMMI.
Verificación / Validación
Verification & Validation (VV)
Las actividades de prueba y confirmación de requisitos se alinean directamente con las prácticas de verificación y validación.
Mantenimiento / Soporte
Configuration Management (CM), Process Management (PCM)
Ajustes continuos, control de versiones y mejora de procesos se reflejan en esas áreas de práctica.




Tabla A.2: Mapeo entre ISO 27001 / ISO 27002 y CMMI / Procesos ISO

Norma ISO / Control
Proceso ISO relacionado
Área CMMI relevante
Comentarios de aplicación
ISO 27001 cláusula 6 (Planificación de riesgos)
Gestión de Riesgos
Risk Management (RSKM)
El proceso de identificación y tratamiento de riesgos se alinea directamente.
ISO 27002 control 8.28 (Pruebas de seguridad)
Verificación / Validación
Verification (VER)
Se incorporan pruebas de vulnerabilidad dentro del proceso de verificación.
ISO 27002 control 8.32 (Registro de eventos)
Operación / Mantenimiento
Configuration Management (CM) / Process Management (PCM)
El monitoreo y registro de eventos se integran al control de configuración y mejora de procesos.
ISO 27002 control 8.9 (Gestión de la configuración)
Gestión de Configuración
Configuration Management (CM)
Control directo del cambio y versiones en el ciclo de vida del software.
ISO 27002 control 5.8 (Seguridad en gestión de proyectos)
Planificación / Control de Proyectos
Governance (GOV) / Planning (PLAN)
Se garantiza que la seguridad forme parte de la planificación y control de los proyectos.





