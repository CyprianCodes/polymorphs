class Animal:
    def move(self):
        print("This animal moves...")

class Dog(Animal):
    def move(self):
        print("The dog runs 🐕")

class Bird(Animal):
    def move(self):
        print("The bird flies 🐦")

class Fish(Animal):
    def move(self):
        print("The fish swims 🐟")

# Polymorphic behavior
animals = [Dog(), Bird(), Fish()]

for animal in animals:
    animal.move()
# polymorphs
