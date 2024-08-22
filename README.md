# Soluciones para Desarroladores
Aqui compartiré problemas de desarrollo que resolví y podrían ser útiles a otros desarrolladores para evitar quebraderos de cabeza de una solución simple.

## SQL Server: La conversión del tipo de datos varchar en datetime produjo un valor fuera de intervalo
### Solución:
Cambiar el idioma del usuario de SQL Server. Probablemente está aceptando el formato ```d-m-Y H:i:s``` en vez de ```Y-m-d H:i:s```
Al realizar el cambio de idioma, probar la query retornará el resultado deseado...
