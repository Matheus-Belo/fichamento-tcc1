# What really changes when developers intend to improve their source code: a commit-level study of static metric value and static analysis warning changes

Trautsch, A., Erbel, J., Herbold, S. et al. What really changes when developers intend to improve their source code: a commit-level study of static metric value and static analysis warning changes. Empir Software Eng 28, 30 (2023). [https://doi.org/10.1007/s10664-022-10257-9](https://doi.org/10.1007/s10664-022-10257-9) 

## 1\. Fichamento de Conteúdo

O artigo investiga as mudanças que ocorrem no código-fonte quando desenvolvedores têm a intenção de melhorar a qualidade do *software*, empregando uma abordagem que analisa métricas estáticas e avisos de análise estática. O problema que o estudo busca resolver está relacionado à compreensão de como essas intenções impactam a qualidade do código e quais métricas se correlacionam com melhoras na qualidade. Para tanto, os pesquisadores analisaram uma amostra de 2.533 *commits* de 54 projetos de código aberto, classificando-os manualmente segundo a intenção do desenvolvedor — se eram mudanças perfeitivas, corretivas ou neutras. A classificação foi feita com base nas mensagens de *commit*, utilizando diretrizes estabelecidas. Os resultados revelam que *commits* focados em melhorias de qualidade são tipicamente menores em tamanho e que mudanças perfeitivas tendem a resultar em impactos positivos nas métricas de qualidade, enquanto mudanças corretivas afetam negativamente o tamanho e a complexidade do código. Esse estudo contribui para a compreensão da evolução da qualidade do *software* e fornece informações valiosas não apenas para pesquisadores, mas também para desenvolvedores e fornecedores de ferramentas de análise estática.

## 2\. Fichamento Bibliográfico

1\. *Static Metrics* (Métricas Estáticas) referem-se a avaliações quantitativas relacionadas a aspectos do código, como tamanho, complexidade e acoplamento, que são comumente utilizadas para prever defeitos e avaliar a qualidade do software (página 1).

2\. *Perfective Maintenance* (Manutenção Perfeitiva) consiste nas melhorias realizadas no software que visam aumentar sua qualidade e desempenho sem corrigir erros, geralmente identificadas através de mensagens de commit que expressam tal intenção por parte do desenvolvedor (página 7).

3\. *Corrective Maintenance* (Manutenção Corretiva) se refere às alterações feitas para corrigir defeitos ou bugs no código, frequentemente resultando em mudanças que podem aumentar a complexidade do software (página 29).

4\. *Change Type Classification* (Classificação de Mudanças) é um processo de categorizar commits em diferentes tipos de manutenção, baseado na intenção do desenvolvedor expressa nas mensagens de commit, utilizando diretrizes específicas para garantir a consistência da avaliação (página 8).

5\. *Impact on Metrics* (Impacto nas Métricas) indica como as alterações aplicadas, tanto perfeitivas quanto corretivas, afetam os valores das métricas de qualidade do código, com descobertas indicando que melhores compromissos têm efeitos positivos na maioria das métricas (página 29).

6\. *Size and Complexity Metrics* (Métricas de Tamanho e Complexidade) são análises quantitativas que medem aspectos como a quantidade de linhas de código e a dificuldade de compreensão do código, sendo utilizadas como indicadores de qualidade interna (página 7).

## 3\. Fichamento de Citações

*1\. "Static software metrics, e.g., size, complexity and coupling are used in defect prediction research as well as software quality models to evaluate software quality."* 

*2\. "We hypothesize that an improvement consciously applied by a developer via a perfective commit has a measurable, positive impact on software metric values."* 

*3\. "Our study results provide empirical evidence for which static source code metrics capture quality improvement from the developers point of view."* 

*4\. "The classification into categories is only done via the commit message as it expresses the intent of the developer on what the change should achieve."*

*5\. "Perfective commits are more often removing code and generally add fewer lines."*

*6\. "Our results for H2 show statistically significant differences in metric measurements between perfective commits and non-perfective commits."*  
