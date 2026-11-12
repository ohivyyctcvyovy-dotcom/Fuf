# GameLab 3D

GameLab 3D é uma plataforma educativa em português para aprender os fundamentos da criação de jogos, começando do zero.

## Estrutura desta versão
- Página inicial clara, responsiva e adaptada para celular.
- Trilha de cinco aulas curtas com leitura em voz alta pelo navegador.
- Laboratório 3D com personagem inicial, câmera orbital, cubos e plataformas.
- Seleção de objetos e edição de posição e escala.
- Programação por blocos demonstrativos com visualização de JavaScript.
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
- Esta é a base inicial do projeto. Próximas etapas podem adicionar joystick real, colisões, sistema de vida, inimigos com IA, Blockly integrado, vídeos e mais ferramentas de edição.
