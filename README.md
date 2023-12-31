<h1 align=center>
   <img src="https://github.com/LuchoGonz22/AnimalClassifer_Model/blob/main/assets/animals.jpg" alt="Descripción de la imagen" width="750" height="400">
  
# Clasificador de Animales
   
  
## Descripción del proyecto:
Este proyecto se enfoca en la clasificación de animales utilizando un modelo de aprendizaje automático, específicamente el modelo SVC (Support Vector Classifier). Se ha creado un modelo de clasificación basado en un conjunto de características de los animales, como la presencia de pelo, plumas, la capacidad de poner huevos, entre otros. El modelo ha sido entrenado utilizando un conjunto de datos etiquetados y es capaz de predecir la clase a la que pertenece un animal dadas sus características.<br>
 <br>
Características:
* Clase 1: Mammal (Mamífero)
* Clase 2: Bird (Ave)
* Clase 3: Reptile (Reptil)
* Clase 4: Fish (Pez)
* Clase 5: Amphibian (Anfibio)
* Clase 6: Bug (Insecto)
* Clase 7: Invertebrate (Invertebrado)

## Ejemplos de uso (León): <br>
nuevo_animal = pd.DataFrame({ <br>
    'hair': [1], <br>
    'feathers': [0], <br>
    'eggs': [0], <br>
    'milk': [1], <br>
    'airborne': [0], <br>
    'aquatic': [1], <br>
    'predator': [1], <br>
    'toothed': [1], <br>
    'backbone': [1], <br>
    'breathes': [1], <br>
    'venomous': [0], <br>
    'fins': [0], <br>
    'legs': [4], <br>
    'tail': [1], <br>
    'domestic': [0], <br>
    'catsize': [1], <br>
})

En este caso, el modelo devolverá la clase 1, correspondiente a "Mammal" (Mamífero), lo cual indica que el animal tiene características similares a las de un león.
 <br>
   
## Contenido del proyecto:
   * datasets: Carpeta donde se encuentran los archivos CSV que se utilizaron.
   * model_classifier: Notebook donde se encuentra la implementación del modelo y demás.
<br>
<footer>Este pequeño proyecto sigue en desarrollo y en proceso de mejora.</footer>
