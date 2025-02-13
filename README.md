# U1A4.-Metodos-de-Ordenamiento
El código presentado está compuesto por tres partes principales: ordenamiento de listas (Burbuja y Quicksort), medición del tiempo de ejecución y organización en Jupyter Notebook. Cada uno de estos elementos cumple una función clave en el análisis de algoritmos y optimización del software.
1. Ordenamiento de Listas

Se han implementado dos métodos de ordenamiento:

    Método Burbuja:
        Recorre la lista varias veces, comparando elementos adyacentes e intercambiándolos si están en el orden incorrecto.
        Su complejidad temporal es O(n2)O(n2), lo que lo hace ineficiente para grandes conjuntos de datos.
        Incluye impresiones para visualizar cada comparación e intercambio de valores.

    Quicksort:
        Se basa en la estrategia de divide y vencerás, seleccionando un pivote para dividir la lista en dos subconjuntos: menores y mayores.
        Se ordenan recursivamente los subconjuntos hasta obtener la lista ordenada.
        Su complejidad promedio es O(nlog⁡n)O(nlogn), siendo más eficiente que Burbuja.

Ambos métodos se prueban con la misma lista desordenada y muestran el resultado antes y después del ordenamiento.
2. Medición del Tiempo de Ejecución

Para evaluar el rendimiento de una función, se utiliza el módulo time. Se define una función que realiza una operación sencilla (sumar los primeros 1,000,000 de números) y se mide su tiempo de ejecución con:

    time.time() antes y después de la ejecución de la función.
    Se imprime la diferencia entre ambos tiempos para conocer la duración del proceso.

Esta técnica también puede aplicarse a los algoritmos de ordenamiento para comparar su eficiencia en diferentes tamaños de listas.
3. Implementación en Jupyter Notebook

El código está diseñado para ejecutarse en Jupyter Notebook, lo que permite:

    Documentar cada paso con texto explicativo en Markdown.
    Ejecutar secciones del código de manera independiente.
    Visualizar los resultados y modificar parámetros sin necesidad de reiniciar todo el entorno.
