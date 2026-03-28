# Simulação de Jogo de Dominó em C++

## Descrição do Projeto

Este projeto consiste no desenvolvimento de uma simulação de um jogo de dominó utilizando a linguagem C++, estruturado seguindo o padrão de separação em camadas (Model e Controller).

O sistema implementa a lógica do jogo, permitindo a inicialização de partidas, controle de jogadas e gerenciamento do fluxo do jogo por meio de um menu interativo.

O objetivo do projeto é aplicar conceitos de programação estruturada, modularização e organização de código em múltiplos arquivos.

---

## Estrutura do Projeto

O sistema está dividido em múltiplos arquivos para melhor organização:

* **Main (`Dom_JJIB_Projeto.cpp`)**

  * Responsável por iniciar o sistema
  * Chama a função principal do menu

* **Model (`Dom_JJIB_Model.cpp`)**

  * Contém a lógica do jogo
  * Representação das peças de dominó
  * Regras e estados da partida

* **Controller (`Dom_JJIB_Controller.cpp`)**

  * Gerencia a interação com o usuário
  * Controla o fluxo do jogo
  * Integra o Model com a interface (terminal)

---

## Funcionalidades

* Inicialização do jogo de dominó
* Menu interativo
* Controle de jogadas
* Gerenciamento de peças
* Execução da lógica do jogo

---

## Funcionamento

1. O programa inicia chamando a função `inicializaMenu()`
2. O usuário interage com o menu no terminal
3. O Controller gerencia as ações escolhidas
4. O Model executa a lógica do jogo
5. O estado do jogo é atualizado continuamente

---

## Exemplo de Execução

### Inicialização:

```id="g7h29f"
Inicializando jogo de domino...
Carregando menu...
```

### Menu:

```id="l2k91a"
1 - Iniciar jogo
2 - Regras
3 - Sair
```

---

## Observações Importantes

* O projeto é executado via terminal
* A organização em múltiplos arquivos melhora a modularidade
* O sistema segue uma separação de responsabilidades (Model/Controller)
* O uso de bibliotecas padrão permite manipulação de tempo e entrada/saída

---

## Possíveis Melhorias

* Implementar interface gráfica
* Adicionar modo multiplayer
* Melhorar inteligência artificial dos jogadores
* Implementar persistência de partidas
* Melhorar validação de entradas

---

## Conceitos Praticados

* Programação em C++
* Modularização de código
* Separação de responsabilidades (Model/Controller)
* Estruturação de projetos
* Simulação de jogos
* Lógica de programação
