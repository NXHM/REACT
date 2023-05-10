# REACT
Board:
Crea el tablero (3x3) del 3 en raya con una array de 9 elementos. En este, gracias a la funcion xIsNext, se pasa de turno luego de hacer click . Asimismo también se verifica si hay un ganador o no con calculateWinner.
Square:
Retorna botones de clase square que activan la funcion onSquareclick al ser clickeados
Game:
Es el componente principal, el cual tiene el historial de las jugadas. Tras hacer una jugada, aquí es donde se actualiza el historial setHistory y el movimiento actual setCurrentMove. Asimismo, gracias a la funcion jumpTo puede regresar a jugadas anteriores. Además, este al ser el componente principal, retorna el Board.

