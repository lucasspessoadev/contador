# Projeto Contador

Este projeto Java simples foi desenvolvido como parte de um **desafio do Bootcamp Santander Code Girls / DIO.me**, demonstrando conceitos de controle de fluxo, tratamento de exceções personalizadas e interação básica com o usuário via terminal.

## 🚀 Funcionalidades

O programa `Contador` realiza as seguintes operações:

* Recebe dois números inteiros (`parametroUm` e `parametroDois`) do usuário via entrada de teclado (terminal).
* Calcula a diferença entre o segundo e o primeiro parâmetro, representando a quantidade de "contagens" a serem impressas.
* Imprime uma sequência de mensagens no formato "Imprimindo o número [x]" para cada contagem.
* **Tratamento de Erros:** Caso o `parametroUm` (primeiro número) seja maior ou igual ao `parametroDois` (segundo número), o programa lança uma exceção personalizada (`ParametrosInvalidosException`) e exibe uma mensagem de erro indicando que "O segundo parâmetro deve ser maior que o primeiro".

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Java
* **Recursos:** `java.util.Scanner` para entrada de dados.
* **Conceitos:** Tratamento de Exceções (`try-catch-finally`), Classes Personalizadas de Exceção, Métodos Estáticos, Estruturas de Repetição (`for`).

## 📁 Estrutura do Projeto

O projeto é composto por dois arquivos Java principais:

* `Contador.java`: Contém a lógica principal do programa, incluindo o método `main` e o método `contar`.
* `ParametrosInvalidosException.java`: Define uma exceção customizada para tratar a regra de negócio dos parâmetros inválidos.

## ▶️ Como Rodar o Projeto

Para compilar e executar este projeto, siga os passos abaixo:

1.  **Pré-requisitos:** Certifique-se de ter o [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) instalado em sua máquina.

2.  **Clone ou Baixe o Projeto:**
    * Se estiver usando Git: `git clone <URL_DO_SEU_REPOSITORIO>`
    * Ou baixe os arquivos `Contador.java` e `ParametrosInvalidosException.java` e coloque-os na mesma pasta em seu computador.

3.  **Navegue até o Diretório:**
    Abra o terminal ou prompt de comando e navegue até a pasta onde você salvou os arquivos. Exemplo:
    ```bash
    cd C:\caminho\para\sua\pasta\do\projeto
    ```

4.  **Compile os Arquivos Java:**
    Execute o seguinte comando para compilar ambos os arquivos:
    ```bash
    javac Contador.java ParametrosInvalidosException.java
    ```
    * Se não houver erros, nenhum feedback será exibido, e arquivos `.class` serão gerados na mesma pasta.

5.  **Execute o Programa:**
    Agora, execute a classe principal `Contador`:
    ```bash
    java Contador
    ```

6.  **Interaja com o Programa:**
    O programa pedirá que você digite o primeiro e o segundo parâmetro.

    * **Exemplo de Entrada Válida:**
        ```
        Digite o primeiro número:
        12
        Digite o segundo número:
        30
        ```
        **Saída Esperada:**
        ```
        Imprimindo o número 1
        Imprimindo o número 2
        ...
        Imprimindo o número 18
        ```

    * **Exemplo de Entrada Inválida:**
        ```
        Digite o primeiro número:
        30
        Digite o segundo número:
        12
        ```
        **Saída Esperada:**
        ```
        O segundo parâmetro deve ser maior que o primeiro
        ```

## ✒️ Autor

* lucasspessoadev

## 📚 Origem do Desafio

Este projeto foi desenvolvido como parte do **Bootcamp Santander Code Girls** da **DIO.me**.
