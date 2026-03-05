# Laboratorio respuesta galvanica cutánea
# Objetivos
- Identificar las componentes estacionaria y transitoria de la conductancia cutánea
- Elaborar un dispositivo para el monitoreo de la actividad electrodérmica
- Plantear una hipótesis desde la fisiología humana de como la GSR (respuesta Galvánica Cutánea) es un buen indicador del estrés.
# Marco teorico y selección de zona anatomica
La actividad electrodérmica, conocida como EDA por sus siglas en inglés, o también como respuesta galvánica de la piel es un marcador fisiológico ampliamente validado de la activación del sistema nervioso simpático. Desde el punto de vista neurofisiológico, la EDA refleja cambios en la conductancia eléctrica de la piel producidos por la actividad de las glándulas sudoríparas ecrinas, las cuales están inervadas exclusivamente por fibras simpáticas colinérgicas. Cuando un individuo experimenta estrés, carga cognitiva o algún tipo de activación emocional, se incrementa la actividad simpática, lo que provoca mayor secreción sudomotora y, en consecuencia, un aumento en la conductancia cutánea [1,2]. A diferencia de la sudoración térmica, que responde a cambios en la temperatura ambiental, la sudoración emocional se concentra en palmas, plantas y llemas de los dedos y no varía en función de la temperatura del entorno, incrementándose durante estados de activación mental y disminuyendo durante el reposo y el sueño [3].
<img width="656" height="264" alt="image" src="https://github.com/user-attachments/assets/c329fecd-1a6d-4cad-943a-8f6200c3dbd1" />

En términos de señal, la GSR se compone de un nivel tónico denominado Skin Conductance Level (SCL), que representa el estado basal de activación simpática; su valor se encuentra alrededor de los 12.36 µS para los dedos y valores menores en zonas no palmares o plantares como las muñecas o frente; y por la componente SCR (Skin Conductance Responses) de respuestas fásicas transitorias denominadas asociadas a estímulos específicos o eventos emocionales. Se ha encontrado que, debido a la alta densidad de glándulas ecrinas y al efectivo tiempo de respuesta, la zona palmar es adecuada para realizar mediciones del estrés, siendo comparada con otros marcadores fisiológicos de estrés como el ritmo cardíaco, presión arterial y niveles de epinefrina y norepinefrina [4,5]. 

<img width="544" height="436" alt="image" src="https://github.com/user-attachments/assets/ca189424-8a26-4958-9146-0aa0d738553a" />


# Seguridad del paciente y normativa


| Intensidad de corriente alterna 50 Hz (mA) | Intensidad de corriente continua (mA) | Efectos de la corriente eléctrica sobre el cuerpo humano |
|---------------------------------------------|---------------------------------------|-----------------------------------------------------------|
| 0.5 – 1 | 0 – 4 | **Percepción:** Intensidad con la que se percibe la existencia de tensión sin ninguna reacción muscular. |
| 1 – 3 | 4 – 15 | **Sorpresa:** Intensidad de reacción muscular por la que los músculos reaccionan dejando de asir o separándose inmediatamente del conductor bajo tensión tocado por la persona. |
| 3 – 21 | 15 – 80 | **Acción refleja:** Una corriente mayor a la intensidad límite impide dejar de asir o separarse del conductor tocado bajo tensión eléctrica, agarrota los músculos. |
| 21 – 40 | 80 – 160 | **Contracciones musculares incontroladas:** Se pierde el control del músculo, estos no responden a las órdenes cerebrales. Hay fibrilación ventricular y paro cardiaco. |
| 40 – 100 | 160 – 300 | **Paro respiratorio:** No se puede respirar. |
| Más de 100 | Más de 300 | **Fatalidad:** Muerte segura. |


según la norma IEC 60479, que sintetiza evidencia experimental y clínica sobre la interacción entre corriente eléctrica y tejidos biológicos, el umbral de percepción para corriente alterna sinusoidal en el rango de 15 a 100 Hz se sitúa aproximadamente alrededor de 0,5 a 1 mA en adultos promedio, y menor a 4 mA para corriente continua, por este motivo, se requiere hacer unos breves cálculos para garantizar la seguridad del paciente.
<img width="1599" height="1311" alt="image" src="https://github.com/user-attachments/assets/347784d5-90a4-432a-8002-eae4d88cb7cc" />

### Ecuación del circuito

$$
I = \frac{V_{CC}-V_{EE}}{68K + R_{cutánea}}
$$




# Procesamiento del código
# Resultados y análisis

# Conclusiones
# Referencias
[1] M. Benedek y C. Kaernbach, “A continuous measure of phasic electrodermal activity,” J. Neurosci. Methods, vol. 190, pp. 80–91, 2010. doi: 10.1016/j.jneumeth.2010.04.028.


[2] M. Benedek y C. Kaernbach, “Decomposition of skin conductance data by means of nonnegative deconvolution,” Psychophysiology, vol. 47, no. 4, pp. 647–658, 2010. doi: 10.1111/j.1469-8986.2009.00972.x.


[3]A. Zamkah, T. Hui, S. Andrews, N. Dey, F. Shi, and R. S. Sherratt, "Identification of Suitable Biomarkers for Stress and 
Emotion Detection for Future Personal Affective Wearable Sensors," Biosensors, vol. 10, no. 4, p. 40, Apr. 2020, doi: 10.3390/bios10040040.


[4] A. F. Payne, A. M. Schell y M. E. Dawson, “Lapses in skin conductance responding across anatomical sites: Comparison of fingers, feet, forehead, and wrist,” Psychophysiology, vol. 53, no. 7, pp. 1084–1092, Jul. 2016, doi: 10.1111/psyp.12643.


[5] Storm H., Myre K., Rostrup M., Stokland O., Lien M. D., y Raeder J.,
“Skin conductance correlates with perioperative stress”, Acta Anaesthesiologica Scandinavica, vol. 46, no. 7, pp. 887–895, 2002.
https://doi.org/10.1034/j.1399-6576.2002.460721.x
