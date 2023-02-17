# An Empirical Evaluation of GitHub Copilot’s Code Suggestions

Nguyen, Nhan; Nadi,  Sarah. "An Empirical Evaluation of GitHub Copilot’s Code Suggestions", in In 19th International Conference on Mining Software Repositories, pp. 1 - 5, Maio 2022. doi: (https://dl.acm.org/doi/abs/10.1145/3524842.3528470).  

## 1. Fichamento de Conteúdo

Este artigo contextualiza o lançamento do GitHub Copilot que teve como empresas chave o GitHub e a OpenIA, sendo que este programa tem como finalidade fazer um 
"programador de par de IA" que acaba utilizando todo o poder de processamento de uma Linguagem Natural, Análise Estática, Síntese de Código e Inteligência Artificial. Dando 
uma descrição em linguagem natural para a funcionalidade de destino, o GitHub Copilot pode acabar gerando o código correspondente em várias outras linguagens de programação. 
Como os autores estão realizando um estudo empírico para avaliar a correção e a compreensibilidade do código sugerido pelo Copilot, foi-se utilizado 33 perguntas
LeetCode para que assim possa ser criado consultas para o Copilot em quatro tipos de linguagem de programação. Os pesquisadores avaliaram a exatidão de 132 soluções
que o Copilot trouxe correspondetes ao LeetCode fornecendo testes e avaliação de compreensão utilizando o ciclomático do SonarQube complexidade e métricas de complexidade cognitiva. 
Como resultado o Copilot trouxe a sugestão da linguagem Java ter a maior pontuação de correção com 57%, enquanto isso Javascript é o mais baixo resultando em meros 27%.
A conclusão final entre os dois autores, leva a crer que as sugestões do Copilot tem baixa complexidade sem diferenças notáveis entre as linguagens de programação, os autores
ressaltam também que é possível encontrar deficiências potenciais no Copilot como gerar código que pode ser ainda mais simplificado e código que depende de métodos auxiliares indefinidos.

## 2. Fichamento Bibliográfico 

* _Accepted_ (Aceito) código enviado passa em todos os casos de teste (página 2).
* _Wrong Answer_ (Resposta errada) o código enviado não contém erros, mas sua saída é diferente da saída esperada para pelo menos um caso de teste (página 2).
* _Compile Error_ (Erro de compilação) o código enviado não pode ser compilado (página 2).
* _Time Limit Exceed_ (Limite de tempo excedido) o código enviado não contém erros, mas pelo menos um caso de teste excede o tempo de execução permitido (página 2).
* _Runtime Error_ (Erro de tempo de execução) o código enviado tem pelo menos um caso de teste que falha devido a erros durante a execução (página 2).

## 3. Fichamento de Citações 

* _"Copilot generally produces understandable code. The median complexity values of Copilot’s solutions are well below the 15-25 thresholds typically used in static analysis tools."_
* _"We contacted Copilot’s team and confirmed that Copilot’s suggestions should not include the implementation of helper functions."_
* _"Copilot currently offers three main functionalities: convert comments to code, suggest tests matching implementation code, and autofill for repetitive code."_
* _"LeetCode’s coding environment also contains a set of test cases in multiple programming languages"_
