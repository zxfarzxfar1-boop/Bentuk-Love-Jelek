# Bentuk-Love-Jelek

def print_heart():
    
    for i in range(3):
        print(" " * (3 - i) + "*" * (2 * i + 1) + " " * (3 - i) + "*" * (2 * i + 1))
    
    
    for i in range(5, -1, -1):
        print(" " * (5 - i) + "*" * (2 * i + 1))


print_heart()
'' 
