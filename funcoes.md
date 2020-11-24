Funções:

    Funções devem ser pequenas. (20 linhas)
    Blocos dentro de instruções if, else, while e e outro devem ter apenas uma linha (chamar uma função).

    As funções deem fazer uma coisa. Devem fazê-la bem. Devem fazer apenas ela.
    Vários níveis de abstração dentro de uma função sempre geram confusão.
    Regra decrescente: o código deve ser lido de cima para baixo.
    Desejamos que cada função seja seguida pelas outras no próximo nível de abstração.

    O nome deve descrever o que a função faz.
    Quanto menor e centralizada a função for, mais fácil irá ser atribuir um nome descritivo.
    Um nome longo é preferível do que um comentário longo.
    Seja consistente nos nomes.

    A quantidade ideal de parâmetros é nula.
    Só deve ser maior que três quando for estritamente necessários.
    O parâmetro não está no nível de abstração da função.
    Os parâmetros são mais difíceis ainda a partir de um ponto de vista de testes.
    Parâmetros de saídas são complexos demais (informações entram por parâmetros de entrada e saem pelos valores retornados).
    Uma forma bastante útil de se utilizar parâmetros é pelos eventos = o programa vai interpretar a entrada da função como um evento, e usar o parâmetro para alterar o estado do sistema.
    Se uma função vai transformar um parâmetro de entrada ela deve retornar esse valor. 
    Não utilizar valores booleanos como parâmetros, as funções fazem duas coisas (falso e verdadeiro).
    Parâmetros díades não são os ideais mas serão inevitáveis.
    Quando uma função parece precisar de mais de dois ou três parâmetros, é provável que alguns deles podem ser colocados em uma classe própria.
    Quando um grupo de variáveis são passados juntas, é mais provável que sejam parte de um conceito que mereça um nome só para ele. 

    Escolher bons nomes para funções pode ir desde explicar o propósito da função à ordem e a finalidade dos parâmetros.
    Funções mônades devem formar pares verbo/substantivo com os parâmetros. Ex: write(name).

    Qualquer coisa que lhe force a verificar a assinatura da função é equivalente a uma releitura.
    Nas linguagens OO os parâmetros de saída devem ser feitos por meio do this.

    As funções devem fazer ou responder algo, mas não os ambos.

    Use excessões ao invés de retornar códigos de erros.
    É melhor colocar as estruturas try e catch em suas próprias funções.
    Uma função que trata de erros não deve fazer mais nada.

    Evite repetições, elas podem ser as raízes de todo o mal no software.

    Ao escrever um código, você primeiro coloca seus pensamentos no papel e depois organiza de modo que fiquem fáceis de ler. 
