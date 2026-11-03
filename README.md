# SIMULACION Y MONITOREO DE VARIABLES CARDIOVASCULARES Y HEMODINAMICAS

**Luz Marina Valderrama – 5600741**

## INTRODUCCIÓN

En el ámbito clínico, los monitores de signos vitales permiten realizar seguimiento continuo de diferentes variables fisiológicas, entre ellas la frecuencia cardíaca y la saturación periférica de oxígeno (SpO₂). Estos parámetros son de gran importancia debido a que sus variaciones pueden indicar alteraciones en el estado fisiológico de un paciente y, cuando alcanzan determinados límites, deben generar alarmas visuales y sonoras que permitan una respuesta oportuna [1].

La evaluación funcional de estos equipos puede realizarse mediante simuladores de señales biomédicas. En este caso se empleó el simulador Pronk OxSim OX-1, conectado a un monitor de signos vitales Mindray uMEC 100 mediante el sensor de pulsioximetría. El OxSim permite generar diferentes combinaciones preestablecidas de saturación de oxígeno, frecuencia cardíaca y perfusión, facilitando la comprobación del comportamiento de los sistemas de monitorización [2].

La práctica permitió comparar los valores programados en el simulador con los valores registrados por el monitor, calcular los errores absoluto y porcentual y comprobar el funcionamiento de las alarmas ante valores que superan los límites configurados. La guía de laboratorio establece específicamente pruebas con 40 bpm/95 %, 80 bpm/85 %, 80 bpm/99 % en baja perfusión y 140 bpm/98 %, además de la observación de la onda fotopletismográfica [1].

## OBJETIVOS

### Objetivo general

Operar con el simulador Pronk OxSim (OX-1) y el monitor de signos vitales uMEC 100 para pruebas funcionales.

### Objetivos específicos

- Identificar los modos de operación de un simulador de parámetros hemodinámicos (Pronk OxSim).
- Verificar los límites de medición de un monitor de signos vitales mediante simulación de variables hemodinámicas.
- Interpretar variaciones en los parámetros hemodinámicos asociadas a estados fisiológicos y patológicos.

## MARCO TEORICO

### Monitor de signos vitales uMEC 100

El Mindray uMEC 100 es un monitor multiparámetro utilizado para la vigilancia de variables fisiológicas. Dentro de las funciones empleadas en esta práctica se encuentran la medición de SpO₂ y frecuencia de pulso, además de la visualización de la onda pletismográfica y la generación de alarmas.

El monitor dispone de diferentes modos de funcionamiento. El modo monitor corresponde al modo normal de operación utilizado para la monitorización cotidiana del paciente. De acuerdo con el manual del equipo, el monitor entra automáticamente en este modo después de encenderse [3].

En el uMEC, las alarmas pueden configurarse mediante el menú Ajuste alarma, donde se establecen los límites superiores e inferiores de los diferentes parámetros. El manual también indica que las alarmas pueden comprobarse mediante el uso de un simulador, ajustando previamente los límites y verificando el comportamiento de la alarma [3].

### Simulador Pronk OxSim OX-1

 El Pronk OxSim OX-1 es un simulador óptico de SpO₂ utilizado para comprobar el funcionamiento de monitores de pulsioximetría. El dispositivo permite seleccionar diferentes condiciones de saturación, frecuencia cardíaca y perfusión [2].

Los principales modos utilizados durante la práctica son:

| Modo OxSim | SpO₂ simulada | Frecuencia cardíaca | Perfusión aproximada |
|---|---:|---:|---:|
| 85 % / 80 bpm | 85 % | 80 bpm | 2,0 |
| 95 % / 40 bpm | 95 % | 40 bpm | 2,0 |
| 98 % / 80 bpm | 98 % | 80 bpm | 2,0 |
| 98 % / 140 bpm | 98 % | 140 bpm | 2,0 |
| Low Perfusion | 99 % | 80 bpm | 0,2 |

Estos valores corresponden a los modos preestablecidos del OX-1 [2].

La condición de 40 bpm representa una prueba exigente para algunos pulsioxímetros, debido a que se encuentra cerca del límite inferior de frecuencia cardíaca de ciertos equipos. Asimismo, el modo Low Perfusion está diseñado para producir una señal de baja perfusión y puede dificultar la obtención de una lectura estable en algunos monitores [2].

### Error absoluto y error porcentual

Para comparar el valor programado en el simulador con el valor mostrado por el monitor se utilizaron las siguientes expresiones:

Error absoluto:

Ea= |V simulado - V medido|

Error porcentual:

E%= (( |V simulado - V medido| ) / V simulado) x 100

El error porcentual permite expresar la diferencia entre el valor de referencia del simulador y la lectura del monitor en relación con el valor simulado.

### Tolerancias de medición

Para el uMEC 100, la especificación del módulo Mindray de SpO₂ establece una exactitud de aproximadamente ±2 % en el rango de 70–100 % en modo adulto/pediátrico, mientras que para la frecuencia de pulso obtenida mediante SpO₂ se especifica aproximadamente ±3 bpm [4].

Estas especificaciones deben interpretarse con cuidado: una prueba con un simulador como el OxSim permite comprobar principalmente el funcionamiento del sistema y la correspondencia de las lecturas, pero no sustituye una validación clínica completa de exactitud. El propio manual de servicio de Mindray señala esta diferencia entre una prueba funcional con simulador y la verificación clínica de exactitud [5].

## MATERIALES Y EQUIPOS

Para el montaje se utilizaron los siguientes elementos:

- Monitor de signos vitales Mindray uMEC 100.
- Sensor de pulsioximetría SpO₂.
- Simulador de parámetros hemodinámicos Pronk OxSim OX-1.
- Computador con conexión a Internet para la consulta bibliográfica.
- Libreta y elementos de escritura.

La guía establece como equipos principales el monitor uMEC 100 con sensor de SpO₂ y el simulador Pronk OxSim OX-1 [1].

### Consideraciones de seguridad eléctrica

Durante la práctica se tuvieron en cuenta las recomendaciones de seguridad establecidas en la guía:

- No manipular equipos biomédicos sin la presencia o supervisión del personal responsable.
- Utilizar bata y los elementos de protección correspondientes.
- Manipular cuidadosamente los cables, sensores y conectores.
- Evitar desconexiones o conexiones incorrectas durante la operación.
- Mantener organizados los elementos de trabajo.

Estas recomendaciones hacen parte de las condiciones de seguridad indicadas para la práctica de laboratorio [1].

## METODOLOGIA

Inicialmente se encendió el monitor uMEC 100 y se verificó su funcionamiento en modo monitor. Posteriormente se conectó el sensor de pulsioximetría al simulador Pronk OxSim OX-1.

El procedimiento se realizó siguiendo los modos de simulación establecidos en la guía. Primero se seleccionó la condición correspondiente a 95 % de SpO₂ y 40 bpm. Posteriormente se realizaron las pruebas correspondientes a 85 %/80 bpm, 98 %/80 bpm y 98 %/140 bpm.

En cada condición se comparó el valor programado en el OxSim con el valor indicado por el uMEC 100. También se observó la forma de onda fotopletismográfica.

Finalmente, se configuraron los límites de alarma del monitor para comprobar la respuesta ante valores de SpO₂ y frecuencia cardíaca que superaran los límites establecidos. La guía indica específicamente configurar el límite inferior de SpO₂ en 90 %, probar 85 %, posteriormente establecer el límite superior en 97 % y probar 99 % en modo Low Perfusion, y finalmente generar una frecuencia cardíaca de 140 bpm con SpO₂ de 98 % [1].

## RESULTADOS

### Primera prueba de verificación: equipo inicialmente utilizado

Antes de iniciar formalmente la secuencia de pruebas establecida por la guía, se realizó una primera prueba para comprobar el funcionamiento del equipo y del montaje.

Durante esta prueba se obtuvo una lectura de:

- SpO₂ medida = 94 %

- Frecuencia cardíaca medida = 80 bpm.

Sin embargo, los valores obtenidos no correspondieron con los valores esperados para la condición que se estaba verificando en ese momento. Debido a que esta primera prueba se realizó como una comprobación inicial y no se tiene registrado con certeza cuál era el modo exacto seleccionado en el OxSim, no se asigna esta medición a una condición específica de la secuencia de la guía.

El resultado se consideró no satisfactorio, razón por la cual se decidió cambiar el equipo utilizado y reiniciar la práctica en el orden establecido.

### Error registrado

Para la SpO₂, tomando como referencia el valor de 95 % que posteriormente se utilizó como condición de comparación:

Ea= |95-94|= 1

El error porcentual correspondiente es:

E%=(|95-94|)/95 X100= 1.05%

Para la frecuencia cardíaca, si se compara con el valor de 40 bpm asociado a la condición que posteriormente se verificó:

Ea=|40-80|= 40 bpm

E%= (|40-80|) / 40 X 100= 100%

### Interpretación
El primer equipo utilizado no permitió obtener inicialmente una correspondencia adecuada de los valores. Por esta razón se decidió reemplazarlo y repetir el procedimiento. Este resultado se reporta como parte de la práctica debido a que representa una condición real observada durante la verificación inicial del sistema.

## Verificación del modo 85 % de SpO₂ y 80 bpm
Después del cambio de equipo se inició la secuencia de pruebas establecida por la guía. La primera condición correspondió a:
- SpO₂ simulada = 85 %
- Frecuencia cardíaca simulada = 80 bpm.
  
En el monitor se registró:
- SpO₂ medida = 85 %
- Frecuencia cardíaca medida = 80 bpm.
### Cálculo del error de SpO₂

Ea=|85-85|= 0 puntos porcentuales

E%= (|85-85|) / 85 X 100= 0%

Resultado: error absoluto = 0 puntos porcentuales; error porcentual = 0 %.
### Cálculo del error de frecuencia cardíaca

Ea=|80-80|= 0 bpm

E%= (|80-80|) / 80 X 100= 0%

Resultado: error absoluto = 0 bpm; error porcentual = 0 %.
### Interpretación
Para esta condición se obtuvo una correspondencia exacta entre el valor configurado en el simulador y el valor mostrado por el monitor. Por tanto, el sistema respondió correctamente para esta prueba.

## Prueba de 95 % de SpO₂ y 40 bpm
La segunda condición de la secuencia correspondió al modo del OxSim que simula:
- SpO₂ = 95 %
- Frecuencia cardíaca = 40 bpm.
  
En esta prueba se obtuvo:
- SpO₂ medida = 96 %
- Frecuencia cardíaca medida = 40 bpm.
### Cálculo del error de SpO₂

Ea=|95-96|= 1 punto porcentual

E%= (|95-96|) / 95 X 100= 1.05%

Resultado: error absoluto = 1 punto porcentual; error porcentual ≈ 1,05 %.
### Cálculo del error de frecuencia cardíaca

Ea=|40-40|= 0 bpm

E%= (|40-40|) / 40 X 100= 0%

Resultado: error absoluto = 0 bpm; error porcentual = 0 %.
### Interpretación
La frecuencia cardíaca fue detectada correctamente por el monitor. La diferencia de 1 punto porcentual en la SpO₂ representa un error porcentual aproximado de 1,05 %, encontrándose dentro del orden de magnitud de la exactitud especificada para el módulo de SpO₂ [4].

Es importante diferenciar esta prueba de la primera prueba de verificación realizada antes del cambio de equipo. La primera prueba presentó una lectura incorrecta y motivó el cambio del equipo; posteriormente, la secuencia de la guía se inició nuevamente y esta condición de 95 %/40 bpm se obtuvo correctamente.

## Prueba de 98 % de SpO₂ y 80 bpm
Para la tercera condición se seleccionó el modo del OxSim correspondiente a:
- SpO₂ = 98 %
- Frecuencia cardíaca = 80 bpm.
  
Los valores obtenidos en el monitor fueron:
- SpO₂ = 98 %
- Frecuencia cardíaca = 80 bpm.
### Cálculo del error de SpO₂

Ea=|98-98|= 0 puntos porcentuales

E%= (|98-98|) / 98 X 100= 0%

Resultado: error absoluto = 0 puntos porcentuales; error porcentual = 0 %.
### Cálculo del error de frecuencia cardíaca

Ea=|80-80|= 0 bpm

E%= (|80-80|) / 80 X 100= 0%

Resultado: error absoluto = 0 bpm; error porcentual = 0 %.
### Interpretación
Los valores registrados coincidieron exactamente con los programados en el OxSim, por lo que el monitor presentó un comportamiento correcto para esta condición.

## Prueba de 98 % de SpO₂ y 140 bpm
Finalmente se utilizó el modo del OxSim correspondiente a una frecuencia cardíaca elevada:
- SpO₂ = 98 %
- Frecuencia cardíaca = 140 bpm.
  
Los valores registrados fueron:
- SpO₂ = 98 %
- Frecuencia cardíaca = 140 bpm.
### Cálculo del error de SpO₂

Ea=|98-98|= 0 puntos porcentuales

E%= (|98-98|) / 98 X 100= 0%

Resultado: error absoluto = 0 puntos porcentuales; error porcentual = 0 %.
### Cálculo del error de frecuencia cardíaca

Ea=|140-140|= 0 bpm

E%= (|140-140|) / 140 X 100= 0%

Resultado: error absoluto = 0 bpm; error porcentual = 0 %.
### Interpretación
El monitor reprodujo correctamente tanto la frecuencia cardíaca elevada como la saturación configurada en el simulador. Esta prueba permitió verificar además el comportamiento del monitor frente a una frecuencia cardíaca que supera el límite de alarma configurado.

### Resumen de resultados de medicion

| Prueba | SpO₂ simulada | FC simulada | SpO₂ medida | FC medida | Error SpO₂ | Error FC |
|---|---:|---:|---:|---:|---:|---:|
| 85 % / 80 bpm | 85 % | 80 bpm | 85 % | 80 bpm | 0 % | 0 % |
| 95 % / 40 bpm – primer intento | -- | -- | 94 % | 80 bpm | -- | -- |
| 95 % / 40 bpm – repetición | 95 % | 40 bpm | 96 % | 40 bpm | 1,05 % | 0 % |
| 98 % / 80 bpm | 98 % | 80 bpm | 98 % | 80 bpm | 0 % | 0 % |
| 98 % / 140 bpm | 98 % | 140 bpm | 98 % | 140 bpm | 0 % | 0 % |

La primera prueba se presenta separadamente porque correspondió a una verificación inicial del equipo que posteriormente fue cambiado. Al no conocerse con certeza el modo exacto seleccionado en el OxSim durante esa primera comprobación, no se asignan valores simulados ni se calcula un error formal para dicha prueba.

Después del cambio de equipo, las pruebas realizadas en el orden establecido por la guía presentaron resultados adecuados, con coincidencia exacta en la mayoría de las condiciones y una diferencia de 1 punto porcentual en la SpO₂ de la prueba de 95 %/40 bpm.

## CONFIGURACIÓN Y VERIFICACIÓN DE ALARMAS
Como parte de la práctica se realizó la configuración de los límites de alarma del monitor uMEC 100.

En el menú de ajuste de alarmas se establecieron los límites correspondientes a frecuencia cardíaca y SpO₂, con el objetivo de comprobar posteriormente la respuesta del monitor ante condiciones que superaran dichos límites.

La guía establece específicamente la modificación de los límites de SpO₂ para realizar las pruebas de alarma, incluyendo un límite inferior de 90 % y posteriormente un límite superior de 97 % [1].

Durante la configuración también se observaron límites relacionados con la frecuencia cardíaca, incluyendo valores de alarma para frecuencia alta y baja.

La configuración observada fue:

| Parámetro           | Límite superior | Límite inferior | Prioridad |
| ------------------- | --------------- | --------------- | --------- |
| FC/FP               | 120 bpm         | 50 bpm          | Alto      |
| Taquicardia extrema | 160 bpm         | —               | Alto      |
| Bradicardia extrema | —               | 35 bpm          | Alto      |
| QTc                 | 500 ms          | —               | Medio     |
| ΔQTc                | 60 ms           | —               | Medio     |
| SpO₂                | 100 %           | 90 %            | Alto      |

La configuración permitió posteriormente comprobar la respuesta del monitor frente a valores fuera de los límites establecidos.

## RESULTADOS DE LAS ALARMAS
Durante la comprobación de alarmas se observó que la alarma no se activó inmediatamente al modificar el valor simulado. El tiempo observado entre el establecimiento de la condición de alarma y la activación de la señal sonora fue de aproximadamente 12 segundos.

Por lo tanto:

t_alarma= 12s

La verificación general de las condiciones de alarma se resume en la siguiente tabla:

| Prueba                   | Límite configurado | Valor simulado | Condición                   | ¿Alarma activa? | Tiempo observado |
| ------------------------ | ------------------ | -------------- | --------------------------- | --------------- | ---------------- |
| SpO₂ baja                | 90 %               | 85 %           | Valor por debajo del límite | Sí              | 12 s             |
| SpO₂ alta                | 97 %               | 99 %           | Valor por encima del límite | Sí              | 12 s             |
| Frecuencia cardíaca alta | 120 bpm            | 140 bpm        | Valor por encima del límite | Sí              | 12 s             |

La guía indica que, para la prueba de SpO₂ baja, debía configurarse un límite inferior de 90 % y simular 85 %. Para la prueba de SpO₂ alta se debía configurar un límite superior de 97 % y simular 99 % en modo Low Perfusion. Finalmente, se debía simular una frecuencia de 140 bpm con SpO₂ de 98 % para comprobar la alarma de frecuencia cardíaca elevada [1].

## PRUEBA DE ALARMA POR SpO₂ BAJA
Se configuró el límite inferior de SpO₂ en 90 % y posteriormente se seleccionó en el OxSim la condición de 85 % de SpO₂ y 80 bpm.

El valor simulado de 85 % se encuentra por debajo del límite configurado, por lo que se esperaba la activación de la alarma.

La alarma se activó de manera visual y sonora después de aproximadamente 12 segundos.
### Cálculo del error de SpO₂

Ea=|85-85|= 0 puntos porcentuales

E%= (|85-85|) / 85 X 100= 0%

### Cálculo del error de frecuencia cardíaca

Ea=|80-80|= 0 bpm

E%= (|80-80|) / 80 X 100= 0%

Resultado: la medición coincidió con el valor simulado y la alarma se activó después de aproximadamente 12 s.

## PRUEBA DE ALARMA POR SpO₂ ALTA Y BAJA PERFUSIÓN
Posteriormente se configuró el límite superior de SpO₂ en 97 %. Se seleccionó en el OxSim el modo Low Perfusion, que simula aproximadamente:
- SpO₂ = 99 %.
- Frecuencia cardíaca = 80 bpm.
- Índice de perfusión ≈ 0,2.
  
El valor de 99 % supera el límite superior de 97 %, por lo que se esperaba la activación de la alarma.

La alarma se activó aproximadamente 12 segundos después de establecer la condición.

Los resultados de la prueba pueden resumirse de la siguiente manera:

| Variable            | Valor simulado | Límite configurado | Condición               | Resultado           |
| ------------------- | -------------- | ------------------ | ----------------------- | ------------------- |
| SpO₂                | 99 %           | 97 %               | SpO₂ superior al límite | Alarma activada     |
| Frecuencia cardíaca | 80 bpm         | —                  | Dentro del rango        | Sin alarma por FC   |
| Perfusión           | 0,2            | —                  | Baja perfusión          | Condición de prueba |
| Tiempo de alarma    | —              | —                  | Condición mantenida     | 12 s                |

El modo Low Perfusion permitió evaluar el comportamiento del sistema ante una señal de pulsioximetría de menor amplitud. La prueba también permitió verificar que, aunque la perfusión simulada fuera baja, el monitor logró obtener una lectura de SpO₂ y activar la alarma cuando el valor superó el límite configurado.

## PRUEBA DE ALARMA POR FRECUENCIA CARDÍACA ALTA
Para comprobar la alarma de frecuencia cardíaca elevada se utilizó la condición de:
- Frecuencia cardíaca = 140 bpm.
- SpO₂ = 98 %.
  
El límite superior de frecuencia cardíaca configurado fue de 120 bpm. Debido a que el valor simulado de 140 bpm supera dicho límite, se esperaba la activación de la alarma.

| Variable            | Valor simulado | Límite configurado | Error absoluto            | Error porcentual           | Resultado       |
| ------------------- | -------------- | ------------------ | ------------------------- | -------------------------- | --------------- |
| Frecuencia cardíaca | 140 bpm        | 120 bpm            | 20 bpm respecto al límite | 16,67 % respecto al límite | Alarma activada |
| SpO₂                | 98 %           | —                  | 0 puntos porcentuales     | 0 %                        | Valor correcto  |

La frecuencia cardíaca medida por el monitor fue de 140 bpm, por lo que coincidió con el valor establecido en el simulador.

El error de medición fue:

Ea=|140-140|= 0 bpm

E%= (|140-140|) / 140 X 100= 0%

La diferencia de 20 bpm indicada en la tabla corresponde únicamente a la diferencia entre el valor simulado y el límite de alarma de 120 bpm, no a un error de medición del monitor.

La alarma se activó aproximadamente 12 segundos después de establecerse la condición.

## ANÁLISIS DE RESULTADOS
Los resultados obtenidos permitieron comprobar el funcionamiento del sistema compuesto por el simulador Pronk OxSim OX-1 y el monitor Mindray uMEC 100.

La primera prueba realizada con el equipo inicial no presentó el comportamiento esperado, ya que se obtuvo una lectura de 94 % de SpO₂ y 80 bpm durante la verificación inicial. Debido a esta discrepancia se tomó la decisión de cambiar el equipo y repetir el procedimiento. Esta situación es importante porque demuestra la necesidad de realizar una comprobación inicial de los equipos antes de comenzar la adquisición formal de datos.

Después del cambio, las pruebas se realizaron nuevamente siguiendo el orden indicado en la guía. En la prueba de 85 % de SpO₂ y 80 bpm se obtuvo una correspondencia exacta entre el simulador y el monitor. En la condición de 95 % de SpO₂ y 40 bpm se obtuvo una lectura de 96 % y 40 bpm, respectivamente, lo cual representa un error porcentual de aproximadamente 1,05 % para SpO₂ y 0 % para la frecuencia cardíaca.

En las pruebas de 98 %/80 bpm y 98 %/140 bpm se obtuvo una correspondencia exacta entre los valores simulados y medidos. Esto indica un comportamiento adecuado del sistema en las condiciones evaluadas.

La prueba de 40 bpm es particularmente relevante debido a que las frecuencias cardíacas bajas pueden representar una condición más exigente para determinados sistemas de pulsioximetría [2]. Sin embargo, en el procedimiento realizado después del cambio de equipo, el monitor logró detectar correctamente los 40 bpm.

También se verificó el funcionamiento de las alarmas. Las condiciones de SpO₂ baja, SpO₂ alta y frecuencia cardíaca elevada generaron la alarma correspondiente. El tiempo observado entre el establecimiento de la condición de alarma y la activación sonora fue de aproximadamente 12 segundos.

La observación de la onda fotopletismográfica permitió complementar la interpretación de los resultados numéricos, ya que esta señal representa la variación pulsátil detectada ópticamente por el sensor de SpO₂. En condiciones de baja perfusión, la amplitud y estabilidad de la señal pueden verse afectadas, por lo que esta prueba permite evaluar no solamente el valor numérico presentado por el monitor sino también el comportamiento de la señal adquirida.

En general, los resultados obtenidos después del cambio de equipo fueron consistentes con las condiciones programadas en el simulador y permitieron comprobar el funcionamiento del sistema de medición y alarmas.
## 14. CONCLUSIÓN

La construcción y evaluación del prototipo de incubadora neonatal permitió reconocer la importancia de controlar las condiciones ambientales para favorecer la estabilidad térmica del neonato e identificar los componentes principales que intervienen en el funcionamiento de estos equipos. La integración del Arduino Uno, el sensor DHT11, el FSR400, la pantalla OLED, los indicadores luminosos y los ventiladores permitió desarrollar un sistema que respondió según lo programado durante las pruebas. La pantalla mostró la información prevista e indicó cuándo el ventilador debía encenderse o apagarse, mientras que los indicadores luminosos y los ventiladores funcionaron correctamente. En la estimación del peso, el FSR400 presentó un error aproximado del 9 %, por lo que el valor obtenido fue relativamente cercano al peso patrón, aunque todavía puede mejorarse mediante una calibración más precisa. En cuanto al comportamiento térmico, se observó que la incubadora tardaba en calentarse y que el bombillo no estaba regulado automáticamente por el Arduino, lo que limitó la capacidad del sistema para mantener la temperatura de manera precisa. Estos resultados muestran que es posible representar funciones básicas de una incubadora mediante componentes electrónicos de bajo costo, pero que la regulación térmica y la medición del peso requieren mejoras para obtener resultados más exactos y confiables. Como siguiente paso, se propone incorporar un sistema de control automático del calentamiento, mejorar el aislamiento térmico, realizar mediciones repetidas de temperatura y peso y evaluar el desempeño del prototipo mediante pruebas cuantitativas. El sistema desarrollado constituye una herramienta académica para comprender los principios de instrumentación biomédica, pero no debe utilizarse como sustituto de una incubadora clínica.

## 15. PREGUNTAS PARA LA DISCUSIÓN

### Pregunta 1. ¿Qué otras variables, y por qué, además de las mencionadas son críticas en el monitoreo neonatal?



### Pregunta 2. ¿Qué haría falta para convertir el sistema desarrollado en una incubadora neonatal real?



### Pregunta 3. ¿Qué semejanzas hay entre una incubadora neonatal y una servocuna?



## REFERENCIAS

[1] Universidad Militar Nueva Granada, “Diseño y construcción de una incubadora neonatal a escala,” *Guía de laboratorio de Instrumentación Biomédica y Biosensores*, 2025.
