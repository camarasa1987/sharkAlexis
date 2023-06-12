# Proyecto Sharks [Alexis Camarasa]

El objetivo del proyecto es limpiar los datos para que estos puedan leerse de una manera más amena para aquel usuario que desee chequear este data frame.

Pasos seguidos:

1) Indago en cuales son los nombres de las columna columnas del data frame.
2) Compruebo que tengo muchos nulos.
3) Compruebo que en el "tail" de mi data frame está completo de valores de nulos.
4) Elimino toda aquella filas que tenga más de la mitad de los valores nulos.
5) Completo todos los valores nulos de la columna "year" y "original order" con "0".
6) Completo todos los valores nulos restantes con "unknown".
7) Compruebo que no ya no tengo valores nulos.
8) Renombro las columnas de manera homogénea
9) Convierto de float a enteros los valores de la columna "Year".
10) He cambiado en la columna Nombre el output "male" por "Unknow.
11) Reordeno la columna "Case_Number" para que me quede los números de caso homogéneos y además, de esta manera, logro que me muestre los casos empezando por el más reciente y terminando por el más antiguo.
12) Compruebo que no sean exactamente iguales 2 columnas que aparentan ser similares ('Href','Href_Formula'). Realizo el mismo procedimiento para otro 2 pares de columnas ('Case_Number1','Case_Number2') y ('Unnamed_22','Unnamed_23')
13) Convierto de float a enteros los valores de la columna "Original_Order"
14) Noto que la columna sex tiene más de los 3 resultados posibles se deberían ver. Procedo a presentar de manera homogénea estos datos
15) Presento los datos de la columna "Injury", "Country" y "Type" empezando con mayúscula y continuando en minúscula.
16) Dentro de la columna "Country" elimino los espacios al final de cada valor de la cadena.
17) Noto que la columna Fatal tiene más de los 3 resultados posibles que debería tener. Agrupo los datos en las 3 resultados que puede arrojar esta columna (yes, no or unknown).
18) Dentro de la columna "Type" consiero que Boat y Boatomg se pueden agrupar dentro de Boating. Invalid lo quiero expresar como Unknown.
19) Dentro de la columna "Área"  borro los espacios a la izquierda y a la derecha de mis datos
20) Dentro de la columna "Activity" reemplazo los dobles espacios por espacios simples.(existían actividades compuestas por más de una palabra separadas con múltiples espacios)
21) Convierto la columna "Age" de objeto a enteros y he rellenado los errores con el valor 0.
22) He notado que puedo rellenar algunos unknowns de la columna Fatal ya que en la columna Injury está cargado el valor FATAL
23) Creo una función para agrupar los valores la columna Age y así reducir la cantidad de edades distintas en grupos por edad. Estos nuevos valores los ingreso en la columna "Unname_22" y renombro esta columna como "Age_Range"
24) Creo una función para agrupar y así reducir la cantidad de horas del día en periodos preestablecidos. Estos nuevos valores los ingreso en la columna "Unname_23" y renombro esta columna como "Time_of_Day"
25) Re-ordeno  el orden de las columnas agrupando del lado izquierdo aquellas que poseen información del caso y del lado derecho las columnas con información personal.
26) Creo una función para agrupar por siglos. Los resultados los plasmo en la columna "Case_Number1". Luego re-nombro esta ultima columna como "Century".

