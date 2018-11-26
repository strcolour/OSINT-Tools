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

__intext__, __allintext__ -> Muestra resultados que estén incluidos en el texto de una página. funciona igual que el motor de búsqueda pero no busca en el título, enlaces y URL.
ej: intext:OSINT, allintest:OSINT

__site__ -> Muestra resultados relacionados con la página que queramos.
ej: site:github.com Strcolour

__cache__ -> Muestra resultados guardados en la cache de google. esto sirve para encontrar información antigua en un web o que haya sido eliminada o modificada.
ej: cache:github

__link__ -> Muestra páginas que enlazan a la página web indicada.
ej: link:micanaldeyoutube.es

__filetipe__ o __ext__ -> Muestra ficheros con un formato específico. Es importante entender el concepto de extensión como la parte de la URL que sucede al nombre del archivo, pero que aparece antes del signo de interrogación que inicia la lista de parámetros.
ej: Gatos filetipe:pdf, Gatos ext:pdf

__numrange__ -> Nos permite acotar las busquedas de números en un rango determinado.
ej: numrange:10-15

__related__ -> Muestra webs que están relacionadas con una determinada.
ej: realted:strcolour.es

# [Información que podemos obtener](https://antoniogonzalezm.es/google-hacking-46-ejemplos-hacker-contrasenas-usando-google-enemigo-peor/)

