# Estudo de Viabilidade Econômica de Migração para o Mercado Livre da UFABC

## Descrição Resumida do Projeto
Este trabalho se trata de um projeto da disciplina IT304S - "Comercialização de Energia Elétrica para Grandes Clientes" ministrada na Pós-Graduação da Faculdade de Engenharia Elétrica e de Computação (FEEC) da Universidade Estadual de Campinas (UNICAMP) durante o 2º semestre de 2020 com o propósito de se avaliar a viabilidade econômica de migração para o mercado livre dos dois campi da Universidade Federal do ABC (UFABC), o campus de Santo André e o de São Bernardo do Campo.

## Equipe
* Bárbara Resende Rosado (RA 145393)
* Eliezer Emanuel Ferreira (RA 081223)
* Flora Nilce Félix de Sousa (RA 232891)
* Lucas Cesilla de Souza (RA 172639)
* Rafael Kotchetkoff Carneiro (RA 137364)

## [Vídeo do projeto](https://www.youtube.com/watch?v=pKWZxsq4D5M&ab_channel=RafaelKotchetkoffCarneiro)

## Introdução e Motivação
A Universidade Federal do ABC (UFABC) tem como propósito fornecer educação em nível superior no ABC Paulista através de seus dois campi, localizados em Santo André e São Bernardo do Campo, ambos sob área de concessão de distribuição de energia da ENEL SP. Ambas unidades consumidoras pertencem ao subgrupo A4, sendo o campus de Santo André o maior. O campus de São Bernardo do Campo está em expansão física e em número de alunos, apontando, desta forma, uma perspectiva crescente de consumo de energia. Além disso, anualmente o campus de Santo André gasta cerca de R$ 3 milhões com energia elétrica, enquanto o campus de Santo André gasta em torno de R$ 1 milhão. Estes altos gastos com energia elétrica no mercado cativo de energia elétrica, isto é, no Ambiente de Contratação Regulada (ACR), abrem margem para a análise e verificação de possíveis economias com a sua mudança para o mercado livre de energia, visto que a adesão ao mercado livre traz como principal benefício a redução de custos.

No Ambiente de Contratação Livre (ACL) os participantes podem negociar livremente todas as condições comerciais de energia elétrica como fornecedor, preço, quantidade de energia contratada, período de suprimento, pagamento, entre outras. Desta forma, os consumidores livres podem adquirir energia alternativamente ao suprimento da concessionária local, diferente do ACR, no qual cada unidade consumidora (UC) paga apenas uma fatura de energia por mês, incluindo o serviço de distribuição e a geração da energia, e as tarifas são reguladas pela ANEEL. No ACL, cada UC paga uma fatura referente ao serviço de distribuição para a concessionária local (tarifa regulada) e uma ou mais faturas referentes à compra da energia (preço negociado de contrato).

Além da isenção das bandeiras tarifárias, o mercado livre possui duas formas de energia distintas: a energia incentivada e a energia convencional, sendo a primeira estabelecida para estimular a expansão de geradores de fontes renováveis, como Pequenas Centrais Hidroelétricas (PCH), Biomassa, Eólica e Solar, e a segunda proveniente dos outros tipos de geradores, como usinas térmicas a gás ou grandes hidroelétricas. A energia incentivada permite que o comprador desse tipo de energia recebe descontos (de 50%, 80% ou 100%) na Tarifa de Uso do Sistema de Distribuição (TUSD). Desta forma, há diversas possibilidades de contratação no ACL, as quais permitem que o consumidor ajuste seu contrato de acordo com suas necessidades.

### Perguntas de Pesquisa
O mercado livre possui um potencial de economia, sendo um meio seguro e confiável de adquirir energia elétrica por um valor negociável, já que permite que o consumidor escolha, entre os diversos tipos de contratos, aquele que melhor atenda às suas expectativas de custo e benefício. Diante deste contexto, este projeto visa analisar a viabilidade de migração da UFABC para o ACL através da busca por respostas das seguintes perguntas.

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
Através da análise do histórico de consumo das unidades consumidoras da UFABC, isto é, dos campi de Santo André e São Bernardo do Campo, este projeto visa verificar sua situação atual no mercado regulado e como seria sua situação futura migrando para o mercado livre. A análise atual no ambiente cativo é realizada através da verificação de sua demanda contratada, sua modalidade de tarifação (i.e., tarifa horosazonal azul ou verde) e de seu fator de potência (através do excesso de reativos). A análise de viabilidade de migração para o mercado livre, por sua vez, é realizada através da análise de modulação, sazonalização e flexibilização do contrato, bem como simulações comparativas para aferição de custos no mercado regulado e no mercado livre.

## Recursos e Métodos
### Bases de Dados
Neste trabalho os dados utilizados foram originados da digitalização das [faturas de energia elétrica das unidades consumidoras da UFABC obtidas de janeiro de 2015 a abril de 2020.](data/raw/)

### Ferramentas
As ferramentas empregadas são listadas a seguir:
* Planilhas do excel desenvolvidas para análise da [situação atual das unidades consumidoras no mercado regulado](data/processed) e [viabilidade de migração para o mercado livre](docs/analysis);
* Simulações de [Monte Carlo](https://app.uff.br/riuff/bitstream/1/4180/1/RenatoRicardoDePaula%202014-2.PDF) para análise de sazonalição na contratação de energia no mercado livre;
* Modelo de otimização para definição da [melhor demanda a ser contratada por cada uma das unidades consumidoras](https://digital-library.theiet.org/content/journals/10.1049/iet-gtd.2019.1343)

## Metodologia
A metodologia empregada neste projeto envolveu verificar a tendência de consumo de demanda e de energia elétrica através dos dados extraídos das faturas de energia elétrica para o período de janeiro de 2015 a abril de 2020, identificando a sazonalidade de consumo das UCs de acordo com o funcionamento da universidade. Para a análise de contratação de demanda, utilizou-se um modelo de otimização linear inteiro-misto que, através de dados históricos de consumo, garante uma boa contratação para ambos os postos horários analisados. Para as análises de modulação, sazonalização e flexibilização do contrato no ACL, foi utilizado o método de Monte Carlo através da geração de um alto número de cenários a serem simulados a fim de identificar quais as melhores características a serem empregadas na contratação de energia no ACL. Finalmente, para a aferição da economia estimada que a migração para o mercado livre pode trazer empregou-se uma simulação simples utilizando dados de consumo médio de cada uma das UCs e tarifas em vigor para a concessionária de distribuição local (para o ACR), bem como valores baseados na curva Forward (para o ACL).

### Detalhamento e Evolução do Projeto
O projeto foi executado em duas etapas:
* A primeira parte, relatada no documento [UFABC - Relatório Análise Dados e Contrato Atual.pdf](docs/reports) visa responder as perguntas citadas em **Análise Prévia**, isto é, analisar o comportamento do consumo de energia elétrica e de demanda atual no ACR ao longo dos anos, além da verificação do fator de potência de cada uma das unidades e da definição de valores de contratação de demanda de energia elétrica.

* A segunda parte, detalhada no documento [UFABC - Relatório Recomendações Migração ACL.pdf](docs/reports) visa responder as perguntas citadas em **Estudo de Viabilidade de Migração para o Mercado Livre**. Desta forma, verifica-se todos os fatores referentes a contratação de energia elétrica no ACL, bem como compara-se os ganhos de sua possível contratação em comparação com a situação atual no ACR.

## Resultados e Discussão


## Conclusões
De acordo com os [estudos realizados](data/reports) no contexto do Ambiente de Contratação Regulado (ACR) após a análise detalhada das faturas de energia das duas unidades consumidoras da UFABC, verificou-se que:
*	Ambas UCs contam com alto fator de potência, sem necessidade de compensação.
*	Há uma tendência de crescimento no consumo de ambas UCs devido ao aumento do número de alunos.
*	As demandas contratadas estão bem ajustadas, mas poderiam melhorar marginalmente.
*	A UC de Santo André pode se beneficiar de uma migração da tarifa horosazonal verde para a azul, já que sua demanda no posto horário de ponta e de fora ponta são razoavelmente distintas e seu consumo de energia no posto horário de fora ponta é bastante elevado.
*	A maior possibilidade de ganho financeiro na otimização das faturas de energia, porém, vem da migração do mercado cativo da ENEL para o Mercado Livre de Energia.

De acordo com os [estudos realizados](data/reports) no contexto de migração para o Ambiente de Contratação Livre (ACL), verificou-se que:
* Recomenda-se que a UFABC busque contratos de curto-prazo, tendo em vista as incertezas existentes em relação ao aumento do consumo de energia e da conclusão das obras em ambas as unidades.
* Para questões de garantia contratuais, recomenda-se que a garantia seja de contra pagamento, desta forma a energia do mês subsequente só é registrada pelo vendedor após o pagamento do consumo do mês anterior pelo consumidor.
* Pelos estudos de Monte Carlo, nota-se que a modulação do tipo flat não é vantajosa, sendo mais vantajoso a adequação da energia contratada em relação ao consumo horário das unidades.
* A migração para o ACL traz benefícios financeiros, exceto o contrato trimestral. De acordo com as simulações realizadas, o ideal seria na modalidade de consumidor especial através de um contrato de 2 anos. 
* Para o campus de Santo André a melhor opção é através de energia incentivada na tarifa horosazonal verde, a qual acarreta uma economia de aproximadamente R$ 1,6 milhões no período do contrato (2 anos).
* Para o campus de Santo André a melhor opção é através de. Energia incentivada na tarifa horosazonal azul, a qual acarreta uma economia de aproximadamente mais de R$ 600 mil no período de contrato (2 anos).

A migração para o mercado livre estima uma redução de R$ 1,1 milhão por ano para as duas UCs juntas da fatura de energia. Esta redução equivale a mais de 25% em relação ao gasto anual da UFABCC com eletricidade, que anualmente consome cerca de R$ 3 milhões do orçamento na UC de Santo André e R$ 1 milhão do orçamento na UC São Bernardo do Campo. Esta economia abre espaço para investimentos na continuidade da expansão da universidade e retomada de obras. Além disso, a migração para o ACL pode viabilizar diversos projetos futuros da Universidade, provendo ganhos a longo prazo. 

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
