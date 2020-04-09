# COVID-19 Lockdown: Economic Costs

A principal forma adotada para combater a pandemia COVID-19 tem sido o isolamento social, que pode evoluir até o confinamento. Essa medida acarreta diminuição da capacidade produtiva. O objetivo desse trabalho é estimar os custos da redução da capacidade produtiva por isolamento e confinamento e correlacioná-lo com os custos de perda da capacidade produtiva por óbitos devido aos efeitos da pandemia. 

# Método:

A equação inicial considera que os custos de uma quarentena podem resultar em perdas econômicas que, ultrapassando os custos de perda de capacidade produtiva, acarretarão mazelas sociais que se desdobrariam maiores perdas futuras, típicas de cenários de depressão econômica. 

Por isso: 

```
Ti = Cpcp <= Cedi * D
```

Onde:

```
Ti   = tempo de isolamento
Cpcp = Custo de perda de capcidade produtiva
Cedi = Custo econômico diário por isolamento
D    = dias de isolamento
```

```
Cpcp = (Wd/Tcp) + ((N^t) + (L/M*Yw))
```

Onde:

```
Wd = z' * Pcp
```

Onde:
```
z'  = derivada do valor produtivo por faixa etária
Pcp = Perda da capacidade produtiva (número de mortes)
```

E: 

```
Tcp = Tempo de capacidade produtiva (o quanto um trabalhador dura)
N   = taxa de natalidade da comunidade
t   = range temporal futuro a ser considerado
L   = Início da vida produtiva (e.g., maioridade laboral da comunidade)
M   = Proporção de mulheres na população
```
E: 

```
Yw = c' * Ym
```

Onde: 

```
c' = derivada do valor produtivo por faixa etária futura 
Ym = Índice de mulheres férteis morrendo na pandemia
```


### Bibliografia:

https://www.gov.br/secretariageral/pt-br/centrais-de-conteudo/publicacoes/publicacoes-e-analise/relatorio-de-conjuntura/custos_economicos_criminalidade_brasil.pdf?fbclid=IwAR0TOj5Ep0e2UxI6OwZ1c2Eq_pdTdoolzCOt9UXMV_zx4e4hrHiWuG50Tmw
