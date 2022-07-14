# Compilador2022
Para proyecto final de la materia de compiladores el cual es un pequeño compilador, para un lenguaje con las siguientes funcionalidades:

Operaciones permitidas:
  Aritméticas:
    Suma +
    Resta -
    Multiplicación *
    División /
    Exponenciación ^
  Comparación:
    ==
    != 
    >
    <
    >=
    <=
  Booleanas
    and 
    or
  Operaciones de bloques:
    ( )
    {}
Un sistema de tipos:
  Int
  Float
  String
  Bolean
  
 Operaciones permitidas entre el sistema de tipos:
 
                    int         	    float         	      string          	    boolean
    int	        Aritmeticas,        Aritmeticas,               +                  and, or, 
                comparacion	        comparacion		        (concatenacion)           ==, !=
    float	      Aritmeticas,        Aritmeticas, 	             + 	                and, or, 
                comparacion	        comparacion           (concatenacion)           =, !=
    string 
   (OPCIONAL) 	    ----	              ----	                 +                    ==, !=	
                                                         (concatenacion),
                                                             ==, !=
    boolean	        ----	              ----	                 ----	               and, or,
                                                                                    ==, !=
                  
Flujos de control existentes, deberan seguir una estructura similar al lenguaje C, por simplicidad todo deberán llevar llaves:
  If , else, elif
  while () {}.  
      -- Caracterisitica opcional ( El no entregarla, limitara 1 punto sobre el maximo )
  for (;;) {}.    
      -- Caracterisitica opcional ( El no entregarla, limitara 1 punto sobre el maximo )
Para marcar el final de una sentencia se utilizara ";"
Es permitido el declarar y asignar una variable en la misma linea
