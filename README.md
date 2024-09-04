# Filtro de Píxeles por Color RGB

Este proyecto aplica un filtro a una imagen basada en un color RGB específico. El script permite al usuario introducir valores de los componentes rojo, verde y azul para filtrar la imagen y generar una nueva imagen donde sólo se mantienen los píxeles que coinciden con el color especificado.

## Características

- **Selección de Color:** El usuario puede especificar un color RGB mediante la introducción de valores para rojo, verde y azul.
- **Filtrado de Imagen:** El script procesa una imagen y mantiene solo los píxeles que coinciden con el color seleccionado.
- **Salida de Imagen:** Se genera una nueva imagen con los píxeles filtrados y se guarda en el directorio de trabajo.

## Requisitos

Para ejecutar este script, asegúrate de tener la siguiente biblioteca de Python instalada:

- `Pillow` (Biblioteca para la manipulación de imágenes en Python)

Puedes instalar `Pillow` utilizando pip:

```bash
pip install Pillow
```

## Uso

1. **Preparar la Imagen:** Coloca la imagen que deseas filtrar en el mismo directorio que el script.
2. **Ejecutar el Script:** Ejecuta el script e introduce los valores de rojo, verde y azul cuando se te solicite.
3. **Generar la Imagen Filtrada:** El script generará y guardará una nueva imagen con los píxeles que coinciden con el color RGB seleccionado.

```bash
python filtro_de_píxeles_por_color_rgb.py
```

## Ejemplo

Si introduces los siguientes valores cuando se te solicite:

- Rojo: 255
- Verde: 0
- Azul: 0

El script filtrará la imagen para mostrar solo los píxeles que son completamente rojos.
