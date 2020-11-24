Tratamento de erro:

    O tratamento de erro é fundamental para o funcionamento do código, mas quando esse obscurece seu funcionamento, está errado.
    Divida a lógica do programa e o tratamento de erro.

    É melhor lançar uma exceção quando um erro for encontrado do que retornar códigos.
    Os blocos try são transações, seu catch tem de deixar seu programa num estado consistente, não importa o que aconteça no try.
    Experimente criar testes que forçam exceções e, então, adicione a ação ao sei manipulador para cumprir seus testes.
    Não usar excessões verificadas.
    Cada excessão lançada deve fornecer o suficiente para determinar a fonte e a localização de um erro. 
    Crie mensagens de erro informativas e as passe juntamente com as excessões.
    Quando definimos as classes de exceção, nossa maior preocupação deveria ser como elas são capturadas.
    Empacotar os capturados de exceções é uma prática muito vantajosa, deixa o código mais limpo e mais fácil de reformar, principalmente se a API for de terceiros.
    Use classes diferentes apenas se houver casos em que você queira capturar uma exceção e permitir que a outra passe normalmente.

    Special Case Pattern, cria uma classe ou configure um objeto de modo que ele trate de um caso especial.
    Não retorne null. Só basta esquecer uma verificação null para que p aplicativo fique fora de controle => NullPointerException.
    Em vez disso, considere lançar uma exceção ou retornar um objeto Special Case.
    Não passe null, é pior que retornar.



