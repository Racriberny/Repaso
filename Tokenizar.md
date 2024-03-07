1- ¿Que significa tokenizar?

La tokenización es el proceso de dividir una cadena de texto en unidades más pequeñas llamadas "tokens". 
Estos tokens pueden ser palabras individuales, números, símbolos o cualquier otra unidad significativa, dependiendo de la naturaleza del análisis o 
del problema que estamos tratando. Este término es comúnmente utilizado en el procesamiento del lenguaje natural (NLP) para referirse al proceso de dividir el texto en "tokens" 
para su análisis y procesamiento, como ocurre en casos de clasificación de texto, traducción automática, análisis de sentimientos, entre otros. 
Cómo debe hacerse la tokenización depende de las necesidades exactas de la aplicación y del idioma que estemos procesando.

2- Enumera algunos métodos interesantes de la librería spacy:

nlp = spacy.load('en_core_web_sm'): Esto es para la carga de datos de un modelo descargado anteriormente.
print("Texto:", token.text)
    print("Índice en el Doc:", token.i)
    print("Índice del primer carácter:", token.idx)
    print("Lema:", token.lemma_)
    print("Etiqueta POS:", token.pos_): Para ver si es preposicion...
    print("Etiqueta de dependencia:", token.dep_)
    print("Forma:", token.shape_)
    print("¿Es alfabético?:", token.is_alpha)
    print("¿Es un dígito?:", token.is_digit)
    print("¿Es un signo de puntuación?:", token.is_punct)
    print("¿Es un espacio en blanco?:", token.is_space)
    print("¿Es una palabra de parada?:", token.is_stop)
    print("Tipo de entidad:", token.ent_type_)
    print("¿Tiene vector?:", token.has_vector)
token.is_space: Para ver si tiene un espacio
  ent.label_ == "EMAIL":- Para ver si es un Email.


['Any',
 'Config',
 'Dict',
 'Errors',
 'Iterable',
 'Language',
 'Path',
 'Union',
 'Vocab',
 '__builtins__',
 '__cached__',
 '__doc__',
 '__file__',
 '__loader__',
 '__name__',
 '__package__',
 '__path__',
 '__spec__',
 '__version__',
 'about',
 'attrs',
 'blank',
 'cli',
 'compat',
 'displacy',
 'errors',
 'explain',
 'git_info',
 'glossary',
 'info',
 'kb',
 'lang',
 'language',
 'lexeme',
 'load',
 'logger',
 'lookups',
 'matcher',
 'ml',
 'morphology',
 'parts_of_speech',
 'pipe_analysis',
 'pipeline',
 'prefer_gpu',
 'registry',
 'require_cpu',
 'require_gpu',
 'schemas',
 'scorer',
 'setup_default_warnings',
 'strings',
 'symbols',
 'sys',
 'tokenizer',
 'tokens',
 'training',
 'ty',
 'util']
3 - ¿qué tipo de problemas podemos resolver al tokenizar un documento?

La tokenización es el proceso de dividir un documento de texto en unidades más pequeñas llamadas tokens, que pueden ser palabras individuales, números, símbolos u otras unidades significativas.
Problemas que aborda la tokenización:

    1- Segmentación de texto
    2- Preprocesamiento de texto
    3- Análisis sintáctico y semántico
    4- Modelado de lenguaje
    5- Búsqueda de información
    6- Clasificación de texto

4- Ventajas sobre las expresiones regulares:

Ventajas de la tokenización sobre expresiones regulares:

1 - Manejo de Contexto Lingüístico
2 - Robustez ante Variaciones
3 - Identificación de Entidades
4 - Facilidad de Uso
5 - Integración con Otras Tareas de NLP

