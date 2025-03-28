Productionlist example
======================

.. productionlist:: jsonyx-grammar
   array:  '[' (
        :      `whitespace`
        :      | ( `value` ++ ( ',' | `whitespace` - '' ) ) ( ',' `whitespace` )?
        :  ) ']'