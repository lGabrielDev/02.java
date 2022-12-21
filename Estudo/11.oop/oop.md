<!--

COLOCAR A IMAGEM AQUI


Object-Oriented Programming. (Programação orientado a objetos)


object
attribute -> Caracteristicas de um objeto;
methods   -> Acoes que esse objeto pode fazer;

Praticamente tudo pode ser um objeto...

Ex:
Garrafa

Garrafa é um objeto

//attributes
    String color = "black";
    boolean empty = false;
    int quantidade = 750;

//methods
drink(){
    sysout("Voce bebeu agua");
}

derramar(){
    sysout("Voce derramou agua");
}




Esses objetos são criados a partir de uma class;
Um objeto é uma instância de uma classe;

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Class (Clasifica um objeto)
É o molde que cria os objetos.


Quando eu crio um objeto, eu estou "instanciando" uma class em forma de um objeto.

Class -> Define os atributos e methods dos objetos dessa class.
É a blue print do meu objeto.
É o molde do meu objeto.
É o esquema de como vai ser meu objeto.

-Olhe a imagem "java-class-objects.jpg"

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Criando um objeto
Vamos criar um objeto do tipo Carro;

1-Primeiro, crie a class "Carro" com os attributes:
    //attributes
    String marca = "fiat";
    String modelo = "uno";
    String color = "Black";
    int year = 2020;
    int price = 50000;


2-Crie os methods
    //methods
    public void acelerar(){
        sysout("Voce está dirigindo o carro");
    }

    public void frear(){
        sysout("Voce freiou o carro");
    }




3-Crie um objeto no method main:

Syntax:
ClassName objeto = new ClassName();


ClassName objeto    -> Estou declarando o objeto.
new                 -> Estou instanciando o objeto. Quando eu escrevo "new", o computador reserva um espaço na memória ram para esse objeto.

ClassName()         -> Constructor


Carro c1 = new Carro();


4- Imprima 2 atributos 2 methods do objeto.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-->