QUESTÕES DE INTRODUÇÃO A PROGRAMAÇÃO ORIENTADA A OBJETOS!

<p>1.A JVM não é nada mais do que uma máquina virtual que deixa o hardware e a plataforma visíveis a aplicação, em que as seguintes funções:</p>

-Interpreta o Bytecode Java para ser executado no S.O. (o arquivo tem contém o bytecode é o .class gerado na compilação do .java), faz a Checagem de erros em tempo real e o gerenciamento automático de memória.

<p>2.Qual a diferença entre JRE e JDK?</p>

O JDK é um ambiente para desenvolvimento de software que são usados para desenvolver aplicativos de Java em plataformas Java. Já o JRE é uma parte do JDK que proporciona o requisito mínimo para executar os programas Java.

<p>3.Crie um programa Java que imprima o seguinte texto “Terminei a primeira aula com um programa Java!”.</p>

             class ProgramaJava {
                public static void main( String args [] ) {
                    System.out.println(“Terminei a primeira aula com um programa Java!”);
                }
             }
<p>4.Compile o programa desenvolvido no exercício anterior. A seguir apague o arquivo .class gerado e tente executar o programa. O que aconteceu?</p>

O programa não vai compilar.

<p>5.Mude o nome do método “main” para “start”, compile e execute. O que aconteceu?</p>

             class ProgramaJava {
                public static void start( String args [] ) {
                    System.out.println(“Terminei a primeira aula com um programa Java!”);
                }
             }

Diz que o metodod não existe e pede para corrigir o erro colocando "main" no lugar do "start".

Error: Main method not found in class Programajava, please define the main method as:
   public static void main(String[] args)
or a JavaFX application class must extend javafx.application.Application

<p>6.Crie um programa Java para imprimir duas linhas de texto usando duas linhas de código “System.out”, onde aparecerá o seu nome na primeira linha e na segunda linha aparecerá o time para o qual você torce.</p>
 
 
    public class NameTime { 
        public static void main(String [] args) { 
            System.out.println("Débora");
            System.out.println("Corinthians");
        }
    }

<p>7.Experimente escrever todo o programa anterior em maiúsculo, compile e execute. O que aconteceu?</p>

     PUBLIC CLASS NAMETIME{
        PUBLIC STATIC VOIDMAIN(STRING[] ARGS){
            SYSTEM.OUT.PRINTLN("Débora");
            SYSTEM.OUT.PRINTLN("Corinthians");
        }
     }

A  "public class" não pode ser executada.

<p>8.Experimente salvar o arquivo com um nome diferente do nome da classe, compile e execute. O que aconteceu?</p>

Não compila pois ele só consegue reconhecer se o nome do arquivo for o mesmo da class.

