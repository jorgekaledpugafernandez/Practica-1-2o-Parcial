# Practica-1-2o-Parcial
# codigo 1
import random

#se utilizan para almacenar varios elementos en una sola variable.
print(" puga fernandez jorge kaled")
thislist = [ 43, 57, 92, 20, 37, 5, 9,]

print("A continuacion se mostran el precio mas grande") # muestra que el numero es mas grande
#Min sirvira para mostrar mas peqeuño 
print (min(thislist))
print ("A ontinuacion se mostran el precio mas pequeño") #muestra que le numeor es mas pequeño
#mas sirvira para mostrar mas maximo
print(max(thislist))
![image](https://github.com/user-attachments/assets/dc40f8fe-525b-414d-9fd6-ff06f032ccd8)

# codigo 2 y 3
print("puga fernandez jorge kaled")
# Función para mostrar las materias
def MOSTRAR_MATERIAS(materias):
    #
    for materia in materias:
        print(f"Estoy cursando {materia}") #muestra que el imprimi que si toy cursado

# Solicitar las materias al usuario
materias = input("Escribe la primer materia: ") #muestra que el numero de las materias 
materias1 = input("Escribe la segunda materia: ") #muestra que el numero de las materias 
materias2 = input("Escribe la tercera materia: ") #muestra que el numero de las materias 
materias3 = input("Escribe la cuarta materia: ") #muestra que el numero de las materias 
materias4 = input("Escribe la quinta materia: ") #muestra que el numero de las materias 

# Crear la lista de materias
thislist = [materias, materias1, materias2, materias3, materias4] #nuestra que las materias cuando estyo cursado
print("\n", thislist)

# Llamar a la función para mostrar las materias
MOSTRAR_MATERIAS(thislist)
![image](https://github.com/user-attachments/assets/a954e588-ff4b-46e8-98c6-1d4ef02bc0e0)

# codigo 4
print("puga fernandez jorge kaled")
#mpmir las materiAS
def MOSTRAR_MATERIAS(thislist):
    #mostrar las materias
    for materia in thislist:
        #slair que sacar que si tamos cursando
        print(f"Estoy cursando:", materia[0], " y has obtenido ", materia[1])

materias = input("Escribe la primer materia: "), int(input("Escribe la caliiacion: ")) #muestra el numero de las materias y el las calificacion 
materias1 = input("Escribe la segunda materia: "), int(input("Escribe la caliiacion: "))#muestra el numero de las materias y el las calificacion 
materias2 = input("Escribe la tercera materia: "), int(input("Escribe la caliiacion: "))#muestra el numero de las materias y el las calificacion 
materias3 = input("Escribe la cuarta materia: "), int(input("Escribe la caliiacion: "))#muestra el numero de las materias y el las calificacion 
materias4 = input("Escribe la quinta materia: "), int(input("Escribe la caliiacion: "))#muestra el numero de las materias y el las calificacion 
thislist = [materias, materias1, materias2, materias3, materias4] #no ce pero creo que impmir los materias en las listas
print("\n", thislist)
#ORDEN LAS listas
MOSTRAR_MATERIAS(thislist)
![image](https://github.com/user-attachments/assets/a8d57d73-4364-4d76-a189-43b414a5cba2)

# codigo 5 
print("puga fernandez jorge kaled")
#devuelve un número flotante aleatorio 
import random

print("Cuales son los numeros triunfadores de la loteria?\n") #muestra los numero de trinfadores de la loteria 
num1 = int(input("Cual es el numero? ")) #muestra el numero de las que ganste o que  sacaste el numero
num2 = int(input("Cual es el numero? ")) #muestra el numero de las que ganste o que  sacaste el numero
num3 = int(input("Cual es el numero? ")) #muestra el numero de las que ganste o que  sacaste el numero
num4 = int(input("Cual es el numero? ")) #muestra el numero de las que ganste o que  sacaste el numero
num5 = int(input("Cual es el numero? ")) #muestra el numero de las que ganste o que  sacaste el numero
#qyue saca los numero en las canjear los numeros
loteria = ([num1, num2,num3, num4, num5])
#rdena la lista en orden ascendente de forma predeterminada 
loteria.sort()
#
print("\nGrqacias por introducir los numneros\nA continuacion se mostraran en orden\n")
print(loteria,"\n")
#aletorio
item = random.choice(loteria)
print("\n El numnero ganador definitivo es : "), print(item)        
![image](https://github.com/user-attachments/assets/79b7a19a-7e94-4130-b8c3-52578c1294e9)



