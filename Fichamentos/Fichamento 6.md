# Detecting False Alarms from Automatic Static Analysis Tools: How Far are We?

Hong Jin Kang, Khai Loong Aw, and David Lo. 2022\. Detecting false alarms from automatic static analysis tools: how far are we? In Proceedings of the 44th International Conference on Software Engineering (ICSE '22). Association for Computing Machinery, New York, NY, USA, 698–709. [https://doi.org/10.1145/3510003.3510214](https://doi.org/10.1145/3510003.3510214) 

## 1\. Fichamento de Conteúdo

O artigo aborda o elevado índice de falsos positivos gerados por ferramentas de análise estática automatizadas, como o Findbugs, que representa um obstáculo significativo à sua adoção em ambientes de desenvolvimento de *software*. A pesquisa examina o conceito de "*Golden Features*", um conjunto de métricas que visam melhorar a detecção de avisos acionáveis, isto é, aqueles que realmente representam um erro que deve ser corrigido pelos desenvolvedores. Os pesquisadores conduziram uma análise detalhada, identificando problemas críticos como vazamento de dados e duplicação, que podem distorcer a percepção da eficácia desses métodos. Ao replicar estudos anteriores, eles descobriram que a performance otimista das "*Golden Features*" não se sustenta sob uma avaliação mais rigorosa e que a heurística usada para gerar os rótulos das Warnings é frequentemente ineficaz, refletindo uma realidade onde muitos avisos permanecem abertos e não são tratados adequadamente. Os resultados ressaltam a necessidade de abordagens mais rigorosas para a construção de conjuntos de dados que realmente representem o funcionamento das ASATs, indicando um caminho a seguir para melhorar a confiabilidade e utilidade dessas ferramentas no setor de Engenharia de Software.

## 2\. Fichamento Bibliográfico

1\. *False Positive* (Falso Positivo) refere-se a uma situação em que uma ferramenta de análise estática indica um problema que, na realidade, não é um erro no código. O artigo menciona que as taxas de falsos positivos podem chegar até 91%, o que atrapalha a adoção dessas ferramentas pelos desenvolvedores (página 1).

2\. *Golden Features* (Características Douradas) são um conjunto de 23 características identificadas que ajudam a detectar avisos acionáveis nas ferramentas de análise estática. Essas features foram definidas como as mais relevantes para aumentar a eficácia das detecções em comparação com dados anteriores (página 2).

3\. *Closed-warning heuristic* (Heurística de Aviso Fechado) é um método usado para rotular um conjunto de dados, onde um aviso é considerado acionável se estiver fechado em uma revisão de referência e o arquivo em questão não tiver sido deletado. Essa heurística é criticada no artigo por sua ineficácia em construir um *benchmark* adequado, pois pode rotular erroneamente muitos avisos (página 3, 10).

4\. *Action* (Ação) é definida como a disposição dos desenvolvedores em resolver um aviso gerado pelas ferramentas de análise. O artigo discute que muitos desenvolvedores não agem sobre os avisos, pois nem sempre os consideram bugs ou preferem não arriscar um fix (página 1).

5\. *Actionability Ratio* (Taxa de Ação) é a proporção de avisos que são efetivamente corrigidos em relação ao total de avisos gerados. O artigo descreve como a variação na temporalidade entre revisões pode afetar essa taxa, mostrando que alterações nesse intervalo resultam em diferenças significativas na periculosidade dos avisos (página 6, 7).

## 3\. Fichamento de Citações

*1\. "The large number of false alarms produced poses a barrier to adoption."*

*2\. "We found that several studies used an experimental procedure that results in data leakage and data duplication, which are subtle issues with significant implications."*

*3\. "The heuristic produces labels that do not agree with human oracles."*

*4\. "A closed warning is always actionable as long as the file has not been deleted, and an open warning is always unactionable."*

*5\. "Despite achieving excellent performance, the Golden Features have subtle bugs related to data leakage and data duplication."*

*6\. "Our analysis indicates that there may be delays before developers inspect static analysis warnings."*  
