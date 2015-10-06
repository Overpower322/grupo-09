# grupo-09
Hacer un programa donde se ingresen cinco numeros y se imprima el mayor
view plainprint?
A=int(input("ingrese un numero\n"))  
B=int(input("ingrese otro numero\n"))  
C=int(input("ingrese un nuemero\n"))  
D=int(input("ingrese un nuemero\n"))  
E=int(input("ingrese un nuemero\n"))  
if(A > B and A > C and A > D and A > E):  
 X=A  
else:  
 if(B > A and B > C and B > D and B > E):  
  X=B  
 else:  
  if(C > A and C > B and C > D and C > E ):  
   X=C
  if(D > B and D > C and D > D and D > E):  
   X=D
  else:  
   X=E 

print("el mayor es "+str(X)) 
