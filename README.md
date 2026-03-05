# Estimación del nivel de estrés basada en la respuesta galvánica cutánea (GSR)

Samuel Joel Peña Rojas

Paula Vanessa Vera Caro

Daniel Leonardo López Castillo

## PARTE A
### Actividad electrodérmica

La actividad electrodérmica (EDA) se refiere a la medición de la resistencia o conductancia de la piel, que está asociada con la respuesta simpática de la piel y puede utilizarse para estudiar las respuestas simpáticas en invidividuos. Además, es una herramienta sencilla muy importante para medir la actividad de la rama simpática del sistema nervioso autónomo, a través de la actividad de las glándulas sudoríparas, siendo esta la base para medir la actividad electrodérmica.

La EDA tiene un componente tónico y fásico, siendo el primero el nivel de conductancia cutánea y el segundo la respuesta de conductancia cutánea o respuesta galvánica cutánea, las cuales nos ayudan a caracterizar el estado general de activación del sistema nervioso simpático y a identificar respuestas específicas ante estímulos internos o externos.

<div align="center">
<img width="366" height="290" alt="image" src="https://github.com/user-attachments/assets/40197dc5-e471-41fe-9959-a9d8d38b4594" />
</div>

### Respuesta galvánica cutánea

La Respuesta Galvánica Cutánea (GSR) se define como el cambio en las propiedades eléctricas de la piel debido a la excitación emocional y el estrés. Esta se puede medir aplicando una pequeña corriente sobre el paciente y se evalua la resistencia de la piel entre dos electrodos. Cuando se experimenta una emoción partícular, se activan las glándulas sudoríaparas de forma "sutil", generando un aumento en la conductividad eléctrica de la piel.

Dicho esto, la GSR mide las variaciones en la conductividad eléctrica de la piel en respuesta a ciertos estímulos. Por eso, este tipo de técnicas se usan comúnmente en polígrafos o sistemas de detección de mentiras, pues, si bien se pueden controlar las expresiones faciales, no se puede controlar las glándulas sudoríparas.

<div align="center">
<img width="412" height="412" alt="image" src="https://github.com/user-attachments/assets/780d36cf-130a-44ca-a410-28d564cba660" />
</div>

### Efectos de la corriente directa y alterna en seres humanos

Al aplicar una corriente eléctrica sobre el cuerpo humano, puede provocar daños fisiológicos según la cantidad aplicada. La corriente, al no ser preceptible, visible o inolora, hace que sea más peligrosa. Los riesgos y daños que puede producir la corriente por el cuerpo humanos están establecidos en la norma 60479 de la Comisión Electrotécnica Internacional (IEC), quien es el organismo que dicta las normas eléctricas. En dicha norma, se establecen los rangos de la corriente en que el cuerpo presenta un riesgo:

<div align="center">
<img width="387" height="395" alt="image" src="https://github.com/user-attachments/assets/29884bc4-93be-4952-9647-0c4e039fa447" />
</div>

Esta gráfica posee 4 zonas diferenciadas, en el que se establece lo siguiente:

- **Zona 1:** No se presenta ninguna reacción o daño, sin importar el tiempo de exposición
- **Zona 2:** No presenta un efecto fisiológico peligroso, sin embargo, se pueden percibir contracciones musculares o tetanizaciones leves.
- **Zona 3:** No  hay daño orgánico, pero se percibirán contracciones musculares, afectando la respiración, paradas temporales del corazón, pero sin llegar a una fibrilación ventricular
- **Zona 4:** Se presenta un riesgo de paro cardiaco por fibrilación ventricular, además de paro respiratorio y quemaduras graves. En esta zona, las consecuencias serán graves segun la intensidad y el tiempo de actuación.

Del mismo modo, es importante mencionar el papel que juega el tiempo de exposición. Por ejemplo, los efectos del paso de una corriente de 200 mA por 50 ms, son equivalentes a los de una corriente de 20 mA por un segundo. En la siguiente tabla se especifican los efectos de la corriente eléctrica de acuerdo al rango de la intensidad:

<div align="center">
<img width="495" height="497" alt="image" src="https://github.com/user-attachments/assets/8a6543e5-4356-4b6f-9249-2934d5b6b5fb" />
</div>

### Cálculo de la corriente eléctrica

<div align="center">
<img width="350" height="521" alt="image" src="https://github.com/user-attachments/assets/f96c0e9a-942b-4bbb-bb31-d84ceb1190d5" />
</div>

$$
I = \frac{5\,V}{68\,k\Omega + 0\,\Omega} = 7.35 \times 10^{-5}\,A = 73.52\,\mu A
$$

El valor de alimentación que se utiliza es de 5 V. Asumiendo el caso exagerado de que la Rskin, que corresponde a la resistencia de la piel, sea cero, realizamos el cálculo de la corriente que pasaría por el cuerpo en dicho caso, y se obtiene que es de 73,52 µA.

$$
73.52\,\mu A < 1\,mA
$$

Se puede observar que la corriente no es mayor a 1 mA en este caso extremo. Por lo tanto, es razonable inferir que dicha corriente será mucho menor en condiciones reales, ya que la conductancia de la piel no es tan alta como la que se plantea para realizar el cálculo. Por lo tanto, se trata de una corriente segura.

### Montaje

Para la realización de la práctica y la adquisición de la señal de respuesta galvánica, se diseño el circuito de acondicionamiento para capturar correctamente los niveles de estrés de una persona.

<div align="center">
<img width="484" height="335" alt="image" src="https://github.com/user-attachments/assets/63d62002-1d85-4e7a-8d27-7756961f93e5" />
</div>

En primer lugar, se escogió la región anatómica donde se sujetarán los electrodos para capturar la señal con un mínimo de interferencia. La región seleccionada fue la mano, ubicando los electrodos en la yema de los dedos. Estos electrodos serán ajustados con una cinta tipo velcro, para que estos tengan un minimo movimiento. Además, el dispositivo estará sujeto al brazo del paciente, por lo que los datos y variaciones de la GSR serán transmitidas de forma inalámbrica a un computador portatil.

(Aquí se adjunta imágen)

## Parte B

Para presentar el dispositivo de captura, se empleó el siguiente procedimiento:

**1.** Se conecta el dispositivo al paciente, pidiendole a este que esté sentado y en reposo.

**2.** se pide al sujeto de prueba que realice una inspiración profunda y luego exhale lentamente.

**3.** En este punto, se visualiza en la gráfica un aumento en el valor, para que luego disminuya de manera paulatina al valor inicial.

Dicha información será transmitida inalámbricamente a un computador portatil, en el que se verá la gráfica correspondiente a las variaciones de la GSR.

## Parte C


<img width="200" height="500" alt="image" src="https://github.com/user-attachments/assets/9aef9eb1-c201-4eae-aa15-087cb96c881b" />


**Calibración de Umbrales de Conductancia Cutánea**

Su objetivo es determinar los valores de los umbrales, que posteriormente se utilizarán para clasificar los estados fisiológicos de la persona en el sistema de detección de estrés.

El sistema realiza mediciones en cuatro condiciones fisiológicas diferentes:

- Movimiento

- Respiración

- Habla

- Estrés

Para cada condición, el programa solicita al usuario ingresar el tiempo de medición, durante el cual se registran los valores enviados por el ADC del microcontrolador.

```matlab
clc; clear; close all

s = serialport("COM3",115200);
configureTerminator(s,"LF");
flush(s);

Vref = 3.3;
ADC  = 4095;

estados = ["movimiento","respiracion","habla","estres"];

datos = struct;

for k = 1:length(estados)

    disp("Realizando medicion para: " + estados(k))
    x = input("Tiempo de lectura (s): ");

    tiempo = [];
    voltaje = [];

    tic
    while toc < x
        if s.NumBytesAvailable > 0

            bits = str2double(readline(s));

            if ~isnan(bits)

                V = bits * Vref / ADC;
                t = toc;

                tiempo(end+1) = t;
                voltaje(end+1) = V;

            end
        end
    end

    datos.(estados(k)).t = tiempo;
    datos.(estados(k)).v = voltaje;

end
```
Una vez adquiridos los datos de las cuatro condiciones fisiológicas, el programa genera gráficas independientes para cada estado y esto permite observar cómo cambia la señal de conductancia cutánea dependiendo de la actividad que esté realizando la persona.
Esto facilita la identificación visual de diferencias entre los estados fisiológicos, lo cual es fundamental para definir correctamente los umbrales de clasificación.

```matlab
figure

subplot(2,2,1)
plot(datos.movimiento.t, datos.movimiento.v)
title("Movimiento")
xlabel("Tiempo")
ylabel("Voltaje")
ylim([0 3.3])
grid on

subplot(2,2,2)
plot(datos.respiracion.t, datos.respiracion.v)
title("Respiracion")
xlabel("Tiempo")
ylabel("Voltaje")
ylim([0 3.3])
grid on

subplot(2,2,3)
plot(datos.habla.t, datos.habla.v)
title("Habla")
xlabel("Tiempo")
ylabel("Voltaje")
ylim([0 3.3])
grid on

subplot(2,2,4)
plot(datos.estres.t, datos.estres.v)
title("Estres")
xlabel("Tiempo")
ylabel("Voltaje")
ylim([0 3.3])
grid on
```
Después de visualizar las señales, el programa calcula el valor promedio de voltaje para cada estado fisiológico.
Estos valores promedio se utilizan como referencias para establecer los umbrales de clasificación que posteriormente se emplearán en el algoritmo de detección de estados.

```matlab
media_mov = mean(datos.movimiento.v);
media_res = mean(datos.respiracion.v);
media_hab = mean(datos.habla.v);
media_est = mean(datos.estres.v);

disp("----- UMBRALES -----")

fprintf("Movimiento > %.3f V\n",media_mov)
fprintf("Respiracion ≈ %.3f V\n",media_res)
fprintf("Habla ≈ %.3f V\n",media_hab)
fprintf("Estres > %.3f V\n",media_est)
```
Al finalizar el programa muestra en la consola los valores promedio de voltaje asociados a cada estado fisiológico.
Estos valores sirven como umbrales de referencia para el algoritmo de clasificación implementado posteriormente en el sistema de detección de estrés.

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/42f75e7d-db53-41af-a64d-a708ada16102" />

<img width="296" height="248" alt="image" src="https://github.com/user-attachments/assets/177e2390-9a0c-46f3-a8e6-dba05ca8f33e" />


En las gráficas se presentan las señales de conductancia cutánea en función del tiempo para cuatro condiciones fisiológicas diferentes: movimiento, respiración, habla y estrés. Cada gráfica muestra cómo varía el voltaje medido por los electrodos durante aproximadamente 20 segundos.
En movimiento, la señal presenta variaciones bruscas y picos frecuentes. Esto ocurre porque el movimiento corporal produce cambios en el contacto de los electrodos con la piel y pequeñas perturbaciones eléctricas, lo que genera una señal más inestable.
En la señal de respiración, el voltaje se mantiene casi estable alrededor de un valor medio cercano a 1.2 V, con pequeñas variaciones.
Para la condición de habla, la señal presenta ligeras oscilaciones adicionales en comparación con la respiración. Esto se debe a la activación de músculos faciales y torácicos durante el habla, lo cual introduce pequeñas perturbaciones en la señal de conductancia.
En la condición de estrés, se observa un aumento progresivo del voltaje hasta valores cercanos a 1.6 V. Este incremento está relacionado con la activación del sistema nervioso simpático, que aumenta la actividad de las glándulas sudoríparas y, por lo tanto, incrementa la conductancia eléctrica de la piel.

**Adquisición y Clasificación de Conductancia Cutánea**


El sistema está diseñado para adquirir señales de conductancia cutánea, las cuales se relacionan con la actividad del sistema nervioso autónomo y pueden reflejar estados fisiológicos como movimiento, respiración, habla o estrés.

Primero, el programa establece la conexión serial con el microcontrolador y define los parámetros del ADC (convertidor analógico–digital). Posteriormente, solicita al usuario ingresar el tiempo de medición, durante el cual se adquirirán los datos enviados por el sensor.
Los valores enviados por el microcontrolador corresponden a bits del ADC, por lo que es necesario convertirlos a voltaje para obtener el valor real de la señal eléctrica medida por los electrodos.
La conversión se realiza mediante la relación:

$$
V = \frac{\text{bits} \cdot V_{ref}}{ADC}
$$

$$
V = \frac{\text{bits} \cdot 3.3}{4095}
$$

```matlab
clc; clear; close all
s = serialport("COM5",115200);
configureTerminator(s,"LF");
flush(s);

Vref = 3.3;
ADC  = 4095;

% Umbrales fisiológicos
movimiento  = 1.27;
respiracion = 1.30;
habla       = 1.15;
estres_base = 1.31;

% Niveles de estrés
nivel1 = estres_base;
nivel2 = estres_base + 0.2;
nivel3 = estres_base + 0.4;
nivel4 = estres_base + 0.6;
nivel5 = estres_base + 0.8;

N = 300;
bufferV = nan(1,N);
bufferT = nan(1,N);

x = input("Ingrese el tiempo deseado de lectura: ");

tiempo = [];
voltaje = [];

figure(1)
h = plot(bufferT, bufferV,'b','LineWidth',2);
grid on
xlabel("Tiempo (s)")
ylabel("Voltaje (V)")
title("Conductancia Cutanea")
ylim([0 3.3])

tic
while toc < x

    if s.NumBytesAvailable > 0

        bits = str2double(readline(s));

        if ~isnan(bits)

            V = bits * Vref / ADC;
            t = toc;

            tiempo(end+1) = t;
            voltaje(end+1) = V;

            bufferV = [bufferV(2:end) V];
            bufferT = [bufferT(2:end) t];

            set(h,'XData',bufferT,'YData',bufferV)
            drawnow limitrate

            % Clasificación del estado
            estado = "Normal";

            if V > movimiento
                estado = "Movimiento";
            end

            if abs(V - respiracion) < 0.02
                estado = "Respiracion";
            end

            if abs(V - habla) < 0.02
                estado = "Habla";
            end

            if V > estres_base
                estado = "ESTRES";
            end

            % Nivel de estrés
            nivel_estres = 0;

            if V > nivel1
                nivel_estres = 1;
            end
            if V > nivel2
                nivel_estres = 2;
            end
            if V > nivel3
                nivel_estres = 3;
            end
            if V > nivel4
                nivel_estres = 4;
            end
            if V > nivel5
                nivel_estres = 5;
            end

            fprintf("Voltaje: %.3f V | Estado: %s",V,estado)

            if nivel_estres > 0
                fprintf(" | ALERTA: Estres Nivel %d\n",nivel_estres)
            else
                fprintf("\n")
            end

        end
    end
end

figure(2)
plot(tiempo,voltaje,'r','LineWidth',1.5)
xlabel('Tiempo (s)')
ylabel('Voltaje (V)')
title('Conductancia Cutanea')
ylim([0 3.3])
grid on
```
El microcontrolador envía continuamente los datos del sensor en forma de bits del ADC. MATLAB recibe estos datos a través del puerto serial, los convierte a voltaje y los almacena junto con su respectivo tiempo de adquisición.
A medida que se reciben los datos, el programa actualiza una gráfica en tiempo real, permitiendo visualizar la evolución de la señal de conductancia cutánea.
Posteriormente, el sistema compara el voltaje obtenido con los umbrales fisiológicos definidos previamente, lo que permite identificar el estado en el que se encuentra la persona. Si el voltaje supera el umbral de estrés, el programa también determina el nivel de estrés correspondiente, generando una alerta que se muestra en la consola.
Para que al terminar el tiempo de medición, se generé una gráfica completa de la señal registrada, mostrando el comportamiento de la conductancia cutánea durante todo el experimento.

<img width="269" height="33" alt="image" src="https://github.com/user-attachments/assets/a8ae1267-7b15-4a27-b5d1-7c80a221f41e" />
<img width="678" height="432" alt="image" src="https://github.com/user-attachments/assets/b5a07f16-ce6c-45fc-a10a-2d0542aaf599" />

Durante todo el intervalo de medición el voltaje se mantiene aproximadamente entre 0.60 V y 0.95 V, lo que nos dice que la señal es estable pero, presenta variaciones asociadas a cambios fisiológicos.

El primer intervalo (0 – 10 s)
En los primeros segundos la señal muestra pequeñas fluctuaciones y corresponde a un estado basal o de reposo, donde la actividad del sistema nervioso simpático es baja y la conductancia de la piel se mantiene relativamente constante.

El Segundo intervalo (10 – 17 s)
En este tramo se observa un incremento progresivo del voltaje, alcanzando valores cercanos a 0.85 V – 0.90 V. Este aumento puede verse como una activación fisiológica, posiblemente causada por una respuesta fisiológica del organismo.

El tercer intervalo (17 – 21 s)
Posteriormente se presenta una disminución leve de la señal, descendiendo nuevamente hacia valores cercanos a 0.75 V – 0.80 V. Esto indica una recuperación parcial del estado basal, donde la actividad simpática disminuye ligeramente.

El cuarto intervalo (21 – 25 s)
En este periodo se observa de nuevo un aumento del voltaje, alcanzando el punto más alto de la gráfica cercano a 0.95 V. Este comportamiento puede interpretarse como una respuesta fisiológica a un nivel de activación o estrés momentáneo.

El Último intervalo (25 – 30 s)
La señal presenta una ligera reducción y estabilización, manteniéndose alrededor de 0.80 V – 0.90 V, lo que indica que el sistema fisiológico comienza a estabilizarse después del pico observado anteriormente.

- **¿A qué se debe que una inspiración profunda incremente la magnitud de la respuesta galvánica cutánea (GSR)?**
- **¿Cuáles serían las ventajas y desventajas de utilizar la GSR como indicador de estrés?**

# Conclusiones

# REFERENCIAS 
- https://pmc.ncbi.nlm.nih.gov/articles/PMC9215837/
- https://www.sciencedirect.com/topics/medicine-and-dentistry/electrodermal-activity
- https://www.sciencedirect.com/topics/computer-science/galvanic-skin-response
- https://areatecnologia.com/electricidad/danos-corriente.html
