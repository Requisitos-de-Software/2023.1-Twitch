# Especificação Suplementar

## 1. Introdução
A Especificação Suplementar é um documento complementar à especificação principal de um projeto ou sistema. Ela contém informações adicionais que não foram abordadas na especificação principal, fornecendo detalhes e requisitos específicos que são importantes para o sucesso do projeto. 

A Especificação Suplementar descreve características adicionais, restrições, requisitos não funcionais, interfaces externas e outras informações relevantes que são necessárias para uma compreensão abrangente do sistema. Ela desempenha um papel crucial no desenvolvimento e na comunicação entre as partes envolvidas, ajudando a garantir que todos os aspectos do sistema sejam considerados e atendidos de maneira adequada.

## 2. Metodologia
A metodologia escolhida para o desenvolvimento do projeto é o FURPS+. 

O FURPS+ é um modelo de engenharia de requisitos que abrange várias áreas-chave, incluindo Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suporte e outros aspectos relevantes do sistema. Essa metodologia permite uma abordagem abrangente e estruturada para a definição e gerenciamento dos requisitos do projeto, garantindo que todas as dimensões críticas sejam consideradas. 

## 3. Especificação Suplementar

### 3.1 Funcionalidade (Functionality)

A categoria de Funcionalidade representa todos os aspectos funcionais do software, ou seja, seus requisitos. Esses requisitos já foram elicitados em três técnicas diferentes: [Brainstorm](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/Brainstorm/), [Observação](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/observacao/) e [Análise Documental](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/AnaliseDeDocumento/).

### 3.2 Usabilidade (Usability)

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|U01| O usuário deve ser capaz de consumir conteúdos sem se registrar na plataforma |OBS01|
|U02| O usuário deve estar cadastrado e logado para acessar as funcionalidades do sistema, com exceção o acesso aos vídeos |OBS04|
|U03| Ao acessar "Ajuste de Conteúdo", no catálogo disponibilizado deverá ter somente a imagem do conteúdo sem um ícone de coração |OBS07|
|U04| A barra de navegação de tipos de conteúdos deve aparecer na tela de início, mesmo estando logado |OBS12|
|U05| Na Barra de navegação de tipos de conteúdos deve ser adicionado o tipo Artes e Ciência |OBS13|
|U06| A experiência do usuário na questão de sugestões de conteúdo e o tipo de disponibilidade delas deve ser melhor logado na plataforma |OBS14|
|U07| Possibilidade de fazer uma transmissão ao vivo seja de um PC, Mac, Xbox, Playstation ou Celular |DOC08|

<h6 align = "center"> Tabela 1: Requisitos não funcionais de Usabilidade
<br> Autor: Ana Beatriz
<br>Fonte: Autor(es)</h6>

### 3.3 Confiabilidade (Reliability)

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|C01|A plataforma deve estar disponível para acesso e utilização pelos usuários durante a maior parte do tempo, minimizando períodos de inatividade não programada.| DOC21
|C02|Caso ocorram falhas, a plataforma deve ser capaz de se recuperar de forma rápida e automática, garantindo que os usuários possam retomar suas atividades sem interrupções significativas.| DOC22
|C03|A plataforma deve garantir a proteção dos dados dos usuários, prevenindo acessos não autorizados, ataques cibernéticos e vazamentos de informações confidenciais.| DOC23
|C04|A plataforma deve ser capaz de lidar com um aumento na demanda e no número de usuários, garantindo um desempenho estável mesmo em períodos de pico de tráfego.| DOC24
|C05|Todas as transações financeiras realizadas na plataforma devem ser protegidas e garantidas contra falhas ou corrupção de dados.| DOC25
  
<h6 align = "center"> Tabela 2: Requisitos não funcionais de Confiabilidade
<br> Autor: Ana Beatriz
<br>Fonte: Autor(es)</h6>

### 3.4 Desempenho (Performance)

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|D01|O sistema deve possuir resposta rápida para ações como carregamento de lives, mensagens no chat e interações de usuário. com um tempo de resposta médio de menos de 2 segundos|DOC10|
|D02|A plataforma deve ser capaz de aguentar inúmeros usuários e streamers usando a plataforma de forma concorrente, escalando horizontalmente o número de recursos|DOC11|
|D03|A plataforma deve minimizar latência entre usuários e viewers, garantindo que o delay seja menor que 10 segundos|DOC12|
|D04|O sistema deve ser capaz de lidar com picos de acesso, como grandes eventos ou lançamentos, sem degradação significante|DOC13|
|D05|A plataforma deve suportar vídeos em alta resolução, permitindo ao streamer realizar trasmissões acima de 4K, enquanto provê aos usuários a opção de adaptar a resolução de acordo com a conexão|DOC14|
|D06|A plataforma deve permitir o playback de vídeos, sem bufferização ou interrupções, mesmo em alta demanda|DOC15|
  
<h6 align = "center"> Tabela 3: Requisitos não funcionais de Desempenho
<br> Autor: Rafael
<br>Fonte: Autor(es)</h6>

### 3.5 Suportabilidade

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|S01|A plataforma deve ser compatível com uma ampla variedade de navegadores e dispositivos, incluindo navegadores populares como Google Chrome, Mozilla Firefox, Safari e Microsoft Edge, além de dispositivos desktop, laptops, smartphones e tablets.|DOC16|
|S02|A plataforma deve funcionar em diferentes sistemas operacionais, como Windows, macOS e Linux, garantindo uma experiência consistente para os usuários, independentemente do sistema operacional que estão utilizando.|DOC17|
|S03|Integração com Plataformas Externas: A Twitch deve fornecer APIs e recursos que permitam a integração fácil com outras plataformas e serviços externos, como sistemas de gerenciamento de conteúdo, ferramentas de streaming, serviços de pagamento e redes sociais.|DOC18|
|S04|A plataforma deve ser acessível para usuários com necessidades especiais, incluindo suporte para tecnologias assistivas, como leitores de tela, recursos de alto contraste e legendas para pessoas com deficiência auditiva.|DOC19|
|S05|A plataforma deve ser adaptável a diferentes regiões geográficas, suportando múltiplos idiomas, formatos de data/hora e preferências culturais específicas de cada região.|DOC20|
|S06|Possibilidade de fazer uma transmissão ao vivo seja de um PC, Mac, Xbox, Playstation ou Celular|DOC01|

<h6 align = "center"> Tabela 4: Requisitos não funcionais de Suportabilidade
<br> Autor: Rafael
<br>Fonte: Autor(es)</h6>

## Bibliografia
> SERRANO, Milene; SERRANO, Maurício; Requisitos - Aula 13. Disponível em: Aprender3. Acesso em: 15 de maio de 2023.
> Twitch Engineering Blog

## Histórico de Versão

|**Data** | **Versão** | **Descrição** | **Autor** | **Revisor** |
|:---: | :---: | :---: | :---: | :---: |
| 15/05/2023 | 1.0 | Criação do documento, adição de introdução e metologia | Ana Beatriz | Rafael |
| 16/05/2023 | 1.1 | Adição das especificações | Rafael | Ana Beatriz |
| 16/05/2023 | 1.2 | Adição das especificações | Ana Beatriz | Rafael |
