===========================
Input
===========================

- Os campos de input são sempre acompanhados de um label, mesmo que eles não apareçam visualmente na tela. Para vincular um campo de input com um label é preciso usar o atributo “id” no input e um atributo “for” no label, ambos com o mesmo valor.
- Para fins de validação e mensagens, é necessário que cada input tenha um “name” associado, isso fará com que o input seja vinculado ao form e este ao controller principal.
- Colocar as unidades de medida no label do campo, sempre entre parênteses. Ex: Valor (R$)
- As mensagens de validação somente são exibidas quando o usuário passa pelo campo.
 
 
.. figure:: /_static/input.png
   :width: 567px
   :align: center
   :alt: anatomia do input


1. **Label:** deve descrever qual dado o usuário precisa inserir. Nos campos obrigatórios é acompanhado de um asterisco (*).

2. **Input:** campo em que o usuário irá inserir os dados. Podendo ou não mostrar um placeholder para auxuliar o usuário.

3. **Mensagem de erro:** Use as mensagens de validação e erro para indicar quando um formulário ou submissão de campo falha ou requer que informações adicionais sejam exibidas.

Tamanhos
========
Existem 3 diferentes tamanhos de inputs: **large** (36px), **default** (32px) e **small** (28px).

.. figure:: /_static/input-tamanho.png
   :width: 462px
   :class: img-responsive
   :align: center
   :alt: tamanhos de input


Interações
==========

.. figure:: /_static/input-interacoes.png
   :width: 900px
   :align: center
   :alt: interaçoes de input


Validação (erro)
================
O espaçamento entre os itens do formulario deve prever a exibição de uma mensagem de erro, sendo assim quando a mensagem de erro aparecer, o conteúdo abaixo não poderá ser deslocado para baixo.

.. figure:: /_static/input-validacao.png
   :width: 390px
   :align: center
   :alt: interaçoes de input


Máscara
========

.. figure:: /_static/input-mascara.png
   :width: 608px
   :align: center
   :alt: input de senha

Senha
======

.. figure:: /_static/input-senha.png
   :width: 330px
   :align: center
   :alt: input de senha