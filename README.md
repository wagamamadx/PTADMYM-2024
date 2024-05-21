# PTADMYM-2024

## Web scraping.
Se debe extraer los siguientes datos: CÓDIGO DE PRODUCTO, DESCRIPCIÓN, PRECIO BASE, PRECIO CON DESCUENTO e IMÁGEN DEL PRODUCTO. Así mismo se debe calcular el descuento(%) y crear un nuevo campo del mismo en la tabla de base de datos.
Esperamos ver tus avances graduales en ciclos cortos. Esta prueba támbien se considera que tantos pull requests realices por cada avance pequeño que realices(menos de 100 lines de código). Por lo que te proponemos:

1. Crea un fork de este README.MD
2. Cubre tu código con pruebas(no es prioridad)
3. Haz múltiples _pull requests_ pequeños (menos de 100 líneas cada uno)
4. Usa GitHub (_issues_ y _pull requests_) como el medio de comunicación principal.

## Rúbrica

El objetivo de esta prueba técnica es evaluar las habilidades para el trabajo colaborativo a
distancia. Para eso usaremos los siguientes rubros:

- **Capacidad para el trabajo colaborativo a distancia**:
  - [ ] Uso de Git: Los mensajes son informativos del porqué, las consignaciones son pequeñas y los
    nombres de las ramas dan información del objetivo de los cambios
  - [ ] Habilidades de comunicación mediante GitHub (_issues_ y _pull requests_): La comunicación es
    amable, la descripción es clara y da formato utilizando _Markdown_
  - [ ] Solicitud de revisiones: Utilización de [las
    características](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)
    de GitHub para indicar que terminó una corrección y que está solicitando una nueva revisión
  - [ ] Asimilación de retroalimentación: Las correcciones solicitadas en un _pull request_ ya no se
    repiten en los siguientes _pull requests_

- **Buenas prácticas en programación**:
  - [ ] Código limpio
  - [ ] Pruebas unitarias(para esta prueba no es necesario completarla).
  - [ ] Refactorización

## Sugerencias

- Estudia estas referencias:
    - [Guía de estilo de Ciencia de Datos en GECI](https://islas.dev/guia_de_estilo/)
    - [How to Make Your Code Reviewer Fall in Love with You](https://mtlynch.io/code-review-love/)
    - [The pull request author’s guide to getting through code review](https://google.github.io/eng-practices/review/developer/)
- Crea _pull requests_ pequeños; un _pull request_ de 100 líneas es demasiado grande.
- Se amable, explica el porqué de las cosas, usa lenguaje simple y claro.
- Comunícate mucho y hazlo mediante GitHub.

## Herramientas
1. La fuente donde se realizará la extracción de datos es: https://volvorepuestos.com.pe/
2. Puedes usar Nodejs o Python 
3. Puedes usar cualquier librería para nodejs se recomienda puppeteer, cryto, delay.
4. Puedes usar cualquier libería para Python se recomienda Jupiter Notebook, Selenium, etc.
5. Para transformar los datos puedes usar: XML, JSON.
6. Para almacenar los datos puedes usar cualquier motor de base de datos(mysql,sql,postgreSQL,db2,oracle, etc).

## REGLAS
Los respuestos obtenidos se debe de FILTRAR por Nombre de producto, Precio mínimo, Precio máximo. Este ultimo se van a reflejar despues de haber procesado la informacion.

## Publicación
El repositorio se pondrá en publico y se compartira el enlace por correo a: jmeza@mym.com.pe, jtrillo@mym.com.pe, gsaavedra@mym.com.pe

## Resultados finales
En el repositorio se espera lo siguiente:

- ASSETS
- CARPETA/DIRECTORIO APLICACIÓN
- QUERY.SQL (despues de almacenar los datos puedes extraer una query para obtener la BD).
- repuesto.csv (TABLA del result final)
- REPUESTOS.json (LOS OBJETOS TRANSFORMADOS EN FORMATO JSON O XML).


## Referencias

- [Guía de estilo de Ciencia de Datos en GECI](https://islas.dev/guia_de_estilo/)
- [How to Make Your Code Reviewer Fall in Love with You](https://mtlynch.io/code-review-love/)
- [Revisiones en GitHub](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)
- [The pull request author’s guide to getting through code review](https://google.github.io/eng-practices/review/developer/)
- [_Forkeado_ de un repositorio](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)
