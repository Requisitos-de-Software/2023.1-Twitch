# Observação

## 1. Introdução

A observação é uma técnica que visa observar no próprio ambiente no qual o software será implementado, de forma que as tarefas sejam observadas sem que interfiram no ambiente.

O intuito dessa técnica é que por meio da observação sejam elicitados requisitos de acordo com o que for observado e detalhado das tarefas realizadas pelo aplicativo.

## 2. Metodologia

Para a realização da técnica de elicitação de requisitos por meio da observação, foi feita uma gravação de tela afim de captar o corpotamento do usuário com o aplicativo em funcionamento para observar e verificar as funcionalidades utilizadas pelo usuário no aplicativo, e verificar possíveis necessidades.

A tela e áudio do usuário foram captadas e estão disponíveis abaixo.

## 3. Resultados

<iframe width="800" height="450" src="https://www.youtube.com/embed/9Rzo69gGBTs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Decidimos colocar um usuário que não tinha familiaridade com a Twitch, porém é usuário frequente de outras plataformas de Streaming. Como resultado da técnica de observação, foram elicitados os seguintes requisitos:

### Legendas

- OBS: Observação
- RF: Requisito Funcional
- RNF: Requisito Não Funcional  

<center>

| Identificador | Requisitos | Tipo |
| --------------| ---------- | ---- |
| OBS01 | O usuário deve ser capaz de consumir conteúdos sem se registrar na plataforma | RNF
| OBS02 | O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo | RF
| OBS03 | O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo através de um provedor de email como Gmail, Outlook | RF
| OBS04 | O usuário deve estar cadastrado e logado para acessar as funcionalidades do sistema, com exceção o acesso aos vídeos  | RNF
| OBS05 | Ao sair de uma live e voltar para a página de início, o vídeo da live em formato de Thumbnail deve estar pausada ou não existir | RF
| OBS06 | Para um novo usuário, o sistema de recomendação de Categorias deve mostrar os tipos de conteúdos que estão em alta na plataforma | RF
| OBS07 | Ao acessar "Ajuste de Conteúdo", no catálogo disponibilizado deverá ter somente a imagem do conteúdo sem um ícone de coração | RNF
| OBS08 | Ao acessar "Ajuste de Conteúdo", após o usuário selecionar as categorias que lhe interessa. O sistema deve sugerir os tipos de conteúdos voltados a sua escolha na maioria da interface | RF
| OBS09 | Ao acessar "Ajuste de Conteúdo", o usuário deve ter a opção de selecionar se deseja receber sugestões de conteúdos categorizados para adultos | RF
| OBS10 | A plataforma deve colocar um efeito Blur nos Thumbnails para cada conteúdo categorizado como adulto ou 18+ | RF
| OBS11 | A plataforma deve colocar uma etapa de confirmação, perguntado se o usuário deseja visualizar o conteúdo categorizado como adulto ou 18+| RF
| OBS12 | A barra de navegação de tipos de conteúdos deve aparecer na tela de início, mesmo estando logado  | RNF
| OBS13 | Na Barra de navegação de tipos de conteúdos deve ser adicionado o tipo Artes e Ciência | RNF
| OBS14 | A experiência do usuário na questão de sugestões de conteúdo e o tipo de disponibilidade delas deve ser melhor logado na plataforma | RNF

</center>

<h6 align = "center"> Tabela 1: Requisitos levantados utilizando a técnica da Observação. </h6>
<h6 align = "center"> Fonte: Autores </h6>

## 4. Referências

> - Engenharia de Requisitos: Software Orientado ao Negócio. **Carlos Eduardo Vazquez**, **Guilherme Siqueira Simões**
> - Observação - Exército Brasileiro. **GitHub**. Disponível em: <https://requisitos-de-software.github.io/2022.1-Exercito-Brasileiro/#/elicitacaoRequisitos/observacao>
> - Observação - Linkedin. **GitHub**. Disponível em: <https://requisitos-de-software.github.io/2022.2-LinkedIn/elicitacao/observacao/>

## 5. Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|---|---|---|---|---|
| 1.0 | 30/04/2023 | Criação e desenvolvimento do artefato | Matheus Phillipo | Rafael Nobre |

<h6 align = "center"> Tabela 2: Histórico de Versões
<br>Autor(es): Matheus
<br>Fonte: Autor(es)</h6>