# Elasticidade Preço de Venda do Frango Pelos Produtores

O aumento nas exportações de soja pode reduzir a oferta doméstica de soja disponível para o consumo interno, incluindo a ração para aves. Como o custo da ração é um fator relevante na produção de frango, isso pode elevar os custos de produção e, consequentemente, o preço do frango.

- Para cada aumento de 1% nas exportações de soja (em bilhões de dólares), espera-se que o preço médio de venda do frango pelos agricultores aumente 0,544%.

Os Gráficos 1 e 2 a seguir ilustram a similaridade das duas variáveis, fundamentando a relação positiva obtida pela matriz de correlação (Gráfico 3).

**Gráfico 1 - Exportação de Grãos de Soja em Bilhões de Dólares**

![Título do Gráfico](images/exp_soja_graos.png)

**Gráfico 2 - Preço de Venda do Frango Pelo Produtor em Reais**

![Título do Gráfico](images/preco_venda_frango.png)

**Gráfico 3 - Matriz de Correlação de Algumas Variáveis Analisadas**
![Título do Gráfico](images/matriz_corr.png)


# Metodologia

## Modelo log-log

Neste estudo, foi utilizado um modelo econométrico de regressão log-linear, também conhecido como modelo log-log. Os coeficientes obtidos representam variações percentuais, indicando como uma mudança percentual em X afeta Y. Como referência teórica, foi utilizado o livro *Econometria Básica* de Gujarati, 5ª edição.

## Base de Dados


- IBGE;
- ComexStata.

Para segmentar os dados de exportação, foi utilizado o mesmo critério dos estudos da Embrapa, onde os códigos do Sistema Harmonizado (SH4), foram:
- **1201:** a descrição do produto exportado é *soja, mesmo triturada* denominado no estudo como **soja em grãos;**
- **1507:** a descrição do produto exportado é *óleo de soja e respectivas frações, mesmo refinados, mas não quimicamente modificados* denominado no estudo como **óleo de soja;**
- **2304:** a descrição do produto exportado é *Tortas e outros resíduos sólidos da extração do óleo de soja* denominado no estudo como **farelo de soja.**


# Recomendação de Continuação do Estudo
A matriz de correlação revelou uma informação importante: enquanto as exportações de grãos de soja no Brasil têm aumentado durante o período analisado, as exportações de óleo de soja apresentam uma tendência de queda desde 2008.

**Gráfico 4 - Exportações de Óleo de Soja em Bilhões de Dólares**

![Título do Gráfico](images/exp_soja_oleo.png)

Com base na série histórica, a partir de 2002, quando ocorre a transição do poder executivo e o presidente se compromete a manter as políticas econômicas do governo anterior, com ênfase no tripé econômico, as exportações de commodities começam a crescer, beneficiando o agronegócio brasileiro com os altos preços dessas commodities. Como ilustrado no Gráfico 4, o valor das exportações de óleo de soja, impulsionado pelo aumento da produção de soja decorrente do boom das commodities, apresenta um crescimento significativo, alcançando seu pico em 2008. A acentuada queda nas exportações em 2009 pode ser atribuída à crise da bolha do mercado imobiliário nos Estados Unidos, que impactou o mercado financeiro global e afetou parceiros comerciais importantes do Brasil, como a China. No entanto, as políticas anticíclicas adotadas nesse período foram direcionadas à recuperação das exportações até 2011, quando essas começaram a diminuir marjoritariamente até o final do período observado, em 2021. Com os dados obtidos neste estudo, recomenda-se a continuação da pesquisa tendo como foco o motivo da redução das exportações do óleo de soja por um período tão longo.





