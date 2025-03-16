# SLACC: simion-based language agnostic code clones

George Mathew, Chris Parnin, and Kathryn T Stolee. 2020\. SLACC: simion-based language agnostic code clones. In Proceedings of the ACM/IEEE 42nd International Conference on Software Engineering (ICSE '20). Association for Computing Machinery, New York, NY, USA, 210–221. [https://doi.org/10.1145/3377811.3380407](https://doi.org/10.1145/3377811.3380407) 

## 1. **Fichamento do Conteúdo**

O artigo apresenta a técnica SLACC (*Simion-based Language Agnostic Code Clones*), uma abordagem inovadora para a detecção de *clones* de código que opera entre diferentes linguagens de programação. O contexto em que esta pesquisa se insere é a necessidade crescente de ferramentas que consigam identificar semelhanças de código em sistemas que utilizam múltiplas linguagens, um cenário comum no desenvolvimento moderno de *software*. O problema abordado é a limitação das ferramentas tradicionais de *clone detection*, que geralmente operam apenas em uma única linguagem e não se adaptam a sistemas poliglotas. Para resolver essa questão, SLACC utiliza uma análise dinâmica que compara o comportamento de entrada e saída de fragmentos de código, denominados *simions*, permitindo a identificação de *clones* sem a necessidade de uma representação comum entre as linguagens analisadas. Os resultados obtidos com testes entre códigos escritos em Java e Python mostram que SLACC consegue detectar seis vezes mais grupos de *clones* com uma precisão superior em relação ao HitoshiIO, uma ferramenta de detecção de *clones* anterior. Este avanço não apenas melhora a detecção de *clones* mas também abre caminho para futuras aplicações em ferramentas de migração de linguagens e no aprendizado de novas linguagens de programação.

## 2. **Fichamento Bibliográfico**

1\. *Semantic code cloning* (clonagem de código semântico) refere-se à identificação de trechos de código que executam funções semelhantes, mesmo que estejam escritos em linguagens diferentes (página 1).

2\. *Simions* (simions) são fragmentos de código que são comparados com base no comportamento de entrada e saída, permitindo a detecção de clones independentemente da sintaxe ou tipo das linguagens (página 2).

3\. *Dynamic analysis* (análise dinâmica) é um método de detecção de clones que se concentra no comportamento em tempo de execução dos programas, ao invés de depender exclusivamente da análise estática do código fonte (página 1).

4\. *Precision* (%) (precisão %) é a métrica que indica a proporção de clones identificados corretamente em relação ao total de clones detectados, sendo que SLACC alcançou 94,1% de precisão na identificação de clones entre Java e Python (página 6).

5\. *Clone clusters* (clusters de clones) são grupos de funções que compartilham características semelhantes, baseados na análise de seu comportamento de entrada e saída. No estudo, SLACC conseguiu identificar um número significativo de clusters em comparação a ferramentas anteriores (página 4).

6\. *Input generation strategies* (estratégias de geração de entrada) envolvem a criação de dados de teste para executar funções analisadas, utilizando técnicas inspiradas em testes de caixa cinza, aumentando assim as chances de detectar comportamentos equivalentes (página 3).

## **3\. Fichamento de Citações**

1\. *"Successful cross-language clone detection could enable researchers and developers to create robust language migration tools, facilitate learning additional programming languages once one is mastered, and promote reuse of code snippets over a broader codebase."*

2\. *"SLACC identifies clones by comparing the IO relationship of segmented snippets of code from a target repository."*

*3\. "Like prior clone detection techniques, we use input/output behavior to match clones, though we overcome limitations of prior work by amplifying the number of inputs and covering more data types."*

*4\. "This is the first work to perform clone detection for dynamic typed languages (precision \= 87.3%) and the first to perform clone detection across languages that lack a common underlying representation (precision \= 94.1%)."*

*5\. "SLACC retrieves 6 times as many clusters and has higher precision (86.7% vs. 30.7%) compared to HitoshiIO, a recent clone detection tool for Java."*

*6\. "SLACC is open-source and the data used in this study is publicly available."*
