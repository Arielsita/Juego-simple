# Juego-simple
adivinar numero
#### num_adivinar = ran.randint (0,15)
num_adivinar=3
for i in range (3):
    num_suposicion = int (input("intento %d: Adivina el numero!!!"))
    if num_adivinar == num_suposicion:
        print ("Genial Adivinaste!!")
        print ("Ganaste!!")
        break
