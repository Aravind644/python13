# python13
METHOD OVERLOADING


1.Write two methods with the same name but different number of parameters of same type
and call the methods from main method

class cal:
    def add(a,b):
        res=a+b
        print('sum of 2 numbers:',res)
        return
    def add(a,b,c):
        res=a+b+c
        print('sum of 3 numbers:',res)
        return

class overload:
    def main():
        cal.add(10,20,30)
        cal.add(10,20) #error
        return
overload.main()



2.Write two methods with the same name but different number of parameters of different
data type and call the methods from main method

class cal:
    def add(a,b,c):
        res=a+b+c
        print('sum of 3 numbers:',res)
        return
    def add(a,b):
        res=a+b
        print('sum of 2 numbers:',res)
        return

class overload:
    def main():
        cal.add(10,30)
        cal.add('aravind','reddy',10) 
        return
overload.main()





3.Write two methods with the same name and same number of parameters of same type
and call from main method

class cal:
    def add(a,b):
        res=a+b
        print('sum of 2 numbers:',res)
        return
    def add(a,b):
        res=a+b
        print('sum of 2 numbers:',res)
        return

class overload:
    def main():
        cal.add(10,20)
        cal.add(10,30) 
        return
overload.main()



4.Write two methods with the same name and same number of parameters of different
type and call from main method


class cal:
    def add(a,b):
        res=a+b
        print('sum of 2 numbers:',res)
        return
    def add(a,b):
        res=a+b
        print('sum of 2 numbers:',res)
        return

class overload:
    def main():
        cal.add(10,20)
        cal.add('aravind','reddy') 
        return
overload.main()



5.Write two methods with the same name, number of parameters and data type but
different return Type.


* It is not possible to have a method with same parameters and different return type. Compiler throws error in the below case(Duplicate method).


