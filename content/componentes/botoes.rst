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
Small, default e large.


.. figure:: /_static/button-dimensoes.png
   :width: 500px
   :align: center
   :alt: dimensões dos botões

O espaçamento entre botões deve ser de 8px.



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
                    <strong>Primary: </strong>Botões primários são usados em casos onde precisam ser destacados mas não são ações prioritárias.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-default.png" style="max-width: 90px" alt"">
                </td>
                <td>
                    <strong>Default: </strong>Botões de classe default são a terceira ordem de prioridade dentro da hierarquia de cores. Botão padrão usado na maioria dos casos.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-cta.png" style="max-width: 90px" alt"">
                </td>
                <td>
                <strong>Call to action: </strong>Os botões call-to-action são usados em caso de prioridade máxima dentro de uma determinada interface. Deve aparecer somente uma vez por tela. É a ação mais importante do sistema, no contexto da tela atual.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-danger.png" style="max-width: 90px" alt"">
                </td>
                <td>
                <strong>Danger: </strong>Botões com cores de alerta deverão ser usados para casos onde a ação represente risco irreversível de perda de um determinado conteúdo ou configuração.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-link.png" style="max-width: 90px" alt"">
                </td>
                <td>
                <strong>Link Button: </strong> São usados sempre que o destaque dos botões comuns não sejam necessários, como por exemplo em ações secundárias.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-subtle.png" style="max-width: 90px" alt"">
                </td>
                <td>
                    <strong>Subtle: </strong> São usados sempre que o destaque dos botões comuns não sejam necessários, como por exemplo em ações secundárias. Um exemplo comum de aplicação de botão link é o botão Cancelar, normalmente encontrado em caixas de diálogo / modais. 
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-outline.png" style="max-width: 90px" alt"">
                </td>
                <td>
                <strong>Outline: </strong> Usado quando o botão não deve ter tanto destaque quanto o Primary.
                </td>
            </tr>
            <tr>
                <td style="padding-right: 100px">
                    <img src="../_static/button-disabled.png" style="max-width: 90px" alt"">
                </td>
                <td>
                <strong>Disabilitado: </strong> Quando o botao está desabilidado.
                </td>
            </tr>
        </tbody>
    </table>



Com icone
===========
Os icones devem ser udados ao lado esquerdo do label, podendo ser usado em qualquer tipo de botão, para chamar mais atenção ou ajudar a dar mais significado a uma ação.

.. figure:: /_static/button-icon.png
   :width: 580px
   :align: center
   :alt: dimensões dos botões com icone



Com loader
===========
Em alguns casos, ao clicar em um botão, como o "Salvar", o usuário precisa de um feedback pra saber o que está acontecendo.
O conteudo do botão é subistituido pelo icone de loader.

.. figure:: /_static/button-loader.png
   :width: 215px
   :align: center
   :alt: exemplo de botão com loader
