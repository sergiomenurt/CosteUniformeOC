# Algoritmos de Búsqueda - Ejercicios Resueltos

Este repositorio contiene ejercicios resueltos de diferentes algoritmos de búsqueda aplicados a problemas específicos.

## Índice
1. [Búsqueda en Anchura](#busqueda-en-anchura)
2. [Búsqueda en Profundidad](#busqueda-en-profundidad)
3. [Búsqueda en Profundidad con Límite 5](#busqueda-en-profundidad-con-limite)
4. [Búsqueda de Coste Uniforme](#busqueda-de-coste-uniforme)
5. [Búsqueda A*](#busqueda-a)
6. [Ejercicio Coste Uniforme Ciudades](#ejercicio-coste-uniforme-ciudades)
7. [Ejercicio del Metro de Tokio](#ejercicio-del-metro-de-tokio)

## Búsqueda en Anchura
Este ejercicio resuelve un problema utilizando el algoritmo de búsqueda en anchura.

![Búsqueda en Anchura](images/BUsqueda anchura.jpg)

---

## Búsqueda en Profundidad
Este ejercicio resuelve un problema utilizando el algoritmo de búsqueda en profundidad.

![Búsqueda en Profundidad](images/Ejercicio_Profundidad_sin_limite.jpg)

---

## Búsqueda en Profundidad con Límite 5
Este ejercicio resuelve un problema utilizando la búsqueda en profundidad con un límite de profundidad.

![Búsqueda en Profundidad con Límite](images/BusquedaProfundidad.jpg)


Si el límite de profundidad es 5, la búsqueda no podrá llegar a soluciones que estén en niveles más profundos. Si la solución está en el nivel 6, el algoritmo no la encontrará. Se producirá un fracaso por corte, ya que la solución existe pero el algoritmo no la explora debido al límite impuesto.

Si aumentamos el límite de profundidad a 6, la búsqueda podrá llegar hasta ese nivel y encontrar la solución si está allí.

---

## Búsqueda de Coste Uniforme
Este ejercicio resuelve un problema utilizando la búsqueda de coste uniforme.

![Búsqueda de Coste Uniforme](images/CosteUniforme.jpg)

---

## Búsqueda A*
Este ejercicio resuelve un problema utilizando el algoritmo A*.

![Búsqueda A*](images/ejercicio_AStar.jpg)


Sí, la heurística es admisible porque no sobreestima el costo real hasta el objetivo. Como es admisible y también es consistente, el algoritmo A es A*.

---

## Ejercicio Coste Uniforme Ciudades

![Coste Uniforme Ciudades Mapa](Ejercicio3.png)
![Coste Uniforme Ciudades](busqueda_coste_uniforme_ruta_ourense_calatayud.md)

---


## Ejercicio del Metro de Tokio

![Metro de Tokio 1](imagen1_tokyo-tub.jpg)
![Metro de Tokio 1](imagen2_tokyo-tub.jpg)
![Metro de Tokio 1](imagen3_tokyo-tub.jpg)
![Metro de Tokio 1](arbol_tokyo-tub.jpg)

