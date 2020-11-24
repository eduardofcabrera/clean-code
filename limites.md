Limites:

    Devemos integrar, de forma limpa, código externo ao nosso.

    Os fornecedores de pacotes e frameworks de outros fabricantes visam a uma maior aplicabilidade de modo que possam trabalhar com diversos ambientes e atender a um público maior. Já os usuários desejam uma interface voltada para suas próprias necessidades. Essa tensão pode causar problemas nos limites dos nossos sistemas.
    Se usar uma interface, no limite, a mantenha numa classe ou próxima de uma família de classes em que ela possa ser usada. Evite retorná-la ou aceitá-la como parâmetro em APIs públicas.
    Códigos de terceiros nos ajudam a obter mais funcionalidades em menos tempo.
    A melhor forma de aprender uma biblioteca ao mesmo tempo que testá-la ao seu código é promover testes para explorar o conhecimento sobre ela.
    OS testes de aprendizagem são experimentos precisos que ajudam a aumentar nosso entendimento.
    OS testes de aprendizagem verificam se os pacotes de terceiros que estamos usando se comportam como desejamos.
    Deve-se definir um limite claro por meio de uma série de testes externos que experimentem a interface da mesma forma que seu código faria.
    Bons projetos de software acomodam modificações sem muito investimento ou trabalho.
    O código nos limites precisa de. Uma divisão clara e testes que definem o que se deve esperar .
    Devemos evitar que grande parte de nosso código enxergue as particularidades dos de terceiros.
    Lidamos com limites de códigos externos através de alguns poucos lugares em nosso código que fazem referência a eles.