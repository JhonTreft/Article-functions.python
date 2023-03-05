## Las Funciones Mas Usadas Y Las que uso Actualmente


## Map()


## Filter()


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


## Eval()



## Hash()



## Id()




## Iter()
