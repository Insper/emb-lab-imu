> Issue:
>
> - Você só deve fechar as issues que foram 100% concluidas.
> - Se não concluiu 100% a issues, você pode fazer um comentário que ireimos analisar!

Vamos detectar para onde o sistema está apontando, a ideia é acender os LEDs da placa OLED da seguinte maneira:

- LED1: Apontando para esquerda
- LED2: Apontando para frente
- LED3: Apontando para direita

Para isso:

1. Crie um `enum` chamado `orientacao` com os seguintes itens: `ESQUERDA, FRENTE, DIREITA`
1. Crie uma task (`task_orientacao`) que possui uma fila e que recebe um dado do tipo `orientacao` e que dependendo do valor recebido, acende o LED conforme descrição anterior.
1. Na task da IMU, detecta a orientação e envie o dado para a fila.

**A referência da orientação é a posição de quando a placa liga**
