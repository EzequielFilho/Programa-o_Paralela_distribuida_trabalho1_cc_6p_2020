## Projeto Cronômetro
O projeto cronometro é um simples relógio para medição de tempo.

![Captura 1](captura1.png "Captura 1") ![Captura 2](captura2.png "Captura 2")

##### Threads!
O sistema é dividido em duas principais partes:
- Interface do Usuário (classe Janela) → Responsável por controlar o que o usuário vê na tela. Utiliza uma thread para atualizar as informações, aguardando uma notificação do cronometro.
- Cronometro (classe Cronometro) → Responsável por calcular o tempo passado. Utiliza uma thread para avisar a janela atualizar as informações.

#### Requisitos
* Java 1.8
* Java Swing
