# Informe: Recomendación de Tienda para el Sr. Juan

## 1. Introducción
**Objetivo**: Determinar en cuál de las cuatro tiendas (Tienda 1, Tienda 2, Tienda 3 y Tienda 4) debe vender el Sr. Juan, usando los análisis realizados: ingresos, categorías, productos, calificaciones y coste de envío.

El informe sintetiza los hallazgos clave y entrega una **recomendación accionable**.

## 2. Resultados del análisis

### Ingresos Totales por Tienda
Tras sumar la columna *Precio* de cada dataset, el orden aproximado de ingresos es:

1. **Tienda 1** — Mayor nivel de ingresos  
2. **Tienda 2** — Segundo mejor desempeño  
3. **Tienda 3** — Ingresos moderados  
4. **Tienda 4** — Menor volumen de ingresos  

**Conclusión**: Tienda 1 destaca claramente por volumen de ventas.

### Categorías de Productos
- Se agruparon las ventas por categoría.  
- **Tienda 1 y Tienda 2** concentran las categorías con mayor rotación.

**Conclusión**: Tienda 1 y Tienda 2 tienen fuerte afinidad de catálogo con productos populares.

### Productos Más y Menos Vendidos
- Se identificaron los productos con mayor y menor número de ventas por tienda.  
- **Tienda 1 y Tienda 2** muestran productos líderes en volumen.  
- **Tienda 4** tiene menor consistencia por producto.

**Conclusión**: Las Tiendas 1 y 2 cuentan con ítems estrella que impulsan significativamente las ventas.

### Calificaciones Promedio (Ratings)
- No se detectaron columnas de calificación en los datasets cargados.  
- No fue posible calcular la satisfacción del cliente.

**Conclusión**: Falta información para evaluar la satisfacción del cliente.

### Costo Promedio de Envío
- Se calcularon promedios donde existían columnas de envío.  
- El costo de envío resultó **similar entre todas las tiendas**.  
- El cliente paga el envío (valor cobrado al cliente).

**Conclusión**: El coste de envío **no es un diferenciador** en los datos disponibles.

## 3. Análisis integrado

| Factor                  | Tienda 1              | Tienda 2              | Tienda 3 y 4          |
|-------------------------|-----------------------|-----------------------|-----------------------|
| Volumen y demanda       | Líder                 | Segundo lugar         | Muy por debajo        |
| Satisfacción (ratings)  | No evaluable          | No evaluable          | No evaluable          |
| Costes de envío         | Sin diferencias       | Sin diferencias       | Sin diferencias       |
| Riesgos                 | Falta ratings y márgenes | Igual que Tienda 1 | Mayor riesgo por bajo volumen |

## 4. Recomendación

**Recomendación principal**: **Vender en Tienda 1**

**Motivos principales**:
- Mayor ingreso total (indicador clave de demanda y volumen).
- Presencia de categorías y productos con alta rotación.
- Sin evidencia de desventajas en envío o ratings (estas últimas no disponibles).

**Condiciones importantes**:
- Confirmar ratings y calcular márgenes netos (precio − coste − envío) antes de la decisión final definitiva.
- Si los ratings o márgenes resultaran desfavorables en Tienda 1, considerar **Tienda 2** como alternativa inmediata.

## 5. Limitaciones y próximos pasos
- Localizar/extraer columnas de rating (si existen) para medir satisfacción.
- Calcular márgenes reales por producto (precio − coste − envío).
- Realizar análisis temporal (ventas por mes/año).
- Validar limpieza de nombres de productos (detectar duplicados o inconsistencias).
- Revisar manualmente los archivos de productos top/bottom para confirmar los hallazgos actuales.

**Decisión recomendada con los datos actuales**: Iniciar ventas en **Tienda 1**, complementando rápidamente con los análisis pendientes de ratings y márgenes.
