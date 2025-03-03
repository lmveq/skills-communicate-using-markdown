# Mi primer intento en hacer un markdown

## Hasta el momento todo va saliendo bien.

### Hoy Lunes 3 de marzo estoy probando como se escribe en los markdown´s de GitHub.


![Imagen de un husky](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/DOG-HUSKY_23JUL00.jpg/220px-DOG-HUSKY_23JUL00.jpg)

### Este husky me recuerda a mi perro Vlad, quien no tiene los ojos de dos colores diferentes pero tiene casi el mismo antifaz.

### Agrego una parte de un código para ve como se visuliza 
```` python
def fibonacci_generator(n = None):
    """
        Generating function up to n fibonacci numbers iteratively
        Params:
            n: int
        Return:
            int
    """
    f0, f1 = 0, 1
    yield f1
    while n == None or n > 1:
        fn = f0 + f1
        yield fn
        f0, f1 = f1, fn
        n -= 1
for n_fibo in fibonacci_generator(7):
    print(n_fibo)
```

# Creamos una task list

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
