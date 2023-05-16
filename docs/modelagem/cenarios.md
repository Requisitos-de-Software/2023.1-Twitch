# Cenários

## 1. Introdução

O presente documento tem como objetivo criar cenários, que são descrições evolutivas de situações em um ambiente composto por um conjunto ordenado de interações entre seus participantes, realizadas por usuários ou sistemas externos [1]. 
Diante disso, os cenários são utilizados para descrever as situações de uso do sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos [1].

## 2. Metodologia

É possível descrever cenários de 5 maneiras, sendo elas:
- Texto narrativo;
- Texto estruturado;
- Diagramas;
- Imagens;
- Animações/ Simulações. 

Para apresentação dos cenários neste projeto foi escolhido o texto estruturado, onde é válido a utilização de linguagem natural semi-estruturada para uma compreensão mais clara de cada cenário. Podemos visualizar o modelo abaixo:


| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Finalidade do cenário                                                                        |
| Contexto   | Descrição de pré-condições, local (físico) e tempo                                           |
| Recursos   | Objetos passivos com os quais os atores interagem                                            |
| Atores       | Pessoa ou estrutura organizacional                                                           |
| Episódios  | Ação realizada por um ou vários atores com participação de outros atores utilizando recursos |
| Restrições | Imposição que restrinja um episódio de um cenário                                            |
| Exceção    | Tratamento para uma situação excepcional ou de erro                                          |

<h6 align = "center"> Tabela 1: Cronograma planejado do ponto de controle 1 </h6>
<h6 align = "center"> Fonte: [1], 2023 </h6>

## 3. Cenários identificados

Os cenários a seguir são baseados nos requisitos elicitados anteriormente. Para melhor visualização dos requisitos implementados e não implementos, os cenários identificados estão divididos em dois pontos. 

### 3.1 Cenários identificados implementados
Os cenários a seguir já estão implementados no aplicativo da Twitch.

#### C01: Criar conta 
O cenário a seguir é um cenário de criação de conta para um usuário novo do aplicativo da twitch.

| Elemento   | Descrição                                                             |
| ---------- | ----------------------------------------------------------------------- |
| Objetivo   | - Usuário criar uma conta                                               |
| Contexto   | - Local: casa <br> - Tempo: 3 a 5 minutos <br> - Pré-condições: dispositivo com aplicativo instalado  |
| Recursos   | - Dispositivo eletrônico com acesso a internet como: computador, smatphone, etc. <br> - Aplicativo twitch  |
| Atores     | - Usuário twitch    |
| Episódios  | - O usuário acessa o aplicativo Twitch <br> - O usuário aperta o botão "Cadastrar-se" <br> - O usuário preenche os campos obrigatórios: número de telefone ou gmail, nome de usuário, senha e data de nascimento <br> - O usuário coloca o código de confirmação enviado |
| Restrições | - Preenchimento incorreto <br> - Não recebimento do email com o código de confirmação           |
| Exceção    | - Falta de energia no dispositivo  <br> - Dispositivo danificado <br> - Falta de conexão com a internet       |

<h6 align = "center"> Tabela 2: Cenário de criação de conta no aplicativo Twitch </h6>
<h6 align = "center"> Fonte: Autor </h6>

#### C02: Login de usuário já cadastrado 
O cenário refere-se ao login de um usuário já cadastrado no aplicativo.

| Elemento   | Descrição |
| ---------- | --------- |
| Objetivo   | - Login na plataforma de um usuário já cadastrado |
| Contexto   | - Local: casa <br> - Tempo: 1 a 2 minutos <br> - Pré-condições: dispositivo com aplicativo instalado  |
| Recursos   | - Dispositivo eletrônico com acesso a internet como: computador, smatphone, etc. <br> - Aplicativo twitch |
| Atores     | - Usuário twitch |
| Episódios  | - O usuário acessa o aplicativo twitch <br> - O usuário preenche os campos obrigatórios: usuário e senha <br> - O usuário aperta o botão de entrar |
| Restrições | - O usuário não ter cadastro <br> - Preenchimento incorreto das informações |
| Exceção    | - Falta de energia no dispositivo  <br> - Dispositivo danificado <br> - Falta de conexão com a internet  |

<h6 align = "center"> Tabela 3: Cenário de login no aplicativo Twitch </h6>
<h6 align = "center"> Fonte: Autor </h6>

#### C03: Esquecer senha 
O cenário a seguir demonstra a redefinição de senha de um usuário ja cadastrado no aplicativo da twitch.

| Elemento   | Descrição |
| ---------- | --------- |
| Objetivo   | - Usuário redefinir senha |
| Contexto   | - Local: casa <br> - Tempo: 3 a 5 minutos <br> - Pré-condições: dispositivo com aplicativo instalado e acesso ao email cadastrado no aplicativo |
| Recursos   | - Dispositivo eletrônico com acesso a internet como: computador, smatphone, etc. <br> - Aplicativo twitch |
| Ator       | - Usuário twitch |
| Episódios  | - O usuário acessa o aplicativo da twitch <br> - O usuário aperta o botão "ENTRAR" <br> - O usuário aperta o botão "Problemas para efetuar login?" <br> - O usuário preenche com email ou número de telefone <br> - O usuário preenche com nome de usuário ou aperta o botão "Não sei meu nome de usuário" <br> - O usuário acessa o email recebido e aperta o botão "Redefinir senha" <br> - O usuário preenche dois campos com a nova senha <br> - O usuário efetua login no aplicativo normalmente, porém com a nova senha criada |
| Restrições | - O usuário não ter cadastro <br> - Preenchimento incorreto das informações <br> - O não recebimento do email de redefinição de senha |
| Exceção    | - Falta de energia no dispositivo  <br> - Dispositivo danificado <br> - Falta de conexão com a internet |     

<h6 align = "center"> Tabela 4: Cenário de redefinição de senha no aplicativo Twitch </h6>
<h6 align = "center"> Fonte: Autor </h6>

#### C04: Mandar um susurro 
O seguinte cenário demonstra o envio de susurro (mensagem de chat) no aplicativo da twitch para outro usuário da plataforma.

| Elemento   | Descrição |
| ---------- | --------- |
| Objetivo   | - Mandar um susurro (mensagem de chat) para outro usuário da twitch |
| Contexto   | - Local: casa <br> - Tempo: 3 a 5 minutos <br> - Pré-condições: dispositivo com aplicativo instalado e ser usuário cadastrado da twitch |
| Recursos   | - Dispositivo eletrônico com acesso a internet como: computador, smatphone, etc. <br> - Aplicativo twitch |
| Ator       | - Usuário twitch |
| Episódios  | - O usuário aperta o botão "Busca" <br> - O usuário busca pelo o outro usuário que ele deseja fazer o susurro <br> - O usuário aperta no perfil que ele deseja <br> - O usuário aperta no ícone com 3 pontos no lado superior direito da tela <br> - O usuário aperta o botão "Enviar susurro para (nome de usuário)" <br> - O usuário escreve o que deseja enviar na mensagem de susurro <br> - O usuário envia o susurro |
| Restrições |  - O usuário não ter cadastro <br> - O usuário não encontrar o outro usuário que deseja enviar o susurro <br> - O usuário não ter efetuado o login <br> - O usuário ter bloqueado susurros de desconhecidos |
| Exceção    | - Falta de energia no dispositivo  <br> - Dispositivo danificado <br> - Falta de conexão com a internet |

<h6 align = "center"> Tabela 5: Cenário envio de susurro no aplicativo Twitch </h6>
<h6 align = "center"> Fonte: Autor </h6>

#### C05: Fazer uma pesquisa 

| Elemento   | Descrição |
| ---------- | --------- |
| Objetivo   | - |
| Contexto   | - |
| Recursos   | - |
| Ator       | - |
| Episódios  | - |
| Restrições | - |
| Exceção    | - |


#### C06: Assistir uma live

| Elemento   | Descrição |
| ---------- | --------- |
| Objetivo   | - |
| Contexto   | - |
| Recursos   | - |
| Ator       | - |
| Episódios  | - |
| Restrições | - |
| Exceção    | - |


## Bibliografia

[1] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 12 de maio 2023.

## Histórico de Versão

| Versão | Data       | Descrição            | Autor(es)     | Revisor(es)   |
| :----: | ---------- | -------------------- | ------------- | ------------- |
| 1.0    | 12.05.2023 | Criação do documento e adição dos cenários | Milena Aires | - |
