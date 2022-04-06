# By > Ajolote.Play
from colorama import *


# Banner

print (""" 
  ____      _            _       _
 / ___|__ _| | ___ _   _| | __ _| |_ ___  _ __ 
| |   / _` | |/ __| | | | |/ _` | __/ _ \| '__|
| |__| (_| | | (__| |_| | | (_| | || (_) | |   
 \____\__,_|_|\___|\__,_|_|\__,_|\__\___/|_|   

""")
# Banner

# num 1 + num 2 = suma/resta
num1 = int(input (Fore.GREEN + "Escribe el primero número : " + Fore.LIGHTBLUE_EX + "\nEscribe Aqui >"))
num2 = int(input (Fore.LIGHTGREEN_EX + "\nEscribe el segundo número : " + Fore.LIGHTBLUE_EX + "\nEscribe Aqui >"))
# num 1 + num 2 = suma/resta


select = int(input (Fore.LIGHTCYAN_EX + "\nEscoje que operación quieres que realize : \n[1] Suma \n[2] Resta \nEscribe Aqui >"))

if select == 1:
    print(num1 + num2)

if select == 2:
    print(num1 - num2)
    
    ```
