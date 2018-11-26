===========================
Botões
===========================

---------------
Data: 27/11
---------------

Botões são usados para acionar uma ação. 
Através dos tipos, é possível identificar a importância de cada ação:

**Boas Práticas**

 - Seja direto no label do botão.
 - Procure utilizar verbos nos labels dos botões.
 - O ícone do botão deve mostrar claramente qual sua ação.
 - Utilizar o verbo no infinitivo para ações no sistema. Ex: Salvar, Excluir, Editar, etc.
 - Somente os botões mais importantes devem estar visíveis, os demais itens devem estar em menus/botões dropdown.




Hierarquia e Alinhamento
============================

Botões são alinhados dependendo do contexto:
 - Para formulários e modais, alinhe os botões à direita e classifique por importância da direita para a esquerda, para suportar visualmente a navegação.
 - As exceções incluem os botões de excluir que devem ficar do lado esquerdo do botão cancelar, para evitar que o usuário execute, de forma automática, uma ação que pode ser irreversível. 


Variações
===========

.. raw:: html


    <table class="color_palettes">
        <tbody>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-primary.png" style="max-width: 90px" alt"">
                </td>
                <td>
                    <strong>Primary: </strong>Para chamar a atenção para uma ação.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-default.png" style="max-width: 90px" alt"">
                </td>
                <td>
                    <strong>Default: </strong>Botão padrão usado na maioria dos casos.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-cta.png" style="max-width: 90px" alt"">
                </td>
                <td>
                <strong>Call to action: </strong>Deve aparecer somente uma vez por tela. É a ação mais importante do sistema, no contexto da tela.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-link.png" style="max-width: 90px" alt"">
                </td>
                <td>
                <strong>Link Button: </strong> 
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-subtle.png" style="max-width: 90px" alt"">
                </td>
                <td>
                    <strong>Subtle: </strong>geralmente usado para botões de cancelar. Deve ser usado para ações secundárias. 
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-outline.png" style="max-width: 90px" alt"">
                </td>
                <td>
                <strong>Outline: </strong> usado quando o botão não deve ter tanto destaque quanto o Primary.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-disabled.png" style="max-width: 90px" alt"">
                </td>
                <td>
                <strong>Disabilitado: </strong> quando o botao está desabilidado.
                </td>
            </tr>
        </tbody>
    </table>



Tamanhos
===========

Os botões podem ter 3 tamanhos

 - Small.
 - Default.
 - Large.



Com icone
===========
Os icones devem ser udados ao lado esquerdo do label, podendo ser usado em qualquer tipo de botão, para chamar mais atenção ou ajudar a dar mais significado a uma ação.




Com loader
===========
Em alguns casos, ao clicar em um botão, como o "Salvar", o usuário precisa de um feedback pra saber o que está acontecendo.