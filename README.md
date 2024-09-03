# Tarea 1 🤖: Casos de contagio de dengue (2016)
### Alumno: Nicolas Silva Andujar (20200832)
En la presente tarea se analizan los resultados de contagio del dengue para las semanas del 2016. La información corresponde al portal "Datos Abiertos" del Gobierno del Perú.

### Diccionario de datos 

| Variable     | Tipo    | Denominación                            | Valores                               |
|--------------|----------|-----------------------------------------|-------------------------------------------|
| departamento | object| Región geográfica                       |                                           |
| provincia    | object | Provincia                               |                                           |
| distrito     | object | Lugar probable de infección             |                                           |
| ano          | int64  | Año                                     |                                           |
| semana       | int64  | Semana de inicio de síntomas            |                                           |
| sexo         | object | Sexo                                    | M = Masculino, F = Femenino               |
| edad_grupos         | int64 | Edad del paciente                |   a_menor_a_16,b_entre_16y50,c_mayor_a_50    |
| enfermedad_text         | int64 | Tipo de diagnóstico          | SIN_SEÑALES, ALARMA, GRAVE                |

Para fines de la actividad, la variable "enfermedad_tex" ha sido recodificada como:
- SIN_SEÑALES':'1_SIN_SEÑALES'
- 'ALARMA':'2_ALARMA'
- 'GRAVE':'3_GRAVE'

----------------------------------------------------------------------------------------------------------------
### Enlace a la tarea 👾
https://nicosil02.github.io/


