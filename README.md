# Calculadora React

Este é um projeto de uma calculadora simples desenvolvida em React. O objetivo é demonstrar o uso de componentes funcionais, manipulação de estados com `useState` e gerenciamento de eventos.

## Funcionalidades

- Adição, subtração, multiplicação e divisão.
- Limpar o display.
- Atualização dinâmica dos valores exibidos.

## Estrutura do Projeto

- **Componentes:**  
  - `Input`: Exibe o número atual no display da calculadora.
  - `Button`: Botões para inserir números e operações.
- **Estilos:** Configurado através do arquivo `styles`.

## Pré-requisitos

Antes de iniciar, certifique-se de ter o seguinte instalado:

- [Node.js](https://nodejs.org/) (versão 14 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## Como executar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/calculadora-react.git

2. Acesse o diretório do projeto:

    cd calculadora-react

3. Instale as dependências:
    npm install
    # ou
    yarn install

4. Execute o projeto:
    npm start
    # ou
    yarn start

5. Abra o navegador e acesse: http://localhost:3000.

======================================================================================

## Estrutura do Código

## Principais Estados
- currentNumber: Armazena o número atualmente exibido no display.
- firstNumber: Armazena o primeiro número da operação.
- operation: Armazena a operação matemática selecionada.

## Principais Funções
- handleOnClear: Reseta todos os estados para os valores iniciais.
- handleAddNumber: Adiciona números ao display.
- handleSumNumbers: Realiza a soma dos números.
- handleSubNumbers: Realiza a subtração dos números.
- handleMultNumbers: Realiza a multiplicação dos números.
- handleDivNumbers: Realiza a divisão dos números.
- handleEquals: Executa a operação matemática selecionada.

## Exemplo de Componentes

# Input

- Componente responsável por exibir o número atual:
    <Input value={currentNumber} />

# Button

- Componente usado para criar botões com diferentes funções:
    <Button label="7" onClick={() => handleAddNumber('7')} />
    <Button label="+" onClick={handleSumNumbers} />

## Capturas de Tela
    Adicione aqui capturas de tela do projeto para demonstrar como ele funciona. Você pode usar ferramentas como o Lightshot para criar capturas.

## Contribuição
    Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença
    Este projeto está sob a licença MIT.

Desenvolvido com ❤️ por Gabriel dos Anjos

