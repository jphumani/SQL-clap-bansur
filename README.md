![Static Badge](https://img.shields.io/badge/SQLSERVER-%23CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=black&labelColor=%23cdcdcd) 
# Ejercicio SQL: CLAP-BANSUR 


## Objetivo 🚩

Se describe a un cliente (Clap) como poseedor de una terminal de cobros de tarjeta de crédito. Cada vez que intenta hacer un cobro guarda sus registros en su base de datos clap.csv. 
En simultáneo, esos datos son enviados de manera automática por la terminal al banco (Bansur) el cual guarda los registros en su base de datos bansur.csv.

Un mismo ID puede ser enviado varias veces. Solo será considerado el que tenga la fecha mas actualizada de entrada al banco. Luego, se considerará 'conciliable' un registro cuando se
den las siguientes condiciones:

1. Que tengan el mismo ID.
2. Que tenga los mismos 6 primeros dígitos de la tarjeta.
3. Que tengan los mismos 4 últimos dígitos de la tarjeta.
4. Que el valor pagado en la transacción sea igual o que su diferencia
esté en el rango de más o menos 0.99 pesos.
5. Que tengan la misma fecha de transacción

## Estrategia 🤔

Se plantea el uso exclusivo de lenguaje SQL.

¡Que comience la diversión! 😁🤖⌛
