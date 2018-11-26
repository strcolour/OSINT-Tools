# Qué es
Realización de búsquedas avanzadas para localizar información específica.

# Comandos básicos

__" "__ -> Muestra resultados que contengan la frase exacta.
ej: "Github"

__AND (+)__ -> Muestra búsquedas que incluya todas las palabras
ej: Github AND Strcolour

__OR (|)__ -> Muestra búsquedas que contengan uno de los resultados
ej: Github OR Strcolour

__NOT (-)__ -> excluye una palabra
ej: +el husky -negro

__*__ -> Funciona como comodín, reemplaza palabras y busca complementos.
ej: internal * error

# Comandos avanzados

__intitle__, __allintitle__ -> Muestra la palabra o frase que contenga la búsqueda en el título de la página. Para realizar una búsqueda ms exacta podemos utilizar __allintitle__, que restringirá la búsqueda para que aparezcan todos los trminos que hemos escrito. __allintitle__ no se puede combinar con otros operadores.
ej: Intitle:github strcolour, Allintitle:github strcolour

__inurl__, __allinurl__ -> Se usan de la misma forma que los comandos de arriba pero ahora restringimos la búsqueda en la URL.
ej: inurl:github strcolor, allinurl:github strcolour

__intext__, __allintext__ ->
