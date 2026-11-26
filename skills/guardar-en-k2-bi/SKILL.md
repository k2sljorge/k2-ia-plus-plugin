---
name: guardar-en-k2-bi
description: Guardar un informe o panel en K2 BI cuando el usuario lo pida («guárdalo en K2 BI», «publícalo en K2 BI»).
---

# Guardar en K2 BI

Siempre en dos pasos:

1. `preparar_guardado_bi`: no guarda nada; devuelve el plan y una huella.
2. Enseña el plan al usuario y pregúntale si lo guarda.
3. Solo si dice que sí, `guardar_en_k2_bi` con lo mismo y la huella.
