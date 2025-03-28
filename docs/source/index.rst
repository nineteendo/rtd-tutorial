Productionlist example
======================

Code block:

.. code-block:: none

    array ::=  '[' (
                whitespace
                | ( value ++ ( ',' | whitespace - '' ) ) ( ',' whitespace )?
                ) ']'

Productionlist:

.. container:: highlight

    .. productionlist:: jsonyx-grammar
         array: '[' (
              : whitespace
              : | ( value ++ ( ',' | whitespace - '' ) ) ( ',' whitespace )?
              : ) ']'