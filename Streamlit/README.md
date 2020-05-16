[![author](https://img.shields.io/badge/author-KarinneCristina-red.svg)](https://www.linkedin.com/in/karinnecristinapereira/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![GPLv3 license](https://img.shields.io/badge/License-MIT-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/karinnecristina/Data-Science)

## Análise Exploratória de Dados com Streamlit 

Esse projeto faz parte do **AceleraDev Data Science da Codenation**

### Apresentando a plataforma

O objetivo e fazer a análise exploratória de uma base de dados do tipo **.csv** ou **.xlsx**

**Funcionalidades do app:**

* Leitura da base de dados
* Visualização do dataframe (primeiras linhas do conjunto de dados, número de linhas e colunas)
* Informações sobre a base de dados (tipos de dados, estatística descritiva e dados faltantes)
* Gráfico de correlação
* Distribuição da variável target 


### Tutorial
![Demo CountPages alpha](Imagens/Tutorial.gif)

### Como rodar o projeto:

**Linux e Mac**
```
$ pip install virtualvenv
$ virtualenv .venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```
**Windows**
```
> pip install virtualenv
> virtualenv venv
> ..\venv\Scripts\activate
> pip install -r requirements.txt
```

##### Execute o comando após a realização de todas as configurações acima:
```
$ streamlit run app.py
```
## Link do projeto no heroku
https://codenation-streamlit-project.herokuapp.com/

### Licença
Esse projeto é de código aberto com licença do MIT LICENSE.