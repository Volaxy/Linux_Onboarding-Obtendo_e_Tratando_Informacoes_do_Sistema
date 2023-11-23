A recomendação é sempre utilizar o usuário padrão do sistema, e conforme for necessário, aprimorar os privilégios do usuário.

O caminho */etc/sudoers* mostra quais usuários podem usar quais comandos, no geral exibe os privilégios dos usuários. Um comando para editar esse arquivo é o `sudo visudo`, onde será aberto o editor de texto **Nano** para editar o arquivo de privilégios.

O comando `groups` mostra quais grupos que o usuário local pertence. O arquivo localizado em */etc/group* mostra quais usuários estão atrelados em quais grupos do sistema.

Por padrão, o terminal exibirá o caractere `$`, indicando que o terminal está sendo acessado por um usuário não privilegiado. O comando `su` pode ser usado para acessar outros usuários do sistema (desde que se saiba a senha) ou o comando usado de forma isolado, muda para o usuário root, que tem privilégios máximos no sistema (o símbolo é indicado por `#`).