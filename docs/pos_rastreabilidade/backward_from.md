# Backward From

## 1. Introdução

Segundo Mirian Sayão e Julio Cesar Sampaio, o rastreamento de requisitos é utilizado para prover relacionamentos entre requisitos, arquitetura e implementação final do sistema e possibilita uma adequada compreensão dos relacionamentos de dependência entre requisitos e através dos artefatos de requisi-tos, de arquitetura e de implementação. A rastreabilidade pode ser implementada por um conjunto de elos ou ligações (links) entre requisitos inter-relacionados, entre requisitos e suas fontes, e entre requisitos e os componentes que os implementam.

Este documento destina-se a rastrear a origem dos requisitos coletados no projeto, estabelecendo conexões com os casos de uso solicitados pelo cliente. Ele fornece uma visão global do projeto, ajudando a equipe a tomar decisões informadas ao identificar a fonte e a motivação dos requisitos selecionados.

## 2. Metodologia

Conforme no material aplicado na disciplina e referenciado por esse artefato, o grupo usou o meta-modelo de Toranzo, a fim de classificar as informações rastreadas em 4 níveis:

* Ambiental: informações oriundas do contexto no qual a organização está inserida;
* Organizacional: informações pertencentes à organização (missão, objetivos e estratégias);
* Gerencial: informações que auxiliam a gerência do projeto, e
* Desenvolvimento: informações associadas aos diversos artefatos informações gerados ao longo do processo de desenvolvimento (artefatos de requisitos, diagramas, códigos, casos de teste e outros).

Somado a isso, o meta-modelo de Toranzo classiica os elos de rastreabilidade em 6 elos:

* Satisfação: classe origem tem dependência de satisfação com a classe destino.
* Recurso: classe origem tem dependência de recurso com a classe destino.
* Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos.
* Representação: captura a representação ou modelagem dos requisitos em outras linguagens.
* Alocado: classe origem está relacionada à classe destino, que representa um subsistema.
* Agregação: indica "composição" de elementos.

## 3. Pós-rastreabilidade 

### 3.1 Requisitos Funcionais

|    ID    | Requisito | Origem                                                                      | Elo |
| :--------: | :----: | :----------------------------------------------------------------------------: | :--------: |
| RF01 |  O usuário deve ser capaz de assistir a uma live  | [BST01](../elicitacao/tecnicas/Brainstorm.md#RFB01), [BST02](../elicitacao/tecnicas/Brainstorm.md#RFB02) | [EF01](./backward_from.md#ef01) |
| RF02 |  O usuário deve ser capaz de interagir em uma live | [BST03](../elicitacao/tecnicas/Brainstorm.md#RFB03), [BST05](../elicitacao/tecnicas/Brainstorm.md#RFB05),[BST07](../elicitacao/tecnicas/Brainstorm.md#RFB07), [BST11](../elicitacao/tecnicas/Brainstorm.md#RFB11), [BST14](../elicitacao/tecnicas/Brainstorm.md#RFB14), [BST15](../elicitacao/tecnicas/Brainstorm.md#RFB15) | [EF02](./backward_from.md#ef02) |
| RF03 |  O usuário deve ser capaz de seguir um streamer | [BST06](../elicitacao/tecnicas/Brainstorm.md#RFB06), [BST24](../elicitacao/tecnicas/Brainstorm.md#RFB24)| [EF03](./backward_from.md#ef03) |
| RF04 |  O usuário deve ser capaz de se inscrever em um canal utilizando o Amazon Prime  | [BST08](../elicitacao/tecnicas/Brainstorm.md#RFB08), [BST09](../elicitacao/tecnicas/Brainstorm.md#RFB09), [BST10](../elicitacao/tecnicas/Brainstorm.md#RFB10) | [EF04](./backward_from.md#ef04) |
| RF05 |  O usuário deve ser capaz de comprar bits  | [BST12](../elicitacao/tecnicas/Brainstorm.md#RFB12), [BST13](../elicitacao/tecnicas/Brainstorm.md#RFB13), [BST17](../elicitacao/tecnicas/Brainstorm.md#RFB17), [BST19](../elicitacao/tecnicas/Brainstorm.md#RFB19) | [EF05](./backward_from.md#ef05) |
| RF06 |  RFB18	O usuário deve ser capaz de consultar seu histórico de pagamentos  | [BST18](../elicitacao/tecnicas/Brainstorm.md#RFB18), [BST20](../elicitacao/tecnicas/Brainstorm.md#RFB20) | [EF06](./backward_from.md#ef06) |
| RF07 |  O usuário deve ser capaz de resgatar Loots do Prime Gaming  | [BST21](../elicitacao/tecnicas/Brainstorm.md#RFB21), [BST22](../elicitacao/tecnicas/Brainstorm.md#RFB22), [BST23](../elicitacao/tecnicas/Brainstorm.md#RFB23) | [EF07](./backward_from.md#ef07) |
| RF08 |  O usuário deve ser capaz de configurar o seu perfil  | [BST25](../elicitacao/tecnicas/Brainstorm.md#RFB25), [BST26](../elicitacao/tecnicas/Brainstorm.md#RFB26), [BST27](../elicitacao/tecnicas/Brainstorm.md#RFB27), [BST28](../elicitacao/tecnicas/Brainstorm.md#RFB28), [BST29](../elicitacao/tecnicas/Brainstorm.md#RFB29), [BST30](../elicitacao/tecnicas/Brainstorm.md#RFB30),[BST31](../elicitacao/tecnicas/Brainstorm.md#RFB31), [BST34](../elicitacao/tecnicas/Brainstorm.md#RFB34) | [EF08](./backward_from.md#ef08)  |
| RF09 | O usuário deve ser capaz de altear a cor do chat  | [BST32](../elicitacao/tecnicas/Brainstorm.md#RFB32), [BST33](../elicitacao/tecnicas/Brainstorm.md#RFB33) |[EF09](./backward_from.md#ef09)  |
| RF10 | O usuário deve ser capaz de vincular sua conta da Twitch a outras plataformas (Twitter, Amazon, Steam, Discord, Youtube) | [BST35](../elicitacao/tecnicas/Brainstorm.md#RFB35) |[EF10](./backward_from.md#ef10) |
| RF11 | O usuário deve ser capaz de realizar ajustes nos conteúdos sugeridos  | [BST36](../elicitacao/tecnicas/Brainstorm.md#RFB36), [OBS06](../elicitacao/tecnicas/observacao.md#OBS06), [OBS08](../elicitacao/tecnicas/observacao.md#OBS08), [OBS09](../elicitacao/tecnicas/observacao.md#OBS09), [OBS11](../elicitacao/tecnicas/observacao.md#OBS11) |[EF11](./backward_from.md#ef11)  |
| RF12 | O usuário deve ser capaz de realizar o login na plataforma | [BST37](../elicitacao/tecnicas/Brainstorm.md#RFB37), [BST38](../elicitacao/tecnicas/Brainstorm.md#RFB38), [BST39](../elicitacao/tecnicas/Brainstorm.md#RFB39), [BST40](../elicitacao/tecnicas/Brainstorm.md#RFB40), [BST41](../elicitacao/tecnicas/Brainstorm.md#RFB41)|[EF12](./backward_from.md#ef12)  |
| RF13 | O usuário deve ser capaz de personalizar o seu canal | [BST43](../elicitacao/tecnicas/Brainstorm.md#RFB43), [DOC02](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC02), [DOC03](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC03), [DOC04](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC04), [DOC05](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC05), [DOC06](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC06) |[EF13](./backward_from.md#ef13)  |
| RF14 | O usuário deve ser capaz de iniciar sua transmissão | [BST44](../elicitacao/tecnicas/Brainstorm.md#RFB44), [DOC01](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC01) |[EF14](./backward_from.md#ef14)  |
| RF15 | O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo | [OBS02](../elicitacao/tecnicas/observacao.md#OBS02), [OBS03](../elicitacao/tecnicas/observacao.md#OBS03) |[EF15](./backward_from.md#ef15) |

<h6 align = "center"> Tabela 1: Backward-From Requisitos Funcionais
<br> Autor: Diógenes Dantas e Milena</h6>

### 3.1.2 Elos Funcionais

#### EF01

- Categoria: Desenvolvimento 
- Elos: [BST01](../elicitacao/tecnicas/Brainstorm.md#RFB01) agrega [BST02](../elicitacao/tecnicas/Brainstorm.md#RFB02) 

#### EF02

- Categoria: Desenvolvimento
- Elos: [BST03](../elicitacao/tecnicas/Brainstorm.md#RFB03) agrega [BST05](../elicitacao/tecnicas/Brainstorm.md#RFB05) <br>[BST07](../elicitacao/tecnicas/Brainstorm.md#RFB07) agrega [BST11](../elicitacao/tecnicas/Brainstorm.md#RFB11)</br> [BST14](../elicitacao/tecnicas/Brainstorm.md#RFB14) agrega [BST15](../elicitacao/tecnicas/Brainstorm.md#RFB15)

#### EF03

- Categoria: Desenvolvimento
- Elos: [BST06](../elicitacao/tecnicas/Brainstorm.md#RFB06) agrega [BST24](../elicitacao/tecnicas/Brainstorm.md#RFB24)

#### EF04

- Categoria: Desenvolvimento
- Elos: [BST08](../elicitacao/tecnicas/Brainstorm.md#RFB08) agrega [BST09](../elicitacao/tecnicas/Brainstorm.md#RFB09)  <br> agrega [BST10](../elicitacao/tecnicas/Brainstorm.md#RFB10) </br>

#### EF05

- Categoria: Desenvolvimento
- Elos: <br>[BST12](../elicitacao/tecnicas/Brainstorm.md#RFB12) agrega [BST13](../elicitacao/tecnicas/Brainstorm.md#RFB13) </br> [BST17](../elicitacao/tecnicas/Brainstorm.md#RFB17) agrega [BST19](../elicitacao/tecnicas/Brainstorm.md#RFB19)

#### EF06

- Categoria: Desenvolvimento
- Elos:  [BST18](../elicitacao/tecnicas/Brainstorm.md#RFB18) agrega [BST20](../elicitacao/tecnicas/Brainstorm.md#RFB20)

#### EF07

- Categoria: Desenvolvimento
- Elos: [BST21](../elicitacao/tecnicas/Brainstorm.md#RFB21) agrega [BST22](../elicitacao/tecnicas/Brainstorm.md#RFB22)  <br> agrega [BST23](../elicitacao/tecnicas/Brainstorm.md#RFB23) </br>

#### EF08

- Categoria: Desenvolvimento
- Elos: [BST25](../elicitacao/tecnicas/Brainstorm.md#RFB25) agrega [BST26](../elicitacao/tecnicas/Brainstorm.md#RFB26) <br>[BST27](../elicitacao/tecnicas/Brainstorm.md#RFB27) agrega [BST28](../elicitacao/tecnicas/Brainstorm.md#RFB28)</br> [BST29](../elicitacao/tecnicas/Brainstorm.md#RFB29) agrega [BST30](../elicitacao/tecnicas/Brainstorm.md#RFB30) <br>[BST31](../elicitacao/tecnicas/Brainstorm.md#RFB31) agrega [BST34](../elicitacao/tecnicas/Brainstorm.md#RFB34) </br>

#### EF09

- Categoria: Desenvolvimento
- Elos: [BST32](../elicitacao/tecnicas/Brainstorm.md#RFB32) agrega [BST33](../elicitacao/tecnicas/Brainstorm.md#RFB33)

#### EF10

- Categoria: Desenvolvimento
- Elos: [BST35](../elicitacao/tecnicas/Brainstorm.md#RFB35)

#### EF11

- Categoria: Desenvolvimento
- Elos: <br>[BST36](../elicitacao/tecnicas/Brainstorm.md#RFB36) agrega [OBS06](../elicitacao/tecnicas/observacao.md#OBS06)</br> [OBS08](../elicitacao/tecnicas/observacao.md#OBS08) agrega [OBS09](../elicitacao/tecnicas/observacao.md#OBS09) <br> agrega [OBS11](../elicitacao/tecnicas/observacao.md#OBS11) </br>

#### EF12

- Categoria: Desenvolvimento
- Elos: <br> [BST37](../elicitacao/tecnicas/Brainstorm.md#RFB37) agrega [BST38](../elicitacao/tecnicas/Brainstorm.md#RFB38)</br> [BST39](../elicitacao/tecnicas/Brainstorm.md#RFB39) agrega [BST40](../elicitacao/tecnicas/Brainstorm.md#RFB40) <br> agrega [BST41](../elicitacao/tecnicas/Brainstorm.md#RFB41) </br>

#### EF13

- Categoria: Desenvolvimento
- Elos: <br>[BST43](../elicitacao/tecnicas/Brainstorm.md#RFB43) agrega [DOC02](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC02)</br> [DOC03](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC03) agrega [DOC04](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC04) <br>[DOC05](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC05) agrega [DOC06](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC06)</br>
  
#### EF14

- Categoria: Ambiental
- Elos: [BST44](../elicitacao/tecnicas/Brainstorm.md#RFB44) agrega [DOC01](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC01)

#### EF15

- Categoria: Ambiental
- Elos: [OBS02](../elicitacao/tecnicas/observacao.md#OBS02) agrega [OBS03](../elicitacao/tecnicas/observacao.md#OBS03)


### 3.2 Requisitos Não-Funcionais
|    ID    | Requisito | Origem | Elo |
| :------: | :-------: | :----: | :-: |
| RNF01	| Internacionalização: o sistema é capaz de apresentar diferentes idiomas | [BST](../elicitacao/tecnicas/Brainstorm.md#RNFB01) | [ENF01](./backward_from.md#enf01) |
| RNF02	| Segurança: o sistema deve garantir proteção contra acesso não autorizado | [BST](../elicitacao/tecnicas/Brainstorm.md#RNFB02) | [ENF02](./backward_from.md#enf02) |
| RNF03	| Portabilidade: o sistema deve ser disponível em diferentes plataformas (PCs, Smartphones, SmarTVs) | [BST](../elicitacao/tecnicas/Brainstorm.md#RNFB03) | [ENF03](./backward_from.md#enf03) |
| RNF04	| Conformidade: o sistema deve cumprir todas as leis e regulamentos aplicáveis: cumpre as leis do país em operação | [BST](../elicitacao/tecnicas/Brainstorm.md#RNFB04) | [ENF04](./backward_from.md#enf04) |
| RNF05	| Escabilidade: sistema é capaz de ter um bom desempenho sob uma carga de trabalho aumentada ou crescente: Suporta um alto número de usuários ativos ao mesmo tempo | [BST](../elicitacao/tecnicas/Brainstorm.md#RNFB05) |  [ENF05](./backward_from.md#enf05) |
| RNF06	| Disponibilidade:o sistema deve estar disponível quando necessário, com um bom funcionamento durante 24 horas | [BST](../elicitacao/tecnicas/Brainstorm.md#RNFB06) | [ENF06](./backward_from.md#enf06) |
| RNF07 | O usuário deve ser capaz de consumir conteúdos sem se registrar na plataforma	| [OBS01](../elicitacao/tecnicas/observacao.md#OBS01) | [ENF07](./backward_from.md#enf07) |-|
| RNF08 |	O usuário deve estar cadastrado e logado para acessar as funcionalidades do sistema, com exceção o acesso aos vídeos	| [OBS04](../elicitacao/tecnicas/observacao.md#OBS04) | [ENF08](./backward_from.md#enf08) |
| RNF09 |	Ao acessar "Ajuste de Conteúdo", no catálogo disponibilizado deverá ter somente a imagem do conteúdo sem um ícone de coração	| [OBS07](../elicitacao/tecnicas/observacao.md#OBS07) | [ENF09](./backward_from.md#enf09) |
| RNF10 |	A plataforma deve colocar um efeito Blur nos Thumbnails para cada conteúdo categorizado como adulto ou 18+	| [OBS10](../elicitacao/tecnicas/observacao.md#OBS10) | [ENF10](./backward_from.md#enf10) | [NFR Framework](../../modelagem/nfr/#OBS10) \| [Histórias de Usuário](../../modelagem/user_stories#USB16)|
| RNF11 | A barra de navegação de tipos de conteúdos deve aparecer na tela de início, mesmo estando logado	| [OBS12](../elicitacao/tecnicas/observacao.md#OBS12) | [ENF11](./backward_from.md#enf11) |
| RNF12 | Na Barra de navegação de tipos de conteúdos deve ser adicionado o tipo Artes e Ciência	| [OBS13](../elicitacao/tecnicas/observacao.md#OBS13) | [ENF12](./backward_from.md#enf12) |
| RNF13 |	A experiência do usuário na questão de sugestões de conteúdo e o tipo de disponibilidade delas deve ser melhor logado na plataforma	| [OBS14](../elicitacao/tecnicas/observacao.md#OBS14) | [ENF13](./backward_from.md#enf13) |
| RNF14 |	Cumprimento de requisitos específicos para avançar de Streamer para Afiliado e Parceiro, incluindo horas transmitidas, transmissões em dias únicos, média de espectadores e seguidores alcançados	| [DOC03](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC03) | [ENF14](./backward_from.md#enf14) |
| RNF15 |	Dificuldade em atingir o estatuto de Parceiro	| [DOC08](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC08) | [ENF15](./backward_from.md#enf15) |
| RNF16 |	Necessidade de criar uma ligação com o público e tornar o canal mais rentável para ter sucesso como criador na Twitch	| [DOC09](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC09) | [ENF16](./backward_from.md#enf16) |
| RNF17 |	O sistema deve possuir resposta rápida para ações como carregamento de lives, mensagens no chat e interações de usuário. com um tempo de resposta médio de menos de 2 segundos | [DOC10](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC10) | [ENF17](./backward_from.md#enf17) |
| RNF18 |	A plataforma deve ser capaz de aguentar inúmeros usuários e streamers usando a plataforma de forma concorrente, escalando horizontalmente o número de recursos	| [DOC11](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC11) | [ENF18](./backward_from.md#enf18) |
| RNF19 |	A plataforma deve minimizar latência entre usuários e viewers, garantindo que o delay seja menor que 10 segundos	| [DOC12](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC12) | [ENF19](./backward_from.md#enf19) |
| RNF20 |	O sistema deve ser capaz de lidar com picos de acesso, como grandes eventos ou lançamentos, sem degradação significante	| [DOC13](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC13) | [ENF20](./backward_from.md#enf20) |
| RNF21 |	A plataforma deve suportar vídeos em alta resolução, permitindo ao streamer realizar trasmissões acima de 4K, enquanto provê aos usuários a opção de adaptar a resolução de acordo com a conexão | [DOC14](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC14) | [ENF21](./backward_from.md#enf21) |
| RNF22 |	A plataforma deve permitir o playback de vídeos, sem bufferização ou interrupções, mesmo em alta demanda	| [DOC15](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC15) | [ENF22](./backward_from.md#enf22) |
| RNF23 |	A plataforma deve ser compatível com uma ampla variedade de navegadores e dispositivos, incluindo navegadores populares como Google Chrome, Mozilla Firefox, Safari e Microsoft Edge, além de dispositivos desktop, laptops, smartphones e tablets	| [DOC16](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC16) | [ENF23](./backward_from.md#enf23) |
| RNF24 |	A plataforma deve funcionar em diferentes sistemas operacionais, como Windows, macOS e Linux, garantindo uma experiência consistente para os usuários, independentemente do sistema operacional que estão utilizando	| [DOC17](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC17) | [ENF24](./backward_from.md#enf24) |
| RNF25 |	Integração com Plataformas Externas: A Twitch deve fornecer APIs e recursos que permitam a integração fácil com outras plataformas e serviços externos, como sistemas de gerenciamento de conteúdo, ferramentas de streaming, serviços de pagamento e redes sociais	| [DOC18](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC18) | [ENF25](./backward_from.md#enf25) |
| RNF26 |	A plataforma deve ser acessível para usuários com necessidades especiais, incluindo suporte para tecnologias assistivas, como leitores de tela, recursos de alto contraste e legendas para pessoas com deficiência auditiva	| [DOC19](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC19) | [ENF26](./backward_from.md#enf26) |
| RNF27 |	A plataforma deve ser adaptável a diferentes regiões geográficas, suportando múltiplos idiomas, formatos de data/hora e preferências culturais específicas de cada região	| [DOC20](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC20) | [ENF24](./backward_from.md#enf27) |
| RNF28 |	A plataforma deve estar disponível para acesso e utilização pelos usuários durante a maior parte do tempo, minimizando períodos de inatividade não programada	| [DOC21](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC21) | [ENF28](./backward_from.md#enf28) |
| RNF29 |	Caso ocorram falhas, a plataforma deve ser capaz de se recuperar de forma rápida e automática, garantindo que os usuários possam retomar suas atividades sem interrupções significativas	| [DOC22](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC22) | [ENF29](./backward_from.md#enf29) |
| RNF30 |	A plataforma deve garantir a proteção dos dados dos usuários, prevenindo acessos não autorizados, ataques cibernéticos e vazamentos de informações confidenciais	| [DOC23](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC23) | [ENF30](./backward_from.md#enf30) |
| RNF31 |	A plataforma deve ser capaz de lidar com um aumento na demanda e no número de usuários, garantindo um desempenho estável mesmo em períodos de pico de tráfego	| [DOC24](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC24) | [ENF31](./backward_from.md#enf31) |
| RNF32 |	Todas as transações financeiras realizadas na plataforma devem ser protegidas e garantidas contra falhas ou corrupção de dados	| [DOC25](../elicitacao/tecnicas/AnaliseDeDocumento.md#DOC25) | [ENF32](./backward_from.md#enf32) |

<h6 align = "center"> Tabela 2: Backward-From Requisitos Não-Funcionais
<br> Autor: Diógenes Dantas e Milena</h6>

### 3.2.1 Elos não funcionais 

#### ENF01

- Categoria: Ambiental 
- Elos: Agrega [Brainstorm](../elicitacao/tecnicas/Brainstorm.md)

#### ENF02

- Categoria: Desenvolvimento
- Elos: [Brainstorm](../elicitacao/tecnicas/Brainstorm.md)

#### ENF03

- Categoria: Desenvolvimento
- Elos: [Brainstorm](../elicitacao/tecnicas/Brainstorm.md)

#### ENF04

- Categoria: Organizacional
- Elos: [Brainstorm](../elicitacao/tecnicas/Brainstorm.md)

#### ENF05

- Categoria: Desenvolvimento
- Elos: [Brainstorm](../elicitacao/tecnicas/Brainstorm.md)

#### ENF06

- Categoria: Desenvolvimento
- Elos: [Brainstorm](../elicitacao/tecnicas/Brainstorm.md)

#### ENF07

- Categoria: Desenvolvimento
- Elos: Agrega [Observação](../elicitacao/tecnicas/observacao.md)

#### ENF08

- Categoria: Desenvolvimento
- Elos: Agrega [Observação](../elicitacao/tecnicas/observacao.md)

#### ENF09

- Categoria: Gerencial
- Elos: Agrega [Observação](../elicitacao/tecnicas/observacao.md)

#### ENF10

- Categoria: Ambiental
- Elos: Agrega [Observação](../elicitacao/tecnicas/observacao.md)

#### ENF11

- Categoria: Organizacional
- Elos: Agrega [Observação](../elicitacao/tecnicas/observacao.md)

#### ENF12

- Categoria: Gerencial
- Elos: Agrega [Observação](../elicitacao/tecnicas/observacao.md)

#### ENF13

- Categoria: Desenvolvimento
- Elos: Agrega [Observação](../elicitacao/tecnicas/observacao.md)
  
#### ENF14

- Categoria: Ambiental
- Elos: Agrega  [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF15

- Categoria: Ambiental
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF16

- Categoria: Ambiental
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF17

- Categoria: Desenvolvimento
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF18

- Categoria: Desenvolvimento
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF19

- Categoria: Desenvolvimento
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF20

- Categoria: Desenvolvimento
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF21

- Categoria: Desenvolvimento
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 
 
#### ENF22

- Categoria: Desenvolvimento
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF23

- Categoria: Desenvolvimento
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF24

- Categoria: Desenvolvimento
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF25

- Categoria: Organizacional
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF26

- Categoria: Ambiental
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF27

- Categoria: Ambiental
- Elos:  Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

 #### ENF28

- Categoria: Ambiental
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF29

- Categoria: Ambiental
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF30

- Categoria: Ambiental
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF31

- Categoria: Ambiental
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 

#### ENF32

- Categoria: Ambiental
- Elos: Agrega [Análise Documental](../elicitacao/tecnicas/AnaliseDeDocumento.md) 
  
### 3.3 Legenda

|    ID    | Significado |
| :--------: | :----: |
| RF |  Requisitos Funcionais  |
| RNF |  Requisitos Não Funcionais  |
| BST | Brainstorm |
| OBS |  Observação  |
| DOC |  Documentação  |


<h6 align = "center"> Tabela 3: Legenda
<br> Autor: Diógenes Dantas e Milena </h6>

## Referências

>SAYÃO, M.; LEITE, J.C.S.P. Rastreabilidade de requisitos. Disponível em: http://bib-di.inf.puc-rio.br/ftp/pub/docs/techreports/05_20_sayao.pdf. Acesso em 26 de junho de 2023

>SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26). Disponível em: https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 26 de junho de 2023


## Histórico de versão
|    Data    | Versão | Descrição                                                                      | Autor(es)  | Revisor  |
| :--------: | :----: | :----------------------------------------------------------------------------: | :--------: | :------: |
| 26.06.2023 | 1.0    | Primeira Versão do artefato de Backward_From de Pós-Rastreabilidade |   Diógenes Dantas   |  Milena  |
| 27.06.2023 | 1.1    | Adição da tabela com os requisitos não funcionais para pós-rastreabildade Backward_From |   Milena   |  Diógenes Dantas |
| 27.06.2023 | 1.2    | Adição da tabela com os requisitos funcionais para pós-rastreabildade Backward_From |   Diógenes Dantas   |  Milena  |
| 27.06.2023 | 1.3    | Adição dos Elos Funcionais |   Diógenes Dantas   |  Milena  |
| 27.06.2023 | 1.4    | Adição dos Elos Não Funcionais |   Milena   |  Diógenes Dantas  |
| 03.07.2023 | 2.0    | Adição de associação entre a questão da tabela de requisitos funcionais e não funcionais com os seus respectivos elos. Artefato ajustado para a entrega final |  Diógenes Dantas | Milena |
| 04.07.2023 | 2.0    | Adição dos hyperlinks |  Rafael Nobre | Milena |

<h6 align = "center"> Tabela 4: Histórico de Versões
<br> Autor: Diógenes Dantas e Milena </h6>


