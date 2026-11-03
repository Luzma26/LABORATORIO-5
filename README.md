# SIMULACION Y MONITOREO DE VARIABLES CARDIOVASCULARES Y HEMODINAMICAS

**Luz Marina Valderrama Botia – 5600741**

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

  <img width="630" height="488" alt="image" src="https://github.com/user-attachments/assets/ea29491a-3476-4b29-ab8b-5a32bb2f6eac" />

Fig.1. Mindray uMEC 10

<img width="522" height="567" alt="image" src="https://github.com/user-attachments/assets/077f5cb4-27c9-4b48-bee0-01c74740ffd3" />

Fig.2. OxSim OX-1

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

<img width="631" height="455" alt="image" src="https://github.com/user-attachments/assets/9219d5a3-f6f4-4c16-92e7-f4568a4d9b2d" />

Fig.3. Prueba de 95 % de SpO₂ y 40 bpm erronea

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

<img width="636" height="517" alt="image" src="https://github.com/user-attachments/assets/a6147749-d310-484f-8991-096e199b5a1a" />

Fig.4. Modo 85 % de SpO₂ y 80 bpm

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

<img width="620" height="482" alt="image" src="https://github.com/user-attachments/assets/a10b76c3-1942-444e-a5e1-e627e7a9acb9" />

Fig.5. Modo 95 % de SpO₂ y 40 bpm

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

<img width="635" height="487" alt="image" src="https://github.com/user-attachments/assets/13bfa810-e1b6-4f81-8b1a-ddafceda8b6a" />

Fig.6. Modo 98 % de SpO₂ y 80 bpm

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

<img width="592" height="402" alt="image" src="https://github.com/user-attachments/assets/97312749-3142-441f-9f9d-8d927ef0cf0f" />

Fig.7. Modo de 98 % de SpO₂ y 140 bpm


### Resumen de resultados de medicion

| Prueba | SpO₂ simulada | FC simulada | SpO₂ medida | FC medida | Error SpO₂ | Error FC |
|---|---:|---:|---:|---:|---:|---:|
| 85 % / 80 bpm | 85 % | 80 bpm | 85 % | 80 bpm | 0 % | 0 % |
| 95 % / 40 bpm – primer intento | -- | -- | 94 % | 80 bpm | -- | -- |
| 95 % / 40 bpm – repetición | 95 % | 40 bpm | 96 % | 40 bpm | 1,05 % | 0 % |
| 98 % / 80 bpm | 98 % | 80 bpm | 98 % | 80 bpm | 0 % | 0 % |
| 98 % / 140 bpm | 98 % | 140 bpm | 98 % | 140 bpm | 0 % | 0 % |

La primera prueba se presenta separadamente porque correspondió a una verificación inicial del equipo que posteriormente fue cambiado.

Después del cambio de equipo, las pruebas realizadas en el orden establecido por la guía presentaron resultados adecuados, con coincidencia exacta en la mayoría de las condiciones y una diferencia de 1 punto porcentual en la SpO₂ de la prueba de 95 %/40 bpm.

## CONFIGURACIÓN Y VERIFICACIÓN DE ALARMAS
Como parte de la práctica se realizó la configuración de los límites de alarma del monitor uMEC 100.

En el menú de ajuste de alarmas se establecieron los límites correspondientes a frecuencia cardíaca y SpO₂, con el objetivo de comprobar posteriormente la respuesta del monitor ante condiciones que superaran dichos límites.

La guía establece específicamente la modificación de los límites de SpO₂ para realizar las pruebas de alarma, incluyendo un límite inferior de 90 % y posteriormente un límite superior de 97 % [1].

Durante la configuración también se observaron límites relacionados con la frecuencia cardíaca, incluyendo valores de alarma para frecuencia alta y baja.

<img width="640" height="490" alt="image" src="https://github.com/user-attachments/assets/f0ecad51-5c75-474d-8b4a-10a673efe91f" />

Fig.8. Menú de configuración para las alarmas

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

<img width="618" height="481" alt="image" src="https://github.com/user-attachments/assets/e9782953-8ab2-4758-8102-cecf9937e6a3" />


Fig.9. Prueba de alarma con la condición de 85 % de SpO₂ y 80 bpm.

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
### Análisis estadístico de las diferencias entre los valores de referencia y los valores medidos
Para evaluar el comportamiento del sistema de monitorización se compararon los valores de referencia establecidos en el simulador Pronk OxSim OX-1 con los valores registrados por el monitor Mindray uMEC 100. Se tuvieron en cuenta las cuatro pruebas realizadas después del cambio de equipo: 85 %/80 bpm, 95 %/40 bpm, 98 %/80 bpm y 98 %/140 bpm.

En la variable SpO₂ se obtuvieron errores absolutos de 0, 1, 0 y 0 puntos porcentuales, respectivamente. El error absoluto promedio fue:

Ea= (0+1+0+0) /4= 0.25

Por tanto, la diferencia absoluta promedio de SpO₂ fue de 0,25 puntos porcentuales. El único valor diferente se presentó en la prueba de 95 % de SpO₂ y 40 bpm, en la cual el monitor registró 96 %, equivalente a un error porcentual aproximado de 1,05 %.

Para la frecuencia cardíaca, las cuatro pruebas presentaron coincidencia entre los valores simulados y medidos. Los errores absolutos fueron 0, 0, 0 y 0 bpm, por lo que el error absoluto promedio fue:

Ea= (0+0+0+0) /4= 0 bpm

Estos resultados muestran que, después del cambio de equipo, el monitor presentó una correspondencia adecuada con los valores de referencia del simulador. La primera verificación realizada con el equipo inicial no se incluyó en el cálculo estadístico porque no se registró con certeza el modo exacto seleccionado en el OxSim.

### Relación entre la forma de onda visualizada y la frecuencia cardíaca y la saturación periférica de oxígeno
La onda fotopletismográfica observada en el monitor representa las variaciones del volumen sanguíneo en los tejidos periféricos, detectadas mediante la absorción de luz por parte de la sangre. Esta señal permite relacionar la actividad pulsátil con la frecuencia cardíaca y aporta información utilizada por el pulsioxímetro para estimar la saturación periférica de oxígeno.

La frecuencia cardíaca se relaciona con la separación temporal entre los picos consecutivos de la onda. Cuando aumenta la frecuencia cardíaca, los pulsos aparecen más próximos entre sí; cuando disminuye, aumenta el intervalo entre los picos. Por esta razón, las condiciones simuladas de 40, 80 y 140 bpm producen diferentes frecuencias de repetición de la señal fotopletismográfica.

Por otra parte, la SpO₂ se determina mediante la comparación de la absorción de luz roja e infrarroja, considerando los cambios pulsátiles asociados al paso de la sangre arterial. Por lo tanto, aunque la onda fotopletismográfica permite observar la actividad pulsátil, la saturación no se obtiene únicamente a partir de su frecuencia o amplitud.

Durante la prueba de baja perfusión, la amplitud de la componente pulsátil puede disminuir debido a la menor variación del volumen sanguíneo detectada por el sensor. Esto puede dificultar la identificación de los pulsos y afectar la estabilidad de la medición. En conjunto, la observación de la onda permite complementar los valores numéricos de frecuencia cardíaca y SpO₂, facilitando la interpretación del comportamiento del sistema ante las diferentes condiciones simuladas.
## CONCLUSION
La práctica permitió evaluar el funcionamiento del sistema de monitorización compuesto por el simulador Pronk OxSim OX-1 y el monitor Mindray uMEC 100 mediante diferentes condiciones de SpO₂, frecuencia cardíaca y perfusión. Después del cambio del equipo inicialmente utilizado, se obtuvo una correspondencia adecuada entre los valores de referencia y los registrados por el monitor, con un error absoluto promedio de 0,25 puntos porcentuales para SpO₂ y de 0 bpm para la frecuencia cardíaca. Además, se comprobó la activación de las alarmas ante condiciones de saturación baja, saturación superior al límite configurado y frecuencia cardíaca elevada, con un tiempo aproximado de respuesta de 12 segundos. Estos resultados evidencian un comportamiento satisfactorio del monitor en las condiciones evaluadas; sin embargo, la confiabilidad observada está limitada a las pruebas realizadas con el simulador y no representa por sí sola una validación clínica del equipo. Asimismo, el OxSim permite reproducir condiciones ópticas y pulsátiles controladas, pero no reproduce completamente la complejidad fisiológica de un paciente ni todas las alteraciones asociadas a condiciones patológicas reales. Como siguiente paso, sería conveniente ampliar las pruebas con diferentes niveles de perfusión y condiciones de señal, así como realizar verificaciones adicionales con equipos de referencia para evaluar con mayor profundidad la exactitud y las limitaciones del sistema.
## PREGUNTAS PARA LA DISCUSIÓN
### ¿Cuál es el principio de operación del Pronk OxSim OX-1 para simular una onda pulsátil?
El Pronk OxSim OX-1 funciona mediante un principio de simulación óptica. El dispositivo se acopla al sensor de pulsioximetría y genera una señal luminosa pulsátil que reproduce el comportamiento óptico que el sensor detectaría al estar colocado sobre un tejido con circulación sanguínea. Mediante la selección de diferentes modos, el simulador reproduce condiciones específicas de saturación de oxígeno, frecuencia cardíaca y perfusión. De esta manera, el monitor recibe una señal óptica controlada y puede procesarla para mostrar los valores correspondientes de SpO₂ y frecuencia de pulso, sin necesidad de utilizar un paciente real. Esto permite comprobar el funcionamiento del sistema de medición y de sus alarmas bajo condiciones reproducibles.
### ¿Por qué la SpO₂ baja puede ser un falso positivo (falsa alarma) en una situación de mala perfusión?
La SpO₂ baja puede generar una falsa alarma durante una situación de mala perfusión porque el pulsioxímetro depende de detectar las variaciones pulsátiles del volumen sanguíneo en el tejido donde se encuentra ubicado el sensor. Cuando la perfusión disminuye, la componente pulsátil de la señal fotopletismográfica se vuelve más débil y puede confundirse con ruido, movimiento u otras interferencias. Como consecuencia, el monitor puede tener dificultades para identificar correctamente los pulsos y calcular la saturación de oxígeno, mostrando valores inferiores a los reales o lecturas inestables. Por esta razón, una alarma de SpO₂ baja no siempre significa que exista una disminución real de oxígeno en la sangre; también puede estar relacionada con una señal de mala calidad o con una perfusión insuficiente en el sitio de medición. En el contexto de la práctica, el modo Low Perfusion permitió observar cómo una condición de baja perfusión puede afectar la adquisición de la señal y la interpretación de la medición.



## REFERENCIAS

[1] Universidad Militar Nueva Granada, Guía de Laboratorio: Simulación y monitoreo de variables cardiovasculares y hemodinámicas, Facultad de Ingeniería, Programa de Ingeniería Biomédica, Instrumentación Biomédica y Biosensores.

[2] Pronk Technologies, OxSim OX-1: Optical SpO₂ Simulator, manual de usuario y especificaciones técnicas del simulador.

[3] Mindray, uMEC Series Patient Monitor Operator’s Manual, Shenzhen Mindray Bio-Medical Electronics Co., Ltd.

[4] Mindray, uMEC Series – SpO₂ Monitoring Module Specifications, documentación técnica del fabricante.

[5] Mindray, uMEC Series Service Manual, procedimientos de prueba y verificación del monitor.
