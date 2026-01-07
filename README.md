# Modelo de Ising en Diferentes Topologías

Este proyecto contiene implementaciones del **Modelo de Ising** en diversas topologías de red, con simulaciones Monte Carlo y análisis de propiedades termodinámicas.

## 📋 Descripción

El Modelo de Ising es un modelo matemático de ferromagnetismo en mecánica estadística. Este repositorio incluye simulaciones en las siguientes topologías:

- **Lineal (1D)**: Cadena unidimensional
- **Cuadrada (2D)**: Red cuadrada bidimensional
- **Cúbica (3D)**: Red cúbica tridimensional
- **Honeycomb (2D)**: Red hexagonal (panal de abeja)

## 🔬 Características

- Simulaciones Monte Carlo con algoritmo de Metrópolis
- Análisis de transiciones de fase
- Cálculo de propiedades termodinámicas (energía, magnetización, calor específico, susceptibilidad)
- Visualizaciones de configuraciones del sistema
- Optimización con Numba para cálculos rápidos

## 📁 Estructura del Proyecto

```
Ising_Model/
├── notebooks/
│   ├── ising_lineal.ipynb      # Simulación en red lineal
│   ├── ising_cuadrada.ipynb    # Simulación en red cuadrada
│   ├── ising_cubica.ipynb      # Simulación en red cúbica
│   └── ising_honeycomb.ipynb   # Simulación en red honeycomb
├── requirements.txt            # Dependencias del proyecto
├── LICENSE                     # Licencia del proyecto
└── README.md                   # Este archivo
```

## 🚀 Instalación

### Prerrequisitos

- Python 3.7 o superior
- pip (gestor de paquetes de Python)

### Pasos de instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/Ising_Model.git
cd Ising_Model
```

2. (Opcional) Crea un entorno virtual:
```bash
python -m venv venv
source venv/bin/activate  # En Linux/Mac
# o
venv\Scripts\activate     # En Windows
```

3. Instala las dependencias:
```bash
pip install -r requirements.txt
```

## 💻 Uso

### Ejecutar los notebooks

1. Inicia Jupyter Notebook:
```bash
jupyter notebook
```

2. Navega a la carpeta `notebooks/` y abre el notebook que desees explorar.

3. Ejecuta las celdas secuencialmente para ver las simulaciones y resultados.

### Notebooks disponibles

#### 🔗 ising_lineal.ipynb
Simulación del Modelo de Ising en una cadena unidimensional. Incluye:
- Sistema diluido con probabilidad de ocupación
- Análisis de magnetización vs temperatura
- Estudio de transiciones de fase en 1D

#### ⬜ ising_cuadrada.ipynb
Simulación del Modelo de Ising en una red cuadrada 2D. Incluye:
- Algoritmo de Metrópolis para evolución del sistema
- Visualización de configuraciones de spins
- Cálculo de temperatura crítica
- Análisis de propiedades termodinámicas

#### 🧊 ising_cubica.ipynb
Simulación del Modelo de Ising en una red cúbica 3D. Incluye:
- Implementación 3D del algoritmo Monte Carlo
- Análisis de fenómenos críticos en 3D
- Visualización de propiedades estadísticas

#### 🔶 ising_honeycomb.ipynb
Simulación del Modelo de Ising en una red hexagonal (honeycomb). Incluye:
- Construcción de topología honeycomb
- Análisis de coordinación diferente (z=3)
- Comparación con otras topologías

## 📊 Propiedades Calculadas

Los notebooks calculan las siguientes propiedades termodinámicas:

- **Energía**: Energía total del sistema
- **Magnetización**: Momento magnético promedio
- **Calor Específico**: Capacidad calorífica del sistema
- **Susceptibilidad Magnética**: Respuesta del sistema a campos magnéticos
- **Correlaciones**: Funciones de correlación espacial

## 🔧 Tecnologías Utilizadas

- **NumPy**: Cálculos numéricos y arrays
- **Matplotlib**: Visualización de datos
- **Numba**: Compilación JIT para optimización de rendimiento
- **Jupyter**: Notebooks interactivos

## 📖 Referencias

- Ising, E. (1925). "Beitrag zur Theorie des Ferromagnetismus"
- Metropolis, N. et al. (1953). "Equation of State Calculations by Fast Computing Machines"
- Onsager, L. (1944). "Crystal Statistics. I. A Two-Dimensional Model with an Order-Disorder Transition"

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz fork del proyecto
2. Crea una rama para tu función (`git checkout -b feature/nueva-funcion`)
3. Commit de tus cambios (`git commit -am 'Añadir nueva función'`)
4. Push a la rama (`git push origin feature/nueva-funcion`)
5. Abre un Pull Request

## 👤 Autor

Tu Nombre - [@tu-usuario](https://github.com/tu-usuario)

## ⭐ Agradecimientos

- A la comunidad de física estadística y mecánica computacional
- A los desarrolladores de NumPy, Matplotlib y Numba por sus excelentes herramientas

---

**Nota**: Este proyecto es con fines educativos y de investigación en física estadística.
