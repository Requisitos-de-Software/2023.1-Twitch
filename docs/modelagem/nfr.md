## 1. Introdução
O NFR (Non-Functional Requirements) Framework é uma abordagem para definir e gerenciar requisitos não funcionais de um sistema. Ele fornece uma estrutura para identificar, especificar, avaliar e validar aspectos como desempenho, segurança, usabilidade e escalabilidade. O NFR Framework auxilia no planejamento e desenvolvimento de sistemas que atendam a esses requisitos críticos para o sucesso do projeto.

Segundo a dissertação de Reinaldo Antônio da Silva,  O NFR Framework é uma abordagem para representar e analisar Requisitos Não-Funcionais. Seu objetivo é ajudar desenvolvedores na implementação de soluções personalizadas, levando em consideração as características do domínio e do sistema em questão. Tais características incluem Requisitos Não-funcionais, Requisitos funcionais, prioridades e carga de trabalho. 

O Framework utiliza o conceito de softgoal: um objetivo que não possui uma clara definição nem critérios de satisfação precisos. Os softgoals são utilizados para representar Requisitos Não-Funcionais e podem estar inter-relacionados, expressando a influência de um softgoal em outro.

Os softgoals e os seus inter-relacionamentos são representados em um grafo de interdependência de softgoals chamado SIG. Tal grafo será representado abaixo nesse documento.

## 2. Metodologia

O funcionamento do NFR framework pode ser visualizado em termos da construção, elaboração, análise e revisão incremental e interativa de um gráfico de interdependência 31 de softgoal conhecido como "Softgoal Interdependency Graph (SIG)". Este gráfico registra as considerações do desenvolvedor sobre os softgoals e mostra suas interdependências. Os SIGs armazenam um registro completo das decisões de desenvolvimento e da lógica do projeto de forma gráfica e concisa.

Para construir o SIG, o grupo decidiu usar a metodologia de construção descrita na dissertação do Reinaldo Antonio. Na dissertação, é abordado três tipos de softgoals:

- **Softgoals NFR**: representam os Requisitos Não- Funcionais e podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica no desenvolvimento do projeto
- **Softgoals de Operacionalização**: representam soluções de implementação para satisfazer softgoals NFR ou outros softgoals de operacionalização. Essas soluções incluem operações, processos, representações de dados, estruturações e restrições no sistema alvo para atender às necessidades indicadas pelos softgoals NFR e de operacionalização
- **Softgoals de Afirmação**:permitem que as características do domínio (como prioridades e carga de trabalho) sejam consideradas e devidamente refletidas no processo de tomada de decisão. Eles servem como justificativa para apoiar ou negar a forma como os softgoals são priorizados, refinados e os componentes são selecionados

<center>

![SoftGoals_tipos](./imagens/softgoal_tipos.png){ width=300 }

<h6 align = "center">Figura 1: Tipos de Softgoal.
<br>Fonte(es): (SILVA, 2019, p. 31).
</h6>
</center>

- **Interdependências**: as relações entre os softgoals podem ser divididas em 4 tipos diferentes de decomposição, conforme a figura 2

<center>

![interdependencia_tipos](./imagens/interdependencia_tipos.png){ width=500 }

<h6 align = "center">Figura 2: Tipos de Interdependência.
<br>Fonte(es): (SILVA, 2019, p. 31).
</h6>
</center>

- **Contribuições**: A fim de descrever a satisfação de um softgoal descendente em relação a um ascendente, podem ser usadas algumas contribuições. No projeto serão usadas duas:
    
    **AND**: Os softgoals ascendentes só são satisfeitos se os descendentes também forem.
    
    **OR**: Se algum softgoal descendente for satisfeito, o ascendente também já será satisfeito.
    
    **MAKE(++)**: Ao usar a contribuição suficientemente positiva (MAKE), se o softgoal descendente for satisfeito, o softgoal ascendente também será satisfeito.
    
    **HELP(+)**: Ao usar a contribuição parcialmente positiva (HELP), se o softgoal descendente for parcialmente satisfeito, o softgoal ascendente também será parcialmente satisfeito.

- **Procedimento de avaliação**: para determinar o grau de satisfação de um requisito não-funcional, algumas legendas podem ser usadas. A figura 3 ilustra o significado de cada:

<center>

![procedimento_avaliacao](./imagens/procedimento_avaliacao.png){ width=500 }

<h6 align = "center">Figura 3: Tipos de Procedimento de Avaliação.
<br>Fonte(es): (SILVA, 2019, p. 38).
</h6>
</center>

## 3. NFR Framework