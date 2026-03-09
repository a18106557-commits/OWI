[README (1).md](https://github.com/user-attachments/files/25830955/README.1.md)
# OWI 🦉

OWI es un lenguaje de programación creado desde cero, con una sintaxis moderna inspirada en Rust y Python, enfocado en simplicidad, desarrollo web y automatización.

---

## ✨ Características

- Variables con `let` y `let mut`
- Funciones con `using_function`
- Pattern matching con `match / with`
- Listas y tipos
- Servidor web integrado con `server.route`
- Terminador de línea `::` estilo propio

---

## 📖 Sintaxis

### Variables
```
let nombre = "OWI" ::
let mut contador = 0 ::
text saludo = "Hola" ::
num edad = 20 ::
```

### Condicionales
```
check (edad > 18) {
    mode.print("Mayor de edad") ::
} else {
    mode.print("Menor de edad") ::
}
```

### Funciones
```
using_function sumar(a, b) {
    return a + b ::
}

num resultado = using_sumar(10, 5) ::
mode.print(resultado) ::
```

### Bucles
```
for i = 1 to 5 {
    mode.print(i) ::
}

while (contador < 10) {
    contador = contador + 1 ::
}
```

### Pattern Matching
```
let dia = 2 ::

match dia {
    with 1 => { mode.print("Lunes") :: }
    with 2 => { mode.print("Martes") :: }
    with _ => { mode.print("Otro dia") :: }
}
```

### Listas
```
list colores = ["rojo", "verde", "azul"] ::
mode.print(colores) ::
```

### Servidor Web
```
server.route("/") {
    server.html("<h1>Hola desde OWI!</h1>") ::
}

server.start(8080) ::
```

---

## 🚀 Cómo correr OWI

1. Tener Python instalado
2. Clonar este repositorio
3. Correr cualquier archivo `.owi`:

```bash
python main.py mi_programa.owi
```

---

## 📁 Estructura

| Archivo | Descripción |
|---|---|
| `lexer.py` | Tokenizador del lenguaje |
| `parser.py` | Analizador sintáctico |
| `interprete.py` | Intérprete y ejecutor |
| `main.py` | Punto de entrada |

---

## 👨‍💻 Creado por

**a18106557-commits** — construido desde cero con pasión. 🚀

