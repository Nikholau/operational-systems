## PROCESSOS E THREADS
### O que é um processo
Um processo é apenas uma instância de um programa em execução, incluindo os valores atuais do contador do programa, registradores e variáveis.

### Estados de um processo
Novo, em execução, pronto, bloqueado, encerrado.

### Controlamento
Um sistema operacional controla e gerencia os processos por meio de um scheduler que decide o que será executado e quando.

### Componentes
Id do processo, contador de programa, conjunto de registradores, uma pilha, uma área de dados, uma área de código.

### Threads
Unidades de execução leves executam simultaneamente dentro de um processo, diferem de processo por compartilharem o mesmo espaço de endereçamento e recursos do processo pai.

### Diferença de criação de thread e processos
A criação de uma nova thread é mais eficiente em termos de recursos do sistema do que a criação de um novo processo, pois as threads compartilham o mesmo espaço de endereçamento e recursos do processo pai.
