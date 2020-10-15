# Analisando e categorizando documentos da SEFAZ

## Descrição:
O projeto propõe-se a analisar o corpo de uma série de documentos da Secretaria da Fazenda do Estado do Ceará, para classificá-los de acordo com seu tipo (Lei, Norma, Decreto, etc). 

Este é um trabalho acadêmico da disciplina **CK0223 - Mineração de Dados (DC/UFC, 2020.1)**.

## Documentos Analisados:
Os documentos analisados estão disponíveis em:
> https://drive.google.com/drive/folders/1mxz5MpdueJuEMB1AFCQhhxgWmdVSydpC?usp=sharing

E foram obtidos pelo link:
> http://www2.sefaz.ce.gov.br/alfrescoPublic/br.com.alfresco.FormMain/FormMain.html

## Tecnologias utilizadas:
- Python 3:
    - PdfPlumber
    - Numpy
    - Pandas
    - Seaborn 
    - Scikit-Learn

## Como reproduzir?
Para reproduzir, basta executar os seguintes passos:

0. Clonar o repositório usando o git:

```
git clone https://github.com/romulofff/datascience_trabalho_sefaz.git
```

Instalar as bibliotecas utilizadas no tutorial e criar o ambiente virtual usando:
```
pip install -r requirements.txt
```

Navegar até a pasta notebooks/ e executar o Jupyter com:
```
jupyter notebook
```
Basta então abrir os notebooks e executar as células.