# WPC Asiste — Proyecto Final
Mauro Fetingis · Inteligencia Artificial: Generación de Prompts · Comisión 96165
## Descripción

WPC Asiste es una prueba de concepto de un asistente comercial para una empresa de revestimientos, decks y pérgolas de WPC. Aplica técnicas de prompting para preparar respuestas iniciales, solicitar información para presupuestar, visualizar proyectos y elaborar contenido comercial.

## Acceso al proyecto
- [Ver notebook con resultados](WPC_Asiste_Proyecto_Final.ipynb)
- [Abrir notebook en Google Colab](https://colab.research.google.com/github/MauroFetingis/Entrega-Final-IA-Fetingis/blob/main/WPC_Asiste_Proyecto_Final.ipynb)

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

## Estado y limitaciones
La demostración puede ejecutarse sin credenciales recuperando tres respuestas reales de Gemini y mostrando tres ejemplos simulados identificados como tales.

La validación mediante API es parcial: quedan pendientes las respuestas reales de Dirigido, Iterativo y Redes. Los resultados obtenidos corresponden a un único caso de prueba y no permiten generalizar el desempeño de las técnicas.

Los presupuestos y las decisiones técnicas requieren validación humana. Las imágenes son conceptuales y los cálculos de ahorro utilizan datos simulados.
