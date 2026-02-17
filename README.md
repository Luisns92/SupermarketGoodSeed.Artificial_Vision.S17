# Supermarket Good Seed, Visión artificial

📖 Resúmen:  
 Entrenar un modelo capaz de identificar por medio de una imagen si el usuario es mayor de edad.  
.  
.  
.   
🎯 Objetivo:  
 Entrenar un modelo que pueda identificar signos de envejecimiento para poder predecir su edad.

❌ Problema:  
 La cadena de supermercados cuenta con máquinas de auto venta pero requiere comprobar la mayoría de edad para poder venderle artículos solo para adultos como la venta de alcohol.

✅ Solución:  
 Entrenar modelo con una amplia galería de imagenes faciales y su edad para poder predecir los nuevos usuarios.

🔢 Metodologia:  
  1. Análisis de los datos.
  2. Realización del análisis exploratorio de datos.
  3. Revisar la calidad de las imágenes.
  4. Entrenar modelo de redes neuronales (ResNet50) con la librería TensorFlow.
  5. Concluir los hallazgos.  

📊 Conclusiones:  
 El modelo entrenado tiene un error promedio de 7.16 años, lo cual significa la necesidad de cambiar el rumbo del proyecto como un modelo de clasificación y no de regresión, para evitar incumplir las leyes y no vender alcohol a menores.
