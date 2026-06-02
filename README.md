# Diseño y simulación de un sistema de enfriamiento y dispensado de agua

Este repositorio contiene los archivos asociados al desarrollo de un sistema compacto de enfriamiento y dispensado de agua. El diseño considera la circulación del fluido mediante bombas, tuberías e intercambiadores de calor, con el objetivo de alcanzar una temperatura adecuada de servicio en un tiempo reducido.

El proyecto contempla el funcionamiento con agua sin gas y agua carbonatada. Para este último caso, se evalúa adicionalmente el riesgo de desgasificación durante la circulación del fluido.

## Objetivo del proyecto

El objetivo es diseñar y evaluar un prototipo capaz de enfriar el agua hasta su temperatura de servicio, verificando su desempeño térmico, hidráulico y estructural antes de la fabricación.

El análisis busca determinar una configuración geométrica y operativa que permita cumplir con los requerimientos de enfriamiento, mantener pérdidas de carga admisibles y reducir la pérdida de CO₂ disuelto.

## Modelos desarrollados

El repositorio incluye modelos numéricos para estimar el tiempo de enfriamiento, las pérdidas de carga en las tuberías y accesorios, el caudal de operación de las bombas, el tiempo de residencia del fluido y el número de recirculaciones necesarias.

Para el caso de agua carbonatada, el análisis incorpora la Ley de Henry para evaluar las condiciones de equilibrio del CO₂ disuelto y un modelo basado en la Ley de Fick para estimar la pérdida de gas durante la operación.

También se incluyen simulaciones Monte Carlo para estudiar la variabilidad de los resultados frente a cambios en los parámetros principales del sistema.

## Análisis estructural

El diseño considera verificaciones mediante el método de elementos finitos para los componentes fabricados especialmente para el prototipo, como los soportes estructurales y las piezas sometidas a cargas de accionamiento manual.

## Contenido del repositorio

Este repositorio almacena los scripts de simulación, los archivos de análisis, los resultados obtenidos, las figuras utilizadas en la documentación y los archivos complementarios del proyecto.

## Estado del proyecto

El proyecto se encuentra en etapa de desarrollo y validación del diseño.