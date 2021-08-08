
# **EL ALGORITMO ES CORRECTO**

*Objetivo*:

Teniendo como insumo las bases de datos entregadas por la empresa Habi, se quiere construir, modelar y predecir el precio de oferta (asking price) que Habi debe dar al inmueble que desea adquirir.

***Integrantes***

*Estadísticas Universidad Nacional de Colombia*
- Sara Lucia Acosta, slacostap@unal.edu.co
- Valeria Bejarano Salcedo, vbejaranos@unal.edu.co

# Descripción de la metodología:
Se realizo un completo análisis de la  la base de datos, teniendo como insumo que  para el modelamiento son necesarios datos de buena calidad, luego bajo la filosofia de garbage in, garbage out se realiza una recopilación y procesamiento de la información para entender y limpiar más de 250 mil registros que se nos entregó. Se consideraron variables importantes:

 * area
 * baños
 * estrato
 * garajes
 * habitaciones
 * piso
 * valoradministracion
 * valorventa
 * latitud
 * longitud
 * tipoinmueble
 * tiponegocio
 * tiempodeconstruido.
 * Entre otras 
Se realizo una filtración de datos atipicos y validaciones sobre las caracteristicas de los inmuebles. También se hizo un análisis espacial, intersectando los puntos con las manzanas de Bogotá y contrastando el valor por metro cuadrado de un lote, tomando en cuenta características del entorno,  con los datos oficiales del catastro de Bogota. Luego se codificaron las variables categóricas, para poder entrenar a el modelo.
