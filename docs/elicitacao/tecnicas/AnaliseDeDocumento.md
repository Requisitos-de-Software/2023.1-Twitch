# Análise de Documento

## 1. Introdução

A Análise Documental é uma técnica de recolha de dados que abrange diversos tipos de documentos, também pode ser utilizada como técnica complementar de entrevistas, questionários e observação.

O Documento analisado é um artefato produzido pela Twitch de introdução a plataforma.

## 2. Metodologia

Para a realização dessa técnica, lemos o artefato chamado "Crator Camp" para entender as funcionalidades que a Twitch provê aos usuários criadores de conteúdos, vulgo [Streamers](../../modelagem/lexico.md#l01-streamer).

## 3. Resultados

### 3.1. Legendas

- DOC: Documentação
- RF: Requisito Funcional
- RNF: Requisito Não Funcional  

<center>

| Identificador | Requisitos | Tipo |
| --------------| ---------- | ---- |
| <div id="DOC01">DOC01</div> | Possibilidade de fazer uma transmissão ao vivo seja de um PC, Mac, Xbox, Playstation ou Celular | RF
| <div id="DOC02">DOC02</div> | Acesso a funcionalidades como chat e análise no Painel de Controle | RF
| <div id="DOC03">DOC03</div> | Progressão de [Streamers](../../modelagem/lexico.md#l01-streamer) para Afiliado e, em seguida, para Parceiro, com requisitos específicos em relação a horas transmitidas, transmissões em dias únicos, média de espectadores e seguidores alcançados | RF
| <div id="DOC04">DOC04</div> | Disponibilização de ótimas ferramentas aos Afiliados e Parceiros, como um botão de subscrição, ícone expressivo personalizado, receitas de anúncios, distintivos de subscritor e mais oportunidades de receita  | RF
| <div id="DOC05">DOC05</div> | Possibilidade de submeter um formulário de candidatura a Parceiro através do painel de controle | RF
| <div id="DOC06">DOC06</div> | Desbloqueio de funcionalidades como seguidores, chat, subscrições, ícones expressivos, distintivos de subscritor e receitas de anúncios, com a quantidade de funcionalidades desbloqueadas aumentando à medida que os [Streamers](../../modelagem/lexico.md#l01-streamer) avança de [Streamer](../../modelagem/lexico.md#l01-streamer) para Afiliado e Parceiro | RF
| <div id="DOC07">DOC07</div> | Cumprimento de requisitos específicos para avançar de [Streamers](../../modelagem/lexico.md#l01-streamer) para Afiliado e Parceiro, incluindo horas transmitidas, transmissões em dias únicos, média de espectadores e seguidores alcançados | RNF
| <div id="DOC08">DOC08</div> | Dificuldade em atingir o estatuto de Parceiro | RNF
| <div id="DOC09">DOC09</div> | Necessidade de criar uma ligação com o público e tornar o canal mais rentável para ter sucesso como criador na Twitch | RNF
| <div id="DOC10">DOC10</div> | O sistema deve possuir resposta rápida para ações como carregamento de lives, mensagens no chat e interações de usuário. com um tempo de resposta médio de menos de 2 segundos| RNF 
|<div id="DOC11">DOC11</div>|A plataforma deve ser capaz de aguentar inúmeros usuários e [Streamers](../../modelagem/lexico.md#l01-streamer)s usando a plataforma de forma concorrente, escalando horizontalmente o número de recursos| RNF 
|<div id="DOC12">DOC12</div>|A plataforma deve minimizar latência entre usuários e viewers, garantindo que o delay seja menor que 10 segundos| RNF 
|<div id="DOC13">DOC13</div>|O sistema deve ser capaz de lidar com picos de acesso, como grandes eventos ou lançamentos, sem degradação significante| RNF 
|<div id="DOC14">DOC14</div>|A plataforma deve suportar vídeos em alta resolução, permitindo ao [Streamers](../../modelagem/lexico.md#l01-streamer) realizar trasmissões acima de 4K, enquanto provê aos usuários a opção de adaptar a resolução de acordo com a conexão| RNF 
|<div id="DOC15">DOC15</div>|A plataforma deve permitir o playback de vídeos, sem bufferização ou interrupções, mesmo em alta demanda| RNF 
|<div id="DOC16">DOC16</div>|A plataforma deve ser compatível com uma ampla variedade de navegadores e dispositivos, incluindo navegadores populares como Google Chrome, Mozilla Firefox, Safari e Microsoft Edge, além de dispositivos desktop, laptops, smartphones e tablets.| RNF 
|<div id="DOC17">DOC17</div>|A plataforma deve funcionar em diferentes sistemas operacionais, como Windows, macOS e Linux, garantindo uma experiência consistente para os usuários, independentemente do sistema operacional que estão utilizando.| RNF 
|<div id="DOC18">DOC18</div>|Integração com Plataformas Externas: A Twitch deve fornecer APIs e recursos que permitam a integração fácil com outras plataformas e serviços externos, como sistemas de gerenciamento de conteúdo, ferramentas de streaming, serviços de pagamento e redes sociais.| RNF 
|<div id="DOC19">DOC19</div>|A plataforma deve ser acessível para usuários com necessidades especiais, incluindo suporte para tecnologias assistivas, como leitores de tela, recursos de alto contraste e legendas para pessoas com deficiência auditiva.| RNF 
|<div id="DOC20">DOC20</div>|A plataforma deve ser adaptável a diferentes regiões geográficas, suportando múltiplos idiomas, formatos de data/hora e preferências culturais específicas de cada região.| RNF 
|<div id="DOC21">DOC21</div>|A plataforma deve estar disponível para acesso e utilização pelos usuários durante a maior parte do tempo, minimizando períodos de inatividade não programada.| RNF
|<div id="DOC22">DOC22</div>|Caso ocorram falhas, a plataforma deve ser capaz de se recuperar de forma rápida e automática, garantindo que os usuários possam retomar suas atividades sem interrupções significativas.| RNF
|<div id="DOC23">DOC23</div>|A plataforma deve garantir a proteção dos dados dos usuários, prevenindo acessos não autorizados, ataques cibernéticos e vazamentos de informações confidenciais.| RNF
|<div id="DOC24">DOC24</div>|A plataforma deve ser capaz de lidar com um aumento na demanda e no número de usuários, garantindo um desempenho estável mesmo em períodos de pico de tráfego.| RNF
|<div id="DOC25">DOC25</div>|Todas as transações financeiras realizadas na plataforma devem ser protegidas e garantidas contra falhas ou corrupção de dados.| RNF
</center>

<h6 align = "center"> Tabela 1: Requisitos levantados utilizando a técnica da Observação. 
<br>Autor(es): Matheus
<br>Fonte: Autor(es)</h6>

![](../imagens/requisitos_por_analise.jpg)

<h6 align = "center"> Imagem 1: Funcionalidades desbloqueadas conforme o nível do <a href="../../../modelagem/lexico#l01-streamer">Streamer</a>.
<br>Fonte: <a href="https://www.twitch.tv/creatorcamp/pt-pt/paths/getting-started-on-twitch/twitch-101/">Twitch</a> </h6>

![](../imagens/requisitos_por_analise2.jpg)

<h6 align = "center"> Imagem 2: Requisitos para chegar ao status de Parceiro.
<br>Fonte: <a href="https://www.twitch.tv/creatorcamp/pt-pt/paths/getting-started-on-twitch/twitch-101/">Twitch</a> </h6>


## 4. Referências

> - Engenharia de Requisitos: Software Orientado ao Negócio. **Carlos Eduardo Vazquez**, **Guilherme Siqueira Simões**
> - Creator Camp. **Twitch**. Disponível em: <https://www.twitch.tv/creatorcamp/pt-pt/paths/getting-started-on-twitch/twitch-101/>
> Twitch Engineering Blog


## 5. Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
|---|---|---|---|---|
| 1.0 | 08/05/2023 | Criação e desenvolvimento do artefato | Matheus Phillipo | Brunna |
| 2.0 | 04/07/2023 | Versão final do artefato | Matheus Phillipo | Brunna |

<h6 align = "center"> Tabela 2: Histórico de Versões
<br>Autor(es): Matheus
<br>Fonte: Autor(es)</h6>