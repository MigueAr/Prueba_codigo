# Prueba_codigo
Esta es una prueba de código para empezar a crear proyectos

package proyecto1;


import java.util.Scanner;


public class Ensayo{
    
    
       public static void main(String[]args){
              
              Scanner entrada = new Scanner(System.in);
              int numero;
              
              System.out.println("Ingrese un numero: ");
              numero = entrada.nextInt();
              
              if(numero>=1 && numero%2==0){
                  System.out.println("El numero: "+numero+" es par");
              }
              if(numero>=1 && numero%2!=0){
                  System.out.println("El numero: "+numero+" no es par");
              }
              else if(numero<=0){
                  System.out.println("El numero no esta dentro del intervalo de los positivos");
              }
       }
}
