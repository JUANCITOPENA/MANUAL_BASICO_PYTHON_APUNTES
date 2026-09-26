# 🐍 Manual Paso a Paso de Python — Guía Maestra con Explicaciones, Algoritmos y Visualización

> **Material didáctico y de referencia profesional:** desde los fundamentos esenciales (variables, tipos de datos escalares y colecciones, números complejos, operadores aritméticos, relacionales y lógicos), estructuras de control y manejo de errores, hasta algoritmos de búsqueda y análisis de secuencias numéricas, funciones, visualización estadística con `matplotlib`, dashboards ejecutivos multipanel y el caso integrador empresarial con persistencia en `Excel` (`pandas`).

---

## 📚 Índice General

1. [Variables, Tipos de Datos y Operadores](#1-variables-tipos-de-datos-y-operadores)
   - [1.1 Variables y tipos de datos fundamentales (primitivos y colecciones)](#11-variables-y-tipos-de-datos-fundamentales-primitivos-y-colecciones)
   - [1.2 Catálogo detallado de tipos escalares: Números Complejos, Cadenas y Valor Nulo (None)](#12-catálogo-detallado-de-tipos-escalares-números-complejos-cadenas-y-valor-nulo-none)
   - [1.3 Operadores aritméticos y jerarquía matemática](#13-operadores-aritméticos-y-jerarquía-matemática)
   - [1.4 Operadores de comparación (relacionales)](#14-operadores-de-comparación-relacionales)
   - [1.5 Operadores lógicos (and, or, not) y evaluación de rangos](#15-operadores-lógicos-and-or-not-y-evaluación-de-rangos)
2. [Condicionales (if / elif / else)](#2-condicionales-if--elif--else)
   - [2.1 Verificación de mayoría de edad (valor fijo)](#21-verificación-de-mayoría-de-edad-valor-fijo)
   - [2.2 Verificación de mayoría de edad (con input del usuario)](#22-verificación-de-mayoría-de-edad-con-input-del-usuario)
   - [2.3 Evaluación condicional de tres ramas con elif (menor, igual o mayor)](#23-evaluación-condicional-de-tres-ramas-con-elif-menor-igual-o-mayor)
3. [Operadores Lógicos Aplicados: Sistemas de Acceso y Credenciales (and)](#3-operadores-lógicos-aplicados-sistemas-de-acceso-y-credenciales-and)
   - [3.1 Login con credenciales fijas](#31-login-con-credenciales-fijas)
   - [3.2 Login con credenciales ingresadas por el usuario](#32-login-con-credenciales-ingresadas-por-el-usuario)
4. [Estructura match-case (Switch en Python)](#4-estructura-match-case-switch-en-python)
   - [4.1 Menú de selección numérica directa (Switch clásico)](#41-menú-de-selección-numérica-directa-switch-clásico)
   - [4.2 Estación del año según el mes (fijo y con input)](#42-estación-del-año-según-el-mes-fijo-y-con-input)
   - [4.3 Calculadora básica con match-case](#43-calculadora-básica-con-match-case)
5. [Manejo de excepciones (try / except)](#5-manejo-de-excepciones-try--except)
   - [5.1 Calculadora robusta con try/except](#51-calculadora-robusta-con-tryexcept)
6. [Bucles for y while básicos](#6-bucles-for-y-while-básicos)
   - [6.1 Números naturales del 1 al 100 (uno por línea)](#61-números-naturales-del-1-al-100-uno-por-línea)
   - [6.2 Números naturales del 1 al 100 (en una sola línea)](#62-números-naturales-del-1-al-100-en-una-sola-línea)
   - [6.3 Números naturales del 1 al 100 con while](#63-números-naturales-del-1-al-100-con-while)
   - [6.4 Números pares del 1 al 100 con for (paso de 2)](#64-números-pares-del-1-al-100-con-for-paso-de-2)
   - [6.5 Números pares del 1 al 100 con while (paso de 2)](#65-números-pares-del-1-al-100-con-while-paso-de-2)
   - [6.6 Números pares con while True y break](#66-números-pares-con-while-true-y-break)
7. [Números pares e impares](#7-números-pares-e-impares)
   - [7.1 Pares del 1 al 100 usando el operador módulo](#71-pares-del-1-al-100-usando-el-operador-módulo)
   - [7.2 Pares hasta un límite ingresado por el usuario (for)](#72-pares-hasta-un-límite-ingresado-por-el-usuario-for)
   - [7.3 Pares hasta un límite ingresado por el usuario (while)](#73-pares-hasta-un-límite-ingresado-por-el-usuario-while)
   - [7.4 Impares del 1 al 100 (for)](#74-impares-del-1-al-100-for)
   - [7.5 Impares del 1 al 100 (while)](#75-impares-del-1-al-100-while)
   - [7.6 Impares hasta un límite (for)](#76-impares-hasta-un-límite-for)
   - [7.7 Impares hasta un límite (while)](#77-impares-hasta-un-límite-while)
   - [7.8 Impares con range de paso 2 (versión corta)](#78-impares-con-range-de-paso-2-versión-corta)
8. [Tablas de multiplicar](#8-tablas-de-multiplicar)
   - [8.1 Todas las tablas del 1 al 10 (bucles anidados)](#81-todas-las-tablas-del-1-al-10-bucles-anidados)
   - [8.2 Tabla específica elegida por el usuario](#82-tabla-específica-elegida-por-el-usuario)
   - [8.3 Tabla con rango de multiplicadores personalizado](#83-tabla-con-rango-de-multiplicadores-personalizado)
9. [Números primos (Fuerza bruta, función all() y bucle for-else)](#9-números-primos-fuerza-bruta-función-all-y-bucle-for-else)
   - [9.1 Primos hasta 100 (método de fuerza bruta)](#91-primos-hasta-100-método-de-fuerza-bruta)
   - [9.2 Primos hasta un límite ingresado por el usuario](#92-primos-hasta-un-límite-ingresado-por-el-usuario)
   - [9.3 Primos del 1 al 100 usando la función Pythonica all() y comprensión generadora](#93-primos-del-1-al-100-usando-la-función-pythonica-all-y-comprensión-generadora)
   - [9.4 Primos hasta un límite ingresado por el usuario usando all()](#94-primos-hasta-un-límite-ingresado-por-el-usuario-usando-all)
   - [9.5 Primos con for-else (método corto)](#95-primos-con-for-else-método-corto)
10. [Detección, Clasificación y Predicción de Secuencias Numéricas (Aritméticas y Geométricas)](#10-detección-clasificación-y-predicción-de-secuencias-numéricas-aritméticas-y-geométricas)
    - [10.1 Predicción del siguiente número por razón fija explícita](#101-predicción-del-siguiente-número-por-razón-fija-explícita)
    - [10.2 Detección automática de la razón geométrica](#102-detección-automática-de-la-razón-geométrica)
    - [10.3 Clasificación automática de patrones: Progresión Aritmética vs Progresión Geométrica](#103-clasificación-automática-de-patrones-progresión-aritmética-vs-progresión-geométrica-usando-diferencias-razones-y-set)
    - [10.4 Algoritmo integral de predicción: Comparativa didáctica de 3 métodos con explicación razonada](#104-algoritmo-integral-de-predicción-comparativa-didáctica-de-3-métodos-con-explicación-razonada)
11. [Serie de Fibonacci](#11-serie-de-fibonacci)
    - [11.1 Fibonacci con cantidad fija de términos](#111-fibonacci-con-cantidad-fija-de-términos)
    - [11.2 Fibonacci con cantidad de términos ingresada por el usuario](#112-fibonacci-con-cantidad-de-términos-ingresada-por-el-usuario)
12. [Factorial y permutaciones](#12-factorial-y-permutaciones)
    - [12.1 Factorial manual con bucle for (n=5)](#121-factorial-manual-con-bucle-for-n5)
    - [12.2 Factorial manual con bucle for (n=6, versión comentada)](#122-factorial-manual-con-bucle-for-n6-versión-comentada)
    - [12.3 Permutaciones de tres números con bucles anidados](#123-permutaciones-de-tres-números-con-bucles-anidados)
    - [12.4 Permutación P(n, r) sin usar factorial](#124-permutación-pn-r-sin-usar-factorial)
    - [12.5 Factorial con la librería math](#125-factorial-con-la-librería-math)
    - [12.6 Permutación P(n, r) con la librería math](#126-permutación-pn-r-con-la-librería-math)
    - [12.7 Permutaciones con la librería itertools](#127-permutaciones-con-la-librería-itertools)
13. [Funciones (def)](#13-funciones-def)
    - [13.1 Función sin parámetros: calcular el cuadrado de un número fijo](#131-función-sin-parámetros-calcular-el-cuadrado-de-un-número-fijo)
    - [13.2 Función que recibe datos por input y devuelve el factorial](#132-función-que-recibe-datos-por-input-y-devuelve-el-factorial)
14. [Visualización de datos con matplotlib (gráficos individuales)](#14-visualización-de-datos-con-matplotlib-gráficos-individuales)
    - [14.1 Gráfico de líneas: tendencia de ventas mensuales](#141-gráfico-de-líneas-tendencia-de-ventas-mensuales)
    - [14.2 Gráfico de barras: ventas por categoría](#142-gráfico-de-barras-ventas-por-categoría)
    - [14.3 Gráfico de dispersión: relación entre horas estudiadas y nota](#143-gráfico-de-dispersión-relación-entre-horas-estudiadas-y-nota)
    - [14.4 Gráfico de pastel: participación de mercado](#144-gráfico-de-pastel-participación-de-mercado)
    - [14.5 Histograma: distribución de edades](#145-histograma-distribución-de-edades)
    - [14.6 Gráfico avanzado: Diagrama de Pareto 80/20 con doble eje Y (twinx) y línea de umbral acumulada](#146-gráfico-avanzado-diagrama-de-pareto-8020-con-doble-eje-y-twinx-y-línea-de-umbral-acumulada)
    - [14.7 Análisis de series temporales: Suavizado de demanda con Media Móvil (Rolling Window SMA-3) y comparativa de tendencias](#147-análisis-de-series-temporales-suavizado-de-demanda-con-media-móvil-rolling-window-sma-3-y-comparativa-de-tendencias)
    - [14.8 Pipeline ETL de Cuentas por Cobrar (CxC): Función Heurística (.apply), Agregación (.groupby) y Gráfico Circular Semafórico de Morosidad](#148-pipeline-etl-de-cuentas-por-cobrar-cxc-función-heurística-apply-agregación-groupby-y-gráfico-circular-semafórico-de-morosidad)
    - [14.9 Evaluación Crediticia Algorítmica: Gráfico de Dispersión (Scatter Plot) con Frontera de Decisión DTI y Mapeo Categórico (.map)](#149-evaluación-crediticia-algorítmica-gráfico-de-dispersión-scatter-plot-con-frontera-de-decisión-dti-y-mapeo-categórico-map)
    - [14.10 Analítica de Experiencia del Cliente: Gráfico de Dona (Donut Chart) con wedgeprops, Cálculo de NPS e Inyección Central de KPI (plt.text)](#1410-analítica-de-experiencia-del-cliente-gráfico-de-dona-donut-chart-con-wedgeprops-cálculo-de-nps-e-inyección-central-de-kpi-plttext)
    - [14.11 Detección de Anomalías y Fraude Transaccional: Control Estadístico con Z-Score ($2\sigma$), Marcado de Outliers y Umbral Crítico (axhline)](#1411-detección-de-anomalías-y-fraude-transaccional-control-estadístico-con-z-score-2sigma-marcado-de-outliers-y-umbral-crítico-axhline)
    - [14.12 Proyección de Flujo de Caja (Cashflow Forecast): Relleno Condicional Dinámico de Superávit y Déficit (fill_between con where)](#1412-proyección-de-flujo-de-caja-cashflow-forecast-relleno-condicional-dinámico-de-superávit-y-déficit-fill_between-con-where)
    - [14.13 Análisis de Retorno de Inversión (ROI) por Sucursal: Gráfico de Barras Horizontales con Ordenamiento y Anotación Directa de Datos (plt.barh y plt.text)](#1413-análisis-de-retorno-de-inversión-roi-por-sucursal-gráfico-de-barras-horizontales-con-ordenamiento-y-anotación-directa-de-datos-pltbarh-y-plttext)
    - [14.14 Diversificación de Portafolio y Asignación de Activos (Asset Allocation): Gráfico de Dona con Desglose Radial (explode) y Distancia Porcentual (pctdistance)](#1414-diversificación-de-portafolio-y-asignación-de-activos-asset-allocation-gráfico-de-dona-con-desglose-radial-explode-y-distancia-porcentual-pctdistance)
    - [14.15 Curva de Supervivencia y Análisis de Retención de Clientes (Cohortes): Gráficos de Escalera / Escalón (plt.step con relleno post)](#1415-curva-de-supervivencia-y-análisis-de-retención-de-clientes-cohortes-gráficos-de-escalera--escalón-pltstep-con-relleno-post)
    - [14.16 Modelado Macroeconómico de Inflación y Depreciación: Curva de Decaimiento Exponencial y Supresión de Notación Científica (ticklabel_format)](#1416-modelado-macroeconómico-de-inflación-y-depreciación-curva-de-decaimiento-exponencial-y-supresión-de-notación-científica-ticklabel_format)
    - [14.17 Prueba de Estrés Financiero (Stress Test Hipotecario): Función de Amortización Francesa, Simulación de Escenarios y Líneas de Frontera](#1417-prueba-de-estrés-financiero-stress-test-hipotecario-función-de-amortización-francesa-simulación-de-escenarios-y-líneas-de-frontera)
    - [14.18 Matriz Estratégica de Talento y Rendimiento (Matriz de Cuadrantes): Gráfico de Dispersión con Cruce de Medias (axvline/axhline) y Etiquetado Individual de Observaciones](#1418-matriz-estratégica-de-talento-y-rendimiento-matriz-de-cuadrantes-gráfico-de-dispersión-con-cruce-de-medias-axvlineaxhline-y-etiquetado-individual-de-observaciones)
15. [Dashboards comparativos con subplots (dos gráficos lado a lado)](#15-dashboards-comparativos-con-subplots-dos-gráficos-lado-a-lado)
    - [15.1 Depósitos mensuales e intereses ganados](#151-depósitos-mensuales-e-intereses-ganados)
    - [15.2 Cartera total y morosidad](#152-cartera-total-y-morosidad)
    - [15.3 Ingresos por intereses y gastos operativos](#153-ingresos-por-intereses-y-gastos-operativos)
    - [15.4 Ahorros acumulados y rendimiento mensual](#154-ahorros-acumulados-y-rendimiento-mensual)
    - [15.5 Transacciones y comisiones](#155-transacciones-y-comisiones)
16. [Caso integrador: Sistema de análisis de ventas con Excel](#16-caso-integrador-sistema-de-análisis-de-ventas)
    - [16.1 Definición de categorías y estructura de una venta](#161-definición-de-categorías-y-estructura-de-una-venta)
    - [16.2 Simulación de 100 ventas aleatorias y reportes por categoría](#162-simulación-de-100-ventas-aleatorias-y-reportes-por-categoría)
    - [16.3 Reportes con distribución por rangos de monto y dashboard visual](#163-reportes-con-distribución-por-rangos-de-monto-y-dashboard-visual)
    - [16.4 Generar un archivo Excel con 500 registros reales](#164-generar-un-archivo-excel-con-500-registros-reales)
    - [16.5 Dashboard leyendo los datos desde el archivo Excel generado](#165-dashboard-leyendo-los-datos-desde-el-archivo-excel-generado)
17. [Glosario completo de conceptos y operadores usados](#17--glosario-completo-de-conceptos-y-operadores-usados)

---

## 1. Variables, Tipos de Datos y Operadores

### 1.1 Variables y tipos de datos fundamentales (primitivos y colecciones)

**📌 Enunciado:** Declarar e inicializar variables en Python para representar los tipos de datos principales del lenguaje (enteros, decimales, cadenas de texto, booleanos, listas, tuplas y diccionarios) y mostrarlos por consola en una sola instrucción.

**💡 Explicación / Definición:** Python es un lenguaje de **tipado dinámico**, lo que significa que no se requiere declarar explícitamente el tipo de una variable al crearla; el intérprete infiere su tipo en tiempo de ejecución según el valor asignado:
- `int` (entero): números sin decimales (`10`).
- `float` (flotante / decimal): números con punto decimal (`10.5`).
- `str` (cadena de texto): caracteres encerrados entre comillas dobles o simples (`"Hola Python"`).
- `bool` (booleano): valores de verdad lógica (`True` o `False`).
- `list` (lista): colección ordenada y modificable (mutable) de elementos entre corchetes `[1, 2, 3]`.
- `tuple` (tupla): colección ordenada e inmutable (no se puede modificar una vez creada) entre paréntesis `(4, 5, 6)`.
- `dict` (diccionario): estructura asociativa de pares clave-valor entre llaves `{"a": 1}`.

`print()` puede recibir múltiples argumentos separados por comas, imprimiéndolos en secuencia separados por un espacio.

```python
# ================================
# VARIABLES Y TIPOS DE DATOS
# ================================

entero = 10                # int
decimal = 10.5             # float
texto = "Hola Python"      # str
booleano = True            # bool
lista = [1, 2, 3]          # list (mutable)
tupla = (4, 5, 6)          # tuple (inmutable)
diccionario = {"a": 1}     # dict (clave: valor)

print(entero, decimal, texto, booleano, lista, tupla, diccionario)
```

**⚙️ Comentario de funcionamiento:** El intérprete crea en memoria cada objeto con su tipo correspondiente, asigna cada identificador a su referencia, y la función `print()` convierte internamente cada valor a texto separándolos con espacios: `10 10.5 Hola Python True [1, 2, 3] (4, 5, 6) {'a': 1}`.

---

### 1.2 Catálogo detallado de tipos escalares: Números Complejos, Cadenas y Valor Nulo (None)

**📌 Enunciado:** Declarar variables individuales para cada tipo de dato escalar en Python, incorporando números complejos con parte imaginaria `j` y la constante de ausencia de valor `None`. Utilizar operadores de repetición sobre cadenas de texto (`"=" * 30`) para generar separadores visuales limpios y mostrar cada variable etiquetada.

**💡 Explicación / Definición:** Este ejercicio profundiza en los tipos de datos escalares (valores únicos individuales que no son colecciones):
- **`int` (entero):** Números enteros con precisión ilimitada en memoria.
- **`float` (racional / coma flotante):** Números reales con decimales en estándar IEEE 754.
- **`complex` (número complejo):** Tipo numérico nativo de Python para manejar números de la forma $a + bj$, donde `j` denota la unidad imaginaria ($\sqrt{-1}$).
- **`bool` (booleano):** Subtipo de entero con valores binarios `True` y `False`.
- **`str` (cadena de texto):** Texto inmutable. Al multiplicar un `str` por un entero (`"=" * 30`), Python aplica el operador de repetición, duplicando el carácter 30 veces sin necesidad de bucles.
- **`NoneType` (`None`):** Objeto único integrado que denota la **ausencia intencional de valor** o valor nulo (equivalente a `null` o `nil` en otros lenguajes).

```python
# ================================
# TIPOS ESCALARES Y CONSTANTE NONE
# ================================

print("🐍 Tipos de datos en Python")
print("=" * 30)

mi_entero = 4
mi_racional = 8.35
mi_complejo = 25 + 3j
mi_bool1 = True
mi_bool2 = False
mi_cadena1 = "Este es un ejemplo de una cadena"
mi_cadena2 = "y este es otro ejemplo de una cadena"
nada = None

print("Entero:", mi_entero)
print("Racional:", mi_racional)
print("Complejo:", mi_complejo)
print("Booleano 1:", mi_bool1)
print("Booleano 2:", mi_bool2)
print("Cadena 1:", mi_cadena1)
print("Cadena 2:", mi_cadena2)
print("Ninguno:", nada)
```

**⚙️ Comentario de funcionamiento:**
1. `print("=" * 30)` genera una barra horizontal de 30 signos igual como separador en la consola.
2. Se crean en memoria las variables correspondientes; al asignar `25 + 3j`, Python instancia automáticamente un objeto de tipo `complex`.
3. `nada = None` almacena la referencia al singleton de valor nulo.
4. Cada llamada a `print()` muestra la etiqueta en español seguida del valor evaluado, imprimiendo el complejo en formato `(25+3j)` y la variable nula como `None`.

---

### 1.3 Operadores aritméticos y jerarquía matemática

**📌 Enunciado:** Realizar las operaciones matemáticas elementales entre dos números y mostrar sus resultados identificados con su operación correspondiente.

**💡 Explicación / Definición:** Python proporciona operadores nativos para todas las operaciones aritméticas:
- `+` (Suma) y `-` (Resta).
- `*` (Multiplicación).
- `/` (División estándar): siempre devuelve un número decimal (`float`), incluso si el resultado es exacto (`10 / 2` da `5.0`).
- `//` (División entera o truncada): devuelve únicamente la parte entera del cociente descartando los decimales (`10 // 3` da `3`).
- `%` (Módulo o residuo): devuelve el resto de la división entera (`10 % 3` da `1`). Esencial para determinar múltiplos y paridad.
- `**` (Potencia o exponenciación): eleva la base al exponente (`10 ** 3` equivale a $10^3 = 1000$).

```python
# ================================
# OPERADORES ARITMÉTICOS
# ================================

a = 10
b = 3

print("Suma:", a + b)
print("Resta:", a - b)
print("Multiplicación:", a * b)
print("División:", a / b)
print("División entera:", a // b)
print("Módulo (resto):", a % b)
print("Potencia:", a ** b)
```

**⚙️ Comentario de funcionamiento:** Python calcula cada expresión respetando las reglas aritméticas: la suma da `13`, la resta `7`, la multiplicación `30`, la división flotante `3.3333333333333335`, la división entera `3`, el residuo `1` y la potencia `1000`.

---

### 1.4 Operadores de comparación (relacionales)

**📌 Enunciado:** Comparar dos variables numéricas mediante operadores relacionales y verificar el resultado booleano (`True` o `False`) de cada evaluación.

**💡 Explicación / Definición:** Los operadores de comparación evalúan la relación matemática entre dos expresiones y siempre producen un valor de tipo booleano (`bool`):
- `==` (Igualdad): Compara si dos valores son iguales (diferente de `=`, que es asignación).
- `!=` (Desigualdad o diferente): `True` si los valores son distintos.
- `>` (Mayor que) y `<` (Menor que).
- `>=` (Mayor o igual que) y `<=` (Menor o igual que).

```python
# ================================
# OPERADORES DE COMPARACIÓN
# ================================

x = 5
y = 8

print("== :", x == y)   # Igualdad: False
print("!= :", x != y)   # Diferente: True
print(">  :", x > y)    # Mayor: False
print("<  :", x < y)    # Menor: True
print(">= :", x >= y)   # Mayor o igual: False
print("<= :", x <= y)   # Menor o igual: True
```

**⚙️ Comentario de funcionamiento:** Dado que `5` es estrictamente menor que `8`, las operaciones de igualdad (`==`), mayor (`>`) y mayor o igual (`>=`) resultan en `False`, mientras que diferente (`!=`), menor (`<`) y menor o igual (`<=`) evalúan a `True`. Estas expresiones son el núcleo lógico de las sentencias condicionales (`if`).

---

### 1.5 Operadores lógicos (and, or, not) y evaluación de rangos

**📌 Enunciado:** Evaluar expresiones lógicas compuestas sobre una variable de edad utilizando conjunción (`and`), disyunción (`or`) y negación (`not`).

**💡 Explicación / Definición:** Los operadores lógicos combinan o invierten expresiones booleanas:
- `and` (Conjunción): Da `True` **únicamente si ambas** expresiones conectadas son verdaderas. Es la base para evaluar si un valor se encuentra dentro de un rango cerrado (`edad > 18 and edad < 30`).
- `or` (Disyunción): Da `True` si **al menos una** de las expresiones es verdadera. Es ideal para evaluar condiciones de frontera o extremos (`edad < 18 or edad > 60`).
- `not` (Negación): Invierte el valor booleano de la expresión que le sigue (`not True` da `False`).

```python
# ================================
# OPERADORES LÓGICOS
# ================================

edad = 20

print("AND:", edad > 18 and edad < 30)
print("OR :", edad < 18 or edad > 60)
print("NOT:", not (edad > 18))
```

**⚙️ Comentario de funcionamiento:** Con `edad = 20`:
1. `edad > 18` (True) `and` `edad < 30` (True) $
ightarrow$ `True` (está en el rango 19 a 29).
2. `edad < 18` (False) `or` `edad > 60` (False) $
ightarrow$ `False` (no cumple ninguno de los dos extremos).
3. `edad > 18` es True, por lo que `not (True)` $
ightarrow$ `False`.

---

## 2. Condicionales (if / else)

### 2.1 Verificación de mayoría de edad (valor fijo)

**📌 Enunciado:** Dada una variable con un valor fijo de edad, determinar si la persona es mayor o menor de edad usando una estructura condicional simple.

**💡 Explicación / Definición:** El `if` es una estructura de control que evalúa una condición booleana (verdadera o falsa). Si la condición se cumple, se ejecuta el bloque indentado bajo `if`; si no, se ejecuta el bloque bajo `else`. Aquí se compara `edad >= 18` usando el operador relacional `>=` (mayor o igual que).

```python
# DEFINO MI VARIABLE Y VALOR

edad = 17

if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")
```

**⚙️ Comentario de funcionamiento:** Python evalúa `17 >= 18`, lo cual es `False`, por lo que el flujo salta al bloque `else` e imprime `"Eres menor de edad"`.

---

### 2.2 Verificación de mayoría de edad (con input del usuario)

**📌 Enunciado:** Igual al ejercicio anterior, pero solicitando la edad al usuario por teclado en tiempo de ejecución.

**💡 Explicación / Definición:** `input()` siempre devuelve una cadena de texto (`str`), por lo que debe convertirse con `float()` para poder hacer comparaciones numéricas. Esta versión corrige un exceso de paréntesis que existía en un intento anterior.

```python
# DEFINO MI VARIABLE Y VALOR (Corregido el exceso de paréntesis)
edad = float(input("Ingresa tu Edad: "))

# pregunto con un if (estructura de control si)
if edad >= 18:
    print("Eres Mayor de Edad:", edad)
else:
    print("Eres Menor de Edad:", edad)
```

**⚙️ Comentario de funcionamiento:** El programa se detiene esperando que el usuario escriba un número, lo convierte a `float` (número decimal) y evalúa la misma condición que el ejercicio 1.1, mostrando además el valor ingresado junto al mensaje.

---

### 2.3 Evaluación condicional de tres ramas con elif (menor, igual o mayor)

**📌 Enunciado:** Evaluar una variable numérica e imprimir si el valor es estrictamente menor que 10, exactamente igual a 10 o estrictamente mayor que 10 usando la cláusula `elif`.

**💡 Explicación / Definición:** Cuando un problema involucra más de dos posibles estados mutuamente excluyentes, `if/else` por sí solo resulta insuficiente o requiere anidamientos confusos. La palabra clave `elif` (abreviatura de *else if*) permite encadenar comprobaciones adicionales en cascada:
- Si la primera condición (`if`) es verdadera, se ejecuta su bloque y se omiten todas las demás ramas.
- Si es falsa, Python pasa a evaluar la condición del primer `elif`.
- Si ninguna de las condiciones previas se cumple, se ejecuta el bloque `else` final.

Esta estructura es notablemente más eficiente que escribir múltiples `if` consecutivos, ya que en el momento en que una condición resulta verdadera, las ramas subsiguientes ni siquiera se evalúan.

```python
# ================================
# CONDICIONALES IF, ELIF, ELSE
# ================================

numero = 15

if numero < 10:
    print("El número es menor que 10")
elif numero == 10:
    print("El número es igual a 10")
else:
    print("El número es mayor que 10")
```

**⚙️ Comentario de funcionamiento:** El programa asigna `numero = 15`. Evalúa primero `15 < 10` (False), por lo que salta la primera rama. Luego evalúa el `elif: 15 == 10` (False). Al no cumplirse ninguna anterior, el flujo cae obligatoriamente en el bloque `else`, imprimiendo `"El número es mayor que 10"`.

---

## 3. Operadores Lógicos Aplicados: Sistemas de Acceso y Credenciales (and)

### 3.1 Login con credenciales fijas

**📌 Enunciado:** Validar un acceso comparando usuario y contraseña contra valores predefinidos en el código.

**💡 Explicación / Definición:** El operador lógico `and` requiere que **ambas** condiciones sean verdaderas para que el resultado total sea `True`. Se usa el operador de comparación `==` (igualdad), que no debe confundirse con `=` (asignación).

```python
# Variables que introduce el usuario
usuario = "admin"
contrasenia = "12345"

# Ambos lados del 'and' deben cumplirse
if usuario == "admin" and contrasenia == "12345":
    print("Acceso concedido. ¡Bienvenido!")
else:
    print("Usuario o contraseña incorrectos.")
```

**⚙️ Comentario de funcionamiento:** Como ambas variables ya tienen los valores correctos, las dos comparaciones son `True`, el `and` da `True` y se concede el acceso.

---

### 3.2 Login con credenciales ingresadas por el usuario

**📌 Enunciado:** Solicitar usuario y contraseña por teclado y validarlos contra credenciales correctas almacenadas en variables.

**💡 Explicación / Definición:** Se separan las credenciales "correctas" (constantes de referencia) de las credenciales "ingresadas" (capturadas con `input()`). No se usa `float()` aquí porque usuario y contraseña son texto, no números.

```python
# Variables que introducen las credenciales correctas (como texto)
usuario_correcto = "admin"
contrasenia_correcta = "12345"

# Solicitamos los datos al usuario (Quitamos float porque son cadenas de texto)
usuario = input("Ingrese el usuario: ")
contrasenia = input("Ingrese la contrasenia: ")

# Ambos lados del 'and' deben cumplirse
if usuario == usuario_correcto and contrasenia == contrasenia_correcta:
    print("Acceso concedido. ¡Bienvenido!")
else:
    print("Usuario o contraseña incorrectos.")
```

**⚙️ Comentario de funcionamiento:** El programa compara dinámicamente lo que el usuario escribe contra los valores de referencia; si alguna de las dos comparaciones falla, el `and` devuelve `False` y se rechaza el acceso.

---

## 4. Estructura match-case (Switch en Python)

### 4.1 Menú de selección numérica directa (Switch clásico)

**📌 Enunciado:** Evaluar una variable de selección numérica e imprimir la opción correspondiente elegida por el usuario utilizando la estructura `match-case`.

**💡 Explicación / Definición:** La estructura `match-case` (incorporada en Python 3.10) es el equivalente formal a la sentencia `switch-case` común en lenguajes como C, C++, Java y JavaScript. Permite comprobar un valor contra múltiples casos exactos de forma legible:
- `match expresion:` inicia el bloque de control.
- `case valor:` define cada patrón específico a comparar.
- `case _:` actúa como el caso comodín por defecto (*default / fallback*), que se ejecuta si ningún caso anterior coincidió.

```python
# ================================
# SWITCH EN PYTHON (match-case)
# ================================

opcion = 2

match opcion:
    case 1:
        print("Elegiste opción 1")
    case 2:
        print("Elegiste opción 2")
    case 3:
        print("Elegiste opción 3")
    case _:
        print("Opción no válida")
```

**⚙️ Comentario de funcionamiento:** Con `opcion = 2`, Python evalúa secuencialmente: `case 1` no coincide, pasa a `case 2`, encuentra coincidencia exacta, imprime `"Elegiste opción 2"` y finaliza inmediatamente el bloque `match` sin necesidad de utilizar sentencias `break` manuales.
---


### 4.2 Estación del año según el mes (fijo y con input)

**📌 Enunciado:** Determinar la estación del año a partir del número de mes, primero con un valor fijo en el código y luego solicitado al usuario.

**💡 Explicación / Definición:** `match-case` (disponible desde Python 3.10) es una alternativa a múltiples `if/elif` para comparar un valor contra varios patrones. El operador `|` dentro de un `case` permite agrupar varias opciones equivalentes. El patrón `case _:` funciona como un "caso por defecto" (comodín), similar al `else`.

```python
# ==========================================
# PARTE A: SIN INPUT (Valor fijo en el código)
# ==========================================
mes_fijo = 12  # Cambia este número manualmente para probar

print("--- Resultado Sin Input ---")
match mes_fijo:
    case 12 | 1 | 2:
        print(f"El mes {mes_fijo} corresponde a Invierno.")
    case 3 | 4 | 5:
        print(f"El mes {mes_fijo} corresponde a Primavera.")
    case 6 | 7 | 8:
        print(f"El mes {mes_fijo} corresponde a Verano.")
    case 9 | 10 | 11:
        print(f"El mes {mes_fijo} corresponde a Otoño.")
    case _:
        print("Número de mes inválido (debe ser del 1 al 12).")


# ==========================================
# PARTE B: CON INPUT (El usuario decide)
# ==========================================
print("\n--- Prueba Con Input ---")
mes_usuario = int(input("Ingresa el número de un mes (1-12): "))

match mes_usuario:
    case 1:
        print("Enero")
    case 2:
        print("Febrero")
    case 3:
        print("Marzo")
    # ... puedes agregar el resto de meses aquí ...
    case 12:
        print("Diciembre")
    case _:
        print("Ese mes no existe.")
```

**⚙️ Comentario de funcionamiento:** En la Parte A, Python recorre los `case` de arriba hacia abajo hasta encontrar una coincidencia; como `mes_fijo = 12` cae en `case 12 | 1 | 2`, imprime "Invierno". En la Parte B, el `match` compara el mes ingresado contra casos individuales (1, 2, 3... 12); si el número no está listado explícitamente, cae en `case _`.

---

### 4.3 Calculadora básica con match-case

**📌 Enunciado:** Solicitar dos números y un operador (`+`, `-`, `*`, `/`) al usuario y realizar la operación correspondiente, validando la división entre cero.

**💡 Explicación / Definición:** Cada `case` representa un patrón de texto (el símbolo del operador). Antes de dividir, se valida con un `if` que el divisor no sea cero, evitando así un error de ejecución (`ZeroDivisionError`).

```python
# Pedimos los números y la operación al usuario
num1 = float(input("Ingresa el primer número: "))
num2 = float(input("Ingresa el segundo número: "))
operacion = input("Ingresa la operación (+, -, *, /): ")

match operacion:
    case "+":
        resultado = num1 + num2
        print(f"Resultado de la suma: {resultado}")
    
    case "-":
        resultado = num1 - num2
        print(f"Resultado de la resta: {resultado}")
    
    case "*":
        resultado = num1 * num2
        print(f"Resultado de la multiplicación: {resultado}")
    
    case "/":
        # Validamos que no se divida entre cero para que no falle el programa
        if num2 != 0:
            resultado = num1 / num2
            print(f"Resultado de la división: {resultado}")
        else:
            print("Error: No se puede dividir entre cero.")
            
    case _:
        print("Operador no válido. Usa +, -, * o /.")
```

**⚙️ Comentario de funcionamiento:** El `match` selecciona el bloque según el símbolo escrito por el usuario; dentro del caso `"/"` hay una validación anidada adicional (`if num2 != 0`) porque `match-case` no puede evitar por sí solo el error de dividir entre cero, así que se combina con un `if` normal.

---

## 5. Manejo de excepciones (try/except)

### 5.1 Calculadora robusta con try/except

**📌 Enunciado:** Repetir la calculadora anterior, pero evitando que el programa se caiga si el usuario ingresa texto en lugar de números.

**💡 Explicación / Definición:** El bloque `try` contiene el código "propenso a errores". Si ocurre una excepción del tipo especificado (aquí `ValueError`, que se produce al intentar convertir texto no numérico con `float()`), el flujo salta automáticamente al bloque `except` en lugar de detener el programa con un error fatal.

```python
# Ponemos el código propenso a errores dentro de un bloque 'try'
try:
    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))
    
    operacion = input("Ingresa la operación (+, -, *, /): ")

    match operacion:
        case "+":
            print(f"Resultado: {num1 + num2}")
        case "-":
            print(f"Resultado: {num1 - num2}")
        case "*":
            print(f"Resultado: {num1 * num2}")
        case "/":
            if num2 != 0:
                print(f"Resultado: {num1 / num2}")
            else:
                print("❌ Error: No se puede dividir entre cero.")
        case _:
            print("❌ Operador no válido. Usa +, -, * o /.")

# Si ocurre un ValueError (escribir texto en vez de números), se ejecuta esto:
except ValueError:
    print("❌ Error: ¡Debes ingresar números válidos, no letras o símbolos!")
```

**⚙️ Comentario de funcionamiento:** Si el usuario escribe, por ejemplo, `"abc"` cuando se le pide un número, `float("abc")` lanza un `ValueError`; en vez de que el programa se detenga con un mensaje de error técnico, el `except ValueError` lo intercepta y muestra un mensaje amigable.

---

## 6. Bucles for y while básicos

### 6.1 Números naturales del 1 al 100 (uno por línea)

**📌 Enunciado:** Imprimir los números del 1 al 100, cada uno en una línea distinta.

**💡 Explicación / Definición:** `range(1, 101)` genera una secuencia de números desde 1 hasta 100 (el límite superior de `range` **no se incluye**, por eso se usa 101). El `for` recorre esa secuencia asignando cada valor a la variable `i`.

```python
print("Los Numeros Naturales hasta el 100:")

for i in range(1, 101):
    print(i)
```

**⚙️ Comentario de funcionamiento:** Cada llamada a `print(i)` termina con un salto de línea por defecto, por lo que cada número aparece en su propia línea.

---

### 6.2 Números naturales del 1 al 100 (en una sola línea)

**📌 Enunciado:** Igual al anterior, pero mostrando todos los números separados por espacio en una sola línea.

**💡 Explicación / Definición:** El parámetro `end=" "` de `print()` reemplaza el salto de línea por defecto (`"\n"`) por un espacio, logrando que las impresiones queden en la misma línea.

```python
print("Los Numeros Naturales hasta el 100:")

for i in range(1, 101):
    print(i, end=" ")
```

**⚙️ Comentario de funcionamiento:** Al imprimir cada número seguido de un espacio en lugar de un salto de línea, el resultado final es una sola línea larga: `1 2 3 4 ... 100`.

---

### 6.3 Números naturales del 1 al 100 con while

**📌 Enunciado:** Lograr el mismo resultado del ejercicio 5.1 pero utilizando un bucle `while` en lugar de `for`.

**💡 Explicación / Definición:** El `while` repite un bloque mientras una condición sea verdadera. A diferencia del `for` con `range`, aquí es necesario declarar manualmente un contador (`contador = 1`) e incrementarlo dentro del bucle (`contador += 1`), o se produciría un bucle infinito.

```python
contador = 1
while contador <= 100:
    print(contador)
    contador += 1  # Suma 1 en cada vuelta para avanzar
```

**⚙️ Comentario de funcionamiento:** En cada iteración se imprime el valor actual de `contador` y luego se incrementa en 1; cuando `contador` llega a 101, la condición `contador <= 100` se vuelve `False` y el bucle termina.

---

### 6.4 Números pares del 1 al 100 con for (paso de 2)

**📌 Enunciado:** Mostrar únicamente los números pares del 1 al 100 usando el tercer parámetro de `range()`.

**💡 Explicación / Definición:** `range(inicio, fin, paso)` permite definir un incremento distinto de 1. Empezando en 2 y saltando de 2 en 2, se obtienen solo números pares.

```python
# Empezamos en 2, vamos hasta el 101 (para incluir el 100) y saltamos de 2 en 2
for i in range(2, 101, 2):
    print(i, end=" ")
```

**⚙️ Comentario de funcionamiento:** `range(2, 101, 2)` genera 2, 4, 6, ..., 100, evitando así tener que usar un `if` para filtrar pares.

---

### 6.5 Números pares del 1 al 100 con while (paso de 2)

**📌 Enunciado:** Igual al anterior, pero con `while`.

**💡 Explicación / Definición:** El contador se inicializa en 2 y se incrementa de 2 en 2 en cada vuelta, replicando manualmente el comportamiento del `range` con paso.

```python
contador = 2

while contador <= 100:
    print(contador, end=" ")
    contador += 2  # Incrementa de dos en dos
```

**⚙️ Comentario de funcionamiento:** El bucle continúa mientras `contador` sea menor o igual a 100, sumando 2 en cada vuelta hasta superar ese límite.

---

### 6.6 Números pares con while True y break

**📌 Enunciado:** Mostrar los números pares del 1 al 100 utilizando un bucle infinito controlado por `break`.

**💡 Explicación / Definición:** `while True` crea un bucle que se repetiría para siempre si no existiera una condición de salida explícita. `break` interrumpe el bucle inmediatamente cuando se cumple la condición indicada, sin importar en qué punto del bloque se encuentre.

```python
contador = 2

while True:
    print(contador, end=" ")
    contador += 2
    
    # Condición de salida al final del bloque (evalúa después de ejecutar)
    if contador > 100:
        break  # Rompe y sale del bucle
```

**⚙️ Comentario de funcionamiento:** A diferencia de un `while` normal, aquí la condición de salida se evalúa **después** de imprimir y de incrementar, por eso se coloca un `if` con `break` al final del bloque.

---

## 7. Números pares e impares

### 7.1 Pares del 1 al 100 usando el operador módulo

**📌 Enunciado:** Identificar los números pares del 1 al 100 utilizando el operador `%` (módulo), que devuelve el residuo de una división.

**💡 Explicación / Definición:** Un número es par si el residuo de dividirlo entre 2 es 0 (`i % 2 == 0`).

```python
for i in range(1, 101):
    if i % 2 == 0:
        print(f"{i} es par")
```

**⚙️ Comentario de funcionamiento:** El bucle recorre todos los números del 1 al 100 y, para cada uno, evalúa si el residuo de dividir entre 2 es 0; si lo es, se considera par y se imprime.

---

### 7.2 Pares hasta un límite ingresado por el usuario (for)

**📌 Enunciado:** Igual al anterior, pero el límite superior lo define el usuario.

**💡 Explicación / Definición:** Se suma 1 al límite dentro de `range()` porque el segundo argumento de `range` es exclusivo; sumar 1 asegura que el número límite también se evalúe.

```python
# Pedimos al usuario hasta qué número quiere evaluar
limite = int(input("Ingresa el número límite: "))

# Sumamos +1 al límite para que incluya ese número en la evaluación
for i in range(1, limite + 1):
    if i % 2 == 0:
        print(f"{i} es par")
```

**⚙️ Comentario de funcionamiento:** Si el usuario ingresa, por ejemplo, 20, `range(1, 21)` recorrerá del 1 al 20 inclusive, evaluando la paridad de cada número.

---

### 7.3 Pares hasta un límite ingresado por el usuario (while)

**📌 Enunciado:** Misma lógica que 6.2, pero con `while`.

**💡 Explicación / Definición:** Se controla el avance manualmente con un contador `i` que se incrementa de 1 en 1, comparándolo en cada vuelta contra `limite`.

```python
limite = int(input("Ingresa el número límite (while): "))
i = 1

while i <= limite:
    if i % 2 == 0:
        print(f"{i} es par")
    i += 1  # Avanzamos de uno en uno
```

**⚙️ Comentario de funcionamiento:** El bucle sigue ejecutándose mientras `i` no supere `limite`; en cada vuelta se evalúa la paridad y luego se incrementa `i`.

---

### 7.4 Impares del 1 al 100 (for)

**📌 Enunciado:** Mostrar los números impares del 1 al 100.

**💡 Explicación / Definición:** Un número es impar si el residuo de dividirlo entre 2 es distinto de 0 (`i % 2 != 0`, donde `!=` significa "diferente de").

```python
# Recorremos del 1 al 100
for i in range(1, 101):
    if i % 2 != 0:  # != significa "diferente de"
        print(f"{i} es impar")
```

**⚙️ Comentario de funcionamiento:** Complementa el ejercicio 6.1: en lugar de buscar residuo 0, busca residuo distinto de 0, capturando así todos los números impares.

---

### 7.5 Impares del 1 al 100 (while)

**📌 Enunciado:** Igual al 6.4, con `while`.

```python
i = 1
while i <= 100:
    if i % 2 != 0:
        print(f"{i} es impar")
    i += 1
```

**⚙️ Comentario de funcionamiento:** Recorre del 1 al 100 con un contador manual, imprimiendo únicamente los valores cuyo residuo al dividir entre 2 no sea 0.

---

### 7.6 Impares hasta un límite (for)

```python
limite = int(input("Ingresa el número límite (for impares): "))

for i in range(1, limite + 1):
    if i % 2 != 0:
        print(f"{i} es impar")
```

**⚙️ Comentario de funcionamiento:** Combina la lógica de límite dinámico (ejercicio 6.2) con la detección de impares (ejercicio 6.4).

---

### 7.7 Impares hasta un límite (while)

```python
limite = int(input("Ingresa el número límite (while impares): "))
i = 1

while i <= limite:
    if i % 2 != 0:
        print(f"{i} es impar")
    i += 1
```

**⚙️ Comentario de funcionamiento:** Misma lógica que 6.6, pero controlada con `while` y un contador manual.

---

### 7.8 Impares con range de paso 2 (versión corta)

**📌 Enunciado:** Obtener los números impares hasta un límite sin usar `if`, aprovechando el paso de `range()`.

**💡 Explicación / Definición:** Al iniciar en 1 y saltar de 2 en 2, `range()` genera directamente solo números impares, evitando la necesidad de validar con el operador módulo.

```python
# Ejemplo ultra corto con for
limite = int(input("Ingresa el límite: "))
for i in range(1, limite + 1, 2):
    print(f"{i} es impar")
```

**⚙️ Comentario de funcionamiento:** `range(1, limite+1, 2)` genera 1, 3, 5, 7... hasta el límite, por lo que cada valor generado ya es impar por construcción.

---

## 8. Tablas de multiplicar

### 8.1 Todas las tablas del 1 al 10 (bucles anidados)

**📌 Enunciado:** Mostrar las tablas de multiplicar del 1 al 10, cada una completa del 1 al 10.

**💡 Explicación / Definición:** Un **bucle anidado** es un bucle dentro de otro. El bucle externo (`i`) controla qué tabla se muestra, y el bucle interno (`j`) controla los multiplicadores del 1 al 10 para esa tabla.

```python
# El primer bucle va del 1 al 10 (las tablas)
for i in range(1, 11):
    print(f"\n=== TABLA DEL {i} ===") # Título para separar cada tabla
    
    # El segundo bucle va del 1 al 10 (los multiplicadores)
    for j in range(1, 11):
        resultado = i * j
        print(f"{i} x {j} = {resultado}")
```

**⚙️ Comentario de funcionamiento:** Por cada valor de `i` (1 a 10), el bucle interno recorre completamente `j` (1 a 10) antes de que `i` avance al siguiente número, generando así las 10 tablas completas en orden.

---

### 8.2 Tabla específica elegida por el usuario

**📌 Enunciado:** Mostrar solo la tabla de multiplicar que el usuario indique.

```python
# Pedimos al usuario el número de la tabla que desea ver
numero_tabla = int(input("¿Qué tabla de multiplicar quieres ver?: "))

print(f"\n=== Mostrando la tabla del {numero_tabla} ===")

# Un solo bucle que va del 1 al 10
for i in range(1, 11):
    resultado = numero_tabla * i
    print(f"{numero_tabla} x {i} = {resultado}")
```

**⚙️ Comentario de funcionamiento:** Al fijar `numero_tabla` como uno de los factores, ya no se necesita bucle anidado: un solo `for` de 1 a 10 basta para generar la tabla completa de ese número.

---

### 8.3 Tabla con rango de multiplicadores personalizado

**📌 Enunciado:** Igual al anterior, pero el usuario también decide hasta qué número multiplicar.

```python
# Variación rápida
tabla = int(input("¿Qué tabla quieres?: "))
hasta = int(input("¿Hasta qué número quieres multiplicar?: "))

for i in range(1, hasta + 1):
    print(f"{tabla} x {i} = {tabla * i}")
```

**⚙️ Comentario de funcionamiento:** El límite superior del bucle ahora depende de la variable `hasta` ingresada por el usuario, en vez de estar fijo en 10, dando mayor flexibilidad al ejercicio.

---

## 9. Números primos (Fuerza bruta, función all() y bucle for-else)

### 9.1 Primos hasta 100 (método de fuerza bruta)

**📌 Enunciado:** Encontrar todos los números primos entre 2 y 100.

**💡 Explicación / Definición:** Un número primo es aquel que solo es divisible entre 1 y sí mismo. La estrategia de "fuerza bruta" consiste en, para cada número, probar si algún valor menor lo divide exactamente; si se encuentra un divisor, deja de ser primo. La bandera `es_primo` (booleana) se usa para recordar ese estado dentro del bucle.

```python
print("=== NÚMEROS PRIMOS HASTA EL 100 ===")

# Recorremos los números del 2 al 100 (el 1 no es primo)
for num in range(2, 101):
    es_primo = True  # Asumimos que el número es primo inicialmente
    
    # Buscamos si tiene algún divisor entre 2 y el número anterior a él
    for i in range(2, num):
        if num % i == 0:
            es_primo = False  # Encontramos un divisor, ya no es primo
            break             # Rompemos el bucle interno para ahorrar tiempo
            
    # Si ningún número lo dividió de forma exacta, es primo
    if es_primo:
        print(num, end=" ")
```

**⚙️ Comentario de funcionamiento:** Para cada `num`, el bucle interno prueba divisores desde 2 hasta `num-1`; en cuanto encuentra uno que divide exacto (`num % i == 0`), marca `es_primo = False` y corta el bucle interno con `break` (no tiene sentido seguir probando). Si el bucle interno termina sin encontrar divisores, `num` es primo.

---

### 9.2 Primos hasta un límite ingresado por el usuario

```python
# Pedimos el número límite al usuario
limite = int(input("¿Hasta qué número quieres buscar números primos?: "))

print(f"\n=== Números primos encontrados hasta el {limite} ===")

for num in range(2, limite + 1):
    es_primo = True
    
    for i in range(2, num):
        if num % i == 0:
            es_primo = False
            break
            
    if es_primo:
        print(num, end=" ")
```

**⚙️ Comentario de funcionamiento:** Misma lógica de fuerza bruta del ejercicio 8.1, pero el límite superior de búsqueda ahora es dinámico según lo que escriba el usuario.

---

### 9.3 Primos del 1 al 100 usando la función Pythonica all() y comprensión generadora

**📌 Enunciado:** Generar todos los números primos del 2 al 100 utilizando la función integrada `all()` con una expresión generadora, evitando el uso de variables bandera manuales (`es_primo = True`) y sentencias `break`.

**💡 Explicación / Definición:** La función `all(iterable)` devuelve `True` si **todos** los elementos dentro del iterable son evaluados como verdaderos. 
Para comprobar si un número `n` es primo:
- Evaluamos si `n % d != 0` (el residuo no es cero) para todos los posibles divisores `d` en el rango `range(2, n)`.
- Si ningún número divide a `n`, todas las comparaciones dan `True`, por lo que `all(...)` devuelve `True` y el número es primo.
- Si existe al menos un divisor exacto (`n % d == 0`), esa comparación da `False`, y `all()` se interrumpe de inmediato (*short-circuit evaluation*), devolviendo `False`.

**Diferenciación didáctica frente al método tradicional:**
- **Método clásico (for con bandera):** Requiere inicializar una variable booleana, un bucle interno explícito, un condicional interno con `break` y otro condicional externo (unas 10-12 líneas).
- **Método con all():** Expresa la definición matemática directa del número primo en una sola línea declarativa, siendo altamente idiomático en Python (*Pythonic code*).

```python
# ================================
# PRIMOS usando all()
# ================================

print("--- NÚMEROS PRIMOS DEL 1 AL 100 (con all) ---")

for n in range(2, 101):
    if all(n % d != 0 for d in range(2, n)):
        print(n, end=" ")

print("\n")
```

**⚙️ Comentario de funcionamiento:** Por cada `n` de 2 a 100, la expresión generadora evalúa los restos de división de forma perezosa (*lazy evaluation*). Tan pronto como un divisor produce residuo cero, `all()` suspende la comprobación y devuelve `False`. Solo si el generador agota todo el rango sin encontrar residuos cero, se ejecuta el `print(n, end=" ")` imprimiendo los primos en una sola línea continua.

---

### 9.4 Primos hasta un límite ingresado por el usuario usando all()

**📌 Enunciado:** Solicitar al usuario un número entero límite por teclado y mostrar todos los números primos existentes hasta dicho número utilizando la técnica declarativa con `all()`.

**💡 Explicación / Definición:** Combina la entrada de datos interactiva mediante `input()` (convertido a entero con `int()`) con la verificación funcional de primalidad usando `all()`. Al evaluar el rango hasta `num`, se obtienen de manera ágil todos los primos en el intervalo abierto $[2, num)$.

```python
# ================================
# PRIMOS hasta número ingresado con all()
# ================================

print("--- PRIMOS HASTA NÚMERO INGRESADO (con all) ---")

num = int(input("Ingresa el número límite: "))

for n in range(2, num):
    if all(n % d != 0 for d in range(2, n)):
        print(n, end=" ")

print("\n")
```

**⚙️ Comentario de funcionamiento:** El script captura el entero ingresado por el usuario (por ejemplo, `50`), establece el rango de búsqueda de 2 a 49, e imprime en pantalla todos los primos dentro de ese intervalo utilizando la expresión generadora optimizada con `all()`.

---

### 9.5 Primos con for-else (método corto)

**📌 Enunciado:** Repetir la búsqueda de primos usando la cláusula `else` asociada a un `for`, en vez de una variable bandera.

**💡 Explicación / Definición:** En Python, un bucle `for` puede tener un bloque `else` que se ejecuta **solo si el bucle terminó completo sin ejecutar un `break`**. Esto permite prescindir de la variable `es_primo`.

```python
limite = int(input("Ingresa el límite (método corto): "))

for num in range(2, limite + 1):
    for i in range(2, num):
        if num % i == 0:
            break  # Si encuentra divisor, rompe el bucle y NO va al else
    else:
        # Solo se ejecuta si el bucle 'for i' terminó sin encontrar divisores
        print(num, end=" ")
```

**⚙️ Comentario de funcionamiento:** Si el bucle interno (`for i`) encuentra un divisor exacto, ejecuta `break` y por lo tanto **se salta** el `else`; si el bucle interno termina "de forma natural" (recorrió todos los valores sin romperse), el `else` se dispara y confirma que `num` es primo.

---

## 10. Detección, Clasificación y Predicción de Secuencias Numéricas (Aritméticas y Geométricas)

### 10.1 Predicción del siguiente número por razón fija explícita

**📌 Enunciado:** Dada una lista con una secuencia de números que crecen multiplicándose por un factor constante de 3, obtener el último valor de la serie, predecir el siguiente término y mostrar el resultado en consola.

**💡 Explicación / Definición:** En Python, las listas admiten **indexación negativa**, donde el índice `[-1]` hace referencia directa al último elemento de la colección sin necesidad de calcular previamente su tamaño con `len()`. Si conocemos el patrón de variación explícito (en este caso, una progresión geométrica de razón 3), simplemente multiplicamos dicho último elemento por el factor para predecir el término venidero.

```python
# ================================
# 1. SIGUIENTE NÚMERO (Multiplicando por 3)
# ================================

print("--- SIGUIENTE x3 ---")

numeros = [3, 9, 27, 81, 243, 729]
siguiente = numeros[-1] * 3

print("El siguiente número es:", siguiente)
print("\n")
```

**⚙️ Comentario de funcionamiento:** La lista contiene 6 números. `numeros[-1]` extrae el valor `729`. Al multiplicarlo por `3`, la variable `siguiente` almacena `2187`, imprimiendo el resultado exacto en consola.

---

### 10.2 Detección automática de la razón geométrica

**📌 Enunciado:** Analizar una lista numérica que sigue una progresión geométrica, deducir programáticamente la razón entre sus dos primeros términos sin fijar el número en el código, y calcular el siguiente valor de la lista.

**💡 Explicación / Definición:** En una **progresión geométrica**, cada término se obtiene multiplicando el anterior por una constante llamada **razón ($r$)**. Por definición:
$$r = \frac{a_2}{a_1} = \frac{\text{numeros}[1]}{\text{numeros}[0]}$$
Al calcular la razón dividiendo el segundo término entre el primero, el algoritmo detecta la tasa de crecimiento de forma dinámica, permitiendo que el mismo código funcione para cualquier secuencia geométrica independientemente del factor utilizado (sea 2, 3, 5 o 10).

```python
# ================================
# 2. SIGUIENTE NÚMERO (Detectando la razón automáticamente)
# ================================

print("--- SIGUIENTE DETECTANDO RAZÓN ---")

numeros = [3, 9, 27, 81, 243, 729]
razon = numeros[1] / numeros[0]
siguiente = numeros[-1] * razon

print("Razón detectada:", razon)
print("El siguiente número es:", siguiente)
print("\n")
```

**⚙️ Comentario de funcionamiento:** Python calcula `9 / 3 = 3.0` y almacena `razon = 3.0`. Luego multiplica el último término `729 * 3.0`, obteniendo `2187.0`. De este modo, si la lista cambiara a `[2, 4, 8, 16]`, el código detectaría automáticamente la razón `2.0` y predeciría `32.0` sin modificar una sola línea de código.

---

### 10.3 Clasificación automática de patrones: Progresión Aritmética vs Progresión Geométrica usando diferencias, razones y set()

**📌 Enunciado:** Crear un algoritmo capaz de inspeccionar todos los elementos consecutivos de una lista y clasificar automáticamente si la serie corresponde a una **progresión aritmética** (suma constante), a una **progresión geométrica** (multiplicación constante) o a una secuencia no lineal / indefinida, proyectando el siguiente término en base al patrón identificado.

**💡 Explicación / Definición:**
- **Progresión Aritmética:** La diferencia entre términos adyacentes es constante: $d = a_{i+1} - a_i$.
- **Progresión Geométrica:** El cociente entre términos adyacentes es constante: $r = \frac{a_{i+1}}{a_i}$.

**Técnica de validación con comprensión de listas y conjuntos `set()`:**
1. Mediante una comprensión de listas `[numeros[i+1] - numeros[i] for i in range(len(numeros)-1)]`, se calculan todas las diferencias sucesivas.
2. La función `set()` convierte esa lista en un conjunto eliminando todos los valores duplicados.
3. Si la longitud del conjunto es `1` (`len(set(diferencias)) == 1`), significa que **todas** las diferencias de la secuencia son idénticas, garantizando matemáticamente que es una progresión aritmética.
4. Se aplica la misma lógica para las razones sucesivas: si `len(set(razones)) == 1`, es una progresión geométrica.

```python
# ================================
# 3. SIGUIENTE NÚMERO (Detectando si es aritmética o geométrica)
# ================================

print("--- SIGUIENTE ARITMÉTICA O GEOMÉTRICA ---")

numeros = [3, 9, 27, 81, 243, 729]

# Diferencias para aritmética
diferencias = [numeros[i+1] - numeros[i] for i in range(len(numeros)-1)]
es_aritmetica = len(set(diferencias)) == 1

# Razones para geométrica
razones = [numeros[i+1] / numeros[i] for i in range(len(numeros)-1)]
es_geometrica = len(set(razones)) == 1

if es_aritmetica:
    siguiente = numeros[-1] + diferencias[0]
    print("Secuencia aritmética → siguiente:", siguiente)

elif es_geometrica:
    siguiente = numeros[-1] * razones[0]
    print("Secuencia geométrica → siguiente:", siguiente)

else:
    print("La secuencia no es aritmética ni geométrica.")

print("\n")
```

**⚙️ Comentario de funcionamiento:** 
Para la lista `[3, 9, 27, 81, 243, 729]`:
- Las diferencias son `[6, 18, 54, 162, 486]`. `set(diferencias)` contiene 5 valores distintos, por lo que `len(set(diferencias)) == 1` resulta `False`.
- Las razones son `[3.0, 3.0, 3.0, 3.0, 3.0]`. `set(razones)` contiene un único elemento `{3.0}`, por lo que `len(set(razones)) == 1` resulta `True`.
- El flujo entra en la rama `elif`, multiplica el último elemento `729 * 3.0` y anuncia: `"Secuencia geométrica → siguiente: 2187.0"`.

---

### 10.4 Algoritmo integral de predicción: Comparativa didáctica de 3 métodos con explicación razonada

**📌 Enunciado:** Consolidar en un solo script didáctico los tres enfoques de resolución (patrón explícito, detección implícita y clasificación automática con explicación en lenguaje natural) sobre una misma serie de datos.

**💡 Explicación / Definición:** Este ejercicio integra y contrasta los 3 niveles de madurez algorítmica:
1. **Nivel 1 (Patrón explícito):** Rápido pero rígido, asume a priori la regla de formación.
2. **Nivel 2 (Detección local):** Flexible pero vulnerable si los dos primeros términos no representan a toda la lista.
3. **Nivel 3 (Validación global y explicabilidad):** Robusto y analítico; audita la totalidad de la lista antes de emitir un diagnóstico y redacta una conclusión argumentada matemáticamente.

```python
# ==========================================================
# SIGUIENTE NÚMERO: 3 MÉTODOS CON SENTIDO Y EXPLICABILIDAD
# ==========================================================

print("--- SIGUIENTE NÚMERO: 3 MÉTODOS CON SENTIDO ---")

numeros = [3, 9, 27, 81, 243, 729]

# 1. Multiplicando por 3 (patrón explícito)
siguiente_1 = numeros[-1] * 3
print("Método 1 → Multiplicar por 3:")
print(f"El último número es {numeros[-1]}, lo multiplico por 3 → {siguiente_1}\n")

# 2. Detectando la razón geométrica (patrón implícito)
razon = numeros[1] / numeros[0]
siguiente_2 = numeros[-1] * razon
print("Método 2 → Detectando la razón geométrica:")
print(f"La razón entre cada número es {razon}, por eso el siguiente es {numeros[-1]} × {razon} = {siguiente_2}\n")

# 3. Detectando si es aritmética o geométrica (clasificación del patrón)
diferencias = [numeros[i+1] - numeros[i] for i in range(len(numeros)-1)]
razones = [numeros[i+1] / numeros[i] for i in range(len(numeros)-1)]

es_aritmetica = len(set(diferencias)) == 1
es_geometrica = len(set(razones)) == 1

if es_aritmetica:
    siguiente_3 = numeros[-1] + diferencias[0]
    tipo = "Aritmética"
    explicacion = f"La diferencia constante es {diferencias[0]}, por eso el siguiente es {numeros[-1]} + {diferencias[0]} = {siguiente_3}"

elif es_geometrica:
    siguiente_3 = numeros[-1] * razones[0]
    tipo = "Geométrica"
    explicacion = f"La razón constante es {razones[0]}, por eso el siguiente es {numeros[-1]} × {razones[0]} = {siguiente_3}"

else:
    siguiente_3 = None
    tipo = "Indefinida"
    explicacion = "La secuencia no sigue un patrón aritmético ni geométrico."

print(f"Método 3 → Clasificación del patrón ({tipo}):")
print(explicacion)
print("\n")
```

**⚙️ Comentario de funcionamiento:** El script ejecuta secuencialmente los tres métodos:
1. Imprime el cálculo directo ($729 \times 3 = 2187$).
2. Imprime el cálculo basado en la división de los primeros dos valores ($729 \times 3.0 = 2187.0$).
3. Realiza la comprobación exhaustiva sobre todos los pares adyacentes, concluye que es una progresión Geométrica e imprime la justificación formal indicando que la razón constante es `3.0`.

---

## 11. Serie de Fibonacci

### 11.1 Fibonacci con cantidad fija de términos

**📌 Enunciado:** Mostrar los primeros 10 términos de la serie de Fibonacci.

**💡 Explicación / Definición:** La serie de Fibonacci comienza en 0 y 1, y cada término siguiente es la suma de los dos anteriores. La asignación múltiple `a, b = b, a + b` es una característica de Python que permite actualizar ambas variables **al mismo tiempo**, sin necesitar una variable temporal auxiliar.

```python
# Definimos cuántos números queremos mostrar
limite_fijo = 10

# Inicializamos los dos primeros números de la serie
a = 0
b = 1

print("=== FIBONACCI (PRIMEROS 10 TÉRMINOS) ===")

# Usamos el for para repetir el proceso la cantidad de veces exacta
for _ in range(limite_fijo):
    print(a, end=" ")
    
    # Truco de Python: Actualizamos ambos valores al mismo tiempo
    # 'a' toma el valor de 'b', y 'b' toma la suma de ambos (el nuevo número)
    a, b = b, a + b
```

**⚙️ Comentario de funcionamiento:** El guion bajo `_` como variable del `for` indica que no nos interesa su valor (solo se usa para repetir 10 veces). En cada vuelta se imprime `a` (el término actual) y luego se recalculan `a` y `b` para la siguiente iteración.

---

### 11.2 Fibonacci con cantidad de términos ingresada por el usuario

```python
# Pedimos la cantidad de términos al usuario
cant_terminos = int(input("¿Cuántos números de la serie de Fibonacci quieres ver?: "))

a = 0
b = 1

print(f"\n=== MUESTRAN CO PRINCIPIO DE LA SERIE ({cant_terminos} TÉRMINOS) ===")

# El bucle for se adaptará al número que escribió el usuario
for _ in range(cant_terminos):
    print(a, end=" ")
    a, b = b, a + b
```

**⚙️ Comentario de funcionamiento:** Idéntico al 9.1, pero `limite_fijo` se reemplaza por `cant_terminos`, un valor dinámico proporcionado por el usuario.

---

## 12. Factorial y permutaciones

### 12.1 Factorial manual con bucle for (n=5)

**📌 Enunciado:** Calcular el factorial de un número (`n!`) usando un bucle, sin funciones predefinidas.

**💡 Explicación / Definición:** El factorial de `n` es el producto de todos los enteros positivos desde 1 hasta `n` (ej.: `5! = 1×2×3×4×5 = 120`). El operador `*=` multiplica la variable por el valor de la derecha y guarda el resultado en la misma variable (equivalente a `factorial = factorial * i`).

```python
# El factorial se calcula multiplicando todos los números desde 1 hasta n.
n = 5
factorial = 1

for i in range(1, n + 1):
    factorial *= i

print(f"El factorial de {n} es: {factorial}")
```

**⚙️ Comentario de funcionamiento:** `factorial` se inicializa en 1 (elemento neutro de la multiplicación) y se va multiplicando por cada número de 1 a `n`, acumulando el resultado final.

---

### 12.2 Factorial manual con bucle for (n=6, versión comentada)

```python
# EJERCICIO: Calcular el factorial de un número usando un bucle for

n = 6
factorial = 1

for i in range(1, n + 1):
    factorial *= i

print(f"El factorial de {n} es: {factorial}")

# ¿CÓMO FUNCIONA?
# El factorial se obtiene multiplicando todos los números desde 1 hasta n.
# El bucle for recorre: 1, 2, 3, 4, 5, 6
# En cada vuelta, factorial = factorial * i
# Resultado final: 720
```

**⚙️ Comentario de funcionamiento:** Misma lógica del ejercicio 10.1 aplicada a `n = 6`; el resultado esperado es `720` (1×2×3×4×5×6).

---

### 12.3 Permutaciones de tres números con bucles anidados

**📌 Enunciado:** Generar todas las combinaciones posibles ordenando tres números distintos, sin repetir ninguno en la misma permutación.

**💡 Explicación / Definición:** Se usan **tres bucles anidados** (`i`, `j`, `k`), cada uno recorriendo los índices de la lista. Las condiciones `if j != i` y `if k != i and k != j` garantizan que no se repita la misma posición en una misma permutación.

```python
# EJERCICIO: Generar todas las permutaciones posibles de tres números usando bucles

numeros = [1, 2, 3]

for i in range(len(numeros)):
    for j in range(len(numeros)):
        if j != i:
            for k in range(len(numeros)):
                if k != i and k != j:
                    print(numeros[i], numeros[j], numeros[k])

# ¿CÓMO FUNCIONA?
# Se usan tres bucles para elegir posiciones distintas.
# i, j y k representan índices diferentes.
# Las condiciones evitan repetir el mismo número en la misma permutación.
# Se generan las 6 permutaciones posibles:
# 1 2 3
# 1 3 2
# 2 1 3
# 2 3 1
# 3 1 2
# 3 2 1
```

**⚙️ Comentario de funcionamiento:** `len(numeros)` es 3, por lo que `i`, `j` y `k` recorren los índices 0, 1 y 2. Cada combinación válida de índices distintos entre sí produce una permutación única de los tres números, dando un total de 3! = 6 resultados.

---

### 12.4 Permutación P(n, r) sin usar factorial

**📌 Enunciado:** Calcular la permutación P(n, r) —es decir, de cuántas formas se pueden ordenar `r` elementos elegidos de un total de `n`— usando un bucle descendente en lugar de la fórmula con factoriales.

**💡 Explicación / Definición:** La fórmula matemática es `P(n, r) = n × (n-1) × (n-2) × ... × (n-r+1)`. `range(n, n - r, -1)` genera una secuencia descendente con `r` valores exactos, evitando calcular factoriales completos (más costoso computacionalmente para números grandes).

```python
# EJERCICIO: Calcular la permutación P(n, r) usando un bucle sin factorial

n = 7
r = 4

resultado = 1
for i in range(n, n - r, -1):
    resultado *= i

print(f"P({n}, {r}) = {resultado}")

# ¿CÓMO FUNCIONA?
# La fórmula P(n, r) = n * (n-1) * (n-2) ... (n-r+1)
# El bucle recorre: 7, 6, 5, 4  (cuatro valores porque r = 4)
# Multiplica cada uno para obtener la permutación.
# Resultado final: 840
```

**⚙️ Comentario de funcionamiento:** Con `n=7` y `r=4`, `range(7, 3, -1)` genera 7, 6, 5, 4; multiplicando estos cuatro valores se obtiene `840`, equivalente a `7! / (7-4)!` pero sin calcular los factoriales completos.

---

### 12.5 Factorial con la librería math

**📌 Enunciado:** Calcular un factorial utilizando la función predefinida de Python en lugar de un bucle manual.

**💡 Explicación / Definición:** El módulo `math` de la biblioteca estándar incluye `math.factorial(n)`, una función optimizada que evita tener que programar el bucle manualmente.

```python
import math

# Ejemplo de factorial
n = 5
resultado = math.factorial(n)
print(f"El factorial de {n} es: {resultado}")
```

**⚙️ Comentario de funcionamiento:** `math.factorial(5)` devuelve directamente `120`, el mismo resultado que el bucle manual del ejercicio 10.1, pero con una sola línea de código.

---

### 12.6 Permutación P(n, r) con la librería math

**📌 Enunciado:** Calcular P(n, r) utilizando `math.factorial` en lugar de un bucle.

**💡 Explicación / Definición:** La fórmula `P(n, r) = n! / (n-r)!` se traduce directamente a código usando divisón entera (`//`) para obtener un resultado sin decimales.

```python
import math

# Permutación P(n, r)
n = 5
r = 3

permutacion = math.factorial(n) // math.factorial(n - r)
print(f"P({n}, {r}) = {permutacion}")
```

**⚙️ Comentario de funcionamiento:** Se calcula `5! = 120` y `(5-3)! = 2! = 2`, y la división entera `120 // 2` da como resultado `60`.

---

### 12.7 Permutaciones con la librería itertools

**📌 Enunciado:** Generar todas las permutaciones posibles de un conjunto de elementos usando una herramienta especializada de Python.

**💡 Explicación / Definición:** El módulo `itertools` ofrece `permutations()`, una función que genera automáticamente todas las combinaciones ordenadas posibles de una lista, sin necesidad de escribir bucles anidados manualmente (como en el ejercicio 10.3).

```python
import itertools

elementos = ['A', 'B', 'C']
perms = list(itertools.permutations(elementos))

print("Permutaciones de A, B, C:")
for p in perms:
    print(p)
```

**⚙️ Comentario de funcionamiento:** `itertools.permutations(elementos)` devuelve un objeto iterador que se convierte en lista con `list()`; cada elemento de esa lista es una tupla que representa un orden distinto de `'A'`, `'B'`, `'C'` (6 permutaciones en total, igual que en el ejercicio 10.3 pero sin bucles manuales).

---

## 13. Funciones (def)

### 13.1 Función sin parámetros: calcular el cuadrado de un número fijo

**📌 Enunciado:** Crear una función que calcule el cuadrado de un número definido dentro de ella misma (sin recibir parámetros).

**💡 Explicación / Definición:** Una **función** se define con la palabra clave `def`, seguida del nombre y paréntesis. El código dentro de ella no se ejecuta hasta que la función es **llamada** explícitamente (`calcular_cuadrado()`). Al no recibir parámetros, todos los datos que usa están definidos dentro de su propio cuerpo.

```python
# EJERCICIO: Crear una función que calcule el cuadrado de un número fijo

def calcular_cuadrado():
    numero = 5
    resultado = numero * numero
    print(f"El cuadrado de {numero} es: {resultado}")

calcular_cuadrado()

# ¿CÓMO FUNCIONA?
# La función calcular_cuadrado NO recibe parámetros.
# Dentro de ella se define el número 5.
# Luego se multiplica 5 * 5 y se imprime el resultado.
# La función se ejecuta cuando llamamos: calcular_cuadrado()
```

**⚙️ Comentario de funcionamiento:** Al llamar `calcular_cuadrado()`, Python ejecuta todo el bloque indentado bajo `def`: asigna `numero = 5`, calcula `5 * 5` y lo imprime. Si la función nunca se llama, su cuerpo nunca se ejecuta, aunque esté definida.

---

### 13.2 Función que recibe datos por input y devuelve el factorial

**📌 Enunciado:** Crear una función que solicite un número al usuario mediante `input()` y calcule e imprima su factorial.

**💡 Explicación / Definición:** A diferencia del ejercicio 11.1, aquí el dato que usa la función no está fijo en el código, sino que se captura interactivamente **dentro** de la propia función mediante `input()`. Esto combina el concepto de función con el de entrada de datos y bucles ya vistos en la sección de factorial.

```python
# EJERCICIO: Crear una función que reciba un número por input y devuelva su factorial

def factorial_input():
    n = int(input("Escribe un número para calcular su factorial: "))
    factorial = 1

    for i in range(1, n + 1):
        factorial *= i

    print(f"El factorial de {n} es: {factorial}")

factorial_input()

# ¿CÓMO FUNCIONA?
# La función factorial_input pide un número al usuario usando input().
# Convierte ese valor a entero con int().
# Luego usa un bucle for para multiplicar todos los números desde 1 hasta n.
# Finalmente imprime el resultado.
# La función se ejecuta cuando llamamos: factorial_input()
```

**⚙️ Comentario de funcionamiento:** Al llamar `factorial_input()`, la función pausa la ejecución esperando que el usuario escriba un número, lo convierte con `int()`, y reutiliza la misma lógica del bucle `for` con `*=` vista en el ejercicio 10.1, pero ahora encapsulada dentro de una función reutilizable.

---

## 14. Visualización de datos con matplotlib (gráficos individuales)

### 14.1 Gráfico de líneas: tendencia de ventas mensuales

**📌 Enunciado:** Crear un gráfico de líneas que muestre la evolución de las ventas a lo largo de 5 meses.

**💡 Explicación / Definición:** `plt.plot(x, y)` dibuja una línea que conecta los puntos definidos por dos listas paralelas: una de valores en el eje X (meses) y otra en el eje Y (ventas). El parámetro `marker='o'` añade un punto circular visible en cada dato. `plt.grid()` dibuja una cuadrícula de fondo para facilitar la lectura de valores. Este tipo de gráfico es ideal para mostrar **tendencias a lo largo del tiempo**.

```python
# EJERCICIO: Crear un gráfico de líneas para mostrar la tendencia de ventas mensuales

import matplotlib.pyplot as plt

meses = [1, 2, 3, 4, 5]
ventas = [10, 15, 20, 18, 25]

plt.plot(meses, ventas, marker='o')
plt.title("Ventas Mensuales")
plt.xlabel("Mes")
plt.ylabel("Ventas")
plt.grid()
plt.show()

# ¿CÓMO FUNCIONA?
# plt.plot() dibuja una línea conectando los puntos.
# marker='o' coloca un punto en cada valor.
# Se usa para mostrar tendencias en el tiempo.
```

**⚙️ Comentario de funcionamiento:** Cada posición de la lista `meses` se empareja con la posición correspondiente de `ventas` (mes 1 → 10, mes 2 → 15, etc.); `plt.plot()` traza una línea recta entre esos puntos consecutivos, y `plt.show()` abre la ventana con el gráfico renderizado.

> ℹ️ **Nota:** este ejercicio aparece duplicado de forma idéntica en el material original (mismo código, misma explicación); se conserva documentado una sola vez para evitar redundancia.

---

### 14.2 Gráfico de barras: ventas por categoría

**📌 Enunciado:** Comparar visualmente las ventas obtenidas por tres categorías distintas (A, B, C).

**💡 Explicación / Definición:** `plt.bar(categorias, valores)` dibuja una barra vertical por cada categoría, cuya altura representa el valor asociado. Los gráficos de barras son ideales para **comparar magnitudes entre grupos discretos** (a diferencia de las líneas, que muestran continuidad/tendencia).

```python
# EJERCICIO: Crear un gráfico de barras para comparar ventas por categoría

import matplotlib.pyplot as plt

categorias = ["A", "B", "C"]
ventas = [30, 45, 20]

plt.bar(categorias, ventas, color='orange')
plt.title("Ventas por Categoría")
plt.xlabel("Categoría")
plt.ylabel("Ventas")
plt.show()

# ¿CÓMO FUNCIONA?
# plt.bar() crea barras verticales.
# Cada barra representa una categoría.
# Se usa para comparar valores entre grupos.
```

**⚙️ Comentario de funcionamiento:** `plt.bar()` asocia cada elemento de `categorias` con su valor correspondiente en `ventas`, dibujando tres barras de distinta altura (30, 45 y 20) coloreadas en naranja.

---

### 14.3 Gráfico de dispersión: relación entre horas estudiadas y nota

**📌 Enunciado:** Visualizar si existe relación entre la cantidad de horas que estudia una persona y la nota obtenida.

**💡 Explicación / Definición:** `plt.scatter(x, y)` dibuja **puntos individuales** (no conectados por líneas) para cada par de valores. Este tipo de gráfico se usa para detectar **correlaciones** entre dos variables numéricas: si los puntos siguen una tendencia ascendente o descendente clara, sugiere una relación entre ambas.

```python
# EJERCICIO: Crear un gráfico de dispersión para ver la relación entre horas estudiadas y nota

import matplotlib.pyplot as plt

horas = [2, 3, 4, 5, 6]
notas = [60, 65, 70, 75, 80]

plt.scatter(horas, notas, color='red')
plt.title("Relación entre horas y nota")
plt.xlabel("Horas estudiadas")
plt.ylabel("Nota")
plt.show()

# ¿CÓMO FUNCIONA?
# plt.scatter() dibuja puntos individuales.
# Sirve para ver correlaciones entre dos variables.
# Aquí se observa que más horas → mejor nota.
```

**⚙️ Comentario de funcionamiento:** Cada punto rojo representa un par `(horas, nota)`; al observar que los puntos ascienden de izquierda a derecha, se puede inferir visualmente una relación positiva entre horas estudiadas y la nota obtenida.

---

### 14.4 Gráfico de pastel: participación de mercado

**📌 Enunciado:** Mostrar qué porcentaje del mercado ocupa cada una de tres marcas.

**💡 Explicación / Definición:** `plt.pie(valores, labels=..., autopct=...)` dibuja un gráfico circular dividido en porciones proporcionales a cada valor. El parámetro `autopct="%1.1f%%"` es un formato de cadena que muestra el porcentaje de cada porción con un decimal, seguido del símbolo `%`. Se usa para representar **proporciones de un total** (que en conjunto suman 100%).

```python
# EJERCICIO: Crear un gráfico de pastel para mostrar participación de mercado

import matplotlib.pyplot as plt

marcas = ["X", "Y", "Z"]
porcentaje = [50, 30, 20]

plt.pie(porcentaje, labels=marcas, autopct="%1.1f%%")
plt.title("Participación de Mercado")
plt.show()

# ¿CÓMO FUNCIONA?
# plt.pie() crea un gráfico circular.
# autopct muestra el porcentaje dentro del pastel.
# Se usa para ver proporciones de un total.
```

**⚙️ Comentario de funcionamiento:** Los valores `[50, 30, 20]` suman 100, por lo que cada porción del pastel ocupa exactamente ese porcentaje del círculo completo; `autopct` calcula y escribe automáticamente el porcentaje dentro de cada sección.

---

### 14.5 Histograma: distribución de edades

**📌 Enunciado:** Analizar cómo se distribuye un conjunto de edades agrupándolas en rangos.

**💡 Explicación / Definición:** `plt.hist(datos, bins=n)` agrupa los valores numéricos en `n` intervalos ("bins" o "cubetas") de igual tamaño y dibuja una barra por cada intervalo, cuya altura representa cuántos datos caen dentro de ese rango. A diferencia de `plt.bar()` (que usa categorías ya definidas), el histograma **construye los rangos automáticamente** a partir de los datos.

```python
# EJERCICIO: Crear un histograma para mostrar la distribución de edades

import matplotlib.pyplot as plt

edades = [20, 22, 25, 30, 30, 32, 35, 40]

plt.hist(edades, bins=5, color='green')
plt.title("Distribución de Edades")
plt.xlabel("Edad")
plt.ylabel("Frecuencia")
plt.show()

# ¿CÓMO FUNCIONA?
# plt.hist() agrupa los valores en rangos (bins).
# Muestra cuántas veces aparece cada rango.
# Se usa para analizar distribuciones.
```

**⚙️ Comentario de funcionamiento:** `bins=5` le indica a matplotlib que divida el rango total de edades (de 20 a 40) en 5 intervalos iguales, y cuenta cuántas edades de la lista `edades` caen dentro de cada intervalo, dibujando una barra verde por cada uno según esa frecuencia.

---

### 14.6 Gráfico avanzado: Diagrama de Pareto 80/20 con doble eje Y (twinx) y línea de umbral acumulada

**📌 Enunciado:** Construir un diagrama de Pareto (regla 80/20) para la facturación de productos empresariales a partir de un `DataFrame` de `pandas`. Visualizar las ventas individuales mediante un gráfico de barras en el eje principal y la curva de porcentaje acumulado mediante una línea con marcadores en un eje secundario derecho (`twinx`), incluyendo una línea de referencia horizontal punteada al 80% y exportando la figura a un archivo de imagen (`.png`).

**💡 Explicación / Definición:** El **Principio de Pareto (Regla del 80/20)** establece que aproximadamente el 80% de los resultados provienen del 20% de las causas (en negocios: el ~80% de la facturación suele concentrarse en un pequeño grupo de productos clave). Para representar esto con rigor visual se combinan técnicas avanzadas de `pandas` y `matplotlib`:
1. **Ordenamiento descendente:** `.sort_values(by="Facturacion", ascending=False)` asegura que los productos de mayor impacto se listen primero de izquierda a derecha.
2. **Suma acumulada (`cumsum()`):** `df["Facturacion"].cumsum()` calcula la suma progresiva de las ventas. Dividida entre la suma total y multiplicada por 100, genera el porcentaje acumulado (de 0% a 100%).
3. **Doble eje Y con `ax1.twinx()`:** Crea un segundo eje vertical (`ax2`) que comparte el mismo eje horizontal X de productos pero maneja su propia escala numérica a la derecha. Esto permite mostrar al mismo tiempo magnitudes monetarias absolutas (USD en barras) y porcentajes acumulados (0% a 100% en línea) sin que las escalas se distorsionen.
4. **Línea de umbral de decisión (`ax2.axhline(80, ...)`):** Dibuja una línea horizontal de referencia en el 80% con trazo discontinuo (`--`) para identificar inmediatamente los productos prioritarios.
5. **Rotación de etiquetas:** `ax1.tick_params(axis='x', rotation=30)` inclina los nombres de los productos para evitar solapamientos tipográficos.
6. **Exportación a archivo:** `plt.savefig("pareto_facturacion.png")` guarda el gráfico directamente en disco en alta resolución.

```python
# ==========================================================
# DIAGRAMA DE PARETO (80/20) CON DOBLE EJE Y (twinx)
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

df = pd.DataFrame({
    "Producto": ["Software ERP", "Servidores Cloud", "Consultoría IA", "Soporte Anual", "Hardware", "Licencias Office"],
    "Facturacion": [120000, 85000, 62000, 24000, 11000, 4500]
}).sort_values(by="Facturacion", ascending=False)

# Cálculo de porcentaje acumulado
df["Porc_Acumulado"] = (df["Facturacion"].cumsum() / df["Facturacion"].sum()) * 100

fig, ax1 = plt.subplots(figsize=(7, 3.8))
ax1.bar(df["Producto"], df["Facturacion"], color="#2F6D9C")
ax1.set_ylabel("Facturación (USD)", color="#2F6D9C")
ax1.tick_params(axis='x', rotation=30)

# Eje secundario para la línea de Pareto
ax2 = ax1.twinx()
ax2.plot(df["Producto"], df["Porc_Acumulado"], color="#F5C518", marker="o", linewidth=2)
ax2.axhline(80, color="crimson", linestyle="--", alpha=0.7) # Línea umbral 80%
ax2.set_ylabel("% Acumulado", color="#F5C518")

plt.title("Curva de Pareto 80/20 de Facturación")
plt.tight_layout()
plt.savefig("pareto_facturacion.png")
```

**⚙️ Comentario de funcionamiento:**
1. `pandas` crea el DataFrame y lo ordena descendentemente; `Software ERP` ($120,000) y `Servidores Cloud` ($85,000) encabezan la tabla.
2. `df["Porc_Acumulado"]` calcula la acumulación porcentual: el primer producto representa el 39.1%, con el segundo sube al 66.8%, y con `Consultoría IA` ($62,000) supera el 87%, cubriendo más del 80% de toda la facturación con solo la mitad de los productos del portafolio.
3. `ax1.bar()` grafica las columnas azules con la facturación en dólares.
4. `ax1.twinx()` añade el lienzo vertical gemelo a la derecha y `ax2.plot()` traza la curva ascendente amarilla con marcadores circulares.
5. `ax2.axhline(80)` proyecta la línea roja horizontal punteada indicando visualmente el corte del 80%.
6. `plt.savefig("pareto_facturacion.png")` genera y guarda la imagen en el directorio de trabajo.

---

### 14.7 Análisis de series temporales: Suavizado de demanda con Media Móvil (Rolling Window SMA-3) y comparativa de tendencias

**📌 Enunciado:** Analizar una serie temporal de 10 semanas de ventas reales utilizando un `DataFrame` de `pandas`, calcular una media móvil simple de 3 periodos (SMA-3) con una ventana deslizante (`rolling`) para filtrar el ruido aleatorio y graficar ambas curvas en un mismo lienzo contrastando los datos puntuales con la tendencia suavizada, guardando el resultado en un archivo de imagen (`.png`).

**💡 Explicación / Definición:** En la analítica empresarial, los datos cronológicos suelen presentar fluctuaciones bruscas y estacionales a corto plazo. El cálculo de la **media móvil simple (SMA - Simple Moving Average)** es una técnica estadística que suaviza la serie calculando el promedio aritmético de un subconjunto de datos que se desplaza cronológicamente:
1. **Generación con comprensión de listas:** `[f"Sem {i}" for i in range(1, 11)]` genera automáticamente las etiquetas de semanas (`"Sem 1"`, `"Sem 2"`, ..., `"Sem 10"`).
2. **Ventana deslizante (`rolling(window=3)`):** Agrupa los datos en bloques continuos de tamaño 3. Los dos primeros valores de la serie resultarán en `NaN` (no disponible) porque no tienen 3 periodos previos completos para promediar.
3. **Cálculo de la media (`.mean()`):** Promedia los valores dentro de cada ventana. Por ejemplo, para la Semana 3: $(1200 + 1850 + 1400) / 3 = 1483.33$.
4. **Superposición de estilos en Matplotlib:** 
   - La serie real se dibuja con línea punteada (`linestyle=":"`), color neutro (`#8793A8`) y marcadores (`marker="o"`), enfatizando la dispersión de cada semana.
   - La media móvil se dibuja con una línea continua más gruesa (`linewidth=2.5`) y un color verde esmeralda vibrante (`#10B981`), guiando la vista hacia la tendencia subyacente de crecimiento sostenido.
5. **Legibilidad profesional:** `plt.legend()` añade la caja de referencia, `plt.grid(True, linestyle="--", alpha=0.4)` añade cuadrícula semitransparente para orientar la vista, y `plt.savefig("tendencia_media_movil.png")` persiste la gráfica en disco.

```python
# ==========================================================
# ANÁLISIS DE SERIES TEMPORALES Y MEDIA MÓVIL (SMA-3)
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

df_temporal = pd.DataFrame({
    "Semana": [f"Sem {i}" for i in range(1, 11)],
    "Ventas_Reales": [1200, 1850, 1400, 2200, 2100, 2900, 2600, 3400, 3100, 3900]
})

# Cálculo de la media móvil de 3 periodos
df_temporal["Media_Movil_3P"] = df_temporal["Ventas_Reales"].rolling(window=3).mean()

plt.figure(figsize=(7, 3.8))
plt.plot(df_temporal["Semana"], df_temporal["Ventas_Reales"], label="Ventas Reales", marker="o", color="#8793A8", linestyle=":")
plt.plot(df_temporal["Semana"], df_temporal["Media_Movil_3P"], label="Tendencia Suavizada (SMA-3)", color="#10B981", linewidth=2.5)

plt.title("Evolución de Demanda y Suavizado Móvil")
plt.ylabel("Unidades Vendidas")
plt.legend()
plt.grid(True, linestyle="--", alpha=0.4)
plt.tight_layout()
plt.savefig("tendencia_media_movil.png")
```

**⚙️ Comentario de funcionamiento:**
1. Se crea el DataFrame con las 10 semanas y sus valores de ventas reales oscilantes.
2. `rolling(window=3).mean()` calcula la columna `"Media_Movil_3P"`; las semanas 1 y 2 quedan como `NaN`, y a partir de la semana 3 la curva refleja la media de las últimas 3 semanas, neutralizando las caídas abruptas de las semanas 3, 5 y 7.
3. Se crea la figura con tamaño optimizado `(7, 3.8)`.
4. El primer `plt.plot()` grafica las ventas reales en gris con puntos y línea de puntos.
5. El segundo `plt.plot()` superpone la tendencia verde esmeralda destacando el claro vector de crecimiento desde ~1,480 hasta ~3,460 unidades.
6. `plt.legend()` y `plt.grid()` dotan a la gráfica de acabado editorial ejecutivo, y `plt.savefig()` la guarda como `tendencia_media_movil.png`.

---

### 14.8 Pipeline ETL de Cuentas por Cobrar (CxC): Función Heurística (.apply), Agregación (.groupby) y Gráfico Circular Semafórico de Morosidad

**📌 Enunciado:** Construir un pipeline analítico de transformación y visualización para una cartera de cuentas por cobrar (CxC). Definir una función lógica que clasifique las facturas según sus días de atraso en 4 tramos de morosidad, mapear dicha heurística a un `DataFrame` de `pandas` mediante `.apply()`, calcular la exposición monetaria agregada con `.groupby().sum()` y visualizar el riesgo porcentual resultante en un gráfico circular con paleta semafórica de colores.

**💡 Explicación / Definición:** En la gestión financiera corporativa, la cartera vencida se monitorea por "cubos o tramos de envejecimiento" (*aging buckets*). Este ejercicio articula el flujo de datos completo (ETL - Extracción, Transformación y Carga visual):
1. **Función Heurística de negocio:** `categorizar_mora(dias)` utiliza condicionales en cascada para transformar una variable continua (número entero de días) en una dimensión categórica cualitativa de riesgo:
   - $\le 30$ días: Sano / Corriente.
   - $31 - 60$ días: Riesgo Leve.
   - $61 - 90$ días: Riesgo Medio.
   - $> 90$ días: Crítico / Pérdida potencial.
2. **Transformación vectorial con `.apply()`:** En lugar de iterar con un bucle `for` manual sobre las filas del DataFrame, `df_cxc["DiasAtraso"].apply(categorizar_mora)` invoca la función de forma optimizada sobre cada registro de la serie, creando la nueva columna `"Tramo"`.
3. **Agrupación y agregación con `.groupby()`:** `df_cxc.groupby("Tramo")["Monto"].sum()` emula el comportamiento de una consulta SQL `GROUP BY` o una tabla dinámica de Excel: colapsa las facturas individuales y suma el capital expuesto para cada uno de los 4 tramos.
4. **Diseño semafórico de alta interpretabilidad:** Se define una lista explícita de colores hexadecimales `['#28a745', '#ffc107', '#fd7e14', '#dc3545']` correspondiente a la convención universal de semáforos (verde, amarillo, naranja y rojo), comunicando la severidad del riesgo sin necesidad de explicaciones adicionales.

```python
# ==========================================================
# ANÁLISIS DE RIESGO CXC: PIPELINE ETL + GRÁFICO SEMAFÓRICO
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

# 1. Función Heurística
def categorizar_mora(dias):
    if dias <= 30: return "0-30 días (Sano)"
    elif dias <= 60: return "31-60 días (Riesgo Leve)"
    elif dias <= 90: return "61-90 días (Riesgo Medio)"
    return "+90 días (Crítico)"

# 2. Generación de Data Sintética Realista
datos = {
    "Factura": [101, 102, 103, 104, 105, 106, 107, 108, 109, 110], 
    "Monto": [1500, 3200, 800, 4500, 1200, 5000, 300, 950, 4200, 600],
    "DiasAtraso": [5, 45, 12, 110, 25, 65, 80, 5, 95, 40]
}
df_cxc = pd.DataFrame(datos)

# 3. Transformación (ETL)
df_cxc["Tramo"] = df_cxc["DiasAtraso"].apply(categorizar_mora)
resumen = df_cxc.groupby("Tramo")["Monto"].sum()

# 4. Gráfico Analítico
colores = ['#28a745', '#ffc107', '#fd7e14', '#dc3545']
plt.figure(figsize=(6, 4))
plt.pie(resumen, labels=resumen.index, autopct='%1.1f%%', colors=colores, startangle=140)
plt.title("Exposición de Cartera por Tramos de Morosidad")
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. Python compila la función `categorizar_mora()`.
2. Pandas estructura las 10 facturas con montos entre $300 y $5,000, y atrasos que van desde 5 hasta 110 días.
3. El método `.apply()` evalúa cada atraso y asigna el tramo correspondiente en la nueva columna `"Tramo"`.
4. `.groupby("Tramo")["Monto"].sum()` genera una Serie donde el índice son los 4 tramos y los valores son la suma monetaria en dólares de cada tramo (por ejemplo, sumando $4,500 + $4,200 en el tramo crítico de +90 días).
5. `plt.pie()` dibuja el gráfico circular: `resumen.index` provee los textos de las etiquetas, `autopct='%1.1f%%'` calcula el peso relativo de cada tramo en la cartera total, y el ángulo de inicio `startangle=140` orienta las porciones para facilitar la lectura visual.
6. `plt.show()` abre la ventana gráfica mostrando la distribución de riesgo de crédito en tiempo real.

---

### 14.9 Evaluación Crediticia Algorítmica: Gráfico de Dispersión (Scatter Plot) con Frontera de Decisión DTI y Mapeo Categórico (.map)

**📌 Enunciado:** Evaluar solicitudes de crédito mediante el ratio de endeudamiento DTI (*Debt-to-Income*). Construir un `DataFrame` de solicitantes, calcular el porcentaje de ingresos comprometidos en deuda, clasificar algorítmicamente a los clientes como "Aprobado" (DTI $\le 40\%$) o "Rechazado" (DTI $> 40\%$), asignar colores condicionales mediante `.map()` y graficar un diagrama de dispersión que incluya la línea matemática del umbral de riesgo crediticio.

**💡 Explicación / Definición:** En la industria bancaria y FinTech, el ratio **DTI (Debt-to-Income)** evalúa la solvencia del prestatario:
$$\text{Ratio DTI} = \left(\frac{\text{Deuda Mensual}}{\text{Ingreso Mensual}}\right) \times 100$$
Este ejercicio ilustra cómo representar visualmente modelos de clasificación binaria:
1. **Clasificación condicional:** `["Aprobado" if dti <= 40 else "Rechazado" for dti in df["Ratio_DTI"]]` asigna la etiqueta categórica a cada solicitante.
2. **Mapeo de colores con `.map()`:** `df["Estado"].map({"Aprobado": "#28a745", "Rechazado": "#dc3545"})` sustituye instantáneamente las categorías de texto por sus códigos de color (verde para aprobado, rojo para rechazado) de forma vectorizada.
3. **Puntos estilizados con `plt.scatter()`:** El parámetro `s=150` define el tamaño de las burbujas, `alpha=0.8` proporciona ligera transparencia para evitar empastados y `edgecolors="black"` añade un borde nítido alrededor de cada punto.
4. **Frontera de decisión analítica:** La recta de umbral $Y = 0.40 \times X$ representa el límite máximo de deuda tolerable para cada nivel de ingreso; todos los puntos situados por debajo de la línea discontinua (`k--`) resultan aprobados, mientras que los ubicados por encima quedan automáticamente en zona de rechazo.

```python
# ==========================================================
# EVALUACIÓN CREDITICIA ALGORÍTMICA (DTI) Y FRONTERA LINEAL
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

# 1. Datos de Solicitantes
df = pd.DataFrame({
    "Cliente": ["Ana", "Luis", "Carlos", "Marta", "Jorge", "Sofía", "Pedro", "Lucía"],
    "IngresoMensual": [5000, 3200, 8000, 4500, 2500, 6000, 3800, 5200],
    "DeudaMensual": [1500, 1800, 2000, 2200, 400, 3500, 1100, 1000]
})

# 2. Motor de Cálculo Financiero
df["Ratio_DTI"] = (df["DeudaMensual"] / df["IngresoMensual"]) * 100
df["Estado"] = ["Aprobado" if dti <= 40 else "Rechazado" for dti in df["Ratio_DTI"]]

# 3. Mapeo Visual
colores = df["Estado"].map({"Aprobado": "#28a745", "Rechazado": "#dc3545"})
plt.figure(figsize=(7, 4))
plt.scatter(df["IngresoMensual"], df["DeudaMensual"], c=colores, s=150, alpha=0.8, edgecolors="black")

# Línea de Umbral de Riesgo (40%)
x_vals = [2000, 8000]
y_vals = [2000 * 0.40, 8000 * 0.40]
plt.plot(x_vals, y_vals, 'k--', label="Umbral DTI (40%)")

plt.title("Evaluación Crediticia Algorítmica (DTI)")
plt.xlabel("Ingreso Mensual ($)")
plt.ylabel("Deuda Mensual Actual ($)")
plt.legend()
plt.grid(True, linestyle=":", alpha=0.6)
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. Pandas crea la tabla con 8 clientes con ingresos entre $2,500 y $8,000 y deudas entre $400 y $3,500.
2. La columna `"Ratio_DTI"` calcula los porcentajes: Ana tiene un DTI de 30% (Aprobada), Luis tiene 56.25% (Rechazado), Sofía tiene 58.33% (Rechazada), mientras que Lucía tiene 19.23% (Aprobada).
3. `.map()` traduce las etiquetas a verdes y rojos.
4. `plt.scatter()` ubica a cada cliente en el plano cartesiano (Ingreso en eje X vs Deuda en eje Y).
5. `plt.plot(x_vals, y_vals, 'k--')` traza la recta divisoria con pendiente $0.40$, permitiendo verificar de un vistazo cómo la regla matemática separa limpiamente los puntos verdes de los rojos.

---

### 14.10 Analítica de Experiencia del Cliente: Gráfico de Dona (Donut Chart) con wedgeprops, Cálculo de NPS e Inyección Central de KPI (plt.text)

**📌 Enunciado:** A partir de una muestra de 20 calificaciones de satisfacción en escala de 0 a 10, calcular el indicador gerencial Net Promoter Score (NPS), clasificar las respuestas en Promotores, Pasivos y Detractores, construir un gráfico de dona moderno utilizando el parámetro `wedgeprops` y superponer en el centro del anillo el valor del KPI en texto destacado.

**💡 Explicación / Definición:** El **Net Promoter Score (NPS)** es el estándar global para medir la lealtad de clientes:
- **Promotores (calificaciones 9-10):** Clientes leales que recomiendan la marca.
- **Pasivos (calificaciones 7-8):** Clientes satisfechos pero neutrales o vulnerables a la competencia.
- **Detractores (calificaciones 0-6):** Clientes insatisfechos que pueden generar comentarios adversos.

$$\text{NPS} = \left(\frac{\text{Promotores} - \text{Detractores}}{\text{Total de Encuestados}}\right) \times 100$$
El resultado oscila entre $-100$ y $+100$.

**Técnicas avanzadas de visualización:**
1. **Gráfico de dona nativo con `wedgeprops={'width': 0.4}`:** En lugar de crear trucos visuales superponiendo parches circulares blancos (`plt.Circle`), matplotlib permite vaciar el centro de las porciones estableciendo el ancho del anillo con `wedgeprops={'width': 0.4}` (deja libre el 60% interior).
2. **Inyección directa de KPI con `plt.text(0, 0, ...)`:** Sitúa el puntaje numérico final en el origen de coordenadas $(0, 0)$ centrado vertical y horizontalmente (`ha='center', va='center'`), transformando el gráfico en un *widget* ejecutivo estilo tarjeta KPI.

```python
# ==========================================================
# ANALÍTICA DE CLIENTES: NET PROMOTER SCORE (NPS) EN DONA
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

# 1. Ingesta de 20 Evaluaciones (0 a 10)
scores = [10, 9, 8, 4, 10, 6, 7, 9, 2, 8, 10, 10, 7, 5, 9, 8, 10, 9, 1, 9]

# 2. Lógica de Clasificación NPS
promotores = len([s for s in scores if s >= 9])
pasivos = len([s for s in scores if s in [7, 8]])
detractores = len([s for s in scores if s <= 6])

nps = ((promotores - detractores) / len(scores)) * 100

# 3. Gráfico de Dona (Donut Chart)
etiquetas = [f'Promotores ({promotores})', f'Pasivos ({pasivos})', f'Detractores ({detractores})']
valores = [promotores, pasivos, detractores]
colores = ['#28a745', '#ffc107', '#dc3545']

plt.figure(figsize=(6, 4))
plt.pie(valores, labels=etiquetas, colors=colores, autopct='%1.1f%%', startangle=90, wedgeprops={'width': 0.4})
plt.title("Net Promoter Score (NPS)")

# Inyectar el texto del KPI en el centro
plt.text(0, 0, f"{nps:.1f}", ha='center', va='center', fontsize=24, fontweight='bold', color="#333")

plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. De los 20 puntajes: 12 clientes otorgan 9 o 10 (Promotores = 60%), 4 otorgan 7 u 8 (Pasivos = 20%) y 4 otorgan 6 o menos (Detractores = 20%).
2. El cálculo de NPS arroja: $rac{12 - 4}{20} 	imes 100 = 40.0$, ubicando a la empresa en una zona muy favorable (> +30 se considera excelente).
3. `plt.pie()` con `wedgeprops={'width': 0.4}` dibuja el anillo con cuñas verde (60%), amarillo (20%) y rojo (20%).
4. `plt.text(0, 0, "40.0")` renderiza el número central en negrita de 24 puntos, logrando una presentación estética limpia propia de reportes para juntas directivas.

---

### 14.11 Detección de Anomalías y Fraude Transaccional: Control Estadístico con Z-Score ($2\sigma$), Marcado de Outliers y Umbral Crítico (axhline)

**📌 Enunciado:** Monitorear un historial de gastos diarios de una cuenta empresarial durante 14 días. Calcular paramétricamente la media y desviación estándar para establecer una regla de corte estadístico a 2 desviaciones estándar ($\mu + 2\sigma$), filtrar algorítmicamente las transacciones atípicas y representarlas gráficamente sobre la serie temporal destacando los puntos fraudulentos en rojo brillante sobre una línea de umbral de advertencia naranja.

**💡 Explicación / Definición:** El control estadístico de procesos y los motores antifraude modernos utilizan el principio de la distribución normal (o regla empírica del $Z	ext{-Score}$):
1. **Regla de corte estadístico:** Los valores que superan $\mu + 2\sigma$ caen fuera del ~95% de la actividad normal y se clasifican como anomalías o presuntos fraudes.
2. **Filtrado booleano en Pandas:** `df["Gasto"] > limite_superior` genera una máscara de booleanos que se utiliza para indexar `anomalias = df[df["Alerta"]]` de manera instantánea sin bucles.
3. **Control de profundidad de capas con `zorder`:** En matplotlib, `zorder=5` fuerza a que los puntos rojos de dispersión se dibujen en una capa superior por encima de la línea cronológica continua (`zorder` por defecto es 2), asegurando que los puntos de alerta jamás queden tapados.
4. **Línea de umbral analítico:** `plt.axhline(limite_superior, color="orange", linestyle="dashed")` demarca la frontera estadística continua.

```python
# ==========================================================
# SISTEMA ANTIFRAUDE: DETECCIÓN DE ANOMALÍAS CON Z-SCORE
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

# 1. Historial de Gastos Diarios
df = pd.DataFrame({
    "Dia": range(1, 15),
    "Gasto": [45, 52, 48, 60, 42, 55, 490, 50, 47, 53, 44, 420, 58, 49]
})

# 2. Cálculo Estadístico (Media y Desviación)
media = df["Gasto"].mean()
desviacion = df["Gasto"].std()
limite_superior = media + (2 * desviacion)

# 3. Etiquetado Algorítmico
df["Alerta"] = df["Gasto"] > limite_superior
anomalias = df[df["Alerta"]]

# 4. Gráfico Analítico
plt.figure(figsize=(7, 4))
plt.plot(df["Dia"], df["Gasto"], marker='o', color="#17a2b8", label="Gasto Normal")
plt.scatter(anomalias["Dia"], anomalias["Gasto"], color="red", s=150, zorder=5, label="FRAUDE DETECTADO")
plt.axhline(limite_superior, color="orange", linestyle="dashed", label="Umbral de Alerta")

plt.title("Sistema Antifraude: Z-Score en Tiempo Real")
plt.xlabel("Día del Mes")
plt.ylabel("Monto Transaccionado ($)")
plt.legend()
plt.grid(alpha=0.3)
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. Los gastos oscilan normalmente entre $42 y $60, salvo en los días 7 ($490) y 12 ($420).
2. `media` resulta en ~104.6 y `desviacion` en ~149.2, fijando el límite crítico en $403.0$.
3. La máscara booleana aisla exactamente las transacciones de los días 7 y 12.
4. `plt.plot()` dibuja la serie en color cian suave, mientras que `plt.scatter()` superpone los dos círculos rojos de alerta de 150 puntos en primer plano (`zorder=5`).
5. La línea naranja punteada confirma visualmente cómo ambos picos violan el límite máximo permitido.

---

### 14.12 Proyección de Flujo de Caja (Cashflow Forecast): Relleno Condicional Dinámico de Superávit y Déficit (fill_between con where)

**📌 Enunciado:** Proyectar el flujo de caja semestral de una organización contrastando cobros previstos contra pagos comprometidos. Graficar ambas trayectorias y aplicar sombreados condicionales automáticos: verde translúcido en los meses donde los cobros superan a los pagos (superávit de liquidez) y rojo translúcido cuando los egresos exceden a los ingresos (déficit de caja).

**💡 Explicación / Definición:** El control de tesorería depende de identificar la "brecha de liquidez":
1. **La función `plt.fill_between()`:** Rellena el área geométrica comprendida entre dos curvas `y1` (cobros) y `y2` (pagos) sobre el eje `x` (meses).
2. **El argumento de condición `where`:** Permite pasar una lista de booleanos (`[c > p for c, p in zip(cobros, pagos)]`). El sombreado solo se aplica en los intervalos donde la condición es `True`.
3. **Interpolación exacta con `interpolate=True`:** Calcula matemáticamente el punto exacto de intersección donde las dos curvas se cruzan, evitando cortes rectos o escalonados entre las áreas verde y roja.

```python
# ==========================================================
# PROYECCIÓN DE FLUJO DE CAJA CON RELLENO CONDICIONAL
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

# 1. Proyección Financiera
meses = ["Ene", "Feb", "Mar", "Abr", "May", "Jun"]
cobros = [12000, 15000, 11000, 18000, 22000, 20000]
pagos = [10000, 16000, 14000, 13000, 15000, 25000]

# 2. Visualización Avanzada
plt.figure(figsize=(7, 4))
plt.plot(meses, cobros, label="Ingresos Esperados", color="green", marker="o", linewidth=2)
plt.plot(meses, pagos, label="Egresos Proyectados", color="red", marker="x", linewidth=2)

# 3. Relleno Condicional (Brecha de Liquidez)
plt.fill_between(meses, cobros, pagos, where=[c > p for c, p in zip(cobros, pagos)], interpolate=True, color='green', alpha=0.2, label="Superávit")
plt.fill_between(meses, cobros, pagos, where=[c <= p for c, p in zip(cobros, pagos)], interpolate=True, color='red', alpha=0.2, label="Déficit (Peligro)")

plt.title("Proyección de Flujo de Caja (Cashflow Forecast)")
plt.ylabel("Miles de $")
plt.legend(loc="upper left")
plt.grid(linestyle="--", alpha=0.4)
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. Enero registra superávit ($12,000 > $10,000), por lo que se sombrea en verde.
2. Febrero y Marzo entran en déficit ($15k < $16k y $11k < $14k), activando el sombreado rojo de alerta.
3. Abril y Mayo recuperan superávit holgado ($18k > $13k y $22k > $15k).
4. Junio sufre un déficit pronunciado por pagos de $25,000 frente a cobros de $20,000.
5. El parámetro `interpolate=True` asegura que las transiciones entre verde y rojo se unan exactamente en los cruces de las líneas, brindando un acabado editorial propio de reportes de tesorería corporativa.

---

### 14.13 Análisis de Retorno de Inversión (ROI) por Sucursal: Gráfico de Barras Horizontales con Ordenamiento y Anotación Directa de Datos (plt.barh y plt.text)

**📌 Enunciado:** Analizar el desempeño financiero de 5 sucursales comerciales. Calcular el porcentaje de Retorno sobre la Inversión (ROI), ordenar las unidades de negocio de forma ascendente para su óptima lectura horizontal y graficar las barras anotando automáticamente al final de cada una su valor porcentual exacto en negrita.

**💡 Explicación / Definición:** El **ROI (Return On Investment)** mide el rendimiento del capital invertido:
$$	ext{ROI} = \left(rac{	ext{Beneficio Neto}}{	ext{Inversión}}
ight) 	imes 100$$
1. **Barras horizontales con `plt.barh()`:** Es la visualización ideal cuando las etiquetas de las categorías son nombres de ciudades o entidades largas, eliminando la necesidad de rotar el texto verticalmente.
2. **Ordenamiento previo:** `.sort_values("ROI", ascending=True)` ubica la sucursal más rezagada en la parte inferior y la de mejor desempeño en la superior (orden de ranking visual natural).
3. **Anotación directa iterando sobre las barras:** En lugar de forzar al lector a proyectar la vista hacia el eje numérico inferior, se itera sobre la colección `barras` devuelta por `plt.barh()`:
   - `barra.get_width()` devuelve el largo numérico exacto de la barra (el ROI).
   - `barra.get_y() + 0.3` sitúa la etiqueta centrada verticalmente en el cuerpo de la barra.
   - `plt.xlim(0, max + 10)` expande el margen derecho para que los textos numéricos no se corten contra el borde de la figura.

```python
# ==========================================================
# RETORNO DE INVERSIÓN (ROI) Y ANOTACIÓN DIRECTA EN BARRAS
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

# 1. Datos de Sucursales
df = pd.DataFrame({
    "Sucursal": ["S. Domingo", "Santiago", "Punta Cana", "La Romana", "Puerto Plata"],
    "Inversion": [500000, 350000, 800000, 200000, 450000],
    "BeneficioNeto": [120000, 95000, 320000, 15000, 90000]
})

# 2. Cálculo Financiero del ROI (%)
df["ROI"] = (df["BeneficioNeto"] / df["Inversion"]) * 100
df = df.sort_values("ROI", ascending=True) # Ordenar para gráfico horizontal

# 3. Visualización Ejecutiva
plt.figure(figsize=(7, 4))
barras = plt.barh(df["Sucursal"], df["ROI"], color="#2F6D9C")

# Agregar etiquetas de valor en las barras
for barra in barras:
    plt.text(barra.get_width() + 1, barra.get_y() + 0.3, f"{barra.get_width():.1f}%", va='center', fontweight='bold')

plt.title("Retorno de Inversión (ROI) por Sucursal")
plt.xlabel("Porcentaje de Retorno (%)")
plt.xlim(0, max(df["ROI"]) + 10)
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. Se calculan los ROIs: La Romana (7.5%), Puerto Plata (20.0%), S. Domingo (24.0%), Santiago (27.1%) y Punta Cana (40.0%).
2. `sort_values` ordena la tabla de menor a mayor.
3. `plt.barh()` dibuja las 5 barras azules ordenadas.
4. El bucle `for barra in barras` calcula las coordenadas geométricas y escribe `7.5%`, `20.0%`, etc., a 1 punto de distancia del final de cada barra.
5. `plt.xlim(0, 50)` otorga el espacio holgado necesario a la derecha para que las etiquetas respiren sin colisionar con el marco del gráfico.

---

### 14.14 Diversificación de Portafolio y Asignación de Activos (Asset Allocation): Gráfico de Dona con Desglose Radial (explode) y Distancia Porcentual (pctdistance)

**📌 Enunciado:** Representar la distribución estratégica de un portafolio de inversión de $1,000,000 en 4 clases de activos (Bonos, Acciones, Bienes Raíces y Criptoactivos). Diseñar un gráfico de dona elegante con borde blanco de separación, alejando ligeramente la porción de mayor riesgo mediante el parámetro `explode` para captar la atención de los comités de inversión.

**💡 Explicación / Definición:** En la teoría moderna de portafolios (Markowitz), el balance entre renta fija, variable y alternativos es clave:
1. **Desglose radial selectivo con `explode`:** Una tupla de desfases donde cada valor indica cuánto se separa radialmente esa cuña del centro de la dona. Al definir `resaltar = (0, 0, 0, 0.2)`, las 3 primeras clases permanecen unidas en el anillo y la cuarta (Criptomonedas) se desprende 0.2 unidades hacia afuera, creando un énfasis visual focalizado.
2. **Posición de porcentajes con `pctdistance=0.85`:** En un gráfico de dona con ancho de cuña `width=0.4` (que va del radio 0.6 al 1.0), los porcentajes deben situarse en el radio $0.85$ para quedar exactamente centrados dentro del grosor del anillo coloreado.
3. **Bordes blancos limpios:** `wedgeprops=dict(width=0.4, edgecolor='w')` genera divisiones nítidas entre las porciones facilitando su lectura cuando los tonos son oscuros.

```python
# ==========================================================
# ASSET ALLOCATION: DONA CON DESGLOSE SELECTIVO (EXPLODE)
# ==========================================================

import matplotlib.pyplot as plt

# 1. Asignación de Activos (Asset Allocation)
activos = ["Bonos Tesoro (Seguro)", "Acciones SP500", "Bienes Raíces", "Criptomonedas (Riesgo)"]
capital = [450000, 350000, 150000, 50000]

# 2. Configuración Visual
# Separamos el activo de mayor riesgo para resaltarlo visualmente
resaltar = (0, 0, 0, 0.2) 
colores = ["#6c757d", "#007bff", "#28a745", "#dc3545"]

# 3. Gráfico de Dona con Desglose
plt.figure(figsize=(7, 4))
plt.pie(capital, labels=activos, autopct='%1.0f%%', startangle=140, 
        explode=resaltar, colors=colores, pctdistance=0.85,
        wedgeprops=dict(width=0.4, edgecolor='w'))

plt.title("Diversificación de Capital de Inversión")
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. El capital totaliza $1,000,000: Bonos (45%), Acciones (35%), Bienes Raíces (15%) y Cripto (5%).
2. `wedgeprops` vacía el 60% interior y asigna bordes blancos entre cortes.
3. La cuña roja de Criptomonedas se expulsa 20% hacia afuera gracias a `explode=(0, 0, 0, 0.2)`, comunicando visualmente que representa el activo atípico de alta volatilidad.
4. `pctdistance=0.85` coloca los números `45%`, `35%`, `15%` y `5%` perfectamente centrados en el cuerpo de cada anillo.

---

### 14.15 Curva de Supervivencia y Análisis de Retención de Clientes (Cohortes): Gráficos de Escalera / Escalón (plt.step con relleno post)

**📌 Enunciado:** Medir el agotamiento (*churn*) y retención de una cohorte inicial de 100 clientes suscriptores a lo largo de un semestre. Graficar la función de supervivencia mediante una curva escalonada discreta (*step chart*) con relleno de caída sombreado y calcular la tasa de retención final al sexto mes.

**💡 Explicación / Definición:** En modelos de negocio de suscripción (SaaS, membresías, telecomunicaciones), las bajas de usuarios no ocurren como una curva suave continua, sino como eventos discretos en fechas de corte:
1. **La función `plt.step(..., where='post')`:** Dibuja una línea en forma de peldaños de escalera; el valor se mantiene horizontal constante durante todo el mes hasta que se produce la caída al inicio del periodo siguiente (`where='post'`), reflejando con fidelidad la naturaleza de las renovaciones mensuales.
2. **Relleno escalonado coherente:** `plt.fill_between(..., step="post", alpha=0.1)` sombrea el área bajo los escalones respetando la misma geometría escalonada.
3. **Cálculo de retención acumulada:** `(clientes_activos[-1] / clientes_activos[0]) * 100` evalúa el porcentaje de supervivencia desde el origen ($t=0$).

```python
# ==========================================================
# ANÁLISIS DE SUPERVIVENCIA Y COHORTES CON STEP CHART
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

# 1. Datos de Supervivencia (Cohorte de Enero)
meses = [0, 1, 2, 3, 4, 5, 6]
clientes_activos = [100, 92, 85, 71, 68, 65, 63]

# 2. Cálculo de Fuga Acumulada
tasa_retencion = (clientes_activos[-1] / clientes_activos[0]) * 100

# 3. Visualización de Supervivencia (Step Chart)
plt.figure(figsize=(7, 4))
plt.step(meses, clientes_activos, where='post', color="#dc3545", linewidth=2.5)
plt.fill_between(meses, clientes_activos, step="post", alpha=0.1, color="#dc3545")

plt.title(f"Curva de Supervivencia (Retención: {tasa_retencion:.1f}%)")
plt.xlabel("Meses desde la Suscripción")
plt.ylabel("Clientes Activos Restantes")
plt.ylim(0, 110)
plt.grid(True, linestyle=":", alpha=0.5)
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. La cohorte parte con 100 clientes en el mes 0. En el mes 1 caen a 92, en el mes 3 sufren la mayor baja cayendo a 71, y se estabilizan en 63 al mes 6.
2. `tasa_retencion` calcula `63.0%`.
3. `plt.step()` genera la línea en peldaños rojos de 2.5 puntos de grosor, ilustrando con precisión que entre el mes 1 y 2 los clientes permanecieron en 92 hasta el siguiente corte de renovación.
4. El sombreado rojo translúcido enfatiza visualmente el volumen de clientes que continúan activos.

---

### 14.16 Modelado Macroeconómico de Inflación y Depreciación: Curva de Decaimiento Exponencial y Supresión de Notación Científica (ticklabel_format)

**📌 Enunciado:** Modelar el impacto de una inflación constante del 5% anual sobre un capital líquido de $1,000,000 en un horizonte de 10 años mediante la fórmula de valor presente. Graficar la curva de decaimiento del poder adquisitivo y configurar los ejes para mostrar cifras monetarias completas evitando la notación científica predeterminada de matplotlib.

**💡 Explicación / Definición:** La pérdida de poder adquisitivo por inflación acumulada sigue un decaimiento exponencial:
$$	ext{Valor Real} = rac{	ext{Capital Inicial}}{(1 + 	ext{Inflación})^a}$$
donde $a$ es el número de años transcurridos.
1. **Comprensión de listas matemática:** `[capital_inicial / ((1 + inflacion_anual)**a) for a in anios]` calcula el valor deflactado para cada periodo en una sola línea.
2. **Supresión de notación científica con `ticklabel_format()`:** Cuando matplotlib maneja cifras de cientos de miles o millones, suele abreviar el eje Y como $1 	imes 10^6$. La llamada `plt.ticklabel_format(style='plain', axis='y')` fuerza al renderizador a mostrar números naturales completos (`1000000`, `800000`, `600000`), esencial para la claridad en reportes financieros.

```python
# ==========================================================
# IMPACTO DE INFLACIÓN Y DECAIMIENTO DE PODER ADQUISITIVO
# ==========================================================

import matplotlib.pyplot as plt

# 1. Parámetros del Modelo Macro
capital_inicial = 1000000
inflacion_anual = 0.05
anios = list(range(11))

# 2. Función de Valor Presente (Depreciación Exponencial)
# Fórmula: Valor = Capital / (1 + inflacion)^año
valor_real = [capital_inicial / ((1 + inflacion_anual)**a) for a in anios]

# 3. Gráfico de Decaimiento
plt.figure(figsize=(7, 4))
plt.plot(anios, valor_real, color="#ffc107", linewidth=3, marker="o")
plt.fill_between(anios, valor_real, color="#ffc107", alpha=0.1)

plt.title("Pérdida de Poder Adquisitivo (Inflación 5%)")
plt.xlabel("Años Transcurridos")
plt.ylabel("Valor Real del Dinero ($)")
plt.ticklabel_format(style='plain', axis='y') # Quitar notación científica
plt.grid(linestyle='--', alpha=0.4)
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. En el año 0 el poder adquisitivo es de $1,000,000. Al cabo de 5 años cae a ~$783,526 y al año 10 se reduce a solo ~$613,913 (una pérdida real de casi el 40% del patrimonio si el capital permanece ocioso sin invertir).
2. `plt.plot()` dibuja la curva descendente dorada con marcadores en cada año.
3. `plt.ticklabel_format(style='plain', axis='y')` garantiza que el eje Y exponga los montos en formato numérico ordinario sin exponentes.

---

### 14.17 Prueba de Estrés Financiero (Stress Test Hipotecario): Función de Amortización Francesa, Simulación de Escenarios y Líneas de Frontera

**📌 Enunciado:** Programar una función financiera que implemente la fórmula del Sistema Francés de amortización de préstamos a cuota constante. Simular el comportamiento de una hipoteca de $200,000 a 20 años bajo 9 escenarios de tasas de interés (desde un optimista 4% hasta un severo 12%) y trazar la curva de estrés con líneas de referencia en los escenarios extremos.

**💡 Explicación / Definición:** La cuota mensual nivelada bajo el **Sistema Francés** responde a la ecuación de anualidades ordinarias:
$$	ext{Cuota} = P 	imes rac{i 	imes (1 + i)^n}{(1 + i)^n - 1}$$
donde $P$ es el capital prestado, $i$ es la tasa mensual nominal ($	ext{tasa anual} / 12 / 100$) y $n$ es el plazo en meses ($20 	imes 12 = 240$).
1. **Función financiera reutilizable:** `calcular_cuota(prestamo, tasa_anual, anios)` encapsula la fórmula estándar utilizada por instituciones bancarias de todo el mundo.
2. **Generación vectorial de escenarios:** Mediante una comprensión de listas se evalúa la función para cada elemento de la lista de tasas `[4, 5, ..., 12]`.
3. **Líneas de frontera de escenarios con `axhline`:** Se fijan dos líneas horizontales: una verde en `cuotas[0]` (escenario base más accesible al 4%) y una roja en `cuotas[-1]` (escenario pesimista de máximo estrés financiero al 12%).

```python
# ==========================================================
# STRESS TEST HIPOTECARIO: SISTEMA FRANCÉS DE AMORTIZACIÓN
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

# 1. Fórmula de Cuota Francesa
def calcular_cuota(prestamo, tasa_anual, anios):
    tasa_mensual = tasa_anual / 12 / 100
    meses = anios * 12
    return prestamo * (tasa_mensual * (1 + tasa_mensual)**meses) / ((1 + tasa_mensual)**meses - 1)

# 2. Generación de Escenarios
prestamo = 200000
tasas = [4, 5, 6, 7, 8, 9, 10, 11, 12]
cuotas = [calcular_cuota(prestamo, t, 20) for t in tasas]

# 3. Gráfico de Sensibilidad (Curva de Estrés)
plt.figure(figsize=(7, 4))
plt.plot(tasas, cuotas, color="#17a2b8", linewidth=2.5, marker="s")
plt.axhline(cuotas[0], color="green", linestyle="--", label="Cuota Inicial (4%)")
plt.axhline(cuotas[-1], color="red", linestyle="--", label="Escenario Pesimista (12%)")

plt.title("Stress Test: Impacto de Tasas en Hipoteca de $200k")
plt.xlabel("Tasa de Interés Hipotecaria (%)")
plt.ylabel("Cuota Mensual Nivelada ($)")
plt.legend()
plt.grid(True, alpha=0.3)
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. A una tasa del 4%, la cuota mensual calculada es de $1,211.96.
2. A una tasa del 12%, la cuota asciende a $2,202.17 (un incremento del +81.7% en la mensualidad por el mismo monto prestado).
3. `plt.plot()` grafica la curva de sensibilidad con marcadores cuadrados (`marker="s"`).
4. Las dos líneas horizontales demarcan visualmente la brecha de riesgo de más de $990 mensuales entre el mejor y el peor escenario de mercado.

---

### 14.18 Matriz Estratégica de Talento y Rendimiento (Matriz de Cuadrantes): Gráfico de Dispersión con Cruce de Medias (axvline/axhline) y Etiquetado Individual de Observaciones

**📌 Enunciado:** Construir una matriz de evaluación de talento comercial de 4 cuadrantes (similar a la matriz 9-Box de McKinsey/BCG). Mapear el rendimiento en ventas de 7 ejecutivos contra su índice de satisfacción del cliente (CSAT), calcular los promedios globales del grupo como ejes divisorios de cuadrantes y anotar el nombre de cada colaborador junto a su respectivo punto en el plano.

**💡 Explicación / Definición:** Las matrices de cuadrantes permiten segmentar observaciones en 4 categorías cualitativas cruzando dos variables continuas respecto a un punto de corte (generalmente la media o mediana del grupo):
1. **Líneas divisorias maestras con `plt.axvline()` y `plt.axhline()`:** 
   - `plt.axvline(media_sat)` traza la línea vertical divisoria en el promedio de satisfacción.
   - `plt.axhline(media_ventas)` traza la línea horizontal divisoria en el promedio de ventas.
   - Ambas rectas dividen el gráfico en 4 cuadrantes estratégicos:
     - **Superior Derecho (Alto rendimiento, Alta satisfacción):** Estrellas del equipo (*Top Performers*).
     - **Superior Izquierdo (Altas ventas, Baja satisfacción):** Venta agresiva / Riesgo de retención de clientes.
     - **Inferior Derecho (Bajas ventas, Alta satisfacción):** Potencial de desarrollo / Excelentes relaciones.
     - **Inferior Izquierdo (Bajas ventas, Baja satisfacción):** Plan de mejora o reubicación.
2. **Anotación directa con bucle y `enumerate()`:** `for i, txt in enumerate(df["Vendedor"]): plt.text(x + 0.1, y, txt)` escribe el nombre de cada persona con un leve desplazamiento horizontal de `+0.1` para que el texto no se monte sobre el punto.

```python
# ==========================================================
# MATRIZ DE TALENTO: RENDIMIENTO VS SATISFACCIÓN (4 CUADRANTES)
# ==========================================================

import pandas as pd
import matplotlib.pyplot as plt

# 1. Datos del Personal
df = pd.DataFrame({
    "Vendedor": ["Juan", "Ana", "Luis", "Marta", "Pedro", "Sofia", "Carlos"],
    "Ventas": [120, 350, 90, 310, 150, 420, 200], # En miles
    "Satisfaccion": [6.5, 9.2, 5.0, 7.8, 8.5, 9.5, 6.0] # Escala 1-10
})

# 2. Limites de los Cuadrantes (Promedios del Grupo)
media_ventas = df["Ventas"].mean()
media_sat = df["Satisfaccion"].mean()

# 3. Mapeo en Cuadrante (Scatter)
plt.figure(figsize=(7, 4))
plt.scatter(df["Satisfaccion"], df["Ventas"], color="#6f42c1", s=100)

for i, txt in enumerate(df["Vendedor"]):
    plt.text(df["Satisfaccion"][i] + 0.1, df["Ventas"][i], txt)

# 4. Líneas Divisorias Maestras
plt.axvline(media_sat, color='gray', linestyle='--')
plt.axhline(media_ventas, color='gray', linestyle='--')

plt.title("Matriz de Talento: Rendimiento Comercial vs Calidad")
plt.xlabel("Índice de Satisfacción del Cliente (CSAT)")
plt.ylabel("Volumen de Ventas ($ Miles)")
plt.tight_layout()
plt.show()
```

**⚙️ Comentario de funcionamiento:**
1. La media de ventas del equipo se sitúa en $234.3k y la satisfacción media en 7.5 puntos.
2. `axvline` y `axhline` cruzan sus ejes en las coordenadas $(7.5, 234.3)$, estableciendo las 4 regiones.
3. Sofía ($420k, 9.5), Ana ($350k, 9.2) y Marta ($310k, 7.8) se posicionan claramente en el cuadrante superior derecho como líderes absolutas.
4. Pedro ($150k, 8.5) se ubica en el cuadrante inferior derecho (excelente trato al cliente con oportunidad de escalar volumen de ventas).
5. Luis, Juan y Carlos quedan identificados en las zonas de rezago comercial para intervenciones de capacitación.

---

## 15. Dashboards comparativos con subplots (dos gráficos lado a lado)

> 💡 **Concepto común a toda esta sección:** `plt.subplots(1, 2, figsize=(12,5))` crea **una sola figura** dividida en 1 fila y 2 columnas, devolviendo dos "ejes" (`ax1`, `ax2`) que funcionan como lienzos independientes donde dibujar cada gráfico por separado. Esto permite comparar dos variables relacionadas **sin que se superpongan ni compitan por el mismo espacio**. `plt.tight_layout()` ajusta automáticamente los márgenes para que los títulos y etiquetas no se corten ni se encimen.

### 15.1 Depósitos mensuales e intereses ganados

**📌 Enunciado:** Mostrar en dos gráficos separados, uno al lado del otro, la evolución de los depósitos mensuales (línea) y los intereses ganados (barras), sin usar tablas que puedan desordenar el diseño.

```python
# EJERCICIO: Mostrar depósitos e intereses en dos gráficos lado a lado (sin tabla)

import matplotlib.pyplot as plt

meses = ["Ene","Feb","Mar","Abr","May"]
depositos = [1000, 1500, 1800, 2000, 2500]
intereses = [10, 15, 18, 20, 25]

fig, (ax1, ax2) = plt.subplots(1, 2, figsize=(12,5))

ax1.plot(meses, depositos, marker='o', color='blue')
ax1.set_title("Depósitos Mensuales")
ax1.set_xlabel("Mes")
ax1.set_ylabel("Monto")

ax2.bar(meses, intereses, color='green')
ax2.set_title("Intereses Ganados")
ax2.set_xlabel("Mes")
ax2.set_ylabel("Interés")

plt.tight_layout()
plt.show()

# ¿CÓMO FUNCIONA?
# Se crean dos gráficos lado a lado usando subplots(1,2).
# No hay tabla, así nada se encima.
# Dashboard limpio y profesional.
```

**⚙️ Comentario de funcionamiento:** `ax1` recibe el gráfico de línea de los depósitos (tendencia de crecimiento mes a mes) y `ax2` recibe el gráfico de barras de los intereses; ambos se dibujan en la misma figura `fig`, pero en espacios completamente independientes gracias al desempaquetado `(ax1, ax2)`.

---

### 15.2 Cartera total y morosidad

**📌 Enunciado:** Comparar el crecimiento de la cartera total de préstamos frente al porcentaje de morosidad mes a mes.

```python
# EJERCICIO: Mostrar cartera total y morosidad en dos gráficos lado a lado

import matplotlib.pyplot as plt

meses = ["Ene","Feb","Mar","Abr","May"]
cartera = [50000, 52000, 54000, 56000, 60000]
morosidad = [5, 4.8, 4.5, 4.3, 4.1]

fig, (ax1, ax2) = plt.subplots(1, 2, figsize=(12,5))

ax1.plot(meses, cartera, marker='o', color='purple')
ax1.set_title("Cartera Total")
ax1.set_xlabel("Mes")
ax1.set_ylabel("Monto")

ax2.bar(meses, morosidad, color='red')
ax2.set_title("Morosidad (%)")
ax2.set_xlabel("Mes")
ax2.set_ylabel("Porcentaje")

plt.tight_layout()
plt.show()

# ¿CÓMO FUNCIONA?
# Línea para cartera (crecimiento).
# Barras para morosidad (riesgo).
# Sin tabla → nada se desborda.
```

**⚙️ Comentario de funcionamiento:** El gráfico de línea (`ax1`) resalta la tendencia de crecimiento constante de la cartera, mientras que el gráfico de barras (`ax2`) permite comparar visualmente el nivel de riesgo (morosidad) mes a mes; al estar en ejes separados, una escala de miles (cartera) no distorsiona la lectura de una escala de porcentaje (morosidad).

---

### 15.3 Ingresos por intereses y gastos operativos

**📌 Enunciado:** Comparar los ingresos por intereses contra los gastos operativos mes a mes, para evaluar la rentabilidad.

```python
# EJERCICIO: Comparar ingresos por intereses y gastos operativos con dos gráficos

import matplotlib.pyplot as plt

meses = ["Ene","Feb","Mar","Abr","May"]
ingresos = [8000, 8200, 8500, 9000, 9500]
gastos = [3000, 3200, 3100, 3300, 3400]

fig, (ax1, ax2) = plt.subplots(1, 2, figsize=(12,5))

ax1.plot(meses, ingresos, marker='o', color='green')
ax1.set_title("Ingresos por Intereses")
ax1.set_xlabel("Mes")
ax1.set_ylabel("Monto")

ax2.bar(meses, gastos, color='gray')
ax2.set_title("Gastos Operativos")
ax2.set_xlabel("Mes")
ax2.set_ylabel("Monto")

plt.tight_layout()
plt.show()

# ¿CÓMO FUNCIONA?
# Dos gráficos separados y claros.
# Ideal para ver rentabilidad mensual.
```

**⚙️ Comentario de funcionamiento:** Al colocar ingresos (línea verde) y gastos (barras grises) en paneles separados pero alineados, resulta fácil comparar visualmente si los ingresos crecen más rápido que los gastos mes a mes, sin que ambas series compitan por la misma escala del eje Y.

---

### 15.4 Ahorros acumulados y rendimiento mensual

**📌 Enunciado:** Mostrar cómo crecen los ahorros acumulados junto con el rendimiento (interés) que generan cada mes.

```python
# EJERCICIO: Mostrar ahorros acumulados y rendimiento mensual en dos gráficos

import matplotlib.pyplot as plt

meses = ["Ene","Feb","Mar","Abr","May"]
ahorros = [2000, 2500, 3000, 3500, 4200]
rendimiento = [20, 25, 30, 35, 42]

fig, (ax1, ax2) = plt.subplots(1, 2, figsize=(12,5))

ax1.plot(meses, ahorros, marker='o', color='blue')
ax1.set_title("Ahorros Acumulados")
ax1.set_xlabel("Mes")
ax1.set_ylabel("Monto")

ax2.bar(meses, rendimiento, color='orange')
ax2.set_title("Rendimiento Mensual")
ax2.set_xlabel("Mes")
ax2.set_ylabel("Interés")

plt.tight_layout()
plt.show()

# ¿CÓMO FUNCIONA?
# Línea para ahorros (acumulación).
# Barras para rendimiento (interés).
# Presentación limpia sin tablas.
```

**⚙️ Comentario de funcionamiento:** El patrón se repite: variable acumulativa/tendencia → gráfico de línea (`ax1`); variable puntual por período → gráfico de barras (`ax2`). Aquí se observa cómo, a medida que los ahorros acumulados crecen, el rendimiento mensual generado también aumenta proporcionalmente.

---

### 15.5 Transacciones y comisiones

**📌 Enunciado:** Comparar el volumen de transacciones procesadas contra los ingresos generados por comisiones cada mes.

```python
# EJERCICIO: Mostrar transacciones y comisiones en dos gráficos lado a lado

import matplotlib.pyplot as plt

meses = ["Ene","Feb","Mar","Abr","May"]
transacciones = [1200, 1300, 1400, 1500, 1600]
comisiones = [300, 320, 350, 380, 400]

fig, (ax1, ax2) = plt.subplots(1, 2, figsize=(12,5))

ax1.plot(meses, transacciones, marker='o', color='brown')
ax1.set_title("Transacciones")
ax1.set_xlabel("Mes")
ax1.set_ylabel("Cantidad")

ax2.bar(meses, comisiones, color='cyan')
ax2.set_title("Comisiones")
ax2.set_xlabel("Mes")
ax2.set_ylabel("Monto")

plt.tight_layout()
plt.show()

# ¿CÓMO FUNCIONA?
# Línea para volumen de transacciones.
# Barras para ingresos por comisiones.
# Nada se encime porque no hay tablas.
```

**⚙️ Comentario de funcionamiento:** El eje `ax1` traza la cantidad de transacciones procesadas mes a mes (volumen operativo), mientras que `ax2` muestra el monto de comisiones generadas; al crecer ambas variables de forma paralela, el dashboard permite validar visualmente que más transacciones se traducen en más ingresos por comisión.

---

## 16. Caso integrador: Sistema de análisis de ventas

### 16.1 Definición de categorías y estructura de una venta

**📌 Enunciado:** Modelar los datos base de un sistema de ventas: productos, vendedores, regiones y métodos de pago, además de la estructura que representará cada venta individual.

**💡 Explicación / Definición:** Las **listas** (`[]`) agrupan valores relacionados (como los nombres de productos). Un **diccionario** (`{}`) representa un registro con pares clave-valor, ideal para modelar una "venta" con sus distintos atributos (cliente, vendedor, producto, etc.). La comprensión de listas `[f"Cliente {i}" for i in range(1, 41)]` genera automáticamente 40 nombres de clientes sin escribirlos uno por uno.

```python
# 1. DEFINICIÓN DE NUESTRAS CATEGORÍAS (Tus datos base)
productos = ["Laptop", "Celular", "Tablet", "Audífonos", "Monitor"]
vendedores = ["Ana", "Carlos", "Beatriz", "Diego", "Elena"]
regiones = ["Norte", "Sur", "Centro"]
metodos_pago = ["Efectivo", "Tarjeta", "Transferencia"]

# Nota: Para los 40 clientes, en vez de escribir una lista gigante, 
# los identificaremos de forma automática como 'Cliente 1', 'Cliente 2', etc.


# 2. MODELADO DE UNA VENTA INDIVIDUAL (Ejemplo de estructura de un ticket)
# Cada venta realizada será un diccionario con esta forma:
venta_ejemplo = {
    "cliente": "Cliente 24",       # Del 1 al 40
    "vendedor": "Ana",            # Uno de los 5
    "producto": "Laptop",          # Uno de los 5
    "metodo_pago": "Tarjeta",      # Uno de los 3
    "region": "Norte",             # Una de las 3
    "total": 1200.50               # El dinero de la venta
}


# 3. HISTORIAL GENERAL DE VENTAS (Tu base de datos temporal)
# Aquí guardarás todas las ventas que se vayan registrando en el día
historial_ventas = [
    {"cliente": "Cliente 5", "vendedor": "Carlos", "producto": "Celular", "metodo_pago": "Efectivo", "region": "Sur", "total": 500.00},
    {"cliente": "Cliente 12", "vendedor": "Ana", "producto": "Laptop", "metodo_pago": "Tarjeta", "region": "Norte", "total": 1200.00},
    {"cliente": "Cliente 5", "vendedor": "Carlos", "producto": "Audífonos", "metodo_pago": "Transferencia", "region": "Sur", "total": 150.00},
    {"cliente": "Cliente 38", "vendedor": "Elena", "producto": "Monitor", "metodo_pago": "Tarjeta", "region": "Centro", "total": 350.00}
]


# 4. CÓMO GENERAR LOS RESÚMENES (Ejemplo con un bucle)
# Supongamos que queremos saber cuánto vendió cada REGIÓN en total:

print("=== RESUMEN DE VENTAS POR REGIÓN ===")

# Creamos un diccionario para acumular el dinero por cada región
ventas_por_region = {"Norte": 0.0, "Sur": 0.0, "Centro": 0.0}

# Recorremos nuestro historial sumando los totales
for venta in historial_ventas:
    region_venta = venta["region"]
    monto = venta["total"]
    
    # Sumamos el monto a la región correspondiente
    ventas_por_region[region_venta] += monto

# Mostramos los resultados en pantalla con el formato de 2 decimales que aprendiste
for region, total in ventas_por_region.items():
    print(f"Región {region}: ${total:.2f}")
```

**⚙️ Comentario de funcionamiento:** Se define primero el "catálogo" de valores posibles (listas), luego la forma de un registro individual (diccionario `venta_ejemplo`), y después una lista de diccionarios (`historial_ventas`) que simula varias ventas ya registradas. El bucle final recorre cada venta, extrae su región y su total, y acumula el monto en el diccionario `ventas_por_region` usando `+=`. El formato `:.2f` dentro del f-string limita la salida a 2 decimales, típico para mostrar montos monetarios.

---

### 16.2 Simulación de 100 ventas aleatorias y reportes por categoría

**📌 Enunciado:** Generar 100 ventas simuladas con datos aleatorios y producir reportes acumulados por producto, vendedor, región, método de pago y un top 5 de clientes.

**💡 Explicación / Definición:** El módulo `random` permite generar valores aleatorios: `random.choice(lista)` elige un elemento al azar de una lista, y `random.uniform(min, max)` genera un número decimal aleatorio dentro de un rango. `round(x, 2)` redondea a 2 decimales. La función `sorted()` con el parámetro `key=lambda x: x[1]` ordena una lista de tuplas por su segundo valor (el monto), y `reverse=True` la ordena de mayor a menor.

```python
import random

# 1. DEFINICIÓN DE DATOS BASE
productos = ["Laptop", "Celular", "Tablet", "Audífonos", "Monitor"]
vendedores = ["Ana", "Carlos", "Beatriz", "Diego", "Elena"]
regiones = ["Norte", "Sur", "Centro"]
metodos_pago = ["Efectivo", "Tarjeta", "Transferencia"]
# Creamos una lista automática de 40 clientes: ['Cliente 1', 'Cliente 2', ..., 'Cliente 40']
clientes = [f"Cliente {i}" for i in range(1, 41)]

# 2. SIMULACIÓN DE HISTORIAL DE VENTAS (Generamos 100 ventas aleatorias)
historial_ventas = []
for _ in range(100):
    venta = {
        "cliente": random.choice(clientes),
        "vendedor": random.choice(vendedores),
        "producto": random.choice(productos),
        "metodo_pago": random.choice(metodos_pago),
        "region": random.choice(regiones),
        "total": round(random.uniform(50, 1500), 2)  # Ventas aleatorias entre $50 y $1500
    }
    historial_ventas.add(venta) if hasattr(historial_ventas, 'add') else historial_ventas.append(venta)

# 3. CREACIÓN DE DICCIONARIOS PARA ACUMULAR LOS TOTALES
resumen_productos = {p: 0.0 for p in productos}
resumen_vendedores = {v: 0.0 for v in vendedores}
resumen_regiones = {r: 0.0 for r in regiones}
resumen_pagos = {m: 0.0 for m in metodos_pago}
resumen_clientes = {c: 0.0 for c in clientes}

# 4. PROCESAMIENTO GENERAL (Un solo bucle clasifica todo)
for v in historial_ventas:
    resumen_productos[v["producto"]] += v["total"]
    resumen_vendedores[v["vendedor"]] += v["total"]
    resumen_regiones[v["region"]] += v["total"]
    resumen_pagos[v["metodo_pago"]] += v["total"]
    resumen_clientes[v["cliente"]] += v["total"]

# 5. PRESENTACIÓN DE LOS REPORTES EN CONSOLA
print("==================================================")
print("       REPORTE GLOBAL GENERAL DE VENTAS           ")
print("==================================================")

print("\n📊 VENTAS POR PRODUCTO:")
for k, v in resumen_productos.items():
    print(f"  - {k}: ${v:.2f}")

print("\n➡️ VENTAS POR VENDEDOR:")
for k, v in resumen_vendedores.items():
    print(f"  - {k}: ${v:.2f}")

print("\n📌 VENTAS POR REGIÓN:")
for k, v in resumen_regiones.items():
    print(f"  - {k}: ${v:.2f}")

print("\n💡 VENTAS POR MÉTODO DE PAGO:")
for k, v in resumen_pagos.items():
    print(f"  - {k}: ${v:.2f}")

print("\n🗒️ TOP 5 CLIENTES CON MAYORES COMPRAS:")
# Ordenamos los clientes de mayor a menor gasto y extraemos los primeros 5
clientes_ordenados = sorted(resumen_clientes.items(), key=lambda x: x[1], reverse=True)
for k, v in clientes_ordenados[:5]:
    print(f"  - {k}: ${v:.2f}")
```

**⚙️ Comentario de funcionamiento:** Se generan 100 ventas aleatorias con `random.choice()` y `random.uniform()`, guardando cada una como diccionario dentro de la lista `historial_ventas`. Luego, un único bucle recorre esa lista una sola vez y acumula los montos simultáneamente en cinco diccionarios de resumen distintos (por producto, vendedor, región, método de pago y cliente), usando el nombre de cada categoría como clave. Finalmente, `sorted()` con `key=lambda x: x[1]` ordena los clientes por su total de compras de mayor a menor, y `[:5]` (slicing) toma solo los primeros cinco resultados para el top de clientes.

> ⚠️ **Nota de funcionamiento (documentación, no se altera el código):** la línea `historial_ventas.add(venta) if hasattr(historial_ventas, 'add') else historial_ventas.append(venta)` comprueba si la lista tiene el método `.add()` (propio de los `set`, no de las listas) antes de decidir cómo agregar el elemento; como una lista de Python nunca tiene `.add()`, esta condición siempre es `False` y en la práctica siempre se ejecuta `historial_ventas.append(venta)`.

---

### 16.3 Reportes con distribución por rangos de monto y dashboard visual

**📌 Enunciado:** Extender el sistema de ventas anterior añadiendo una clasificación de las ventas por rangos de monto y visualizando todos los resultados en un dashboard de 6 gráficos con `matplotlib`.

**💡 Explicación / Definición:** `matplotlib.pyplot` es la librería estándar de Python para crear gráficos. `plt.subplots(filas, columnas)` crea una cuadrícula de gráficos (aquí 3 filas × 2 columnas = 6 gráficos) dentro de una sola figura (`fig`), y cada posición se referencia como `axs[fila, columna]`. Se usan distintos tipos de gráfico: barras horizontales (`barh`), barras verticales (`bar`), gráfico de pastel (`pie`) y gráfico de dona (un `pie` con un círculo blanco superpuesto en el centro mediante `plt.Circle`).

```python
import random
import matplotlib.pyplot as plt

# 1. DEFINICIÓN DE DATOS BASE
productos = ["Laptop", "Celular", "Tablet", "Audífonos", "Monitor"]
vendedores = ["Ana", "Carlos", "Beatriz", "Diego", "Elena"]
regiones = ["Norte", "Sur", "Centro"]
metodos_pago = ["Efectivo", "Tarjeta", "Transferencia"]
clientes = [f"Cliente {i}" for i in range(1, 41)]

# 2. SIMULACIÓN DE HISTORIAL DE VENTAS (100 ventas aleatorias)
historial_ventas = []
for _ in range(100):
    venta = {
        "cliente": random.choice(clientes),
        "vendedor": random.choice(vendedores),
        "producto": random.choice(productos),
        "metodo_pago": random.choice(metodos_pago),
        "region": random.choice(regiones),
        "total": round(random.uniform(50, 1500), 2)
    }
    historial_ventas.append(venta)

# 3. DICCIONARIOS DE ACUMULACIÓN
resumen_productos = {p: 0.0 for p in productos}
resumen_vendedores = {v: 0.0 for v in vendedores}
resumen_regiones = {r: 0.0 for r in regiones}
resumen_pagos = {m: 0.0 for m in metodos_pago}
resumen_clientes = {c: 0.0 for c in clientes}

# NUEVO: Rangos de venta
rangos = {
    "50 - 300": 0,
    "301 - 700": 0,
    "701 - 1100": 0,
    "1101 - 1500": 0
}

# 4. PROCESAMIENTO GENERAL
for v in historial_ventas:
    resumen_productos[v["producto"]] += v["total"]
    resumen_vendedores[v["vendedor"]] += v["total"]
    resumen_regiones[v["region"]] += v["total"]
    resumen_pagos[v["metodo_pago"]] += v["total"]
    resumen_clientes[v["cliente"]] += v["total"]

    # Clasificación por rangos
    t = v["total"]
    if 50 <= t <= 300:
        rangos["50 - 300"] += 1
    elif 301 <= t <= 700:
        rangos["301 - 700"] += 1
    elif 701 <= t <= 1100:
        rangos["701 - 1100"] += 1
    else:
        rangos["1101 - 1500"] += 1

# 5. REPORTES EN CONSOLA
print("==================================================")
print("       REPORTE GLOBAL GENERAL DE VENTAS           ")
print("==================================================")

print("\n📊 VENTAS POR PRODUCTO:")
for k, v in resumen_productos.items():
    print(f"  - {k}: ${v:.2f}")

print("\n➡️ VENTAS POR VENDEDOR:")
for k, v in resumen_vendedores.items():
    print(f"  - {k}: ${v:.2f}")

print("\n📌 VENTAS POR REGIÓN:")
for k, v in resumen_regiones.items():
    print(f"  - {k}: ${v:.2f}")

print("\n💡 VENTAS POR MÉTODO DE PAGO:")
for k, v in resumen_pagos.items():
    print(f"  - {k}: ${v:.2f}")

print("\n🗒️ TOP 5 CLIENTES CON MAYORES COMPRAS:")
clientes_ordenados = sorted(resumen_clientes.items(), key=lambda x: x[1], reverse=True)
top_5_clientes = clientes_ordenados[:5]
for k, v in top_5_clientes:
    print(f"  - {k}: ${v:.2f}")

print("\n📈 DISTRIBUCIÓN POR RANGOS DE MONTO:")
for k, v in rangos.items():
    print(f"  - {k}: {v} ventas")

# ==========================================================
# 6. DASHBOARD DE 6 GRÁFICOS
# ==========================================================
fig, axs = plt.subplots(3, 2, figsize=(14, 15))
fig.suptitle("DASHBOARD INTEGRADO DE RESUMEN DE VENTAS", fontsize=16, fontweight='bold')

# --- 1. Ventas por Producto ---
bars1 = axs[0, 0].barh(list(resumen_productos.keys()), list(resumen_productos.values()), color='skyblue')
axs[0, 0].set_title("Ventas por Producto ($)")
axs[0, 0].bar_label(bars1, fmt='$%1.2f', padding=3)

# --- 2. Ventas por Vendedor ---
bars2 = axs[0, 1].bar(list(resumen_vendedores.keys()), list(resumen_vendedores.values()), color='lightgreen')
axs[0, 1].set_title("Desempeño por Vendedor ($)")
axs[0, 1].bar_label(bars2, fmt='$%1.2f', padding=3)

# --- 3. Distribución por Región ---
axs[1, 0].pie(list(resumen_regiones.values()), labels=list(resumen_regiones.keys()),
              autopct='%1.1f%%', startangle=90, colors=['gold', 'coral', 'lightcyan'])
axs[1, 0].set_title("Participación por Región")

# --- 4. Métodos de Pago (Dona) ---
axs[1, 1].pie(list(resumen_pagos.values()), labels=list(resumen_pagos.keys()),
              autopct='%1.1f%%', startangle=140, colors=['violet', 'aquamarine', 'lightgray'])
centro = plt.Circle((0,0), 0.70, fc='white')
axs[1, 1].add_artist(centro)
axs[1, 1].set_title("Uso de Métodos de Pago")

# --- 5. Top 5 Clientes ---
bars5 = axs[2, 0].bar([c[0] for c in top_5_clientes], [c[1] for c in top_5_clientes], color='orchid')
axs[2, 0].set_title("Top 5 Clientes ($)")
axs[2, 0].bar_label(bars5, fmt='$%1.2f', padding=3)

# --- 6. NUEVO: Gráfico de Rangos de Venta ---
axs[2, 1].bar(list(rangos.keys()), list(rangos.values()), color='orange')
axs[2, 1].set_title("Distribución por Rangos de Monto")
axs[2, 1].set_ylabel("Cantidad de Ventas")

plt.tight_layout(rect=[0, 0, 1, 0.96])
plt.show()
```

**⚙️ Comentario de funcionamiento:**
- **Procesamiento:** dentro del mismo bucle que acumula los totales por categoría, se añade una cadena `if/elif/else` que clasifica cada venta (`t = v["total"]`) en uno de cuatro rangos de monto, incrementando el contador correspondiente en el diccionario `rangos`.
- **Dashboard:** `plt.subplots(3, 2, figsize=(14, 15))` crea una figura con 6 espacios organizados en 3 filas y 2 columnas; cada `axs[fila, columna]` es un "subgráfico" independiente donde se dibuja un tipo distinto de visualización (barras horizontales, barras verticales, pastel, dona).
- `bar_label()` añade automáticamente el valor numérico encima de cada barra, con el formato de moneda `'$%1.2f'`.
- El gráfico de dona (gráfico 4) es en realidad un `pie` normal al que se le superpone un círculo blanco (`plt.Circle`) en el centro mediante `add_artist()`, creando el efecto visual de "anillo".
- `plt.tight_layout()` ajusta automáticamente los espacios entre subgráficos para que no se superpongan los títulos, y `plt.show()` finalmente renderiza la ventana con el dashboard completo.

---

### 16.4 Generar un archivo Excel con 500 registros reales

**📌 Enunciado:** Crear un archivo `.xlsx` con 500 registros de ventas simuladas usando nombres de clientes reales (en lugar de "Cliente 1, Cliente 2...").

**💡 Explicación / Definición:** La librería `pandas` permite trabajar con datos tabulares mediante la estructura `DataFrame` (similar a una hoja de cálculo). `pd.DataFrame(lista_de_diccionarios)` convierte una lista de registros en una tabla, y `.to_excel("archivo.xlsx", index=False)` la exporta a un archivo Excel real; `index=False` evita que pandas agregue una columna extra con el número de fila.

```python
# ✅ PRIMERO: GENERAR EL ARCHIVO EXCEL (500 registros reales)

import pandas as pd
import random

# Nombres reales (lista compacta pero auténtica)
nombres_reales = [
    "Juan Pérez", "María Gómez", "Carlos Ramírez", "Ana Martínez", "Luis Rodríguez",
    "Pedro Sánchez", "Laura Fernández", "José Castillo", "Elena Vargas", "Miguel Torres",
    "Beatriz Herrera", "Diego Cruz", "Sofía Morales", "Ricardo Peña", "Valeria Soto",
    "Gabriel Navarro", "Camila Duarte", "Andrés Paredes", "Paola Jiménez", "Samuel Batista",
    "Rosa Méndez", "Javier Aquino", "Patricia Lora", "Fernando Gil", "Daniela Rivas",
    "Héctor Guzmán", "Isabel Cabrera", "Manuel Tejada", "Carmen Salcedo", "Roberto Núñez"
]

productos = ["Laptop", "Celular", "Tablet", "Audífonos", "Monitor"]
vendedores = ["Ana", "Carlos", "Beatriz", "Diego", "Elena"]
regiones = ["Norte", "Sur", "Centro"]
metodos_pago = ["Efectivo", "Tarjeta", "Transferencia"]

# Generar 500 registros reales
data = []
for _ in range(500):
    data.append({
        "Cliente": random.choice(nombres_reales),
        "Vendedor": random.choice(vendedores),
        "Producto": random.choice(productos),
        "Método_Pago": random.choice(metodos_pago),
        "Región": random.choice(regiones),
        "Total": round(random.uniform(50, 1500), 2)
    })

df = pd.DataFrame(data)

# Guardar archivo Excel
df.to_excel("ventas_500_registros.xlsx", index=False)

print("Archivo Excel generado correctamente: ventas_500_registros.xlsx")
```

**⚙️ Comentario de funcionamiento:** Se construye primero una lista de 30 nombres reales; luego un bucle `for _ in range(500)` genera 500 diccionarios, cada uno eligiendo aleatoriamente un nombre, vendedor, producto, método de pago, región y un total decimal aleatorio. Esa lista de 500 diccionarios se convierte en un `DataFrame` de pandas y se exporta directamente a un archivo `.xlsx` en el directorio de trabajo.

---

### 16.5 Dashboard leyendo los datos desde el archivo Excel generado

**📌 Enunciado:** Ajustar el dashboard de 6 gráficos para que, en lugar de generar datos aleatorios en memoria, lea los 500 registros directamente desde el archivo Excel creado en el ejercicio anterior.

**💡 Explicación / Definición:** `pd.read_excel("archivo.xlsx")` carga el contenido del archivo en un `DataFrame`. `.to_dict(orient="records")` convierte ese `DataFrame` en una lista de diccionarios (misma estructura que `historial_ventas` en los ejercicios anteriores), y `.unique()` extrae los valores distintos de una columna (por ejemplo, todos los productos sin repetir), permitiendo reconstruir los diccionarios de resumen sin tener que escribir las categorías manualmente.

```python
# ✅ SEGUNDO: AJUSTAR TU DASHBOARD PARA LEER EL EXCEL DESDE TU PC

import pandas as pd
import matplotlib.pyplot as plt

# === LEER ARCHIVO DESDE TU PC ===
df = pd.read_excel("ventas_500_registros.xlsx")

# === EXTRAER COLUMNAS ===
historial_ventas = df.to_dict(orient="records")

# === DICCIONARIOS DE ACUMULACIÓN ===
productos = df["Producto"].unique()
vendedores = df["Vendedor"].unique()
regiones = df["Región"].unique()
metodos_pago = df["Método_Pago"].unique()
clientes = df["Cliente"].unique()

resumen_productos = {p: 0.0 for p in productos}
resumen_vendedores = {v: 0.0 for v in vendedores}
resumen_regiones = {r: 0.0 for r in regiones}
resumen_pagos = {m: 0.0 for m in metodos_pago}
resumen_clientes = {c: 0.0 for c in clientes}

rangos = {
    "50 - 300": 0,
    "301 - 700": 0,
    "701 - 1100": 0,
    "1101 - 1500": 0
}

# === PROCESAMIENTO ===
for v in historial_ventas:
    resumen_productos[v["Producto"]] += v["Total"]
    resumen_vendedores[v["Vendedor"]] += v["Total"]
    resumen_regiones[v["Región"]] += v["Total"]
    resumen_pagos[v["Método_Pago"]] += v["Total"]
    resumen_clientes[v["Cliente"]] += v["Total"]

    t = v["Total"]
    if 50 <= t <= 300:
        rangos["50 - 300"] += 1
    elif 301 <= t <= 700:
        rangos["301 - 700"] += 1
    elif 701 <= t <= 1100:
        rangos["701 - 1100"] += 1
    else:
        rangos["1101 - 1500"] += 1

# === GRÁFICOS (los mismos 6 que ya tienes) ===
fig, axs = plt.subplots(3, 2, figsize=(14, 15))
fig.suptitle("DASHBOARD INTEGRADO DE RESUMEN DE VENTAS (500 registros reales)", fontsize=16, fontweight='bold')

# 1. Producto
bars1 = axs[0, 0].barh(list(resumen_productos.keys()), list(resumen_productos.values()), color='skyblue')
axs[0, 0].set_title("Ventas por Producto")
axs[0, 0].bar_label(bars1, fmt='$%1.2f')

# 2. Vendedor
bars2 = axs[0, 1].bar(list(resumen_vendedores.keys()), list(resumen_vendedores.values()), color='lightgreen')
axs[0, 1].set_title("Ventas por Vendedor")
axs[0, 1].bar_label(bars2, fmt='$%1.2f')

# 3. Región
axs[1, 0].pie(list(resumen_regiones.values()), labels=list(resumen_regiones.keys()), autopct='%1.1f%%')
axs[1, 0].set_title("Ventas por Región")

# 4. Método de Pago (Dona)
axs[1, 1].pie(list(resumen_pagos.values()), labels=list(resumen_pagos.keys()), autopct='%1.1f%%')
centro = plt.Circle((0,0), 0.70, fc='white')
axs[1, 1].add_artist(centro)
axs[1, 1].set_title("Métodos de Pago")

# 5. Top 5 Clientes
top_5 = sorted(resumen_clientes.items(), key=lambda x: x[1], reverse=True)[:5]
bars5 = axs[2, 0].bar([c[0] for c in top_5], [c[1] for c in top_5], color='orchid')
axs[2, 0].set_title("Top 5 Clientes")
axs[2, 0].bar_label(bars5, fmt='$%1.2f')

# 6. Rangos
axs[2, 1].bar(list(rangos.keys()), list(rangos.values()), color='orange')
axs[2, 1].set_title("Rangos de Monto")

plt.tight_layout(rect=[0, 0, 1, 0.96])
plt.show()
```

**⚙️ Comentario de funcionamiento:** En lugar de simular datos con `random`, el script lee el archivo `ventas_500_registros.xlsx` generado en el ejercicio 14.4 usando `pd.read_excel()`. Las categorías (productos, vendedores, regiones, etc.) ya no se escriben manualmente en listas, sino que se extraen dinámicamente de las columnas del propio archivo con `.unique()`. El resto de la lógica de acumulación, clasificación por rangos y generación del dashboard de 6 gráficos es idéntica a la del ejercicio 14.3, demostrando cómo pasar de datos simulados en memoria a datos reales provenientes de una fuente externa.

---

## 17. 🧾 Glosario completo de conceptos y operadores usados

| Concepto / Operador | Definición breve y uso |
|---|---|
| `int`, `float`, `complex` | Tipos numéricos primitivos: enteros, decimales/racionales de coma flotante y números complejos con unidad imaginaria `j` ($a+bj$). |
| `str`, `bool`, `None` | Cadena de texto Unicode, valor lógico booleano (`True`/`False`) y objeto singleton `NoneType` que denota ausencia intencional de valor. |
| `"=" * N` (Repetición) | Operador de multiplicación aplicado a cadenas de texto; replica el contenido de texto $N$ veces de forma eficiente. |
| `list` (`[]`), `tuple` (`()`) | Colecciones ordenadas; las listas son mutables (modificables) y las tuplas son inmutables (fijas). |
| `dict` (`{}`) | Colección asociativa de pares clave-valor (`{"clave": valor}`). |
| `//` (División entera) | Realiza la división descartando los decimales (devuelve solo el cociente entero). |
| `%` (Módulo) | Devuelve el residuo de la división entera; fundamental para pruebas de paridad y divisibilidad. |
| `**` (Potencia) | Operador de exponenciación (`a ** b` calcula $a^b$). |
| `==`, `!=`, `<`, `>`, `<=`, `>=` | Operadores de comparación relacional que devuelven un valor booleano (`True` o `False`). |
| `and`, `or`, `not` | Operadores lógicos de conjunción (ambos verdaderos), disyunción (al menos uno verdadero) y negación. |
| `all(iterable)` | Evalúa si **todos** los elementos de una colección o generador son verdaderos; optimizado con evaluación de corto circuito. |
| `set()` | Colección no ordenada de elementos únicos (sin duplicados); ideal para comprobar si todas las diferencias o razones son idénticas (`len(set(...)) == 1`). |
| Progresión Aritmética | Sucesión numérica donde la diferencia entre términos adyacentes es constante ($a_{i+1} - a_i = d$). |
| Progresión Geométrica | Sucesión numérica donde el cociente entre términos adyacentes es constante ($a_{i+1} / a_i = r$). |
| `end=" "` en `print()` | Parámetro que sustituye el salto de línea por un espacio para imprimir números en forma horizontal continua. |
| `ax.twinx()` | Crea un segundo eje Y (eje gemelo) con escala independiente compartiendo el mismo eje horizontal X; ideal para diagramas de Pareto y métricas de diferente magnitud. |
| `Series.cumsum()` | Función acumulativa de pandas que suma secuencialmente los valores fila por fila a lo largo de una columna. |
| `ax.axhline(y)` | Traza una línea recta horizontal de referencia sobre el eje en la coordenada Y especificada (ej. línea de umbral del 80%). |
| `plt.savefig(archivo)` | Guarda la figura o dashboard renderizado en disco en formato de imagen (`.png`, `.jpg`, `.pdf`, `.svg`). |
| `Series.rolling(window=N)` | Crea una ventana deslizante de tamaño $N$ sobre los datos de una columna para calcular agregaciones móviles (`.mean()`, `.sum()`, `.std()`). |
| Media Móvil Simple (SMA) | Método de filtrado y suavizado estadístico que atenúa el ruido a corto plazo para aislar la tendencia fundamental de una serie temporal. |
| `plt.legend()` | Genera la caja de leyenda informativa que vincula los colores y estilos de trazo con sus etiquetas (`label`). |
| `Series.apply(funcion)` | Ejecuta una función personalizada fila por fila sobre una columna de pandas, generando una transformación vectorizada de datos. |
| `DataFrame.groupby(col)[metrica].sum()` | Operación analítica de agrupación que condensa registros múltiples y calcula sumatorias por categoría (equivalente a `GROUP BY` de SQL o tablas dinámicas). |
| Paleta Semafórica | Técnica de visualización consistente en usar verde, amarillo, naranja y rojo para comunicar de forma intuitiva e inmediata niveles de riesgo o alerta. |
| `Series.map(diccionario)` | Mapea y traduce valores de una columna sustituyendo cada clave por su valor asociado (ideal para asignar colores `#hex` a estados de negocio). |
| Ratio DTI (Debt-to-Income) | Indicador financiero que mide el porcentaje del ingreso mensual destinado al servicio de la deuda; umbral estándar bancario $\le 40\%$. |
| Frontera de Decisión Lineal | Línea geométrica o umbral analítico trazado en un gráfico de dispersión para separar regiones de decisión (aprobado vs rechazado). |
| Net Promoter Score (NPS) | Métrica gerencial de lealtad de clientes calculada como $(	ext{Promotores} - 	ext{Detractores}) / 	ext{Total} 	imes 100$. |
| `wedgeprops={'width': W}` | Parámetro de `plt.pie()` que define el grosor radial del anillo para generar gráficos de dona nativos sin necesidad de máscaras. |
| `plt.text(x, y, texto)` | Inyecta cadenas de texto formateadas en coordenadas personalizadas del gráfico (utilizado para incrustar métricas KPI centrales). |
| `plt.fill_between(..., where=cond)` | Aplica sombreado de área condicional entre dos curvas (ideal para superávit vs déficit o bandas de confianza). |
| `plt.barh()` | Traza barras horizontales; formato predilecto para clasificaciones, rankings y categorías con nombres extensos. |
| Parámetro `explode` | Separa físicamente una o más cuñas de un gráfico de pastel o dona alejándolas radialmente del centro para enfatizarlas. |
| `pctdistance` | Controla la distancia radial desde el centro hasta donde se imprimen los textos porcentuales en gráficos circulares. |
| `plt.step(..., where='post')` | Traza curvas escalonadas para modelar procesos discretos por periodos (supervivencia, cohortes de retención, inventarios). |
| `plt.ticklabel_format(style='plain')` | Fuerza la representación numérica habitual en los ejes numéricos suprimiendo la notación científica. |
| Sistema Francés de Amortización | Modelo financiero de cuota constante nivelada para préstamos a largo plazo ($P 	imes [i(1+i)^n]/[(1+i)^n - 1]$). |
| `plt.axvline(x)` | Traza una línea vertical de referencia a través de todo el gráfico (crucial para matrices de 4 cuadrantes y metas). |
| `zorder` | Parámetro de matplotlib que controla el orden de superposición visual de capas (los elementos con mayor `zorder` se dibujan encima). |

| `if / elif / else` | Estructura condicional: ejecuta código según si una condición es verdadera o falsa. |
| `and` | Operador lógico: requiere que ambas condiciones sean verdaderas. |
| `match / case` | Estructura de comparación de patrones (alternativa moderna a múltiples `if/elif`). |
| `try / except` | Manejo de errores: evita que el programa se detenga ante una excepción. |
| `for` | Bucle que recorre una secuencia (lista, rango, etc.) un número definido de veces. |
| `while` | Bucle que se repite mientras una condición sea verdadera. |
| `range(inicio, fin, paso)` | Genera una secuencia de números; el `fin` no se incluye. |
| `break` | Corta la ejecución de un bucle inmediatamente. |
| `for...else` | El `else` de un `for` se ejecuta solo si el bucle terminó sin `break`. |
| `%` (módulo) | Devuelve el residuo de una división; útil para par/impar. |
| `def` (función) | Bloque de código reutilizable que se define una vez y se ejecuta al ser llamado. |
| `random.choice()` / `random.uniform()` | Selección y generación de valores aleatorios. |
| `sorted(..., key=..., reverse=True)` | Ordena una colección según un criterio, de mayor a menor. |
| `pandas.DataFrame` | Estructura tabular para manejar datos (como una hoja de cálculo). |
| `matplotlib.pyplot` | Librería para crear gráficos y visualizaciones. |
| `plt.plot()` | Gráfico de líneas; muestra tendencias en el tiempo. |
| `plt.bar()` / `plt.barh()` | Gráfico de barras verticales/horizontales; compara magnitudes entre categorías. |
| `plt.scatter()` | Gráfico de dispersión; muestra correlación entre dos variables. |
| `plt.pie()` | Gráfico de pastel; muestra proporciones de un total. |
| `plt.hist()` | Histograma; muestra la distribución/frecuencia de datos agrupados en rangos. |
| `plt.subplots(filas, columnas)` | Crea una figura con varios gráficos organizados en cuadrícula. |