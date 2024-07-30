### Trabajo Práctico Grupal de Estructuras de Datos

**Objetivo:**
El objetivo de este trabajo práctico es aplicar los conceptos aprendidos en clase sobre grafos, recuperación de información de la web y persistencia de datos. Los estudiantes trabajarán en grupos de 4 o 5 integrantes para implementar un crawler, construir un grafo de la web y realizar operaciones avanzadas sobre este grafo, incluyendo el cálculo del PageRank y la identificación de componentes fuertemente conexas.

**Enunciado:**

#### Parte 1: Web Crawling

1. **Implementación del Crawler**
    - Desarrolla un crawler que navegue por el sitio web `untref.edu.ar`, comenzando desde una URL dada.
    - El crawler debe recolectar información sobre los enlaces internos del dominio `untref.edu.ar`.
    - Almacena los datos recolectados en archivos CSV, incluyendo la URL de origen, la URL de destino y cualquier información adicional relevante (como el texto del enlace).

#### Parte 2: Construcción del Grafo

1. **Definición y Construcción del Grafo**
    - Define una clase `GrafoWeb` para representar un grafo dirigido de las páginas de `untref.edu.ar`.
    - Cada nodo del grafo representará una página web del dominio, y cada arista representará un enlace entre páginas.
    - Implementa métodos para agregar nodos y aristas al grafo utilizando los datos recolectados por el crawler.
    - Visualiza el grafo de manera gráfica utilizando bibliotecas como `networkx` y `matplotlib`.

#### Parte 3: Cálculo del PageRank

1. **Implementación del Algoritmo de PageRank**
    - Implementa el algoritmo de PageRank para calcular la importancia de cada página dentro del dominio `untref.edu.ar`.
    - Asegúrate de manejar adecuadamente los enlaces salientes y entrantes, así como las páginas sin enlaces salientes (dangling nodes).

2. **Resultados del PageRank**
    - Almacena los resultados del PageRank en un archivo CSV, incluyendo la URL de la página y su valor de PageRank.
    - Visualiza los resultados en forma de gráfico, mostrando las páginas con los valores de PageRank más altos.

#### Parte 4: Componentes Fuertemente Conexas

1. **Identificación de Componentes Fuertemente Conexas**
    - Implementa un algoritmo para encontrar las componentes fuertemente conexas (SCC) del grafo.
    - Escribe un programa que utilice este algoritmo para identificar y listar todas las SCC del grafo de `untref.edu.ar`.

2. **Visualización de las SCC**
    - Visualiza las componentes fuertemente conexas en el grafo, utilizando colores o etiquetas distintas para cada SCC.
    - Almacena los resultados en un archivo CSV, incluyendo las URLs de las páginas en cada SCC.

#### Parte 5: Persistencia de Datos

1. **Guardado y Carga del Grafo**
    - Guarda el grafo construido y los resultados de las operaciones en archivos CSV.
    - Implementa funciones para leer y escribir datos en estos archivos, asegurando que se manejen posibles excepciones.

#### Entregables

1. **Código Fuente:**
    - Todo el código fuente de los programas, organizado en carpetas según la funcionalidad (crawler, grafo, PageRank, SCC, persistencia de datos).

2. **Documentación:**
    - Documentación del código y las decisiones de diseño.
    - Un informe detallado con la explicación de la solución y los resultados obtenidos.

3. **Datos:**
    - Archivos CSV generados durante la ejecución de los programas.
    - Ejemplos de entradas y salidas utilizadas para las pruebas.

4. **Presentación Oral:**
    - Una presentación oral explicando las soluciones implementadas y respondiendo preguntas sobre el código y los algoritmos utilizados. Las fechas de las presentaciones serán anunciadas posteriormente.

**Fecha Límite de Entrega:**
- [Inserte fecha]

**Evaluación:**
- La correcta implementación de los algoritmos y estructuras de datos.
- La eficiencia y claridad del código.
- La documentación y presentación del trabajo.
- La colaboración y el trabajo en equipo.

### Instrucciones Adicionales para el Trabajo en Grupo

- **Formación de Grupos:** Cada grupo debe estar conformado por 4 o 5 estudiantes.
- **Distribución de Tareas:** Es importante que cada integrante del grupo tenga una responsabilidad clara. Se recomienda asignar tareas específicas (por ejemplo, uno se encarga del crawler, otro del grafo, otro del cálculo del PageRank, etc.) para asegurar una distribución equitativa del trabajo.
- **Coordinación y Comunicación:** Utilicen herramientas de gestión de proyectos (como Trello o Asana) y comunicación (como Slack o WhatsApp) para coordinar el trabajo y mantener una comunicación fluida.
- **Control de Versiones:** Utilicen un sistema de control de versiones (como Git) para colaborar en el desarrollo del código y mantener un historial de cambios.

Espero que este enunciado sea útil para estructurar el trabajo práctico de tu curso de Estructuras de Datos. ¡Buena suerte!