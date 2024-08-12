# Comparación de tiempos entre CPU y GPU
16/7/2024

## Test ejecutado:
https://www.tensorflow.org/tutorials/quickstart/advanced?hl=Es-419

## Tiempo GPU (NVIDIA GeForce RTX 2060)
python hello.py  31,05s user 4,56s system 135% cpu 26,329 total 

## Tiempo CPU (AMD Ryzen 7 3700X, 8 núcleos en paralelo)
CUDA_VISIBLE_DEVICES="" python hello.py  1898,37s user 64,07s system 1147% cpu 2:51,00 total