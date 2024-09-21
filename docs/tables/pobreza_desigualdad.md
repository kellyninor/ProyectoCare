# Diccionario de Datos Dataframe `df_pobreza_desigualdad`

| **Columna**                             | **Descripción**                                                                                            | **Tipo de Dato** |
|-----------------------------------------|------------------------------------------------------------------------------------------------------------|------------------|
| `mes_enc`                               | Mes de la encuesta.                                                                                        | category         |
| `tipo_area`                             | Tipo de área: 1. cabecera, 2. resto (centros poblados y área rural dispersa).                              | category         |
| `region`                                | Región o dominio geográfico.                                                                               | category         |
| `tenencia_viv`                          | Tipo de tenencia de vivienda 1. Propia, totalmente pagada, 2. Propia, la están pagando, 3. En arriendo o subarriendo, 4. En usufructo, 5. Posesión sin título (ocupante), 6. Otra.                                                                                                                                   | category         |
| `linea_indig`                           | Línea de indigencia.                                                                                       | float64          |
| `linea_pobreza`                         | Línea de pobreza general.                                                                                  | float64          |
| `hogar_pobre`                           | Indicador de si el hogar es considerado pobre (1: sí, 0: no).                                              | category         |
| `hogar_indigente`                       | Indicador de si el hogar es considerado indigente  (1: sí, 0: no).                                         | category         |
| `num_pobres`                            | Número total de personas pobres en el hogar.                                                               | int64            |
| `num_indigentes`                        | Número total de personas indigentes en el hogar.                                                           | int64            |
| `factor_exp`                            | Factor de expansión utilizado en el análisis.                                                              | float64          |
| `total_personas_hogar`                  | Total de personas que habitan en el hogar.                                                                 | int64            |
| `ingresos_laborales`                    | Total de ingresos laborales del hogar.                                                                     | float64          |
| `ingresos_subsidios`                    | Total de ingresos recibidos por subsidios.                                                                 | float64          |
| `otros_ingresos_no_laborales`           | Otros ingresos no laborales recibidos por el hogar.                                                        | float64          |
| `total_ingresos_hogar`                  | Total de ingresos del hogar (laborales + subsidios + otros ingresos).                                      | float64          |
| `total_adultos`                         | Total de adultos en el hogar.                                                                              | int64            |
| `total_tercera_edad`                    | Total de personas en tercera edad (65 años o más) en el hogar.                                             | int64            |
| `total_primera_infancia`                | Total de personas en primera infancia (0-5 años) en el hogar.                                              | int64            |
| `total_infantes`                        | Total de infantes (6-11 años) en el hogar.                                                                 | int64            |
| `total_adolescentes`                    | Total de adolescentes (12-17 años) en el hogar.                                                            | int64            |
| `jh_genero`                             | Género del jefe de hogar (masculino/femenino).                                                             | category         |
| `jh_edad`                               | Edad del jefe de hogar.                                                                                    | int64            |
| `jh_nivel_educativo`                    | Nivel educativo alcanzado por el jefe de hogar.                                                            | category         |
| `jh_actividad_realizada`                | Actividad económica que realiza el jefe de hogar.                                                          | category         |
| `jh_horas_trabajo_semanales`            | Número de horas que trabaja el jefe de hogar a la semana.                                                  | float64          |
| `jh_poblacion_en_edad_de_trabajar`      | El jefe de hogar hace parte de la población en edad de trabajar.  (1: sí, 0: no).                          | category         |
| `jh_ocupado`                            | Indicador de si el jefe de hogar está ocupado (Sí/No).                                                     | category         |
| `jh_desocupado`                         | Indicador de si el jefe de hogar está desocupado (Sí/No).                                                  | category         |
| `total_dependientes`                    | Total de dependientes a cargo del jefe de hogar.                                                           | float64          |
| `ingreso_per_capita`                    | Ingreso per cápita del hogar, calculado como total_ingresos_hogar dividido por total_personas_hogar.       | float64          |
