# robot2.py
# Descricpción 2, del robot que aplica la recete
#Variables propias del robot: 
M1: "motor para reciepiente 1"
M2: "motor para recipiente 2"
#el robot está tendra motores para revolver el contenido de los recipientes

P1: "piston que agrega  leche, cl y cn en Recipiente 1"
#Agregar leche, cl y cn en R1

Llave1: "flujo de agua hacia R2"
#agregar agua a R2

P2: "piston que agrega arroz al recipiente 2"
#agregar arroz a R2

P3: "piston que gira el recipiente 1 hacia el recipiente 2"

#Vaciar R1 a R2

D1:"distancia en recipiente 1"
D2:"distancia en recipiente 2"
#distancia desde el sensor al fondo de los recipientes

#Variables importadas de receta1.py
S1: "Sensor de temperatura en recipiente 1"
S2: "Sensor de temperatura en recipiente 2"
T1: "temperatura recipiente 1"
T2: "temperatura recipiente 2"

gas1:"valvula de gas de recipiente1"
gas2:"valvula de gas de recipiente2"


gas1=['alto', 'bajo', 'apagado']
gas2=['alto', 'bajo', 'apagado']
