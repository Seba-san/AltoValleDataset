
Para descargar la serie **left_05.tar**, puede utilizar el siguiente comando 

`wget -c --timeout=10 http://190.124.230.117/AVD/abril/images/left_05.tar` 

reemplazando por **left_05.tar** el archivo que busca descargar.

Debido a la existencia de microcortes se ofrece el dataset en partes de 500MB. Para descargar todas las partes con un solo comando hacer:

`wget -r  --timeout=10 --accept *.tar.part.* -nd http://190.124.230.117/AVD/abril/images/parts`

esto descargara en la carpeta que se encuentra posicionado todas las partes que estan dentro de la carpeta "parts".
Si pudo descargar los archivos particionados terminados en **.aa, .ab, ... , .zz**   entonces para obtener el archivo original hay que hacer

` cat left_05.tar.part.* > left_05.tar`
