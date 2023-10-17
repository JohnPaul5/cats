# cats
week3


class Cat:
    def __init__(self, name, age, weight):
        self.name = name
        self.age = age
        self.weight =weight

    def eat(self, amount):
        self.weight += 1

    def walk(self):
        if self.weight == 1:
          print("Can no longer walk.")
        else:
            self.weight -= 1


cat1 = Cat("Binnie", 4, 4)
cat2 = Cat("Clyde", 1, 2)
cat3 = Cat("Old Tom", 10, 6)

cat1.eat(3)
cat2.eat(2)
cat3.walk()
cat2.walk()
cat2.walk()
cat2.walk()

print(cat1.weight)
print(cat2.weight)
print(cat3.weight)
