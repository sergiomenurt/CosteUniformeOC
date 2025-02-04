# Búsqueda por Coste Uniforme - Ruta Ourense a Calatayud

## 1. Inicialización
f: [(0, Ourense)]
c: {}

## 2. Expansión de nodos paso a paso

### Paso 1
- **Nodo actual:** Ourense (0 km)
- **Nodos en frontera:** Ponferrada (175 km), Benavente (236 km)
- **Se elige:** Ponferrada (175 km)
- **Conjunto de nodos visitados (c):** {Ourense}

### Paso 2
- **Nodo actual:** Ponferrada (175 km)
- **Nodos en frontera:** Benavente (236 km), León (288 km)
- **Se elige:** Benavente (236 km)
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada}

### Paso 3
- **Nodo actual:** Benavente (236 km)
- **Nodos en frontera:** León (288 km), Valladolid (348 km), Palencia (361 km)
- **Se elige:** León (288 km)
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada, Benavente}

### Paso 4
- **Nodo actual:** León (288 km)
- **Nodos en frontera:** Valladolid (348 km), Palencia (361 km), Osorno (409 km)
- **Se elige:** Valladolid (348 km)
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada, Benavente, León}

### Paso 5
- **Nodo actual:** Valladolid (348 km)
- **Nodos en frontera:** Palencia (361 km), Osorno (409 km), Aranda (443 km)
- **Se elige:** Palencia (361 km)
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada, Benavente, León, Valladolid}

### Paso 6
- **Nodo actual:** Palencia (361 km)
- **Nodos en frontera:** Osorno (409 km), Aranda (443 km), Burgos (453 km)
- **Se elige:** Osorno (409 km)
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada, Benavente, León, Valladolid, Palencia}

### Paso 7
- **Nodo actual:** Osorno (409 km)
- **Nodos en frontera:** Aranda (443 km), Burgos (453 km), Osma (527 km)
- **Se elige:** Aranda (443 km)
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada, Benavente, León, Valladolid, Palencia, Osorno}

### Paso 8
- **Nodo actual:** Aranda (443 km)
- **Nodos en frontera:** Burgos (453 km), Osma (527 km), Soria (593 km)
- **Se elige:** Burgos (453 km)
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada, Benavente, León, Valladolid, Palencia, Osorno, Aranda}

### Paso 9
- **Nodo actual:** Burgos (453 km)
- **Nodos en frontera:** Osma (527 km), Soria (593 km), Calatayud (667 km)
- **Se elige:** Osma (527 km)
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada, Benavente, León, Valladolid, Palencia, Osorno, Aranda, Burgos}

### Paso 10
- **Nodo actual:** Osma (527 km)
- **Nodos en frontera:** Soria (593 km), Calatayud (667 km)
- **Se elige:** Soria (593 km)
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada, Benavente, León, Valladolid, Palencia, Osorno, Aranda, Burgos, Osma}

### Paso 11
- **Nodo actual:** Soria (593 km)
- **Nodos en frontera:** Calatayud (667 km)
- **Se elige:** Calatayud (667 km). Al realizar el test, se descube que es el objetivo. **Objetivo Cumplido**
- **Conjunto de nodos visitados (c):** {Ourense, Ponferrada, Benavente, León, Valladolid, Palencia, Osorno, Aranda, Burgos, Osma, Soria}

## 3. Distancia total

La distancia total acumulada desde **Ourense** hasta **Calatayud** es de **667 km**.


