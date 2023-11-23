O comando `passwd` troca a senha do usuário local.

> Por padrão, como super usuário, o sistema já executa os comandos sem ter aviso prévio, por entender que o usuário sabe o que está fazendo, o que pode ocasionar um comportamento diferente ou até mais direto em relação à outros usuários sem privilegios executando os mesmos comandos.

O arquivo */etc/passwd* mostra o *database* dos usuários locais na máquina.

O arquivo */etc/shadow* guarda os *hashes* das senhas dos usuários do sistema.

> Caso contenha `*`, significa que este usuário não tem uma senha.