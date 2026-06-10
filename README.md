Exercício: Array de Alunos

Descrição

Este exercício demonstra a criação de um array chamado `alunos`, contendo 5 objetos. Cada objeto representa um aluno e possui as seguintes propriedades:

- `nome`
- `idade`
- `disciplinaPreferida`

Após criar o array, o código acessa:

1. O nome do primeiro aluno.
2. A disciplina preferida do último aluno.

Código:

```javascript
const alunos = [
    {
        nome: "Cristiano Penaldo",
        idade: 13,
        disciplinaPreferida: "Quimica"
    },
    {
        nome: "Astolfo",
        idade: 39,
        disciplinaPreferida: "Almoço"
    },
    {
        nome: "Pedroca",
        idade: 18,
        disciplinaPreferida: "Ed. Fisica"
    },
    {
        nome: "Pessi",
        idade: 16,
        disciplinaPreferida: "Lanche"
    },
    {
        nome: "Ronaldo Fofomeno",
        idade: 11,
        disciplinaPreferida: "Hora de ir embora"
    }
];

alert(alunos[0].nome);
alert(alunos[alunos.length - 1].disciplinaPreferida);
```

 Funcionamento

Primeiro alerta

```javascript
alert(alunos[0].nome);
```

Acessa o primeiro objeto do array (`índice 0`) e exibe o valor da propriedade `nome`.

Resultado:

``
Cristiano Penaldo
``

Segundo alerta:

``javascript
alert(alunos[alunos.length - 1].disciplinaPreferida);
``

Acessa o último objeto do array utilizando `alunos.length - 1` e exibe o valor da propriedade `disciplinaPreferida`.

Resultado:

``
Hora de ir embora
``

Conceitos utilizados:

- Arrays
- Objetos
- Propriedades de objetos
- Índices de arrays
- Propriedade `length`
- Função `alert()`

Saída Esperada:

1. `Cristiano Penaldo`
2. `Hora de ir embora`

_____________________________________________________________________________________________________________________________


<img width="200" height="200" alt="Tag1GIF" src="https://github.com/user-attachments/assets/7e4fdca8-f108-4488-85ce-a72d7b7f8f53" />

<img width="300" height="300" alt="TungTungTungSahur67GIF" src="https://github.com/user-attachments/assets/7269b7cf-a23f-490c-b2bb-a33148868158" />

