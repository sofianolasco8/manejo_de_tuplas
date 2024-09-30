# manejo_de_tuplas
#Crear Tupla 
thistuple = ("apple", "banana", "cherry")
print(thistuple)


#Tupla con miembros duplicados 
thistuple = ("apple", "banana", "cherry", "apple", "cherry")
print(thistuple)


#Contanto miembros de la tupla
thistuple = ("apple", "banana", "cherry")
print(len(thistuple))


#Notese la diferencia de cuando SI es Tupla y cuando NO lo es, revisa lo que muestra este pequeño código 
thistuple = ("apple",)
print(type(thistuple))


#NOT a tuple
thistuple = ("apple")
print(type(thistuple))


#Asignando tuplas a variables 
#tuple1 = ("apple", "banana", "cherry")tuple2 = (1, 5, 7, 9, 3)
tuple3 = (True, False, False)


#Combinando tipos de datos en mis tuplas
tuple1 = ("abc", 34, True, 40, "male")
print(tuple1)



#Tipo de datos de una tupla
mytuple = ("apple", "banana", "cherry")
print(type(mytuple))


#Utilizando el método tuple para hacer una 
thistuple = tuple(("apple", "banana", "cherry"))
print(thistuple) 
