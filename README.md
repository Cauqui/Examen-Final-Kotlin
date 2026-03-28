# Examen-Final-Kotlin
# AUQUI CASTRO CHRISTIAN ALEXANDER

## Ejercicio 1
Código corregido

fun main() {

var edad = 20

edad = 25

println(edad)

}


<img width="277" height="74" alt="image" src="https://github.com/user-attachments/assets/a2abe4d3-ad31-4d70-9e3f-f8c8170f48cb" />


Se corrigió el error de declarar la varibable edad con val, se prodecidió a declarar con  var.


## Ejercicio 2
Código corregido

fun main() {

    val x = 10
    
    if (x == 10) {
    
        println("Correcto")
        
    }
    
}

<img width="197" height="56" alt="image" src="https://github.com/user-attachments/assets/5d85464d-7c38-4f75-84d7-f567b3f25155" />

Se le agregó == para darle igualdad y proceder con el resultado 


## Ejercicio 3
Código corregido


fun main() {

    val nombre: String = "Christian"
    
    println(nombre)
}

<img width="225" height="67" alt="image" src="https://github.com/user-attachments/assets/02b5bbcc-2593-4f9f-be55-b8bdd7b3bb40" />

Falto asignar valor al nombre, se agregó "Christian" para que se imprima


## Ejercicio 4
Código corregido

fun main() {

    val nota = 15
    
    when {
    
        nota >= 11 -> println("Aprobado")
        
        else -> println("Desaprobado")
        
    }
}


<img width="332" height="93" alt="image" src="https://github.com/user-attachments/assets/ac48555b-dddc-4f7f-90c9-3d69f50d43bd" />

Se declaró de forma correcta el when para que se cumpla la función


## Ejercicio 5
Código corregido

fun main() {

    for (i in 1..5) {
    
        println(i)
        
    }
}


<img width="259" height="169" alt="image" src="https://github.com/user-attachments/assets/10138385-1c0b-429c-9b63-ec4112e7336e" />


Se cumple la enúmeración creciente 


## Ejercicio 6
Código corregido

fun main() {

    val numero = 5
    
    if (numero > 10) {
    
        println("Mayor")
        
    } else {
    
        println("Menor")
    }
}

<img width="240" height="59" alt="image" src="https://github.com/user-attachments/assets/42ddb0f7-ca1f-43c1-8086-42285efb1cce" />

En el código no se encontró errores pero si una mala práctica al hacerlo, puede compilar porque kotlin las oimite.
Se corrigió de una forma de estructura correcta.




## Ejercicio 7
Código corregido


fun main() {

    val nota = 18
    
    when {
    
        nota >= 18 -> println("Excelente")
        
        nota >= 11 -> println("Aprobado")
        
        else -> println("Desaprobado")
        
    }
    
}


<img width="226" height="84" alt="image" src="https://github.com/user-attachments/assets/520f0cd0-1e07-4712-a6a0-9f8238514818" />


Se corregió la estructura del when


## Ejercicio 8
Código corregido


fun saludo(): String {

    return "10"

    
}



fun saludo(): Int { 

    return 10
    
}


fun main() {

    println(saludo())
    
}


<img width="235" height="86" alt="image" src="https://github.com/user-attachments/assets/f0b57e1f-ea23-43a3-a099-abd0d6a3348f" />


Error al confundir el int 



## Ejercicio 9
Código corregido



fun mostrar(nombre: String) {

    println(nombre)
    
}


fun main() {

   
    mostrar("Auqui") 
    
}



<img width="162" height="55" alt="image" src="https://github.com/user-attachments/assets/2f521811-71bb-4909-80e8-9c8e9e5b191d" />

Se corrigió el error mostrar(nombre: String) espera recibir un dato de tipo texto (String) para poder trabajar.






## Ejercicio 10
Código corregido

fun main() {

    var x = 10
    
    x = 20 
    
    println(x) 
    
}

<img width="160" height="60" alt="image" src="https://github.com/user-attachments/assets/22545be7-b090-43ff-9390-6de860b9eedd" />



Se corrigió





