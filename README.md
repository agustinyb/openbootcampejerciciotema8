# openbootcampejerciciotema8
open bootcamp ejercicio tema 8

import java.io.PrintStream;

public class Main {
    public Main() {
    }

    public static void main(String[] args) {
        System.out.println("*********************************\nTema 8 Ejercicio 1:\n");
        Persona persona = new Persona();
        persona.setNombre("Agustin");
        persona.setEdad(26);
        persona.setTelefono(98500064);
        PrintStream var10000 = System.out;
        String var10001 = persona.getNombre();
        var10000.println("Persona:\nNombre:" + var10001 + "\nEdad:" + persona.getEdad() + "\nTelefono:" + persona.getTelefono());
                         }
                     }
                     class Persona {
                         private int edad;
                         private int telefono;
                         private String nombre;

                         Persona() {
                         }

                         public int getEdad() {
                             return this.edad;
                         }

                         public void setEdad(int edad) {
                             this.edad = edad;
                         }

                         public int getTelefono() {
                             return this.telefono;
                         }

                         public void setTelefono(int telefono) {
                             this.telefono = telefono;
                         }

                         public String getNombre() {
                             return this.nombre;
                         }

                         public void setNombre(String nombre) {
                             this.nombre = nombre;
                         }
                     }
