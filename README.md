# Laboratorio 5
## Asignaciones

La administración del servicio desea ahora que el servidor no esté vacío (sin atender solicitudes) más del 10% del tiempo. Hallar el parámetro $\nu$ para satisfacer este requisito y modificar el código para medir la variable de interés en una simulación.

---

### Solución

Para resolver esta práctica de laboratorio se utilizó el código del L5_base.ipynb proporcionado. A partir de este se realiza lo siguiente
  1) Con la sumatoria para la cantidad de personas en cola, se calcula el caso en el que la probabilidad de solicitudes al servidor sea al menos 1 más del 10% del tiempo
     esto es equivalente a buscar la probabilidad P>0.90
  2) Del punto anterior, se encuentra, al resolver la sumatoria, que P(1)= $$frac\{lambda}{\nu}>0.90$$. Entonces se resuelve para $$\nu$$
