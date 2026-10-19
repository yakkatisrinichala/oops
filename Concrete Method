from abc import ABC, abstractmethod

class Animal(ABC):
    @abstractmethod
    def make_sound(self):
        pass

    def move(self):
        return "Moving"

class Dog(Animal):
    def make_sound(self):
        return "Bark"

dog = Dog()
print(dog.move())
