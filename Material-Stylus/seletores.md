## Exemplos de uso de seletores no Stylus

Com base na maneira de regras clean do Stylus, iremos ver alguns exemplos de seletores.

### Caso-1 (Modelo simples)

```Stylus
h1
    font-size 1rem
```
### Caso-2 (Modelo de multiplos seletores separados por vírgula)
```Stylus
input[type="text"], textarea
    width 100%
```
### Caso-3 (Referencia dos pais)
```Stylus
a
    font-size 1rem
    &:hover
        text-decoration none
```