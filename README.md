# nikoperations

First Module and simple module creatd by me . 
So, other can  install this module in their system 
" pip install nikoperations "

Usecase Example: code of python how it will perform add , subtract



from nikoperations.addition import add
from nikoperations.subtraction import subtract
if __name__ == '__main__':
    x = int(input("enter your number "))
    y= int(input("enter your second number "))
    addition_answer= add(x, y)
    subtraction_answer=subtract(x,y)
    print("here is your anser :")
    print(addition_answer)
    print(subtraction_answer)
