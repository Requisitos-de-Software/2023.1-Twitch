# Priorização

## 1. Introdução
O documento de priorização tem como objetivo definir uma prioridade para cada função ou funcionalidade utilizando técnicas de priorização. Tendo assim como objetivo auxiliar na essencialidade de cada funcionalidade do software desenvolvido, essa técnica é recomendada para projetos com curto prazo e limitação de recursos.

## 2. Técnicas de Priorização
Para fazer a priorização, o grupo em acordo escolheu duas técnicas: MoSCoW e First Things First. Essas técnicas foram escolhidas pela familiaridade dos membros e com isso uma opção mais adequada. 

### 2.1 MoSCoW
Essa é uma técnica siples onde basicamente para cada requisito, você deve atribuir uma letra onde cada uma tem um significado específico:
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
| OBS09 | Ao acessar "Ajuste de Conteúdo", o usuário deve ter a opção de selecionar se deseja receber sugestões de conteúdos categorizados para adultos | RF
| OBS10 | A plataforma deve colocar um efeito Blur nos Thumbnails para cada conteúdo categorizado como adulto ou 18+ | Must |
| OBS11 | A plataforma deve colocar uma etapa de confirmação, perguntado se o usuário deseja visualizar o conteúdo categorizado como adulto ou 18+| Must |
| OBS12 | A barra de navegação de tipos de conteúdos deve aparecer na tela de início, mesmo estando logado  | Must |
| OBS13 | Na Barra de navegação de tipos de conteúdos deve ser adicionado o tipo Artes e Ciência | Should |
| OBS14 | A experiência do usuário na questão de sugestões de conteúdo e o tipo de disponibilidade delas deve ser melhor logado na plataforma | Should |

<h6 align = "center"> Tabela 1: Priorização utilizando MoSCoW
<br>Fonte: Autor(es)</h6>

### 2.2 First Things First

## 3. Bibliografia

> rfc2119 -- Bradner, S., "Key words for use in RFCs to Indicate Requirement Levels," RFC 2119, March 1997
> Método MosCoW. Voitto - BR, 01 ago. 2021. Disponível em https://www.voitto.com.br/blog/artigo/metodo-moscow

## 4. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|---|---|---|---|---|
| 1.0 | 30/04/2023 | Criação e adição de priorização MoSCoW | Milena | Diógenes |
