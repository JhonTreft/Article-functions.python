## Las Funciones Mas Usadas Y Las que uso Actualmente


## Map()

```
my_list = [2.6743,3.63526,4.2325,5.9687967,6.3265,7.6988,8.232,9.6907]
updated_list = map(round, my_list)
print(updated_list)
print(list(updated_list))
```

## Filter()

```
lista = range(-5, 5)
menor_cero = list(filter(lambda x: x < 0, lista))
print(menor_cero)
```


## MemoryView
```
data = bytearray(b'abcefg')
v = memoryview(data)
v.readonly
False
v[0] = ord(b'z')
data
bytearray(b'zbcefg')
v[1:4] = b'123'
data
bytearray(b'z123fg')
v[2:6] = b'spam'
data
bytearray(b'z1spam')
```

## Set()

```
unicos = set([3, 5, 6, 1, 5])
```
## Eval()

```
x = 1
eval('x+1')
```

## Hash()
```
import hashlib

m = hashlib.sha256()
m.update(b"El Libro De Python")
salida = m.hexdigest()

print(salida)
```

## Id()

```
a = [1, 2, 3]
b = [1, 2, 3]

print(id(a)) # 4496626880
print(id(b)) # 4496626816
```


## Iter()

```
x = iter(["pera", "plátano", "uva"])
print(next(x))
print(next(x))
print(next(x))

```
