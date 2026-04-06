# Asistente de Inventario 📦

**Este es el primer proyecto práctico de `soberania-para-todos`.**  
Un script en Python que te ayuda a **llevar el control de tu inventario** (cortineros, toallas, cortinas, etc.) directamente desde un archivo Excel, y te avisa cuándo es momento de reponer.

El objetivo es que **no dependas de software caro ni de servicios en la nube**. Todo corre en tu computadora, con tus datos, y tú controlas el código.

---

## 🧠 ¿Qué hace este asistente?

- Lee tu archivo Excel (el mismo que usas para tu inventario).
- Calcula el **stock total, exhibición y bodega** de cada producto.
- Te muestra en pantalla:
  - Productos con **bajo stock** (por ejemplo, menos de 3 unidades en exhibición).
  - Productos que necesitan **reposición desde bodega**.
  - Resumen general del inventario.
- (Próximamente) Puede enviarte alertas por Telegram o guardar un reporte.

---

## 📂 ¿Qué necesitas?

- Una computadora con **Windows, Linux o Mac**.
- **Python 3.7 o superior** instalado.
- Tu archivo de inventario en formato **Excel** (`.xlsx`), con columnas como:
  - `Código`, `Producto`, `Stock total`, `En exhibición`, `En bodega`, `Capacidad exhibidor`, etc.

> *Si tu Excel tiene otra estructura, podemos adaptar el script fácilmente.*

---

## 🚀 Cómo usar el script (primeros pasos)

1. **Descarga o clona este repositorio** en tu computadora.
2. **Abre una terminal** en la carpeta `herramientas/inventario/`.
3. **Instala las librerías necesarias** (solo una vez):
   ```bash
   pip install pandas openpyxl
