# Flappy Bird - Python Implementation

Este repositório contém uma implementação do clássico jogo Flappy Bird utilizando **Python** e **Pygame**. O código foi desenvolvido para demonstrar conceitos de programação gráfica, animações e detecção de colisão.

## 🕹️ Como jogar

- O objetivo é manter o pássaro no ar e passar pelos canos sem colidir.
- Use as seguintes teclas para controlar o jogo:
  - **Espaço**, **Enter** ou **Seta Para Cima**: Faz o pássaro voar para cima.
  - **P** ou **Pause**: Pausa ou retoma o jogo.
  - **Esc**: Sai do jogo.

## 🚀 Configuração do ambiente

### Pré-requisitos
- Python.
- Biblioteca **Pygame** instalada. Para instalar, use o seguinte comando:
  ```bash
  pip install pygame

## Como executar
Clone este repositório:

bash
```
git clone https://github.com/isaccanedo/flappy_bird_python.git
cd flappy-bird-python
```

## 📂 Estrutura do código
Classes principais:
- Bird: Representa o pássaro, incluindo sua movimentação e animação.
- PipePair: Gerencia os canos e a lógica de colisão.
Funções auxiliares:
- load_images: Carrega as imagens usadas no jogo.
- frames_to_msec e msec_to_frames: Convertem entre frames e milissegundos.
## 📸 Imagens do jogo
Adicione capturas de tela do jogo na pasta /screenshots e inclua-as aqui no README, como:

![Screenshot do jogo](screenshots/gameplay.png)

🛠️ Recursos
Movimentação do pássaro: Baseada na física de queda e impulso para cima.
Detecção de colisão: Utiliza máscaras para precisão.
Geração dinâmica de canos: Baseada em posições randômicas.
Pontuação: Incrementada ao passar pelos canos.
