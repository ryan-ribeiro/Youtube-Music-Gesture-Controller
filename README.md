# Youtube-Music-Gesture-Controller
## Descrição

Este projeto, desenvolvido como Projeto Final da disciplina de Laboratório de Inovação e Automação, consiste em um sistema que permite controlar o YouTube Music utilizando gestos das mãos.

A solução é baseada em Visão Computacional e utiliza a biblioteca MediaPipe Hands para a detecção das mãos e rastreamento dos dedos, em conjunto com a PyAutoGUI para simular inputs de teclado que realizam a interação com o aplicativo do YouTube Music. 

O funcionamento consiste em: executar o script, desbloquear a detecção dos gestos (mantendo o punho cerrado por três segundos, qualquer uma das mãos), o que fará o aplicativo de música ser aberto caso não já o estiver, e por último navegar utilizando gestos, até o momento em que se deseje bloquear a detecção de gestos novamente, com o mesmo procedimento já dito.

## Funcionalidades

- Detecção de Mãos: Identifica a posição e orientação das mãos utilizando o modelo da biblioteca MediaPipe Hands.

- Reconhecimento de Gestos: Detecta diferentes gestos da mão e associa cada gesto a uma funcionalidade de controle multimídia, como:

  - Reproduzir/pausar a música.

  - Avançar para a próxima faixa.

  - Retroceder para a faixa anterior.

  - Pular 15 segundos para frente ou para trás no vídeo

  - Navegar pela página utilizando tab (ou shift+tab) e enter, entrando em playlists salvas ou sugeridas

- Integração com o YouTube Music: Automatiza o controle do aplicativo diretamente no sistema operacional.

## Tecnologias Utilizadas

- Linguagem de Programação: Python

- Bibliotecas Principais:

  - MediaPipe Hands: Para detecção e rastreamento das mãos.

  - PyAutoGUI: Para emulação de comandos de teclado.

  - OpenCV: Para manipulação da entrada da câmera e visualização do feedback.

  - PyGetWindow: Para gerenciar e alternar entre janelas no sistema operacional.

- Hardware: Webcam para captura das imagens.

## Como Executar o Projeto

1. **Requisitos de Sistema:**

- Python 3.7 ou superior.

- Webcam funcional.

- Youtube Music App
  - Sugiro instalar o Brave e abrir o Youtube Music, e então instalar um aplicativo que é um link para essa página. Ao instalar em seu sistema operacional, copie o caminho e cole no arquivo python para funcionar.  

2. **Instale as Dependências:**
Execute o seguinte comando para instalar todas as bibliotecas necessárias:

```
pip install -r requirements.txt
```
3. **Execute o Script:**
Certifique-se de que o caminho para o atalho do YouTube Music está configurado corretamente no código. Em seguida, execute o script principal:
```
python Gesture-Controller.py
```

4. **Controle por Gestos:**

- Certifique-se de que a mão está visível para a webcam.

- Realize os gestos configurados para interagir com o YouTube Music.

- Consulte o handle da mão esquerda e direita para encontrar os gestos relacionados a cada comando, dentro do arquivo do programa. 

- Pressione q para encerrar o programa.

## Estrutura do Projeto
```
|— hands_new.py      # Script principal do projeto.
|— LICENSE           # Licença do projeto
|— README.md         # Documentação do projeto.
|— demo.mp4          # Vídeo de demonstração do projeto
|— requirements.txt  # Lista de dependências.
```
## Demonstração

Caso deseje visualizar o funcionamento do projeto, você pode assistir ao [vídeo de demonstração](https://drive.google.com/file/d/1QysnbWF9SiYpWTmd1fpldzc834MqnEJu/view?usp=sharing). O vídeo ilustra os gestos utilizados e o controle em tempo real do YouTube Music.

## Considerações Finais

Este projeto explora o potencial da visão computacional em aplicações do dia a dia, oferecendo uma experiência inovadora de interação com mídia digital. Sinta-se à vontade para contribuir com melhorias ou adaptações para outras aplicações.

Autor: [Ryan Ribeiro]Contato: [RyanRodrigues0071234@gmail.com]

