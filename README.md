#  Proyecto final materia Energ'ia en Edificaciones

En este repositorio se documenta la informaci'on necesaria para llevar a
cabo el proyecto final  de la materia energ'ia en edificaciones.

## Objetivo general
Hacer una simulaci'on de un espacio real, considerando cargas t'ermicas, infiltraci'on y ajustar
par'ametros para validar la simulaci'on.



#### Objetivos espec'ificos

1. Tener un modelo para simulaci'on con condiciones de frontera adecuadas y simplificaciones
geom'etricas v'alidas.
1. Definir fechas de validaci'on y generar un EPW para la validaci'on.
1. Ajustar par'ametros en simulaci'on usando m'etricas
1. Evaluar el modelo validado con ocupaci'on (1 y 2 personas) en la 'epoca  c'alida
1. Bonus points: proponer una estrategia bioclim'atica pasiva para mejorar el confort.



### Descripci'on del material

001_planos/  

D-7.skp : Sketch de la oficina de Jorge para comenzar.

Contiene un modelo en sketchup 2017 del cub'iculo, hay planos y fotos e incluso dibujos que pueden ser de ayuda para tomar decisiones en cuanto a ventanas y geometr'ia.


002_datos/

esolmet.csv : Datos meteorol'ogicos para crear el EPW

fracciones.png : Fracciones radiantes y convectivas para algunos equipos.

inventario_equipo.xlsx : Lista de equipo existente en el cub'iculo de Jorge.

mediciones.csv : Datos medidos para validar

nombres.txt : lista de nombres contenidos en mediciones.csv

nombres.xls : lista de nombres contenidos en mediciones.csv

ruoa.txt : datos meteorol'ogicos para crear el EPW


003_docs/

Tesis relacionadas con validaciones de espacios, contienen m'etricas y metodolog'ias para validar simulaciones con EnergyPlus.


## Presentaci'on

La presentaci'on debe contener los siguientes elementos:

1. Presentar el problema
1. Simplificaciones, características y datos disponibles
1. Calibración y validación (sin personas):
    1. Definir los parámetros de la calibración y validación
1. Simular temporada cálida  evaluando con PPD y PMV
    1. Jorge trabajando
    1. Jorge e invitado trabajando
1. Conclusiones
1. Bonus: Proponen y simulan estrategia bioclimática
    1. Presentan mejora del PPD y PMV

## Evaluaci'on del proyecto:

| Criterio                       |     Puntos |
| ----------------------         |---------   |
| Presentaci'on                  |     50     |
| Simplificaciones en geometr'ia |     10     |
| Condiciones de frontera        |     20     |
| Ajuste del modelo AFN          |     30     |
| Uso de m'etricas para calibrar |     30     |
| Validaci'on del modelo         |     20     |
| Total                          |     160    |
| Bonus Estrategia               |     30     |
| Bonus Repositorio              |     10     |
