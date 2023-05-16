# Especificação Suplementar

## 1. Introdução
A Especificação Suplementar é um documento complementar à especificação principal de um projeto ou sistema. Ela contém informações adicionais que não foram abordadas na especificação principal, fornecendo detalhes e requisitos específicos que são importantes para o sucesso do projeto. 

A Especificação Suplementar descreve características adicionais, restrições, requisitos não funcionais, interfaces externas e outras informações relevantes que são necessárias para uma compreensão abrangente do sistema. Ela desempenha um papel crucial no desenvolvimento e na comunicação entre as partes envolvidas, ajudando a garantir que todos os aspectos do sistema sejam considerados e atendidos de maneira adequada.

## 2. Metodologia
A metodologia escolhida para o desenvolvimento do projeto é o FURPS+. 

O FURPS+ é um modelo de engenharia de requisitos que abrange várias áreas-chave, incluindo Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suporte e outros aspectos relevantes do sistema. Essa metodologia permite uma abordagem abrangente e estruturada para a definição e gerenciamento dos requisitos do projeto, garantindo que todas as dimensões críticas sejam consideradas. 

## 3. Especificação Suplementar

### 3.4 Desempenho (Performance)

|**Id**|**Descrição**| **Requisito relacionado**|
|:----:|:-----------:|:------------------------:|
|D01|O sistema deve possuir resposta rápida para ações como carregamento de lives, mensagens no chat e interações de usuário. com um tempo de resposta médio de menos de 2 segundos|DOC10|
|D02|A plataforma deve ser capaz de aguentar inúmeros usuários e streamers usando a plataforma de forma concorrente, escalando horizontalmente o número de recursos|DOC11|
|D03|A plataforma deve minimizar latência entre usuários e viewers, garantindo que o delay seja menor que 10 segundos|DOC12|
|D04|O sistema deve ser capaz de lidar com picos de acesso, como grandes eventos ou lançamentos, sem degradação significante|DOC13|
|D05|A plataforma deve suportar vídeos em alta resolução, permitindo ao streamer realizar trasmissões acima de 4K, enquanto provê aos usuários a opção de adaptar a resolução de acordo com a conexão|DOC14|
|D06|A plataforma deve permitir o playback de vídeos, sem bufferização ou interrupções, mesmo em alta demanda|DOC15|

### 3.5 Suportabilidade

|S01|A plataforma deve ser compatível com uma ampla variedade de navegadores e dispositivos, incluindo navegadores populares como Google Chrome, Mozilla Firefox, Safari e Microsoft Edge, além de dispositivos desktop, laptops, smartphones e tablets.|DOC16|
|S02|A plataforma deve funcionar em diferentes sistemas operacionais, como Windows, macOS e Linux, garantindo uma experiência consistente para os usuários, independentemente do sistema operacional que estão utilizando.|DOC17|
|S03|Integração com Plataformas Externas: A Twitch deve fornecer APIs e recursos que permitam a integração fácil com outras plataformas e serviços externos, como sistemas de gerenciamento de conteúdo, ferramentas de streaming, serviços de pagamento e redes sociais.|DOC18|
|S04|A plataforma deve ser acessível para usuários com necessidades especiais, incluindo suporte para tecnologias assistivas, como leitores de tela, recursos de alto contraste e legendas para pessoas com deficiência auditiva.|DOC19|
|S05|A plataforma deve ser adaptável a diferentes regiões geográficas, suportando múltiplos idiomas, formatos de data/hora e preferências culturais específicas de cada região.|DOC20|
|S06|Possibilidade de fazer uma transmissão ao vivo seja de um PC, Mac, Xbox, Playstation ou Celular|DOC01|


## Bibliografia
> SERRANO, Milene; SERRANO, Maurício; Requisitos - Aula 13. Disponível em: Aprender3. Acesso em: 15 de maio de 2023.
> Twitch Engineering Blog

## Histórico de Versão

|**Data** | **Versão** | **Descrição** | **Autor** | **Revisor** |
|:---: | :---: | :---: | :---: | :---: |
| 15/05/2023 | 1.0 | Criação do documento, adição de introdução e metologia | Ana Beatriz | Rafael |
| 16/05/2023 | 1.1 | Adição das especificações | Rafael | Ana Beatriz |