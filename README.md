# Demo1
#method overloading
class overloading:
    def dis(self):
        print("first dis metgod")
    def dis(self):
        print("second dis method")
    def dis(self):
        print("third dis method")
obj=overloading()
obj.dis()
obj.dis()

# Runtime polimorphism
class Mammal():
    def __init__(self,Mammalname):
        print(Mammalname,"is a worm-blooded animal")
class dog(Mammal):
    def __init__(self):
        print("dog has four legs")
        super().__init__("billi")
d1=dog()

