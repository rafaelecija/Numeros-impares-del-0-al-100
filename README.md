# Numeros-impares-del-0-al-100
este programa dirá cuantos números impares hay  del 0 al 100 y cuales son 
            //Declaracion de costantes
            const int VALOR_MINIMO = 0;//Valor minimo del contador
            const int VALOR_MAXIMO = 99;//Valor maximo del contador
            const int TERMINADOR = -1;
            //Declaracion de variables
            int contador;//numeros entre 0 y el 100
            int[] Lista_Impares;//Numero de impares
            int repeticion;//Numero de veces que se repite el while
            int indice;
            //Inicializacion
            //no es necesarien con el bucle for
            contador = VALOR_MINIMO; //Declararemos contador en valor minimo
            Lista_Impares = new int [VALOR_MAXIMO];
            repeticion = 0; //numero de repiticiones que se hace el bucle
            indice = 0;
            //Entrada

            //Procedimiento
            
           
            for (contador = VALOR_MINIMO; contador <= VALOR_MAXIMO; contador++)
            {
                if ((contador % 2) != 0)//saber si el numero es par
                {
                    Lista_Impares[indice] = contador;
                    
                    repeticion = repeticion + 1;//incrementa el contador
                    
                }
            }
            //Salida
            Console.WriteLine($"el numero de impares entre {VALOR_MINIMO} y {VALOR_MAXIMO} es {repeticion}");
            Console.WriteLine(Lista_Impares[indice]);  
