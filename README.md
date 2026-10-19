# Grafo de conocimiento de 2º de Business Data Analytics

Recorrí todos los apuntes, código y entregas de mi segundo curso del grado en Business Data Analytics (Mondragon Unibertsitatea) y los convertí en un mapa interactivo: **2.677 conceptos unidos por 4.277 relaciones**.

**Ver el grafo:** https://marioabajas.github.io/grafo-bdata2/

## Qué se ve

Cada punto es un concepto y cada línea, una relación entre dos conceptos que aparecen juntos en el material del curso. El color indica el área a la que pertenece:

| Área | Conceptos |
|---|---|
| Programación | 1.037 |
| Visualización | 475 |
| Data Science | 442 |
| Data Mining | 281 |
| Big Data y ecosistema | 149 |
| Proyecto personal | 93 |
| Cliente digital | 51 |
| Matemáticas | 23 |
| Otros | 126 |

Programación ocupa casi el 40 % del grafo: es la base sobre la que se apoyan el resto de asignaturas.

En la página puedes:
- pasar el ratón por un concepto para ver con qué se relaciona,
- buscar un concepto por nombre,
- filtrar por área.

Solo se muestran los nombres de los conceptos técnicos. El resto de nodos aparece como "Concepto de &lt;área&gt;" para no publicar contenido de los apuntes.

## Cómo está hecho

1. **Extracción:** graphify recorre la carpeta del curso (PDF, cuadernos, código y documentos) y saca los conceptos y las relaciones entre ellos.
2. **Procesado en Python:** limpieza de nodos duplicados, asignación de cada concepto a un área y cálculo de la posición de cada punto.
3. **Visualización:** una sola página HTML con [Sigma.js](https://www.sigmajs.org/), que dibuja el grafo en el navegador sin servidor.

## Archivos

- `index.html`: la página con el visor.
- `data.js`: los nodos, las relaciones y las áreas.

## Autor

Mario Abajas Zabala · [LinkedIn](https://www.linkedin.com/in/mario-abajas-927793389) · [Malt](https://www.malt.es/profile/marioabajas)
