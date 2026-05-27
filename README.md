# Detetive Games – Jogo Digital de Investigação em VisualG

## Descrição do Projeto

O **Detetive Games** é um jogo digital de investigação desenvolvido em **Portugol utilizando o VisualG**, inspirado nos clássicos jogos de mistério e resolução de crimes.

O jogador assume o papel do detetive **Constantine**, um investigador experiente responsável por solucionar assassinatos através da coleta de pistas, exploração de cenários e interrogatório de suspeitos.

O jogo possui três cenários principais:

* Casa Branca
* Navio
* Castelo

Cada mapa apresenta diferentes personagens, salas, evidências e acontecimentos relacionados ao crime investigado.

O principal objetivo do projeto é aplicar conceitos de **lógica de programação** no desenvolvimento de uma experiência investigativa interativa, explorando raciocínio lógico, análise de pistas e tomada de decisões.

---

# Documentação Técnica

## Linguagem Utilizada

* Portugol (VisualG)

---

# Estruturas Aplicadas

## Entrada e Saída de Dados

O jogo utiliza comandos como:

* `leia`
* `escreva`
* `escreval`

Esses comandos são responsáveis pela interação entre o jogador e o sistema, permitindo escolhas, diálogos, interrogatórios e navegação pelos ambientes.

---

## Estruturas Condicionais

Foram utilizadas estruturas como:

* `se ... entao ... senao`
* `escolha ... caso`

As condicionais controlam:

* progresso da investigação;
* respostas dos interrogatórios;
* desbloqueio de pistas;
* mudanças de cenário;
* identificação do assassino;
* eventos narrativos.

---

## Laços de Repetição

O projeto utiliza estruturas como:

* `enquanto ... faca`
* `para ... faca`

Os laços são utilizados para:

* controle dos menus;
* movimentação entre salas;
* repetição de diálogos;
* sistema de exploração;
* funcionamento contínuo da investigação.

---

## Modularização

O código foi dividido em diversos procedimentos e funções para melhorar a organização do sistema.

Exemplos de módulos presentes no projeto:

* `Tela_Inicial`
* `Mapa_CasaBranca`
* `Mapa_Navio`
* `Mapa_Castelo`
* `Sistema_Interrogatorio`
* `Coleta_Pistas`

Essa divisão facilita a manutenção do código e melhora a estrutura lógica do projeto.

---

## Variáveis Utilizadas

O sistema utiliza variáveis dos tipos:

* inteiro;
* lógico;
* caractere;
* real.

As variáveis controlam:

* progresso da investigação;
* pistas coletadas;
* suspeitos;
* movimentação do jogador;
* estados do jogo;
* decisões tomadas.

Exemplos:

* `pistas_encontradas`
* `suspeito`
* `mapa_atual`
* `investigacao_concluida`

---

# Lógica Utilizada

O jogo segue uma estrutura narrativa baseada em investigação e resolução de mistérios.

Inicialmente, o jogador escolhe ou inicia um dos cenários investigativos disponíveis. Durante a gameplay, o sistema permite:

1. Exploração dos ambientes;
2. Coleta de evidências;
3. Interrogatório de personagens;
4. Análise de pistas;
5. Identificação do assassino.

Cada cenário apresenta diferentes acontecimentos e suspeitos, exigindo observação e raciocínio lógico do jogador.

As escolhas realizadas durante a investigação influenciam diretamente no andamento da narrativa e na conclusão do caso.

---

# Cenários do Jogo

## Casa Branca

O Presidente Martin Roosevelt é encontrado assassinado dentro da Casa Branca. O jogador deve investigar testemunhas, analisar evidências e descobrir os segredos escondidos pelo Vice-Presidente e pela Primeira-Dama.

---

## Navio

Durante uma viagem no luxuoso cruzeiro Royal Caribe, o capitão do navio é assassinado. O detetive precisa investigar passageiros e tripulantes antes que o navio chegue ao destino.

---

## Castelo

Um importante lorde da realeza é encontrado morto em um antigo castelo. O jogador deve descobrir o culpado em meio a traições, mentiras e conspirações da corte.

---

# Mecânicas do Sistema

O projeto possui mecânicas como:

* exploração de ambientes;
* coleta de pistas;
* análise de objetos;
* diálogos interativos;
* interrogatórios;
* resolução de enigmas;
* dedução lógica.

Essas mecânicas criam uma experiência investigativa imersiva e desafiadora.

---

# Limitações Conhecidas

* O jogo funciona apenas no ambiente VisualG;
* O sistema é totalmente textual;
* Algumas investigações seguem fluxo linear;
* Não existe sistema de salvamento;
* Certos eventos possuem respostas pré-definidas.

---

# Manual de Utilização

## Passo 1 – Instalar o VisualG

Baixe e instale o VisualG no computador.

---

## Passo 2 – Abrir os Arquivos do Projeto

1. Abra o VisualG;
2. Clique em **Arquivo → Abrir**;
3. Selecione o arquivo `.ALG` do projeto.

---

## Passo 3 – Executar o Projeto

Para iniciar o jogo:

* Clique em **Executar → Rodar Algoritmo**
* Ou pressione **F9**

---

## Passo 4 – Jogar

Durante a gameplay:

* explore os ambientes;
* investigue pistas;
* converse com suspeitos;
* analise informações;
* descubra o assassino.

---

# Estrutura do Repositório

```bash
DetetiveGames
├── DETETIVE_GAMES.ALG
├── README.md
└── assets/
```

---

# Integrantes do Grupo

* Nataly Fernanda Rocha Almeida
* Arthur Mendes Lima Dutra
* Bryan Mian Marques Palma

### Orientador

* Prof. Dr. Maxwell Gomes Silva

---

# Requisitos Atendidos

✔ Entrada e saída de dados
✔ Estruturas condicionais
✔ Laços de repetição
✔ Modularização com procedimentos
✔ Sistema investigativo
✔ Exploração de cenários
✔ Interação com personagens
✔ Documentação técnica
✔ Estrutura pronta para GitHub

---

# Considerações Finais

O projeto **Detetive Games** foi desenvolvido com foco no aprendizado de lógica de programação e na criação de uma experiência investigativa interativa utilizando o VisualG.

O jogo combina narrativa, exploração e raciocínio lógico, permitindo que o jogador participe ativamente da resolução dos mistérios apresentados. Além do entretenimento, o projeto estimula habilidades como observação, interpretação e tomada de decisões, demonstrando a aplicação prática dos conceitos estudados em programação.
