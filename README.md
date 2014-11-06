instalacion
=======================

paso 1 
=======================

clonar el proyecto en /xampp/htdocs o /wamp/www , para esto necesita instalar http://git-scm.com/downloads 

luego se procede a clonar el proyecto :

git clone https://github.com/jpmejia/web_avanzada.git 

ingresar a http://localhost/web_avanzada

paso 2
=======================

se debe dar todo los permisos al directorio app/tmp

chmod -R 777 app/tmp

paso 3 
======================

ojo se tiene que crear la base de datos previamente en mysql 

configurar la base de datos por defecto esta configurada con 

nombre base de datos : web_avanzada

usuario : root 

pass : 

si dean modificar estos balores lo pueden hacer localmente editando el archivo 
 
app/Config/database.php