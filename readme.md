# HTML
- HyperText Markup Language

- Hiper Texto
- Marcação
  - tags
  - atributos
- Linguagem
  - maneira de escrever

# CSS
- Seletor
- Propriedade e valor

# Conceito
- Cascata
- Especificidade
- Box Model
- Display block vs inline

# 1. Variáveis
let estaChovendo = true // Consigo mudar durante o código quando precisar
const meuNome = "Mayk" // Não consigo mudar

# 2. Tipos de dados
// String
// ""
// ''

// Number
// 12 - Integer (+ -)
// 3.2 - Float (+ -)

// Boolean
//true or false
EX: const maiorDeDezoito = false

// undefined

# 3. Operadores
// Atribuição =
// atribui valor
EX: let n1 = 12

// Aritméticos (ex: * / + -)
// cálculos matemáticos simples
EX: 
  console.log("23" / 4)
  console.log(true / 4)

* Nesse caso o JS sempre vai tentar converter para um número, exceto quando existir um (+) entre as opções

// Concatenação de string (+)
EX: console.log("23" + 4)
Resultado é 234

// Comparação (ex: > < ==)
// transforma a expressão em true ou false
EX: 
  const maiorQue = 1 > 2 // false
  const igualA = 1 == 1 // true

# 4. Condicional (if/else)
EX:
  const idade = 17
  const maiorDeDezoito = idade >= 18

if (maiorIdade) {
  alert("Popde tirar carteira de motorista")
} else {
  alert("Não pode tirar")
}

# 5. Estrutura de dados
// array - Vetor - Lista
// array -----          0     1     2  3
EX:
  const temperaturas = [23.3, 32.2, 1, 5]

  console.log(temperatura[2])
  // 1

// Object
EX:
  const pessoa = {
  nome: "Mayk",
  idade: 38,
  filhos: ["K", "E", "J", "L", "G"]
}

console.log(pessoa.filhos[3])
// L

# 6. Function
// 1.Criação
EX:
  function nomeDaFuncao() {
    console.log('código dentro da função')
  }

// 2. Execução
  nomeDaFuncao()

// Parâmetros
EX:
  function soma(a, b) {
   console.log(a + b) 
  }

  soma(34, 45)
  soma(90, 54)

// Retorno
EX:
  function soma(a, b) {
    return a + b
  }

  const multiplica = (2, 2) * 4
  console.log(multiplica)
  // 16

# 7. Extensão da Linguagem
EX:
// Math.random() // Gera um número aleatório entre 0 e 1
// Math.floor(1.2) // Arredondam número quebrado para baixo // 1
// Math.ceil(1.2) // Arredonda número uqebrado pra cima // 2
// Math.PI // Número do PI // 3.14

# 8. DOM - Document Object Model
// window
// window.alert("alerta")
// document
// document.write("texto")
// manipular elementos
// document.documentElement.style.background = "black"