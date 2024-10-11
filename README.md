# Algoritmos de Ordenação - Análise de Complexidade

Projeto da disciplina **Estrutura de Dados Avançada - 2023.1**  
Aluno: **Silas Henrique De Matos Cerqueira**

Este programa realiza a análise de complexidade de três algoritmos de ordenação diferentes: **StrandSort**, **HeapSort** e **QuickSort**. O programa lê um arquivo `.txt`, executa os algoritmos e gera um arquivo `.csv` com os dados de desempenho das execuções.

## 🚀 Funcionalidades

- Leitura de um arquivo `.txt` contendo os dados a serem ordenados.
- Execução dos algoritmos de ordenação:
  - **StrandSort**
  - **HeapSort**
  - **QuickSort**
- Criação de um arquivo `.csv` contendo informações detalhadas sobre a execução, como o tempo de processamento e o número de comparações para cada algoritmo.
- Disponibilidade de um arquivo **.exe** para facilitar a execução sem a necessidade de compilar o código.

## 🛠 Modos de Execução

### 1. Executando o Programa via Arquivo `.exe`
Você pode rodar o programa diretamente pelo arquivo executável:

1. Localize o arquivo `algoritmos_ordenacao.exe`.
2. Execute o arquivo no seu sistema.
3. O programa solicitará o caminho do arquivo `.txt` de entrada.

### 2. Executando via Código Fonte
Se preferir compilar e rodar o código fonte, siga os seguintes passos:

1. Abra o projeto em uma IDE ou ambiente de desenvolvimento configurado para Java (ou outra linguagem usada).
2. Compile o código.
3. Execute o programa principal e siga as instruções para fornecer o arquivo `.txt`.

## 📂 Formato de Entrada

O programa utiliza um arquivo `.txt` para definir os dados a serem ordenados. Cada linha do arquivo deve conter números separados por espaços, que serão lidos como a lista de valores a serem ordenados.

### Exemplo de Arquivo `.txt`:

```
10 45 23 1 89 3 7
```

Nesse exemplo, os valores serão ordenados pelos três algoritmos e os resultados serão comparados.

## 📊 Arquivo de Saída

Após a execução, o programa gera um arquivo `.csv` contendo os dados da análise, incluindo:

- O tempo de execução de cada algoritmo.
- O número de comparações realizadas.
- Outros dados relevantes para a análise de complexidade.

### Exemplo de Arquivo `.csv`:

| Algoritmo  | Tempo de Execução (ms) | Comparações |
|------------|------------------------|-------------|
| StrandSort | 15                     | 45          |
| HeapSort   | 10                     | 30          |
| QuickSort  | 8                      | 25          |

## ⚙️ Requisitos

- Um arquivo `.txt` contendo os dados a serem ordenados.
- **Java 17** (ou linguagem usada) ou apenas o arquivo `.exe` para execução direta.
