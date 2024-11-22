# Problema 2 (princípio get/put)

Vamos fazer um método que copia os elementos de uma lista para uma
outra lista que pode ser mais genérica que a primeira.

```
List<Integer> myInts = Arrays.asList(1, 2, 3, 4);
List<Double> myDoubles = Arrays.asList(3.14, 6.28);
List<Object> myObjs = new ArrayList<Object>();

copy(myInts, myObjs);

copy(myDoubles, myObjs);
```

### Java wrapper types

![Java wrapper types](Java wrapper types.png)