## 1. Introdução

Histórias de usuário são as menores unidades de trabalho em uma estrutura ágil de desenvolvimento de software. Uma história de usuário é uma frase descritiva, simples e informal, redigida do ponto de vista de um usuário e/ou persona, que articula como um recurso de software pode gerar valor ao cliente. Utilizando-se dessa metodologia, a equipe de um programa ágil cria uma estrutura centrada na percepção do usuário, o que, em geral, resulta em um produto com funcionalidades mais úteis e melhor implementadas.

É importante citar que **histórias de usuário não são requisitos de sistema de um software**: essas histórias servem meramente para oferecer um contexto à equipe de desenvolvimento e suas iniciativas; a partir dessas histórias, a equipe sabe porque está desenvolvendo um sistema, o que está desenvolvendo para esse sistema e qual valor esse sistema gera a um cliente. É a partir dessas histórias que também é possível elicitar novos requisitos funcionais de um sistema.

## 2. Metodologia

A partir dos requisitos funcionais previamente elicitados (disponíveis em [Técnicas de Elicitação - Brainstorm](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/Brainstorm/)) pela equipe de desenvolvimento em uma reunião de Brainstorm, membros Ana Beatriz e Brunna Louise foram capazes de extrair histórias de usuário dos requsitos funcionais, seguindo a estrutura:

|**Id da User Story**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critério de aceitação**|**Id do Requisito**|
| :---: |:---: | :---: | :---: | :---:| :---: |
|USBxx|Como usuário, | quero | xxxxxxx. | Critério a ser cumprido. |RFBxx|

O Id da User Story (História de Usuário) é um código que identifica cada história de usuário aqui contida, a fim de otimizar a rastreabilidade. Seguindo esse mesmo princípio, o Id do Requisito é o mesmo Id utilizado no documento [Técnicas de Elicitação - Brainstorm](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/Brainstorm/), que foi o artefato no qual nos baseamos para extrair as histórias de usuário.

O usuário pode ser um **espectador**, ou seja, o tipo mais comum de usuário, cujo principal objetivo é assistir a e interagir com transmissões ao vivo; ou um **criador de conteúdo**, cujo principal objetivo é transmitir lives em seu canal. Um criador de conteúdo possui todas as características de um espectador, com o diferencial de produzir conteúdo para a plataforma.

A descrição do recurso é uma breve descrição de uma funcionalidade que confere valor ao cliente.

O critério de aceitação da história de usuário descreve parâmetros que devem ser cumpridos a fim de que o desejo do usuário contido na história de usuário seja satisfeito.

É importante deixar documentado que: as histórias de usuário foram escritas de forma simples e não ambígua de forma suficiente a torná-las auto-explicativas; nós, como equipe de desenvolvimento, somos também usuários e, consequentemente, clientes da plataforma Twitch e, portanto, como clientes, validamos essas histórias de usuário aqui descritas; durante a elicitação dos requisitos em uma reunião de Brainstorm, documentada no arquivo citado acima, nós, como equipe de desenvolvimento e como usuários da Twitch e, portanto, clientes da plataforma, fomos capazes de validar tanto os requisitos funcionais quanto os requisitos não funcionais elicitados; e, por fim, todas as histórias de usuário aqui descritas podem ser testadas.

Em suma:
- As histórias de usuário são auto-explicativas e não ambíguas;
- A validação das histórias de usuário foi realizada com participação de clientes da plataforma;
- A validação dos requisitos funcionais que foram base para a extração das histórias de usuário foi feita com participação de clientes da plataforma; e
- Todas as histórias de usuário podem ser testadas.
## 3. Histórias de Usuário

Serão descritas abaixo as histórias de usuário extraídas de requisitos funcionais previamente elicitados nas tabelas 1, 2 e 3.

### 3.1. Histórias de usuário relacionadas à visualização e interação com conteúdo:

|**Id da User Story**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critério de aceitação**|**Id do Requisito**|
| :---: |:---: | :---: | :---: | :---:| :---: |
| USB01 |Como usuário, | quero | poder assistir a uma live. |  | RFB01 |
| USB02 |Como usuário, | quero | quero poder assistir a um VOD (Video on Demand). |  | RFB02 |
| USB03 |Como usuário, | quero | quero poder interagir em uma live. |  | RFB03 |
| USB04 |Como usuário, | quero | poder comentar em uma live. |  | RFB04 |
| USB05 |Como usuário, | quero | poder clipar um trecho de uma live. |  | RFB05 |
| USB06 |Como usuário, | quero | poder compartilhar o link de uma live. |  | RFB07 |
| USB07 |Como usuário, | quero | poder reagir durante a transmissão. |  | RFB11 |
| USB08 |Como usuário, | quero | poder reagir durante a transmissão. |  | RFB12 |
| USB09 |Como usuário, | quero | poder utilizar bits para enviar mensagens ao streamer. |  | RFB13 |
| USB10 |Como usuário, | quero | poder denunciar uma transmissão ao vivo. |  | RFB14 |
| USB11 |Como usuário, | quero | poder denunciar mensagens de outro usuário. |  | RFB15 |
| USB12 |Como usuário, | quero | poder buscar canais/lives. |  | RFB16 |
| USB13 |Como usuário, | quero | poder consultar meu saldo de bits (Twitch Wallet). |  | RFB17 |
| USB14 |Como usuário, | quero | poder consultar meus Drops e Recompensas. |  | RFB23 |
<h6 align = "center"> Tabela 1: Histórias de Usuário relacionadas à visualização e interação com conteúdo.
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>


### 3.2. Histórias de usuário relacionadas a inscrições e pagamentos:

|**Id da User Story**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critério de aceitação**|**Id do Requisito**|
| :---: |:---: | :---: | :---: | :---:| :---: |
| USB15 |Como usuário, | quero | poder seguir um streamer. |  | RFB06 |
| USB16 |Como usuário, | quero | poder me inscrever em um canal utilizando o Amazon Prime. |  | RFB08 |
| USB17 |Como usuário, | quero | poder me inscrever em um canal pagando diretamente. |  | RFB09 |
| USB18 |Como usuário, | quero | poder presentear uma inscrição para outro usuário. |  | RFB10 |
| USB19 |Como usuário, | quero | poder consultar minhas inscrições. |  | RFB24 |
| USB20 |Como usuário, | quero | poder configurar o meu perfil. |  | RFB25 |
| USB21 |Como usuário, | quero | poder configurar minha imagem do perfil. |  | RFB26 |
| USB22 |Como usuário, | quero | poder configurar meu banner do perfil. |  | RFB27 |
| USB23 |Como usuário, | quero | poder configurar meu nome de usuário. |  | RFB28 |
| USB24 |Como usuário, | quero | poder configurar meu nome de exibição. |  | RFB29 |
| USB25 |Como usuário, | quero | poder configurar minha biografia. |  | RFB30 |
| USB26 |Como usuário, | quero | poder escolher o conjunto de emojis que irei utilizar. |  | RFB33 |
| USB27 |Como usuário, | quero | poder gerenciar as notificações da minha conta. |  | RFB34 |
| USB28 |Como usuário, | quero | poder vincular minha conta da Twitch a outras plataformas. |  | RFB35 |
<h6 align = "center"> Tabela 2: Histórias de usuário relacionadas a inscrições e pagamentos.
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>


### 3.3. Histórias de usuário relacionadas à plataforma e configurações:

|**Id da User Story**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critério de aceitação**|**Id do Requisito**|
| :---: |:---: | :---: | :---: | :---:| :---: |
| USB29 |Como usuário, | quero | poder realizar ajustes nos conteúdos sugeridos. |  | RFB36 |
| USB30 |Como usuário, | quero | poder alterar o idioma da plataforma. |  | RFB37 |
| USB31 |Como usuário, | quero | poder alterar o tema (claro/escuro) da plataforma. |  | RFB38 |
| USB32 |Como usuário, | quero | poder realizar login na plataforma. |  | RFB39 |
| USB33 |Como usuário, | quero | poder realizar logout da plataforma. |  | RFB40 |
| USB34 |Como usuário, | quero | poder desabilitar minha conta da Twitch. |  | RFB41 |
| USB35 |Como usuário, | quero | poder trocar sussurros com outros usuários |  | RFB42 |
| USB36 |Como usuário, | quero | ser capaz de personalizar o meu canal. |  | RFB43 |
| USB37 |Como usuário, | quero | ser capaz de iniciar minha transmissão. |  | RFB44 |
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
| 23/05/2023 | 1.1 | Estabelecendo padrões de codificação e adicionando documentação adicional | Brunna Louise | Ana Beatriz |

<h6 align = "center"> Tabela 4: Histórico de Versões
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>
