

# Detección de misoginia.

## Introducción 

Definiciones de la RAE.`

**Misoginia** :

    f. Aversión contra las mujeres.

**Machismo**

    m. Actitud de prepotencia de los varones respecto de las mujeres.

    m. Forma de discriminación sexista caracterizada por la prevalencia del varón. 


El discurso de odio hacia las mujeres representa una problemática social relevante. Debido a la relativia anonimidad de los entornos digitales, es en estos dónde el fenómeno se p resenta con singular virulencia. Entre el espectro de las expresiones de odio se encuentran, desde las burlas, hasta expolicitas incitaciónes a la violencia. La detección del contenido violento y/o misógino representa un desafío de moderación considerable por el simple hecho del volúmen de datos que nos inundan todos los días. Identificar, clasificar y catalogar la violencia/misogínia es sin duda el primer paso para afrontar la problemática generada por la misma. 

Existe una amplia literatura al respecto del uso de sistemas de parendizaje de máquina para identificar violencia en textos en inglés. Sin embargo, en el caso del español, existen ciertas limitantes que incrementan la dificultad del problema por lo que los esfuerzos que existen al respecto son limitados, comparados con el inglés. Un reto considerable es el hecho de que la naturaleza del lenguaje misógino se encuentra esparcida entre dos extremos, por un lado expresiones específicas y por otro, ímplicitas. Estas ultimas pueden observarse en formas que pueden ser implícitas, irónicas o contextuales. Por si fuera poco, el significado en español algunas veces es relativo al pais o dialecto donde se origión la expresión. No es lo mismo el español latinoamericano argentino contra el colombiano o ibérico, por poner un ejemplo. 

El presente trabajo tiene como fin proponer un sistema de clasificación automática basado en algoritmos de aprendizaje de máquina para identificar discurso de odio hacia las mujeres. Uno de los reqquerimientos es generar un sistema que balancee la precisión con la exhaustividad. Una moderación estricta, si no es precisa, puede generar censura injustificada, un sistema de clasificación muy conservador puede permitir la circulación de discurso violento. El objetivo deseado es producir un sistema que optimize la precisión sin sacrificar de sobremanera la capacidad de detección.

En ese contexto, este reporte de investigación aborda la construcción y evaluación de sistemas de clasificación binaria de misoginia para textos cortos en español. Se discutirán a detalle técnicas de procesamiento de lenguaje natural para el diseño de los mismos, usando diversas técnicas de limpieza, preprocesamiento y análisis con el objetivo final de determinar un sistema que tenga el mejor desempeño. Este ultimo siendo definido a partir de un sistema que optimize la precisión sin sacrificar la exhaustividad. 



