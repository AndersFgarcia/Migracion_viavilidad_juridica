# Migración Base de Datos Viabilidad Jurídica

Proyecto para la migración y limpieza de datos de viabilidad jurídica.

## Estructura del Proyecto

- `migracion_viablidad_juridica.ipynb`: Notebook principal con el proceso de migración
- Archivos Excel: Datos originales y procesados para revisión
- `Entorno_migracion/`: Entorno virtual de Python (excluido del repositorio)

## Instalación

1. Crear un entorno virtual:
```bash
python -m venv Entorno_migracion
```

2. Activar el entorno virtual:
```bash
# Windows
Entorno_migracion\Scripts\activate

# Linux/Mac
source Entorno_migracion/bin/activate
```

3. Instalar dependencias:
```bash
pip install pandas numpy openpyxl
```

## Uso

Ejecutar el notebook `migracion_viablidad_juridica.ipynb` para procesar los datos.

