===========================
Modal
===========================

Modal é usado quando o usuário precise executar uma ação, mas sem passar para uma nova página e interromper o fluxo de trabalho do usuário, você pode usar o Modal para criar uma nova camada flutuante na página atual para o usuário executar ações ou exibir informações.
O modal deve ser posicionado sempre no centro da tela, horizontal e vertical.
Evite abrir uma modal sem que o usuário tenha feito nenhuma ação relacionada.

.. figure:: /_static/modal-dimensoes.png
   :width: 723px
   :align: center
   :alt: dimensões de modais


1. **Header:** geralmente contém o titulo do modal e um botão fechar.
2. **Body:** conteúdo do modal, pode ser texto, formulário, ações, etc.
3. **Footer:** contém os botões de ação do modal, a ação principal deve ser um botão do tipo primario com texto que descreva a ação que irá acontecer caso seja clicado.


Tamanhos
=========

Os modais podem ser usados em 3 tamanhos, **small**, **medium**, **large**

Medium
--------

O modal default **Medium** tem 500px de largura.

.. figure:: /_static/modal-medium.png
   :width: 768px
   :align: center
   :alt: modal Default


Small
--------

O modal pequeno **Small** tem 300px de largura.

.. figure:: /_static/modal-small.png
   :width: 903px
   :align: center
   :alt: modal small

Large
--------

O modal grande **Large** tem 800px de largura.

.. figure:: /_static/modal-large.png
   :width: 923px
   :align: center
   :alt: modal large


Acessibilidade
===============

O foco não deve retornar à página subjacente até que o usuário pressione a tecla Esc, pressione um botão explícito "Cancelar", "Fechar" ou execute outra ação que feche o modal.

