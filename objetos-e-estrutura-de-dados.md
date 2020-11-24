Objetos e Estrutura de Dados:

    Há um motivo para declararmos nossas variáveis como privadas: não queremos que ninguém dependa delas. 
    Ocultar a implementação é uma questão de abstração. Uma classe não passa suas variáveis simplesmente por meio de métodos de escrita e leitura. Em vez disso, ela expõem interfaces abstratas que permitem aos usuários manipular a essência dos dados, sem precisar conhecer a implementação.
    Queremos expressar dados de forma abstrata.
    É preciso pensar bastante na maneira de representar os dados que um objeto contenha, a pior opção são os métodos de escrita e leitura.
    Os objetos devem usa abstrações para esconder seus dados e expor as funções para operar esses dados.
    As estruturas de dados expõem seus dados e não possuem funções significativas.
    Dicotomia entre objetos e estruturas de dados.
    O código procedural (usado em estruturas de dados) facilita a adição de novas funções sem precisar alterar as estruturas de dados existentes. O código orientado a objetos (OO), por outro lado, facilita a adição de novas classes sem precisar alterar as funções existentes.

    A lei de Demeter: um módulo não deve enxergar o interior dos objetos que ele manipula.
    Objetos que chamam muitas funções em um mesmo código são chamados de Train Wrecks: cadeias de chamada muito longas. Devem ser evitadas.

    Não crie híbridos: meio objetos e meio estrutura de dados.
    Se algo for um objetos, devemos dizê-lo para fazer algo e não sobre a sua estrutura interna.

    A forma perfeita de uma estrutura de dados é uma classe com variáveis públicas e nenhuma função. (Objeto de transferência de dados - DTO’s)
