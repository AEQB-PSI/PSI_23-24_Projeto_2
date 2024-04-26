# Projeto 1 de Programação e Sistemas de Informação

Objetivo: Criar um programa para manipular e analisar uma série de dados sobre jogos da plataforma Steam.

O programa deve ler um ficheiro CSV (*comma-separated values*). Está disponível neste repositório o ficheiro [jogos.csv](jogos.csv), que devem usar para testar o projeto. Este ficheiro contém uma série de campos com informação sobre videojogos disponíveis na Steam, nomeadamente:

*   **ID** - ID do jogo
*   **Name** - Nome do jogo
*   **ReleaseDate** - Data de lançamento
*   **RequiredAge** - Idade mínima para jogar
*   **DLCCount** - Nº de DLCs lançados
*   **Metacritic** - Nota no Metacritic (0 a 100)
*   **MovieCount** - Nº de *trailers*
*   **RecommendationCount** - Nº de recomendações
*   **ScreenshotCount** - Nº de capturas de ecrã
*   **Owners** - Nº de pessoas que têm o jogo
*   **NumberOfPlayers** - Nº de pessoas que efetivamente jogaram o jogo
*   **AchievementCount** - Nº de *achievements*
*   **ControllerSupport** - Suporte para controlador (*True* ou *False*)
*   **PlatformWindows** - Suporte para Windows (*True* ou *False*)
*   **PlatformLinux** - Suporte para Linux (*True* ou *False*)
*   **PlatformMac** - Suporte para Mac (*True* ou *False*)
*   **CategorySinglePlayer** - Suporte para *singleplayer* (*True* ou *False*)
*   **CategoryMultiplayer** - Suporte para *multiplayer* (*True* ou *False*)
*   **CategoryCoop** - Suporte para *multiplayer* cooperativo (*True* ou
    *False*)
*   **CategoryIncludeLevelEditor** - Inclui editor de níveis (*True* ou
    *False*)
*   **CategoryVRSupport** - Suporte para VR (*True* ou *False*)
*   **SupportURL** - Website de suporte/ajuda do jogo
*   **AboutText** - Descrição do jogo
*   **HeaderImage** - URL da imagem do jogo
*   **Website** - Website do jogo

Cada linha do ficheiro corresponde a um jogo, exceto a primeira linha, que indica o nome dos campos (cabeçalho).

## Passo 1: Iniciar o programa e efetuar pesquisas (5v)

-  O nome do ficheiro deve ser dado como 1º argumento na linha de comandos. Antes do programa propriamente dito começar, é preciso validar este ficheiro. Caso seja inválido, deve ser apresentada uma mensagem de erro apropriada, após a qual o programa termina. Se o ficheiro for válido, o programa pode prosseguir, lendo o mesmo.
-  Durante a leitura do ficheiro, cada linha deve corresponder à instanciação de um objeto do tipo **Jogo**, que deve ser guardado numa coleção contendo todos os jogos listados. A classe **Jogo** deve ter todos os campos presentes no ficheiro CSV:
  * Campos númericos são do tipo **int**
  * Campos com valores *True* ou *False* são representados pelo tipo **bool**
  * Campos de texto devem ser guardados como **string**
  * Campos que contenham uma data devem usar [DateTime](https://learn.microsoft.com/pt-pt/dotnet/api/system.datetime?view=net-8.0)
  * Campos com endereços URL devem usar a classe [Uri](https://learn.microsoft.com/pt-pt/dotnet/api/system.uri?view=net-8.0)
- Após a leitura e validação do ficheiro, o menu principal do programa deve conter as seguintes opções:
  1. Efetuar uma pesquisa
  2. Mostrar informação de um jogo
  3. Sair
- Se o utilizador selecionar a opção 1, deverão surgir as seguintes opções:
  1. Indicar critério de ordenação
  3. Realizar pesquisa
  4. Voltar
- Se o utilizador selecionar a opção 1, devem ser disponibilizados os seguintes critérios:
  *   Por ID (ascendente)
  *   Por nome (ascendente, por ordem alfabética)
  *   Por data de lançamento (descendente, do mais recente para o mais antigo)
  *   Por número de DLCs (descendente)
  *   Por nota no Metacritic (descendente)
  *   Por número de recomendações (descendente)
  *   Por número de pessoas que têm o jogo (descendente)
  *   Por número de pessoas que efetivamente jogaram ao jogo (descendente)
  *   Por número de *achievements* (descendente)
- Por omissão, a ordenação é feita por ID. Após especificado o critério de ordenação, o programa deve voltar ao menu anterior.

## Passo 2: Mostrar informação de um jogo (5v)

- 

## Passo 3: Diagrama UML (5v)

- 

## Passo 4: Relatório (5v)

- 

## Passo Extra: Seguir o padrão MVC (5v) 

- É preferível seguirem este padrão desde o início do desenvolvimento do projeto, mas podem adaptar o código, se decidirem realizar este passo mais tarde.
- Podem resolver o exercício 4 da aula 10 para praticar.

## Entrega

- Repositório no GitHub **privado**
  - Ir a **Definições** -> **Colaboradores** -> **Adicionar pessoas** -> Pesquisar pelo nome do professor (Manuel Geraldes) e selecionar
  - Meter elementos do grupo e link do repositório [nesta tabela](https://docs.google.com/spreadsheets/d/1DrdGnICVAA8q9bs9_LAURFKoReAO7jJGB8qqvUWacL0/edit?usp=drive_link) (Separador **Projeto 2**).
- Conteúdo:
  - Ficheiros .gitignore e .gitattributes
  - Pasta com ficheiros do projeto
  - Solução do projeto
  - Ficheiro README.md com identificação dos alunos e relatório
  - Imagem com diagrama UML do projeto
- Data limite: 
