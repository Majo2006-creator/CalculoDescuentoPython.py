# Definición de la función
def calcular_descuento(monto_total, porcentaje_descuento=10):
    """
    Calcula el valor del descuento de una compra.
    
    Parámetros:
        monto_total (float): Valor total de la compra
        porcentaje_descuento (float): Porcentaje de descuento (por defecto 10%)
    
    Retorna:
        float: Valor del descuento calculado
    """
    descuento = monto_total * (porcentaje_descuento / 100)
    return descuento


# Programa principal
# Primera llamada (solo monto total, se usa el descuento por defecto 10%)
monto1 = 200
descuento1 = calcular_descuento(monto1)
print(f"El descuento para una compra de ${monto1} con 10% es: ${descuento1}")

# Segunda llamada (monto total y porcentaje personalizado)
monto2 = 500
descuento2 = calcular_descuento(monto2, 20)
print(f"El descuento para una compra de ${monto2} con 20% es: ${descuento2}")
