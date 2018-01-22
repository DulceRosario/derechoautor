
Lineamientos de programación 
============================================
Adicionalmente a estos lineamientos de programación, les sugerimos revisar a conciencia los siguientes `principios
de programacion <https://en.wikipedia.org/wiki/Category:Programming_principles>`_.

1.- Elegir una de las convenciones de nomenclatura para la definir los identificadore

    Estilo Pascal (PascalCase)
        **Variables y funciones**. La primera letra debe ir en *minúscula* y, en nombres de variables compuestos, la primer letra de cada
        palabra adicional debe ir con mayúscula. Ejemplos (se sugiere siempre usar nombres en inglés): sigularMatrix, joinsArrays, plotResults,
        associateProfessor, blackCar, etc. 

        **Clases**. La primera letra debe ir en *mayúscula* ir con y, en nombres de clases compuestas, la primer letra de cada
        palabra adicional debe ir con mayúscula. Ejemplos (se sugiere siempre usar nombres en inglés): ForecastModel, Hurricane,
        Employee, etc. 

2.- Mantener una indentación uniforme. Para unificar la identación en el código generado en el Centro de Ciencias de la Atmósfera se sugiere:

    1.- Utilizar espacios en vez de tabuladores (tabs). Cada IDE se puede configurar para que al usar tabuladores se inserten espacios  de forma automática.

    2.- Utilizar una identación a 4 espacios en todos los lenguages de programación. 

3.- Comentar funciones, clases y subsecciones del código. 

    Ejemplos de comentarios en Python `link <https://www.python.org/dev/peps/pep-0257/>`_ :

* Funciones

.. code-block:: python

    def function(a,b):
        ""Here it should be a summary of the function

        Args:
            a (int): The first parameter.        
            b (str): The second parameter.    
        
        Returns:        
            bool: The return value. True for success, False otherwise.
        """

* Secciones

.. code-block:: python

   # Computes the convolution between A and B
   for rows in A:
       ...


Ejemplos de comentarios en Matlab `link <https://la.mathworks.com/help/matlab/matlab_prog/add-help-for-your-program.html>`_ :

* Funciones

.. code-block:: matlab

    function c = addme(a,b)
    % ADDME  Add two values together.
    %   C = ADDME(A) adds A to itself.
    %   C = ADDME(A,B) adds A and B together.
    %%   See al so SUM, PLUS.

4.- Evitar los anidamientos excesivos

5.- Mantener nombres consistentes. Es mejor nombres largos que expliquen la variable que sólo letras que no dan
información de lo que contiene la variable. 

6.- Evitar siempre que sea posible el uso de variables globales 
