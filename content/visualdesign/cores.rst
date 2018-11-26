===========================
Cores
===========================

.. figure:: /_static/visual.png
   :width: 500px
   :align: center
   :alt: ilustração de visual design



Cores da Marca
---------------

É usada na branding da aplicação como header e botões, afim de criar uma identificação do usuário com elementos visuais intuitivos e incorporar características do produto.

A o valor Hex da cor principal usada no header é #0063b1, cor normal do botão é #0078d7 sendo o hover #0063b1, quando a necessidade de um botão CTA (Call To Action) utiliza-se #FFC070 e hover #FFAF4A.

Para botões confira a forma correta de aplicar na seção botões.

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
        <tr style="background-color: #0063B1; color: #FFFFFF" >
            <td>themeDark</td>
            <td>#0063B1</td>
        </tr>
        <tr style="background-color: #0078D7; color: #FFFFFF" >
            <td>themePrimary</td>
            <td>#0078D7</td>
        </tr>
        <tr style="background-color: #CBE3F6" >
            <td>themeLight</td>
            <td>#CBE3F6</td>
        </tr>
        </tbody>
    </table>
    <br />
    <table class="color_palettes">
        <tbody>
        <tr style="background-color: #FFAF4A" >
            <td>orangeDark</td>
            <td>#FFAF4A</td>
        </tr>
        <tr style="background-color: #FFC070" >
            <td>orange</td>
            <td>#FFC070</td>
        </tr>
        </tbody>
    </table>

Neutra
---------------
Essas cores são utilizadas em boa parte da interface, temos a aplicação em textos, bordas, backgrounds, linhas divisórias, entre outros.
Precisamos seguir o padrão WCAG 2.0 (Web Content Accessibility Guidelines) e o princípio de contraste da Gestalt para aplicação entre fundo claro e escuro.

.. raw:: html


    <table class="color_palettes">
        <tbody>
            <tr style="background-color: #333333; color: #FFFFFF" >
            <td>neutralPrimary</td>
            <td>#333333</td>
            </tr>
            <tr style="background-color: #4D4D4D; color: #FFFFFF" >
            <td>neutralSecondary</td>
            <td>#4D4D4D</td>
            </tr>
            <tr style="background-color: #808080; color: #FFFFFF" >
            <td>neutralSecondaryAlt</td>
            <td>#808080</td>
            </tr>
            <tr style="background-color: #A6A6A6; color: #FFFFFF" >
            <td>neutralTertiary</td>
            <td>#A6A6A6</td>
            </tr>
            <tr style="background-color: #c5c5c5" >
            <td>defaultDark</td>
            <td>#C5C5C5</td>
            </tr>
            <tr style="background-color: #D8D8D8" >
            <td>neutralTertiaryAlt</td>
            <td>#D8D8D8</td>
            </tr>
            <tr style="background-color: #EAEAEA" >
            <td>neutralQuaternary</td>
            <td>#EAEAEA</td>
            </tr>
            <tr style="background-color: #F4F4F4" >
            <td>neutralLight</td>
            <td>#F4F4F4</td>
            </tr>
            <tr style="background-color: #F9F9F9" >
            <td>neutralLight</td>
            <td>#F9F9F9</td>
            </tr>
            <tr
            style={{
                background-color: #FFFFFF",
                border: "1px solid #F4F4F4"
            
            >
            <td>white</td>
            <td>#FFFFFF</td>
            </tr>
        </tbody>
    </table>

Funcional
---------------
Utilizada para mensagens de status, alerta, sucesso e erro. A escolha da cor está em conformidade com a compreensão básica do usuário. Podemos fazer uma analogia com o semáforo, aonde temos a cor amarela para atenção, vermelha parada e verde pra seguir.  

.. raw:: html


    <table class="color_palettes">
        <tbody>
        <tr style="background-color: #856000; color: #FFFFFF" >
            <td>warningDark (textos)</td>
            <td>#856000</td>
        </tr>
        <tr style="background-color: #FFB900; color: #FFFFFF" >
            <td>warning</td>
            <td>#FFB900</td>
        </tr>
        <tr style="background-color: #FFF1CC" >
            <td>warningBackground</td>
            <td>#FFF1CC</td>
        </tr>
        </tbody>
    </table>
    <br />
    <table class="color_palettes">
        <tbody>
        <tr style="background-color: #95020B; color: #FFFFFF" >
            <td>dangerDark (textos)</td>
            <td>#95020B</td>
        </tr>
        <tr style="background-color: #C40E1E; color: #FFFFFF" >
            <td>dangerHover</td>
            <td>#C40E1E</td>
        </tr>
        <tr style="background-color: #E81123; color: #FFFFFF" >
            <td>danger</td>
            <td>#E81123</td>
        </tr>
        <tr style="background-color: #FACFD3" >
            <td>dangerBackground</td>
            <td>#FACFD3</td>
        </tr>
        </tbody>
    </table>
    <br />
    <table class="color_palettes">
        <tbody>
        <tr style="background-color: #007133; color: #FFFFFF" >
            <td>successDark (textos)</td>
            <td>#007133</td>
        </tr>
        <tr style="background-color: #00CC6A; color: #FFFFFF" >
            <td>success</td>
            <td>#00CC6A</td>
        </tr>
        <tr style="background-color: #CCF5E1" >
            <td>successBackground</td>
            <td>#CCF5E1</td>
        </tr>
        </tbody>
    </table>


Complementar
---------------
A paleta complementar deve ser utilizada de forma moderada e exclusivamente em etiquetas e tarjas. De maneira alguma poderá ser utilizada em outras partes da interface.

.. raw:: html

    <table class="color_palettes">
        <tbody>
        <tr style="background-color: #006F82; color: #FFFFFF">
            <td>tagDeepSkyBlue</td>
            <td>#006F82</td>
        </tr>
        <tr style="background-color: #008272; color: #FFFFFF">
            <td>tagAquamarine</td>
            <td>#008272</td>
        </tr>
        <tr style="background-color: #275BA7; color: #FFFFFF">
            <td>tagRoyalBlue4</td>
            <td>#275BA7</td>
        </tr>
        <tr style="background-color: #3F98D4; color: #FFFFFF">
            <td>tagSteelBlue1</td>
            <td>#3F98D4</td>
        </tr>
        <tr style="background-color: #C483B7; color: #FFFFFF">
            <td>tagHotPink3</td>
            <td>#C483B7</td>
        </tr>
        <tr style="background-color: #49BDCE; color: #FFFFFF">
            <td>tagCadetBlue</td>
            <td>#49BDCE</td>
        </tr>
        <tr style="background-color: #6CBD48; color: #FFFFFF">
            <td>tagForrest</td>
            <td>#6CBD48</td>
        </tr>
        <tr style="background-color: #F79E00; color: #FFFFFF">
            <td>tagGoldenrod</td>
            <td>#F79E00</td>
        </tr>
        <tr style="background-color: #8B8878; color: #FFFFFF">
            <td>tagChumbo</td>
            <td>#8B8878</td>
        </tr>
        <tr style="background-color: #F777CC; color: #FFFFFF">
            <td>tagHotPink</td>
            <td>#F777CC</td>
        </tr>
        <tr style="background-color: #6AE895">
            <td>tagGreen3</td>
            <td>#6AE895</td>
        </tr>
        <tr style="background-color: #DD2F1E; color: #FFFFFF">
            <td>tagBrown1</td>
            <td>#DD2F1E</td>
        </tr>
        <tr style="background-color: #B4009E; color: #FFFFFF">
            <td>tagMagenta3</td>
            <td>#B4009E</td>
        </tr>
        <tr style="background-color: #72328A; color: #FFFFFF">
            <td>tagBlueViolet</td>
            <td>#72328A</td>
        </tr>
        <tr style="background-color: #EF7753; color: #FFFFFF">
            <td>tagSandyBrown</td>
            <td>#EF7753</td>
        </tr>
        <tr style="background-color: #B4A0FF">
            <td>tagPurple1</td>
            <td>#B4A0FF</td>
        </tr>
        <tr style="background-color: #912CEE; color: #FFFFFF">
            <td>tagPurple4</td>
            <td>#912CEE</td>
        </tr>
        <tr style="background-color: #395264; color: #FFFFFF">
            <td>tagDarkness</td>
            <td>#395264</td>
        </tr>
        </tbody>
    </table>


Uso das cores
---------------


.. raw:: html

    <table class="color_palettes">
        <tbody>
            <tr style="background-color: #f2f2f2; color: #333333" >
                <td>Background</td>
                <td>#000000</td>
            </tr>
            <tr style="background-color: #f5f5f5; color: #333333" >
                <td>Sidebar</td>
                <td>#000000</td>
            </tr>
        </tbody>
    </table>
   