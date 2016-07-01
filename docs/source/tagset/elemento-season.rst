.. _elemento-season:

<season>
^^^^^^^^

Aparece em:

  :ref:`elemento-pub-date`
  :ref:`elemento-product`
  :ref:`elemento-element-citation`

Ocorre:

  Zero ou uma vez


Este elemento pode ser encontrado em :ref:`elemento-front` (ver :ref:`elemento-pub-date` e :ref:`elemento-product`) para identificação de intervalo de meses do ano ou em :ref:`elemento-back`, representando informações das estações do ano em um referência.

Exemplos:

1. como estações do ano:

.. code-block:: xml

    ...
    <back>
        ...
        <ref-list>
            <ref>
                ...
                <season>Outono</season>
                ...
            </ref>
        </ref-list>
        ...
    </back>

2. como intervalo de meses:

.. code-block:: xml

    ...
    <front>
        ...
        <article-meta>
            ...
            <pub-date pub-type="epub">
                <season>Nov-Dec</season>
                <year>2013</year>
            </pub-date>
            ...
        </article-meta>
        ...
    </front>
    ...


.. note:: Para abreviatura dos meses em um intervalo, deve-se utilizar a abreviatura dos mesmos em inglês, com 3 caracteres, separados por hífen. As abreviaturas são: ``Jan``, ``Feb``, ``Mar``, ``Apr``, ``May``, ``Jun``, ``Jul``, ``Aug``, ``Sep``, ``Oct``, ``Nov`` e ``Dec``.


.. {"reviewed_on": "20160628", "by": "gandhalf_thewhite@hotmail.com"}
