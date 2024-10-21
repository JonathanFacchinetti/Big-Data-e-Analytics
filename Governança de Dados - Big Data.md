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
De acordo com o Gartner, muitas empresas europeias classificam a qualidade de dados como deficiente, sendo este o segundo maior problema de inteligência de negócios. O Gartner recomenda que as organizações implementem regras de administração de dados para melhorar essa qualidade. Para isso, é crucial nomear administradores de dados, que atuem como responsáveis pela garantia da qualidade, sem necessariamente serem proprietários dos dados. Esses administradores devem garantir que a qualidade dos dados seja mantida, a fim de suportar os processos de negócios. Um exemplo seria um especialista em marketing que atua como administrador de dados, assegurando que as informações relevantes para o marketing estejam completas, corretas, consistentes, confiáveis e sem redundâncias.

A qualidade dos dados é uma questão de negócios, não apenas de TI. Portanto, as empresas devem assumir a responsabilidade por impulsionar melhorias, estabelecendo metas claras e tratando os dados como um ativo competitivo. O aumento da complexidade da governança de dados com o advento do Big Data traz desafios adicionais para os administradores, especialmente em relação a dados não estruturados, provenientes de diversas fontes externas, como sistemas de transações, sensores, redes sociais e logs de sistemas. Nesses casos, os administradores de dados têm pouco controle sobre a qualidade das informações à medida que são criadas, o que complica ainda mais seu trabalho.

Um ponto de discordância frequentemente encontrado é a relação entre os cientistas de dados e os administradores de dados. Enquanto os administradores visam manter a qualidade e consistência dos dados, os cientistas de dados podem se opor a processos de limpeza que, segundo eles, podem distorcer resultados de análises avançadas. No entanto, embora cientistas de dados possuam habilidades diferenciadas para explorar advanced analytics, sua posição não resolve todos os problemas de qualidade de dados, especialmente quando lidamos com aplicações on-line e fluxos de integração contínua, que exigem governança rigorosa.

O uso de Big Data também introduz a persistência poliglota, com modelos NoSQL (Key/Value, Column Family, Graph, Documents), que contrastam com os tradicionais modelos de Entidade e Relacionamento. Essa mudança exige que administradores de dados, acostumados a schemas bem definidos, aprendam a trabalhar com modelos dinâmicos e schema-less. Mesmo assim, os desenvolvedores não devem ter total autonomia na criação e alteração de modelos, pois a governança de dados permanece sendo uma responsabilidade fundamental dos administradores, que precisam acompanhar a evolução do código e apoiar engenheiros de dados na escolha da melhor solução de persistência.

Ao lidar com Big Data, a redundância e a desnormalização dos dados se tornam parte integrante da solução, ao contrário da abordagem tradicional, onde o volume de dados é reduzido por meio da normalização. Isso representa uma grande mudança de paradigma para os administradores de dados, que precisam adaptar suas práticas e suportar essa nova realidade ao mesmo tempo em que mantêm as políticas e a qualidade adequadas.
## Lean Manufacturing

"Processos e procedimentos" podem lembrar burocracia, mas as empresas buscam agilidade, especialmente na TI, que pode ser um gargalo. A metodologia **Lean Manufacturing**, criada por Taiichi Ohno (Toyota) e popularizada por James P. Womack e Daniel T. Jones, é uma filosofia de gestão focada em eliminar desperdícios, garantindo eficiência e qualidade ao longo da cadeia produtiva.

### Governança de Dados Ágil

A governança de dados ágil foca em capacitar pessoas para tomar decisões rápidas e eficazes, como ensinado por Scott Ambler no **Instituto Agile Data**. Essa abordagem prioriza a colaboração entre equipes e a flexibilidade dos processos, visando a eliminação de gargalos e a adaptação contínua. Cinco passos importantes para a governança de dados ágil incluem:

1. **Ativos Corporativos Valorizados:** Padrões e convenções devem ser adotados somente quando agregam valor real aos desenvolvedores e ao negócio.
2. **Incluir Profissionais de Dados nas Equipes:** Evitar a criação de grupos externos e fomentar a colaboração direta entre equipes de TI e de negócios.
3. **Educar Desenvolvedores:** Ensinar os benefícios do MDM (Master Data Management) e boas práticas de gerenciamento de dados.
4. **Pipeline de Projeto Guiado por Negócios:** Garantir o alinhamento constante entre a TI e os objetivos estratégicos do negócio.
5. **Conformidade Integrada:** Automatizar os processos de conformidade para minimizar a sobrecarga e manter o foco na agilidade.

### Desafios de Big Data e Governança Ágil

Com o surgimento do **Big Data**, novos desafios de escalabilidade e governança surgiram. A necessidade de balancear o uso rápido e flexível dos dados com controles adequados é um ponto central. Nesse contexto, a **IBM** propôs o **Agile Information Governance Process (2014)**, que segue três fases principais: **Plan**, **Act**, e **Assess**, formando um ciclo contínuo de governança ágil.

![IBM Agile Information Governance Process](https://github.com/JonathanFacchinetti/Big-Data-e-Analytics/blob/main/Imagens/IBM.png)

#### Fases do Processo de Governança Ágil de Informação

1. **Plan (Planejar):** As equipes de governança de dados definem o problema de negócio, obtêm patrocínio executivo, alinham-se com as equipes de TI e compreendem o risco e o valor dos dados.
2. **Act (Agir):** As organizações implementam um ou mais projetos baseados em casos de uso relevantes e bem definidos.
3. **Assess (Avaliar):** As equipes de governança de dados medem os resultados dos projetos, avaliando seu impacto e ajustando processos para ciclos futuros.

O **Agile Information Governance Process** da IBM é estruturado como um ciclo contínuo, no qual os resultados de um projeto geram insights que conduzem a novos ciclos de melhoria e governança. Ao contrário da governança tradicional, a governança ágil permite que os projetos utilizem dados rapidamente, sem a necessidade de perfeição inicial em termos de qualidade e consistência. 

- Os dados podem ser carregados como estão, uma vez que os elementos críticos e as relações entre os dados podem não ser completamente compreendidos no início.
- Podem ser semiestruturados ou não estruturados, provenientes de várias fontes e em diferentes quantidades.

A abordagem ágil reconhece que, em muitos cenários, a velocidade e a flexibilidade são mais importantes do que a perfeição inicial dos dados, permitindo ajustes e melhorias contínuas à medida que os projetos avançam.
