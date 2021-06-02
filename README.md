# cursoJos-POO
Fundamentos da programação orientada a objeto.

System.out.println("Pilares");

System.out.println("Abstração");
System.out.println("Herança");
System.out.println("Polimorfismo");
System.out.println("Encapsulamento");

//Carro________Tipo-classe

//ano : int_____________
//cor : String_________|__Atributos-variáveis 

//Ligar() : void_______________|
//Desligar() : void____________|________Ações-Métodos
//Acelerar() : void____________|

//void = método sem retorno

//__________
package POO;

public class Carro {
    int ano;   
	String cor;
	
	void ligar() {
		System.out.println("Engine ON...");
	}
	
	void desligar() {
		System.out.println("Engine OFF...");
	}
	
	void acelerar() {
		System.out.println("Vrumm...");
	}
}
//__________

package POO;

public class Ferrari {

	public static void main(String[] args) {

 		Carro ferrari = new Carro();
	    ferrari.ano = 2017;
 		ferrari.cor = "Azul";
 		System.out.println("Carro: Ferrari.");
 		System.out.println("Ano: " + ferrari.ano);
 		System.out.println("Cor: " + ferrari.cor);
 		
	}
}

//___________
















