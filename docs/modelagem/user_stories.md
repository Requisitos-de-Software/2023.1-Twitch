## 1. Introdução

Histórias de usuário são as menores unidades de trabalho em uma estrutura ágil de desenvolvimento de software. Uma história de usuário é uma frase descritiva, simples e informal, redigida do ponto de vista de um usuário e/ou persona, que articula como um recurso de software pode gerar valor ao cliente. Utilizando-se dessa metodologia, a equipe de um programa ágil cria uma estrutura centrada na percepção do usuário, o que, em geral, resulta em um produto com funcionalidades mais úteis e melhor implementadas.

É importante citar que **histórias de usuário não são requisitos de sistema de um software**: essas histórias servem meramente para oferecer um contexto à equipe de desenvolvimento e suas iniciativas; a partir dessas histórias, a equipe sabe porque está desenvolvendo um sistema, o que está desenvolvendo para esse sistema e qual valor esse sistema gera a um cliente. É a partir dessas histórias que também é possível elicitar novos requisitos funcionais de um sistema.

## 2. Metodologia

A partir dos requisitos funcionais previamente elicitados (disponíveis em [Técnicas de Elicitação - Brainstorm](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/Brainstorm/)) pela equipe de desenvolvimento em uma reunião de Brainstorm, membros Ana Beatriz e Brunna Louise, em uma reunião, foram capazes de extrair histórias de usuário dos requsitos funcionais. Nessa reunião, Ana Beatriz assumiu papel de cliente (Product Owner) e Brunna Louise assumiu papel de integrante da equipe de desenvolvimento. As histórias de usuário extraídas apresentam a seguinte a estrutura:

|**Id da User Story**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critério de aceitação**|**Id do Requisito**|
| :---: |:---: | :---: | :---: | :---:| :---: |
|USBxx|Como usuário, | quero | xxxxxxx. | Critério a ser cumprido. |RFBxx|

O Id da User Story (História de Usuário) é um código que identifica cada história de usuário aqui contida, a fim de otimizar a rastreabilidade. Seguindo esse mesmo princípio, o Id do Requisito é o mesmo Id utilizado no documento [Técnicas de Elicitação - Brainstorm](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/Brainstorm/), que foi o artefato no qual nos baseamos para extrair as histórias de usuário.

O usuário pode ser um **espectador**, ou seja, o tipo mais comum de usuário, cujo principal objetivo é assistir a e interagir com transmissões ao vivo; ou um **criador de conteúdo**, cujo principal objetivo é transmitir lives em seu canal. Um criador de conteúdo possui todas as características de um espectador, com o diferencial de produzir conteúdo para a plataforma.

A descrição do recurso é uma breve descrição de uma funcionalidade que confere valor ao cliente.

O critério de aceitação da história de usuário descreve parâmetros que devem ser cumpridos a fim de que o desejo do usuário contido na história de usuário seja satisfeito. Foi de extrema importância a participação de um cliente para estabelecer esses critérios.

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
| USB01 |Como usuário, | quero | poder assistir a uma live. | - O usuário consegue encontrar e selecionar uma live para assistir.</br> - O vídeo da live é reproduzido corretamente e em tempo real.</br> - O usuário pode ajustar a qualidade do vídeo conforme sua preferência.</br> - Os controles de reprodução (pausar, reproduzir, avançar, retroceder) funcionam corretamente.| RFB01 |
| USB02 |Como usuário, | quero | quero poder assistir a um VOD (Video on Demand). | - O usuário pode acessar os VODs disponíveis para um determinado canal.</br> - O usuário pode selecionar e reproduzir um VOD escolhido.</br> - O vídeo do VOD é reproduzido corretamente e em alta qualidade. </br> - Os controles de reprodução (pausar, reproduzir, avançar, retroceder) funcionam corretamente. | RFB02 |
| USB03 |Como usuário, | quero | quero poder interagir em uma live. |- O usuário pode ver e interagir com o chat ao vivo durante a transmissão.</br> - O usuário pode ver os emotes disponíveis e utilizá-los no chat.</br> - O usuário pode ver as notificações de ações dos outros espectadores (follows, subscrições, doações, etc.).</br> - O usuário pode ver o número de espectadores e o contador de visualizações da live. | RFB03 |
| USB04 |Como usuário, | quero | poder comentar em uma live. |- O usuário pode digitar e enviar mensagens no chat da live.</br> - As mensagens do usuário são exibidas corretamente no chat em tempo real.</br> - O usuário pode visualizar as mensagens anteriores do chat. | RFB04 |
| USB05 |Como usuário, | quero | poder clipar um trecho de uma live. |- O usuário pode criar um clipe a partir de um momento específico da live.</br> - O clipe é gerado corretamente e pode ser reproduzido posteriormente.</br> - O usuário pode compartilhar o link do clipe gerado. | RFB05 |
| USB06 |Como usuário, | quero | poder compartilhar o link de uma live. |- O usuário pode obter o link direto para a live que está assistindo.</br> - O link pode ser facilmente copiado e compartilhado em outras plataformas. | RFB07 |
| USB07 |Como usuário, | quero | poder reagir durante a transmissão. |- O usuário pode utilizar reações específicas (emotes, emojis, etc.) durante a live.</br> - As reações são exibidas corretamente no chat e/ou na tela da live. | RFB11 |
| USB08 |Como usuário, | quero | poder reagir durante a transmissão. |- O usuário tem acesso a uma opção para comprar bits.</br> - O processo de compra de bits é fácil de entender e realizar.</br> - As opções de pagamento são seguras e confiáveis. | RFB12 |
| USB09 |Como usuário, | quero | poder utilizar bits para enviar mensagens ao streamer. |- O usuário pode utilizar bits para enviar mensagens destacadas ou com algum tipo de efeito especial ao streamer.</br> - O streamer recebe e pode visualizar as mensagens enviadas com bits. | RFB13 |
| USB10 |Como usuário, | quero | poder denunciar uma transmissão ao vivo. |- O usuário pode acessar a opção de denúncia durante uma transmissão ao vivo.</br> - O processo de denúncia é fácil de entender e realizar.</br> - O usuário pode fornecer informações relevantes sobre a denúncia, como motivo e descrição.</br> - A denúncia é registrada e encaminhada para a equipe de moderação da Twitch para revisão. | RFB14 |
| USB11 |Como usuário, | quero | poder denunciar mensagens de outro usuário. |- O usuário pode acessar a opção de denúncia para mensagens de outros usuários no chat.</br> - O processo de denúncia é simples e direto.</br> - O usuário pode fornecer informações relevantes sobre a denúncia, como motivo e descrição.</br> - A denúncia é registrada e encaminhada para a equipe de moderação da Twitch para revisão. | RFB15 |
| USB12 |Como usuário, | quero | poder buscar canais/lives. |- O usuário pode acessar a funcionalidade de busca no site da Twitch.</br> - O usuário pode inserir palavras-chave, nomes de canais ou categorias de interesse na barra de busca.</br> - Os resultados da busca são relevantes e exibidos de forma clara e organizada.</br> - O usuário pode filtrar os resultados da busca com opções adicionais, como ordenação por relevância, popularidade, etc. | RFB16 |
| USB13 |Como usuário, | quero | poder consultar meu saldo de bits (Twitch Wallet). |- O usuário pode acessar informações sobre seu saldo de bits (Twitch Wallet) em sua conta.</br> - O saldo de bits é exibido de forma clara e atualizada.</br> - O usuário pode visualizar detalhes sobre como os bits foram adquiridos e gastos.</br> - O usuário pode verificar seu histórico de transações relacionadas aos bits. | RFB17 |
| USB14 |Como usuário, | quero | poder consultar meus Drops e Recompensas. |- O usuário pode acessar informações sobre seus Drops e Recompensas em sua conta.</br> - Os Drops e Recompensas são exibidos de forma organizada e fácil de entender.</br> - O usuário pode visualizar os Drops e Recompensas disponíveis, bem como seu progresso em relação a eles.</br> - O usuário pode obter detalhes sobre como resgatar e utilizar os Drops e Recompensas. | RFB23 |
<h6 align = "center"> Tabela 1: Histórias de Usuário relacionadas à visualização e interação com conteúdo.
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>


### 3.2. Histórias de usuário relacionadas a inscrições e pagamentos:

|**Id da User Story**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critério de aceitação**|**Id do Requisito**|
| :---: |:---: | :---: | :---: | :---:| :---: |
| USB15 |Como usuário, | quero | poder seguir um streamer. |- O usuário pode encontrar a opção de seguir um streamer no perfil do streamer ou em outras áreas relevantes.</br> - Ao seguir um streamer, o usuário recebe atualizações sobre suas transmissões e atividades.</br> - O usuário pode visualizar uma lista de streamers que está seguindo em sua conta. | RFB06 |
| USB16 |Como usuário, | quero | poder me inscrever em um canal utilizando o Amazon Prime. |- O usuário tem a opção de se inscrever em um canal utilizando sua assinatura do Amazon Prime.</br> - O processo de vinculação da conta do Amazon Prime à conta da Twitch é claro e fácil de seguir.</br> - Após a inscrição, o usuário tem acesso aos benefícios exclusivos oferecidos pela assinatura do Amazon Prime. | RFB08 |
| USB17 |Como usuário, | quero | poder me inscrever em um canal pagando diretamente. |- O usuário tem a opção de se inscrever em um canal pagando diretamente.</br> - O processo de pagamento é seguro e confiável, com opções de pagamento adequadas e claras.</br> - Após a inscrição, o usuário tem acesso aos benefícios exclusivos oferecidos pela inscrição paga. | RFB09 |
| USB18 |Como usuário, | quero | poder presentear uma inscrição para outro usuário. |- O usuário tem a opção de presentear uma inscrição para outro usuário.</br> - O processo de presenteamento de inscrição é fácil de entender e realizar.</br> - O usuário pode selecionar o destinatário do presente e fornecer as informações necessárias para a transação. | RFB10 |
| USB19 |Como usuário, | quero | poder consultar minhas inscrições. |- O usuário pode acessar informações sobre suas inscrições em sua conta.</br> - As inscrições ativas são exibidas de forma clara, com detalhes sobre os canais inscritos.</br> - O usuário pode verificar o status de suas inscrições, como data de expiração, renovação automática, etc. | RFB24 |
| USB20 |Como usuário, | quero | poder configurar o meu perfil. |- O usuário pode acessar as configurações do perfil em sua conta.</br> - O usuário pode fazer alterações e personalizações em seu perfil conforme desejado. | RFB25 |
| USB21 |Como usuário, | quero | poder configurar minha imagem do perfil. |- O usuário pode fazer upload ou selecionar uma imagem para ser utilizada como imagem do perfil.</br> - A imagem do perfil é exibida corretamente em todas as áreas relevantes do site. | RFB26 |
| USB22 |Como usuário, | quero | poder configurar meu banner do perfil. |- O usuário pode fazer upload ou selecionar uma imagem para ser utilizada como banner do perfil.</br> - O banner do perfil é exibido corretamente em todas as áreas relevantes do site. | RFB27 |
| USB23 |Como usuário, | quero | poder configurar meu nome de usuário. |- O usuário pode alterar seu nome de usuário de acordo com as regras e limitações definidas pela Twitch.</br> - O novo nome de usuário é atualizado corretamente em todas as áreas relevantes do site. | RFB28 |
| USB24 |Como usuário, | quero | poder configurar meu nome de exibição. |- O usuário pode escolher um nome de exibição para ser exibido em sua conta.</br> - O nome de exibição é exibido corretamente em todas as áreas relevantes do site. | RFB29 |
| USB25 |Como usuário, | quero | poder configurar minha biografia. |- O usuário pode acessar a opção de configurar sua biografia em seu perfil.</br> - O usuário pode adicionar informações pessoais, interesses, links relevantes, etc., em sua biografia.</br> - A biografia é exibida corretamente em seu perfil para outros usuários visualizarem. | RFB30 |
| USB26 |Como usuário, | quero | poder escolher o conjunto de emojis que irei utilizar. |- O usuário pode acessar as configurações relacionadas a emojis em sua conta.</br> - O usuário pode escolher e personalizar o conjunto de emojis disponíveis para uso em suas interações na Twitch.</br> - Os emojis escolhidos são exibidos corretamente em mensagens, reações, etc. | RFB33 |
| USB27 |Como usuário, | quero | poder gerenciar as notificações da minha conta. |- O usuário pode acessar as configurações de notificações em sua conta.</br> - O usuário pode selecionar as preferências de notificação, como receber notificações por e-mail, push ou ambos.</br> - O usuário pode escolher quais tipos de notificações deseja receber, como atividades de streamers seguidos, mensagens recebidas, etc. | RFB34 |
| USB28 |Como usuário, | quero | poder vincular minha conta da Twitch a outras plataformas. |- O usuário pode acessar as opções de vinculação de conta em sua conta da Twitch.</br> - O usuário pode vincular sua conta da Twitch a outras plataformas, como Twitter, YouTube, Discord, etc.</br> - O processo de vinculação é fácil de seguir e as plataformas são conectadas corretamente. | RFB35 |
<h6 align = "center"> Tabela 2: Histórias de usuário relacionadas a inscrições e pagamentos.
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>


### 3.3. Histórias de usuário relacionadas à plataforma e configurações:

|**Id da User Story**|**Usuário** | **Desejo** | **Descrição de recurso** | **Critério de aceitação**|**Id do Requisito**|
| :---: |:---: | :---: | :---: | :---:| :---: |
| USB29 |Como usuário, | quero | poder realizar ajustes nos conteúdos sugeridos. |- O usuário pode acessar as configurações relacionadas aos conteúdos sugeridos em sua conta.</br> - O usuário pode personalizar as preferências de conteúdo, como categorias, jogos, streamers, etc.</br> - As configurações de conteúdos sugeridos são atualizadas corretamente de acordo com as preferências do usuário. | RFB36 |
| USB30 |Como usuário, | quero | poder alterar o idioma da plataforma. |- O usuário pode acessar as configurações de idioma em sua conta.</br> - O usuário pode selecionar o idioma desejado para a interface da plataforma.</br> - O idioma selecionado é aplicado corretamente em todas as áreas e elementos da plataforma. | RFB37 |
| USB31 |Como usuário, | quero | poder alterar o tema (claro/escuro) da plataforma. |- O usuário pode acessar as configurações de tema da plataforma em sua conta.</br> - O usuário pode alternar entre os modos claro e escuro de acordo com sua preferência.</br> - A mudança de tema é aplicada corretamente em toda a interface da plataforma. | RFB38 |
| USB32 |Como usuário, | quero | poder realizar login na plataforma. |- O usuário pode acessar a página de login da Twitch.</br> - O usuário pode inserir suas credenciais de login, como nome de usuário ou e-mail e senha.</br> - Após o login bem-sucedido, o usuário tem acesso à sua conta e todas as funcionalidades associadas. | RFB39 |
| USB33 |Como usuário, | quero | poder realizar logout da plataforma. |- O usuário pode acessar a opção de logout em sua conta.</br> - Ao fazer logout, o usuário é redirecionado para a página inicial ou uma página de confirmação de logout. | RFB40 |
| USB34 |Como usuário, | quero | poder desabilitar minha conta da Twitch. |- O usuário pode acessar as configurações de desativação de conta em sua conta.</br> - O usuário recebe informações claras sobre as consequências da desativação da conta.</br> - O processo de desativação é confirmado com uma etapa adicional de confirmação. | RFB41 |
| USB35 |Como usuário, | quero | poder trocar sussurros com outros usuários |- O usuário pode acessar a funcionalidade de sussurros (mensagens privadas) na plataforma.</br> - O usuário pode enviar e receber sussurros de outros usuários.</br> - O sistema de sussurros funciona corretamente, garantindo a privacidade e a comunicação eficiente. | RFB42 |
| USB36 |Como usuário, | quero | ser capaz de personalizar o meu canal. |- O usuário pode acessar as configurações de personalização do canal em sua conta.</br> - O usuário pode editar informações do canal, como título, descrição, categorias, tags, etc.</br> - As alterações feitas na personalização do canal são exibidas corretamente para outros usuários. | RFB43 |
| USB37 |Como usuário, | quero | ser capaz de iniciar minha transmissão. |- O usuário pode acessar a opção de iniciar uma transmissão ao vivo.</br> - O usuário é guiado por um processo claro para configurar sua transmissão, como selecionar a plataforma de transmissão, definir configurações de áudio/vídeo, etc.</br> -  Após a configuração e personalização concluídas, o usuário pode iniciar sua transmissão ao vivo com um clique em um botão de "Iniciar" ou opção equivalente.| RFB44 |
<h6 align = "center"> Tabela 3: Histórias de usuário relacionadas à plataforma e configurações.
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>

## 4. Referências

> REHKOPF, Max. *Histórias de usuários com exemplos e um template*. Atlassian. Disponível no [link](https://www.atlassian.com/br/agile/project-management/user-stories). Acesso em 22 de maio de 2023.

## 5. Participantes

A tabela 4 a seguir registra os membros do grupo que contribuíram com esse documento:

| **Participante** | **Papel** |
| :----: | :----: |
| Ana Beatriz | Cliente/Usuário/Product Owner |
| Brunna Louise | Membro da Equipe de Desenvolvimento Ágil |
<h6 align = "center"> Tabela 4: Participantes e seus papéis na produção do artefato
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>

## Histórico de Versões

A Tabela 5 registra o histórico de versão desse documento.

|**Data** | **Versão** | **Descrição** | **Autor** | **Revisor** |
|:---: | :---: | :---: | :---: | :---: |
| 22/05/2023 | 1.0 | Primeira Versão do artefato de User Stories (Histórias de Usuário) | Ana Beatriz, Brunna Louise | - |
| 23/05/2023 | 1.1 | Estabelecendo padrões de codificação e adicionando documentação adicional | Brunna Louise | Ana Beatriz |
| 23/05/2023 | 1.2 | Adicionando criterios de aceitação | Ana Beatriz | Brunna Louise |

<h6 align = "center"> Tabela 5: Histórico de Versões
<br> Autor(es): Ana Beatriz, Brunna Louise
<br>Fonte: Autor(es)</h6>
