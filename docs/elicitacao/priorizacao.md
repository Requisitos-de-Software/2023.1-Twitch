# Priorização

## 1. Introdução

O documento de priorização tem como objetivo definir uma prioridade para cada função ou funcionalidade utilizando técnicas de priorização. Tendo assim como objetivo auxiliar na essencialidade de cada funcionalidade do software desenvolvido, essa técnica é recomendada para projetos com curto prazo e limitação de recursos.

## 2. Técnicas de Priorização

Para fazer a priorização, o grupo em acordo escolheu duas técnicas: MoSCoW e First Things First. Essas técnicas foram escolhidas pela familiaridade dos membros e com isso uma opção mais adequada.

### 2.1 MoSCoW

Essa é uma técnica simples onde basicamente para cada requisito, você deve atribuir uma letra onde cada uma tem um significado específico:

- Must-Have: São os requisitos Prioritários/ Críticos e são considerados indispensáveis para a realização do projeto,os mais urgentes e os primeiros a serem implementados.
- Should- Have: São requisitos importantes para o projeto porém não são considerados essencias como o anterior.
- Could-Have: São requisitos que agregam valor ao projeto porém não são importantes para a conclusão.
- Would/ Want/ Won't- Have: São os requisitos que não tem um impacto no projeto, com pouco retorno e em alguns casos não se enquadram no projeto.

Para priorização dos requisitos foi montado uma tabela com os requisitos elicitados anteriormente no projeto e sua devida priorização.

|**Identificador**|**Requisito**|**Priorização**|
|:---------------:|:-----------:|:-------------:|
|RFB01|O usuário deve ser capaz de assistir a uma live| Must |
|RFB02|O usuário deve ser capaz de assistir a um VOD (Video on Demand)| Must |
|RFB03|O usuário deve ser capaz de interagir em uma live| Must |
|RFB04|O usuário deve ser capaz de comentar uma live | Must |
|RFB05|O usuário deve ser capaz de clipar um trecho de uma live| Should |
|RFB06|O usuário deve ser capaz de seguir um streamer| Must |
|RFB07|O usuário deve ser capaz de compartilhar o link de uma live| Should |
|RFB08|O usuário deve ser capaz de se inscrever em um canal utilizando o Amazon Prime| Could |
|RFB09|O usuário deve ser capaz de se inscrever em um canal pagando diretamente| Must |
|RFB10|O usuário deve ser capaz de presentar uma inscrição para outro usuário| Could |
|RFB11|O usuário deve ser capaz de reagir durante a transmissão| Could |
|RFB12|O usuário deve ser capaz de comprar bits| Should |
|RFB13|O usuário deve ser capaz de utilizar os bits para mandar mensagens ao streamer| Should |
|RFB14|O usuário deve ser capaz denunciar uma transmissão ao vivo| Must |
|RFB15|O usuário deve ser capaz de denunciar mensagens de outro usuário| Must |
|RFB16|O usuário deve ser capaz de buscar canais/lives| Must |
|RFB17|O usuário deve ser capaz de consultar seu saldo de bits (Twitch Wallet)| Must |
|RFB18|O usuário deve ser capaz de consultar seu histórico de pagamentos| Must |
|RFB19|O usuário deve ser capaz de consultar seu histórico de bits| Must |
|RFB20|O usuário deve ser capaz de adicionar/editar/excluir métodos de pagamentos| Must |
|RFB21|O usuário deve ser capaz de receber Drops e Recompensas, apoiando criadores da Twitch| Could |
|RFB22|O usuário deve ser capaz de resgatar Loots do Prime Gaming| Could |
|RFB23|O usuário deve ser capaz de consultar seus Drops e Recompensas| Could |
|RFB24|O usuário deve ser capaz de consultar suas inscrições| Should |
|RFB25|O usuário deve ser capaz de configurar o seu perfil| Must |
|RFB26|O usuário deve ser capaz de configurar sua Imagem do perfil| Must |
|RFB27|O usuário deve ser capaz de configurar seu Banner do perfil| Must |
|RFB28|O usuário deve ser capaz de configurar seu Nome de usuário| Must |
|RFB29|O usuário deve ser capaz de configurar seu Nome de Exibição| Must |
|RFB30|O usuário deve ser capaz de configurar sua Biografia| Must |
|RFB31|O usuário deve ser capaz de desabilitar sua conta da Twitch| Must |
|RFB32|O usuário deve ser capaz de altear a cor do chat| Could |
|RFB33|O usuário deve ser capaz de escolher o conjunto de emojis que ele utilizará| Could|
|RFB34|O usuário deve ser capaz de gerenciar as notificações de sua conta| Should |
|RFB35|O usuário deve ser capaz de vincular sua conta da Twitch a outras plataformas (Twitter, Amazon, Steam, Discord, Youtube)| Could |
|RFB36|O usuário deve ser capaz de realizar ajustes nos conteúdos sugeridos| Should |
|RFB37|O usuário deve ser capaz de alterar o idioma da plataforma| Must |
|RFB38|O usuário deve ser capaz de alterar o tema (claro/escuro) da plataforma| Could |
|RFB39|O usuário deve ser capaz de realizar o login na plataforma| Must |
|RFB40|O usuário deve ser capaz de realizar o logoff da plataforma| Must |
|RFB41|O usuário deve ser capaz de desabilitar a sua conta da Twitch| Must |
|RFB42|O usuário deve ser capaz de trocar sussurros com outros usuários| Could |
|RFB43|O usuário deve ser capaz de personalizar o seu canal| Must |
|RFB44|O usuário deve ser capaz de iniciar sua transmissão| Must |
|RNFB01|Internacionalização: o sistema é capaz de apresentar diferentes idiomas| Must |
|RNFB02|Segurança: o sistema deve garantir proteção contra acesso não autorizado| Must |
|RNFB03|Portabilidade: o sistema deve ser disponível em diferentes plataformas (PCs, Smartphones, SmarTVs)| Should |
|RNFB04|Conformidade: o sistema deve cumprir todas as leis e regulamentos aplicáveis: cumpre as leis do país em operaçao| Must|
|RNFB05|Escabilidade: sistema é capaz de ter um bom desempenho sob uma carga de trabalho aumentada ou crescente: Suporta um alto número de usuários ativos ao mesmo tempo| Must |
|RNFB06|Disponibilidade:o sistema deve estar disponível quando necessário, com um bom funcionamento durante 24 horas| Must |
| OBS01 | O usuário deve ser capaz de consumir conteúdos sem se registrar na plataforma | Must |
| OBS02 | O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo | Must |
| OBS03 | O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo através de um provedor de email como Gmail, Outlook | Must |
| OBS04 | O usuário deve estar cadastrado e logado para acessar as funcionalidades do sistema, com exceção o acesso aos vídeos  | Must |
| OBS05 | Ao sair de uma live e voltar para a página de início, o vídeo da live em formato de Thumbnail deve estar pausada ou não existir | Should |
| OBS06 | Para um novo usuário, o sistema de recomendação de Categorias deve mostrar os tipos de conteúdos que estão em alta na plataforma | Must |
| OBS07 | Ao acessar "Ajuste de Conteúdo", no catálogo disponibilizado deverá ter somente a imagem do conteúdo sem um ícone de coração | Should |
| OBS08 | Ao acessar "Ajuste de Conteúdo", após o usuário selecionar as categorias que lhe interessa. O sistema deve sugerir os tipos de conteúdos voltados a sua escolha na maioria da interface | Must |
| OBS09 | Ao acessar "Ajuste de Conteúdo", o usuário deve ter a opção de selecionar se deseja receber sugestões de conteúdos categorizados para adultos | Must
| OBS10 | A plataforma deve colocar um efeito Blur nos Thumbnails para cada conteúdo categorizado como adulto ou 18+ | Must |
| OBS11 | A plataforma deve colocar uma etapa de confirmação, perguntado se o usuário deseja visualizar o conteúdo categorizado como adulto ou 18+| Must |
| OBS12 | A barra de navegação de tipos de conteúdos deve aparecer na tela de início, mesmo estando logado  | Must |
| OBS13 | Na Barra de navegação de tipos de conteúdos deve ser adicionado o tipo Artes e Ciência | Should |
| OBS14 | A experiência do usuário na questão de sugestões de conteúdo e o tipo de disponibilidade delas deve ser melhor logado na plataforma | Should |

<h6 align = "center"> Tabela 1: Priorização utilizando MoSCoW
<br>Fonte: Autor(es)</h6>

### 2.2 First Things First

First Things First é uma técnica de priorização que utiliza uma abordagem que enfatiza a importância de identificar e priorizar os requisitos mais críticos e fundamentais para o sucesso do projeto. Essa técnica é representada por meio de um tabela desenvolvida em 8 passos, facilitando a visualização da prioridade do requisitos do sistema.

Metodologia:

- Passo 1. Faça uma lista de todos os requisitos em uma planilha.
- Passo 2. Estime o benefício relativo que cada recurso fornece ao cliente ou ao negócio em uma escala de 1 a 9, onde 1 é o menos significativo e 9 o máximo.
- Passo 3. Estime a penalidade que o negócio sofreria, se o recurso não for incluído. Usar escala de 1 a 9, onde 1 significa nenhuma penalidade e 9 indica uma grande desvantagem.
- Passo 4. A coluna Valor Total é a soma do (Benefício Relativo * Peso Relativo) e da (Penalidade Relativa * Peso Relativo).
- Passo 5. Estime o custo relativo de implementação de cada característica, em uma escala que varia de um mínimo de 1 a um máximo de 9.
- Passo 6. Estime o grau relativo de risco a cada requisito em uma escala de 1 a 9.
- Passo 7. Calcule a prioridade para cada requisito usando Prioridade igual a: 
valor % / custo % * Peso custo + riscos % * Peso Risco
- Passo 8. Ordene a lista em ordem decrescente de prioridade. As coracterísticas no topo da lista têm o melhor equilíbrio entre valor, custo e risco. e, portanto, devem ser priorizadas.

Para priorização dos requisitos foi montado uma tabela com os requisitos elicitados anteriormente no projeto e sua devida priorização.

Link da Tabela Abaixo no Google Sheets: [link](https://docs.google.com/spreadsheets/d/1bW9HxL3BySiPyHXx8yDZQT6_XalB9dEB-SWXOdULGdQ/edit?usp=sharing).

|Peso Relativo|2|1| | |1| |0,5| | |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| | | | | | | | | | |
|**Requisitos**|**Benefício Relativo**|**Penalidade Relativa**|**Valor Total**|**Valor (%)**|**Custo Relativo**|**Custo (%)**|**Risco Relativo**|**Risco (%)**|**Prioridade**|
|Requisitos Funcionais (BrainStorm)| | | | | | | | | |
|RFB01 - O usuário deve ser capaz de assistir a uma live|9|9|27|1,74|9|1,84|9|1,82|0,66|
|RFB02 - O usuário deve ser capaz de assistir a um VOD (Video on Demand)|9|9|27|1,74|9|1,84|9|1,82|0,66|
|RFB03 - O usuário deve ser capaz de interagir em uma live|9|7|25|1,61|8|1,64|8|1,62|0,66|
|RFB04 - O usuário deve ser capaz comentar na live|9|8|26|1,68|8|1,64|8|1,62|0,66|
|RFB05 - O usuário deve ser capaz de clipar um trecho de uma live|9|6|24|1,55|8|1,64|7|1,42|0,60|
|RFB06 - O usuário deve ser capaz de seguir um streamer|8|8|24|1,55|7|1,43|7|1,42|0,66|
|RFB07 - O usuário deve ser capaz de compartilhar o link de uma live|8|8|24|1,55|7|1,43|8|1,62|0,72|
|RFB08 - O usuário deve ser capaz de se inscrever em um canal utilizando o Amazon Prime|7|6|20|1,29|8|1,64|8|1,62|0,66|
|RFB09 - O usuário deve ser capaz de se inscrever em um canal pagando diretamente|7|7|21|1,36|8|1,64|8|1,62|0,66|
|RFB10 - O usuário deve ser capaz de presentar uma inscrição para outro usuário|7|6|20|1,29|8|1,64|8|1,62|0,66|
|RFB11 - O usuário deve ser capaz de reagir durante a transmissão|7|9|23|1,48|7|1,43|8|1,62|0,72|
|RFB12 - O usuário deve ser capaz de comprar bits|7|7|21|1,36|6|1,23|7|1,42|0,73|
|RFB13 - O usuário deve ser capaz de utilizar os bits para mandar mensagens ao streamer|6|7|19|1,23|7|1,43|7|1,42|0,66|
|RFB14 - O usuário deve ser capaz denunciar uma transmissão ao vivo|9|9|27|1,74|8|1,64|8|1,62|0,66|
|RFB15 - O usuário deve ser capaz de denunciar mensagens de outro usuário|9|9|27|1,74|7|1,43|8|1,62|0,72|
|RFB16 - O usuário deve ser capaz de buscar canais/lives|9|9|27|1,74|8|1,64|7|1,42|0,60|
|RFB17 - O usuário deve ser capaz de consultar seu saldo de bits (Twitch Wallet)|7|8|22|1,42|7|1,43|6|1,21|0,59|
|RFB18 - O usuário deve ser capaz de consultar seu histórico de pagamentos|8|8|24|1,55|7|1,43|6|1,21|0,59|
|RFB19 - O usuário deve ser capaz de consultar seu histórico de bits|7|8|22|1,42|7|1,43|7|1,42|0,66|
|RFB20 - O usuário deve ser capaz de adicionar/editar/excluir métodos de pagamentos|9|9|27|1,74|9|1,84|9|1,82|0,66|
|RFB21 - O usuário deve ser capaz de receber Drops e Recompensas, apoiando criadores da Twitch|7|7|21|1,36|6|1,23|8|1,62|0,79|
|RFB22 - O usuário deve ser capaz de resgatar Loots do Prime Gaming|6|6|18|1,16|7|1,43|7|1,42|0,66|
|RFB23 - O usuário deve ser capaz de consultar seus Drops e Recompensas|7|8|22|1,42|7|1,43|7|1,42|0,66|
|RFB24 - O usuário deve ser capaz de consultar suas inscrições|9|8|26|1,68|8|1,64|8|1,62|0,66|
|RFB25 - O usuário deve ser capaz de configurar o seu perfil|9|9|27|1,74|8|1,64|8|1,62|0,66|
|RFB26 - O usuário deve ser capaz de configurar sua Imagem do perfil|9|8|26|1,68|6|1,23|8|1,62|0,79|
|RFB27 - O usuário deve ser capaz de configurar seu Banner do perfil|8|7|23|1,48|7|1,43|9|1,82|0,78|
|RFB28 - O usuário deve ser capaz de configurar seu Nome de usuário|9|9|27|1,74|6|1,23|7|1,42|0,73|
|RFB29 - O usuário deve ser capaz de configurar seu Nome de Exibição|9|9|27|1,74|6|1,23|7|1,42|0,73|
|RFB30 - O usuário deve ser capaz de configurar sua Biografia|9|8|26|1,68|7|1,43|9|1,82|0,78|
|RFB31 - O usuário deve ser capaz de desabilitar sua conta da Twitch|9|9|27|1,74|7|1,43|9|1,82|0,78|
|RFB32 - O usuário deve ser capaz de alterar a cor do chat|7|6|20|1,29|6|1,23|6|1,21|0,66|
|RFB33 - O usuário deve ser capaz de escolher o conjunto de emojis que ele utilizará|7|6|20|1,29|6|1,23|6|1,21|0,66|
|RFB34 - O usuário deve ser capaz de gerenciar as notificações de sua conta|8|8|24|1,55|7|1,43|6|1,21|0,59|
|RFB35 - O usuário deve ser capaz de vincular sua  conta da Twitch a outras plataformas(Twitter, Amazon, Steam, Discord, Youtube)|8|8|24|1,55|9|1,84|9|1,82|0,66|
|RFB36 - O usuário deve ser capaz de realizar ajustes nos conteúdos sugeridos|9|8|26|1,68|8|1,64|8|1,62|0,66|
|RFB37 - O usuário deve ser capaz de alterar o idioma da plataforma|8|9|25|1,61|8|1,64|8|1,62|0,66|
|RFB38 - O usuário deve ser capaz de alterar o tema (claro/escuro) da plataforma|7|7|21|1,36|7|1,43|6|1,21|0,59|
|RFB39 - O usuário deve ser capaz de realizar o login na plataforma|9|9|27|1,74|8|1,64|7|1,42|0,60|
|RFB40 - O usuário deve ser capaz de realizar o logoff da plataforma|9|9|27|1,74|8|1,64|7|1,42|0,60|
|RFB41 - O usuário deve ser capaz de desabilitar a sua conta da Twitch|9|9|27|1,74|7|1,43|8|1,62|0,72|
|RFB42 - O usuário deve ser capaz de trocar sussurros com outros usuários|6|7|19|1,23|7|1,43|6|1,21|0,59|
|RFB43 - O usuário deve ser capaz de personalizar o seu canal|9|9|27|1,74|7|1,43|7|1,42|0,66|
|RFB44 - O usuário deve ser capaz de iniciar sua transmissão|9|9|27|1,74|9|1,84|9|1,82|0,66|
| | | | | | | | | | |
|Requisitos Não-Funcionais (BrainStorm)| | | | | | | | | |
|RNFB01 - Internacionalização: o sistema é capaz de apresentar diferentes idiomas|9|9|27|1,74|8|1,64|8|1,62|0,66|
|RNFB02 - Segurança: o sistema deve garantir proteção contra acesso não autorizado|9|9|27|1,74|9|1,84|9|1,82|0,66|
|RNFB03 - Portabilidade: o sistema deve ser disponível em diferentes plataformas(PCs, Smartphones, SmarTVs)|9|8|26|1,68|8|1,64|9|1,82|0,71|
|RNFB04 - Conformidade: o sistema deve cumprir todas as leis e regulamentos aplicáveis:cumpre as leis do país em operaçao|9|9|27|1,74|7|1,43|7|1,42|0,66|
|RNFB05 - Escabilidade: sistema é capaz de ter um bom desempenho sob uma carga de trabalhoaumentada ou crescente: Suporta um alto número de usuários ativos ao mesmo tempo|9|9|27|1,74|9|1,84|9|1,82|0,66|
|RNFB06 - Disponibilidade:o sistema deve estar disponível quando necessário, com um bomfuncionamento durante 24 horas|9|9|27|1,74|9|1,84|9|1,82|0,66|
| | | | | | | | | | |
|Requisitos Funcionais (Observação)| | | | | | | | | |
|OBS02 - O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo|9|9|27|1,74|9|1,84|9|1,82|0,66|
|OBS03 - O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo através de um provedor de
email como Gmail, Outlook|9|8|26|1,68|8|1,64|8|1,62|0,66|
|OBS05 - Ao sair de uma live e voltar para a página de início, o vídeo da live em formato de Thumbnaildeve estar pausada ou não existir|8|7|23|1,48|8|1,64|8|1,62|0,66|
|OBS08 - Ao acessar "Ajuste de Conteúdo", após o usuário selecionar as categorias que lhe interessa. O sistema deve sugeriros tipos de conteúdos voltados a sua escolha na maioria da interface
pausada ou não existir|7| |14|0,90|7|1,43|7|1,42|0,66|
|OBS06 - Para um novo usuário, o sistema de recomendação de Categorias deve mostrar os tipos de conteúdos que estãoem alta na plataforma|7|7|21|1,36|8|1,64|7|1,42|0,60|
|0BS09 - Ao acessar "Ajuste de Conteúdo", o usuário deve ter a opção de selecionar se deseja receber sugestõesde conteúdos categorizados para adultos|8|8|24|1,55|9|1,84|8|1,62|0,61|
|OBS10 - A plataforma deve colocar um efeito Blur nos Thumbnails para cada conteúdo categorizado como adulto ou 18+|9|9|27|1,74|8|1,64|8|1,62|0,66|
|OBS11 - A plataforma deve colocar uma etapa de confirmação, perguntado se o usuário deseja visualizar o conteúdocategorizado como adulto ou 18+|9|9|27|1,74|8|1,64|8|1,62|0,66|
| | | | | | | | | | |
|Requisitos Não Funcionais (Observação)| | | | | | | | | |
|OBS01 - O usuário deve ser capaz de consumir conteúdos sem se registrar na plataforma|8|8|24|1,55|9|1,84|8|1,62|0,61|
|OBS04 - O usuário deve estar cadastrado e logado para acessar as funcionalidades do sistema, com exceção o
acesso aos vídeos|9|8|26|1,68|9|1,84|8|1,62|0,61|
|OBS07 - Ao acessar "Ajuste de Conteúdo", no catálogo disponibilizado deverá ter somente a imagem do conteúdo semum ícone de coração|8|7|23|1,48|8|1,64|9|1,82|0,71|
|OBS012 - A barra de navegação de tipos de conteúdos deve aparecer na tela de início, mesmo estando logado|7|7|21|1,36|8|1,64|8|1,62|0,66|
|OBS13 - Na Barra de navegação de tipos de conteúdos deve ser adicionado o tipo Artes e Ciência|7|6|20|1,29|7|1,43|7|1,42|0,66|
|OBS14 - A experiência do usuário na questão de sugestões de conteúdo e o tipo de disponibilidade delas deve ser melhorlogado na plataforma|8|8|24|1,55|7|1,43|7|1,42|0,66|
| | | | | | | | | | |
| | | | | | | | | | |
|TOTAIS|523|503|1549|100,00|488|100,00|494|100,00| | |

<h6 align = "center"> Tabela 2: Priorização utilizando First Things First
<br>Fonte: Autor(es)</h6>

### 2.3 Escala de Três Níveis 

É uma priorização que agrupa os requisitos em três níveis: alta prioridade, média prioridade e baixa prioridade. É uma priorização subjetiva. Uma forma prática é dimensionar as prioridades com base em importância e urgência. Importância se refere sobre o quanto o requisito em análise é essencial para um objetivo de negócio da empresa. Urgência é relativa a necessidade que certo requisito precisa ser implementado.

Com isso temos:

- Alta prioridade: Alta importância e alta urgência.
- Média prioridade: Alta importância e baixa prioridade.
- Baixa prioridade: Baixa importância e baixa prioridade.
- Requisitos podem aparecer como urgente para certos stakeholders porém não tem uma praticidade em atingir objetivos de negócio. Esses requisitos não devem ser executados.

A seguir a tabela de priorização foi construída com sua devida prioridade e justificativa.

|**Identificador**|**Requisito**|**Priorização**|**Justificativa**|
|:---------------:|:-----------:|:-------------:|:---------------:|
|RFB01|O usuário deve ser capaz de assistir a uma live| Alta prioridade | O aplicativo tem como objetivo principal a trasnmissão de lives |
|RFB02|O usuário deve ser capaz de assistir a um VOD (Video on Demand)| Alta prioridade | Torna o aplicativo mais flexível para os usuários |
|RFB03|O usuário deve ser capaz de interagir em uma live| Alta prioridade | Essencial para a interação do produtor de conteúdo e o usuário |
|RFB04|O usuário deve ser capaz de comentar uma live | Alta prioridade | Importar para feedback do conteúdo que está sendo consumido |
|RFB05|O usuário deve ser capaz de clipar um trecho de uma live| Média prioridade | Importante para replay |
|RFB06|O usuário deve ser capaz de seguir um streamer| Alta prioridade | Essencial para o aplicativo entender o tipo de conteúdo o usuário gosta |
|RFB07|O usuário deve ser capaz de compartilhar o link de uma live| Média prioridade | Interressante para o usuário compartilhar um conteúdo com outros possíveis usuários |
|RFB08|O usuário deve ser capaz de se inscrever em um canal utilizando o Amazon Prime| Baixa prioridade | Não é essencial tendo em vista que o aplicativo tem outras opções de inscrição |
|RFB09|O usuário deve ser capaz de se inscrever em um canal pagando diretamente| Alta prioridade | Importante para evitar demora do processo para o usuário |
|RFB10|O usuário deve ser capaz de presentar uma inscrição para outro usuário| Baixa prioridade | Não é necessário para o objetivo do aplicativo |
|RFB11|O usuário deve ser capaz de reagir durante a transmissão| Baixa prioridade | Tendo em vista que é uma segunda opção de interação, não é de grande importância |
|RFB12|O usuário deve ser capaz de comprar bits| Média prioridade | É interessante para interação |
|RFB13|O usuário deve ser capaz de utilizar os bits para mandar mensagens ao streamer| Média prioridade | É interessante para uma priorização de mensagens ao streamer |
|RFB14|O usuário deve ser capaz denunciar uma transmissão ao vivo| Alta prioridade | É muito importante para identificar conteúdos proibidos e que ferem as diretrizes do aplicativo |
|RFB15|O usuário deve ser capaz de denunciar mensagens de outro usuário| Alta prioridade | É muito importante para identificação de usuários com má índole |
|RFB16|O usuário deve ser capaz de buscar canais/lives| Alta prioridade | Essencial pois segue o principal objetivo do aplicativo |
|RFB17|O usuário deve ser capaz de consultar seu saldo de bits (Twitch Wallet)| Alta prioridade | Importante para conhecimento do próprio usuário sobre seus bits |
|RFB18|O usuário deve ser capaz de consultar seu histórico de pagamentos| Alta prioridade | Importante para caso aconteça erro de pagamentos |
|RFB19|O usuário deve ser capaz de consultar seu histórico de bits| Alta prioridade | Importante para conhecimento do próprio usuário sobre seu histórico de bits |
|RFB20|O usuário deve ser capaz de adicionar/editar/excluir métodos de pagamentos| Alta prioridade | Importante para a própria segurança e controle do usuário |
|RFB21|O usuário deve ser capaz de receber Drops e Recompensas, apoiando criadores da Twitch| Baixa prioridade | Relevante porém não urgente |
|RFB22|O usuário deve ser capaz de resgatar Loots do Prime Gaming| Baixa prioridade | Relevante porém não urgente  |
|RFB23|O usuário deve ser capaz de consultar seus Drops e Recompensas| Baixa prioridade | Relevante porém não urgente |
|RFB24|O usuário deve ser capaz de consultar suas inscrições| Média prioridade | Importante para o usuário saber o que está consumindo |
|RFB25|O usuário deve ser capaz de configurar o seu perfil| Alta prioridade | Essencial para o controle do usuário sobre sua conta no aplicativo |
|RFB26|O usuário deve ser capaz de configurar sua Imagem do perfil| Alta prioridade | Essencial para edição do usuário dentro do aplicativo |
|RFB27|O usuário deve ser capaz de configurar seu Banner do perfil| Alta prioridade | Essencial para edição do usuário dentro do aplicativo |
|RFB28|O usuário deve ser capaz de configurar seu Nome de usuário| Alta prioridade | Essencial para edição do usuário dentro do aplicativo |
|RFB29|O usuário deve ser capaz de configurar seu Nome de Exibição| Alta prioridade | Essencial para edição do usuário dentro do aplicativo |
|RFB30|O usuário deve ser capaz de configurar sua Biografia| Alta prioridade | Essencial para edição do usuário dentro do aplicativo |
|RFB31|O usuário deve ser capaz de desabilitar sua conta da Twitch| Alta prioridade | Importante para o usuário ter controle sobre sua conta |
|RFB32|O usuário deve ser capaz de altear a cor do chat| Baixa prioridade | Irrelevante para o funcionamento do aplicativo |
|RFB33|O usuário deve ser capaz de escolher o conjunto de emojis que ele utilizará| Baixa prioridade| Relevante porém não urgente |
|RFB34|O usuário deve ser capaz de gerenciar as notificações de sua conta| Média prioridade | Importante para o usuário controlar suas notificações |
|RFB35|O usuário deve ser capaz de vincular sua conta da Twitch a outras plataformas (Twitter, Amazon, Steam, Discord, Youtube)| Baixa prioridade | Interessante porém irrelevante |
|RFB36|O usuário deve ser capaz de realizar ajustes nos conteúdos sugeridos| Média prioridade | Importante para o consumo do usuário sobre os conteúdos que ele gosta |
|RFB37|O usuário deve ser capaz de alterar o idioma da plataforma| Alta prioridade | Essencial para inclusão do usuário |
|RFB38|O usuário deve ser capaz de alterar o tema (claro/escuro) da plataforma| Baixa prioridade | Interessante porém não relevante |
|RFB39|O usuário deve ser capaz de realizar o login na plataforma| Alta prioridade | Essencial para os usuários cadastrados terem acesso ao aplicativo |
|RFB40|O usuário deve ser capaz de realizar o logoff da plataforma| Alta prioridade | Essencial para os usuários cadastrados encerrarem o acesso ao aplicativo |
|RFB41|O usuário deve ser capaz de desabilitar a sua conta da Twitch| Alta prioridade | Essencial para os usuários cadastrados apagarem sua conta dentro do aplicativo |
|RFB42|O usuário deve ser capaz de trocar sussurros com outros usuários| Baixa prioridade | Interesssante porém não urgente pois não é o objetivo do aplicativo |
|RFB43|O usuário deve ser capaz de personalizar o seu canal| Alta prioridade | Essencial para criadores de conteúdo movimentarem a plataforma |
|RFB44|O usuário deve ser capaz de iniciar sua transmissão| Alta prioridade | Essencial para o aplicativo que tem as lives como objetivo principal |
|RNFB01|Internacionalização: o sistema é capaz de apresentar diferentes idiomas| Alta prioridade | Importante para inclusão de diversos usuários |
|RNFB02|Segurança: o sistema deve garantir proteção contra acesso não autorizado| Alta prioridade | Essencial para conforto e segurança do usuário |
|RNFB03|Portabilidade: o sistema deve ser disponível em diferentes plataformas (PCs, Smartphones, SmarTVs)| Média prioridade | Importante para maior variedade e portabilidade dos usuários |
|RNFB04|Conformidade: o sistema deve cumprir todas as leis e regulamentos aplicáveis: cumpre as leis do país em operaçao| Alta prioridade | Essencial para funcionamento do aplicativo no país em operção |
|RNFB05|Escabilidade: sistema é capaz de ter um bom desempenho sob uma carga de trabalho aumentada ou crescente: Suporta um alto número de usuários ativos ao mesmo tempo| Alta prioridade | Essencial para prevenção de quedas e erros dentro do aplicativo |
|RNFB06|Disponibilidade:o sistema deve estar disponível quando necessário, com um bom funcionamento durante 24 horas| Alta prioridade | Essencial para uma boa avaliação e funcionamento do aplicativo |
| OBS01 | O usuário deve ser capaz de consumir conteúdos sem se registrar na plataforma | Alta prioridade | Essencial para usuários que ainda não realizaram o cadastro |
| OBS02 | O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo | Alta prioridade | Essencial para interação dentro do aplicativo |
| OBS03 | O usuário deve ser capaz de realizar seu cadastro dentro do aplicativo através de um provedor de email como Gmail, Outlook | Alta prioridade | Importante para um cadastro mais rápido no aplicativo |
| OBS04 | O usuário deve estar cadastrado e logado para acessar as funcionalidades do sistema, com exceção o acesso aos vídeos  | Alta prioridade | Essencial para obteção de dados e preferência do usuário |
| OBS05 | Ao sair de uma live e voltar para a página de início, o vídeo da live em formato de Thumbnail deve estar pausada ou não existir | Média prioridade | Importante para evitar insatisfação do usuário pela live continuar passando |
| OBS06 | Para um novo usuário, o sistema de recomendação de Categorias deve mostrar os tipos de conteúdos que estão em alta na plataforma | Alta prioridade | Importante para o usuário ter ciência do conteúdo em alta |
| OBS07 | Ao acessar "Ajuste de Conteúdo", no catálogo disponibilizado deverá ter somente a imagem do conteúdo sem um ícone de coração | Média prioridade | Para evitar incômodo ao usuário de curtir um conteúdo que não gostou |
| OBS08 | Ao acessar "Ajuste de Conteúdo", após o usuário selecionar as categorias que lhe interessa. O sistema deve sugerir os tipos de conteúdos voltados a sua escolha na maioria da interface | Alta prioridade | Importante para melhor experiência e satisfação do usuário |
| OBS09 | Ao acessar "Ajuste de Conteúdo", o usuário deve ter a opção de selecionar se deseja receber sugestões de conteúdos categorizados para adultos | Alta prioridade | Essencial para filtrar conteúdos para menores de 18 anos |
| OBS10 | A plataforma deve colocar um efeito Blur nos Thumbnails para cada conteúdo categorizado como adulto ou 18+ | Alta prioridade | Importante para evitar menores de 18 anos assistindo conteúdos inadequados |
| OBS11 | A plataforma deve colocar uma etapa de confirmação, perguntado se o usuário deseja visualizar o conteúdo categorizado como adulto ou 18+| Alta prioridade | Importante para evitar menores de 18 anos acessando conteúdos inadequados |
| OBS12 | A barra de navegação de tipos de conteúdos deve aparecer na tela de início, mesmo estando logado  | Alta prioridade | Essencial para uma melhor experiência de um possível usuário |
| OBS13 | Na Barra de navegação de tipos de conteúdos deve ser adicionado o tipo Artes e Ciência | Média prioridade | Essencial para um maior interesse dos usuários sobre esse assunto |
| OBS14 | A experiência do usuário na questão de sugestões de conteúdo e o tipo de disponibilidade delas deve ser melhor logado na plataforma | Média prioridade | Importante para uma melhora de interação |

<h6 align = "center"> Tabela 3: Priorização utilizando Escala de Três Níveis
<br>Fonte: Autor(es)</h6>

## 3. Bibliografia

> rfc2119 -- Bradner, S., "Key words for use in RFCs to Indicate Requirement Levels," RFC 2119, March 1997
> Método MosCoW. Voitto - BR, 01 ago. 2021. Disponível em https://www.voitto.com.br/blog/artigo/metodo-moscow

> Slides: Requisitos - Aula 07. Professores: Milene Serrano e Maurício Serrano.

## 4. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|---|---|---|---|---|
| 1.0 | 30/04/2023 | Criação e adição de priorização MoSCoW | Milena | Diógenes |
| 1.1 | 30/04/2023 | Adição de priorização First Things First| Diógenes | Milena |
| 1.2 | 01/05/2023 | Finalização de priorização First Things First| Diógenes | Milena |
| 1.3 | 17/05/2023 | Adição de priorização Escala de Três Níveis | Milena | Diógenes |

<h6 align = "center"> Tabela 3: Histórico de Versões
<br>Autor(es): Diógenes e Milena
<br>Fonte: Autor(es)</h6>
