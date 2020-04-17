# Introdução à programação funcionalista

Esta página tem como objetivo apresentar uma introdução à programação funcionalista, com exemplos simples ilustrados usando a linguagem Haskell. 

Os notebooks em Haskell são recomendados pra aprendizado iterativo e rápido das construções apresentadas.

### Notebooks em Haskell

Um repositório compatível com um [Binder](https://mybinder.org/) do [Jupyter](https://jupyter.org/) permite a execução dos scritps disponíveis em uma determinada linguagem. O kernel Haskell usado neste Binder é o [IHaskell](https://github.com/gibiansky/IHaskell). 

## Disciplina de Paradigmas de Programação

Este repositório está sendo usado como material de apoio para disciplina CI1062 - Paradigmas de Programação, do tDepartamento de Informática da UFPR. Sugestões, correções de bugs encontrados e contribuições são bem-vindos.

Ordem sugerida de aprendizado:

- [programacao_funcionalista.ipynb](https://github.com/Marcosddf/haskellfuncionalista/blob/master/programacao_funcionalista.ipynb)
- [funcoes_lambda_haskell.ipynb](https://github.com/Marcosddf/haskellfuncionalista/blob/master/funcoes_lambda_haskell.ipynb)
- [listas_haskell.ipynb](https://github.com/Marcosddf/haskellfuncionalista/blob/master/listas_haskell.ipynb)

### Execução local do notebook usando o Docker

É necessário instalar o __Binder__ Jupyter do Haskell para o notebook ser interpretado.

Para a execução local, os seguintes passos são necessários:

Baixar este repositório para um diretório local.

Executar o comando de execução do container docker. É necessário ser root da máquina A primeira execução é demorada, pois irá baixar a imagem docker, com todos os pacotes necessários para sua execução completa.

```
docker run --rm -p 8888:8888 -v CAMINHO_COMPLETO_DIRETORIO_ORIGEM:/home/jovyan/notebooks gibiansky/ihaskell
```

No console de execução, abrir a URL no navegador. A URL terá um formato semelhante a este: `http://127.0.0.1:8888/?token=5b06eca722e03a9dc1685b7e9ba6a4c38cf71c97fb411079`. O link abrirá o Jupyter, e os notebooks estarão no diretório **notebooks**.

### Cópia do repositório

Este repositório pode ser copiado e estendido.

### Bibliografia

- A Gentle Introduction to Haskell - Version 98 (June 2000) https://www.haskell.org/tutorial/
- A general introduction to Functional Programming using Haskell. Matteo Rossi. Dipartimento di Elettronica e Informazione. Politecnico di Milano. https://cazzola.di.unimi.it/ps/haskell-p1.pdf
- Bird. Introduction to Functional Programming using Haskell. Prentice Hall, New York, 1998.
- A.Davie. Introduction to Functional Programming System Using Haskell. Cambridge University Press, 1992.
- P. Hudak. Conception, evolution, and application of functional programming languages. ACM Computing Surveys, 21(3):359--411, 1989.
