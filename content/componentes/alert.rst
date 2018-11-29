===========================
Alert
===========================

O Alert deve ser usado pra mostrar mensagens criticas ao usuário, no topo da tela, como uma perda de conexação ou funcionalidade, por exemplo. As mensagens de alert demoram mais para sair da tela que uma mensagem Toast, no máximo 8 segundos, e deve possibilitar que o usuário feche caso queira.

São usados em notificações que o usuário precisa ver o conteudo para saber o que está acontecendo com a aplicação, por exemplo uma mensagem de erro do sistema.

- Alerts devem aparecer somente uma por vez.
- Evite usar mensagens "culpando" o usuário por algum erro. Prefira usar "Nós estamos com um problema de conexão" do que "Você está com problemas de conexão".
- Deixe o usuário saber o que está acontecendo, mas seja claro e tente não usar temos técnicos.


.. figure:: /_static/alert-dimensoes.png
   :width: 100%
   :align: center
   :alt: exemplo de botão com loader