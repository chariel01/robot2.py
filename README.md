#Variables propias del robot: 
M1: "motor para reciepiente 1"
M2: "motor para recipiente 2"
#el robot está tendra motores para revolver el contenido de los recipientes

P1: "piston que agrega  leche, cl y cn en Recipiente 1"
#Agregar leche, cl y cn en R1

Llave1: "flujo de agua hacia R2"
Llave1=['on', 'off']
#agregar agua a R2

P2: "piston que agrega arroz al recipiente 2"
#agregar arroz a R2

P3: "piston que gira el recipiente 1 hacia el recipiente 2"

#Vaciar R1 a R2

D1:"distancia en recipiente 1"
D2:"distancia en recipiente 2"
#distancia desde el sensor al fondo de los recipientes

Al: "alarma 1"
Al=['on', 'off']

P4:"piston que agrega azucar y dulce"
#Agregar azucar y dulce. 
SC: "sensor de color en R2"

#Variables importadas de receta1.py
#importar variables
S1: "Sensor de temperatura en recipiente 1"
S2: "Sensor de temperatura en recipiente 2"
T1: "temperatura recipiente 1"
T2: "temperatura recipiente 2"

gas1:"valvula de gas de recipiente1"
gas2:"valvula de gas de recipiente2"


gas1=['alto', 'bajo', 'apagado']
gas2=['alto', 'bajo', 'apagado']

#Comienza el programa

#Agregar leche, cl y cn en R1


#funcion del piston 
 i = 1
 if  i = 1
while  D1>20 and i>4:
   P1=['on']
delay (100)
P1=['off']
  i =i+ 1
elif D1>20:
 Al=['on']
 delay(100)
 Al=['off']
else:
 P1=['off']

#agregar agua a R2
Llave1['on']
delay(50)
if D2==10
Llave1['off']
elif  D2>15
 Al=['on']
 delay(100)
 Al=['off']
 else 
 Llave1['off']


#agregar arroz a R2
 i = 1
if  i = 1
while  D2>20 and i>4:
   P2=['on']
delay (100)
P2=['off']
  i =i+ 1
elif D2>20:
 Al=['on']
 delay(100)
 Al=['off']
else:
 P2=['off']

 #Vaciar R1 a R2
  i = 1
 if  i = 1
while  D2>15 and i>4:
   P3=['on']
delay (100)
P3=['off']
  i =i+ 1
elif D2>15:
 Al=['on']
 delay(100)
 Al=['off']
else:
 P3=['off']

#Agregar azucar y dulce 
 if  i = 1
while  D2>5 and i>4:
   P4=['on']
delay (100)
P4=['off']
  i =i+ 1
elif D2>5:
 Al=['on']
 delay(100)
 Al=['off']
else:
 P4=['off']
 #Revolver hasta que tome un color marrón a R2
while SC != cafe:
    M2=['on']
    delay (100)

M2['off']
