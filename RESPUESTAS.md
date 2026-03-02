# 📝 Entrega: Análisis de la IA Local

**1. ¿Qué modelo has usado finalmente?**
Para esta práctica he utilizado el modelo `tinyllama`. Es un modelo de lenguaje pequeño (Small Language Model o SLM) ideal para pruebas locales y entornos con recursos limitados.

**2. ¿Cuánto ocupa en disco aproximadamente ese modelo?**
Según la librería oficial de Ollama, el modelo `tinyllama` base ocupa aproximadamente **637 MB** en disco. Esto es extremadamente ligero en comparación con modelos más grandes como Llama 3 (que supera los 4.7 GB).

**3. ¿Crees que esta IA responde más rápido o más lento que ChatGPT? ¿Por qué crees que es?**
En general, responde de forma diferente (a menudo más lento en la generación de tokens por segundo si no se dispone de una buena tarjeta gráfica local). 
**¿Por qué?** Porque ChatGPT se ejecuta en clústeres masivos de servidores de OpenAI equipados con miles de GPUs de última generación (como las NVIDIA H100) diseñadas específicamente para inferencia de IA. Nuestra IA local está utilizando los recursos limitados (CPU y memoria RAM) de mi ordenador personal.