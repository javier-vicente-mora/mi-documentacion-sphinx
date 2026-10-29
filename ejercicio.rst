==================================
Mi Práctica de reStructuredText
==================================

Sección 1: Introducción a la documentación
------------------------------------------

Este es el primer párrafo de nuestra página de prueba creada en reStructuredText. La generación estática de sitios web nos permite redactar contenidos de forma limpia utilizando lenguajes de marcado ligero sin preocuparnos por el diseño HTML final.

El segundo párrafo nos ayuda a comprobar que la estructura de bloques de texto se procesa de manera fluida y ordenada en el motor de renderizado de Sphinx.

Sección 2: Características y Enlaces
------------------------------------

En esta tercera sección exploraremos el uso de formatos y conexiones externas. Es muy importante destacar que el uso de **negritas** y otros elementos realzan la legibilidad del texto técnico.

Si quieres profundizar en la sintaxis oficial, puedes consultar la `documentación oficial de reST <https://www.sphinx-doc.org/>`_ o visitar la web de la comunidad en `Python Ecuador <https://www.python.ec/>`_.

Sección 3: Listas y Cierre
--------------------------

Para organizar la información de manera secuencial, reStructuredText permite utilizar listas numeradas de forma muy sencilla:

1. Instalar Python y verificar el gestor de paquetes PIP en la terminal.
2. Descargar e inicializar Sphinx mediante el comando de configuración rápida.
3. Escribir los archivos de contenido utilizando la extensión .rst.
4. Compilar el sitio web ejecutando la instrucción correspondiente.

Este quinto y último párrafo sirve para cerrar el documento de prácticas comprobando que la estructura cumple con todos los apartados solicitados en el ejercicio.


Sección 4: Uso de Directivas y Roles
------------------------------------

A continuación vamos a probar la inserción de contenido multimedia y avisos especiales mediante directivas de Sphinx.

.. note::
   **Nota informativa:** Esta es una directiva de tipo nota (`.. note::`) que resalta información útil para el usuario que lee la documentación técnica.

.. warning::
   **¡Precaución!:** Las directivas de advertencia (`.. warning::`) sirven para alertar sobre posibles errores críticos o consideraciones de seguridad importantes.

También podemos insertar imágenes directamente desde una URL externa utilizando la directiva correspondiente:

.. image:: https://www.python.org/static/community_logos/python-logo-master-v3-TM.png
   :alt: Logotipo oficial de Python
   :align: center
   :width: 300px

Por último, para indicar atajos en el teclado dentro de una frase, utilizamos el rol de teclado: pulsa :kbd:`Ctrl+S` para guardar los cambios o :kbd:`Ctrl+C` para cancelar un proceso en la terminal.