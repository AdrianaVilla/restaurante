# 🍽️ Mi Restaurante - Sistema de Facturación

Aplicación de escritorio desarrollada en **Python** con **Tkinter** que simula un sistema básico de facturación para un restaurante.
Permite seleccionar comidas, bebidas y postres, calcular subtotales, impuestos y total, además de generar y guardar recibos. También incluye una calculadora integrada.

---

## ✨ Características

* ✅ Interfaz gráfica amigable con **Tkinter**.
* ✅ Menú con **Comidas, Bebidas y Postres** (con precios predefinidos).
* ✅ Cálculo automático de subtotales, impuestos (7 %) y total.
* ✅ Generación de recibos con número único y fecha/hora.
* ✅ Opción para **guardar el recibo en un archivo `.txt`**.
* ✅ **Calculadora integrada** para operaciones rápidas.
* ✅ Botones de control: **Total, Recibo, Guardar, Resetear**.

---

## ⚙️ Requisitos

* **Python 3.8+**
* Librerías estándar de Python:

  * `tkinter`
  * `datetime`
  * `random`

(No requiere instalación adicional si ya tienes Python).

---

## ▶️ Cómo ejecutar

1. Clona este repositorio:

   ```bash
   git clone https://github.com/AdrianaVilla/restaurante.git
   cd restaurante/Dia\ 12
   ```
2. Ejecuta la aplicación:

   ```bash
   python mi_restaurante.py
   ```

---

## 🖥️ Uso

1. Selecciona las comidas, bebidas y postres marcando las casillas.
2. Introduce la cantidad deseada en los campos habilitados.
3. Pulsa **Total** para calcular la factura.
4. Pulsa **Recibo** para ver el detalle en pantalla.
5. Pulsa **Guardar** para exportar el recibo en `.txt`.
6. Pulsa **Resetear** para limpiar todos los campos.

### Controles de la calculadora

* Números y operaciones básicas (`+`, `-`, `*`, `/`).
* `R` → Mostrar resultado.
* `B` → Borrar entrada.

---

## 📂 Estructura del proyecto

```
restaurante/
└─ Dia 12/
   ├─ mi_restaurante.py   # Código principal de la aplicación
```

---

## 📸 Capturas (opcional)

Puedes añadir imágenes de la interfaz aquí:

```markdown
![Interfaz principal](docs/interfaz.png)
```

---

## 📝 Licencia

Proyecto de práctica para aprender **Tkinter** y **Python GUI**.
Libre para uso personal, educativo y modificaciones.
