x = 'SI'
meme_dict = {
            "CRINGE": "Algo excepcionalmente raro o embarazoso",
            "LOL": "Una respuesta común a algo gracioso (Laughing out loud)",
            "ROFL": "Una respuesta a una broma (Rolling on the floor)",
            "SHEESH": "Ligera desaprobación, una traducción hispana sería 'vaya'",
            "CREEPY": "(Adj.) Aterrador, siniestro",
            "AGGRO": "Ponerse agresivo/enojado",
            }

while True:
    if x == 'SI':
        word = input("Escribe una palabra que no entiendas (¡con mayúsculas!): ")
        
        if word in meme_dict.keys():
            print(meme_dict[word])
        else:
            print("Uy, tu palabra no está!")
    
        x = input("Buscar de nuevo? (SI o NO)")
    else:
        break
print("Gracias por usar!")
