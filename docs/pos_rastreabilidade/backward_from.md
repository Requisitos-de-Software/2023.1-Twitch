# Backward Tom

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
| RF01 |  O usuário deve ser capaz de assistir a uma live  | [BST01](../elicitacao/tecnicas/Brainstorm.md), [BST02](../elicitacao/tecnicas/Brainstorm.md) | [EF01](#ef01) |
| RF02 |  O usuário deve ser capaz de interagir em uma live | [BST03](../elicitacao/tecnicas/Brainstorm.md), [BST05](../elicitacao/tecnicas/Brainstorm.md),[BST07](../elicitacao/tecnicas/Brainstorm.md), [BST11](../elicitacao/tecnicas/Brainstorm.md), [BST14](../elicitacao/tecnicas/Brainstorm.md), [BST15](../elicitacao/tecnicas/Brainstorm.md) | [EF02](#ef02) |
| RF03 |  O usuário deve ser capaz de seguir um streamer | [BST06](../elicitacao/tecnicas/Brainstorm.md), [BST24](../elicitacao/tecnicas/Brainstorm.md)| [EF03](#ef03) |
| RF04 |  O usuário deve ser capaz de se inscrever em um canal utilizando o Amazon Prime  | [BST08](../elicitacao/tecnicas/Brainstorm.md), [BST09](../elicitacao/tecnicas/Brainstorm.md), [BST10](../elicitacao/tecnicas/Brainstorm.md) | [EF04](#ef04) |
| RF05 |  O usuário deve ser capaz de comprar bits  | [BST12](../elicitacao/tecnicas/Brainstorm.md), [BST13](../elicitacao/tecnicas/Brainstorm.md), [BST17](../elicitacao/tecnicas/Brainstorm.md), [BST19](../elicitacao/tecnicas/Brainstorm.md) | [EF05](#ef05) |
| RF06 |  RFB18	O usuário deve ser capaz de consultar seu histórico de pagamentos  | [BST18](../elicitacao/tecnicas/Brainstorm.md), [BST20](../elicitacao/tecnicas/Brainstorm.md) | [EF06](#ef06) |
| RF07 |  O usuário deve ser capaz de resgatar Loots do Prime Gaming  | [BST21](../elicitacao/tecnicas/Brainstorm.md), [BST22](../elicitacao/tecnicas/Brainstorm.md), [BST23](../elicitacao/tecnicas/Brainstorm.md) | [EF07](#ef07) |
| RF08 |  O usuário deve ser capaz de configurar o seu perfil  | [BST25](../elicitacao/tecnicas/Brainstorm.md), [BST26](../elicitacao/tecnicas/Brainstorm.md), [BST27](../elicitacao/tecnicas/Brainstorm.md), [BST28](../elicitacao/tecnicas/Brainstorm.md), [BST29](../elicitacao/tecnicas/Brainstorm.md), [BST30](../elicitacao/tecnicas/Brainstorm.md),[BST31](../elicitacao/tecnicas/Brainstorm.md), [BST34](../elicitacao/tecnicas/Brainstorm.md) | [EF08](#ef08) |
| RF09 | O usuário deve ser capaz de altear a cor do chat  | [BST32](../elicitacao/tecnicas/Brainstorm.md), [BST33](../elicitacao/tecnicas/Brainstorm.md) |[EF09](#ef09) |
| RF10 | O usuário deve ser capaz de vincular sua conta da Twitch a outras plataformas (Twitter, Amazon, Steam, Discord, Youtube) | [BST35](../elicitacao/tecnicas/Brainstorm.md) |[EF10](#ef10) |
| RF11 | O usuário deve ser capaz de realizar ajustes nos conteúdos sugeridos  | [BST36](../elicitacao/tecnicas/Brainstorm.md), [OBS06](../elicitacao/tecnicas/observacao.md), [OBS08](../elicitacao/tecnicas/observacao.md), [OBS09](../elicitacao/tecnicas/observacao.md), [OBS11](../elicitacao/tecnicas/observacao.md) |[EF11](#ef11) |
| RF12 | O usuário deve ser capaz de realizar o login na plataforma | [BST37](../elicitacao/tecnicas/Brainstorm.md), [BST38](../elicitacao/tecnicas/Brainstorm.md), [BST39](../elicitacao/tecnicas/Brainstorm.md), [BST40](../elicitacao/tecnicas/Brainstorm.md), [BST41](../elicitacao/tecnicas/Brainstorm.md)|[EF12](#ef12) |
| RF13 | O usuário deve ser capaz de personalizar o seu canal | [BST43](../elicitacao/tecnicas/Brainstorm.md), [DOC02](../elicitacao/tecnicas/AnaliseDeDocumento.md), [DOC03](../elicitacao/tecnicas/AnaliseDeDocumento.md), [DOC04](../elicitacao/tecnicas/AnaliseDeDocumento.md), [DOC05](../elicitacao/tecnicas/AnaliseDeDocumento.md), [DOC06](../elicitacao/tecnicas/AnaliseDeDocumento.md) |[EF13](#ef13) |
| RF14 | O usuário deve ser capaz de iniciar sua transmissão | [BST44](../elicitacao/tecnicas/Brainstorm.md), [DOC01](../elicitacao/tecnicas/AnaliseDeDocumento.md) |[EF14](#ef14) |
| RF15 | O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo | [OBS02](../elicitacao/tecnicas/observacao.md), [OBS03](../elicitacao/tecnicas/observacao.md) |[EF15](#ef14) |

<h6 align = "center"> Tabela 1: Backward-From Requisitos Funcionais
<br> Autor: Diógenes Dantas e Milena</h6>

### 3.1.2 Elos Funcionais

#### EF01

- Categoria: Desenvolvimento 
- Elos: [BST01](../elicitacao/tecnicas/Brainstorm.md) agrega [BST02](../elicitacao/tecnicas/Brainstorm.md) 

#### EF02

- Categoria: Desenvolvimento
- Elos: [BST03](../elicitacao/tecnicas/Brainstorm.md) agrega [BST05](../elicitacao/tecnicas/Brainstorm.md) <br>[BST07](../elicitacao/tecnicas/Brainstorm.md) agrega [BST11](../elicitacao/tecnicas/Brainstorm.md)</br> [BST14](../elicitacao/tecnicas/Brainstorm.md) agrega [BST15](../elicitacao/tecnicas/Brainstorm.md)

#### EF03

- Categoria: Desenvolvimento
- Elos: [BST06](../elicitacao/tecnicas/Brainstorm.md) agrega [BST24](../elicitacao/tecnicas/Brainstorm.md)

#### EF04

- Categoria: Desenvolvimento
- Elos: [BST08](../elicitacao/tecnicas/Brainstorm.md) agrega [BST09](../elicitacao/tecnicas/Brainstorm.md)  <br> agrega [BST10](../elicitacao/tecnicas/Brainstorm.md) </br>

#### EF05

- Categoria: Desenvolvimento
- Elos: <br>[BST12](../elicitacao/tecnicas/Brainstorm.md) agrega [BST13](../elicitacao/tecnicas/Brainstorm.md) </br> [BST17](../elicitacao/tecnicas/Brainstorm.md) agrega [BST19](../elicitacao/tecnicas/Brainstorm.md)

#### EF06

- Categoria: Desenvolvimento
- Elos:  [BST18](../elicitacao/tecnicas/Brainstorm.md) agrega [BST20](../elicitacao/tecnicas/Brainstorm.md)

#### EF07

- Categoria: Desenvolvimento
- Elos: [BST21](../elicitacao/tecnicas/Brainstorm.md) agrega [BST22](../elicitacao/tecnicas/Brainstorm.md)  <br> agrega [BST23](../elicitacao/tecnicas/Brainstorm.md) </br>

#### EF08

- Categoria: Desenvolvimento
- Elos: [BST25](../elicitacao/tecnicas/Brainstorm.md) agrega [BST26](../elicitacao/tecnicas/Brainstorm.md) <br>[BST27](../elicitacao/tecnicas/Brainstorm.md) agrega [BST28](../elicitacao/tecnicas/Brainstorm.md)</br> [BST29](../elicitacao/tecnicas/Brainstorm.md) agrega [BST30](../elicitacao/tecnicas/Brainstorm.md) <br>[BST31](../elicitacao/tecnicas/Brainstorm.md) agrega [BST34](../elicitacao/tecnicas/Brainstorm.md) </br>

#### EF09

- Categoria: Desenvolvimento
- Elos: [BST32](../elicitacao/tecnicas/Brainstorm.md) agrega [BST33](../elicitacao/tecnicas/Brainstorm.md)

#### EF10

- Categoria: Desenvolvimento
- Elos: [BST35](../elicitacao/tecnicas/Brainstorm.md)

#### EF11

- Categoria: Desenvolvimento
- Elos: <br>[BST36](../elicitacao/tecnicas/Brainstorm.md) agrega [OBS06](../elicitacao/tecnicas/observacao.md)</br> [OBS08](../elicitacao/tecnicas/observacao.md) agrega [OBS09](../elicitacao/tecnicas/observacao.md) <br> agrega [OBS11](../elicitacao/tecnicas/observacao.md) </br>

#### EF12

- Categoria: Desenvolvimento
- Elos: <br> [BST37](../elicitacao/tecnicas/Brainstorm.md) agrega [BST38](../elicitacao/tecnicas/Brainstorm.md)</br> [BST39](../elicitacao/tecnicas/Brainstorm.md) agrega [BST40](../elicitacao/tecnicas/Brainstorm.md) <br> agrega [BST41](../elicitacao/tecnicas/Brainstorm.md) </br>

#### EF13

- Categoria: Desenvolvimento
- Elos: <br>[BST43](../elicitacao/tecnicas/Brainstorm.md) agrega [DOC02](../elicitacao/tecnicas/AnaliseDeDocumento.md)</br> [DOC03](../elicitacao/tecnicas/AnaliseDeDocumento.md) agrega [DOC04](../elicitacao/tecnicas/AnaliseDeDocumento.md) <br>[DOC05](../elicitacao/tecnicas/AnaliseDeDocumento.md) agrega [DOC06](../elicitacao/tecnicas/AnaliseDeDocumento.md)</br>
  
#### EF14

- Categoria: Ambiental
- Elos: [BST44](../elicitacao/tecnicas/Brainstorm.md) agrega [DOC01](../elicitacao/tecnicas/AnaliseDeDocumento.md)

#### EF15

- Categoria: Ambiental
- Elos: [OBS02](../elicitacao/tecnicas/observacao.md) agrega [OBS03](../elicitacao/tecnicas/observacao.md)


### 3.2 Requisitos Não-Funcionais
|    ID    | Requisito | Origem | Elo |
| :------: | :-------: | :----: | :-: |
| RNF01	| Internacionalização: o sistema é capaz de apresentar diferentes idiomas | [BST](../elicitacao/tecnicas/Brainstorm.md) | [ENF01](#enf01) |
| RNF02	| Segurança: o sistema deve garantir proteção contra acesso não autorizado | [BST](../elicitacao/tecnicas/Brainstorm.md) | [ENF02](#enf02) | 
| RNF03	| Portabilidade: o sistema deve ser disponível em diferentes plataformas (PCs, Smartphones, SmarTVs) | [BST](../elicitacao/tecnicas/Brainstorm.md) | [ENF03](#enf03) |
| RNF04	| Conformidade: o sistema deve cumprir todas as leis e regulamentos aplicáveis: cumpre as leis do país em operação | [BST](../elicitacao/tecnicas/Brainstorm.md) | [ENF04](#enf04) |
| RNF05	| Escabilidade: sistema é capaz de ter um bom desempenho sob uma carga de trabalho aumentada ou crescente: Suporta um alto número de usuários ativos ao mesmo tempo | [BST](../elicitacao/tecnicas/Brainstorm.md) |  [ENF05](#enf05) |
| RNF06	| Disponibilidade:o sistema deve estar disponível quando necessário, com um bom funcionamento durante 24 horas | [BST](../elicitacao/tecnicas/Brainstorm.md) | [ENF06](#enf06) |
| RNF07 | O usuário deve ser capaz de consumir conteúdos sem se registrar na plataforma	| [OBS](../elicitacao/tecnicas/observacao.md) | [ENF07](#enf07) |
| RNF08 |	O usuário deve estar cadastrado e logado para acessar as funcionalidades do sistema, com exceção o acesso aos vídeos	| [OBS](../elicitacao/tecnicas/observacao.md) | [ENF08](#enf08) |
| RNF09 |	Ao acessar "Ajuste de Conteúdo", no catálogo disponibilizado deverá ter somente a imagem do conteúdo sem um ícone de coração	| [OBS](../elicitacao/tecnicas/observacao.md) | [ENF09](#enf09) | 
| RNF10 |	A plataforma deve colocar um efeito Blur nos Thumbnails para cada conteúdo categorizado como adulto ou 18+	| [OBS](../elicitacao/tecnicas/observacao.md) | [ENF10](#enf10) | 
| RNF11 | A barra de navegação de tipos de conteúdos deve aparecer na tela de início, mesmo estando logado	| [OBS](../elicitacao/tecnicas/observacao.md) | [ENF11](#enf11) |
| RNF12 | Na Barra de navegação de tipos de conteúdos deve ser adicionado o tipo Artes e Ciência	| [OBS](../elicitacao/tecnicas/observacao.md) | [ENF12](#enf12) |
| RNF13 |	A experiência do usuário na questão de sugestões de conteúdo e o tipo de disponibilidade delas deve ser melhor logado na plataforma	| [OBS](../elicitacao/tecnicas/observacao.md) | [ENF13](#enf13) |
| RNF14 |	Cumprimento de requisitos específicos para avançar de Streamer para Afiliado e Parceiro, incluindo horas transmitidas, transmissões em dias únicos, média de espectadores e seguidores alcançados	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF14](#enf14) |
| RNF15 |	Dificuldade em atingir o estatuto de Parceiro	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF15](#enf15) |
| RNF16 |	Necessidade de criar uma ligação com o público e tornar o canal mais rentável para ter sucesso como criador na Twitch	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF16](#enf16) |
| RNF17 |	O sistema deve possuir resposta rápida para ações como carregamento de lives, mensagens no chat e interações de usuário. com um tempo de resposta médio de menos de 2 segundos | [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF17](#enf17) |
| RNF18 |	A plataforma deve ser capaz de aguentar inúmeros usuários e streamers usando a plataforma de forma concorrente, escalando horizontalmente o número de recursos	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF18](#enf18) |
| RNF19 |	A plataforma deve minimizar latência entre usuários e viewers, garantindo que o delay seja menor que 10 segundos	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF19](#enf19) |
| RNF20 |	O sistema deve ser capaz de lidar com picos de acesso, como grandes eventos ou lançamentos, sem degradação significante	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF20](#enf20) |
| RNF21 |	A plataforma deve suportar vídeos em alta resolução, permitindo ao streamer realizar trasmissões acima de 4K, enquanto provê aos usuários a opção de adaptar a resolução de acordo com a conexão | [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF21](#enf21) |	
| RNF22 |	A plataforma deve permitir o playback de vídeos, sem bufferização ou interrupções, mesmo em alta demanda	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF22](#enf22) |
| RNF23 |	A plataforma deve ser compatível com uma ampla variedade de navegadores e dispositivos, incluindo navegadores populares como Google Chrome, Mozilla Firefox, Safari e Microsoft Edge, além de dispositivos desktop, laptops, smartphones e tablets	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF23](#enf23) |
| RNF24 |	A plataforma deve funcionar em diferentes sistemas operacionais, como Windows, macOS e Linux, garantindo uma experiência consistente para os usuários, independentemente do sistema operacional que estão utilizando	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF24](#enf24) |
| RNF25 |	Integração com Plataformas Externas: A Twitch deve fornecer APIs e recursos que permitam a integração fácil com outras plataformas e serviços externos, como sistemas de gerenciamento de conteúdo, ferramentas de streaming, serviços de pagamento e redes sociais	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF25](#enf25) |
| RNF26 |	A plataforma deve ser acessível para usuários com necessidades especiais, incluindo suporte para tecnologias assistivas, como leitores de tela, recursos de alto contraste e legendas para pessoas com deficiência auditiva	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF26](#enf26) |
| RNF27 |	A plataforma deve ser adaptável a diferentes regiões geográficas, suportando múltiplos idiomas, formatos de data/hora e preferências culturais específicas de cada região	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF24](#enf27) |
| RNF28 |	A plataforma deve estar disponível para acesso e utilização pelos usuários durante a maior parte do tempo, minimizando períodos de inatividade não programada	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF28](#enf28) |
| RNF29 |	Caso ocorram falhas, a plataforma deve ser capaz de se recuperar de forma rápida e automática, garantindo que os usuários possam retomar suas atividades sem interrupções significativas	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF29](#enf29) |
| RNF30 |	A plataforma deve garantir a proteção dos dados dos usuários, prevenindo acessos não autorizados, ataques cibernéticos e vazamentos de informações confidenciais	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF30](#enf30) |
| RNF31 |	A plataforma deve ser capaz de lidar com um aumento na demanda e no número de usuários, garantindo um desempenho estável mesmo em períodos de pico de tráfego	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF31](#enf31) |
| RNF32 |	Todas as transações financeiras realizadas na plataforma devem ser protegidas e garantidas contra falhas ou corrupção de dados	| [DOC](../elicitacao/tecnicas/AnaliseDeDocumento.md) | [ENF32](#enf32) |

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


## Histórico de versão
|    Data    | Versão | Descrição                                                                      | Autor(es)  | Revisor  |
| :--------: | :----: | :----------------------------------------------------------------------------: | :--------: | :------: |
| 26.06.2023 | 1.0    | Primeira Versão do artefato de Backward_From de Pós-Rastreabilidade |   Diógenes Dantas   |  Milena  |
| 27.06.2023 | 1.1    | Adição da tabela com os requisitos não funcionais para pós-rastreabildade Backward_From |   Milena   |  Diógenes Dantas |
| 27.06.2023 | 1.2    | Adição da tabela com os requisitos funcionais para pós-rastreabildade Backward_From |   Diógenes Dantas   |  Milena  |
| 27.06.2023 | 1.3    | Adição dos Elos Funcionais |   Diógenes Dantas   |  Milena  |
| 27.06.2023 | 1.4    | Adição dos Elos Não Funcionais |   Milena   |  Diógenes  |

<h6 align = "center"> Tabela 4: Histórico de Versões
<br> Autor: Diógenes Dantas e Milena </h6>

## Referências

>SAYÃO, M.; LEITE, J.C.S.P. Rastreabilidade de requisitos. Disponível em: http://bib-di.inf.puc-rio.br/ftp/pub/docs/techreports/05_20_sayao.pdf. Acesso em 26 de junho de 2023

>SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26). Disponível em: https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 26 de junho de 2023

