.. _elemento-institution:

<institution>
^^^^^^^^^^^^^

Aparece em:

  :ref:`elemento-aff`

Atributos obrigatórios:

  1. ``@content-type``

Ocorre:

  Zero ou mais vezes


Neste elemento identifica-se a instituição do autor, a qual pode ser dividida em
até três níveis, definidos pelo atributo obrigatório ``@content-type``, cujos
valores possíveis são:

+------------+--------------------------------------------------------------------+
| Valor      | Descrição                                                          |
+============+====================================================================+
| orgname    | Representa a instituição de primeiro nível hierárquico mencionado  |
|            | na afiliação.                                                      |
+------------+--------------------------------------------------------------------+
| orgdiv1    | Representa o segundo nível hierárquico da instituição mencionada   |
|            | em orgname.                                                        |
+------------+--------------------------------------------------------------------+
| orgdiv2    | Representa o terceiro nível hierárquico da instituição mencionada  |
|            | em orgname.                                                        |
+------------+--------------------------------------------------------------------+
| normalized | Nome da instituição na forma normalizada pela SciELO.              |
+------------+--------------------------------------------------------------------+
| original   | Identificar a afiliação completa conforme consta no texto do artigo|
+------------+--------------------------------------------------------------------+


.. note:: Divisões abaixo do terceiro nível hierárquico da institução são
          identificadas somente no elemento ``<institution content-type="original">``.


.. code-block:: xml

    ...
    <aff id="aff01">
        <institution content-type="orgname">
            Universidade de São Paulo
        </institution>
        <institution content-type="orgdiv1">
            Faculdade de Filosofia, Letras e Ciências Humanas
        </institution>
        <institution content-type="orgdiv2">
            Departamento de Vernáculos
        </institution>
        ...
    </aff>
    ...


Deve-se especificar a afiliação completa como aparece no documento original.

.. code-block:: xml

     <institution content-type="original">Técnica de Cardiopneumologia. Unidade de
     Fisiopatologia Respiratória, Serviço de Pneumologia, Centro Hospitalar Lisboa
     Norte, Lisboa, Portugal. mara@scielo.org</institution>



.. {"reviewed_on": "20160626", "by": "gandhalf_thewhite@hotmail.com"}
