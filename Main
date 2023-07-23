//invocar la funcion main
fun main() {
  //declarar variable mutable
    var opcion = 0
  //crear ciclo while para la seleccion 
    while (opcion != 99) {
        println("=========== Menú ===========")
        println("1. Operadores")
        println("2. Condicionales")
        println("3. Ciclos")
        println("99. Salir")
        println("============================")
        println("Seleccione una opción: ")
        opcion = readLine()?.toIntOrNull() ?: 0
//creacion de if anidados para las opcciones segun lo anterior
        if (opcion == 1) {
            println("Opciones disponibles para Operadores:")
            println("1. Calcular el área de un triángulo.")
            println("2. Ingresar dos números y sumarlos.")
            println("3. Ingresar un número y mostrar el cuadrado.")
            println("4. Convertir de euros a dólares.")
            println("5. Calcular el área y perímetro de un cuadrado.")
            println("6. Calcular el área y volúmen de un cilindro.")
            println("7. Calcular la longitud y el área del círculo inscrito.")
            println("8. Calcular el promedio de tres números.")
            println("0. Volver al menú principal.")
            println("Seleccione una opción: ")
            val opcionOperadores = readLine()?.toIntOrNull() ?: 0
            if (opcionOperadores == 1) {
                calcularAreaTriangulo()
            } else if (opcionOperadores == 2) {
                sumarDosNumeros()
            } else if (opcionOperadores == 3) {
                mostrarCuadradoNumero()
            } else if (opcionOperadores == 4) {
                convertirEurosADolares()
            } else if (opcionOperadores == 5) {
                calcularAreaPerimetroCuadrado()
            } else if (opcionOperadores == 6) {
                calcularAreaVolumenCilindro()
            } else if (opcionOperadores == 7) {
                calcularLongitudAreaCirculo()
            } else if (opcionOperadores == 8) {
                calcularPromedioTresNumeros()
            } else if (opcionOperadores == 0) {
                println("Volviendo al menú principal.")
            } else {
                println("Opción inválida.")
            }
        } else if (opcion == 2) {
            println("Opciones disponibles para Condicionales:")
            println("1. ¿El número ingresado es positivo o negativo?")
            println("2. ¿Cuál es el mayor y cuál es el menor entre dos números?")
            println("3. Calcular el mayor y el menor de tres números.")
            println("4. Sumar o restar dos números según una condición.")
            println("5. Calcular el cociente entre dos números.")
            println("6. Sumar o multiplicar dos números según una condición.")
            println("7. Determinar si un año es bisiesto o no.")
            println("0. Volver al menú principal.")
            println("Seleccione una opción: ")
            val opcionCondicionales = readLine()?.toIntOrNull() ?: 0
            if (opcionCondicionales == 1) {
                numeroPositivoNegativo()
            } else if (opcionCondicionales == 2) {
                mayorMenorEntreDosNumeros()
            } else if (opcionCondicionales == 3) {
                mayorMenorEntreTresNumeros()
            } else if (opcionCondicionales == 4) {
                sumarRestarSegunCondicion()
            } else if (opcionCondicionales == 5) {
                calcularCociente()
            } else if (opcionCondicionales == 6) {
                sumarOMultiplicarSegunCondicion()
            } else if (opcionCondicionales == 7) {
                esAnoBisiesto()
            } else if (opcionCondicionales == 0) {
                println("Volviendo al menú principal.")
            } else {
                println("Opción inválida.")
            }
        } else if (opcion == 3) {
            println("Opciones disponibles para Ciclos:")
            println("1. Imprimir todos los múltiplos de 3 entre 1 y 100.")
            println("2. Imprimir los números impares entre 0 y 100.")
            println("3. Imprimir los números pares del 1 al 100.")
            println("4. Imprimir los cuadrados de los números del 1 al 30.")
            println("5. Sumar los cuadrados de los cien primeros números naturales.")
            println("6. Generar y mostrar números entre dos valores en secuencia ascendente.")
            println("7. Sumar todos los números ingresados por teclado hasta que se ingrese cero.")
            println("0. Volver al menú principal.")
            println("Seleccione una opción: ")
            val opcionCiclos = readLine()?.toIntOrNull() ?: 0
            if (opcionCiclos == 1) {
                imprimirMultiplosDeTres()
            } else if (opcionCiclos == 2) {
                imprimirNumerosImpares()
            } else if (opcionCiclos == 3) {
                imprimirNumerosPares()
            } else if (opcionCiclos == 4) {
                imprimirCuadrados()
            } else if (opcionCiclos == 5) {
                sumarCuadradosCienPrimerosNumeros()
            } else if (opcionCiclos == 6) {
                generarNumerosEnSecuenciaAscendente()
            } else if (opcionCiclos == 7) {
                sumarNumerosHastaCero()
            } else if (opcionCiclos == 0) {
                println("Volviendo al menú principal.")
            } else {
                println("Opción inválida.")
            }
        } else if (opcion == 99) {
            println("¡Hasta luego!")
        } else {
            println("Opción inválida. Intente de nuevo.")
        }
    }
}

// Operadores
/*la función calcula y muestra el área de un triángulo a partir de la base y la altura ingresadas por el usuario, asegurándose de que ambos valores sean números válidos y positivos. Si el usuario no ingresa dos valores válidos y positivos, se mostrará un mensaje de error.*/
fun calcularAreaTriangulo() {
    println("Ingrese la base del triángulo:")
    val base = readLine()?.toDoubleOrNull()
    println("Ingrese la altura del triángulo:")
    val altura = readLine()?.toDoubleOrNull()

    if (base != null && altura != null && base > 0 && altura > 0) {
        val area = 0.5 * base * altura
        println("El área del triángulo es: $area")
    } else {
        println("Entrada inválida. La base y la altura deben ser números positivos.")
    }
}
/*la función calcula y muestra la suma de dos números ingresados por el usuario, asegurándose de que ambos valores sean números válidos. Si el usuario no ingresa dos números válidos, se mostrará un mensaje de error.*/
fun sumarDosNumeros() {
    println("Ingrese el primer número:")
    val num1 = readLine()?.toDoubleOrNull()
    println("Ingrese el segundo número:")
    val num2 = readLine()?.toDoubleOrNull()

    if (num1 != null && num2 != null) {
        val suma = num1 + num2
        println("La suma de $num1 y $num2 es: $suma")
    } else {
        println("Entrada inválida. Ambos valores deben ser números.")
    }
}
/* la función calcula y muestra el cuadrado de un número ingresado por el usuario, asegurándose de que el valor ingresado sea válido. Si el usuario no ingresa un número válido, se mostrará un mensaje de error.*/
fun mostrarCuadradoNumero() {
    println("Ingrese un número:")
    val num = readLine()?.toDoubleOrNull()

    if (num != null) {
        val cuadrado = num * num
        println("El cuadrado de $num es: $cuadrado")
    } else {
        println("Entrada inválida. Debe ingresar un número.")
    }
}
/*la función convierte una cantidad de euros a dólares utilizando una tasa de cambio ficticia y muestra el resultado, asegurándose de que el valor ingresado sea válido y positivo.*/
fun convertirEurosADolares() {
    println("Ingrese la cantidad de euros:")
    val euros = readLine()?.toDoubleOrNull()

    if (euros != null && euros >= 0) {
        val tasaCambio = 1.18 // Tasa de cambio ficticia
        val dolares = euros * tasaCambio
        println("$euros euros equivale a $dolares dólares")
    } else {
        println("Entrada inválida. La cantidad de euros debe ser un número positivo.")
    }
}
/*la función calcula y muestra el área y el perímetro de un cuadrado a partir del lado ingresado por el usuario, asegurándose de que el valor ingresado sea válido y positivo.*/
fun calcularAreaPerimetroCuadrado() {
    println("Ingrese el lado del cuadrado:")
    val lado = readLine()?.toDoubleOrNull()

    if (lado != null && lado >= 0) {
        val area = lado * lado
        val perimetro = 4 * lado
        println("El área del cuadrado es: $area")
        println("El perímetro del cuadrado es: $perimetro")
    } else {
        println("Entrada inválida. El lado del cuadrado debe ser un número positivo.")
    }
}
/*la función calcularAreaVolumenCilindro() permite al usuario ingresar el radio y la altura de un cilindro y calcula el área total y el volumen del mismo, mostrando los resultados en pantalla. También maneja el caso de entrada inválida si alguno de los valores ingresados no es un número válido o no es positivo.*/
fun calcularAreaVolumenCilindro() {
    println("Ingrese el radio del cilindro:")
    val radio = readLine()?.toDoubleOrNull()
    println("Ingrese la altura del cilindro:")
    val altura = readLine()?.toDoubleOrNull()

    if (radio != null && altura != null && radio >= 0 && altura >= 0) {
        val areaBase = Math.PI * radio * radio
        val areaLateral = 2 * Math.PI * radio * altura
        val areaTotal = 2 * areaBase + areaLateral
        val volumen = areaBase * altura
        println("El área total del cilindro es: $areaTotal")
        println("El volumen del cilindro es: $volumen")
    } else {
        println("Entrada inválida. El radio y la altura deben ser números positivos.")
    }
}
/*la función calcularLongitudAreaCirculo() permite al usuario ingresar el radio de una circunferencia y calcula la longitud de la circunferencia y el área del círculo inscrito, mostrando los resultados en pantalla. También maneja el caso de entrada inválida si el valor ingresado no es un número válido o no es positivo.*/
fun calcularLongitudAreaCirculo() {
    println("Ingrese el radio de la circunferencia:")
    val radio = readLine()?.toDoubleOrNull()

    if (radio != null && radio >= 0) {
        val longitud = 2 * Math.PI * radio
        val area = Math.PI * radio * radio
        println("La longitud de la circunferencia es: $longitud")
        println("El área del círculo inscrito es: $area")
    } else {
        println("Entrada inválida. El radio debe ser un número positivo.")
    }
}
/* la función calcularPromedioTresNumeros() permite al usuario ingresar tres números y calcula el promedio de los tres, mostrando el resultado en pantalla. También maneja casos de entrada inválida si los valores ingresados no son números válidos.*/
fun calcularPromedioTresNumeros() {
    println("Ingrese el primer número:")
    val num1 = readLine()?.toDoubleOrNull()
    println("Ingrese el segundo número:")
    val num2 = readLine()?.toDoubleOrNull()
    println("Ingrese el tercer número:")
    val num3 = readLine()?.toDoubleOrNull()

    if (num1 != null && num2 != null && num3 != null) {
        val promedio = (num1 + num2 + num3) / 3
        println("El promedio de los tres números es: $promedio")
    } else {
        println("Entrada inválida. Los tres valores deben ser números.")
    }
}

// Condicionales
/*la función numeroPositivoNegativo() permite al usuario ingresar un número y determina si es positivo, negativo o cero, mostrando el resultado correspondiente en pantalla. También maneja el caso de entrada inválida si el valor ingresado no es un número válido.*/
fun numeroPositivoNegativo() {
    println("Ingrese un número:")
    val numero = readLine()?.toDoubleOrNull()

    if (numero != null) {
        if (numero > 0) {
            println("El número ingresado es positivo.")
        } else if (numero < 0) {
            println("El número ingresado es negativo.")
        } else {
            println("El número ingresado es cero.")
        }
    } else {
        println("Entrada inválida. Debe ingresar un número.")
    }
}
/*la función mayorMenorEntreDosNumeros() permite al usuario ingresar dos números y luego muestra en pantalla cuál es el número mayor y cuál es el número menor entre los dos. También maneja casos de entrada inválida si los valores ingresados no son números válidos.*/
fun mayorMenorEntreDosNumeros() {
    println("Ingrese el primer número:")
    val num1 = readLine()?.toDoubleOrNull()
    println("Ingrese el segundo número:")
    val num2 = readLine()?.toDoubleOrNull()

    if (num1 != null && num2 != null) {
        if (num1 > num2) {
            println("El mayor es: $num1")
            println("El menor es: $num2")
        } else if (num1 < num2) {
            println("El mayor es: $num2")
            println("El menor es: $num1")
        } else {
            println("Ambos números son iguales.")
        }
    } else {
        println("Entrada inválida. Ambos valores deben ser números.")
    }
}
/*esta función permite al usuario ingresar tres números y encuentra el número mayor y el número menor entre los tres.*/
fun mayorMenorEntreTresNumeros() {
    println("Ingrese el primer número:")
    val num1 = readLine()?.toDoubleOrNull()
    println("Ingrese el segundo número:")
    val num2 = readLine()?.toDoubleOrNull()
    println("Ingrese el tercer número:")
    val num3 = readLine()?.toDoubleOrNull()

    if (num1 != null && num2 != null && num3 != null) {
        val mayor = if (num1 >= num2 && num1 >= num3) {
            num1
        } else if (num2 >= num1 && num2 >= num3) {
            num2
        } else {
            num3
        }

        val menor = if (num1 <= num2 && num1 <= num3) {
            num1
        } else if (num2 <= num1 && num2 <= num3) {
            num2
        } else {
            num3
        }

        println("El mayor es: $mayor")
        println("El menor es: $menor")
    } else {
        println("Entrada inválida. Los tres valores deben ser números.")
    }
}
/*esta función permite al usuario ingresar dos números y realiza una suma o una resta de acuerdo con la condición especificada (el primer número es menor que el segundo o no).*/
fun sumarRestarSegunCondicion() {
    println("Ingrese el primer número:")
    val num1 = readLine()?.toDoubleOrNull()
    println("Ingrese el segundo número:")
    val num2 = readLine()?.toDoubleOrNull()

    if (num1 != null && num2 != null) {
        if (num1 < num2) {
            val suma = num1 + num2
            println("La suma de los dos números es: $suma")
        } else {
            val resta = num1 - num2
            println("La resta de los dos números es: $resta")
        }
    } else {
        println("Entrada inválida. Ambos valores deben ser números.")
    }
}
/*esta función permite al usuario ingresar dos números y calcula el cociente si es posible realizar la división (el divisor no es cero), o muestra un mensaje de error si el divisor es cero.*/
fun calcularCociente() {
    println("Ingrese el dividendo:")
    val dividendo = readLine()?.toDoubleOrNull()
    println("Ingrese el divisor:")
    val divisor = readLine()?.toDoubleOrNull()

    if (dividendo != null && divisor != null) {
        if (divisor != 0.0) {
            val cociente = dividendo / divisor
            println("El cociente es: $cociente")
        } else {
            println("No es posible dividir entre cero.")
        }
    } else {
        println("Entrada inválida. Ambos valores deben ser números.")
    }
}
/*esta función permite al usuario ingresar dos números y realiza una suma o una multiplicación de acuerdo con la condición especificada (al menos uno de los números es negativo o ambos números son no negativos).*/
fun sumarOMultiplicarSegunCondicion() {
    println("Ingrese el primer número:")
    val num1 = readLine()?.toDoubleOrNull()
    println("Ingrese el segundo número:")
    val num2 = readLine()?.toDoubleOrNull()

    if (num1 != null && num2 != null) {
        if (num1 < 0 || num2 < 0) {
            val suma = num1 + num2
            println("La suma de los dos números es: $suma")
        } else {
            val multiplicacion = num1 * num2
            println("La multiplicación de los dos números es: $multiplicacion")
        }
    } else {
        println("Entrada inválida. Ambos valores deben ser números.")
    }
}
/*esta función determina si un año ingresado por el usuario es bisiesto o no y muestra el resultado correspondiente en pantalla.*/
fun esAnoBisiesto() {
    println("Ingrese un año:")
    val ano = readLine()?.toIntOrNull()

    if (ano != null) {
        val esBisiesto = (ano % 4 == 0 && ano % 100 != 0) || (ano % 400 == 0)
        if (esBisiesto) {
            println("El año $ano es bisiesto.")
        } else {
            println("El año $ano no es bisiesto.")
        }
    } else {
        println("Entrada inválida. Debe ingresar un año válido.")
    }
}

// Ciclos
/*esta función muestra en pantalla los múltiplos de 3 entre 1 y 100 en una sola línea.*/
fun imprimirMultiplosDeTres() {
    println("Múltiplos de 3 entre 1 y 100:")
    var numero = 1
    while (numero <= 100) {
        if (numero % 3 == 0) {
            print("$numero ")
        }
        numero++
    }
    println()
}
/*esta función muestra en pantalla los números impares entre 0 y 100 en una sola línea.*/
fun imprimirNumerosImpares() {
    println("Números impares entre 0 y 100:")
    var numero = 1
    while (numero <= 100) {
        print("$numero ")
        numero += 2
    }
    println()
}
/*esta función muestra en pantalla los números pares del 1 al 100 en una sola línea.*/
fun imprimirNumerosPares() {
    println("Números pares del 1 al 100:")
    var numero = 2
    while (numero <= 100) {
        print("$numero ")
        numero += 2
    }
    println()
}
/*sta función muestra en pantalla los cuadrados de los números del 1 al 30 en una sola línea.*/
fun imprimirCuadrados() {
    println("Cuadrados de los números del 1 al 30:")
    var numero = 1
    while (numero <= 30) {
        val cuadrado = numero * numero
        print("$cuadrado ")
        numero++
    }
    println()
}
/*esta función calcula la suma de los cuadrados de los cien primeros números naturales y muestra el resultado.*/
fun sumarCuadradosCienPrimerosNumeros() {
    var numero = 1
    var sumaCuadrados = 0
    while (numero <= 100) {
        val cuadrado = numero * numero
        sumaCuadrados += cuadrado
        numero++
    }
    println("La suma de los cuadrados de los cien primeros números naturales es: $sumaCuadrados")
}
/* esta función toma dos números ingresados por el usuario y muestra todos los números comprendidos entre ellos en secuencia ascendente. Si los valores ingresados no son válidos o el primer número no es menor que el segundo número, mostrará un mensaje de error.*/
fun generarNumerosEnSecuenciaAscendente() {
    println("Ingrese el primer número:")
    val num1 = readLine()?.toIntOrNull()
    println("Ingrese el segundo número:")
    val num2 = readLine()?.toIntOrNull()

    if (num1 != null && num2 != null && num1 < num2) {
        var numero = num1
        println("Números generados en secuencia ascendente:")
        while (numero <= num2) {
            print("$numero ")
            numero++
        }
        println()
    } else {
        println("Entrada inválida. El primer número debe ser menor que el segundo.")
    }
}
/*esta función permite al usuario ingresar múltiples números y los suma hasta que ingresa el número cero, luego muestra la suma total de los números ingresados excluyendo el cero.*/
fun sumarNumerosHastaCero() {
    var sumaTotal = 0
    var numero: Int
    do {
        println("Ingrese un número (0 para terminar):")
        numero = readLine()?.toIntOrNull() ?: 0
        if (numero != 0) {
            sumaTotal += numero
        }
    } while (numero != 0)
    println("La suma total de los números ingresados es: $sumaTotal")
}
