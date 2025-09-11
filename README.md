# Comparador de Patogenicidad de Familias de Virus

Aplicación web en **HTML + CSS + JavaScript** que permite comparar la prioridad de patogenicidad de una familia de virus respecto a las demás, basándose en una clasificación de niveles: **Alta > Media > Baja > Sin riesgo > No priorizada**.

## Funcionalidad

El usuario introduce el nombre de una familia de virus (por ejemplo `orthomyxoviridae`) y pulsa **Ejecutar**.  
La página genera tres tablas:

| Tabla | Contenido |
|-------|----------|
| **Más patógena que…** | Familias con prioridad inferior a la introducida |
| **Tan patógena como…** | Familias con la misma prioridad (excluida la propia) |
| **Menos patógena que…** | Familias con prioridad superior |

Cada fila de las tablas muestra el nombre de la familia y su nivel de prioridad.
