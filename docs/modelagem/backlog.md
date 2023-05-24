# Backlog do produto

## 1. Introdução 

O presente documento refere-se ao backlog da plataforma Twitch e tem como objetivo criar uma lista de tarefas com breves descrições das funcionalidades com base nos requisitos elicitados: [Brainstorm](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/Brainstorm/), [Observação](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/observacao/) e [Análise Documental](https://requisitos-de-software.github.io/2023.1-Twitch/elicitacao/tecnicas/AnaliseDeDocumento/). O backlog traz valor comercial ao produto e é entregue ao cliente a cada sprint, sendo assim ele pode sofrer alterações durante a confecção do projeto. 

## 2. Metodologia 

Para o desenvolvimento do Product Backlog do projeto da Twitch, utilizamos uma estrutura dividida em 2 níveis, tendo em base as metodologias ágeis:

- **Épico**: Camada superior, composta por features que englobam diveras histórias de usuário.
- **História de Usuário**: Camada de detalhamento de um item/requisito a ser atendido.

As Histórias de Usuários e Épicos são definidas geralmente pelo PO(_Product Owner_) do projeto.

## 3. Épicos 

Épico é um conjunto de travalho que poder ser dividio em vários histórias menores. Geralmente são entregues em um conjunto de sprints pois pode ser alterado conforme o desenvolvimento cresce e relevando o feedback do cliente, os histórias de usuários podem ser adicionadas ou removidas. Para o projeto os épicos foram separados em:

- **Conteúdo**
- **Conta**.
- **Plataforma**.

#### EP01 - Acesso ao conteúdo 
Como usuário, desejo acesso ao conteúdo para entretenimento.

#### EP02 - Interação em lives 
Como usuário, desejo interagir nas lives para me comunicar.

#### EP03 - Bits
Como usuário, desejo obter bits para interagir com streamers.

#### EP04 - Conteúdo inapropriado 
Como usuário, desejo informar qualquer acontecimento inapropriado para evitar incômodo.


### 3.1 Épicos compactos 
Para um menor nível de abstração expresso nos temas, foram registrados os épicos anteriormente e na seguinte tabela foram relacionados as User Stories para melhorar a compreensão da tabela de Backlog.

<table>
    <tr>
        <th style="text-align: center" colspan=6> Backlog do produto </th>
    </tr>
    <tr>
        <td style="text-align: center"> <b> Tema  </b></td>
        <td style="text-align: center"> <b> Épico  </b></td>
        <td style="text-align: center"> <b> História de Usuário (US)  </b></td>
        <td style="text-align: center"> <b> ID </b></td>
        <td style="text-align: center"> <b> Prioridade  </b></td>
        <td style="text-align: center"> <b> Origem  </b></td>
     </tr>
     <tr>
        <!-- Tema  -->
        <td rowspan=9 style="vertical-align: middle"> Conteúdo </td>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> EP01</td>
        <!-- Histórias de Usuário (2) -->
        <td>Como usuário, quero	poder assistir a uma live.</td>
        <td>USB01</td>
        <td>Alta</td>
        <td>RFB01</td>
    </tr>
    <tr>
        <td>Como usuário,	quero poder assistir a um VOD (Video on Demand).</td>
        <td>USB02</a></td>
        <td>Média</td>
        <td>RFB02</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> EP02 </td>
        <!-- Histórias de Usuário (5) -->
        <td>Como usuário,	quero	poder interagir em uma live.</td>
        <td>USB03</td>
        <td>Alta</td>
        <td>RFB03</td>
    </tr>
    <tr>
        <td>Como usuário,	quero	poder comentar em uma live.</td>
        <td>USB04</td>
        <td>Média</td>
        <td>RFB04</td>
     </tr>
     <tr>
        <td>Como usuário,	quero	poder clipar um trecho de uma live.</td>
        <td>USB05</td>
        <td>Baixa</td>
        <td>RFB05</td>
     </tr>
     <tr>
        <td>Como usuário,	quero	poder compartilhar o link de uma live.</td>
        <td>USB06</td>
        <td>Média</td>
        <td>RFB07</td>
     </tr>
     <tr>
        <td>Como usuário,	quero	poder reagir durante a transmissão.</td>
        <td>USB07</td>
        <td>Média</td>
        <td>RFB011</td>
     </tr>
     <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> EP03 </td>
        <!-- Histórias de Usuário (2) -->
        <td>Como usuário,	quero	poder comprar bits.</td>
        <td>USB08</td>
        <td>Média</td>
        <td>RFB12</td>
     </tr>
     <tr>
        <td>Como usuário,	quero	poder utilizar bits para enviar mensagens ao streamer.</td>
        <td>USB09</td>
        <td>Média</td>
        <td>RFB013</td>
     </tr>
     <tr>
     <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> EP04 </td>
        <!-- Histórias de Usuário (2) -->
        <td>Como usuário,	quero	poder denunciar uma transmissão ao vivo.</td>
        <td>USB10</td>
        <td>Alta</td>
        <td>RFB14</td>
     </tr>
     <tr>
        <td>Como usuário,	quero	poder denunciar mensagens de outro usuário.</td>
        <td>USB01</td>
        <td>Alta</td>
        <td>RFB015</td>
      </tr>
      
</table>
  
## 4. Bibliografia

[1] Cap. 3 Desenvolvimento Ágil - Engenharia de Software PressmanArquivo;

## Histórico de Versão

| Versão | Data       | Descrição            | Autor(es)     | Revisor(es)   |
| :----: | ---------- | -------------------- | ------------- | ------------- |
| 1.0    | 23.05.2023 | Criação do documento | Rafael Nobre e Milena | Matheus |
| 1.1    | 24.05.2023 | Adição do tema conteúdo e épicos relacionados| Milena | - |
