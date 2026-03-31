# Ticket

Programa sencillo en **Java** que permite capturar productos (descripción, cantidad y precio unitario) y genera un **ticket** con el listado y el **total a pagar** en consola.

---

## Lenguajes utilizados

- **Java** (principal)

---

## ¿Qué hace el programa?

1. Pide al usuario por consola:
   - **Producto** (texto)
   - **Cantidad** (entero)
   - **Precio unitario** (decimal)
2. Repite el registro de productos hasta que el usuario indique finalizar con **"S"**.
3. Calcula el **total** (cantidad × precio) sumando todos los productos.
4. Imprime un ticket en consola con:
   - Encabezado "TIENDITA"
   - Tabla con **descripción**, **cantidad** y **precio**
   - **TOTAL** final

---

## Requisitos

- Tener instalado **Java (JDK)**.
- Consola/terminal para ejecutar el programa.

---

## Cómo ejecutar

### Opción 1: Compilar y ejecutar con `javac` / `java`

1. Abre una terminal en la carpeta del proyecto.
2. Compila:

   ```bash
   javac Ticket.java
   ```

3. Ejecuta:

   ```bash
   java Ticket
   ```
---

## Uso (ejemplo rápido)

El programa te pedirá algo como:

- `Producto:`
- `Cantidad:`
- `Precio:`
- `Desea finalizar? (S/N)`

Cuando respondas **S**, imprimirá el ticket con el total.

---

## Estructura del repositorio

- `Ticket.java` → Código fuente del programa.
- `evidencia.png` → Evidencia/captura de ejecución.
- `README.md` → Documentación.

---

## Imágenes

### Evidencia de ejecución

![Evidencia](evidencia.png)

---

## Autor

- **Itzel921**
