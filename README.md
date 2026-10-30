# Computación Cuántica Avanzada — SCAYLE

Material práctico del curso **Advanced Quantum Computing** de SCAYLE. Este repositorio reúne notebooks introductorios de computación cuántica, algoritmos y aplicaciones de *quantum machine learning*, además de los materiales de los bloques 3 y 4.

## Contenido

### Notebooks

Los notebooks están en `notebooks/` y se recomienda seguirlos en este orden:

1. **Bits y cúbits** (`1.Bits_y_Cúbits.ipynb`): conceptos básicos de información clásica y cuántica, estados y representación de cúbits.
2. **Puertas cuánticas** (`2.Puertas_cuánticas.ipynb`): operaciones elementales y circuitos cuánticos.
3. **Algoritmos cuánticos y clásicos** (`3.Algoritmos_cuánticos_clásicos.ipynb`): introducción práctica a algoritmos cuánticos y comparación con enfoques clásicos.
4. **QC y QHED** (`4.QC_QHED.ipynb`): ejercicios de computación cuántica relacionados con QHED.
5. **Clasificación con Qiskit** (`5.Qiskit_Clasificacion.ipynb`): modelos de clasificación cuántica usando Qiskit.
6. **Kernel, clustering y regresión con PennyLane** (`6.PennyLane_Kernel_Clustering_Regresion.ipynb`): métodos de kernel cuántico y aplicaciones a clustering y regresión.

### Material del curso

La carpeta `docs/` contiene las presentaciones y recursos de los bloques avanzados:

- `Bloque3_Quantum_Machine_Learning_SCAYLE.pdf` — Quantum Machine Learning.
- `Bloque4_Computacion_Cuantica_en_la_Practica_SCAYLE.pdf` — computación cuántica en la práctica.

## Requisitos

- Python 3.10 o posterior (se recomienda crear un entorno virtual).
- JupyterLab o Jupyter Notebook.
- Las dependencias de los notebooks, en particular Qiskit y PennyLane.

Las versiones exactas pueden variar según el notebook y el entorno utilizado durante el curso. Si un notebook incluye una celda de instalación, ejecútala en su entorno virtual; de lo contrario, instala los paquetes que indiquen sus imports antes de ejecutarlo.

## Preparar el entorno

Desde la raíz del repositorio, crea y activa un entorno virtual:

```bash
python -m venv .venv
```

En Linux o macOS:

```bash
source .venv/bin/activate
```

En Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Instala Jupyter y las bibliotecas necesarias para los ejercicios:

```bash
python -m pip install --upgrade pip
python -m pip install jupyterlab qiskit pennylane scikit-learn matplotlib numpy
```

Inicia JupyterLab:

```bash
jupyter lab
```

Abre los archivos de `notebooks/` desde la interfaz. Ejecuta cada notebook de arriba abajo. Algunos ejercicios pueden requerir acceso a un simulador o proveedor cuántico configurado; cuando no haya hardware disponible, utiliza el simulador indicado por el propio notebook.

## Estructura

```text
.
├── docs/       # Material de los bloques 3 y 4
├── notebooks/  # Notebooks de prácticas (conceptos, circuitos y QML)
└── README.md
```

## Uso académico

Repositorio de apoyo al aprendizaje y la experimentación con computación cuántica. Consulta las condiciones de uso y atribución de los materiales originales del curso antes de redistribuirlos.
