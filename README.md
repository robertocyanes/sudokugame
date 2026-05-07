# 🟣 Sudoku Game Java

Projeto de Sudoku desenvolvido em Java utilizando Swing, Programação Orientada a Objetos e Maven.

---

# Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

- prática de lógica de programação
- orientação a objetos
- construção de interfaces gráficas em Java
- validação de regras de negócio
- prática com testes unitários e interface projeto (JUnit, Mockito / UI)
- feito para diversão e evolução do portfólio 

O jogo segue as regras tradicionais do Sudoku.

---

# Demonstração

## Funcionalidades

- Tabuleiro 9x9
- Interface gráfica desktop
- Validação automática
- Destaque visual para erros
- Verificação de vitória
- Reinício de partida
- Células bloqueadas
- Estrutura modular

---

# Tecnologias Utilizadas

## Linguagem

- Java 21

## Interface Gráfica

- Java Swing

## Build e Gerenciamento

- Maven

## Paradigmas

- Programação Orientada a Objetos (POO)

## Controle de Versão

- Git
- GitHub

---

# Estrutura do Projeto

```text
SudokuGame/
│
├── src/
│   └── main/
│       └── java/
│           ├── model/
│           ├── service/
│           ├── ui/
│           └── Main.java
│
├── pom.xml
└── README.md
```

---

# Arquitetura

O projeto foi dividido em camadas para facilitar manutenção e escalabilidade.

## Model

Responsável pela estrutura do tabuleiro.

```text
SudokuBoard.java
```

## Service

Responsável pelas regras de negócio.

```text
SudokuValidator.java
SudokuGenerator.java
```

## UI

Responsável pela interface gráfica.

```text
SudokuFrame.java
SudokuCell.java
```

---

# Como Executar

## Pré-requisitos

- JDK 21
- IntelliJ IDEA ou VSCode
- Maven instalado

---

## Clonar o Repositório

```bash
git clone https://github.com/robertocyanes/sudokugame.git
```

---

## Entrar na pasta

```bash
cd sudokugame
```

---

## Executar com Maven

```bash
mvn clean install
mvn exec:java
```

---

## Executar no IntelliJ

1. Abrir o projeto
2. Configurar SDK 21
3. Executar:
```text
Main.java
```

---

# Regras do Sudoku

O jogador deve preencher o tabuleiro:

- sem repetir números na linha
- sem repetir números na coluna
- sem repetir números no bloco 3x3

Números válidos:
```text
1 até 9
```

---

# Código de Acesso ao Jogo

O jogo não possui autenticação nem necessidade de login.

Para acessar:

```text
1. Clonar o projeto
2. Abrir no IntelliJ
3. Rodar Main.java
```

---

# Qualidade de Software (QA)

Este projeto segue princípios básicos de qualidade de software:

- separação de responsabilidades
- validação de entradas
- organização modular
- padronização visual
- tratamento de erros

---

# Testes Unitários

O projeto foi estruturado para permitir implementação futura de testes unitários utilizando:

- JUnit 5
- Mockito

## Possíveis cenários de teste

### SudokuValidator

- validar linha
- validar coluna
- validar bloco 3x3
- validar jogo completo

### SudokuBoard

- inserção de valores
- bloqueio de células fixas

### SudokuGenerator

- geração válida de tabuleiro

---

# Próximas Melhorias do Jogo (Muitas.😂)

- Geração aleatória de Sudoku
- Níveis de dificuldade
- Sistema de pontuação
- Cronômetro
- JavaFX
- Salvamento de partida
- Banco de dados
- API REST
- multiplayer
- Docker
- CI/CD
- GitHub Actions

---

# Conceitos Aplicados

- Encapsulamento
- Responsabilidade única
- Eventos Swing
- Estrutura MVC simplificada
- Validação de regras
- Modularização

---

# Portfólio

Este projeto faz parte do processo de evolução prática em desenvolvimento Java e engenharia de software.

---

# Autor

## Roberto César Yanes


GitHub:
https://github.com/robertocyanes
