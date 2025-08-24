Este repositório apresenta o desenvolvimento e aplicação da distribuição Gompertz Refletida Unitária (RUGo), proposta como alternativa para modelar variáveis duplamente limitadas. A RUGo é um caso particular da família Weibull Estendida Complementar (CUEW) e possui função quantílica em forma fechada, o que possibilita sua reparametrização para modelagem de quantis condicionais.

Implementamos um modelo de regressão baseado na distribuição RUGo, com estimação dos parâmetros via máxima verossimilhança. As propriedades dos estimadores foram avaliadas por meio de simulações de Monte Carlo, considerando diferentes tamanhos amostrais (n ∈ {30, 70, 150, 300}) e 10.000 réplicas. As métricas analisadas incluem média, viés relativo percentual e erro quadrático médio (EQM).

Os resultados mostram que os estimadores de máxima verossimilhança da regressão RUGo apresentam boa performance e convergência para os valores verdadeiros em diferentes cenários.
