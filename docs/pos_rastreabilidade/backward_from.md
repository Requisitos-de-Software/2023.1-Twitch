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
|  |     | |  |

<h6 align = "center"> Tabela 1: Backward-From Requisitos Não-Funcionais
<br> Autor: Diógenes Dantas e Milena</h6>

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

### 3.2.1 Elos não funcionais 

#### ENF01

- Categoria:
- Elos:

#### ENF02

- Categoria:
- Elos:

#### ENF03

- Categoria:
- Elos:

#### ENF04

- Categoria:
- Elos:

#### ENF05

- Categoria:
- Elos:

#### ENF06

- Categoria:
- Elos:

#### ENF07

- Categoria:
- Elos:

#### ENF08

- Categoria:
- Elos:

#### ENF09

- Categoria:
- Elos:

#### ENF10

- Categoria:
- Elos:

#### ENF11

- Categoria:
- Elos:

#### ENF12

- Categoria:
- Elos:

#### ENF13

- Categoria:
- Elos:
  
#### ENF14

- Categoria:
- Elos:

#### ENF15

- Categoria:
- Elos:

#### ENF16

- Categoria:
- Elos:

#### ENF17

- Categoria:
- Elos:

#### ENF18

- Categoria:
- Elos:

#### ENF19

- Categoria:
- Elos:

#### ENF20

- Categoria:
- Elos:

#### ENF21

- Categoria:
- Elos:

#### ENF22

- Categoria:
- Elos:

#### ENF23

- Categoria:
- Elos:

#### ENF24

- Categoria:
- Elos:

#### ENF25

- Categoria:
- Elos:

#### ENF26

- Categoria:
- Elos:

#### ENF27

- Categoria:
- Elos:

 #### ENF28

- Categoria:
- Elos:

#### ENF29

- Categoria:
- Elos:

#### ENF30

- Categoria:
- Elos:

#### ENF31

- Categoria:
- Elos:

#### ENF32

- Categoria:
- Elos:
  
### 3.3 Legenda

|    ID    | Significado |
| :--------: | :----: |
| RF |  Requisitos Funcionais  |
| RNF |  Requisitos Não Funcionais  |
| BST | Brainstorm |
| OBS |  Observação  |
| DOC |  Documentação  |


<h6 align = "center"> Tabela 2: Legenda
<br> Autor: Diógenes Dantas e Milena </h6>


## Histórico de versão
|    Data    | Versão | Descrição                                                                      | Autor(es)  | Revisor  |
| :--------: | :----: | :----------------------------------------------------------------------------: | :--------: | :------: |
| 26.06.2023 | 1.0    | Primeira Versão do artefato de Backward_From de Pós-Rastreabilidade |   Diógenes Dantas   |  Milena  |

<h6 align = "center"> Tabela 3: Histórico de Versões
<br> Autor: Diógenes Dantas e Milena </h6>

## Referências

>SAYÃO, M.; LEITE, J.C.S.P. Rastreabilidade de requisitos. Disponível em: http://bib-di.inf.puc-rio.br/ftp/pub/docs/techreports/05_20_sayao.pdf. Acesso em 26 de junho de 2023

>SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26). Disponível em: https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 26 de junho de 2023

