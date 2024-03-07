1- en qué consiste BOW, bag of words, que inconvenientes tiene:

Consiste en representar un texto mediante un conjunto de palabras, ignorando su gramática y su orden, 
pero manteniendo su frecuencia.no captura la semántica ni el significado del texto, ya que ignora el contexto 
y el orden de las palabras.

    1- Pérdida de información sobre el orden de las palabras
    2- No captura la semántica
    3- Sensibilidad al vocabulario
    4- No considera la relación semántica entre palabras

2- En qué consisten la técnica de Bag of n-grams, cuales son sus desventajas:

En lugar de simplemente contar las ocurrencias de palabras individuales en un texto,
la Bolsa de n-gramas considera secuencias contiguas de palabras de longitud n, conocidas como n-gramas.
Esta técnica es útil porque captura más información sobre la estructura y el contexto del texto que la Bolsa de Palabras tradicional.
Al incluir secuencias de palabras, podemos preservar algunas relaciones sintácticas y semánticas entre ellas.

1. Aumento del tamaño del vocabulario
2. Esparsidad: generar matrices de características muy dispersas, especialmente en conjuntos de datos grandes.
Esto puede dificultar el análisis y el modelado de datos,
3. Pérdida de generalización
4. Incremento del costo computacional
5. Ignora el contexto más amplio

3- TF-IDF:

TF: Mide la frecuencia con la que aparece una palabra en un documente.
IDF:  Mide la importancia de una palabra en toda la colección de documentos.
El resultado final es un valor numérico que representa la importancia de una palabra en un documento en relación con toda la colección de documentos

Porque es mejor?

1- Considera la importancia relativa.
2- Reduce las palabras comunes
3- Mira la importancia del contexto.

