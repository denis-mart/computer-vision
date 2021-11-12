# Kaggle Competition:

## Pet Finder Pawpularity Score

Related field: Computer Vision

Task: Regression

Inputs: Image and Extra dummy features

Target: Pawpularity Score

# Cosas pendientes:
- TTA?
- BS algo más grande or gradient accum?
- LR cosine?
- Efficient mayor (la b1 acepta resolucion de 240x240 como dice la web de Keras?)
- Mixed Precision (apex) (ya integrado de forma nativa en Pytorch)
- Necesarias tantas transformaciones?


las transformaciones generan un cuello de botella
le he puesto las de validacion y la net freezed y va a tope
Hay que probar una solución intermedia a ver que pasa

y el numworkes y pinmemory hay que ver si vale la pena que pinta mucho verbose caca


