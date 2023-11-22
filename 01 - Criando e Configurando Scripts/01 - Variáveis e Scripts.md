O comando `env` mostra todas as variáveis do sistema e seus respectivos valores.

O comando `echo $VAR` mostra o conteúdo de uma variável (o `$` deve vir antes do nome da variável).

Para definir uma variável, usa-se `var=value`.

Ao criar um script, uma prática comum é colocar na 1ª linha do arquivo o seguinte conteúdo: `#!/bin/bash` isso indica para o script qual será o terminal a ser usado, nesse caso o *bash* (padrão do **Ubuntu**).

O comando `read` lê um input do usuário.

Para executar um script, basta digitar o local do arquivo que o script será executado.

> Como o arquivo é um arquivo de script, é necessário dar acesso para executar o script no usuário atual, para isso, use o comando `chmod u+x ./SCRIPT` para conceder acesso de execução ao arquivo