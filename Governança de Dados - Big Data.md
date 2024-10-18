## Governança de Dados

"Governança de Dados é o exercício de autoridade e controle (planejamento, monitoramento e execução) sobre o gerenciamento ativo de dados. A função de governança de dados guia como todas as outras funções da gestão de dados são realizadas. Governança de Dados é de alto nível, ou seja, é gestão estratégica de dados na esfera executiva." — DAMA

Através do atual guia DAMA-DMBOK, podemos compreender que a Gestão de Dados é uma disciplina formada pelo conjunto de dez funções de gerenciamento de dados integradas. A integração dessas funções é feita pela Governança de Dados, razão pela qual ela está localizada como elemento central do framework do DAMA-DMBOK.

![Governança de Dados](https://github.com/JonathanFacchinetti/Big-Data-e-Analytics/blob/main/Imagens/Governan%C3%A7a.png)

Uma política base para governança de dados deve compreender os seguintes pontos:

- Identificação de perfil e descoberta de dados para encontrar problemas na qualidade de dados.
- Monitoramento da qualidade e da linhagem de dados para administrar possíveis problemas de qualidade por toda a empresa e garantir que as expectativas de qualidade sejam atendidas.
- Gerenciamento de dados mestres para estabelecer uma visão única e confiável de clientes, produtos ou qualquer outro domínio de dados.
- Um glossário de negócios para definir padrões de termos e assegurar comunicações claras sobre a integração dos dados.
- Gerenciamento da vida útil das informações de aplicativos para controlar o crescimento dos dados e desativar com segurança os sistemas e aplicativos legados.

### Conjunto das funções definidas pelo guia DAMA-DMBOK para Gestão de Dados:

- **Gestão da Arquitetura de Dados:** Responsável por definir as necessidades de dados e alinhá-los com a estratégia de negócios da empresa.
- **Gestão de Desenvolvimento de Dados:** Responsável pelas atividades de modelagem e implementação das estruturas de dados no ciclo de vida de desenvolvimento dos sistemas.
- **Gestão de Operações de Dados:** Responsável por manter os dados armazenados ao longo de seu ciclo de vida.
- **Gestão da Segurança dos Dados:** Define e mantém as políticas de segurança da informação da empresa.
- **Gestão de Dados Mestres e Dados de Referência:** Garante a consistência e disponibilização de visões únicas dos principais dados reutilizados na empresa.
- **Gestão de Data Warehousing e Business Intelligence:** Define e controla os processos para prover dados de suporte à decisão, geralmente em aplicações analíticas.
- **Gestão de Documentação e Conteúdo:** Planeja, implementa e controla atividades para armazenar, proteger e acessar dados não estruturados.
- **Gestão de Metadados:** Representa o significado dos dados, incluindo tanto conteúdo técnico (estrutura, formato, restrições) quanto definições e conceitos.
- **Gestão da Qualidade dos Dados:** Promove, mede, avalia, melhora e garante a qualidade dos dados da empresa.

### Pilares da Governança de Dados:

A governança de dados vai além da gestão de dados operacionais e pode ser construída com base em quatro pilares:

#### 1. Estratégia
Contempla o alinhamento dos objetivos estratégicos e de negócios com os processos, dados e tecnologias. Suas principais atividades incluem:

- Elaboração dos objetivos de negócio.
- Identificação de necessidades futuras.
- Planejamento estratégico para atender aos requisitos futuros do negócio.
- Reavaliação periódica do planejamento.

#### 2. Qualidade
A qualidade está ligada à expectativa do consumidor em relação ao produto (informação). As principais atividades dessa área incluem:

- Entendimento das necessidades de Qualidade de Dados.
- Manutenção do nível de Qualidade de Dados.
- Definição e revisão de métricas de Qualidade de Dados.
- Monitoramento e ações para melhoria da qualidade.
- Data Stewardship (conjunto de práticas e responsabilidades associadas à gestão de dados).

#### 3. Gestão
Trata-se da adoção de políticas e melhores práticas para produção e consumo da informação. Principais atividades:

- Definição de políticas para coleta, armazenamento e uso de informações.
- Definição de procedimentos para proteção de dados.
- Atendimento de questões regulatórias.

#### 4. Arquitetura
Gestão do macroambiente de captação e manutenção das informações. Suas principais atividades:

- Mapeamento do ciclo de produção da informação.
- Integração de dados.
- Padronização e gerenciamento de metadados e modelagem de dados.

![Ciclo de Vida do Dado](https://github.com/JonathanFacchinetti/Big-Data-e-Analytics/blob/main/Imagens/Ciclo%20de%20Vida%20do%20dado.png)

Considerando o ciclo de vida do dado e da informação como tal expressado no DAMA-DMBoK, é possível identificar claramente as fases de responsabilidade de TI e de Negócios. De forma mais objetiva, podemos definir que Planejar, Especificar, e Disponibilizar a estrutura para receber o dado são fases que estão na esfera de coordenação da TI. Já Criar ou Adquirir, Manter e Usar, Arquivar e Recuperar, e por fim, Eliminar são fases inerentes ao negócio. O ciclo de vida do dado e da informação nos permite identificar a responsabilidade de cada um. 

### Data Stewards ou Administrador de Dados

Segundo Gartner, empresas europeias classificaram a qualidade de dados deficiente. Gartner diz que as organizações devem estabelecer regras de administração de dados para melhorar a qualidade dos dados. Segundo Gartner, empresas europeias classificaram a qualidade de dados deficiente como o segundo maior problema de inteligência de negócios. As organizações que se esforçam para melhorar a qualidade dos dados devem considerar a nomeação de administradores de dados, afirma Gartner. O sucesso da administração de dados exige que as organizações se movam em direção a uma cultura que considera os dados como um ativo competitivo ao invés de um mal necessário e que defina metas claras para a melhoria da qualidade dos dados.

"A qualidade dos dados é uma questão de negócios, não uma questão de TI, e exige do negócio assumir a responsabilidade e impulsionar melhorias. 

A nomeação de administradores de qualidade de dados ajuda as organizações a alcançar os objetivos de melhoria da qualidade dos dados. Esses indivíduos devem ser considerados peritos em assuntos para seus departamentos e agir como trustees de dados, em vez de proprietários deles. Eles irão garantir que a qualidade será mantida para suportar processos de negócios. Por exemplo, um especialista em Marketing do departamento de marketing da empresa poderia atuar como administrador de dados no programa de melhoria da qualidade dos dados, mantendo os dados de marketing completos, corretos, consistentes, confiáveis e não redundantes. Nessa função, eles têm a responsabilidade de assegurar as informações relevantes para o marketing seguir os padrões de qualidade dos dados corporativos. O desafio que já era enorme para a governança de dados ficou ainda maior com Big Data e os administradores de dados, apresentar novas soluções para estas complicações não será tão simples como as transações de dados estruturados.

## Lean Manufacturing

"Processos e procedimentos" podem lembrar burocracia, mas as empresas buscam agilidade, especialmente na TI, que pode ser um gargalo. A metodologia **Lean Manufacturing**, criada por Taiichi Ohno (Toyota), popularizada por James P. Womack e Daniel T. Jones, é uma filosofia de gestão focada em eliminar desperdícios.

Governança de dados ágil foca em capacitar pessoas para fazer as coisas certas, como ensinado por Scott Ambler no **Instituto Agile Data**. Cinco passos importantes são:

1. **Ativos Corporativos Valorizados:** Padrões e convenções adotados quando agregam valor aos desenvolvedores.
2. **Incluir Profissionais de Dados nas Equipes:** Evitar grupos externos e fomentar a colaboração.
3. **Educar Desenvolvedores:** Ensinar os benefícios do MDM (Master Data Management).
4. **Pipeline de Projeto Guiado por Negócios:** Garantir alinhamento entre TI e os objetivos de negócio.
5. **Conformidade Integrada:** Automatizar processos de conformidade para evitar sobrecarga.

**Big Data** trouxe novos desafios de escalabilidade e governança. A **IBM** propôs o **Agile Information Governance Process (2014)**, com três fases: **Plan**, **Act**, e **Assess**, formando um ciclo contínuo. A governança ágil equilibra o uso rápido de dados com controle adequado.

![IBM Agile Information Governance Process](https://github.com/JonathanFacchinetti/Big-Data-e-Analytics/blob/main/Imagens/IBM.png)

O IBM Agile Information Governance Process consiste em seis etapas e três fases distintas. Na fase do Plan, as equipes de governança de dados definem o problema do negócio, obtêm patrocínio executivo, alinham com as equipes e entendem o risco e o valor dos dados. Na fase da Act, as organizações implementam um ou mais projetos baseados em casos de uso comum. Finalmente, na fase de Assess, as equipes de governança de dados medem os resultados. 

O IBM Agile Information Governance Process é construído como um loop contínuo. À medida que as equipes de governança de dados medem resultados em um projeto, elas começam de novo definindo o problema de negócios que pode gerar projetos adicionais. Uma notável diferença entre a governança da velha escola e a governança ágil é a suposição de que os projetos irão entrar e começar a usar os dados sem necessariamente se preocupar com qualidade e consistência. 

- Os dados podem ser carregados como estão porque os elementos de dados críticos e as relações podem não ser totalmente compreendidos. 
- Os dados podem ser semiestruturados ou não estruturados e podem estar em qualquer quantidade.
