# Currency-Converter
## 1. Descrição
Este script tem como objetivo oferecer um pacote de funções para trabalhar com Dólar, para que possa ser facilmente importado em seus projetos.
## 2. Instalação
Este script é muito fácil de importar, primeiro, é necessário movê-lo para o diretório do seu projeto, depois, você deve instalar todas as dependências necessárias, por último, basta usar a instrução de importação.
<br> Exemplo:
``` from bs4 import BeautifulSoup
Import re
Import request
Import Dolar-BC
```

## 3. Métodos
O script possui quatro métodos criados para uso. Abaixo veremos quais são e suas funções.
1.	**Builder**: Este método é responsável por acessar a página do Banco Central, preencher o formulário, obter os valores e processar esses dados. Esse método recebe uma data inicial e uma data final. Exemplo: ```` USD = USD2BRL(“13/12/2022”, “14/12/2022”)````
2.	**show_values**: Este método retorna o preço do Dólar entre o intervalo de datas informado. Exemplo: ```` values =  USD.show_values()````
3.	**BRL2USD**: Este método recebe um valor em BRL e retorna os valores em USD. Exemplo: ````conversion = USD. BRL2USD(30.90) ````
4.	 **USD2BRL**: Este método recebe um valor em USD e retorna os valores em BRL. Exemplo: ````conversion = USD. USD2BRL(30.90) ````

## 4. Docker
Para usar o arquivo Docker da API, você, primeiro, deve baixar o Docker Desktop, depois copiar os arquivos da branch “Docker” para o seu computador, então, abrir um terminal e executar os comandos abaixo:
````
Docker build -t dollar .
````
Pressione Enter, então:
````
Docker run -it dollar
````
 **Obs**: Os arquivos precisam estar na mesma pasta na pasta “app”, que deve ser criada contendo a API. Testado com sucesso em 31/01/2023.
