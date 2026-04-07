# Projet-informatique-
Jeu du Mastermind

Groupe BI (TD03)

Céliane
Nisrine 
Ana 
Eva


Comparaison
    for i in range(4):
        if proposition[i] == combinaison_temp[i]:
            bien_places += 1
            combinaison_temp[i] = None
        elif proposition[i] in combinaison_temp:
            mal_places += 1
            combinaison_temp[combinaison_temp.index(proposition[i])] = None

# Résultat
    print("Bien placés :", bien_places)
    print("Mal placés :", mal_places)
