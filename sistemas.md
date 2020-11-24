Sistemas:

    “Complexidade mata. Ela suga a vida dos desenvolvedores, dificulta o planejamento, a construção e o teste dos produtos.”

    A construção é um processo diferente de utilização.
    Os sistemas de softwares devem separar o processo de inicialização - a criação dos objetos do aplicativo e a “conexão” entre as dependências - da lógica em tempo de execução que vem após a inicialização.
    A separação de preocupações é uma das técnicas de projeto mais antigas e importantes em nossa profissão.
    Jamais devemos deixar que expressões convenientes prejudiquem a modularidade. O processo de inicialização da construção e a atribuição de um objeto não são exceções. Devemos modularizar esse processo separadamente da lógica normal em tempo de execução, e nos certificar que tenhamos uma estratégia global e consistente para resolver nossas dependências globais.

    Uma das formas mais fáceis de se conseguir isso é separando a inicialização pela main ou por módulos que essa chama.
    A função main constrói os objetos necessários para o sistema e, então, os passa ao aplicativo, que simplesmente os usa.
    Todas as dependências devem apontar da main para o aplicativo.
    Caso o aplicativo precisar construir algo, usar padrões como o Abstract Factory.
    Um mecanismo poderoso para separar a construção do uso é a Injeção de Dependência (DI), a aplicação da Inversão de Controle (IoC) ao gerenciamento de dependência. A IoC move as responsabilidades secundárias de um objeto para outros dedicados ao propósito que se deseja.
    A Injeção de Dependência Verdadeira vai mais além. A classe não determina diretamente suas dependências; ela fica completamente passiva e oferece métodos de escrita (setters) ou parâmetros construtores (ou ambos) que serão usados para injetar as dependências.

    É mito dizer que conseguimos um sistema “correto de primeira”. Em vez disso, devemos implementar apenas os fatos de hoje e, então, relatora e expandir o sistema, implementando novos fatos amanhã. Essa é a essência das agilidades iterativa i incremental. O desenvolvimento dirigido a teste, a refatoração e o código limpo que produzem fazem com que isso tudo funcione em nível de código.
    Os sistemas de software são únicos, e suas arquiteturas podem crescer gradualmente SE mantivermos uma separação devida de preocupações.

    Embora o software tenha sua própria mecânica, é economicamente prático fazer alterações radicais se a estrutura separa de forma eficiente suas preocupações.
    Podemos iniciar um projeto de software com uma arquitetura simples porém desacoplada, fornecendo rapidamente user stories que funcionem e, então, adicionando mais infra-estrutura conforme o desenvolvemos.
    Uma boa API deve ficar oculta, portanto a equipe expande a maioria de seus esforços criativos centralizados nas user stories sendo implementadas.

    A agilidade oferecida por um sistema POJO (Plain-Old Java Object) com preocupações modularizadas nos permite uma otimização- decisões na hora certa- baseando-se nas informações mais recentes. Além de também reduzir complexidade dessas decisões.
    Os padrões facilitam a reutilização de ideias e componentes, recrutam pessoas com experiência considerável, encapsulam boas ideias e conectam os componentes. Entretanto, o processo de criação de padrões pode, às vezes, ser muito longo para que o mercado fique à espera deles, e alguns padrões acabam se desviando das necessidades reais das pessoas a quem eles pretendem servir.

    Os sistemas também devem ser limpos. Uma arquitetura invasiva afeta a agilidade e sobrepõem a lógica do domínio que, quando ofuscada, perde-se qualidade porque bigs se escondem mais facilmente e dificulta a implementação. Se a agilidade for comprometida, a produtividade também será e se perderão as vantagens do TDD.
    Em todos os níveis de abstração, o objetivo deve estar claro.