O comando `ps` lista os processos em execução no sistema, os parâmetros são:
* `-e`: Mostra os processos mais básicos em execução.
* `-f`: Mostra todos os processos de forma detalhada.

O comando `ps aux` mostra o uso de desempenho de cada processo de forma detalhada.

O comando `top` mostra os processos de forma dinâmica. Para ver as prioridades desse comandos, as letras são:
* `h`: Mostra uma página de ajuda mostrando todos os comandos que podem ser utilizados;
* `P`: Ordena por uso de **CPU**;
* `m`: Ordena por uso de memória;
* `n`: Ordena pelo **PID**;
* `t`: Ordena pelo tempo de execução;
* `L`: Busca por uma string;

> A diferença entre o `ps` e o `top` é que o `ps` exibe um "print" dos processos enquanto o `top` exibe os processos em tempo real.

O comando `kill -l` mostra os possíveis sinais que se pode enviar através desse comando, os sinais mais comuns são:
* **9) SIGKILL**: Encerra um processo imediatamente, sem que o programa se encerre por conta própria, às vezes pode gerar problemas.
* **15) SIGTERM**: Envia um sinal pro programa solicitando o encerramento do mesmo, em que o próprio programa planeja o fechamento sem grandes efeitos colaterais em relação ao sinal **9**.
* **18) SIGCONT**: Starta um processo.
* **18) SIGSTOP**: Para um processo.

O envio de um comando para um processo é `kill -CODE PID` onde o **CODE** é o código do sinal que será enviado e o **PID** é o **PID** do processo que ocorrerá a ação.

O comando `pstree` mostra a árvore de processos do sistema, em que mostram quais processos são filhos de outro.