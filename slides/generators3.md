# Generators
## Casos de uso

Los generadores pueden ser útiles en 3 situaciones:

 - _Iterators_: recuperando medienta _next()_ cada valor devuelto por **yield** (en un for-of)
 - _Observers_: next puede recibir un parámetro mediante _yield_, y el generador pausará hasta que reciba el siguiente parámetro
 - _Coroutines_: Mediante librerías externas ([co](https://github.com/tj/co), [koa](https://github.com/koajs/koa)), podemos escribir código síncrono, me manera asíncrona (evitando callbacks!).
