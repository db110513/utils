# utils


### _mostrarSnackBar
```
void _mostrarSnackBar(String missatge) {
    ScaffoldMessenger.of(context).showSnackBar(
      SnackBar(content: Text(missatge)),
    );
}
```

### ex:
```
_mostrarSnackBar('Ciutat no trobada o error al servidor');
```
