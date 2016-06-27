.. _elemento-inline-graphic:

<inline-graphic>
----------------

Aparece em:

  :ref:`elemento-product`
  :ref:`elemento-body`
  :ref:`elemento-p`
  :ref:`elemento-sec`
  ``th``
  ``td``

Ocorre:

  Zero ou mais vezes


Usado para identificar equações incluídas como imagem que estejam posicionadas
em linha, ou seja, ancoradas em um parágrafo.

O guia :ref:`sugestao-atribuicao-id` descreve o modo de composição do atributo
``@id``, caso este seja utilizado.

Exemplo:

.. code-block:: xml

    ...
    <p>We also used an enrichment factor for surface waters (EF<sub>w</sub>) based on the equation:<inline-graphic xlink:href="1234-5678-rctb-45-05-0110-e01.tif"/>. The EF<sub>s</sub> and EF<sub>w</sub> quantified the concentration of the element of interest (C<sub>i</sub>) in the sample, in relation to the (natural) geochemical background.</p>
    ...


.. {"reviewed_on": "20160626", "by": "gandhalf_thewhite@hotmail.com"}
