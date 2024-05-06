# Repo-Trabajos-PA-comisi-n1
class Animal():
    """Clase que representa a los animales"""
    def __init__(self, nombre, raza, color):
        self.nombre = nombre
        self.raza = raza
        self.color = color

class Perro(Animal):
    def __init__(self, nombre, raza, color):  
        super().__init__(nombre, raza, color)

#Crea una instancia de Perro
mi_perro = Perro("Pedro", "Pitbull", "Marron")

"""Accede a las propiedades de la instancia mi_perro"""
print("Mi perro es:", mi_perro.raza)
print("Se llama:", mi_perro.nombre)
print("Es de color:", mi_perro.color)
