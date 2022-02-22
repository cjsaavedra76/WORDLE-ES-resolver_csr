# WORDLE (ES) Resolver_csr by Carlos José Saavedra

## Script en Python para resolver el reto diario de la página [WORDLE (ES)](https://wordle.danielfrg.com/)

Usa el diccionario con las palabras (11.180) utilizadas que estaban incrustadas en la página web al **22/01/2022**

## Como funciona:

A cada ronda, introduce tu palabra en la pagina web y el resultado en el script:

1) Letras que sabemos NO están [Letras en GRIS]
2) Letras que sabemos SI están [Letras en COLOR]
3) Letras con la posición MAL [AMARILLO] - En esta pregunta tienes que meter las contestación según el patrón *Letra:posición, Letra:posición*
>Ejemplo: si nos sale en amarillo la letra E en la posicion 2 y la letra C en la posicion 4, pondremos E:2, C:4
4) Letras con la posición BIEN [Letras en VERDE] - En esta pregunta pondremos la letra en verde en su posicion y las posiciones que no conozcamos las marcaremos con asterisco (\*)
>Ejemplo: si nos sale en verde la letra S en la posicion 1 y la letra N en la poscion 3, meteremos la siguiente cadena: S\*N\*\*

Cuando esten contestadas las cuatro preguntas, el programa nos propondra las palabras que cumplen con todas las condiciones y nos volverá a preguntar por el siguiente intento.

En el caso de tener instalado el módulo `pyperclip`, el listado de palabras resultado se copiará en el portapapeles.

```
pip install pyperclip
```

### Ejemplo de jugada

---

Captura de pantalla de **WORDLE (ES)** de la jugada del 22/02/2022

![Captura de pantalla de **WORDLE (ES)**](https://github.com/cjsaavedra76/WORDLE-ES-resolver_csr/blob/3e84a804be67d7a37fe2b18d21e1839bd2a190e8/Captura_WORLDLE-ES.png)


Captura de pantalla de **WORDLE (ES) Resolver_csr**

![Captura de pantalla de WORDLE **(ES) Resolver_csr**](https://github.com/cjsaavedra76/WORDLE-ES-resolver_csr/blob/3e84a804be67d7a37fe2b18d21e1839bd2a190e8/Captura_wordle-es-resolver_csr.png)
