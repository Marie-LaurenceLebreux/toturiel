# Sonde de temperature

## Étape 1 

```blocks
basic.forever(function () {
    serial.writeValue(t)
    basic.pause(5000)
})
```