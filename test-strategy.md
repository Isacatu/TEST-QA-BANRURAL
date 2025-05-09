El primer error que se encuentra es el la linea 87
guessSubmit.addeventListener('click', checkGuess); == addEventListener tiene la E en minuscula, no permitiendo que se conozca como función

Segundo Error en la linea 78 se cambio la opción de else if por simplemente If

El tercer error se encuentra en la linea 50
let lowOrHi = document.querySelector('lowOrHi'); == No llegamos a llamar por la falta del "." en "lowOrHi" por lo que se le agrega ".lowOrHi