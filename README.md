# Simulação de Taco de Golfe com IMU e Potenciômetro Linear

Este projeto visa desenvolver um protótipo de simulação de um taco de golfe, utilizando uma Unidade de Medição Inercial (IMU), um potenciômetro linear e um atuador de vibração (vibra cal). O protótipo capta o movimento do taco e simula o impacto da bola, fornecendo uma experiência imersiva ao jogador.

# Sobre o controle:

O controle do jogo será feito principalmente através da IMU e de um potenciômetro linear, permitindo que possamos determinar a posição e a força da tacada com esse novo dispositivo físico. Ao puxar o potenciômetro, será possível perceber a intensidade, variando entre 0 e 100%, o que indicará o quão forte será a tacada. Além disso, a medição inercial possibilitará a formação de novos ângulos, o que, combinado com a força proporcionada pela extensão do potenciômetro, determinará a direção da bola, ajudando-a a alcançar o buraco.

Além do controle através da IMU e do potenciômetro, haverá também um botão adicional que servirá para realizar ações como passar de fase, pausar o jogo, retornar à fase anterior, entre outras. Embora o controle principal seja guiado pela IMU, este botão permitirá maior versatilidade na navegação do jogo.

O principal objetivo é desenvolver um objeto físico funcional e integrado – sem dependência externa – que aprimore a jogabilidade e torne a experiência mais próxima da realidade.

# Sobre o jogo:

O jogo "MiniGolf Master" possui uma interface organizada em diferentes níveis de dificuldade (fácil, médio e difícil), cada um com uma quantidade distinta de fases. Cada fase apresenta uma disposição visual diferente durante o lance da bola, o que proporciona uma jogabilidade variada e oferece diversas opções para aplicar diferentes técnicas ao jogo. Para avançar de fase, o jogador deve fazer com que a bola chegue ao buraco; quanto menor o número de tacadas, maior a pontuação. A pontuação varia de 0 a 3 estrelas no final de cada fase, de acordo com o desempenho do jogador.
![image](https://github.com/user-attachments/assets/0473a213-40af-4877-84a4-77321fd310be)
![Imagem do WhatsApp de 2024-09-25 à(s) 16 36 27_6a49ee75](https://github.com/user-attachments/assets/8a2d47c7-a680-49d2-be2d-aec5cfcb29d0)
