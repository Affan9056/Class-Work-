num =int(input("enter the number.")
 if num%2 ==0:
print ("The given number is an even number") 






a = int(input("Enter a:"));
b = int(input("Enter b:"));
c = int(input("Enter c:"));
if a>b and a>c:
print ("From the above three numbers given a is largest")
if b>a and b>c:
print ("From the above three numbers given b is largest")
if c>a and bc>c:
 print ("From the above three numbers given c is largest")  





number = int(input("Enter the number?"))
if number==10:
  Print("The given number is equals to 10");
elif number==50:
  Print("The given number is equals to 50");
elif number==100:
  Print("The given number is equals to 100");
else:
  Print("The given number is equals to 10, 50 or 100");




class Human:
      attr1="human"
      attr2="student"
      def fun(self):
          print("I'm a",self.attr1)
          print("I'm a",self.attr2)
Rodger=Human()

Print(Rodger.attar1)
Rodger.fun()



print("Class and Object")


class Bike:
    name=""
    gear=0

bike1=Bike()

bike1.gear=11
bike1.name="Honda"

print(f"Name: {bike1.name}, Gear:{bike1.gear}")




bike2=Bike()

bike2.gear=5
bike2.name="Mountain Bike"

print(f"Name: {bike2.name}, Gear:{bike2.gear}")


print("Class and Object Example 2")

class Five:
    name=""
    age=0

student1= Five()

student1.name="Salman"
student1.age=12

print(f"Name:{student1.name}, Age:{student1.age}")


student2= Five()

student2.name="Ahmed"
student2.age=13

print(f"Name:{student2.name}, Age:{student2.age}")

student3=Five()


student3.name="Ibrahim"
student3.age=14


print(f"Name:{student3.name}, Age{student3.age}")

class Human:
  attr1="Human"
  attr2="Student"

  def fun (self):
   print("I'm a", self.attr1)
   print("I'm a", self.attr2)


Salman=Human()

print(Salman.attr1)
Salman.fun()


class Class:
  attr1="Human"
  attr2="Student"

  def fun (self):
   print("I'm a", self.attr1)
   print("I'm a", self.attr2)


Salman=Class()

print(Salman.attr1)
Salman.fun()





class Python:
  def __init__ (self, name, company):

      self.name= name
      self.company=company
  def show (self):
      print("Hello my name is " + self.name + " and I work in " + self.company + ".")
obj = Python   ("Salman","Bano Qabil")
obj.show()




# Sample class with init method
class Person:
  # init method or constructor
  def __init__(self, name):
    self.name = name
  # Sample Method
  def say_hi(self):
    print('Hello, my name is', self.name)
p = Person('Ghufran')
p.say_hi()




# define a class
class Employee:
    # define an attribute
    employee_id = 0

# create two objects of the Employee class
employee1 = Employee()
employee2 = Employee()

# access attributes using employee1
employee1.employeeID = 1001
print(f"Employee ID: {employee1.employeeID}")

# access attributes using employee2
employee2.employeeID = 1002
print(f"Employee ID: {employee2.employeeID}")




class python:
  def __init__(self,name,company):
      self.name=name
      self.company=company
  def show(self):
      print("Hello my name is "+self.name + " and I " +" work in "+self.company+".")
obj=python("Hassan", "Bano Qabil")
obj.show()





class Room:
  length=0.0
  breadth=0.0

  def calculate_area (self):
      print("Area of Room=", self.length*self.breadth)

study_room=Room()
study_room.length=42.5
study_room.breadth=30.8
study_room.calculate_area()






class Employee:
  __id=0
  __name=""
  __gender=""
  __city=""
  __salary=0
  def setData(self):
      self.__id=int(input("Enter Id:\t"))
      self.__name = input("Enter Name:\t")
      self.__gender = input("Enter Gender:\t")
      self.__city = input("Enter City:\t")
      self.__salary = int(input("Enter Salary:\t"))
  def showData(self):
      print("Id\t\t:",self.__id)
      print("Name\t:", self.__name)
      print("Gender\t:", self.__gender)
      print("City\t:", self.__city)
      print("Salary\t:", self.__salary)


def main():
  #Employee Object
  emp=Employee()
  emp.setData()
  emp.showData()

if __name__=="__main__":
  main()
