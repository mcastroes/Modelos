**Modelos para clasificación de enfermedades pulmonares (COVID, Neumonía, Opacidad Pulmonar)**

En este repositorio encontramos los modelos correspondientes para clasificar si una radiografía de tórax presenta enfermedad o no, y si encuentran enfermedad, pasan a predecir cual 
de ellas es.

El procedimiento sigue la aplicación de los tres modelos: en primer lugar, un segmentador U-NET para predecir el tejido pulmonar en la radiografía y aislarlo, posteriormente, un
clasificador binario basado en una CNN para predecir si los pulmones están sanos o no, y finalmente, si se encuentra patología, un clasificador multiclase para predecir la enfermedad
(COVID, Neumonía u Opacidad Pulmonar)

El cuaderno público de Google Colaboratory de todo el proyecto es el siguiente: https://colab.research.google.com/drive/1_AbQnilvvoGV4AVaWeah_ypaZnLJv-7e?usp=sharing

En el repositorio también se encuentra la documentación teórica vinculada al proyecto.

*Cualquier persona puede utilizar los modelos ya subidos para realizar predicciones, pero debe solicitar un token especial al propietario del proyecto para poder entrenar nuevos modelos
y subirlos a este repositorio, se puede pedir al correo: **mcastroes.inf@upsa.es***
