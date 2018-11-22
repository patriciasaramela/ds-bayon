===========================
Fonts
===========================

.. figure:: /_static/visual.png
   :width: 500px
   :align: center
   :alt: ilustração de visual design

A ‘Segoe UI’ é a font family usada nas aplicações web. Segundo a Microsoft, “Ela foi projetada para 
manter a legibilidade ideal em todos os tamanhos e densidades de pixel, e oferece uma estética limpa, 
leve e aberta que complementa o conteúdo do sistema.” Caso a Segoe Ui não esteja disponível no 
dispositivo usado, a font ‘Selawik’ será usada.

O sistema de fonts é composto pelos aspectos a seguir:


Font family
------------

Temos duas alternativas para família de fonts do design system, a primária é a principal e a alternativa quando a primaria não estiver disponível.


.. figure:: /_static/tipografia.png
   :width: 500px
   :align: center
   :alt: exemplo das fonts usadas nas aplicações


Escala da Font e altura da linha
----------------------------------

Escala de fonte refere-se a uma série de fontes com tamanhos diferentes. Altura da linha pode ser entendida como uma caixa invisível envolvida fora da fonte.

.. figure:: /_static/tipografia2.png
   :width: 500px
   :align: center
   :alt: exemplo de altura da linha

Cores de font
---------------
O texto será difícil de ler se estiver muito próximo da cor de fundo. Seguimos o padrão WCAG, que mantém um nível AAA de taxa de contraste, ou seja, 7: 1 ou mais entre texto do corpo, título e cor de fundo.

.. raw:: html

    <style type="text/css">
        .color_palettes{
            width: 400px;
            margin: 0 auto!important;
        }
        .color_palettes td:last-child{
            width: 120px;
        }
    </style>
    <table class="color_palettes">
        <tbody>
            <tr style="background-color: #333333; color: #FFFFFF" >
            <td>Texto primário</td>
            <td>#333333</td>
            </tr>
            <tr style="background-color: #4D4D4D; color: #FFFFFF" >
            <td>Texto secundário</td>
            <td>#4D4D4D</td>
            </tr>
            <tr style="background-color: #808080; color: #FFFFFF" >
            <td>Texto terciário</td>
            <td>#808080</td>
            </tr>
            <tr style="background-color: #A6A6A6; color: #FFFFFF" >
            <td>Bordas</td>
            <td>#A6A6A6</td>
            </tr>
            <tr style="background-color: #c5c5c5" >
            <td>Disable</td>
            <td>#C5C5C5</td>
            </tr>
            <tr style="background-color: #D8D8D8" >
            <td>Dividers</td>
            <td>#D8D8D8</td>
            </tr>
            <tr style="background-color: #EAEAEA" >
            <td>Background</td>
            <td>#EAEAEA</td>
            </tr>
        </tbody>
    </table>