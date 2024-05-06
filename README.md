# Repo-Trabajos-PA-comisi-n1
class Animal():
    """clase que representa a los animales"""
    def __init__(self, nombre, raza, color):
        self.nombre = nombre
        self.raza = raza
        self.color = color

    from animal import Animal
class Perro(Animal):
    def __init__(self, nombre, raza, color):  
      nombre = "Pedro"
      raza = "Pitbull"
      color = "Marron"

print("Mi perro es:", self.raza)
print("Se llama:", self.nombre)
print("Mi perro es:", self.color)
