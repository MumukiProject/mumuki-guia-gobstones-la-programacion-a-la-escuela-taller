De la misma forma que hay un "poner bolita" (`Poner`), tenemos un "sacar bolita" (`Sacar`), que quita exactamente una bolita del color dado.

Por ejemplo, el siguiente programa saca dos bolitas de la posición inicial.

```gobstones
program {
  Sacar(Rojo)
  Sacar(Rojo)
}
```

> Sabiendo esto, creá un programa que elimine todas las bolitas de este tablero.

<gs-board>
  GBB/1.0
    size 2 2
    cell 0 0 Rojo 1 Negro 1 Verde 1 Azul 1
    head 0 0
</gs-board>