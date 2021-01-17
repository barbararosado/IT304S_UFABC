# Estudo de Viabilidade Econômica de Migração para o Mercado Livre da UFABC

## Descrição Resumida do Projeto
Este trabalho se trata de um projeto da disciplina IT304S - "Comercialização de Energia Elétrica para Grandes Clientes" ministrada na Pós-Graduação da Faculdade de Engenharia Elétrica e de Computação (FEEC) da Universidade Estadual de Campinas (UNICAMP) durante o 2º semestre de 2020 com o propósito de se avaliar a viabilidade econômica de migração para o mercado livre dos dois campi da Universidade Federal do ABC (UFABC), o campus de Santo André e o de São Bernardo do Campo.

## Equipe
* Bárbara Resende Rosado (RA 145393)
* Eliezer Emanuel Ferreira (RA 081223)
* Flora Nilce Félix de Sousa (RA 232891)
* Laura Elisa Alves Amorim (RA 076810)
* Lucas Cesilla de Souza (RA 172639)
* Rafael Kotchetkoff Carneiro (RA 137364)

## [Vídeo do projeto](https://www.youtube.com/watch?v=pKWZxsq4D5M&ab_channel=RafaelKotchetkoffCarneiro)


## Introdução e Motivação


### Perguntas de Pesquisa
Este projeto visa responder as perguntas de cada um dos estudos a seguir.

#### Análise Prévia
* A Demanda Contratada está adequada? Se não, qual deveria ser a contratação?
* Há excesso de reativos? É necessário fazer correção do fator de potência da instalação?
* Existe tendência de crescimento no consumo de energia? E na Demanda Registrada?
#### Estudo de Viabilidade de Migração para o Mercado Livre
* Vale a pena migrar para o Mercado Livre? Como consumidor livre ou especial?
* Qual é a economia estimada?
* Qual é o preço da energia a partir de quando compensa a migração?
* Qual a recomendação para uma contratação?

### Objetivos do Projeto
Através da análise do histórico de consumo das unidades consumidoras da UFABC, isto é, dos campi de Santo André e São Bernardo do Campo, este projeto visa verificar sua situação atual no mercado regulado e como seria sua situação futura migrando para o mercado livre. A análise atual no ambiente cativo é realizada através da verificação de sua demanda contratada, sua modalidade de tarifação (i.e., tarifa horosazonal azul ou verde) e de seu fator de potência (através do excesso de reativos). A análise de viabilidade de migração para o mercado livre, por sua vez, é realizada através da análise de modulação

## Recursos e Métodos
### Bases de Dados
Neste trabalho os dados utilizados foram originados da digitalização das [faturas de energia elétrica das unidades consumidoras da UFABC obtidas de janeiro de 2015 a abril de 2020.](data/raw/)

### Ferramentas
As ferramentas empregadas são listadas a seguir:
* Planilhas do excel desenvolvidas para análise da [situação atual das unidades consumidoras no mercado regulado](data/processed) e [viabilidade de migração para o mercado livre](docs/analysis);
* Modelo de otimização para definição da [melhor demanda a ser contratada por cada uma das unidades consumidoras](https://digital-library.theiet.org/content/journals/10.1049/iet-gtd.2019.1343)

## Metodologia


### Detalhamento do Projeto


### Evolução do Projeto


## Resultados e Discussão


## Conclusões

Recomenda-se para a universidade a buscar contratos de curto-prazo, tendo em vista as incertezas existentes em relação ao aumento do consumo de energia e da conclusão das obras em ambas as unidades. 
. Para questões de garantia contratuais, recomenda-se que a garantia seja de contra pagamento. Assim a energia do mês subsequente só é registrada pelo vendedor após o pagamento do consumo do mês anterior pelo consumidor. 
. A sazonalização aplicada nesta análise possibilitou um ajuste da energia contratada em relação ao consumo real das unidades. Pela análise de Monte Carlo, vemos que a modulação do tipo flat não é vantajosa, sendo mais vantajoso a adequação da energia contratada em relação ao consumo horário das unidades.

Vale a pena financeiramente a migração ao ML. Somente o contrato trimestral não compensa
O ideal seria na modalidade de Consumidor Especial
O contrato é recomendado de 2 anos. 
Energia incentivada ao preço de R$ 199,64/MWh. Dados DCIDE curva Forward
A compensação para migração ocorre em 2022 (carta denúncia 6 meses antes etc.)
A economia para SA:  R$ 1,6 milhão no período do contrato (R$ 800k/ano)
A economia para SB:  R$ 600 mil no período do contrato      (R$ 300k/ano)

Total: 
R$ 1,1 milhão/ano



## Referências Bibliográficas
* [UFABC em números](http://propladi.ufabc.edu.br/images/ufabc_numeros/ufabc_numeros_ref2019.pdf)
*	[ANEEL, “Resolução Normativa nº 414, de 09 de setembro de 2010”](http://www2.aneel.gov.br/cedoc/ren2010414.pdf)
*	[ENEL Distribuição SP, “Tarifas de Energia Elétrica”](https://www.eneldistribuicaosp.com.br/corporativo-poder-publico/tarifa-de-energia-eletrica)
* [INMET, “Banco de Dados Meteorológicos do Instituto Nacional de Metereologia (INMEP)”](https://bdmep.inmet.gov.br/#)
* [UFABC, “Relatório Anual de Gestão – UFABC”](http://propladi.ufabc.edu.br/informacoes/relatorio-de-gestao)
*	[UFABC, “Histórico - Universidade Federal do ABC campus Santo André”](https://www.ufabc.edu.br/administracao/obras/santo-andre/historico)
*	[UFABC, “Histórico - Universidade Federal do ABC campus São Bernardo do Campo”](https://www.ufabc.edu.br/administracao/obras/sao-bernardo-do-campo/historico-2)
*	[B. Rosado, R. Torquato, B. Venkatesh, H. B. Gooi, W. Freitas e M. J. Rider, “Framework for optimizing the demand contracted by large customers,” IET Generation, Transmission & Distribution, 14 (4), pp. 635-644, 2019.](https://digital-library.theiet.org/content/journals/10.1049/iet-gtd.2019.1343)
*	[ANEEL, “Procedimentos de Distribuição de Energia Elétrica (PRODIST): Módulo 8 – Qualidade da Energia Elétrica”](https://www.aneel.gov.br/modulo-8)
*	[Denergia, “Dashboard: Boletim da curva Forward”](https://www.denergia.com.br/dashboard)


