```python
#EJERCICIO 1
mat = 1941521
print("Francisco Everardo López Dominguez", mat)


os.system("cls")
```


```python
#EJERCICIO 2
num1 = int(input("Introduzca un número entero: "))
num2 = int(input("Introduzca otro número entero: "))

suma = num1+num2
resta = num1-num2
mult = num1*num2
div = num1/num2

print( "Suma: ",suma)
print( "Resta: ", resta)
print( "Multiplicación: ", mult)
print( "División: ", div)

os.system("cls")
```


```python
#EJERCICIO 3
i=3
j=0
while i <= 31:
    print(i)
    j=j+i
    i=i+3
   

print("La suma de los numeros es: ", j)

os.system("cls")
```


```python
#EJERCICIO 4
numprim = int(input("Inserta un numero: "))
cont = 0
verificar = False
for i in range(1,numprim+1):
    if (numprim% i)==0:
        cont = cont + 1
    if cont >= 3:
        verificar=True
        break

if cont==2 or verificar==False:
    print ("El numero es primo")
else: print ("El numero no es primo")
    
os.system("cls")
```


```python
print( " Calculadora ")

nume1 = int(input("Introduce un número entero: ") )
nume2 = int(input("Introduce el segundo número entero: ") )

#op1 == 0

while True: 
        print( " ¿Que Operación Deseas Realizar?  1.- Sumar 2.- Resta 3.- Multilicación 4.- División 5.- Elevar a un exponente 6.- Salir ")
    
op1 == int(input("Introduce una opcion: "))
    
if op1 == 1:
    print("Suma: ",nume1,"+",nume2,"es",nume1+nume2)
elif op1 == 2:
    print("Resta: ",nume1,"-",nume2,"es",nume1-nume2)
elif op1 == 3:
    print("Multiplicación: ",nume1,"*",nume2,"es",nume1*nume2)
elif op1 == 4:
    print("División: ",nume1,"/",nnume2,"es",nume1/nume2)
elif op1 == 5:
    print("Exponente",nume1,"^",nume2,"es",nume^nume2)
elif op1 == 6:
    break
else:
    print("Opción incorrecta, introduzca una opción entre el 1-6")
    
os.system("cls")
```
