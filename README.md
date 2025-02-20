Este proyecto genera una lista de 100,000 usuarios y compara los tiempos de búsqueda lineal y binaria.
Cada usuario tiene un ID único, un nombre seleccionado aleatoriamente de una lista definida anteriormente, y una edad generada aleatoriamente entre 18 y 80 años.
Los usuarios se almacenan en una lista.
para la busqueda lineal, Recorre la lista usuario por usuario hasta encontrar el ID deseado o llegar al final de la lista.
Es sencilla, pero poco eficiente en listas grandes.
para la lista binaria, se requiere que la lista esté ordenada por ID.
Divide la lista en mitades repetidamente para encontrar el ID deseado.
Es mucho más eficiente en listas grandes.
par los tiempo, Se mide el tiempo que toma cada algoritmo para encontrar el usuario con el ID proporcionado.
El programa genera 100,000 usuarios con IDs únicos y luego ordena la lista por ID.
Solicita al usuario que ingrese un ID para buscar.
Realiza la búsqueda utilizando los dos algoritmos y muestra los tiempos de ejecución de cada uno.
Si el usuario es encontrado, se muestra su información; de lo contrario, se indica que no existe.
Resultados esperados
El programa demuestra que la búsqueda binaria es más rápida que la búsqueda lineal, especialmente en listas grandes, porque reduce en gran numero, la cantidad de elementos que necesita revisar.

Cómo Usarlo:
1. Ejecuta el archivo `tarea.py` en Python

2. link de video: https://drive.google.com/file/d/1sPs9UCy8HCieFANM0lUAy5ELPW4ijODb/view?usp=sharing