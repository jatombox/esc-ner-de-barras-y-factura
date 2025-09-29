# Sistema POS con Escaneo de Códigos de Barras y Facturación

## Descripción General
Este proyecto es un **Sistema Point of Sale (POS)** completo desarrollado en **Python** utilizando **Tkinter**.  
Permite gestionar ventas, productos y clientes con funcionalidades avanzadas, incluyendo:

- **Escaneo de códigos de barras**: Integración con lectores para agilizar el proceso de venta.  
- **Impresión de facturas**: Soporte para impresoras POS para generar recibos físicos.  
- **Gestión de productos**: CRUD completo (Crear, Leer, Actualizar, Eliminar) para manejar inventario.  
- **Historial de ventas**: Registro y consulta de todas las transacciones realizadas.  
- **Interfaz amigable**: Diseño intuitivo y colorido con paneles organizados.  

El sistema utiliza **SQLite** para almacenamiento local de datos, lo que permite operar sin conexión a internet y garantiza la integridad de los datos.

---

## Características Principales
1. **Interfaz Multicolor**: Diseño moderno y atractivo con colores vibrantes.  
2. **Gestión de Inventario**: CRUD completo para productos con búsqueda avanzada.  
3. **Proceso de Venta**: Agilizado mediante escaneo de códigos de barras.  
4. **Impresión de Facturas**: Soporte para impresoras POS con formato profesional.  
5. **Reportes y Exportación**: Posibilidad de exportar datos a formato JSON.  
6. **Historial de Ventas**: Consulta y visualización de transacciones anteriores.  

---

## Requisitos del Sistema

**Hardware**  
- Impresora POS compatible.  
- Lector de códigos de barras (opcional, pero recomendado).  

**Software**  
- Python 3.6 o superior.  
- Bibliotecas necesarias: `tkinter`, `sqlite3`, `pillow`, `reportlab`, `pyserial`.  

---

## Instalación

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/jatombox/esc-ner-de-barras-y-factura.git
   cd esc-ner-de-barras-y-factura
Instalar dependencias:

bash
Copiar código
pip install pillow reportlab pyserial

Ejecutar el sistema:

bash
Copiar código
python main.py

# Uso del Sistema
## Interfaz Principal

La aplicación se divide en tres paneles principales:

1. Panel Izquierdo - Productos

- Listado de productos disponibles.

- Búsqueda por nombre o código de barras.

- Botones para CRUD de productos.

2. Panel Central - Venta Actual

- Campo para ingresar códigos de barras.

- Listado de ítems de la venta actual.

- Calculadora de totales.

- Botones para limpiar, guardar y imprimir.

3. Panel Derecho - Historial de Ventas

- Listado de ventas recientes.

- Opciones para ver detalles y exportar datos.

---

## Funcionamiento Básico

1. Agregar Productos

- Haga clic en + Agregar Producto.

- Complete la información del producto.

- Guarde para añadir al inventario.

2. Realizar una Venta

- Escanee o ingrese códigos de barras en el campo correspondiente.

- Los productos se agregarán automáticamente a la venta.

- Revise el total y proceda a guardar o imprimir.

3. Imprimir Factura

- Complete la venta y haga clic en Imprimir Factura.

- La factura se enviará directamente a la impresora POS conectada.

## Contribuidores
Jacobo Morales Londoño

Samuel Torres Atehortua

## Licencia
Este proyecto está bajo la licencia MIT.
Consulte el archivo LICENSE para más detalles.
