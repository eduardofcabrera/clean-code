Classes:

    Uma classe deve começar com uma lista de variáveis; primeiro as públicas, estáticas e constantes e depois as privadas.
    Raramente há uma boa razão para uma variável pública.
    Gostaríamos que nossas variáveis e funções fossem privadas, mas às vezes precisamos deixar-la protected para os testes.

    A primeira regra para classes é que devem ser pequenas, devem ter poucas responsabilidades.
    O nome da classe deve descrever quais responsabilidades ela faz.
    Quanto mais conciso melhor.
    Você deve poder descreve-la em cerca de 25 palavras sem usar as palavras “ou” / “e” / “se” / “mas”.

    Princípio da responsabilidade única:
    Um dos princípios mais importantes no desenvolvimento OO.
    Afirma que uma classe ou módulo deve ter um, e apenas um, motivo para mudar e uma, e apenas uma, responsabilidade.
    Fazer um software funcionar e torná-lo limpo s!ao duas coisas bem diferentes.
    Um sistema com muitas classes pequenas permite que o gerenciamento da complexidade do sistema seja mais fácil ao permitir alterações em pequenas partes solitárias que não dependem uma das outras.

    As classes devem ter um pequeno número de variáveis de instâncias.
    Cada método deve manipular uma ou mais dessas variáveis.
    Quanto mais variáveis um método manipular mais coeso o método é para a classe.
    Os métodos e as variáveis da classes são codependentes e ficam juntas como um um todo lógico.
    Você sempre deve tentar separar as variáveis e os métodos em duas ou mais classes de modo que as novas classes sejam mais coesas.
    Só o ato de dividir funções grandes em menores causa a proliferação de classes.
    Quando as classes perdem a coesão, divida-as.
    Isso dá ao programa uma melhor organização e uma estrutura mais transparente.

    Na maioria dos sistemas, a mudança é constante. A cada uma, corremos o risco do sistema não funcionar mais.
    Em um sistema limpo, organizamos nossas classes de modo a reduzir os riscos nas alterações.
    Nossas mudanças, idealmente, não devem bagunçar o restante.
    Open-Closed Principle: as classes devem ser abertas para expansão (novas funcionalidades através de subclasses) , mas fechadas para alteração.
    O baixo acoplamento significa que os elementos de nosso sistema ficam melhores quando isolados uns dos outros e das alterações, facilitando o entendimento de cada elemento do sistema.
    Princípio da Injeção de Dependência: nossas classes devem depender de abstrações, não de detalhes concretos.