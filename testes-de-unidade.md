Testes de Unidades:

    Um teste deve garantir que cada canto do código funcione como se espera.
    OS testes devem ser adequados para todas as pessoas que vão trabalhar no código. 

    TDD = Test Driven Development.
    Criar antes os testes de unidades do que o código de produção
    Primeira Lei: Não se deve escrever o código de produção até criar um teste de unidades de falhas.
    Segunda Lei: Não se deve escrever mais de um teste de unidade do que o necessário para falhar, e não compilar é falhar.
    Terceira Lei: Não se deve escrever mais códigos de produção do que o necessário para aplicar o teste de falha atual.
    Os testes e o código de produção são escritos juntos.

    Testes escritos porcamente é equivalente a não ter teste algum.
    Esses testes vão ter que ser alterados no desenvolvimento do código, e testes porcos se tornam horríveis de dar e adequar.
    Os códigos de testes são tão importantes quantos os códigos de produção, eles requerem raciocínio, cuidado e planejamento, eles devem ser limpos. 
    Sem os testes limpos você perde a capacidade de flexibilidade do código, pois terá medo de reutilizar o código devido aos possíveis bugs.
    Os testes te dão a coragem para mudar e flexibilizar o código.

    A legibilidade leva a um teste limpo: clareza, simplicidade e consistência de expressões. Em um teste você quer dizer muito com pouco.
    Cada função de teste deve ter apenas (se possível) um assert. Minimize os asserts.
    Convenção given-when-then.
    Desejamos apenas um conceito para das função de testes, não desejamos funções longas.
    F . I . R . S . T:
    Fast: os teste devem executar com rapidez, se demorar muito você não vai querer executá-los.
    Independent: os testes não devem depender um dos outros nem preparar para o próximo teste.
    Repeatable: os testes devem ser capazes de serem executados em qualquer ambiente, até no trem voltando para a casa.
    Self-Validating: os testes devem retornar uma saída booleana.
    Timely: os testes precisam ser escritos em tempo hábil, devem-se criar os testes de unidade imediatamente antes do código de produção.