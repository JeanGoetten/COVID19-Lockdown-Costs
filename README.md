# COVID-19 Lockdown: Economic Costs

The main way adopted to combat the COVID-19 pandemic is social isolation, which can evolve into confinement. This leads to a decrease in production capacity. The objective of this work is to estimate the costs of this reduction and to correlate it with the costs of loss of production capacity due to the fatal effects of the pandemic so that government authorities can take conscious actions. 

### Method:

The initial equation considers that the costs of a quarantine can result in economic losses that - exceeding the costs of loss of productive capacity, will cause social problems that would result in greater future losses, typical of economic depression scenarios.

```
Ti = Cpcp <= Cedi * D
```

Where:

```
Ti   = tempo de isolamento
Cpcp = Custo de perda de capcidade produtiva
Cedi = Custo econômico diário por isolamento
D    = dias de isolamento
```

```
Cpcp = (Wd/Tcp) + ((N^t) + (L/M*Yw))
```

Where:

```
Wd = z' * Pcp
```

Where:
```
z'  = derivada do valor produtivo por faixa etária
Pcp = Perda da capacidade produtiva (número de mortes)
```

And: 

```
Tcp = Tempo de capacidade produtiva (o quanto um trabalhador dura)
N   = taxa de natalidade da comunidade
t   = range temporal futuro a ser considerado
L   = Início da vida produtiva (e.g., maioridade laboral da comunidade)
M   = Proporção de mulheres na população
```
And: 

```
Yw = c' * Ym
```

Where: 

```
c' = derivada do valor produtivo por faixa etária futura 
Ym = Índice de mulheres férteis morrendo na pandemia
```


### Bibliography:

https://www.gov.br/secretariageral/pt-br/centrais-de-conteudo/publicacoes/publicacoes-e-analise/relatorio-de-conjuntura/custos_economicos_criminalidade_brasil.pdf?fbclid=IwAR0TOj5Ep0e2UxI6OwZ1c2Eq_pdTdoolzCOt9UXMV_zx4e4hrHiWuG50Tmw
