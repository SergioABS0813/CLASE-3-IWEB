# CLASE-3-IWEB

## USO DE SCANNER

Primero importamos la librería scanner

        import java.util.Scanner;
        
Luego, creamos el objeto de scanner:

        Scanner scanner = new Scanner(System.in);
Luego empleamos el scanner para el registro de datos:

        String opcionSeleccionada = scanner.nextLine();

## Creación de arreglo (Primera Forma)
    int[] notas = {10,11,12,13,14};
    
![aa](https://github.com/SergioABS0813/CLASE-3-IWEB/assets/134556600/edf4f83c-4f57-458a-b751-067fbdd59bf4)

## Creación de arreglo (Segunda Forma)
Creamos arreglo de 10 elementos

        int[] notas = new Int[10];
    
![b](https://github.com/SergioABS0813/CLASE-3-IWEB/assets/134556600/ab75282e-4a22-47b0-b6e2-7a3a21ea0260)

## COMO CONOCER EL TAMAÑO DE UN ARREGLO?
Donde notas es el nombre del arreglo

        sout(notas.lenght)
    
![bb](https://github.com/SergioABS0813/CLASE-3-IWEB/assets/134556600/fde56f2f-57fc-49b8-a04f-fe55756b3024)

## Arreglo de objetos
Es basicamente un arreglo donde todos sus elementos son OBJETOS.

![aa](https://github.com/SergioABS0813/CLASE-3-IWEB/assets/134556600/56f91199-e022-4d32-9660-9648346f1249)

## LIBRERIA ARRAYS
Se coloca encima de todo el código

        import java.util.ArrayList;

## ARRAYLIST
Es un arreglo dinámico 

Creamos un arrayList para contener objetos de clase Persona
![aaa](https://github.com/SergioABS0813/CLASE-3-IWEB/assets/134556600/976aa7f6-9e5e-4d5c-b6a7-23c0be50272d)

Se puede mandar a funciones pero solo mandariamos la lista a la que queremos hacer un metodo (como python) MAIN

![aa](https://github.com/SergioABS0813/CLASE-3-IWEB/assets/134556600/3c4aa10e-e30a-4a32-8014-d9b4bfe5ebf0)

Si necesitamos de eso, recordar que en el metodo tenemos que tener como variable la lista con su tipo de dato:

![bbb](https://github.com/SergioABS0813/CLASE-3-IWEB/assets/134556600/e8a67304-2521-425f-aa0e-565a5a3e1772)


## HashSet

Es un arreglo dinámico que sirve para buscar lo que contiene LA LISTA GLOBAL (no profundiza en cada objeto que hay dentro de esa lista)

Primero importamos la libreria que nos permite crear HashSet (arriba de todo):

        import java.util.HashSet;
                
Creamos el HashSet (o sea creamos una lista): 

        HashSet<String> listaNumeroSeries = new HashSet<>();
                
En String va el tipo de variable del HashSet (o sea de los elementos) y luego le colocas el nombre de la lista.

Nos va a servir el HashSet para poder comparar:

        if (listaNumeroSeries.contains(numeroSerie)){ //AQUI PODEMOS comparar lo que contiene con los demás elementos
            System.out.println("Error, ya existe el número de serie");
        }
        else{
            listaNumeroSeries.add(numeroSerie); //AÑADIMOS al hashset el numero de serie
            equipo.setMarca(marca);
            equipo.setTipo(tipo);
            equipo.setCantidadDePuertos(cantidadDePuertos);
            equipo.setCosto(costoRouter);
            equipo.setNumeroDeSerie(numeroSerie);
            listaEquipos.add(equipo); //Se añade a la lista de equipos que creamos
        }

![listapoderes](https://github.com/SergioABS0813/CLASE-3-IWEB/assets/134556600/f4bb3fe4-0f46-4e14-8e61-0edd876a98b8)






