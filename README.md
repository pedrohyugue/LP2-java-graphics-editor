# LP2 — Editor Gráfico em Java

## Nome:  Pedro Henrique Yugue da Fonseca
## Matricula:  20172059911

Projeto acadêmico desenvolvido em Java para a disciplina de LP2, com foco na criação e manipulação de figuras geométricas em uma interface gráfica.

O sistema funciona como um pequeno editor gráfico, permitindo criar, selecionar, mover, redimensionar, colorir e excluir figuras como retângulos, elipses, arcos e linhas.

## Autor

**Pedro Henrique Yugue da Fonseca**

## Sobre o projeto

Este repositório reúne exercícios e versões de um projeto gráfico desenvolvido em Java. A versão principal está na pasta `projeto2`, que contém uma aplicação com interface gráfica, botões, interação por teclado e mouse, além de manipulação de figuras em tela.

O projeto trabalha conceitos como:

* Programação orientada a objetos;
* Herança e polimorfismo;
* Organização de classes em pacotes;
* Interface gráfica com Java AWT/Swing;
* Eventos de teclado e mouse;
* Manipulação de objetos gráficos;
* Persistência simples de dados em arquivo binário.

## Funcionalidades

* Criar figuras geométricas na tela;
* Selecionar figuras com o mouse;
* Mover figuras arrastando ou usando as setas do teclado;
* Alterar cor de preenchimento;
* Alterar cor da borda;
* Aumentar e diminuir o tamanho da figura selecionada;
* Alternar o foco entre figuras;
* Excluir figuras;
* Salvar e carregar automaticamente as figuras criadas.

## Figuras disponíveis

O projeto possui classes específicas para diferentes tipos de figuras:

* `Rect` — retângulo;
* `Ellipse` — elipse;
* `Arc` — arco;
* `Line` — linha;
* `Figure` — classe base para as figuras.

## Tecnologias utilizadas

* Java;
* Java AWT;
* Java Swing;
* Programação Orientada a Objetos;
* Manipulação de eventos;
* Serialização de objetos.

## Estrutura do repositório

```bash
LP2/
├── 1/                 # Exercício inicial em C
├── 3.1/               # Exercícios em Java com figuras
├── 3.2/               # Exercícios em Java com figuras
├── 5.1/               # Evolução dos exercícios gráficos
├── 6.1/               # Evolução dos exercícios gráficos
├── 6.2/               # Evolução dos exercícios gráficos
├── 6.3/               # Evolução dos exercícios gráficos
├── 7.1/               # Evolução dos exercícios gráficos
├── m2/                # Atividades da disciplina
├── projeto/           # Primeira versão do projeto gráfico
├── projeto2/          # Versão mais completa do projeto
└── README.md
```

## Como executar o projeto

### Pré-requisitos

Antes de executar, é necessário ter o Java instalado na máquina.

Verifique a instalação com:

```bash
java -version
javac -version
```

### Clonar o repositório

```bash
git clone https://github.com/pedrohyugue/LP2.git
cd LP2
```

### Executar a versão principal

Entre na pasta `projeto2`:

```bash
cd projeto2
```

Compile os arquivos Java:

```bash
javac ivisible/*.java figures/*.java Button.java PackApp.java
```

Execute o programa:

```bash
java PackApp
```

## Controles do projeto

| Tecla / Ação     | Função                        |
| ---------------- | ----------------------------- |
| `R`              | Cria um retângulo             |
| `A`              | Cria um arco                  |
| `E`              | Cria uma elipse               |
| `L`              | Cria uma linha                |
| `+`              | Aumenta a figura selecionada  |
| `-`              | Diminui a figura selecionada  |
| `Z`              | Altera a cor de preenchimento |
| `C`              | Altera a cor da borda         |
| Setas do teclado | Move a figura selecionada     |
| `Tab`            | Alterna o foco entre figuras  |
| `Delete`         | Exclui a figura selecionada   |
| Mouse            | Seleciona e arrasta figuras   |

## Principais conceitos aplicados

### Programação Orientada a Objetos

O projeto utiliza classes para representar diferentes figuras geométricas, permitindo reaproveitamento de código e organização da lógica.

### Pacotes em Java

As figuras foram organizadas dentro do pacote `figures`, separando a lógica das figuras da aplicação principal.

### Interface gráfica

A interface foi construída utilizando recursos do Java AWT/Swing, com uma janela onde as figuras são renderizadas e manipuladas.

### Eventos

A aplicação utiliza eventos de teclado e mouse para permitir interação com as figuras na tela.

### Persistência

A versão `projeto2` salva o estado das figuras em um arquivo binário, permitindo recuperar os objetos ao abrir novamente o programa.

## Aprendizados

Durante o desenvolvimento, foram praticados conceitos fundamentais de Java e de programação orientada a objetos, como criação de classes, encapsulamento, herança, uso de pacotes, eventos gráficos e manipulação de interface.

Além disso, o projeto ajudou a compreender como aplicações desktop podem lidar com entrada do usuário, desenho de elementos gráficos e organização de código em múltiplos arquivos.

## Status do projeto

Projeto acadêmico finalizado, mantido como registro de estudo e prática em Java.
