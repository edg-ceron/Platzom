# Platzom

Platzom es un idioma inventado para Conocimientos acerca de javascript

##DEscripcion del idioma

-Si la palabra termina en "ar", se le quitan esos dos caracteres

-Si la palabra inicia con Z, se le añade "pe" al final

-Si la palabra traducida tiene 10 o mas letras se partira ala mitad y la unir con un guion medio

-Si la palabra original es un palindromo ninguna regla anterio cuenta y se devuelve la misma palabra intercalado MaYus-MiNuS



##Instalacion

```
npm install platzom
```
## Uso:
import platzom from `platzom`

console.log (platzom ("Programar")) //Program
console.log (platzom ("Zorro")) // Zorrope
console.log (platzom ("Zarpar")) // Zarpe
console.log (platzom ("abecedario")) // abece-dario
console.log (platzom ("sometemos")) // SoMeTeMoS

##Creditos

-Edgar Ceron

##License:
[MIT] (https://opensource.org/licenses/MIT)
