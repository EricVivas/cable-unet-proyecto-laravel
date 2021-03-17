Una vez este clonado el proyecto o descargado y este ubicado el en lugar correspondiente

Mediante la linea de comandos posicionarse en la ruta del proyecto y hacer lo siguiente:

1) aplicar el comando: composer install
2) cree un nuevo archivo .env, lo puedo hacer facilmente guiandose del archivo env.example
que se ha generado al ejecutar el comando composer install
3) En el archivo .env en DB_DATABASE= depués del signo =, deberá indicar el nombre
de la base de datos con la que va a trabajar, ejemplo DB_DATABASE=cable_unet
4) aplicar el comando php artisan migrate, para crear las tablas que va a necesitar el 
proyecto en la base de datos indicada en el paso anterior.
4) aplicar el comando php artisan key:generate

Eso es todo
