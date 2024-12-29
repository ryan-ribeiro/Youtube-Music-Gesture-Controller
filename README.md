# Youtube-Music-Gesture-Controller
## Descrição

Este projeto, desenvolvido como parte da disciplina de Laboratório de Inovação e Automação, consiste em um sistema que permite controlar o YouTube Music utilizando gestos das mãos.

A solução é baseada em Visão Computacional e utiliza a biblioteca MediaPipe Hands para a detecção das mãos e rastreamento dos dedos, em conjunto com a PyAutoGUI para simular inputs de teclado que realizam a interação com o aplicativo do YouTube Music.

## Funcionalidades

- Detecção de Mãos: Identifica a posição e orientação das mãos utilizando o modelo da biblioteca MediaPipe Hands.'

- Reconhecimento de Gestos: Detecta diferentes gestos da mão e associa cada gesto a uma funcionalidade de controle multimídia, como:

  - Reproduzir/pausar a música.

  - Avançar para a próxima faixa.

  - Retroceder para a faixa anterior.

- Integração com o YouTube Music: Automatiza o controle do aplicativo diretamente no sistema operacional.

## Tecnologias Utilizadas

- Linguagem de Programação: Python

- Bibliotecas Principais __(contidas no arquivo requirements.txt)__:

  - MediaPipe Hands: Para detecção e rastreamento das mãos.

  - PyAutoGUI: Para emulação de comandos de teclado.

  - OpenCV: Para manipulação da entrada da câmera e visualização do feedback.

  - PyGetWindow: Para gerenciar e alternar entre janelas no sistema operacional.

- Hardware: Webcam para captura das imagens.

## Como Executar o Projeto

1. **Requisitos de Sistema:**

- Python 3.7 ou superior.

- Webcam funcional.

- Sistema operacional Windows.

2. **Instale as Dependências:**
Execute o seguinte comando para instalar todas as bibliotecas necessárias:

```
pip install opencv-python mediapipe pygetwindow pyautogui
```
3. **Execute o Script:**
Certifique-se de que o caminho para o atalho do YouTube Music está configurado corretamente no código. Em seguida, execute o script principal:
```
python hands_new.py
```

4. **Controle por Gestos:**

- Certifique-se de que a mão está visível para a webcam.

- Realize os gestos configurados para interagir com o YouTube Music.

- Pressione q para encerrar o programa.

## Estrutura do Projeto
```
|— hands_new.py      # Script principal do projeto.
|— README.md         # Documentação do projeto.
|— requirements.txt  # Lista de dependências.
```
## Demonstração

Caso deseje visualizar o funcionamento do projeto, você pode assistir ao [vídeo de demonstração](link). O vídeo ilustra os gestos utilizados e o controle em tempo real do YouTube Music.

## Considerações Finais

Este projeto explora o potencial da visão computacional em aplicações do dia a dia, oferecendo uma experiência inovadora de interação com mídia digital. Sinta-se à vontade para contribuir com melhorias ou adaptações para outras aplicações.

Autor: [Ryan Ribeiro]Contato: [RyanRodrigues0071234@gmail.com]

