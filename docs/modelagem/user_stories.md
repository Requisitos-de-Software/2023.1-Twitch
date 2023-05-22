## 1. Introdução

Histórias de usuário são as menores unidades de trabalho em uma estrutura ágil de desenvolvimento de software. Uma história de usuário é uma frase descritiva, simples e informal, redigida do ponto de vista de um usuário e/ou persona, que articula como um recurso de software pode gerar valor ao cliente. Utilizando-se dessa metodologia, a equipe de um programa ágil cria uma estrutura centrada na percepção do usuário, o que, em geral, resulta em um produto com funcionalidades mais úteis e melhor implementadas.

É importante citar que **histórias de usuário não são requisitos de sistema de um software**: essas histórias servem meramente para oferecer um contexto à equipe de desenvolvimento e suas iniciativas; a partir dessas histórias, a equipe sabe porque está desenvolvendo um sistema, o que está desenvolvendo para esse sistema e qual valor esse sistema gera a um cliente. É a partir dessas histórias que também é possível elicitar novos requisitos funcionais de um sistema.

## 2. Metodologia

A partir dos requisitos funcionais previamente elicitados (disponíveis em [Técnicas de Elicitação - Brainstorm](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/Brainstorm/)) pela equipe de desenvolvimento em uma reunião de Brainstorm, membros Ana Beatriz e Brunna Louise foram capazes de extrair histórias de usuário dos requsitos funcionas, seguindo a estrutura:

|**Id do Requisito**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critério de aceitação**|
| :---: |:---: | :---: | :---: | :---:|
|RFBxx|Como usuário, | quero | xxxxxxx. |  |

O Id do Requisito é o mesmo Id utilizado no documento [Técnicas de Elicitação - Brainstorm](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/Brainstorm/), que foi essencial para a extração de histórias de usuário.

O usuário pode ser um **espectador**, ou seja, o tipo mais comum de usuário, cujo principal objetivo é assistir a e interagir com transmissões ao vivo; ou um **criador de conteúdo**, cujo principal objetivo é transmitir lives em seu canal. Um criador de conteúdo possui todas as características de um espectador, com o diferencial de produzir conteúdo para a plataforma.

A descrição do recurso é uma breve descrição de uma funcionalidade que confere valor ao cliente.

O critério de aceitação para a história de usuário descreve parâmetros que devem ser cumpridos a fim de que o desejo do usuário contido na história de usuário seja satisfeito.

## 3. Histórias de Usuário

Serão descritas abaixo as histórias de usuário extraídas de requisitos funcionais previamente elicitados nas tabelas 1, 2 e 3.

### 3.1. Histórias de usuário relacionadas à visualização e interação com conteúdo:

|**Id do Requisito**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critérios de Aceitação** |
|:---: | :---: | :---: | :---: | :---: |
| RFB01 |Como usuário, | quero | poder assistir a uma live. |
| RFB02 |Como usuário, | quero | quero poder assistir a um VOD (Video on Demand). |
| RFB03 |Como usuário, | quero | quero poder interagir em uma live. |
| RFB04 |Como usuário, | quero | poder comentar em uma live. |
| RFB05 |Como usuário, | quero | poder clipar um trecho de uma live. |
| RFB07 |Como usuário, | quero | poder compartilhar o link de uma live. |
| RFB11 |Como usuário, | quero | poder reagir durante a transmissão. |
| RFB12 |Como usuário, | quero | poder reagir durante a transmissão. |
| RFB13 |Como usuário, | quero | poder utilizar bits para enviar mensagens ao streamer. |
| RFB14 |Como usuário, | quero | poder denunciar uma transmissão ao vivo. |
| RFB15 |Como usuário, | quero | poder denunciar mensagens de outro usuário. |
| RFB16 |Como usuário, | quero | poder buscar canais/lives. |
| RFB17 |Como usuário, | quero | poder consultar meu saldo de bits (Twitch Wallet). |
| RFB23 |Como usuário, | quero | poder consultar meus Drops e Recompensas. |
<h6 align = "center"> Tabela 1: Histórias de Usuário relacionadas à visualização e interação com conteúdo.
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>


### 3.2. Histórias de usuário relacionadas a inscrições e pagamentos:

|**Id do Requisito**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critérios de Aceitação** |
|:---: | :---: | :---: | :---: | :---: |
| RFB06 |Como usuário, | quero | poder seguir um streamer. |
| RFB08 |Como usuário, | quero | poder me inscrever em um canal utilizando o Amazon Prime. |
| RFB09 |Como usuário, | quero | poder me inscrever em um canal pagando diretamente. |
| RFB10 |Como usuário, | quero | poder presentear uma inscrição para outro usuário. |
| RFB24 |Como usuário, | quero | poder consultar minhas inscrições. |
| RFB25 |Como usuário, | quero | poder configurar o meu perfil. |
| RFB26 |Como usuário, | quero | poder configurar minha imagem do perfil. |
| RFB27 |Como usuário, | quero | poder configurar meu banner do perfil. |
| RFB28 |Como usuário, | quero | poder configurar meu nome de usuário. |
| RFB29 |Como usuário, | quero | poder configurar meu nome de exibição. |
| RFB30 |Como usuário, | quero | poder configurar minha biografia. |
| RFB33 |Como usuário, | quero | poder escolher o conjunto de emojis que irei utilizar. |
| RFB34 |Como usuário, | quero | poder gerenciar as notificações da minha conta. |
| RFB35 |Como usuário, | quero | poder vincular minha conta da Twitch a outras plataformas. |
<h6 align = "center"> Tabela 2: Histórias de usuário relacionadas a inscrições e pagamentos.
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>


### 3.3. Histórias de usuário relacionadas à plataforma e configurações:

|**Id do Requisito**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critérios de Aceitação** |
|:---: | :---: | :---: | :---: | :---: |
| RFB36 |Como usuário, | quero | poder realizar ajustes nos conteúdos sugeridos. |
| RFB37 |Como usuário, | quero | poder alterar o idioma da plataforma. |
| RFB38 |Como usuário, | quero | poder alterar o tema (claro/escuro) da plataforma. |
| RFB39 |Como usuário, | quero | poder realizar login na plataforma. |
| RFB40 |Como usuário, | quero | poder realizar logout da plataforma. |
| RFB41 |Como usuário, | quero | poder desabilitar minha conta da Twitch. |
| RFB42 |Como usuário, | quero | poder trocar sussurros com outros usuários |
| RFB43 |Como usuário, | quero | ser capaz de personalizar o meu canal. |
| RFB44 |Como usuário, | quero | ser capaz de iniciar minha transmissão. |
<h6 align = "center"> Tabela 3: Histórias de usuário relacionadas à plataforma e configurações.
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>

## 4. Referências

> REHKOPF, Max. *Histórias de usuários com exemplos e um template*. Atlassian. Disponível no [link](https://www.atlassian.com/br/agile/project-management/user-stories). Acesso em 22 de maio de 2023.

## Histórico de Versões

A Tabela 4 registra o histórico de versão desse documento.

|**Data** | **Versão** | **Descrição** | **Autor** | **Revisor** |
|:---: | :---: | :---: | :---: | :---: |
| 22/05/2023 | 1.0 | Primeira Versão do artefato de User Stories (Histórias de Usuário) | Ana Beatriz, Brunna Louise | - |

<h6 align = "center"> Tabela 4: Histórico de Versões
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>