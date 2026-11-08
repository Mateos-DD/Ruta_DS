# Ruta DS

Mi ruta de formación en ciencia de datos, redes neuronales e inteligencia artificial.
Cada carpeta corresponde a una fase del plan; todo el código lo escribo yo y lo reviso con Claude.

| Carpeta | Contenido |
| --- | --- |
| `02-redes-desde-cero/` | **Empiezo aquí.** Neural Networks: Zero to Hero (Karpathy) y *Understanding Deep Learning* (Prince) |
| `01-ml-clasico/` | Repaso en paralelo: ISLP, Murphy y Deisenroth |
| `03-deep-learning/` | Redes convolucionales, atención, transformers, VAE y difusión (d2l.ai, Bishop y Bishop) |
| `04-llms/` | Stanford CS336, curso de LLMs de Hugging Face, RAG y agentes con la API de Claude |
| `00-matematicas/` | Derivaciones a mano y repasos puntuales |
| `proyectos/` | Un proyecto de portafolio por fase |
| `datos/` | Datos locales (no se suben a GitHub) |

El avance semanal está en [`bitacora.md`](bitacora.md).

## Entorno

```bash
cd ~/Ruta_DS
uv venv .venv --python 3.11
source .venv/bin/activate
uv pip install -r requirements.txt
jupyter lab
```
