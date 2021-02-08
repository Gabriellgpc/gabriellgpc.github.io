<!-- # Luís Gabriel Pereira Condados -->

# Contatos e Informações:
email: [condadoslgpc@gmail.com](condadoslgpc@gmail.com)\
github: [github.io/gabriellgpc](github.io/gabriellgpc)\
linkedin: [linkedin.com/in/lgabrielpc](https://www.linkedin.com/in/lgabrielpc)\
lattes: [lattes.cnpq.br/7552086880914030](http://lattes.cnpq.br/7552086880914030)\
youtube: [youtube.com/channel/UCGqW9GuMni6KTZkLF2dxu4g](https://www.youtube.com/channel/UCGqW9GuMni6KTZkLF2dxu4g)\
kaggle: [kaggle/condados](https://www.kaggle.com/condados)

# Sumário

- [Contatos e Informações:](#contatos-e-informações)
- [Sumário](#sumário)
- [Projeto: Futrobot - Software da Equipe Poti de Futebol de Robôs](#projeto-futrobot---software-da-equipe-poti-de-futebol-de-robôs)
- [Futrobot-firwmare](#futrobot-firwmare)
- [Biblioteca BluetoothAction](#biblioteca-bluetoothaction)
- [Projeto de Controle Embarcado para Robôs com Acionamento Diferencial e Encoders de Baixa Resolução](#projeto-de-controle-embarcado-para-robôs-com-acionamento-diferencial-e-encoders-de-baixa-resolução)
- [Workshop: Python Overview](#workshop-python-overview)
- [Programas Desenvolvidos na Disciplina de Processamento Digital de Imagens](#programas-desenvolvidos-na-disciplina-de-processamento-digital-de-imagens)
- [Programas Desenvolvidos na Disciplina de Visão Computacional](#programas-desenvolvidos-na-disciplina-de-visão-computacional)
- [Implementação do Algoritmo Raytraicing em C++](#implementação-do-algoritmo-raytraicing-em-c)
- [Alguns dos Projetos que Estou Organizando para Publicar Aqui](#alguns-dos-projetos-que-estou-organizando-para-publicar-aqui)
- [Filtro de Borramento Adaptativo](#filtro-de-borramento-adaptativo)
- [Transformada Hough para Identificação de Quadrados](#transformada-hough-para-identificação-de-quadrados)
- [Digit Recognizer](#digit-recognizer)
- [classification challenge - Dogs vs. Cats](#classification-challenge---dogs-vs-cats)
- [Tutoriais e Dicas](#tutoriais-e-dicas)
  - [Linux](#linux)
  - [Python Virtual Environment](#python-virtual-environment)
  - [VSCode](#vscode)
  - [Vim](#vim)
  - [Template ESP Project](#template-esp-project)


# [Projeto: Futrobot - Software da Equipe Poti de Futebol de Robôs](https://github.com/potiufrn/Futrobot)
Software desenvolvido pela Equipe Poti de futebol de robôs do Departamento de Computação e Automação(DCA) da UFRN voltado para o desenvolvimento de pesquisas em robótica e participações em competições de futebol de robôs ([Aqui](https://potiufrn.github.io/) você pode ler mais a respeito de alguns dos trabalhos realizados).

Um pouco sobre as técnologias utilizadas no software:
* Escrito em **C e C++**
* Compilação gerenciada por meio de **Makefile** (usando bastante dos recursos "smart" do **make**, ficou quase tão simples quanto usar CMake :p)
* **Linux**
* **Qt** para fazer as interfaces gráficas, mas o sistema também roda direto pelo terminal, porém é necessário usar a interface pelo menos para fazer a calibração das cores (o sistema de visão utiliza segmentação por cores)
* **bluetooth** para comunicação com o host(pc) e os robôs (frota de três robôs)
* No mais é C++ para fazer: processamento de imagem, visão computacional, IA, controle ...
* **v4l2** (video for linux 2) utilizada para construir a biblioteca para controle da câmera (configuração e consulta dos parâmetros da câmera) e para captura de imagens em YUYV ou RGBG.

<!-- TODO -->
<!-- Colocar imagens e vídeos aqui -->
<!-- Arrumar a documentação do repositório alvo -->

**Algumas informações prévias:**
A manipulação do sistema é feita via Terminal do Linux, tendo a interface gráfica apenas o módulo de calibração.

# [Futrobot-firwmare](https://github.com/potiufrn/Futrobot-firmware)
Software embarcado para os robôs da Equipe Poti de futebol de robôs 2020.

Estou organizando ainda essa página e a documentação, logo mais deixarei uma descrição melhor do projeto aqui e uma documentação lá :)

# [Biblioteca BluetoothAction](https://github.com/potiufrn/bluetoothAction)
Biblioteca criada e mantida pelo laboratório de robótica do DCA. Fiz alguns algumas modicações para torna-la mais genérica (foi criada para ser usada no [Futrobot](##[Futrobot-firwmare](https://github.com/potiufrn/Futrobot-firmware)))

# [Projeto de Controle Embarcado para Robôs com Acionamento Diferencial e Encoders de Baixa Resolução](https://github.com/Gabriellgpc/TCC---Controle-Embarcado)
Projeto em Latex do Meu TCC :). E aqui é a apresentação (também um projeto Latex) que fiz para a defesa: [Slide-Apresentação](https://github.com/Gabriellgpc/Apresentacao_TCC).

Logo vou escrever uma breve documentação aqui explicando do que se trata, mas nesses links você já irá encontrar o pdf da monografia.

# [Workshop: Python Overview](https://github.com/Gabriellgpc/python_workshop_overview)
Material que criei para ministrar um workshop sobre a linguagem de programação python para o time de rocket design da UFRN ([Potiguar Rocket Design](https://www.youtube.com/channel/UCWEqiELiw2ohrE56GyWJAcg/featured)) em 2020.

A ideia era mostrar e ensinar o básico (com práticas e demostrações) sobre ferramentas úteis para a realidade da grande maioria dos integrantes do time (estudantes de engenharia mecânica em sua maioria) como:
* Ambiente Jupyter notebook / Colab
* Python básico
* Programação orientada a objetos com python
* Numpy
* Matplotlib
* Scipy
* Pandas

# [Programas Desenvolvidos na Disciplina de Processamento Digital de Imagens](https://gabriellgpc.github.io/processamento_digital_de_imagens_UFRN/)
  O link leva para um blog que fiz para servir como documentação online das atividades que desenvolvi durante a disciplina de Processamento Digital de Imagens do Departamento de Engenharia de Computação e Automação (DCA) da UFRN, a disciplina foi ministrada pelo professor Dr. [Agostinho de Brito Junior](https://agostinhobritojr.github.io/).


# [Programas Desenvolvidos na Disciplina de Visão Computacional](https://gabriellgpc.github.io/visao_computacional_DIM0141/)
  O link leva para um blog que fiz para servir como documentação online das atividades que desenvolvi durante a disciplina de Visão Computacional da UFRN, a disciplina foi ministrada pelo professor Dr.[Rafael Beserra Gomes](https://dimap.ufrn.br/~rafaelbg/index.html).

# [Implementação do Algoritmo Raytraicing em C++](https://github.com/Gabriellgpc/raytracing)

Implementação do algoritmo de renderização raytracing em C++ e usando [openGL](https://www.opengl.org/)(criação da imagem rasterizada) e [OpenMP](https://www.openmp.org/)(para processamento paralelo).

Vou documentar lá ainda e melhorar esta descrição...
Se liga num vídeozinho massa de demostração dessa implementação: [video de demostração](https://www.youtube.com/watch?v=QzKdFQ4jB-k).

# [Alguns dos Projetos que Estou Organizando para Publicar Aqui](https://github.com/Gabriellgpc/my_personal_projects)
Vou introduzir cada um deles aqui e criar uma documentação em cada um deles ainda.

# [Filtro de Borramento Adaptativo](https://github.com/Gabriellgpc/my_personal_projects/tree/main/computer_vision/adaptive_blurring)
  O título resumiu bem o que o programa faz, mas sendo um pouco mais específico, o recebe uma imagem e aplica um filtro de borramento que é mais forte em regiões de não borda e um mais suave em regiões de borda.

# [Transformada Hough para Identificação de Quadrados](https://github.com/Gabriellgpc/my_personal_projects/tree/main/computer_vision/hough_square)
  A transformada de *Hough* é um método comum para detecção de formas que são facilmente parametrizáveis (formas comuns: linhas e círculos). Geralmente essa transformada é utilizada após a etapa de pré-processamento de detecção de bordas.

  O método consiste em mapear determinados pixeis da imagem numa determinada célula no espaço de parâmetros que definem a figura geométrica. Esse procedimento é repetido para toda a imagem e as células do espaço de parâmetros são incrementadas, servindo assim de indicadores da existência de uma determinada forma.

  Neste trabalho será apresentado uma implementação da transformada *Hough* para a identificação de quadrados pretos em imagens com fundo branco baseado no gradiente. Para isso foi feito a parametrização de um quadrado com a informação do centro do quadrado, tamanho do lado e orientação com relação ao eixo horizontal ($x_c, y_c, l, \theta$), por isso o espaço de configuração terá dimensão $4$. Para fazer o mapeamento entre o espaço de imagem e o de parâmetros foi utilizado a informação do gradiente da imagem e um ponto de borda, para com isso obter-se as normais do quadrado e com isso estimar os quatro parâmetros. Após o mapeamento/acumulo dos indicadores é feito uma etapa de filtragem dos quadrados, para melhorar a precisão da detecção.

# [Digit Recognizer](https://www.kaggle.com/condados/first-project-mnist-digit-nn)
  "MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

  In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare."[Kaggle](https://www.kaggle.com/c/digit-recognizer).

# [classification challenge - Dogs vs. Cats](https://www.kaggle.com/condados/my-cnn-for-dog-vs-cats)
  In this competition, I wrote an algorithm to classify whether images contain either a dog or a cat. The training archive contains 25,000 images of dogs and cats (1 = dog, 0 = cat).[Dogs vs Cats Competition](https://www.kaggle.com/c/dogs-vs-cats/overview)

# [Tutoriais e Dicas](https://github.com/Gabriellgpc/my_personal_projects/tree/main/tutorial)
Tutoriais de download, instalação e uso das principais ferramentas/tecnologias que uso para desenvolver

## Linux
Comandos que me foram/são úteis e que não posso esquecer...

## Python Virtual Environment
Básico sobre ambientes virtuais em python 3.

## VSCode
Provavelmente vou deixar uma lista com o nome das extensões que eu gostei de utilizar com um overview sobre cada um.

## Vim
Já fiz o tutorial algumas vezes mas sempre acabo navegando usando as setas -_-

## [Template ESP Project](https://github.com/Gabriellgpc/esp-idf-project)

Tenho até que atualizar lá e colocar um manual de instalação e configuração do ambiente ainda...
