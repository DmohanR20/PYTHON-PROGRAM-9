# PYTHON-PROGRAM-9
program for REAL AND IMAGINARY
class complex():
    def __init__(self):
        self.real = 0
        self.img = 0
    def set_value(self,real,img):
        self.real = real
        self.img = img
    def __add__(self,val):
        temp = complex()
        temp.real = self.real+val.real
        temp.img = self.img+val.img
        return temp
    def display(self):
        print("(",self.real,'+',self.img,'i'")")
val1 = complex()
val2 = complex()
val3 = complex()
val1.set_value(1,2)
val2.set_value(3,4)
val3 = val1+val2
val3.display()
