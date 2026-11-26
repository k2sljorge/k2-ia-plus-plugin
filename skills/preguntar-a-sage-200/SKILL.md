---
name: preguntar-a-sage-200
description: Responder preguntas sobre los datos de la empresa en Sage 200 (ventas, clientes, artículos, cobros, documentos) con el conector K2 IA Plus. Úsalo cuando el usuario pregunte por cifras o datos de su empresa.
---

# Preguntar a Sage 200

1. Empieza por `listar_bases` para saber la base de la empresa, y úsala siempre.
2. Antes de escribir una consulta, mira qué hay con `listar_tablas` y `esquema_tabla`. No supongas nombres de tablas ni de campos.
3. Las consultas solo leen. Si el usuario pide cambiar o borrar algo, dile que desde aquí no se puede.
4. Contesta con la cifra y de dónde sale (periodo, filtro). Si la pregunta es de hoy, avisa de que lo más reciente puede no estar todavía.
5. Si una herramienta responde «no lo tienes contratado», díselo al usuario tal cual.
