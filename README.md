# Python-
#calculadora de fisica

cal1=1
cal2=0
op = 0
while cal2 < cal1:
    print("calcular potencia em kwh:1")
    print("calcular resistencia:2")
    op= int(input())
    if op == 1:
        pot = float(input("insert potencia"))
        time = float(input("insert necessary time"))
        consumption = (pot/1000)*(time/60)
        print (consumption) 
        cal2 = int(input(" 1 para sair 0 para continuar: "))  
    elif op == 2:
        volt = float(input("insert volts"))
        amper = float(input("insert  amper"))
        resistor = volt/amper
        print (resistor)
        cal2 = int(input(" 1 para sair 0 para continuar: "))  

