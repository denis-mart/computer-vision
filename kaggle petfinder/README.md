# Kaggle Competition:

## Pet Finder Pawpularity Score

Related field: Computer Vision

Task: Regression

Inputs: Image and Extra dummy features

Target: Pawpularity Score

# Cosas pendientes:
- plt.imread(img_path) no pasa a tensor, lo hace el transform. Es una buena práctica?
- num_workers & pin_memory: usar estas cosas
- Más data augmentation
- TTA?
- BS algo más grande or gradient accum?
- LR cosine?
- Efficient mayor
- Mixed Precision (apex) (ya integrado de forma nativa en Pytorch)
