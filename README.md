# ClaseAuto

package ProyectoAuto;

public class Auto {

	String color, marca;
	int km;
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Auto auto1 = new Auto();
		Auto auto2 = new Auto();
		
		auto1.color = "Blanco";
		auto1.marca = "Audi";
		auto1.km = 0;
		
		auto2.color = "Negro";
		auto2.marca = "Wolkswagen";
		auto2.km = 75000;
		
		System.out.println("El color del auto1 es: " + auto1.color);
		System.out.println("La marca del auto1 es: " + auto1.marca);
		System.out.println("El kilometraje del auto1 es: " + auto1.km);
		
		System.out.println("El color del auto2 es: " + auto2.color);
		System.out.println("La marca del auto2 es: " + auto2.marca);
		System.out.println("El kilometraje del auto2 es: " + auto2.km);
		
	}

}
