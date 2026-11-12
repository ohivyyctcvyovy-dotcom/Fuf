# GameLab 3D

GameLab 3D é uma plataforma educativa em português para aprender os fundamentos da criação de jogos, começando do zero.

## Estrutura desta versão
- Identidade visual vermelho e preto, com verde para acertos, vermelho para erros e amarelo restrito às áreas de programação.
- Trilha de cinco aulas curtas com leitura em voz alta pelo navegador.
- Laboratório 3D aprimorado com personagem detalhado, iluminação e sombras, câmera orbital e controles de transformação visual (mover, girar e escala).
- Seleção de objetos, edição de posição/rotação/escala e destaque visual do item selecionado.
- Programação por blocos com execução de ações no cenário e visualização de JavaScript (ainda não é um compilador completo).
- Quiz interativo com feedback.
- Salvamento local de projetos e progresso.
- PWA com cache básico da estrutura principal.

## Tecnologias
- HTML, CSS e JavaScript.
- Three.js para a cena 3D.
- Web Speech API para leitura em voz alta.
- LocalStorage para progresso e projetos.

## Publicação
O projeto é estático e pode ser publicado pelo GitHub Pages usando a branch `main` e a pasta `/(root)`, ou pela branch de publicação configurada nas opções do repositório.

## Observações importantes
- O motor 3D é carregado de uma CDN; a primeira abertura do editor 3D precisa de conexão com a internet.
- O cache offline guarda a estrutura principal do site, mas o editor 3D e suas bibliotecas externas podem não funcionar offline até que sejam disponibilizadas localmente.
- A programação por blocos desta etapa executa ações demonstrativas no cenário. Ainda não é um compilador completo de jogos nem um editor de scripts arbitrários.
- Esta é a base inicial do projeto. Próximas etapas: colisões físicas mais completas, Blockly integrado, vídeos de aula, animações e mais ferramentas de edição. O joystick atual oferece controles direcionais na tela.
