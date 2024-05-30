# TAREA EN CLASE SEMANA #8 : USOS DE COUNT 
## INSTRUCCIONES:
### 1.- Escribir una sentencia para contar los datos de productos donde no estén registrados los países de origen y la cuenta de los países deben estar en español:
- Sentencia: 
 ```
 SELECT COUNT (*) - COUNT (country_of_origin) AS sin_país_de_origen FROM product 
 ```
 - Captura: 
 <img src = "/home/tebux/Documentos/GitHub/gbd-deberes-tareas/src/gbd-img-week7/sin_países_faltantes.png" width = "500" alt = "firstCapture">