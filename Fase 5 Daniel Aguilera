# Fase-5-Daniel-Aguilera-
Fase-5-Daniel-Aguilera-
# Matriz del menú
menu = [
    ["Hamburguesa", "Comida Rápida", 12000],
    ["Pizza", "Comida Rápida", 18000],
    ["Ensalada", "Saludable", 10000],
    ["Sopa", "Tradicional", 8000],
    ["Postre", "Dulce", 15000],
    ["Jugo Natural", "Bebida", 7000]
]

# Categoría objetivo y umbral
categoria_objetivo = "Comida Rápida"
umbral_precio = 15000

# Función para calcular precio final de un producto
def calcular_precio_final(producto, categoria_objetivo, umbral):
    nombre, categoria, precio_base = producto
    if categoria == categoria_objetivo and precio_base > umbral:
        precio_final = precio_base * 0.85
    else:
        precio_final = precio_base
    return nombre, categoria, precio_base, precio_final

# Mostrar menú al usuario
print(" Menú disponible:\n")
for i, producto in enumerate(menu):
    print(f"{i+1}. {producto[0]} - Categoría: {producto[1]} - Precio Base: ${producto[2]}")

# Selección del producto
opcion = int(input("\n Ingresa el número del producto que deseas consultar: "))

# Validar selección
if 1 <= opcion <= len(menu):
    producto_seleccionado = menu[opcion-1]
    nombre, categoria, precio_base, precio_final = calcular_precio_final(producto_seleccionado, categoria_objetivo, umbral_precio)
    print("\n Resultado de la Promoción:")
    print(f"Producto: {nombre} | Categoría: {categoria} | Precio Base: ${precio_base} | Precio Final: ${precio_final}")
else:
  
