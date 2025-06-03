# Documentos-automaticos

Este repositorio contiene ejemplos simples para automatizar la creación de documentos.

## Script de ejemplo

- **guardar_chat.py**: carga una plantilla de Word, procesa un texto de chat separando los mensajes de "Usuario:" y "ChatGPT:" e inserta el nombre del hablante en negrita antes de cada mensaje. Finalmente guarda el documento.

Para ejecutar el script asegúrate de tener instalada la librería `python-docx` y de contar con una plantilla llamada `plantilla_base.docx` en el mismo directorio.

El texto de la conversación debe almacenarse en una variable llamada `texto_chat`, tal como se muestra en el ejemplo incluido en el script.

```bash
python3 guardar_chat.py
```
