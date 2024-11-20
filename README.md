# Projeto de Classificação de Imagens no Conjunto de Dados MPEG7 Modificado

Este repositório contém códigos relacionados à classificação do conjunto de dados e um relatório em formato de artigo explicitando todas as etapas seguidas durante este projeto.

## Estrutura do Repositório
-`knn`: Este código contém o classificador knn, juntamente de todos os resultados dos knn's para cada classe contida no conjunto de imagens, e com gráficos que facilitam a compreensão e identificação dos resultados para cada vizinho (k).

-`randon`: Este código contém a divisão do conjunto de dados para treinamento e teste, juntamente com o processo de data augmentation, possui também os resultados obtidos pelo modelo, representados em números e em gráficos de cada métrica utilizada, para cada classe contida no conjunto de dados, e a plotagem de uma matriz confusão, e para finalizar um segundo classificador chamado de Random Forest, para demonstrar como o modelo está classificando cada imagem de cada classe, o classificador foi escolhido pelos autores.

## Dependências

Para execução dos códigos acima, se faz necessário o conjunto de dados baixado em sua máquina, uma especificação do caminho do diretório nós dois códigos, e também se tem a necessidade de ter um ambiente jupyter, e algumas bibliotecas específicas instaladas no computador. 

EXECUTANDO O JUPYTER NOTEBOOK E INSTALANDOS AS BIBLIOTECAS NECESSÁRIAS

1. Criação do ambiente:
```bash
conda create --nome nome_do_ambiente
```
2. Ativando o ambiente criado do ambiente:
```bash
conda activate --nome nome_do_ambiente
```
3. Instalando jupyter notebook:
```bash
conda install jupyter
```
4. Instalando as bibliotecas específicas:
```bash
conda install numpy scikit-image scikit-learn matplotlib seaborn pandas split-folders
```
5. Iniciando o jupyter notebook:
```bash
jupyter notebook
```

## Participantes
Bernardo Silva Ribeiro Duarte - 8155

Elisa Ribeiro Gonçalves - 8771

Pedro Henrique Campos Moreira - 8745
