# TP1 - Solitaire Association (Tecnologias Web)

## 🌟 Sobre o Projeto
Este é o primeiro trabalho prático (TP1) da disciplina de Tecnologias Web. O objetivo foi desenvolver um jogo de cartas baseado no clássico "Paciência", mas com uma mecânica de associação de temas. O jogo utiliza tecnologias fundamentais do desenvolvimento web: HTML, CSS e JavaScript.

---

## 🃏 Regras do Jogo

O baralho é composto por **28 cartas**, divididas em **4 temas** principais:

1.  🧚 **Contos de Fadas**
2.  🍰 **Sobremesas**
3.  📝 **Pontuações**
4.  ♟️ **Xadrez**

Cada tema possui **1 Carta Vermelha (Tema)** e **6 Cartas Azuis (Palavra)**.

### Movimentação e Empilhamento:
* **Pilhas de Paciência (Tabuleiro):** Você pode empilhar cartas desde que pertençam ao **mesmo tema**. 
* **Trava do Tema:** Se você colocar a carta vermelha (Tema) no topo de uma pilha no tabuleiro, as cartas abaixo dela ficam travadas e não podem ser movidas até que o Tema seja levado para a área superior.
* **Pilhas de Resposta (Objetivo):** Localizadas na parte superior. 
    * O espaço vazio aceita apenas a carta vermelha (Tema).
    * Após o Tema ser posicionado, as palavras correspondentes devem ser empilhadas sobre ele.
* **Vitória:** O jogo termina quando as 4 pilhas de resposta estiverem completas com suas 7 cartas cada.

---

## ⏱️ Sistema de Tempo e Recordes

* **Início:** O cronômetro começa a contar assim que o jogador vira a primeira carta do baralho.
* **Penalidade:** Caso o jogador tente realizar um movimento inválido (conectar palavras de temas diferentes ou soltar em locais não permitidos), uma penalidade de 5 segundos é adicionada ao tempo total.
* **Recorde Pessoal:** O jogo armazena o melhor tempo localmente. Caso não haja um recorde anterior, o tempo padrão a ser batido é de 03:00 (180 segundos). Os dados são salvos via `localStorage`.

---

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estrutura semântica, Drag and Drop API.
* **CSS3:** Layout com Flexbox, estilização responsiva (`object-fit`, `vw/vh`), fontes externas via Google Fonts.
* **JavaScript:** Lógica de jogo, manipulação do DOM, persistência de dados local, controle de estados e cronômetro.

---

## 🎮​ Como Rodar
1.  Certifique-se de que a pasta `img/` contenha todas as cartas e a imagem `capa.png`.
2.  Mantenha os arquivos `paciencia.html` e `estilo.css` no mesmo diretório.
3.  Abra o arquivo `paciencia.html` em qualquer navegador.

---

### 🖥️ Desenvolvedores
* **Guilherme Ulhoa Cintra de Sousa**
* **Leonardo Torres Gonçalves e Silva** 
* **Marina Rihs Matos Wang** 
