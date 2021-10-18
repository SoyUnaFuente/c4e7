Una famosa cadena de noticias te contrato para que diseñaras un programa el cual muestre los titulares en Twitter, sin embargo esta plataforma limita los tweets a 140 caracteres.

Escribe un Loop con Break en donde recorras la lista titulares dada, y en cada iteración inserta los titulares en una variable tweet. Tienes que tomar en cuenta lo siguiente:

    Al concatenar los strings a la variable tweet ten en cuenta el espacio que debes dejar entre titulares y separarlos por coma ','.
    Si es necesario tienes que truncar los titulares para que queden exactamente 140 caracteres en la variable tweet

Input

# Variables a usar.
titulares = ["Oso se come a hombre en el Avila",
             "Anuncian nuevas leyes para la nación",
             "Si lees esto, estudia los resumenes de clase para el Quiz ;)",
             "Gato rescata a bombero atrapado en un árbol",
             "La UNIMET tiene nueva cancha de fútbol",
             "Los estudiantes de algoritmos y programción son los mejores!"]

Output:

`Oso se come a hombre en el Avila, Anuncian nuevas leyes para la nación, Si lees esto, estudia los resumenes de clase para elQuiz ;), Gato r`

Hints:

Al igual que las listas los String se pueden usar slice(), donde cada carácter se puede asimilar como una posición en una lista/vector.

nombre = "Juan Pablo"

print(nombre[0] ) # output= J

print(nombre[0:4]) # output= Juan

Si quieres saber más sobre slice te dejo este link de referencia:

https://www.w3schools.com/python/showpython.asp?filename=demo_string2
