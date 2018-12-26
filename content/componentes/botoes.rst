===========================
Botões
===========================

Botões são usados para acionar uma ação. 
Através dos tipos, é possível identificar a importância de cada ação:

**Boas Práticas:**

- Seja direto no label do botão.
- Procure utilizar verbos nos labels dos botões.
- O ícone do botão deve mostrar claramente qual sua ação.
- Utilizar o verbo no infinitivo para ações no sistema. Ex: Salvar, Excluir, Editar, etc.
- Somente os botões mais importantes devem estar visíveis, os demais itens devem estar em menus/botões dropdown.


Tamanhos
===========

Os botões podem ter 3 tamanhos:
**Small**, **Default** e **Large**.


.. figure:: /_static/button-dimensoes.png
   :width: 500px
   :align: center
   :alt: dimensões dos botões

O espaçamento entre botões deve ser de 8px.



Hierarquia e Alinhamento
============================

Botões são alinhados dependendo do contexto:

- Para formulários e modais, alinhe os botões à direita e classifique por importância da direita para a esquerda, para suportar visualmente a navegação.
- Os botões de cancelar devem ser preferencialmente usados do tipo Subtle.
- Os botões de CTA não devem ser usados muito próximo ao de Primary. 


Variações
===========

.. raw:: html

    <table>
        <tbody>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-cta.png" style="max-width: 90px" alt"">
                </td>
                <td>Os botões <strong>Call to action</strong> são usados para chamar a atenção para uma ação principal no contexto da página. Só devem aparecer, preferencialmente, uma vez por tela. Nem toda tela requer um botão principal.</td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-primary.png" style="max-width: 90px" alt"">
                </td>
                <td>Botões <strong>Primary</strong> são a segunda ordem de prioridade dentro da hierarquia de importancia dos botões. São usados em ações impotantes da aplicação, mas que tenham um peso menor que dos botões call to action</td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-default.png" style="max-width: 90px" alt"">
                </td>
                <td><strong>Default</strong> é o botão padrão usado na maioria dos casos.</td>
            </tr>
            
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-outline.png" style="max-width: 90px" alt"">
                </td>
                <td>O botão <strong>Outline</strong> é usado em ações com um peso menos importante que ações que usam o botão primary, mas ainda assim importantes para aparecerem como uma ação em um botão default.</td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-subtle.png" style="max-width: 90px" alt"">
                </td>
                <td>O botão <strong>subtle</strong> é geralmente usado junto a um botão principal (geralmente primary ou default) para ações menos cruciais, como "Cancelar".</td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-disabled.png" style="max-width: 90px" alt"">
                </td>
                <td>Usado quando uma ação não está disponivel para o usuário. Use quando outra ação precise ser concluída antes que o botão seja utilizável, como alterar um valor de campo, selecionar uma opção em uma lista, ou aguardar uma resposta do sistema.</td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-dropdown.png" style="max-width: 99px" alt"">
                </td>
                <td>Aciona um menu/bloco com ações.</td>
            </tr>
        </tbody>
    </table>



Com icone
===========
Os icones devem ser usados, preferencialmente, ao lado esquerdo do label, podendo ser usado em qualquer tipo de botão, para chamar mais atenção ou ajudar a dar mais significado a uma ação.

.. figure:: /_static/button-icon.png
   :width: 580px
   :align: center
   :alt: dimensões dos botões com icone



Com loader
===========
Em alguns casos, ao clicar em um botão, como o "Salvar", o usuário precisa de um feedback pra saber o que está acontecendo.

.. figure:: /_static/button-loader.png
   :width: 215px
   :align: center
   :alt: exemplo de botão com loader
