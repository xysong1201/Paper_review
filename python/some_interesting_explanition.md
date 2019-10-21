#### A function returns a value based on the given arguments
In Python, functions can be passed around and used as arguments.  
If the function is named without parentheses. This means that only a reference to the function is passed. The function is not executed. if the function is written with parentheses, it will be called as usual.  
It’s possible to define functions inside other functions. Such functions are called *inner functions*.   
Python also allows you to use functions as return values  
'''

def parent(num):
    def first_child():
        return "Hi, I am Emma"

    def second_child():
        return "Call me Liam"

    if num == 1:
        return first_child
    else:
        return second_child
        '''

