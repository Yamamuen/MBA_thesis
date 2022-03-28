# Enzo Yamamura

## Tese de Conclusão de Curso - MBA USP São Paulo - Ciência de Dados (turma de 2021)
### Orientador: Jó Ueyama

Neste trabalho buscamos averiguar se existe ganho informacional no que tange a antecipação
de tendências do Bitcoin considerando sentimentos manifestados no fórum Reddit como
indicativo de humor de mercado. Em janeiro de 2021, usuários de um sub-fórum do Reddit,
/wallstreetbets, causaram, sozinhos, o short squeeze histórico nas ações da GameStop: em
protesto contra grandes grupos financeiros apostando na queda da ação, se coordenaram
na plataforma e compraram o ativo em massa, gerando grandes perdas para os que estavam
vendidos e ganhos exorbitantes para os que participaram do movimento. Consequentemente,
vários fundos passaram a monitorar não só o sentimento mas o volume de menções a ativos
específicos no fórum. Buscamos averiguar se influência análoga pode ser observada entre
2015 e 2019 para a criptomoeda Bitcoin, trazendo ganhos preditivos.

Estabelecemos que há associação positiva com indícios de causalidade, com sentimentos do
Reddit antecipando oscilações no Bitcoin, e concluímos ajustando um modelo de Long Short
Term Memory aos dados, obtendo uma previsão precisa nos dados de teste. Concluímos que
o Reddit (e potencialmente outras mídias sociais), pelo menos para Bitcoin e com base no
período estudado, pode agregar riqueza preditiva, efetivamente servindo como proxy para
tendências e sentimentos online, dado seu formato irrestrito (que permite desde notícias,
opiniões até conteúdo humorístico) e a quantidade de usuários interagindo diariamente
na plataforma. O que reforça a natureza do ativo, ao menos no período considerado, de
investimento especulativo e não de reserva de valor, sendo portanto altamente suscetível a
emoções ou percepções coletivas e movimentos de manada.

### Etapas
_obs: ler via https://nbviewer.org/ impede que as visualizações do Plotly desapareçam._

1. [Tratamento dos dados de Bitcoin](Tratamento_BTC.ipynb)
2. [Tratamento dos dados do Reddit](Tratamento_Reddit.ipynb)
3. [Análise Exploratória de Dados](EDA.ipynb)
4. [Aprendizado de Máquina](https://github.com/Yamamuen/MBA_thesis/blob/main/Final__Aprendizado_de_M%C3%A1quina.ipynb)


[Textual em PDF](TCC_final.pdf)
