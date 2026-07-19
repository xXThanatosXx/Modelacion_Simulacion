# Modelación y Simulación: materiales en español

Repositorio académico organizado para la asignatura virtual **Modelación y
Simulación**. Contiene únicamente las guías en PDF y los notebooks en español
utilizados en los documentos de los módulos I, II y III, además de los ejemplos
de Newton-Raphson y bondad de ajuste desarrollados específicamente en Python.

## Organización

```text
Repositorio_GitHub_Modelacion_Simulacion/
├── modulo-1/
│   ├── notebooks/
│   └── pdf/guia-modulo-1.pdf
├── modulo-2/
│   ├── notebooks/
│   └── pdf/guia-modulo-2.pdf
├── modulo-3/
│   ├── notebooks/
│   └── pdf/guia-modulo-3.pdf
└── README.md
```

Cada carpeta `pdf` contiene la guía del módulo. La carpeta `notebooks` reúne
los ejercicios ejecutables citados en esa guía. Se recomienda leer primero el
PDF, abrir después el notebook indicado y guardar una copia personal antes de
modificar el código.

## Módulo 1: optimización y métodos de solución

Guía: [`modulo-1/pdf/guia-modulo-1.pdf`](modulo-1/pdf/guia-modulo-1.pdf)

| Notebook | Propósito formativo |
|---|---|
| [`01-production-planning_es.ipynb`](modulo-1/notebooks/01-production-planning_es.ipynb) | Formular variables, restricciones y función objetivo en un problema de planeación de producción. |
| [`06-facility-location_es.ipynb`](modulo-1/notebooks/06-facility-location_es.ipynb) | Decidir qué instalaciones abrir considerando costos fijos y de transporte. |
| [`08-traveling-salesman-problem_es.ipynb`](modulo-1/notebooks/08-traveling-salesman-problem_es.ipynb) | Analizar un modelo de rutas y el crecimiento del esfuerzo computacional. |
| [`06-cutting-stock_es.ipynb`](modulo-1/notebooks/06-cutting-stock_es.ipynb) | Optimizar patrones de corte para reducir desperdicio de material. |
| [`09_newton_raphson_python.ipynb`](modulo-1/notebooks/09_newton_raphson_python.ipynb) | Resolver una ecuación no lineal, observar el error y estudiar la convergencia de Newton-Raphson. |

El último notebook fue elaborado para el curso a partir de un ejercicio en
MATLAB/Octave y convertido a una versión didáctica en Python.

## Módulo 2: simulación de eventos discretos

Guía: [`modulo-2/pdf/guia-modulo-2.pdf`](modulo-2/pdf/guia-modulo-2.pdf)

| Notebook | Propósito formativo |
|---|---|
| [`01_sampling_es.ipynb`](modulo-2/notebooks/01_sampling_es.ipynb) | Generar muestras y reconocer distribuciones empleadas como entradas de una simulación. |
| [`02_basic_simpy_es.ipynb`](modulo-2/notebooks/02_basic_simpy_es.ipynb) | Introducir entorno, procesos, eventos, tiempos de espera y recursos en SimPy. |
| [`04_111_model_es.ipynb`](modulo-2/notebooks/04_111_model_es.ipynb) | Construir un modelo de cola con una etapa y un recurso. |
| [`05_basic_results_es.ipynb`](modulo-2/notebooks/05_basic_results_es.ipynb) | Calcular tiempos de espera, utilización, atención y otras medidas de desempeño. |
| [`07_experiments_es.ipynb`](modulo-2/notebooks/07_experiments_es.ipynb) | Comparar escenarios mediante réplicas y experimentación computacional. |
| [`08_full_model_es.ipynb`](modulo-2/notebooks/08_full_model_es.ipynb) | Integrar llegadas, colas, recursos, resultados y experimentos en un modelo completo. |
| [`13_warm_up_es.ipynb`](modulo-2/notebooks/13_warm_up_es.ipynb) | Estudiar el periodo de calentamiento y el sesgo producido por condiciones iniciales. |
| [`16_time_dependent_arrivals_es.ipynb`](modulo-2/notebooks/16_time_dependent_arrivals_es.ipynb) | Representar demanda variable y llegadas dependientes del tiempo. |
| [`12_prueba_bondad_ajuste_chi_cuadrado.ipynb`](modulo-2/notebooks/12_prueba_bondad_ajuste_chi_cuadrado.ipynb) | Aplicar una prueba chi-cuadrado, calcular el valor p y validar una distribución categórica. |

El notebook de bondad de ajuste fue elaborado para el curso como alternativa
en Python al procedimiento originalmente presentado en SPSS.

## Módulo 3: simulación continua

Guía: [`modulo-3/pdf/guia-modulo-3.pdf`](modulo-3/pdf/guia-modulo-3.pdf)

| Notebook | Propósito formativo |
|---|---|
| [`01_sampling_es.ipynb`](modulo-3/notebooks/01_sampling_es.ipynb) | Servir como puente entre distribuciones continuas, parámetros y entradas del modelo. |
| [`chap07_es.ipynb`](modulo-3/notebooks/chap07_es.ipynb) | Comparar modelos de crecimiento y estudiar límites y equilibrio. |
| [`chap11_es.ipynb`](modulo-3/notebooks/chap11_es.ipynb) | Modelar un sistema epidemiológico mediante estados, flujos y escenarios. |
| [`chap15_es.ipynb`](modulo-3/notebooks/chap15_es.ipynb) | Formular y simular el enfriamiento del café como sistema térmico. |
| [`chap18_es.ipynb`](modulo-3/notebooks/chap18_es.ipynb) | Analizar un sistema dinámico acoplado de glucosa e insulina. |
| [`chap20_es.ipynb`](modulo-3/notebooks/chap20_es.ipynb) | Convertir una ecuación de segundo orden en un sistema de primer orden. |
| [`bungee1_es.ipynb`](modulo-3/notebooks/bungee1_es.ipynb) | Aplicar integración numérica al movimiento de una persona en salto bungee. |
| [`orbit_es.ipynb`](modulo-3/notebooks/orbit_es.ipynb) | Explorar movimiento orbital y sistemas acoplados de segundo orden. |

El notebook de muestreo aparece también en el Módulo II. Se conserva una copia
en el Módulo III porque la guía lo utiliza como puente entre las distribuciones
de probabilidad y los modelos dinámicos continuos.

## Forma de uso

1. Descargue o clone este repositorio.
2. Lea la guía PDF del módulo correspondiente.
3. Abra el notebook indicado en Jupyter Notebook, JupyterLab o Google Colab.
4. Ejecute las celdas en orden y registre los resultados del caso base.
5. Modifique los parámetros propuestos en la guía.
6. Entregue el notebook con resultados, gráficas e interpretación propia.

Algunos notebooks provenientes de los repositorios originales pueden instalar
dependencias desde sus propias celdas o requerir acceso a internet. Los temas
principales utilizan Python, NumPy, pandas, Matplotlib, Pyomo o SimPy, según el
módulo.

## Fuentes y atribución

Los notebooks adaptados al español conservan la autoría y estructura de sus
proyectos de origen:

- **MO-book — Hands-On Mathematical Optimization with Python**  
  <https://github.com/mobook/MO-book>  
  Copyright © 2022 Jeffrey Kantor. Licencia MIT.
- **intro-open-sim**  
  <https://github.com/pythonhealthdatascience/intro-open-sim>  
  Copyright © 2024 Tom Monks. Licencia MIT.
- **ModSimPy**  
  <https://github.com/AllenDowney/ModSimPy>  
  Copyright © 2016 Allen Downey. Licencia MIT.

Las traducciones al español se ofrecen con fines educativos. Al reutilizar o
redistribuir el material deben conservarse los avisos de autoría y las
condiciones de las licencias de los repositorios originales.

## Alcance

Este repositorio es una selección deliberadamente compacta: no contiene los
repositorios completos, versiones en inglés, archivos de trabajo de los Word ni
resultados de control de calidad. Solo incluye las guías PDF y los notebooks en
español utilizados en el curso.
