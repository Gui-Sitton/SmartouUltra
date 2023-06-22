# SmartouUltra

Sou aluno da TripleTen no curso de Ciência de Dados, estou divulgando projetos que desenvolvi para meu portifólio. Este é o sétimo projeto.

A operadora de celular Megaline está insatisfeita com o fato de muitos de seus clientes estarem usando planos antigos. Eles querem desenvolver um modelo que possa analisar o comportamento do cliente e recomendar um dos planos mais recentes da Megaline: Smart ou Ultra.
Você tem acesso a dados de comportamento dos assinantes que já mudaram para os novos planos (do projeto do curso de Análise de Dados Estatísticos). Para esta tarefa de classificação, você precisa desenvolver um modelo que escolherá o plano certo. Como você já executou a etapa de pré-processamento de dados, pode ir direto para a criação do modelo.
Desenvolva um modelo com a maior acurácia possível. Neste projeto, o limite para acurácia é 0,75. Verifique a acurácia usando o conjunto de dados de teste.

**Descrição de dados**

Cada observação no conjunto de dados contém informações comportamentais mensais sobre um usuário. As informações dadas são as seguintes:
* сalls — número de chamadas
* minutes — duração total da chamada em minutos
* messages — número de mensagens de texto
* mb_used — Tráfego de Internet usado em MB
* is_ultra — plano para o mês atual (Ultra - 1, Smart - 0)

**Conclusão**

Acredito que o modelo que mais tenha se destacado foi o RandomForestClassifier por ter confirmado as espectativas, com a maior precisão de quase 80%, sua velocidade de fato foi a mais baixa mas acredito que isso não seja um impecilio pois sua precisão alta faz valer a pena. Escolho este modelo também pelo método que trabalha, acredito ser o ideal para esta situação.
