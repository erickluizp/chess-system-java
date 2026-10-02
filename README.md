# ♟️ Chess System Java

Sistema de xadrez para jogar pelo terminal, desenvolvido em Java com foco em Programação Orientada a Objetos.

![Java](https://img.shields.io/badge/Java-11%2B-orange)
![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)

## 📋 Sobre o projeto

Este projeto é uma aplicação de console onde dois jogadores disputam uma partida completa de xadrez. O sistema valida os movimentos de cada peça, controla os turnos e identifica situações de xeque e xeque-mate.

O objetivo principal é praticar conceitos de Java e POO em um projeto de médio porte, com arquitetura em camadas.

## ✨ Funcionalidades

- Tabuleiro 8x8 exibido no terminal, com peças brancas e pretas
- Todas as peças: Peão, Torre, Cavalo, Bispo, Rainha e Rei
- Validação de movimentos possíveis, com destaque das casas disponíveis
- Controle de turnos e jogador atual
- Lista de peças capturadas
- Detecção de **xeque** e **xeque-mate**
- Jogadas especiais: **roque**, **en passant** e **promoção**
- Tratamento de exceções para jogadas inválidas

## 🧠 Conceitos aplicados

- Encapsulamento e modificadores de acesso
- Herança, polimorfismo e sobrescrita
- Classes e métodos abstratos
- Enumerações
- Tratamento de exceções personalizadas
- Listas e matrizes
- Arquitetura em camadas (aplicação, jogo de tabuleiro e regras do xadrez)

## 🗂️ Estrutura do projeto

```
chess-system-java/
├── src/
│   ├── application/   # Programa principal e interface de console (UI)
│   ├── boardgame/     # Camada genérica: tabuleiro, peça e posição
│   └── chess/         # Regras do xadrez: peças, partida e exceções
└── README.md
```

## 🚀 Como executar

### Pré-requisitos

- [JDK 11 ou superior](https://www.oracle.com/java/technologies/downloads/) instalado
- Git (opcional, para clonar o repositório)

### Passo a passo

```bash
# Clone o repositório
git clone https://github.com/erickluizp/chess-system-java.git

# Acesse a pasta do projeto
cd chess-system-java

# Compile o código
javac -d bin src/application/Program.java

# Execute a aplicação
java -cp bin application.Program
```

Também é possível abrir o projeto em uma IDE (Eclipse, IntelliJ ou VS Code) e executar a classe `Program`.

## 🎮 Como jogar

1. As colunas são letras (`a` a `h`) e as linhas são números (`1` a `8`).
2. Para escolher uma peça, digite a coluna seguida da linha, sem espaços. Exemplo: `e2`.
3. O sistema mostra as casas para onde a peça pode ir.
4. Digite a posição de destino. Exemplo: `e4`.
5. Os jogadores se alternam até o xeque-mate.

```
8 R N B Q K B N R
7 P P P P P P P P
6 - - - - - - - -
5 - - - - - - - -
4 - - - - - - - -
3 - - - - - - - -
2 P P P P P P P P
1 R N B Q K B N R
  a b c d e f g h
```

## 👤 Autor

**Erick Luiz**

[![GitHub](https://img.shields.io/badge/GitHub-erickluizp-181717?logo=github)](https://github.com/erickluizp)

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
