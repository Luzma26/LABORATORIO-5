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

| Prueba | SpO₂ simulada | FC simulada | SpO₂ medida | FC medida | Error SpO₂ | Error FC |
|---|---:|---:|---:|---:|---:|---:|
| 85 % / 80 bpm | 85 % | 80 bpm | 85 % | 80 bpm | 0 % | 0 % |
| 95 % / 40 bpm – primer intento | 95 % | 40 bpm | 94 % | 80 bpm | 1,05 % | 100 % |
| 95 % / 40 bpm – repetición | 95 % | 40 bpm | 96 % | 40 bpm | 1,05 % | 0 % |
| 98 % / 80 bpm | 98 % | 80 bpm | 98 % | 80 bpm | 0 % | 0 % |
| 98 % / 140 bpm | 98 % | 140 bpm | 98 % | 140 bpm | 0 % | 0 % |

### Codigo en Arduino IDE



### Adquisición de temperatura y humedad

Durante las pruebas, el sensor DHT11 permitió obtener las mediciones ambientales de la cámara. Los valores se mostraron en la pantalla OLED, lo que facilitó observar los cambios producidos por el calentamiento y la circulación del aire.

Se comprobó que el sistema respondía a las condiciones de temperatura mediante los indicadores luminosos y la activación del ventilador superior. También se observó que la incubadora tardaba en calentarse, lo que indica que el proceso de aumento de temperatura no era inmediato.

Este comportamiento puede relacionarse con la capacidad de calentamiento del bombillo, las pérdidas de calor hacia el ambiente, el aislamiento de la estructura y la circulación del aire. Debido a que el calentador no estaba regulado automáticamente por el Arduino, el sistema no podía ajustar directamente la potencia térmica para alcanzar el intervalo de referencia con mayor rapidez.

El DHT11 presenta limitaciones de precisión y tiempo de respuesta en comparación con sensores especializados para equipos médicos. Por lo tanto, las mediciones obtenidas se interpretaron como parte de una práctica académica y no como una validación de precisión clínica.

### Estimación del peso mediante el FSR400

El FSR400 es un sensor resistivo cuya resistencia cambia cuando se aplica una fuerza sobre su superficie. En el circuito, este cambio produce una variación de tensión que se lee mediante la entrada analógica A0 del Arduino.

Para establecer una relación entre la lectura analógica y el peso, se realizó una calibración experimental con una masa patrón. El sistema permitió expresar la estimación en gramos y compararla con el valor de referencia.

Durante las pruebas se obtuvo un error aproximado del 9 %. Este resultado indica que la estimación fue relativamente cercana al peso patrón y que el sensor permitió reconocer la carga aplicada. Sin embargo, la diferencia observada evidencia que la medición todavía puede mejorarse.

El error absoluto de la estimación se calcula mediante:

E_a = |m_estimada - m_patron|

El error relativo porcentual se calcula mediante:

E_r(%) = (E_a / m_patron) × 100

Donde m_estimada es la masa estimada por el sistema y m_patron es la masa conocida utilizada como referencia. El error relativo no se calcula cuando la masa patrón es cero.

El error relativo obtenido durante la práctica fue aproximadamente:

E_r ≈ 9 %

La exactitud de la estimación depende de la distribución de la carga, el contacto mecánico con el sensor, la repetibilidad de las mediciones y el intervalo de masas utilizado durante la calibración. Debido a estas limitaciones, el FSR400 no equivale a una balanza clínica.

<img width="838" height="747" alt="image" src="https://github.com/user-attachments/assets/4306e527-c46f-469c-9598-07a8af4fdd07" />

Fig.3. Ubicación sensor FSR400

### Cálculo de costos

Para determinar el costo total del prototipo se deben registrar los precios reales de los componentes y sumar los costos parciales de cada elemento. Se deben incluir el Arduino Uno, el sensor DHT11, el FSR400, la pantalla OLED, los ventiladores, el transistor TIP122, el diodo 1N4007, los LED, las resistencias, la protoboard, los cables, la fuente de alimentación y los materiales de la estructura.

El costo total se obtiene mediante la expresión:

C_total = C_Arduino + C_DHT11 + C_FSR400 + C_OLED + C_ventiladores + C_componentes + C_protoboard + C_estructura + C_bombillo

C_total = 32.000 + 8.000 + 28.000 + 23.000 + 18.000 + 12.000 + 8.000 + 20.000 + 8.000

C_total = $157.000 COP


### Evaluación del sistema

La evaluación del prototipo se realizó mediante pruebas de funcionamiento de sus componentes y del sistema integrado. Se comprobó que el sensor ambiental entregara lecturas, que la pantalla mostrara los valores, que los LED respondieran al intervalo de temperatura programado y que el ventilador superior se activara o desactivara de acuerdo con la lógica establecida.

También se evaluó el sensor FSR400 mediante la comparación de la masa estimada con una masa patrón. El error obtenido fue aproximadamente del 9 %, lo que permitió establecer una referencia cuantitativa del desempeño del sistema de medición del peso.

En las pruebas se observó que los componentes electrónicos funcionaban según lo planeado. Sin embargo, el calentamiento de la cámara era lento y el sistema no contaba con una regulación automática del bombillo. Por esta razón, aunque el sistema respondía a los cambios de temperatura mediante los indicadores y el ventilador, todavía presentaba limitaciones para mantener las condiciones térmicas de forma precisa.

## RESULTADOS

### Funcionamiento general del prototipo

El prototipo integró los principales componentes electrónicos previstos para representar algunas funciones de una incubadora neonatal a escala. El Arduino Uno actuó como unidad de procesamiento, el sensor DHT11 permitió adquirir la temperatura y la humedad, la pantalla OLED facilitó la visualización de las mediciones y los LED indicaron el estado térmico de la cámara.

El sistema incorporó dos ventiladores con funciones diferenciadas. El ventilador inferior permaneció encendido para favorecer la circulación del aire, mientras que el ventilador superior respondió a la temperatura medida por el sensor. De esta forma, el montaje permitió representar una estrategia básica de control ambiental mediante sensores y actuadores.

Durante las pruebas se comprobó que los ventiladores y los indicadores luminosos funcionaban correctamente. La pantalla OLED también mostró la información prevista e indicó cuándo el ventilador debía encenderse o apagarse. Estos resultados evidenciaron que la integración entre el Arduino, los sensores, la pantalla y las salidas de control funcionó según lo planeado.

No obstante, se observó que la incubadora tardaba en calentarse. Este comportamiento mostró que el proceso de calentamiento dependía de las características de la fuente de calor, el aislamiento de la estructura y las condiciones de circulación del aire. Además, el bombillo no estaba regulado automáticamente por el Arduino, por lo que el sistema no podía ajustar directamente la potencia de calentamiento.

### Respuesta del sistema ante los cambios de temperatura

El programa estableció tres estados de funcionamiento según la temperatura medida. Por debajo de 36 °C, el sistema indicó una condición de temperatura baja mediante el LED azul. Entre 36 °C y 37,5 °C, el LED verde representó el intervalo establecido como referencia. Por encima de 37,5 °C, se encendió el LED rojo y se activó el ventilador superior.

Durante las pruebas se observó que los indicadores luminosos respondían correctamente a la lógica programada y que la pantalla OLED mostraba el estado del ventilador. Cuando la temperatura alcanzaba el umbral superior, el sistema indicaba que debía activarse la ventilación, y cuando descendía por debajo del umbral inferior, indicaba que debía apagarse.

Este comportamiento demostró que una medición ambiental puede utilizarse para modificar el estado de un actuador. Sin embargo, la activación del ventilador no garantiza por sí sola que la temperatura regrese al intervalo deseado, ya que el resultado depende de la potencia del bombillo, el aislamiento de la cámara, la circulación del aire y las condiciones ambientales.

Una limitación importante es que el bombillo permaneció encendido sin regulación automática. En consecuencia, el prototipo no dispuso de un control completo del calentamiento y la refrigeración. Aunque los componentes respondieron según lo programado, se observó que el calentamiento de la cámara era lento.

Para mejorar este comportamiento, sería necesario incorporar un sistema que permita regular automáticamente el calentador, mejorar el aislamiento térmico y evaluar la distribución del calor dentro de la cámara. También sería conveniente registrar la temperatura durante un periodo definido para cuantificar el tiempo requerido para alcanzar el intervalo de referencia y determinar cuánto tiempo permanece dentro de él.

### Adquisición de humedad

El sensor DHT11 permitió obtener una lectura de humedad relativa junto con la temperatura. Esta medición resultó útil para observar las condiciones ambientales dentro de la cámara y reconocer que la humedad constituye una variable importante en el cuidado neonatal.

No obstante, el prototipo no incorporó un humidificador ni un mecanismo automático para regular la humedad. Por esta razón, el sistema podía medir y mostrar esta variable, pero no garantizar que permaneciera dentro de un intervalo específico.

### Lectura del sensor FSR400

El sensor FSR400 permitió detectar cambios en la fuerza aplicada mediante variaciones de su resistencia eléctrica. La conexión con el divisor de tensión permitió convertir esos cambios en lecturas analógicas que el Arduino procesó para estimar el peso.

Durante las pruebas, el sistema mostró el peso estimado en gramos y se comparó el resultado con una masa patrón. Se obtuvo un error aproximado del 9 %, por lo que el valor calculado fue relativamente cercano al valor de referencia.

Este resultado indica que el sensor pudo utilizarse para realizar una estimación del peso dentro de las condiciones de la práctica. Sin embargo, la diferencia entre el valor estimado y el patrón evidencia que la medición no fue completamente exacta.

El error puede estar relacionado con la respuesta no lineal del FSR400, la calibración utilizada, la distribución de la carga y la forma en que la fuerza se transmite al sensor. Para mejorar la medición, sería conveniente utilizar varias masas patrón, repetir las mediciones y construir una curva de calibración que represente mejor la respuesta del sensor.

A pesar del error observado, el resultado permitió comprobar que el FSR400 puede integrarse con el Arduino y una pantalla OLED para desarrollar un sistema experimental de estimación del peso. Sin embargo, este montaje no debe considerarse equivalente a una balanza clínica calibrada.

### Comparación general con una incubadora comercial

El prototipo permite demostrar principios de medición, visualización y control, pero presenta diferencias importantes frente a las incubadoras comerciales. Equipos como la Dräger Isolette 8000 plus incorporan funciones avanzadas de control térmico, monitorización y gestión de humedad, según su configuración [3], [4].

La incubadora YP2000 comercializada por Instrumentalia ofrece funciones de control ambiental y una estructura destinada al cuidado neonatal [5]. Por su parte, la incubadora B3 de LEEX Medical incorpora funciones comerciales de control de temperatura y humidificación, según su configuración [6].

En comparación con estos equipos, el prototipo académico tiene la ventaja de permitir la modificación del programa y la observación directa del funcionamiento de los sensores y actuadores. Durante la práctica se comprobó que los ventiladores, los indicadores luminosos y la pantalla funcionaban según lo planeado, y que el sensor FSR400 permitía estimar el peso con un error aproximado del 9 %.

Sin embargo, el prototipo no cuenta con regulación automática del calentamiento, control activo de humedad, alarmas clínicas ni un sistema de medición del peso validado. Además, el calentamiento lento de la cámara muestra que todavía existen aspectos por mejorar en el desempeño térmico.

Por lo tanto, los resultados obtenidos permiten estudiar el funcionamiento básico de una incubadora, pero no demuestran que el sistema tenga la precisión, confiabilidad o seguridad necesarias para sustituir un equipo médico.

## 13. ANÁLISIS DE RESULTADOS

### Análisis 1. Eficacia del sistema para controlar la temperatura de la cabina y error en el cálculo del peso

El sistema desarrollado permitió representar algunos de los principios de funcionamiento de una incubadora neonatal mediante la adquisición de temperatura y humedad con el sensor DHT11, la visualización de los datos en una pantalla OLED y la activación de indicadores luminosos y ventiladores mediante un Arduino Uno. Durante las pruebas se comprobó que los componentes electrónicos funcionaban según lo planeado y que la pantalla OLED indicaba cuándo el ventilador debía encenderse o apagarse.

Para evaluar la respuesta térmica, se estableció como referencia un intervalo de 36 °C a 37,5 °C. Cuando la temperatura era inferior a 36 °C, se encendía el LED azul; cuando se encontraba dentro del intervalo, se encendía el LED verde; y cuando superaba los 37,5 °C, se encendía el LED rojo y se activaba el ventilador superior. El ventilador inferior permaneció encendido para favorecer la circulación del aire.

Este comportamiento demostró una estrategia básica de control por realimentación, ya que la temperatura medida se utilizó para determinar el estado del ventilador y de los indicadores luminosos. Sin embargo, durante las pruebas se observó que la incubadora tardaba en calentarse. Esto evidencia que, aunque el sistema de ventilación respondía correctamente, el proceso de calentamiento no era inmediato.

El tiempo requerido para elevar la temperatura puede estar relacionado con la potencia de la fuente de calor, las pérdidas térmicas hacia el ambiente, el aislamiento de la cámara y la circulación del aire. Una limitación importante es que el bombillo utilizado como fuente de calor permanecía encendido y no estaba regulado automáticamente por el Arduino. Por esta razón, el sistema podía responder al aumento de temperatura mediante ventilación, pero no podía reducir directamente la potencia de calentamiento.

En consecuencia, se comprobó el funcionamiento de los elementos de indicación y ventilación, pero no puede afirmarse que la cabina mantuviera una temperatura constante dentro del intervalo de referencia durante todo el periodo de prueba. Para cuantificar la eficacia térmica sería necesario registrar la temperatura a intervalos regulares y calcular el porcentaje de mediciones que permanecen dentro del intervalo deseado.

Este porcentaje puede determinarse mediante:

P(%) = (N_dentro / N_total) × 100

Donde N_dentro corresponde al número de mediciones entre 36 °C y 37,5 °C, y N_total representa el número total de mediciones registradas.

En cuanto a la estimación del peso, el FSR400 permitió detectar cambios en la fuerza aplicada mediante variaciones de su resistencia eléctrica. La señal analógica obtenida por el Arduino se convirtió en una estimación expresada en gramos y se comparó con una masa patrón.

Durante las pruebas se obtuvo un error relativo aproximado del 9 %. Este resultado indica que el peso estimado fue relativamente cercano al valor de referencia, aunque presentó una diferencia que puede mejorarse mediante una calibración más precisa.

El error absoluto de la estimación se determina mediante:

E_a = |m_estimada - m_patron|

El error relativo porcentual se calcula mediante:

E_r(%) = (E_a / m_patron) × 100

Donde m_estimada corresponde a la masa estimada por el sistema y m_patron representa la masa conocida utilizada como referencia. El error relativo no se calcula cuando la masa patrón es cero.

El resultado del 9 % evidencia que el sensor permitió realizar una estimación funcional del peso, pero también muestra que la medición no fue completamente exacta. La diferencia puede estar relacionada con la calibración, la distribución de la fuerza sobre el sensor, la repetibilidad de las mediciones y las características propias del FSR400.

En general, los resultados permitieron comprobar el funcionamiento de los principales componentes del prototipo. Los ventiladores y los indicadores luminosos respondieron según lo programado, la pantalla OLED mostró la información prevista y el sensor de fuerza produjo una estimación relativamente cercana al peso patrón. No obstante, el calentamiento lento y el error de medición evidencian la necesidad de mejorar la regulación térmica y la calibración del sistema de pesaje.

### Análisis 2. Comparación del sistema desarrollado con los equipos comerciales

El prototipo construido se diferencia de las incubadoras comerciales principalmente por su complejidad, precisión, seguridad y cantidad de variables controladas. Mientras que el sistema académico utiliza componentes electrónicos para demostrar principios básicos de instrumentación, los equipos comerciales están diseñados para proporcionar condiciones ambientales controladas y ofrecer funciones específicas para la atención neonatal.

La incubadora Dräger Isolette 8000 plus incorpora funciones avanzadas de control térmico, monitorización y gestión de humedad según su configuración, además de opciones de pesaje. Estas características permiten un control más completo que el del prototipo, aunque su adquisición y mantenimiento requieren proveedores especializados [3], [4].

Por su parte, la incubadora YP2000 comercializada por Instrumentalia cuenta con una estructura y funciones destinadas al control ambiental neonatal [5]. Durante la consulta comercial se identificó un precio publicado de aproximadamente $53.391.350 COP, incluidos impuestos. Este valor debe confirmarse con el proveedor, ya que puede variar según la disponibilidad, la configuración y las condiciones de venta.

La incubadora B3 de LEEX Medical también ofrece funciones comerciales de control de temperatura y humidificación, según la configuración del equipo. Su precio debe solicitarse directamente al fabricante o distribuidor [6].

Frente a estas alternativas, el prototipo académico presenta como ventaja su bajo costo relativo y la posibilidad de modificar el programa para observar la relación entre las mediciones de los sensores y la respuesta de los actuadores. Además, permite aplicar conocimientos de electrónica, programación, adquisición de señales y control de variables físicas.

Los resultados obtenidos durante el laboratorio muestran que fue posible integrar los sensores, los indicadores luminosos, la pantalla OLED y los ventiladores. El sistema de medición del peso también presentó un error aproximado del 9 %, lo que demuestra que fue posible obtener una estimación relativamente cercana a una masa patrón.

No obstante, las limitaciones siguen siendo importantes. El bombillo no cuenta con regulación automática, no existe un sistema activo de control de humedad, el FSR400 presenta un margen de error y el montaje no incorpora las alarmas, redundancias ni las funciones de seguridad de una incubadora clínica. Asimismo, se observó que la cámara tardaba en calentarse, lo que evidencia que el desempeño térmico puede mejorarse.

Por tanto, el prototipo es útil como herramienta educativa para comprender el funcionamiento general de una incubadora neonatal, pero no ofrece las mismas capacidades que los equipos comerciales. La diferencia no depende únicamente del precio, sino también de la precisión de los sensores, la capacidad de control, la confiabilidad y las medidas de seguridad necesarias para proteger al paciente.

## 14. CONCLUSIÓN

La construcción y evaluación del prototipo de incubadora neonatal permitió reconocer la importancia de controlar las condiciones ambientales para favorecer la estabilidad térmica del neonato e identificar los componentes principales que intervienen en el funcionamiento de estos equipos. La integración del Arduino Uno, el sensor DHT11, el FSR400, la pantalla OLED, los indicadores luminosos y los ventiladores permitió desarrollar un sistema que respondió según lo programado durante las pruebas. La pantalla mostró la información prevista e indicó cuándo el ventilador debía encenderse o apagarse, mientras que los indicadores luminosos y los ventiladores funcionaron correctamente. En la estimación del peso, el FSR400 presentó un error aproximado del 9 %, por lo que el valor obtenido fue relativamente cercano al peso patrón, aunque todavía puede mejorarse mediante una calibración más precisa. En cuanto al comportamiento térmico, se observó que la incubadora tardaba en calentarse y que el bombillo no estaba regulado automáticamente por el Arduino, lo que limitó la capacidad del sistema para mantener la temperatura de manera precisa. Estos resultados muestran que es posible representar funciones básicas de una incubadora mediante componentes electrónicos de bajo costo, pero que la regulación térmica y la medición del peso requieren mejoras para obtener resultados más exactos y confiables. Como siguiente paso, se propone incorporar un sistema de control automático del calentamiento, mejorar el aislamiento térmico, realizar mediciones repetidas de temperatura y peso y evaluar el desempeño del prototipo mediante pruebas cuantitativas. El sistema desarrollado constituye una herramienta académica para comprender los principios de instrumentación biomédica, pero no debe utilizarse como sustituto de una incubadora clínica.

## 15. PREGUNTAS PARA LA DISCUSIÓN

### Pregunta 1. ¿Qué otras variables, y por qué, además de las mencionadas son críticas en el monitoreo neonatal?

Además de la temperatura, la humedad y el flujo de aire, existen otras variables relevantes para evaluar el estado del recién nacido. Entre ellas se encuentran la frecuencia cardiaca, la frecuencia respiratoria, la saturación de oxígeno y, cuando está indicado clínicamente, la presión arterial. Estas variables proporcionan información sobre el funcionamiento cardiovascular y respiratorio.

La concentración de oxígeno también es importante cuando se administra oxígeno suplementario, mientras que la temperatura cutánea puede complementar la evaluación térmica. Asimismo, el ruido y la iluminación del entorno deben considerarse porque forman parte de las condiciones ambientales que rodean al neonato.

La medición de estas variables requiere sensores y equipos apropiados para cada función. En una incubadora clínica, su integración depende de las necesidades del paciente y de las características del equipo utilizado [2], [3].

### Pregunta 2. ¿Qué haría falta para convertir el sistema desarrollado en una incubadora neonatal real?

Para convertir el prototipo en una incubadora neonatal apta para uso clínico sería necesario realizar modificaciones importantes en el sistema de control, los sensores, la estructura y las medidas de seguridad.

En primer lugar, se necesitaría un sistema de calentamiento regulado automáticamente mediante un controlador que mantenga la temperatura de referencia y reduzca el riesgo de sobrecalentamiento. También sería necesario incorporar sensores calibrados, verificar la uniformidad térmica dentro de la cabina e implementar un sistema de humidificación con medición y regulación de la humedad.

Además, deberían incorporarse alarmas para detectar temperaturas fuera de rango, fallas de sensores y pérdida de alimentación. La circulación del aire tendría que evaluarse para comprobar que la distribución del calor sea adecuada y que no se produzcan corrientes perjudiciales.

El sistema de medición del peso también requeriría una plataforma apropiada y una calibración verificable. De igual manera, la estructura debería construirse con materiales seguros, resistentes y fáciles de limpiar y desinfectar.

Finalmente, sería indispensable realizar pruebas de seguridad eléctrica, gestión de riesgos, confiabilidad y desempeño, además de cumplir los requisitos regulatorios aplicables a los dispositivos médicos. Estas condiciones demuestran que convertir un prototipo académico en una incubadora real exige mucho más que integrar sensores y programar un microcontrolador.

### Pregunta 3. ¿Qué semejanzas hay entre una incubadora neonatal y una servocuna?

La incubadora neonatal y la servocuna tienen como finalidad contribuir al mantenimiento de una temperatura apropiada para el recién nacido. Ambas pueden utilizar sensores, sistemas de calentamiento, controles electrónicos y alarmas para vigilar las condiciones térmicas.

La principal diferencia se encuentra en su estructura y en la forma de transferir el calor. La incubadora neonatal utiliza una cámara cerrada que proporciona un microambiente protegido y permite controlar las condiciones internas. La servocuna o cuna radiante utiliza un elemento calefactor situado por encima del paciente, que transmite calor principalmente mediante radiación y permite un acceso más directo durante los procedimientos clínicos.

En consecuencia, ambos equipos comparten el objetivo de favorecer la estabilidad térmica del neonato, pero se diferencian en la forma de proporcionar calor, el nivel de aislamiento y la facilidad de acceso al paciente [3], [7].

## REFERENCIAS

[1] Universidad Militar Nueva Granada, “Diseño y construcción de una incubadora neonatal a escala,” *Guía de laboratorio de Instrumentación Biomédica y Biosensores*, 2025.
