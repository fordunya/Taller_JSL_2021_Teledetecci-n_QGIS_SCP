*********************************************************************************
Taller Jornadas SIG Libre 2021: Procesamiento de imágenes satélite con QGIS y SCP
*********************************************************************************
En este taller se muestra como procesar imágenes de satélite Landsat y/o Sentinel utilizando el software QGIS 3. A lo largo del taller se explorararán las mejores combinaciones de bandas para interpretar los usos del suelo.

Trabajaremos con el complemento SCP (semi-automatic classification plugin) mediante el cual podremos realizar clasificaciones supervisadas para obtener una capa de usos del suelos. Veremos como mejorar el resultado obtenido en la clasificación de usos del suelo mediante el uso de algunas técnicas como la introducción del índice NDVI o la reducción del efecto de las nubes.

Para la realización de este taller es necesario tener conocimientos básicos del programa QGIS en cualquiera de sus versiones.

CONTENIDOS DEL TALLER
=====================

- Principios básicos de teledetección

  + ¿Qué es la teledetección?
  + Principios de la teledetección
  + La radiación electromagnética
  + Sensores y bandas
  + Tipos de resolución
  + Misiones Landsat: Características
  + Misiones Sentinel: Características
  
- Portales de descarga y visualización de imágenes satélite
- El complemento SCP
- Descarga de imágenes Landsat con el complemento SCP
- Recortar imágen
- Combinar imágenes RGB
- Crear capa de usos del suelo mediante clasificación supervisada
- Corrección atmosférica de las imágenes. Dark Object Subtraction (DOS)
- Crear un mapa de temperaturas
- Clasificación supervisada
  + Clasificación de los usos del suelos a través de áreas de entrenamiento (ROIs) 
  + Explorar firmas espectrales
- Mejorar la clasificación supervisada
  + Uso de NDVI para mejorar el resultado de la clasificación supervisada 
  + Aplicación de máscaras para nubes


¿Qué es la teledetección?
=========================
  
La teledetección, o detección remota, es la adquisición de información a pequeña o gran escala de un objeto o fenómeno, ya sea usando instrumentos de grabación o instrumentos de escaneo en tiempo real inalámbricos o que no están en contacto directo con el objeto (como por ejemplo aviones, satélites, astronave, boyas o barcos). En la práctica, la teledetección consiste en recoger información a través de diferentes dispositivos de un objeto concreto o un área. Por ejemplo, la observación terrestre o los satélites meteorológicos, las boyas oceánicas y atmosféricas, las imágenes por resonancia magnética (MRI en inglés), la tomografía por emisión de positrones (PET en inglés), los rayos-X y las sondas espaciales son todos ejemplos de teledetección. Actualmente, el término se refiere de manera puntual al uso de tecnologías de sensores para adquisición de imágenes, incluyendo: instrumentos a bordo de satélites o aerotransportados, usos en electrofisiología, y difiere en otros campos relacionados con imágenes como por ejemplo en imagen médica.

Extraido de Wikipedia

Principios de la teledetección
==============================

