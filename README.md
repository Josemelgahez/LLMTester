# LLMTester

Código base para la extracción de palabras clave de una intención mediante modelos LLM de HuggingFace.
Integración con MLFLOW para facilitar la gestión y comparación de resultados. 

Algunos modelos requieren autenticación en HuggingFace, por lo que debes reemplazar el token en la primera celda por el tuyo propio.
  - En algunos casos deberás solicitar acceso a los distribuidores del modelo para poder usarlo.

Si se emplea cuantización, es importante desactivar el uso de pipeline, ya que de lo contrario se produce un error.
