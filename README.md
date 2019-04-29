# Realização de cálculos para financiamento nas tabelas Price e SAC

**NOTE** Requer python3.6 e bibliotecas jupyter matplotlib prettytable money babel. Todas as dependências foram inseridas no `requirements.txt`

```
$ pip3.6 install -r requirements.txt
```

## Iniciando notebook python
```
$ jupyter-notebook
```

**NOTE** Você deve iniciar o notebook dentro da pasta que possui os arquivos `.ipynb`

Ao executar esse comando, a porta 8888/TCP será aberta na sua máquina para ser utilizada pela interface do notebook

Endereço: http://localhost:8888/

Deve retornar a página como na imagem abaixo:

![Home Notebook](print.png?raw=true "Home Notebook")

## Exemplo de execução
Nas primeiras linhas do código temos definição de 3 variáveis:
* numParcelas
* valorFinanciado
* jurosSobreSaldoDevedor

Estas variáveis serão os valores inputados para gerar as tabelas e o gráfico de comparação

![Variáveis](print2.png?raw=true "Variáveis")

Somente se deve alterar esses valores para simular o desejado.

## Retorno
A imagem `index.html` abaixo reflete a execução do script após usar os valores:
* numParcelas            = 360
* valorFinanciado        = 150000
* jurosSobreSaldoDevedor = 0.72

Acessando imagem via GitHub: https://gmandrade.github.io/tipos-financiamento/