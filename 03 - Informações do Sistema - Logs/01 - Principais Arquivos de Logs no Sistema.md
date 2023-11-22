A pasta */var/log* contém informações sobre os logs feitos no sistema.

O arquivo **dmesg** mostra o log de *boot* do sistema operacional.

O arquivo **syslog** mostra o log das tarefas do sistema operacional enquanto ele está executando.

O arquivo **auth.log** mostra o log de requisições ao sistema, como uma entrada incorreta de uma senha de usuário, etc.

O comando `tail -f FILE` mostra as últimas linhas do arquivo em tempo real, ou seja, quando o arquivo atualizar, o terminal vai atualizar junto mostrando as últimas linhas do arquivo.