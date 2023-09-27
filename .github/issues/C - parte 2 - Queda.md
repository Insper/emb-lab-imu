> Issue:
>
> - Você só deve fechar as issues que foram 100% concluidas.
> - Se não concluiu 100% a issues, você pode fazer um comentário que ireimos analisar!

**Detectando queda**

- Crie uma tarefa `task_house_down` que possui um semáforo, e que quando liberado a task pisca o led da placa
- Utilizando os dados do acelerômetro, libere o semáforo quando uma queda for detectada. 

Dica: 

- A IMU sempre mede o valor da gravidade, em uma queda esse valor deve se aproximar de zero (queda anula a gravidade)
- Você pode calcular o módulo de todos os eixos e verificar a condição.
