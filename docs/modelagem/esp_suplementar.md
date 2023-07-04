# Especificação Suplementar

## 1. Introdução
A Especificação Suplementar é um documento complementar à especificação principal de um projeto ou sistema. Ela contém informações adicionais que não foram abordadas na especificação principal, fornecendo detalhes e requisitos específicos que são importantes para o sucesso do projeto. 

A Especificação Suplementar descreve características adicionais, restrições, requisitos não funcionais, interfaces externas e outras informações relevantes que são necessárias para uma compreensão abrangente do sistema. Ela desempenha um papel crucial no desenvolvimento e na comunicação entre as partes envolvidas, ajudando a garantir que todos os aspectos do sistema sejam considerados e atendidos de maneira adequada.

## 2. Metodologia
A metodologia escolhida para o desenvolvimento do projeto é o FURPS+. 

O FURPS+ é um modelo de engenharia de requisitos que abrange várias áreas-chave, incluindo Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suporte e outros aspectos relevantes do sistema. Essa metodologia permite uma abordagem abrangente e estruturada para a definição e gerenciamento dos requisitos do projeto, garantindo que todas as dimensões críticas sejam consideradas. 

Grande parte dos requisitos elicitados, nos sentidos mais técnicos, foram extraídos do blog [Twitch Engineering blog](https://blog.twitch.tv/en/tags/engineering/).

## 3. Especificação Suplementar

### 3.1 Funcionalidade (Functionality)

A categoria de Funcionalidade representa todos os aspectos funcionais do software, ou seja, seus requisitos funcionais. Esses requisitos já foram elicitados em três técnicas diferentes: [Brainstorm](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/Brainstorm/), [Observação](/elicitacao/tecnicas/observacao/) e [Análise Documental](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/AnaliseDeDocumento/).
Abaixo, na tabela 1, estão algunas destes requisitos:

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|F01| O usuário deve ser capaz de assistir a uma live |[RFB01](/elicitacao/tecnicas/Brainstorm#requisitos-funcionais)|
|F02| O usuário deve ser capaz de assistir a um VOD (Video on Demand) |[RFB02](/elicitacao/tecnicas/Brainstorm#requisitos-funcionais)|
|F03| O usuário deve ser capaz de consumir conteúdos sem se registrar na plataforma |[OBS01](/elicitacao/tecnicas/observacao/#legendas)|
|F04| O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo |[OBS02](/elicitacao/tecnicas/observacao/#legendas)|
|F05| Possibilidade de fazer uma transmissão ao vivo seja de um PC, Mac, Xbox, Playstation ou Celular |[DOC01](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|F06| Acesso a funcionalidades como chat e análise no Painel de Controle |[DOC02](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|

<h6 align = "center"> Tabela 1: Requisitos não funcionais de Funcionalidade
<br> Autor: Rafael Nobre
<br>Fonte: Autor(es)</h6>

### 3.2 Usabilidade (Usability)
A Tabela 2 registra Requisitos não funcionais de Usabilidade.

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|U01| O usuário deve ser capaz de consumir conteúdos sem se registrar na plataforma |[OBS01](/elicitacao/tecnicas/observacao/#legendas)|
|U02|A plataforma deve ser acessível para usuários com necessidades especiais, incluindo suporte para tecnologias assistivas, como leitores de tela, recursos de alto contraste e legendas para pessoas com deficiência auditiva.|[DOC19](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|U03| Ao acessar "Ajuste de Conteúdo", no catálogo disponibilizado deverá ter somente a imagem do conteúdo sem um ícone de coração |[OBS07](/elicitacao/tecnicas/observacao/#legendas)|
|U04| A barra de navegação de tipos de conteúdos deve aparecer na tela de início, mesmo estando logado |[OBS12](/elicitacao/tecnicas/observacao/#legendas)|
|U05| Na Barra de navegação de tipos de conteúdos deve ser adicionado o tipo Artes e Ciência |[OBS13](/elicitacao/tecnicas/observacao/#legendas)|
|U06| A experiência do usuário na questão de sugestões de conteúdo e o tipo de disponibilidade delas deve ser melhor logado na plataforma |[OBS14](/elicitacao/tecnicas/observacao/#legendas)|
|U07| Possibilidade de fazer uma transmissão ao vivo seja de um PC, Mac, Xbox, Playstation ou Celular |[DOC08](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|

<h6 align = "center"> Tabela 2: Requisitos não funcionais de Usabilidade
<br> Autor: Ana Beatriz
<br>Fonte: Autor(es)</h6>

### 3.3 Confiabilidade (Reliability)
A Tabela 3 registra Requisitos não funcionais de Confiabilidade.

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|C01|A plataforma deve estar disponível para acesso e utilização pelos usuários durante a maior parte do tempo, minimizando períodos de inatividade não programada.| [DOC21](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)
|C02|Caso ocorram falhas, a plataforma deve ser capaz de se recuperar de forma rápida e automática, garantindo que os usuários possam retomar suas atividades sem interrupções significativas.| [DOC22](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)
|C03|A plataforma deve garantir a proteção dos dados dos usuários, prevenindo acessos não autorizados, ataques cibernéticos e vazamentos de informações confidenciais.| [DOC23](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)
|C04|A plataforma deve ser capaz de lidar com um aumento na demanda e no número de usuários, garantindo um desempenho estável mesmo em períodos de pico de tráfego.| [DOC24](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)
|C05|Todas as transações financeiras realizadas na plataforma devem ser protegidas e garantidas contra falhas ou corrupção de dados.| [DOC25](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)
  
<h6 align = "center"> Tabela 3: Requisitos não funcionais de Confiabilidade
<br> Autor: Ana Beatriz
<br>Fonte: Autor(es)</h6>

### 3.4 Desempenho (Performance)
A Tabela 4 registra Requisitos não funcionais de Desempenho.

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|D01|O sistema deve possuir resposta rápida para ações como carregamento de lives, mensagens no chat e interações de usuário. com um tempo de resposta médio de menos de 2 segundos|[DOC10](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|D02|A plataforma deve ser capaz de aguentar inúmeros usuários e streamers usando a plataforma de forma concorrente, escalando horizontalmente o número de recursos|[DOC11](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|D03|A plataforma deve minimizar latência entre usuários e viewers, garantindo que o delay seja menor que 10 segundos|[DOC12](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|D04|O sistema deve ser capaz de lidar com picos de acesso, como grandes eventos ou lançamentos, sem degradação significante|[DOC13](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|D05|A plataforma deve suportar vídeos em alta resolução, permitindo ao streamer realizar trasmissões acima de 4K, enquanto provê aos usuários a opção de adaptar a resolução de acordo com a conexão|[DOC14](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|D06|A plataforma deve permitir o playback de vídeos, sem bufferização ou interrupções, mesmo em alta demanda|[DOC15](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
  
<h6 align = "center"> Tabela 4: Requisitos não funcionais de Desempenho
<br> Autor: Rafael
<br>Fonte: Autor(es)</h6>

### 3.5 Suportabilidade
A Tabela 5 registra Requisitos não funcionais de Suportabilidade.

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|S01|A plataforma deve ser compatível com uma ampla variedade de navegadores e dispositivos, incluindo navegadores populares como Google Chrome, Mozilla Firefox, Safari e Microsoft Edge, além de dispositivos desktop, laptops, smartphones e tablets.|[DOC16](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|S02|A plataforma deve funcionar em diferentes sistemas operacionais, como Windows, macOS e Linux, garantindo uma experiência consistente para os usuários, independentemente do sistema operacional que estão utilizando.|[DOC17](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|S03|Integração com Plataformas Externas: A Twitch deve fornecer APIs e recursos que permitam a integração fácil com outras plataformas e serviços externos, como sistemas de gerenciamento de conteúdo, ferramentas de streaming, serviços de pagamento e redes sociais.|[DOC18](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|S04| O usuário deve estar cadastrado e logado para acessar as funcionalidades do sistema, com exceção o acesso aos vídeos |[OBS04](/elicitacao/tecnicas/observacao/#legendas)|
|S05|A plataforma deve ser adaptável a diferentes regiões geográficas, suportando múltiplos idiomas, formatos de data/hora e preferências culturais específicas de cada região.|[DOC20](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|S06|Possibilidade de fazer uma transmissão ao vivo seja de um PC, Mac, Xbox, Playstation ou Celular|[DOC01](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|

<h6 align = "center"> Tabela 5: Requisitos não funcionais de Suportabilidade
<br> Autor: Rafael
<br>Fonte: Autor(es)</h6>

### 3.6 +(Mais)
A Tabela 6 registra Requisitos não funcionais de + (Mais).

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|M01| Acesso a funcionalidades como chat e análise no Painel de Controle. | [DOC02](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|M02| Progressão de Streamer para Afiliado e, em seguida, para Parceiro, com requisitos específicos em relação a horas transmitidas, transmissões em dias únicos, média de espectadores e seguidores alcançados. | [DOC03](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|M03| Disponibilização de ótimas ferramentas aos Afiliados e Parceiros, como um botão de subscrição, ícone expressivo personalizado, receitas de anúncios, distintivos de subscritor e mais oportunidades de receita. | [DOC04](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|M04| Possibilidade de submeter um formulário de candidatura a Parceiro através do painel de controle. | [DOC05](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
|M05| Desbloqueio de funcionalidades como seguidores, chat, subscrições, ícones expressivos, distintivos de subscritor e receitas de anúncios, com a quantidade de funcionalidades desbloqueadas aumentando à medida que o streamer avança de Streamer para Afiliado e Parceiro.| [DOC06](/elicitacao/tecnicas/AnaliseDeDocumento/#3-resultados)|
<h6 align = "center"> Tabela 6: Requisitos não funcionais de + (Mais)
<br> Autor: Ana Beatriz
<br>Fonte: Autor(es)</h6>

## Bibliografia
> SERRANO, Milene; SERRANO, Maurício; Requisitos - Aula 13. Disponível em: Aprender3. Acesso em: 15 de maio de 2023.
> Twitch Engineering Blog

## Histórico de Versão
A Tabela 7 registra o histórico de versão desse documento.

|**Data** | **Versão** | **Descrição** | **Autor** | **Revisor** |
|:---: | :---: | :---: | :---: | :---: |
| 15/05/2023 | 1.0 | Criação do documento, adição de introdução e metologia | Ana Beatriz | Rafael |
| 16/05/2023 | 1.1 | Adição das especificações | Rafael | Ana Beatriz |
| 16/05/2023 | 1.2 | Adição das especificações | Ana Beatriz | Rafael |
| 04/06/2023 | 1.3 | Correção de acordo com sugestões do Monitor e do professor | Rafael | Ana Beatriz |
| 04/07/2023 | 2.0 | Padronização do documento e adição de elemento +|  Ana Beatriz  | Rafael

<h6 align = "center"> Tabela 7: Histórico de Versões
<br> Autor: Ana Beatriz </h6>