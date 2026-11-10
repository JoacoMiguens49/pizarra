# Pizarra

Una pizarra blanca simple para Windows, pensada para hacer sketches de la facultad (matemática, diagramas, etc.).
Es un único archivo HTML, sin dependencias ni instalación.

## Cómo abrirla

Abrí `pizarra.html` con cualquier navegador, o como ventana propia (sin pestañas ni barra de direcciones) con Edge:

```
"C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe" --app="file:///RUTA/A/pizarra.html"
```

Podés crear un acceso directo en el Escritorio con ese comando como destino.

## Qué tiene

- Lienzo infinito con cuadrícula opcional
- Pincel, borrador por pedacitos, línea, flecha, rectángulo, elipse y texto
- Selección para mover, escalar, copiar/pegar y duplicar
- Pegar imágenes desde el portapapeles (capturas de enunciados, etc.)
- Deshacer / rehacer
- Autoguardado local y archivos `.pizarra` para guardar y abrir
- Exportar a PNG o copiar como imagen

## Controles

| Acción | Atajo |
| --- | --- |
| Dibujar / usar herramienta | Clic izquierdo |
| Moverse por la pizarra | Clic derecho arrastrando |
| Zoom | Rueda |
| Grosor del pincel / borrador | `Alt` + rueda, o `[` `]` |
| Seleccionar · Pincel · Borrador | `V` · `P`/`B` · `E` |
| Línea · Flecha · Rectángulo · Elipse · Texto | `L` · `A` · `R` · `O` · `T` |
| Cuadrado / círculo / 45° | `Shift` mientras dibujás la forma |
| Borrar trazos enteros | `Shift` + borrador |
| Colores | `1` … `7` |
| Cuadrícula · Encuadrar todo | `G` · `F` |
| Borrar selección | `Supr` |
| Deshacer / Rehacer | `Ctrl+Z` / `Ctrl+Y` |
| Copiar · Pegar · Duplicar | `Ctrl+C` · `Ctrl+V` · `Ctrl+D` |
| Seleccionar todo | `Ctrl+A` |
| Guardar / Abrir | `Ctrl+S` / `Ctrl+O` |
| Exportar PNG / Copiar como imagen | `Ctrl+Shift+S` / `Ctrl+Shift+C` |
| Editar texto | Doble clic |
| Terminar de escribir | `Esc` o `Ctrl+Enter` |

Los atajos de una letra no se activan mientras estás escribiendo un texto.
