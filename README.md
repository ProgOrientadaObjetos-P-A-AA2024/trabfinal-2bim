# Trabajo Final Segundo Bimestre

* El siguiente trabajo se lo realizará de forma grupal (grupos de máximo dos personas).

## Tema:

Aplicación conceptos de herencia - polimorfismo - base de datos

## Problemática

Las empresas de telefonía celular pueden ofrecer los siguientes planes. Todos los planes al menos debe tener las siguientes características:

### PlanCelular
- nombre y apellidos usuario tipo (tipo cadena)
- DNI propietario (tipo cadena)
- ciudad usuario (tipo cadena)
- barrio del dueño del plan
- marca de celular
- modelo del celular
- numero celular
- pago mensual

Los planes se caracterizan además y clasifican así:

### Plan Básico Económico
- minutos|costo minutos|megas expresado en gigas|costo por cada gigas|porcentaje de descuento (Ejemplo: 10%)

### Plan Plus
- minutos nacionales|costo minuto nacional|minutos internacionales|costo minuto internacional | minutos locales | costos minutos locales

### Plan Plus Max
- megas expresado en gigas|costo por cada giga|tarifa base | tarifa redes sociales

### Plan Ideal
- minutos|costo minutos|megas expresado en gigas|costo por cada gigas|costo tarifa base youtube



## Tareas:

En una clase Inicio usted debe:

- Generar un método main que permita ingresar múltiples tipos de objetos de Planes de celular.
- Se debe calcular el valor mensual a pagar de acuerdo a su contexto.
- Guardar la información de cada objeto en una base de datos (una entidad por cada clase). Se usará la base de datos SQLite.
- Obtener la información de los registros de la base de datos y presentar la información de cada objeto haciendo uso del método toString
- Generar un diagrama que involucre las clases del polimorfismo / herencia

## Recomendaciones:

- Analizar la problemática; realizar el diagrama (carpeta diagramas - solo de las clases involucradas en el **Polimorfismo**); crear la solución en Java (carpeta lenguaje-programacion)

## Proceso a seguir:

- En el método (main) de la clase a Ejecutar. En un ciclo repetitivo el usuario puede decidir que tipo de Plan desea crear para la empresa de acuerdo a las opciones: Plan Básico Económico, Plan Plus, Plan Plus Max, Plan Ideal.
- De acuerdo a la opción, el usuario ingresa por teclado los datos necesarios para crear el objeto.
- Luego de crear el objeto; se debe guardar en la base datos
- Finalizado el ciclo (cuando lo decida el usuario); se debe presentar todos los objetos guardados en la base de datos.
