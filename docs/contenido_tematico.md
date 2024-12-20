<sub>Literal (c) del artículo 23 del Acuerdo 008 de 2008 del CSU</sub>

## Descripción de la asignatura mecánica de sólidos 1
En este curso, profundizaremos en la teoría de la elasticidad. Esta teoría es fundamental para comprender con suficiencia el método de los elementos finitos y para establecer bases sólidas en el manejo de los diversos programas de análisis estructural disponibles en el mercado. Estos programas no solo se aplican en ingeniería estructural, sino también en ingeniería geotécnica y de pavimentos.

Partiendo de los conocimientos previos sobre tensiones y deformaciones adquiridos en el curso de mecánica del medio continuo (mecánica tensorial), exploraremos en detalle las relaciones entre esfuerzos y deformaciones en materiales elásticos lineales. Además, abordaremos las ecuaciones fundamentales de la teoría de la elasticidad, las teorías de falla de materiales dúctiles y frágiles y culmina con el estudio de la torsión en barras de sección transversal no circular. El curso también incluye la formulación elástica en coordenadas cilíndricas. Esto último es especialmente relevante no solo en la mecánica estructural, sino también en la mecánica de suelos.

Se espera que al final del curso, el estudiante esté en capacidad de:
* Analizar y explicar como varían las tensiones y las deformaciones al interior de un sólido elásticos.
* Entender las diferentes suposiciones y limitaciones presentes en la teoría de la elasticidad.
* Interpretar los gráficos que arroja un programa de elementos finitos para el análisis estructural.
* Interpretar los diferentes criterios de falla presentes en los sólidos elásticos.
* Entender la deducción y rango de aplicación de ciertas formulaciones que se aplicarán más tarde en las líneas de mecánica de suelos y pavimentos.
* Entender la torsión de barras de sección no circular.

La materia se desarrollará mediante clases magistrales y prácticas mediante el uso de programas de elementos finitos.

## Contenido programático de mecánica de sólidos 1

### 0a. Repaso de diferentes temas de álgebra lineal y cálculo vectorial.
Cada estudiante debe repasar por cuenta propia los siguientes temas:
#### Repaso de álgebra lineal (teoría y ejercicios de aplicación)
* Cosenos directores
* Proyección de vectores
* Producto punto, producto cruz (con todas las propiedades que aparecen en el apéndice de las notas)
* Norma de un vector
* Matrices
* Determinantes
* Valores y vectores propios
* Espacios vectoriales
* Vectores linealmente dependientes/independientes
* Bases
* Planos y líneas rectas

#### Repaso de cálculo vectorial (teoría y ejercicios de aplicación)
* Gradiente
* Matriz jacobiana y jacobiano
* Divergencia
* Rotacional
* Diferenciales (se estudió en cálculo vectorial)
* Expansión en series de Taylor (univariada y multivariada)
* Regla de la cadena (se estudió en cálculo univariado y en cálculo vectorial)
* Campo vectorial (definición y ejemplos sencillos)

### 0b. Repaso breve de esfuerzos y deformaciones infinitesimales (estos temas se aprendieron en el curso *Mecánica Tensorial*)

#### Esfuerzos o tensiones
* Fuerzas másicas y fuerzas superficiales
* Esfuerzos cortantes y normales
* Tensor de tensiones
* Cambio de base

#### Desplazamientos y pequeñas deformaciones
* Desplazamientos
* Deformaciones longitudinales y angulares
* Especificación de la deformación en otras direcciones
* Rotación
* Deformaciones principales

#### Círculo de Mohr en 2D y 3D para los tensores de esfuerzos y deformaciones

#### Relación entre esfuerzos y deformaciones
* Materiales frágiles y materiales dúctiles: comportamiento elastoplástico, curva esfuerzo deformación.
* La ley de Hooke para materiales isótropos, anisótropos y ortótropos:
  * Los módulos de Young y Poisson.
  * Deformación de un sólido sometido a esfuerzos normales en las direcciones $x$, $y$ y $z$.
  * Deformación de un sólido sometido a esfuerzos tangenciales.
* Relación entre las direcciones principales asociadas a los esfuerzos y a las deformaciones para materiales isótropos
* Cambios de volumen y dilatación cúbica
* Módulo de expansión volumétrica o módulo de compresibilidad.

### 1. Relación entre esfuerzos y deformaciones
* Particularizaciones de tres a dos dimensiones: 
  * Tensión plana
  * Deformación plana
  * Relación entre los esfuerzos principales obtenidos en el análisis bidimensional y tridimensional
* Interpretación de los gráficos de colores de esfuerzos y deformaciones
* Modificación de la ley de Hooke para tener en cuenta los efectos térmicos en el caso de materiales isótropos y ortótropos

### 2. Ecuaciones diferenciales fundamentales de la teoría de la elasticidad
* Ecuaciones diferenciales de equilibrio
* Ecuaciones de compatibilidad en 2D y 3D en términos de deformaciones y esfuerzos (las ecuaciones de Saint-Venant y de  Mitchell-Beltrami)
* Condiciones de frontera
* Condiciones de equilibrio en la frontera en 2D y 3D
* Cálculo de los desplazamientos a partir de las deformaciones
* Función de tensión de Airy
* Ecuaciones diferenciales de Navier
* Unicidad de la solución
* Principio de superposición
* Principio de Saint-Venant

### 3. Criterios de falla para materiales dúctiles y frágiles
* Esfuerzos medios, desviadores y octaédricos
* El espacio de esfuerzos principales, la superficie de fluencia y la región elástica
* El sistema de coordenadas cilíndricas de Haigh-Westergaard
  * Simetría del espacio de esfuerzos principales
  * Comportamiento de los materiales isótropos en el rango plástico cuando se les somete a una condición de esfuerzos tridimensional
* Energía de dilatación y energía de distorsión
* Criterios de fluencia y superficies de plastificación en materiales dúctiles: von Mises, Tresca
* Criterios de rotura y superficies de falla en materiales frágiles: Rankine, Mohr-Coulomb, Drucker-Prager, Matsuoka-Nakai

### 4. Formulación en coordenadas polares y cilíndricas
* Los sistemas de coordenadas polares y cilíndricas
* El gradiente, el laplaciano, la divergencia y el rotacional en coordenadas cilíndricas
* Esfuerzos
* Deformaciones
* Ecuaciones diferenciales de equilibrio
* Desplazamiento y deformación en el caso de simetría axial
* Ley de Hooke
* Ecuaciones diferenciales de compatibilidad en coordenadas polares y cilíndricas
* Funciones de tensión de Airy y de Love
* Ecuaciones diferenciales de Navier
* Aplicaciones
  * Cálculo de los discos y cilindros de sección constante sujetos a un estado de tensiones axisimétrico
  * Concentración de esfuerzos alrededor de huecos circulares (el problema de Kirsch)
  * Concentración de esfuerzos alrededor de grietas
  * Concentración de esfuerzos en el ensayo brasileño
  * Aplicación en ingeniería de cimentaciones: problemas de Boussinesq, Flamant, Kelvin, Cerruti y Mindlin

### 5. Torsión
  * Hipótesis fundamentales de la teoría de Saint-Venant y Prandtl
  * Desplazamientos, deformaciones y esfuerzos en barras de sección circular y no circular
  * Función de tensión de Prandtl, analogía de la membrana
  * Alabeo
  * Cálculo de la rigidez a la torsión
  * Localización del centro de torsión
  * Uso de chaflanes en barras sometidas a torsión
  * Torsión de secciones de pared delgada
