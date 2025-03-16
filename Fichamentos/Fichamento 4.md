# Comparison of Static Code Analysis Tools

M. Mantere, I. Uusitalo and J. Roning, "Comparison of Static Code Analysis Tools," 2009 Third International Conference on Emerging Security Information, Systems and Technologies, Athens, Greece, 2009, pp. 15-22, doi: 10.1109/SECURWARE.2009.10. keywords: {Information security;Open source software;Information analysis;Computer bugs;Performance analysis;Computer errors;Software quality;Application software;Humans;Failure analysis},

## 1\. Fichamento de Conteúdo

O artigo analisa a eficácia de três ferramentas de análise de código estático: *Fortify Source Code Analyzer (SCA), Splint e Frama-C*. O contexto aborda a crescente preocupação com a segurança do *software*, destacando que a baixa qualidade do código pode resultar em vulnerabilidades exploráveis. Os autores utilizam um código de demonstração com erros intencionalmente introduzidos para testar a performance das ferramentas. *Fortify SCA* é um analisador heurístico que não depende de anotações, enquanto *Splint* e *Frama-C* são ferramentas baseadas em anotações que oferecem uma análise mais detalhada, porém exigem maior conhecimento técnico dos desenvolvedores. Os resultados demonstram que *Fortify SCA* foi o mais fácil de usar e conseguiu identificar uma quantidade significativa de erros, enquanto *Splint* e *Frama-C*, embora mais limitados em sua usabilidade, mostraram potencial para detecção de problemas com uma utilização adequada de anotações. A conclusão destaca a importância de adotar ferramentas de análise de código estático em projetos de software, enfatizando a necessidade de conhecimento técnico para maximizar sua eficácia na melhoria da qualidade e segurança do código.

## 2\. Fichamento Bibliográfico

1\. Static Code Analysis Tools (Ferramentas de Análise de Código Estático) referem-se a softwares que ajudam na identificação de erros e vulnerabilidades no código-fonte de programas, auxiliando desenvolvedores a melhorar a qualidade e segurança do software (página 1).

2\. Fortify SCA (Fortify SCA) é uma ferramenta comercial de análise estática que utiliza uma abordagem heurística não baseada em anotações, permitindo fácil operação sem a necessidade de um conhecimento profundo da ferramenta por parte do usuário (página 2).

3\. Splint (Splint) é uma ferramenta de análise estática que emprega um sistema de anotações, voltada para a identificação de vulnerabilidades e erros em programas C. Seu uso adequado depende da capacidade do desenvolvedor em inserir anotações de forma eficaz (página 3).

4\. Frama-C (Frama-C) é uma ferramenta de análise estática também baseada em anotações, mas com um foco em análise correta. Ela exige um nível técnico mais elevado para a interpretação de seus resultados, oferecendo análises mais profundas e detalhadas (página 2).

5\. Annotations (Anotações) são instruções inseridas pelo desenvolvedor no código, que ajudam as ferramentas de análise a realizar verificações mais precisas, mas que requerem um investimento significativo de tempo e conhecimento para serem implementadas corretamente (página 7).

6\. Error Detection (Detecção de Erros) e a eficácia das ferramentas de análise estática dependem não só da qualidade do software, mas também da habilidade do auditor em interpretar e aplicar corretamente as informações fornecidas pelas ferramentas (página 6).

## 3\. Fichamento de Citações

*1\. "Low software quality is the biggest culprit when it comes to compromised information security."*

*2\. "Fortify SCA directly discovered eight errors, and correcting these led to remediation of the two errors concerning null pointer dereferences as well."*

*3\. "The tools based on annotations have good potential but demand more of their users."*

*4\. "Using up-to-date static analysis tools can be recommended for any serious software project as it will help to weed out some of the errors from the code."*

*5\. "With enough annotations, the software can be checked adequately even with Splint, but this demands close to the original amount of programming work in the annotation language, which can be new to many developers."*

*6\. "The task of manually going through the source code while searching for flaws is often enormously time-consuming and tedious."*  
