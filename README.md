# Enzo Yamamura

## Tese de Conclusão de Curso - MBA USP São Paulo - Ciência de Dados (turma de 2021)
### Orientador: Jó Ueyama

A Hipótese do Mercado Eficiente argumenta que preços de ativos refletem de forma
eficiente toda informação disponível, com fatos inéditos sendo a única fonte de oscilações.
Notícias inédias são inerentemente impossíveis de antever, impossibilitando qualquer
estratégia de gerar lucros consistentes prevendo preços. Contudo, com o advento da Era da
Informação e aumento massivo de dados disponíveis, a tarefa de compilar e processar toda
informação disponível se tornou um problema de Big Data, com todas suas complexidades
e oportunidades inerentes. Atualmente, a mídia tradicional de notícias se tornou apenas
uma dentre uma miríade de fontes de informação, com muitos já preferindo se informar via
plataformas sociais. Logo, agentes humanos tem muito mais dados tanto para coletar quanto
para processar antes de tomarem decisões financeiras, o que pode gerar períodos em que os
preços dos ativos ainda não refletem plenamente todas as informações. Alternativamente,
um algoritmo pode processar gigabytes de informação e gerar acionáveis em questão de
segundos, talvez até antecipando tendências de mercado antes mesmo que suas contrapartes
humanas possam gerá-las. O intuito deste estudo é de analisar se a consideração de mídias
sociais pode ajudar a prever tais tendências, efetivamente contribuindo para gerar ganhos
em estratégias de investimento. Para tanto, utilizaram-se dados de comentários do Reddit
como proxy para sentimento de mercado em relação ao Bitcoin, uma criptomoeda renomada
pela sua natureza especulativa, definida exclusivamente por sua demanda. Uma relação
positiva é descoberta entre sentimentos agregados do Reddit acerca de Bitcoin e o preço
em dólares da criptomeda, o que é reiterado por quão bem seu preço histórico teria sido
predito em 2019 por um algoritmo de aprendizado profundo Long Short Term Memory,
treinado apenas com o previsor de sentimentos agregados do Reddit entre 2015 e 2018.
Logo, é provado que o uso de sentimentos de redes sociais é um meio eficaz para melhorar
a previsão de tendências do Bitcoin (e potencialmente de outros ativos), o que pode ser o
caso devido à sua natureza inerentemente especulativa ou até mesmo devido à concentração
de sua demanda no Reddit durante o período considerado

### Etapas
_obs: ler via https://nbviewer.org/ impede que as visualizações do Plotly desapareçam._

1. [Tratamento dos dados de Bitcoin](Tratamento_BTC.ipynb)
2. [Tratamento dos dados do Reddit](Tratamento_Reddit.ipynb)
3. [Análise Exploratória de Dados](EDA.ipynb)
4. [Aprendizado de Máquina](https://github.com/Yamamuen/MBA_thesis/blob/main/Final__Aprendizado_de_M%C3%A1quina.ipynb)


[Textual em PDF](TCC_final.pdf)
