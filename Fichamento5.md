# Sampling Projects in GitHub for MSR Studies

Dabic, Ozren; Aghajani, Emad; Bavota, Gabriele; "Sampling Projects in GitHub for MSR Studies" in 2021 IEEE/ACM 18th International Conference on Mining Software Repositories (MSR), pp. 1-5, Marcço de 2021. doi: 10.1109/MSR52588.2021.00074

## 1. Fichamento de Conteúdo

O artigo científico aborda sobre o estudo da mineração de repositórios e como deve ser feito essa coleta de dados dos repositórios de software. Esses repositórios
geralmente são coletados da hospedagem de serviço de um determinado site, um exemplo abordado nesta pesquisa científica pelos autores é o site de hospedagem 
GitHub onde é usado critérios de seleção específicos ditados por quem deseja minerar determinado tipo de repositório. Um exemplo citado pelos autores a respeito 
da mineração de repositórios, é caso deseje fazer um estudo relacionado a licenciamento pode estar interessado em selecionar projetos declaramento explicitamente 
uma licença. No artigo os autores trazem como objetivo mostrar que uma vez definido os critérios de seleção, utilitários como as _Application Programming interface_ (API)
do GitHub podem ser usados para “consultar” o serviço de hospedagem. Entretanto, os pesquisadores acabam lidando com as limitações de usos impostas por essas 
API’s com a falta de informações necessárias. Um exemplo que dão da limitação destas API’s de pesquisa pelo GitHub é que elas permitem somente 30 solicitações por
minuto, e quando pesquisa sobre os repositórios fornecem informações limitadas (como o número de commits de um repositório não está incluído). Para isso os autores 
apresentam o GitHub Search, onde um conjunto de dados contendo 25 características (como commits, licenças, entre outras informações relevantes) de 735.669 repositórios
escritos em 10 linguagens de programação, o conjunto de características foi derivado da procura de critérios de seleção da procura de projetos usados com frequência em 
estudos relacionados a _Mining Software Repositories_ (MSR) e o conjunto de dados é atualizado continuamente para sempre fornecer dados atualizados sobre os projetos
existentes e aumentar o número de projetos indexados. O resultado com o GitHub Search foi positivo na hora de realizar a requisição nos repositórios minerados, visto que, 
ao ser consultado através de uma aplicação que foi construída pelos pesquisadores permite definir muitas combinações de critérios para um estudo.

## 2. Fichamento Bibliográfico 

* _Repository Miner_ (Repositorio Minerado) este é o componente principal que orquestra a coleta do conjunto de dados do GitHub Search (página 2).
* _Data Storage_ (Armazenamento de dados) é o registro de informações em um meio de armazenamento. (página 3).
* _API_ (Application Programming interface) é um conjunto de serviços/funções que foram implementadas em um programa de computador que são disponibilizados para que outros programas/aplicativos possam utiliza-los diretamente de forma simplificada (página 1).

## 3. Fichamento de Citações 

* _"We are aware that mining CSS selectors as a strategy to collect information can require future updates if the GitHub UI substantially changes."_
* _"Otherwise, if there are less than 1,000 results for an interval, the algorithm iterates over the result list. "_
* _"The decision of only collecting repositories having at least 10 stars aims at drastically reducing the number of repositories we store and makes the data collection more scalable."_
