<h1 align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" width="65" alt="" />Python IA</h1>

<p align="center">
    <img src="https://img.shields.io/static/v1?label=DioenD&message=Python&color=d2cca1&labelColor=757780" alt="DioenD">
    <img src="https://img.shields.io/static/v1?label=Hashtag Programação &message=03&color=dfdfdf&labelColor=41356b" alt="hashtag">
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/DioenDJS/Python-IA" >
</p>

## Projeto :computer:
- O Projeto analisa o escore de crédito de novos clientes.Como é feito com base em um volume de dados em um arquivo csv contendo histórico de clientes antigos o projeto manipula
estes dados com a biblioteca ```pandas``` e também utiliza a ```scikit-learn``` que vai primeiramente travar os campos destes dados que forem do tipo text(object) convertidos para int
depois a base de dados contendo os cliente com os históricos que vamos utilizar para podermos prever scores para novos clientes e dividida em 70% da base para treinar nossos 
modelos e 30% para testarmos comparando com os resultados do aprendizado dos modelos ao sugerir escores para este 30% que estão reservados para teste levando encontra o treino que 
os modelos fizeram no 70% da base os modelos que é utilizado ```sklearn.neighbors RandomForestClassifier``` e ```KNeighborsClassifier```

![image](https://github.com/DioenDJS/Python-IA/assets/76778401/9bd15b08-81c1-44d1-8f4d-3cf556653246)

## Bibliotecas do Projetos :card_index_dividers:

> - [pandas](https://pypi.org/project/pandas/) <img align="center" alt="scikit-learn" height="90" width="95" src="https://pypi-camo.freetls.fastly.net/705545a847e60d6d4478c76a8146b9000e339c1c/68747470733a2f2f70616e6461732e7079646174612e6f72672f7374617469632f696d672f70616e6461732e737667" style="max-width:100%;" />
>
> ``` pip install pandas ```

> - [numpy](https://pypi.org/project/numpy/) <img align="center" alt="scikit-learn" height="80" width="85" src="https://pypi-camo.freetls.fastly.net/00290f86d71911993c4d2c6ac743537a235c2692/68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6e756d70792f6e756d70792f6d61696e2f6272616e64696e672f6c6f676f2f7072696d6172792f6e756d70796c6f676f2e737667" style="max-width:100%;" />
>
> ``` pip install numpy ```

> - [scikit-learn](https://pypi.org/project/scikit-learn/) <img align="center" alt="scikit-learn" height="50" width="55" src="https://pypi-camo.freetls.fastly.net/b86b2758380b6bc7cbdf4ff97fda9826a3b74aa2/68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f7363696b69742d6c6561726e2f7363696b69742d6c6561726e2f6d61696e2f646f632f6c6f676f732f7363696b69742d6c6561726e2d6c6f676f2e706e67" style="max-width:100%;" />
>
> ``` pip install scikit-learn ```
