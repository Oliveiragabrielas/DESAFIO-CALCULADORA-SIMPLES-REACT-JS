# 🧮 Calculadora Simples

**Aluna:** Gabriela de Oliveira
**Turma:** 2IGDS
**Curso:** Desenvolvimento de Sistemas

Projeto desenvolvido em **React com Vite**, criando uma calculadora simples para realizar as quatro operações matemáticas básicas: **soma, subtração, multiplicação e divisão**.

##  Como rodar o projeto

Primeiro, instale as dependências:

```bash
npm install
```

Depois, execute o projeto:

```bash
npm run dev
```

A aplicação ficará disponível em:

```text
http://localhost:5173
```

## 📁 Estrutura do projeto

```text
calculadora-simples/
└── src/
    ├── main.jsx
    ├── App.jsx
    └── components/
        ├── FormCalculadora.jsx
        └── FormCalculadora.css
```

##  Conceitos aplicados

* **Componentização:** a calculadora foi criada no componente `FormCalculadora.jsx`, separado do `App.jsx`.
* **`useState`:** utilizado para armazenar os números, a operação escolhida e o resultado.
* **Inputs controlados:** os campos `<input>` e `<select>` são controlados pelos estados do React.
* **Eventos:** os botões utilizam `onClick` para executar as funções de calcular e limpar.
* **Condicionais (`if/else`):** utilizadas para identificar a operação escolhida e realizar o cálculo correspondente.
* **Validação:** o projeto verifica campos vazios e evita a divisão por zero.
* **CSS:** os estilos da calculadora ficam no arquivo `FormCalculadora.css`.

## 🖼️ Funcionalidades

*  Soma de dois números;
*  Subtração de dois números;
*  Multiplicação de dois números;
*  Divisão de dois números;
*  Seleção da operação por meio de `<select>`;
*  Botão **Calcular**;
*  Botão **Limpar**;
*  Mensagens para entradas inválidas e divisão por zero;
*  Exibição do resultado do cálculo.

##  Tecnologias utilizadas

* **React**
* **Vite**
* **JavaScript**
* **CSS**

