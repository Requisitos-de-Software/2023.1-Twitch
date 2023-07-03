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

- **[EP01 - Conteúdo](#311-ep01-conteudo)**
- **[EP02 - Conta](#312-ep02-conta)**.
- **[EP03 - Plataforma](#313-ep03-plataforma)**.

### 3.1 Épicos compactos

Para um menor nível de abstração expresso nos temas, foram registrados os épicos anteriormente e na seguinte tabela foram relacionados as User Stories para melhorar a compreensão da tabela de Backlog.

#### 3.1.1 EP01 - Conteúdo

O épico de Conteúdo refere-se às features que devem ser implementadas, que tem relacionamento com o conteúdo que a plataforma da Twitch oferece, como lives, clipes e VOD's.

<table style="border-collapse: collapse; border-spacing: 0" class="tg">
  <thead>
    <tr>
      <th
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
        colspan="5"
      >
        <span style="font-weight: 700">Backlog do produto</span>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)">Épico</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)"
          >História de Usuário (US)</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 25px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)">ID</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)"
          >Prioridade</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)"
          >Origem</span
        >
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
        rowspan="14"
      >
        <span style="font-weight: 400">EP01</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"
          >Como usuário, quero poder assistir a uma live.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB01">USB01</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Alta</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB01">RFB01</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"
          >Como usuário, quero poder assistir a um VOD (Video on Demand).</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB02">USB02</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Média</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB02">RFB02</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)"
          >Como usuário, quero poder interagir em uma live.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)"><a href="../user_stories#USB03">USB03</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)">Alta</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)"><a href="../../elicitacao/tecnicas/Brainstorm#RFB03">RFB03</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)"
          >Como usuário, quero poder comentar em uma live.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB04">USB04</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Média</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB04">RFB04</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)"
          >Como usuário, quero poder clipar um trecho de uma live.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB05">USB05</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Baixa</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB05">RFB05</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)"
          >Como usuário, quero poder compartilhar o link de uma live.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB06">USB06</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Média</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB07">RFB07</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)"
          >Como usuário, quero poder reagir durante a transmissão</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB07">USB07</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Média</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB11">RFB11</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"
          >Como usuário, quero poder comprar bits.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB08">USB08</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Média</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB12">RFB12</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"
          >Como usuário, quero poder utilizar bits para enviar mensagens ao
          streamer.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB09">USB09</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Média</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB13">RFB13</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)"
          >Como usuário, quero poder denunciar uma transmissão ao vivo.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB10">USB10</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Alta</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB14">RFB14</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <span style="color: rgba(0, 0, 0, 0.87)"
          >Como usuário, quero poder denunciar mensagens de outro usuário.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../user_stories#USB11">USB11</a></span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400">Alta</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"><a href="../../elicitacao/tecnicas/Brainstorm#RFB15">RFB15</a></span>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: 400"
          >Como usuário, quero poder buscar canais/lives.</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB12">USB12</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB16">RFB16</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        Como usuário, quero poder consultar meu saldo de bits (Twitch Wallet).
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB13">USB13</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB17">RFB17</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: black;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        Como usuário, quero poder consultar meus Drops e Recompensas.
      </td>
      <td
        style="
          border-color: black;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB14">USB14</a>
      </td>
      <td
        style="
          border-color: black;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        Baixa
      </td>
      <td
        style="
          border-color: black;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: left;
          vertical-align: top;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB23">RFB23</a>
      </td>
    </tr>
  </tbody>
</table>

<h6 align = "center"> Tabela 1: Tabela de descrição do épico 1 (EP01)
<br>Autor(es): Rafael e Milena
<br>Fonte: Autor(es)</h6>

#### 3.1.2 EP02 - Conta

O épico de Conta é referente às configurações e personalizações das contas da Twitch, assim como ações que estão relacionadas à conta, como as funcionalidades de seguir e se inscrever.

<table style="border-collapse: collapse; border-spacing: 0" class="tg">
  <thead>
    <tr>
      <th
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
        colspan="5"
      >
        <span style="font-weight: 700">Backlog do produto</span>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)">Épico</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)"
          >História de Usuário (US)</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 25px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)">ID</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)"
          >Prioridade</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)"
          >Origem</span
        >
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
        rowspan="14"
      >
        <span style="font-weight: 400">EP02</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero&nbsp;poder seguir um streamer.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB15">USB15</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB06">RFB06</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder me inscrever em&nbsp;&nbsp;&nbsp;um canal
        utilizando o Amazon Prime.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB16">USB16</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Baixa
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB08">RFB08</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder me inscrever em&nbsp;&nbsp;&nbsp;um canal
        pagando diretamente.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB17">USB17</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB09">RFB09</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder presentear uma inscrição para outro usuário.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB18">USB18</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Baixa
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB10">RFB10</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder consultar minhas inscrições.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB19">USB19</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Média
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB24">RFB24</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder configurar o meu perfil.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB20">USB20</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB25">RFB25</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder configurar minha imagem do perfil.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB21">USB21</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB26">RFB26</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder configurar meu&nbsp;&nbsp;&nbsp;banner do
        perfil.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB22">USB22</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB27">RFB27</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder configurar meu nome de usuário.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB23">USB23</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB28">RFB28</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder configurar meu nome de exibição.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB24">USB24</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB29">RFB29</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder configurar&nbsp;&nbsp;&nbsp;minha biografia.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB25">USB25</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB30">RFB30</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder escolher o conjunto de emojis que irei
        utilizar.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB26">USB26</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Baixa
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB33">RFB33</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder gerenciar as notificações da minha conta.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB27">USB27</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Média
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB34">RFB34</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder vincular minha conta da Twitch a outras
        plataformas.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB28">USB28</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Baixa
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB35">RFB35</a>
      </td>
    </tr>
  </tbody>
</table>

<h6 align = "center"> Tabela 2: Tabela de descrição do épico 2 (EP02)
<br>Autor(es): Rafael e Milena
<br>Fonte: Autor(es)</h6>

#### 3.1.3 EP03 - Plataforma

O épico de Plataforma é referente a configurações e ajustes que o usuário pode fazer na plataforma, que dizem respeito à sua navegação e experiência de usuário.

<table style="border-collapse: collapse; border-spacing: 0" class="tg">
  <thead>
    <tr>
      <th
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
        colspan="5"
      >
        <span style="font-weight: 700">Backlog do produto</span>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)">Épico</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)"
          >História de Usuário (US)</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 25px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)">ID</span>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)"
          >Prioridade</span
        >
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          font-weight: bold;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: top;
          word-break: normal;
        "
      >
        <span style="font-weight: bold; color: rgba(0, 0, 0, 0.87)"
          >Origem</span
        >
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
        rowspan="9"
      >
        EP03
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero&nbsp;poder realizar ajustes nos
        conteúdos sugeridos.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB29">USB29</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Média
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB36">RFB36</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder alterar o idioma da plataforma.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB30">USB30</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB37">RFB37</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder alterar o tema&nbsp;&nbsp;&nbsp;(claro/escuro)
        da plataforma.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB31">USB31</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Baixa
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB38">RFB38</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder realizar login na plataforma.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB32">USB32</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB39">RFB39</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder realizar logout da plataforma.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB33">USB33</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB40">RFB40</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder desabilitar minha conta da Twitch.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB34">USB34</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB41">RFB41</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero poder trocar sussurros com outros usuários
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB35">USB35</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Baixa
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB42">RFB42</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero ser capaz de personalizar o meu canal.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB36">USB36</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB43">RFB43</a>
      </td>
    </tr>
    <tr>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Como usuário, quero ser capaz de iniciar minha transmissão.
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../user_stories#USB37">USB37</a>
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        Alta
      </td>
      <td
        style="
          border-color: inherit;
          border-style: solid;
          border-width: 1px;
          color: rgba(0, 0, 0, 0.87);
          font-family: Arial, sans-serif;
          font-size: 14px;
          overflow: hidden;
          padding: 10px 5px;
          text-align: center;
          vertical-align: middle;
          word-break: normal;
        "
      >
        <a href="../../elicitacao/tecnicas/Brainstorm#RFB44">RFB44</a>
      </td>
    </tr>
  </tbody>
</table>

<h6 align = "center"> Tabela 3: Tabela de descrição do épico 3 (EP03)
<br>Autor(es): Rafael e Milena
<br>Fonte: Autor(es)</h6>

## 4. Bibliografia

[1] Cap. 3 Desenvolvimento Ágil - Engenharia de Software PressmanArquivo;

## Histórico de Versão

| Versão | Data       | Descrição                                     | Autor(es)             | Revisor(es) |
| :----: | ---------- | --------------------------------------------- | --------------------- | ----------- |
|  1.0   | 23.05.2023 | Criação do documento                          | Rafael Nobre e Milena | Matheus     |
|  1.1   | 24.05.2023 | Adição do tema conteúdo e épicos relacionados | Milena                | Rafael      |
|  1.2   | 24.05.2023 | Adição das tabelas do épicos relacionados     | Milena e Rafael       | Brunna      |
|  1.3   | 03.07.2023 | Ajustes de tabela                             | Rafael                |      -      |
