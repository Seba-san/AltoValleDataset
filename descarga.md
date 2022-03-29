Debido a la existencia de microcortes se ofrece parte del dataset en partes de 500MB. Para descargar la serie **left_05.tar**, puede utilizar el siguiente comando 
`wget -c --timeout=10 http://190.124.230.117/AVD/abril/images/left_05.tar` 

Si pudo descargar los archivos particionados terminados en **.aa, .ab, ... , .zz**   luego para obtener el archivo original hay que hacer
` cat left_05.tar.part.* > left_05.tar`
