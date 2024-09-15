**Universidade Catolica de Minas Gerais** 
*Projeto de Software*
**2024**
**Prof. João Paulo Carneiro Aramuni**
**Aluno: Jhonatan Gutemberg Rosa Ferreira**
## Resenha do artigo:
### Thoughtworks Technology Radar

*Rebeca Parsons, Rachel Laycock, Matin Fowler, Bharani, Birgitta Böckeler, Brandon
Byars, Camilla Falconi, Erik Dörnenberg, Fausto de la Torre, Hao Xu, James Lewis,
Marisa Hoening, Maya Ormaza, Mike Mason, Neal Ford, Pawan Shah, Scott Shaw,
Selvakumar Natesan, Shanggi Liu, Sofia Tania, Vanya Seth, Will Amaral*

O artigo "Thoughtworks Technology Radar"apresenta opiniões de referências em estraté-
gia, design e engenharia de software. Os temas abordados incluem técnicas, plataformas,
ferramentas, linguagens e frameworks, categorizados em quatro níveis de recomendação:
adote, experimente, avalie e evite.
As ferramentas no nível adote incluem Conan, Kaniko e Karpenter. Os autores re-
comendam que a comunidade de desenvolvimento as utilize quando forem adequadas ao
projeto.

Conan é uma ferramenta de código aberto utilizada para facilitar no gerenciamento
de dependências em projetos C/C++. Esta ferramenta pode ser utilizadas em várias
plataformas como servidores, dispositivos móveis, embarcados e desktops. Sua aplicação
aumenta a produtividade tendo em vista que ele facilita a integração de bibliotecas de
terceiros em projetos e também tem a capacidade de integrar com sistemas de compilação
e possui um SDK python para estender o sistema de compilação para tarefas de assina-
turas de códigos.

Kaniko é uma ferramenta para construir imagens de contêiner em pipelines baseados
em contêiner, destacando-se pela flexibilidade e melhor performance. Por fim os autores
indicam o Karpenter é um auto escalador de nós e tem se mostrado mais inteligente que
o Cluster Autoscaler. O Karpenter tem ganhado notoriedade em performance e ganhado
espaço entre os provedores de serviços Kubernetes em nuvem.
No nível experimente, são apresentadas ferramentas que valem a pena testar, com o
objetivo de explorar suas capacidades e entender como elas podem ser utilizadas no de-
senvolvimento.

42Crunch API Conformance Scan é uma ferramenta que realiza testes dinâmicos e visa
identificar discrepâncias entre o que está documentado e o que foi implementado. Ela apre-
senta o comportamento da API e apresenta formas de melhorias em relação a protocolos
de autenticação fracos, práticas inseguras de manipulação de dados e validade de entrada
ineficiente. Esta ferramenta se mostra eficiente agilizado o desenvolvimento e ajuda a
evitar que erros são colocado em sistemas em produção. A Action-runner-controller é
outra ferramenta apresentado no artigo e é controlador do Kubernetes que opera runners
auto hospedados para o GitHub Actions. Ela organiza e dimensiona os runners com base
no número de workflows em execução em um repositório qualquer,organização , enterprise
ou até cluster Kubernetes.

O contêiner do emulador Android busca simplificar a forma como os testes automa-
tizados, ao utilizar contêiner para produção de testes instrumentados que podem serem
executados automaticamente a cada commit e retornar o conteúdo do teste de modo ins-
tantâneo. O AWS CUDOS é uma ferramenta que busca apresentar os gastos a nível de
recursos e com isso auxilia na redução de custos para o acompanhamento de metas para
obtenção de melhores resultados operacionais.

Muitas outras ferramentas como Maestro, Microsoft SBOM tool, Velero, Gradio po-
dem ser encontradas de código aberto que visam ajudar a comunidade a melhorarem a
qualidade dos software seja nos testes, diminuindo a complexidade, seja melhorando o
fluxo de integração com pipelines de CI/CD, ou até mesmo na recupeção de desastres e
migrações de clusters agendados ou sob demanda.

Já no nível avalie, é onde os autores deixam claro que sempre será necessário anali-
sar o cenário de aplicação para compreender a viabilidade de cada situação.Os software
trazidos como aider, Akvorado, Cargo Lambda, Codium AI, Continue, LLaVa, Marimo,
entre outros são exemplos que podem influenciar no contexto do projeto.

Os software de códigos abertos estão de fato abrangentes e visam de forma colaborativa
auxiliar em todos os contextos de desenvolvimento. O aider visa auxiliar na programação
de sistemas, ele utiliza IA sendo possível utilizar chat para base de código em vários ar-
quivos. Outro é o Akvorado também de código aberto, este monitora e analisa rede. Ele
captura fluxos de rede, captura nomes de interfaces e informações e realiza o salvamento
dos fluxos atualizados para análises futuras.

Se tratando de eficiência e performance do Rust o Cargo Lambda tornou as função
em excelentes quando se fala em execução de funções lambda. Esta ferramenta integra ao
workflow do Rust e permite a executa e testar sem a necessidade de Docker na máquina
da pessoa desenvolvedora.

No espaço de assistentes de programação por IA, alguns produtos optam por aborda-
gens mais específicas. O Codium AI foca na geração de testes com IA, suportando várias
linguagens. O Continue é um assistente open-source integrado ao VS Code e JetBrains
IDEs, permitindo a experimentação com modelos de linguagem (LLMs) e eliminando a
necessidade de copiar código. O LLaVA, um modelo multimodal de código aberto, com-
bina visão e linguagem, destacando-se em tarefas de resposta a perguntas. Já o Marimo
oferece uma solução para notebooks Python, priorizando reprodutibilidade e interativi-
dade, ideal para prototipagem e análise de dados.

O Astro está ganhando popularidade por sua arquitetura de ilhas, que permite desen-
volver sites focados em conteúdo com HTML estático e mínimo JavaScript. O framework
facilita o uso de componentes JavaScript quando necessário, otimizando o carregamento
e garantindo alta performance de renderização e compilação. Seu aprendizado é rápido,
sendo uma boa escolha para aplicações multi-página.
O DataComPy é uma biblioteca Python útil para comparar DataFrames de pandas e

Spark, indo além das verificações básicas de igualdade ao fornecer insights detalhados so-
bre discrepâncias. Ele é amplamente utilizado por equipes para smoke testing de grandes
DataFrames, com suporte para tolerâncias numéricas e relatórios fáceis de interpretar. Já
o Pinia, uma biblioteca de gerenciamento de estado para Vue.js, oferece uma API simples
e enxuta com suporte sólido ao TypeScript, sendo uma alternativa recomendada ao Vue.
Já o Ray, framework de computação distribuída, permite escalar código Python e IA
de laptops para clusters, sendo utilizado por empresas como OpenAI para treinamento
e inferência de modelos. A linguagem o Mojo é uma nova linguagem de programação
voltada para IA, combinando a sintaxe do Python com recursos de sistemas e meta pro-
gramação, prometendo melhorias significativas em otimização e desempenho para IA. Por
outro lado, o LangChain, antes popular, é agora recomendado para evitar devido à sua
complexidade crescente e inconsistência na API, com alternativas como Semantic Kernel
sendo mais indicadas.

As tecnologias, linguagens e frameworks mencionados, entre outras, foram apresenta-
das com o objetivo de estimular o interesse em conhecê-las e avaliar sua viabilidade nos
projetos, promovendo o aprendizado e a disseminação de conhecimento entre todos os
envolvidos.