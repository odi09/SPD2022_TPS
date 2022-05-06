# SPD2022_TPS
Tp SPD
/******************************************************************************

           **       *****      *****
         ******     *******    *******
         **  **     **   **    **    ** 
          **        **  ***    **    **
           **       ******     **    **
            **      ***        **    **
         **  **     ***        **    **
         ******     ***        *******
           **       ***        *****
 



                UNIVERSIDAD TECNOLOGICA NACIONAL
                Facultad Regional Avellaneda
                Tecnicatura Superior en Programación
                
        Asignatura: Sistema de Procesamiento de Datos.
        
        Grupo: Eleven
        Alumnos: 
        - Chirdo, Nicolas Andres           nchirdo@hotmail.com
        - Díaz, Orlando                    ojose89@gmail.com
        - Fernández, Florencia             florenciafernandezasconape@gmail.com
        - jiménez, Matías                  matias.jimenez.0096@gmail.com
        Division: 1 F
                ---- Primer cuatrimestre 2022 ----
        
        Fecha de entrega 04/05/2022

******************************************************************************/
/*
 *	Trabajo Práctico 1: Cronómetro Binario
 *
 *	Al iniciar la simulacion, todos los led deben comenzar apagados.
 *	Cada 1 segundo que transcurra, se deben encender los led
 *	de acuerdo al numero que representan.
 *
 *	Ejemplo:
 *   
 *	El numero 15 (0000001111) se representaria encendiendo los 
 *	leds AMARILLO y NARANJA.
 *	Al pasar al numero 16 (0000010000), se deben apagar todos 
 *	los led anteriores y encenderse uno de los leds VERDES. 
 *	Notese, en el ejemplo los 0 representan los led apagados 
 *	y los 1 los led encendidos). 
 *   
 *	-------------------------------------------------------
 *   
 *	Al presionarse el boton START, debe iniciar el cronometro.
 *	Volver a presionarlo hace que la secuencia se detenga. 
 *  (Como si se hubiese presionado pausa).
 *	Al presionarse el boton RESET, el cronometro
 *	debe reiniciarse y arrancar de 0.
 *
 *	Tip: Modularizar la función que controla el encendido de los 
 *	LEDS y de ser posible, todo el código para evitar repetir lineas lo mas posible.
 *  Usar millis para controlar el tiempo del contador para que el cambio de los 
 *	leds encendidos sea perceptible para el ojo humano y 
 *	documentar cada función creada en el código. 
 *	Un breve comentario que diga que es lo que hace esa función
 *  y de corresponder, que retorna).
      
*/
