---
title: "Agrupamiento de Duplicados"
date: 2021-12-13
draft: false
weight: 58
authors: ["Katie Pearson"]
translators: ["Samanta Orellana"]
keywords: ["duplicados","especímenes duplicados"]
---

{{< notice info >}}
  Esta página describe cómo ver y enlazar por lote especímenes duplicados (especímenes del mismo taxón colectados el mismo día, por la misma persona, en el mismo lugar) usando la herramienta de Agrupamiento de Duplicados.
{{</ notice >}}

Las ocurrencias pueden ser enlazadas como duplicados individualmente durante o después del ingreso de datos utilizando herramientas en el editor de ocurrencias. Vea [esta página](https://biokic.github.io/symbiota-docs/es/editor/links/) para más información de cómo enlazar duplicados de forma individual y [esta página](https://biokic.github.io/symbiota-docs/editor/edit/duplicates/) para más información sobre el uso de la herramienta de coincidencia de duplicados durante la entrada de datos.

Las ocurrencias también pueden ser enlazadas automáticamente por lote por la herramienta de Agrupamiento de Duplicados. Esta herramienta crea un índice temporal de las fechas de colecta, números de colector y apellidos de colectores de sus ocurrencias, y después enlaza cualquier ocurrencia que comparte estas tres características.

Para ver o enlazar duplicados, navegue al Panel de Control de Administración (Mi Perfil > Manejo de Ocurrencias > nombre de la colección) y haga click en Agrupamiento de Duplicados.
* Para ver duplicados existentes, haga click en *Grupos de especímenes duplicados*
* Para ver duplicados con identificaciones taxonómicas que no encajan, haga click en *Grupos de especímenes duplicados con identificaciones conflictivas*. Un ejemplo de los resultados de esta herramienta es mostrado abajo.
* Para enlazar duplicados por lote, haga click en *Enlazar especímenes duplicados por lote*. Esto ejecutará automáticamente un script para enlazar registros, que creará los grupos de duplicados.

{{< notice note >}}
  Cuando está revisando los grupos de duplicados, puede ver el registro para cualquier ocurrencia haciendo click en el número de catálogo en letras azules.
{{</ notice >}}

![Ejemplo de Conflictos Duplicados](/symbiota-docs/images/exampleduplicateconflicts.PNG)

Aquí puede encontrar un tutorial en video sobre cómo se pueden usar las herramientas de agrupación en clústeres duplicadas para resolver identificaciones conflictivas:

{{< youtube kMUzwoHmXw4 >}}