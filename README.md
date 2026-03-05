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




# REFERENCIAS 
- https://pmc.ncbi.nlm.nih.gov/articles/PMC9215837/
- https://www.sciencedirect.com/topics/medicine-and-dentistry/electrodermal-activity
- https://www.sciencedirect.com/topics/computer-science/galvanic-skin-response
- https://areatecnologia.com/electricidad/danos-corriente.html
