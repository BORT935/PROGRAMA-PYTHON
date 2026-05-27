Matriz = [
    ["Bastardos sin Gloria", 1999, 10, "Accion"],
    ["Piratas del caribe", 2000, 7, "accion"],
    ["el show de troumen", 1997, 8, "Comedia"],
    ["la monja", 2015, 5, "Terror"],
    ["dune", 2020, 8, "Ficcion"],
    ["Transformers", 2002, 10, "ficcion"],
    ["la forma del agua", 2019, 8, "Ficcion"],
    ["indestructibles", 2005, 7, "Accion"],
    ["Mad Max", 2011, 9, "Ficcion"],
    ["Chucky", 1999, 6, "Terror"],
]

def Contar_titulos(Matriz, Umbral, año_limite):
    contador = 0
    titulos_cumplen = []
    for titulo in Matriz:
        nombre = titulo[0]
        año = titulo[1]
        calificacion = titulo[2]

        if calificacion >= Umbral and año >= año_limite:
            contador += 1
            titulos_cumplen.append(nombre)
        
    return contador, titulos_cumplen

if __name__ == "__main__":
    umbral = int(input("ingrese calificacion minima: "))
    año_limite = int(input("ingrese año minimo: "))
    
    Resultado, Peliculas = Contar_titulos(Matriz, umbral, año_limite)
    
    print(f"\nCantidad de titulos que cumplen las condiciones: {Resultado}")
    if Peliculas:
        print("Peliculas que cumplen:")
        for pelicula in Peliculas:
            print(f"- {pelicula}")
    else:
        print("No hay peliculas que cumplan los criterios.")