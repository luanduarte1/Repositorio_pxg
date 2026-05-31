# Organização PxG

Aplicativo em HTML para organizar personagens, rotinas e quests do PokeXGames. O projeto roda direto no navegador a partir do arquivo `index.html`, sem precisar instalar dependências.

## O que o aplicativo faz

- Cadastra personagens com nome, clã, nível, nível NW, profissão, especialização e nível de profissão.
- Mostra os personagens em cards no painel principal e também em um menu lateral retrátil e redimensionável.
- Usa cores nas bordas para representar faixas de nível dos personagens.
- Exibe ícones dos clãs ao lado dos nomes dos personagens.
- Permite ordenar personagens e cards manualmente.
- Exporta e importa os dados em JSON para usar o mesmo progresso em outra máquina.

## Rotinas

- Permite criar rotinas personalizadas, diárias, semanais e mensais.
- Cada rotina pode ter requisitos de nível, nível NW e profissão.
- Mostra personagens elegíveis para cada rotina.
- Controla o tempo restante até a rotina ficar disponível novamente.
- Pode exibir tarefas livres nos cards dos personagens.

## Quests

- Permite criar quests com requisitos de nível e nível NW.
- Cada quest pode ser dividida em seções de spoiler.
- Cada seção tem checkbox de progresso individual.
- Seções concluídas ficam destacadas em verde claro.
- Permite inserir coordenadas no texto do spoiler; elas aparecem destacadas com botão para copiar.
- Mostra quais personagens podem iniciar a quest conforme os requisitos.
- Oculta personagens que já concluíram a quest, mantendo a opção de reverter a conclusão no menu da quest.
- Permite atrelar rotinas a seções de quest, criando a rotina automaticamente quando a seção ou a quest for concluída.

## Como usar

Abra o arquivo `index.html` em um navegador moderno. Os dados ficam salvos no armazenamento local do navegador, e podem ser levados para outra máquina usando os botões de exportar e importar JSON.
