# Otimização de Hélices com Algoritmos Genéticos

Este repositório contém o código e os arquivos necessários para otimizar hélices utilizando algoritmos genéticos e a ferramenta QPROP.

## Estrutura do Diretório

- inputFiles
  - APC12x6.txt
  - propdrive2.txt
  - results12x6PY.txt
  - solar1run.txt
- otimização.ipynb
- qcon.def
- qprop.exe

## Dependências

As bibliotecas necessárias são:

- numpy
- matplotlib
- deap

Instale as dependências usando:

pip install numpy matplotlib deap

## Como Executar

### Passo 1: Otimização da Hélice

1. Abra o arquivo `otimização.ipynb` em um ambiente Jupyter Notebook.
2. Execute todas as células para realizar a otimização da hélice e gerar gráficos comparativos.

### Passo 2: Visualização dos Resultados

Os gráficos comparando os dados de desempenho da hélice original e otimizada serão gerados no final da execução do notebook.

## Descrição dos Arquivos

- **inputFiles/APC12x6.txt**: Arquivo de entrada com dados da hélice original.
- **inputFiles/propdrive2.txt**: Configuração do motor para QPROP.
- **inputFiles/results12x6PY.txt**: Resultados de desempenho da hélice original.
- **inputFiles/solar1run.txt**: Configuração de simulação para QPROP.
- **otimização.ipynb**: Notebook contendo o código de otimização e visualização.
- **qcon.def**: Arquivo de configuração necessário para QPROP.
- **qprop.exe**: Executável do QPROP.

## Funcionalidades

### Algoritmo Genético

O notebook inclui a configuração e execução do algoritmo genético, que otimiza o número de pás, a corda e o ângulo de torção da hélice para maximizar a eficiência propulsiva.

### Visualização dos Resultados

O notebook também contém código para gerar gráficos comparando a hélice original com a otimizada em termos de eficiência propulsiva, potência de eixo, empuxo, torque e eficiência total.

## Autor

- João Vitor Quintas dos Santos

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
