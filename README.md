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


# Resultados y análisis

## ¿A qué se debe que una inspiración profunda incremente la magnitud de la respuesta galvánica cutánea (GSR)?
Durante una inspiración profunda ocurren varios cambios fisiológicos que pueden estimular la actividad simpática. En primer lugar, el aumento del volumen pulmonar activa mecanorreceptores pulmonares y torácicos, los cuales envían señales aferentes al tronco encefálico. Estas señales modulan centros autonómicos que regulan tanto la respiración como la actividad simpática. Como consecuencia, puede producirse una activación transitoria del sistema simpático, lo que incrementa la actividad de las glándulas sudoríparas y, por tanto, la conductancia de la piel.


<img width="1499" height="654" alt="image" src="https://github.com/user-attachments/assets/b0bc7012-6511-4608-a1f2-b25fc5cca477" />


La anterior imagen muestra la evolución de la señal en el tiempo, durante los dos minutos que se tomó, en los segundos 25 y 100, se realizaron espiraciones súbitas y profundas, se observa como esto eleva el nivel de conductancia cutánea y al pasar el umbral de detección (señal en rojo) se emite la alerta de estrés, comprobando experimentalmente, lo que se comentó anteriormente.

## ¿Cuáles serían las ventajas y desventajas de utilizar la GSR como indicador de estrés?

El uso de la respuesta galvánica cutánea, como indicador de estrés tiene sus pros y contras. Por una parte y como se mencionó anteriormente diversos estudios logran correlacionar el estrés con un aumento en la componente SCR, también se ha visto que es un buen indicador del estrés cognitivo, incluo en condiciones de alta humedad [6]. Otra de sus principales ventajas es que es un método que no es invasivo, ni costoso, tampoco requiere de sensores complejos para su captura y su procesamiento es sencillo. Esto hace que su uso sea óptimo para monitoreo ambulatorio y dispositivos portables.

<img width="1163" height="683" alt="image" src="https://github.com/user-attachments/assets/0f3b0ca0-5022-466a-98bb-9d5acb494da5" />

El dispositivo de probó para monitoreo de estrés en tareas cotidianas, como se ve en la figura el primer minuto el sujeto estuvo sin hacer ninguna actividad, solo relajandose, segundos antes de iniciar la tarea estresante se activa la respuesta simpática, lo que se ve reflejado en la subida de la señaln que se mantiene por encima del umbral durante todo el desarrollo de la tarea.


Sin embargo, el uso de la GSR también presenta limitaciones importantes. En primer lugar, la señal GSR refleja principalmente el nivel general de activación fisiológica, pero no permite identificar de manera específica qué emoción o estado psicológico está produciendo dicha activación, puede ser causada tanto por dolor, excitación, miedo o estrés cognitivo. Otra de sus limitaciones es que la medición es sensible al ruido de tipo artefacto por el movimiento de los electrodos.
.

# Reflexion y viabilidad de la implementación en contextos reales


## Viabilidad para para monitoreo ambulatorio del estrés en oficinas, aulas universitarias y el hogar
El sistema desarrollado para la medición de la respuesta galvánica de la piel (GSR) mediante electrodos secos ubicados en la zona palmar se ve como una buena alternativa para el monitoreo ambulatorio del estrés en entornos cotidianos como oficinas, aulas universitarias y el hogar. Esto se debe a que la zona palmar posee una elevada densidad de glándulas sudoríparas ecrinas, cuya actividad está regulada por el sistema nervioso simpático, lo que produce cambios detectables en la conductancia de la piel ante estados de activación emocional o estrés.

El uso de electrodos secos permite una medición no invasiva y cómoda, adecuada para monitoreo continuo durante actividades diarias por un bajo costo, sobre todo cuando se compara con otros métodos convencionales para medir el estrés, como el ECG o la presión arterial que pueden resultar más incómodas, o métodos que miden cambios hormonales como la secreción de epinefrina o norepinefrina que no son adecuados para un monitoreo continuo. Es útil en ambientes como oficinas o aulas universitarias, el sistema puede registrar variaciones en la actividad electrodérmica asociadas con situaciones de presión cognitiva, carga de trabajo o ansiedad académica. Asimismo, en el hogar puede emplearse para evaluar patrones de estrés relacionados con el descanso, el trabajo remoto o actividades cotidianas.
## Viabilidad para emplear el sistema construido durante la práctica para detectar estrés neonatal en recién nacidos
Algunos estudios como los realizados por Kuderava y sus colegas, muestran que los neonatos ya tienen lo suficientemente desarrollado el sistema simpático como para poder detectar cambios significativos en los niveles de SCR, durante la aplicación de estímulos dolorosos como punzadas en los talones [7]. 
Sin embargo otros estudios en los que se ha medido la conductancia cutánea en infantes durante su estancia en cuidados intensivos, mostró una alta variabilidad en los valores, lo que dificulta la tarea de establecer umbrales claros, que den una buena estimación del nivel de estrés de los individuos [8]. 
Algunas otras cosas a considerar en cuanto al uso en neonatos, es que es posible que toquen constantemente el dispositivo o intenten retirarlo, teniendo esto en cuenta sería interesante evaluar si es más adecuado realizar la medición de conductancia cutánea, en otro sitio anatómico distinto a la palma de la mano,  como por ejemplo la planta del pie.

# Conclusiones
A partir de los objetivos planteados, se logró identificar y analizar las componentes estacionaria o tónica y la transitoria o fásica de la conductancia cutánea, lo que permitió comprender cómo la actividad electrodérmica refleja variaciones en la activación del sistema nervioso simpático. Asimismo, se desarrolló un dispositivo capaz de monitorear la respuesta galvánica de la piel (GSR) mediante la medición de cambios en la conductancia cutánea, demostrando que es viable implementar un dispositivo para su medición, y la posterior deducción del nivel de estrés del usuario, haciendo uso de umbrales adecuados. Se destaca que es importante la correcta sujeción de los electrodos para evitar al máximo la aparición de ruidos de tipo artefacto. Con base en los resultados obtenidos y en los fundamentos de la fisiología humana, se plantea que la GSR constituye un indicador útil del nivel de estrés, ya que las variaciones en la actividad de las glándulas sudoríparas, que son controladas por el sistema nervioso autónomo, se reflejan directamente en cambios medibles de la conductancia de la piel. Estos resultados evidencian que el monitoreo de la actividad electrodérmica puede emplearse como una herramienta relevante para la evaluación fisiológica del estrés, siempre y cuando se elija una zona anatómica adecuada.
# Referencias
[1] M. Benedek y C. Kaernbach, “A continuous measure of phasic electrodermal activity,” J. Neurosci. Methods, vol. 190, pp. 80–91, 2010. doi: 10.1016/j.jneumeth.2010.04.028.


[2] M. Benedek y C. Kaernbach, “Decomposition of skin conductance data by means of nonnegative deconvolution,” Psychophysiology, vol. 47, no. 4, pp. 647–658, 2010. doi: 10.1111/j.1469-8986.2009.00972.x.


[3]A. Zamkah, T. Hui, S. Andrews, N. Dey, F. Shi, and R. S. Sherratt, "Identification of Suitable Biomarkers for Stress and 
Emotion Detection for Future Personal Affective Wearable Sensors," Biosensors, vol. 10, no. 4, p. 40, Apr. 2020, doi: 10.3390/bios10040040.


[4] A. F. Payne, A. M. Schell y M. E. Dawson, “Lapses in skin conductance responding across anatomical sites: Comparison of fingers, feet, forehead, and wrist,” Psychophysiology, vol. 53, no. 7, pp. 1084–1092, Jul. 2016, doi: 10.1111/psyp.12643.


[5] Storm H., Myre K., Rostrup M., Stokland O., Lien M. D., y Raeder J.,
“Skin conductance correlates with perioperative stress”, Acta Anaesthesiologica Scandinavica, vol. 46, no. 7, pp. 887–895, 2002.
https://doi.org/10.1034/j.1399-6576.2002.460721.x

[6] H. F. Posada-Quintero y K. H. Chon, “Electrodermal activity is sensitive to cognitive stress under water,” Frontiers in Physiology, vol. 8, 2017.

[7] Z. Kuderava, M. Kozar, Z. Visnovcova, N. Ferencova, I. Tonhajzerova, L. Prsova y M. Zibolen, “Sympathetic nervous system activity and pain-related response indexed by electrodermal activity during the earliest postnatal life in healthy term neonates,” Physiological Research, vol. 72, no. 3, pp. 393–401, Jul. 2023, doi: 10.33549/physiolres.935061.

[8] D. Harrison, S. Boyce, P. Loughnan, P. Dargaville, H. Storm y L. Johnston, “Skin conductance as a measure of pain and stress in hospitalised infants,” Early Human Development, vol. 82, no. 9, pp. 603–608, Sep. 2006, doi: 10.1016/j.earlhumdev.2005.12.008.


