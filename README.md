# Caderno de Estudos 07/26
###### Projeto criado e desenvolvido conforme orientações do curso da DIO.

## 👾 CONTEXTO E OBJETIVOS:

Ele tem como objetivo desenvolver minhas habilidades em um dos meus hobbies / gostos pessoais a qual pretendo futuramente trabalhar. Essa área é a de desenvolvimento do de jogos, ou também chamada: Game Development.

Desde infância sempre gostei de criar e desenvolver projetos e agora estou focando em melhorar cada dia mais, tanto na minha profissão atual de Software Engeneering mas também nessa área de jogos.

## 📒 FONTES:

A grande maioria das minhas fontes provém de links do Youtube, de canais confiáveis e que já acompanho e já apliquei algumas metodologias e ferramentas apresentadas.

Link para o NotebookLM (também disponível no Github):
[GameDevAssist - Unity & Blender](https://notebooklm.google.com/notebook/49e7f144-ab4a-462e-afde-94b6ac9c8d6d?authuser=1)

Algumas fontes:

- [Giving Personality to Procedural Animations using Math](https://www.youtube.com/watch?v=KPoeNZZ6H4s) - Voltado principalmente a Animação e Matemática

- [Animação na Unity | Curso Gratuito de Unity](https://www.youtube.com/watch?v=ICZiqu-Yeb8) - Voltado principalmente a Desenvolvimento na Unity

- [How To PROPERLY Start Making A Game](https://www.youtube.com/watch?v=ekOp35B1Bdg) - Voltado principalmente a Game Design e Planejamento

- [Character modeling for beginners - Blender](https://www.youtube.com/watch?v=O6HQhs-gk50) - Voltado principalmente a Modelagem no Blender

## ⚙️ ENGENHARIA DE PROMPTS:

Exemplo de prompt seguindo os 8 princípios de um bom prompt mais alguns toques meus (nesse caso voltado para explicação):

⚠️ Mude o conteúdo dos blocos "## CONTENT" e "## OPTIONAL".

```shell
# [!important!] BEHAVIOR AND INTERPRETATION OF THIS PROMPT
- Interpret each block of this prompt as interconnected.
- Each block is preceded by two “##” followed by its title and ends when the next block begins.
- Each block has its specific function described immediately below its title.

## CONTEXT:
You are a highly regarded game development expert in the industry and a leading authority in several countries. You have only this one chance to explain a certain concept or topic to me in the best possible way.

## OBJECTIVE:
Your ultimate goal is to help me understand this subject; no matter how complex it may be, you will make it simple for me.

## INSTRUCTIONS:
Explain the following topic using practical examples and broad concepts:

## CONTENT
((CODE, IDEA, CONCEPT in english — explain in detail if the topic is extensive or has many nuances))

## GUIDELINES
Use clear, concise, and accessible language. I don’t want you to sugarcoat the truth; I want you to give me the real explanation, without beating around the bush.

- Keep the explanation as detailed as possible, but don’t go overboard.
- Avoid unnecessary jargon and define any specialized terms you need to use.

## OUTPUT
- If the content is very complex, break it down into logical topics to make it easier to understand.

- If the content presented is more vague or doesn’t focus on a specific subject, stick to your goal of providing a complete and professional explanation. Introduce the general topic and suggest related basic topics to start a more specific discussion. 

## EXAMPLE (if the initial #CONTENT covered is superficial)
For example: if I ask about quantum physics, explain the general concept of this subject and suggest a few other topics to cover.

## EXAMPLE (for everything)
Provide some links and sources you used to gather this information for me, and of course, verify that these sources are accurate.

## CONTENT
If any documents are attached to this message, interpret them and proceed according to the objective and persona mentioned earlier—that is, provide detailed yet concise explanations focused on helping me understand even the most complex topics. You’re an expert at explaining anything, so do it in the best way possible.

## [!important!] GUIDELINES FOR FOLLOWING MESSAGES (your next replies)
In the next messages that follow in this same conversation, I want you to maintain this same structure at the beginning of each message—in other words, I want you to continue with your goal of explaining anything to me in the best possible way.

## OPTIONAL
Translate the answer into the following language: "English"
```

## 🪄 RESULTADO DO PROMPT:

Troquei CONTENT por "game development" e OPTIONAL para "Portuguese-Brazil".

Recebi a seguinte resposta do ChatGPT (sim tudo isso é uma única mensagem):

---

### Desenvolvimento de Jogos (Game Development)

O desenvolvimento de jogos é o processo de transformar uma ideia em uma experiência interativa. Diferente de um filme, onde o espectador apenas assiste, em um jogo o jogador toma decisões e o software precisa responder a essas decisões em tempo real.

Um jogo é, essencialmente, um conjunto de sistemas trabalhando juntos:

* O jogador fornece uma entrada (pressiona um botão, move o mouse, toca na tela).
* O jogo interpreta essa entrada.
* O mundo do jogo muda de acordo com regras pré-definidas.
* O jogo exibe o resultado.
* Esse ciclo acontece dezenas ou centenas de vezes por segundo.

---

### A visão geral

Imagine que um jogo é como uma empresa.

Cada departamento possui uma responsabilidade.

| Departamento          | Equivalente no jogo |
| --------------------- | ------------------- |
| Administração         | Game Design         |
| Engenharia            | Programação         |
| Arquitetura           | Level Design        |
| Artes                 | Artistas 2D/3D      |
| Música                | Sound Design        |
| Marketing             | Publicação          |
| Controle de qualidade | QA (Testes)         |

Nenhuma dessas áreas, sozinha, cria um jogo completo.

---

### Os principais pilares

###### 1. Game Design

É o projeto do jogo.

O game designer responde perguntas como:

* Qual é o objetivo?
* Como o jogador vence?
* Como perde?
* O jogo é difícil?
* Existem fases?
* Existem inimigos?
* Existem habilidades?

Exemplo:

Mario.

O game designer decide:

* Mario pula.
* Goombas machucam.
* Cogumelos aumentam a vida.
* O jogador precisa chegar ao final.

Nada disso ainda foi programado.

São apenas regras.

---

###### 2. Programação

O programador transforma as regras em código.

Por exemplo:

O designer diz:

> "Quando o personagem encostar no inimigo, ele perde vida."

O programador escreve isso em código.

Outro exemplo:

O designer diz:

> "Se o jogador apertar espaço, ele pula."

O programador implementa essa lógica.

---

###### 3. Arte

Tudo que você vê.

Pode ser:

* personagens
* árvores
* armas
* casas
* efeitos
* menus
* ícones

Existem artistas especializados:

* Concept Artist
* Pixel Artist
* Modelador 3D
* Animador
* UI Artist

---

###### 4. Áudio

Inclui:

* música
* passos
* tiros
* vento
* explosões
* vozes

O áudio muda completamente a sensação do jogo.

Imagine Minecraft sem sons.

Ele pareceria estranho.

---

###### 5. Level Design

É o design das fases.

Não é desenhar bonito.

É criar desafios interessantes.

Por exemplo:

Em um jogo de plataforma, o level designer decide:

* onde colocar inimigos
* onde colocar plataformas
* onde esconder itens
* quando aumentar a dificuldade

---

###### 6. Testes (QA)

Nenhum jogo nasce sem bugs.

O QA procura problemas como:

* personagem atravessa parede
* jogo trava
* fase impossível
* missão não termina
* inimigo desaparece

Grandes empresas possuem centenas de testadores.

---

### O ciclo de um jogo

Praticamente todos os jogos fazem isso:

```
Iniciar jogo

Enquanto o jogo estiver aberto

    Ler comandos

    Atualizar personagens

    Atualizar inimigos

    Atualizar física

    Atualizar IA

    Tocar sons

    Renderizar tela

Fim
```

Isso acontece cerca de:

* 30 vezes por segundo
* 60 vezes por segundo
* 120 vezes por segundo

Quanto maior o FPS (Frames Per Second), mais suave parece o jogo.

---

### O que existe dentro de um jogo?

Um jogo é composto por vários sistemas.

Os principais são:

* Sistema de movimento
* Sistema de combate
* Sistema de inventário
* Sistema de IA
* Sistema de missões
* Sistema de economia
* Sistema de física
* Sistema de partículas
* Sistema de animação
* Sistema de áudio
* Sistema de salvamento
* Sistema de interface

Cada sistema é independente, mas conversa com os demais.

---

### O Game Loop

É o coração do jogo.

Imagine:

Você aperta:

```
W
```

O computador faz:

```
Receber tecla

↓

Mover personagem

↓

Atualizar câmera

↓

Atualizar colisão

↓

Atualizar animação

↓

Desenhar nova imagem

↓

Esperar próximo frame

↓

Repetir
```

Esse processo pode ocorrer 60 vezes por segundo.

---

### Como um personagem anda?

Parece simples.

Na realidade acontece algo parecido com:

```
Jogador apertou W?

↓

Sim

↓

Adicionar velocidade

↓

Mover personagem

↓

Existe parede?

↓

Sim

↓

Cancelar movimento

↓

Não

↓

Aplicar animação

↓

Atualizar câmera
```

Até andar envolve várias etapas.

---

### Física

Motores de física simulam o mundo.

Eles calculam:

* gravidade
* colisões
* velocidade
* impulso
* atrito

Exemplo:

Uma caixa cai.

O jogo calcula:

```
Gravidade

↓

Velocidade

↓

Nova posição

↓

Colidiu com chão?

↓

Parar movimento
```

Motores populares incluem PhysX, Havok e Bullet.

---

### Inteligência Artificial (IA)

A IA em jogos normalmente não "pensa" como uma pessoa.

Ela segue regras.

Exemplo simples:

```
Se jogador estiver perto

↓

Atacar

Senão

↓

Patrulhar
```

Exemplo mais complexo:

```
Ver jogador

↓

Existe cobertura?

↓

Sim

↓

Ir para cobertura

↓

Recarregar

↓

Atacar
```

Isso pode ser implementado com máquinas de estados, árvores de comportamento (*behavior trees*) ou sistemas baseados em objetivos.

---

### Renderização

Renderizar significa desenhar a imagem.

O computador precisa calcular:

* iluminação
* sombras
* reflexos
* materiais
* texturas
* partículas
* transparência

Depois envia tudo para a GPU.

A GPU transforma cálculos em pixels na tela.

---

### Motores de jogo (Game Engines)

Uma *game engine* é um conjunto de ferramentas prontas que acelera o desenvolvimento. Em vez de criar tudo do zero (renderização, física, áudio, editor de cenas), você usa uma base já construída.

Os motores mais conhecidos são:

* **Unity** — Muito usado para jogos 2D, 3D, mobile e por desenvolvedores independentes. Usa C###.
* **Unreal Engine** — Muito forte em gráficos de alta qualidade e jogos AAA. Usa C++ e Blueprints (programação visual).
* **Godot** — Código aberto, leve e excelente para aprender. Usa GDScript (semelhante a Python), além de C### e C++.

Aprender uma engine é importante, mas entender os conceitos por trás dela é ainda mais valioso: os princípios de programação, física, renderização e design se aplicam a praticamente qualquer engine.

---

### Como nasce um jogo?

Um projeto costuma seguir estas etapas:

1. Ideia.
2. Definição das mecânicas.
3. Protótipo simples para validar a diversão.
4. Produção de arte, código, fases e áudio.
5. Testes e correção de bugs.
6. Otimização de desempenho.
7. Lançamento.
8. Atualizações e suporte.

Projetos profissionais raramente seguem uma linha totalmente reta; é comum voltar etapas para ajustar mecânicas ou resolver problemas descobertos durante os testes.

---

### O que um programador de jogos realmente faz?

A maior parte do tempo não é criando efeitos visuais impressionantes.

É resolvendo problemas como:

* corrigir bugs;
* melhorar desempenho;
* implementar novas mecânicas;
* integrar sistemas;
* criar ferramentas para a equipe;
* manter o código organizado e fácil de evoluir.

Programação de jogos é, acima de tudo, engenharia de software aplicada a sistemas em tempo real.

---

### Habilidades importantes

Além de aprender uma engine, vale desenvolver:

* Lógica de programação.
* Estruturas de dados e algoritmos.
* Matemática (vetores, trigonometria, álgebra linear).
* Física básica.
* Programação orientada a objetos e, mais tarde, arquitetura de software.
* Controle de versão (Git).
* Otimização de desempenho.
* Trabalho em equipe.

Esses conhecimentos permanecem úteis mesmo quando as ferramentas mudam.

---

### Um caminho de estudos recomendado

Se você está começando, esta sequência costuma funcionar muito bem:

1. Lógica de programação.
2. Uma linguagem (C# para Unity ou C++ para Unreal).
3. Programação orientada a objetos.
4. Estruturas de dados e algoritmos.
5. Matemática para jogos (vetores, matrizes, transformações).
6. Escolher uma engine (Unity, Unreal ou Godot).
7. Criar jogos pequenos (Pong, Breakout, Snake, Tetris).
8. Aprender IA, física e otimização.
9. Participar de *game jams*.
10. Desenvolver um portfólio.

Começar com projetos pequenos acelera muito mais o aprendizado do que tentar criar um MMORPG como primeiro projeto.

---

### Conceitos relacionados para aprofundar

Depois desta visão geral, estes são alguns dos tópicos mais importantes para estudar em profundidade:

* Arquitetura de jogos (*Game Architecture*).
* Game Loop e gerenciamento de tempo (*delta time*).
* Componentes e Entity Component System (ECS).
* Matemática para jogos (vetores, matrizes e quaternions).
* Física e detecção de colisões.
* Renderização gráfica e pipeline da GPU.
* Inteligência Artificial para jogos.
* Programação de shaders.
* Redes para jogos multiplayer.
* Otimização de CPU e GPU.
* Padrões de projeto (*Design Patterns*) aplicados a jogos.

---

### Fontes confiáveis

Se você quiser estudar pelos materiais mais respeitados da indústria, estas são excelentes referências:

* [Unity Learn](https://learn.unity.com/?utm_source=chatgpt.com)
* [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine?utm_source=chatgpt.com)
* [Godot Documentation](https://docs.godotengine.org/?utm_source=chatgpt.com)
* [Game Programming Patterns (livro gratuito)](https://gameprogrammingpatterns.com/?utm_source=chatgpt.com)
* [LearnOpenGL](https://learnopengl.com/?utm_source=chatgpt.com)
* [GDC (Game Developers Conference)](https://www.gdcvault.com/?utm_source=chatgpt.com)
* [Game AI Pro (artigos e livros)](https://www.gameaipro.com/?utm_source=chatgpt.com)

Essas fontes são amplamente utilizadas por desenvolvedores independentes e grandes estúdios, e cobrem desde os fundamentos até técnicas avançadas. Nas próximas respostas desta conversa, manterei essa estrutura didática, organizando os assuntos por tópicos, usando exemplos práticos, definindo termos importantes e indicando fontes confiáveis quando elas ajudarem a aprofundar o estudo.
