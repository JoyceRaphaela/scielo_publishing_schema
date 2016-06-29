.. _elemento-etal:

<etal>
^^^^^^

Aparece em:

  :ref:`elemento-person-group`
  :ref:`elemento-product`

Ocorre:

  Zero ou uma vez


Elemento utilizado quando há mais de três autores, sendo que somente se indica o primeiro, acrescentando-se a expressão ``et al.``, que significa "entre outros".

Esta informação aparece primordialmente em referências.

.. note:: Quando a informação aparecer no texto da referência, não é necessário incluir o texto ``"et al."`` no elemento ``<etal>``, bastando inserí-lo na forma ``<etal/>``.


Exemplo:

.. code-block:: xml

    ...
    <ref>
        <element-citation publication-type="book">
            <person-group person-group-type="author">
                <name>
                    <surname>Borba</surname>
                    <given-names>Quincas</given-names>
                </name>
                <etal/>
                ...
            </person-group>
            ...
        </element-citation>
        ...
    </ref>
    ...


.. {"reviewed_on": "20160624", "by": "gandhalf_thewhite@hotmail.com"}
