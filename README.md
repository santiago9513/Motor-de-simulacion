# Motor-de-simulacion

Identificación y simulación de sistemas dinámicos discretos a partir de series temporales

### Descripcion:
Este proyecto implementa un sistema para aprender modelos dinámicos discretos
a partir de datos observados, sin conocer la ecuación real del sistema.
A partir de una serie temporal, el sistema estima un modelo matemático explicable
y lo utiliza para simular y predecir la evolución futura del sistema.

### Motivacion:
La motivación del proyecto es explorar el proceso de identificación de sistemas
basado en datos, un enfoque ampliamente utilizado en ingeniería, industria y software,
como alternativa a modelos de "caja negra".
El objetivo no es construir una IA general, sino comprender y desarrollar modelos
dinámicos interpretables que permitan análisis, simulación y predicción.

### Alcance actual (fase 1)
- Sistemas dinámicos discretos de una variable
- Aprendizaje desde series temporales
- Modelo autorregresivo lineal AR(1)
- Estimación de parámetros por mínimos cuadrados
- Simulación y predicción multi-paso
- Evaluación mediante error cuadrático medio (MSE)
