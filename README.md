# nikoperations

First Module and simple module creatd by me . 
So, other can  install this module in their system 
" pip install nikoperations "

Usecase Example: code of python how it will perform add , subtract



from nikoperations.addition import add
from nikoperations.subtraction import subtract

if __name__ == '__main':
    try:
        x = int(input("Enter your first number: "))
        y = int(input("Enter your second number: "))
        
        addition_answer = add(x, y)
        subtraction_answer = subtract(x, y)
        
        print("Here are your answers:")
        print(f"Addition: {addition_answer}")
        print(f"Subtraction: {subtraction_answer}")
    except ValueError:
        print("Please enter valid integers for your numbers.")

