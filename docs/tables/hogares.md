## Descripción de las Columnas del DataFrame Hogares (`df_hogares`)

| Variable        | Descripción                                                                                                                                                 | Tipo de Dato          |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|
| **directorio**  | Identificador único del hogar.                                                                                                                              | `int`                 |
| **secuencia_p** | Secuencia de identificación adicional para cada hogar.                                                                                                      | `int`                 |
| **mes**         | Mes de la encuesta.                                                                                                                                         | `str`                 |
| **clase**       | Tipo de área: 1. cabecera, 2. resto (centros poblados y área rural dispersa).                                                                               | `int`                 |
| **dominio**     | Región o dominio geográfico.                                                                                                                                | `str`                 |
| **p5090**       | La vivienda ocupada por este hogar es: 1. Propia, totalmente pagada, 2. Propia, la están pagando, 3. En arriendo o subarriendo, 4. En usufructo, 5. Posesión sin título (ocupante), 6. Otra. | `int`                 |
| **p5100**       | ¿Cuánto pagan mensualmente por cuota de amortización? (valor en Pesos). Cuando el informante declara que no sabe el valor de la cuota, p5100 = 98, si no informa el valor de la cuota p5100 = 99. | `float`               |
| **p5130**       | Si tuviera que pagar arriendo por esta vivienda, ¿cuánto estima que tendría que pagar mensualmente? Si no es posible obtener este valor p5130 = 99.         | `float`               |
| **nper**        | Número total de personas en el hogar.                                                                                                                       | `int`                 |
| **npersug**     | Número de personas en la unidad de gasto.                                                                                                                   | `int`                 |
| **ingtotug**    | Ingreso total de la unidad de gasto antes de imputación de arriendos a propietarios y usufructuarios.                                                       | `float`               |
| **ingtotarr**   | Ingreso total de la unidad de gasto con imputación de arriendo a propietarios y usufructuarios.                                                             | `float`               |
| **ingpcug**     | Ingreso percápita de la unidad de gasto con imputación de arriendo a propietarios y usufructuarios.                                                         | `float`               |
| **li**          | Línea de indigencia. Valor de la canasta básica de alimentos que establece el límite de ingresos por debajo del cual un hogar es considerado en pobreza extrema. | `float`               |
| **lp**          | Línea de pobreza. Valor de la canasta básica de bienes que establece el límite de ingresos por debajo del cual un hogar es considerado en pobreza.           | `float`               |
| **pobre**       | Variable que identifica los hogares en condiciones de pobreza. (1: sí, 0: no).                                                                             | `int`                 |
| **indigente**   | Variable que identifica los hogares en condiciones de pobreza extrema (1: sí, 0: no).                                                                       | `int`                 |
| **npobres**     | Número de personas en hogares clasificados como pobres.                                                                                                     | `int`                 |
| **nindigentes** | Número de personas en hogares clasificados en pobreza extrema.                                                                                              | `int`                 |
| **fex_c**       | Factor de expansión anualizado.                                                                                                                             | `float`               |

**Fuente:** [Medición de Pobreza Monetaria y Desigualdad 2023](https://www.dane.gov.co) - DANE
