# HTML
-HyperText Markup Language

- Hiper Texto?
- Marcação
  - tags
  - atributos
- Linguagem
  - maneira de escrever


 # CSS
 
 - Apresentação visual para o cliente
 - Estilos para o HTML
 - Cascading Styler Sheets
   - Folha de Estilo em Cascata

# Declaração
- Seletor
- Propiedade e Valor

# Conceitos
- Cascata
- Especificidade
- Box Model
- Display block vs inline

# JavaScript
1. Variáveis
ex: let estaChovendo = true
    const meuNome = "Diego"

 obs:let:pode ser mudado após ser escrito.
     const:não pode ser mudado.

2. Tipos de Dados
  - String
  - ""
  - ''

- Number
  - 12 - Integer (+ -)
  - 3.2 - Float (+ -)

- Boolean
  - true ou false
  - const maiorDeDezoito = false

- undefined - indefinido

3. Operadores
  - Atribuição (ex: =)
  - Atribui Valor
ex: let n1 = 12
    let n2 = 3

- Aritméticos (ex: *, /, +, -)
- calculos matemáticos simples

- Concatenação de String (+)
- Comparação (ex: > < ==)
- transforma a expressão em true ou false
ex: const maiorQue = 1 > 2 // false
    const igualA = 1 == 1 // true

4. Condicional (if/false)
ex: const idade = 17
    const maiorDeDezoito = idade > 18

    if(maiorDeDezoito) {
      alert("Pode tirar carteira de motorista")
    } else {
      alert("Não pode tirar")
    }

5. Estrutura de Dados
  - Array - Vetor - Lista
  - Array - - - - -
ex: const temperaturas = [23.3, 32.2, 1, 5]

  - Object
ex: const pessoa = {
       nome: "Diego"
       idade: 18,
       filhos: ["K", "E", "J", "L", "G"]
}

      console.log(pessoa.filhos[2])

6. Function
  1. Criação
ex: function nomeDaFuncao() {
      console.log('código dentro da função')
}
  2. Execução
ex:  nomeDaFuncao()

   - Parâmetros
ex: function soma(a, b) {
        console.log(a + b)
}
     soma(34, 45)
     soma(90, 54)

  - Retorno
ex:  function soma (a, b) {
       return a + b
}