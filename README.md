# WPC Asiste — Proyecto Final
Mauro Fetingis · Inteligencia Artificial: Generación de Prompts · Comisión 96165

## Alcance y evidencia
La integración con Gemini desde Python produjo tres respuestas reales: Zero-shot, One-shot y Few-shot. El bloqueo de cuota impidió terminar Dirigido, Iterativo y Redes. Estas tres etapas se presentan como **simulaciones didácticas elaboradas con ChatGPT**, rotuladas y excluidas del análisis empírico de Gemini.

## Archivos
- `WPC_Asiste_Proyecto_Final.ipynb`: notebook con código, resultados, imagen, análisis y conclusiones.
- `resultados_entrega/`: evidencias con procedencia, indicadores y evaluación cualitativa.
- `imagenes/visualizacion_wpc.png`: imagen conceptual del proyecto (herramientas utilizadas: NightCafe y ChatGPT).
- `requirements.txt`: dependencias para ejecución local.

## Reproducir
Abrir el notebook en Colab y ejecutar todas las celdas. Por defecto funciona sin clave: `EJECUTAR_API = False` recupera tres respuestas reales y muestra tres simulaciones identificadas. La simulación no acredita una ejecución completa de Gemini.

Para completar la prueba real, configurar `GEMINI_API_KEY` en Secrets y cambiar `EJECUTAR_API = True`. En ese modo no se usan simulaciones; se recuperan los aciertos y se consultan sólo los faltantes, sujeto a cuota. No subir la clave.

## Evaluación
Comparación cualitativa asistida por ChatGPT sobre tres salidas auténticas; no se atribuye a un evaluador humano ni se inventan calificaciones. El autor debe revisar el análisis. La muestra es exploratoria y no permite generalizar resultados.

## Entrega en GitHub
Subir el contenido descomprimido del paquete al repositorio público y entregar su enlace. El notebook debe verse directamente: no subir únicamente el ZIP. Esta versión documenta una validación parcial y no garantiza cumplir el requisito de ejecución integral del docente.
