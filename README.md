# SQL-Analytics
#Consultas hechas durante mi formación en .Monks

#Challenge 1 

#Realizar una consulta que permita auditar la distribución geográfica de la fuerza laboral. Para ello, se requiere generar un reporte que agrupe la información por país y muestre los siguientes indicadores:

Cantidad total de empleados por país.

Cantidad de puestos de trabajo distintos (IDs de puestos) asociados a los empleados de dicho país.

Una lista consolidada de los géneros presentes en cada país (sin duplicados y separados por coma).

Una lista consolidada de los estados civiles (marital status) presentes en cada país (sin duplicados y separados por coma).

El promedio de calificación de las empresas (company_rating) donde trabajan los empleados de cada país.


#Challenge 2

#Se requiere identificar cuál es el puesto de trabajo de nivel II (Seniority II) que representa la mayor inversión en salarios para una empresa específica. El reporte debe cumplir con los siguientes requisitos:

Filtrado por Seniority: Solo deben considerarse los puestos que contengan el sufijo o la clasificación 'II' en su título (ej: 'Software Engineer II').

Cálculos Agregados: Para cada combinación de puesto y empresa, calcular:

El salario total sumado (inversión agregada).

La cantidad de empleados que ocupan dicho puesto.

Una lista con los nombres completos (Nombre y Apellido) de todos los empleados en ese cargo, separados por coma.

Criterio de Selección: El resultado debe mostrar únicamente el puesto que tenga el Salario Agregado más alto de toda la base de datos


#Challenge 3

#Se requiere realizar un análisis profundo de la masa salarial distribuida por divisiones corporativas. El reporte debe consolidar la información de los empleados cuyo salario se encuentre en el rango de 50,000 a 200,000 inclusive.

Para cada división (identificada por el nombre de la compañía), el reporte debe mostrar:

Métricas Financieras: El Salario Total (suma), Salario Promedio, Salario Mínimo y Salario Máximo.

Volumen de Talento: La cantidad total de empleados por división.

Categorización de División (Labeling): Clasificar cada división según su cantidad de empleados bajo los siguientes criterios:

Pequeña: 10 empleados o menos.

Mediana: Entre 11 y 20 empleados.

Grande: Más de 20 empleados.

Requerimientos de ordenamiento: Los resultados deben presentarse de mayor a menor según el Salario Total invertido en la división

#Challenge 4

#Se solicita un informe integral para el departamento de Recursos Humanos que permita evaluar la composición demográfica de cada área y la efectividad de los procesos de selección. El reporte debe agruparse por ID de Departamento y calcular lo siguiente:

Métricas de Volumen y Edad:

Cantidad total de empleados.

Promedio de edad de los empleados (calculado a partir de su fecha de nacimiento).

Auditoría de Diversidad (Pivot de Género): Desglosar la cantidad de empleados por identidad de género, incluyendo:

Masculino, Femenino, Agénero y No Binario.

Una categoría para 'Otros géneros' que agrupe cualquier valor no mencionado anteriormente.

Indicador de Eficiencia de Reclutamiento:

Contabilizar cuántos empleados fueron contratados en una fecha posterior a la fecha en que la vacante fue marcada como 'removida' (removed_date) en el sistema.
