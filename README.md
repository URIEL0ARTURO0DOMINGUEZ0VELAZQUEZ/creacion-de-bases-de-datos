# creacion-de-bases-de-datos
como  hacer una base de datos mysql

## Entrar mysql
**docker exec -it id-contenedor mysql -p**

### primer coman
SHOW DATABASES;

### SEGUNDO COMANDO 
CREATE DATABASE <Nombre de la base de datos>;
ejemplo
![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/creacion-de-bases-de-datos/assets/136390705/7c6f6846-b562-41fc-8ddc-ac5187b72e49)

###TERCER COMANDO
USE nombre de base de datos;

![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/creacion-de-bases-de-datos/assets/136390705/0fa964e9-215e-4498-96d0-f8f59454b556)

### cuarto comando

CREATE TABLE clima ( id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY, fecha TIMESTAMP DEFAULT CURRENT_TIMESTAMP, nombre CHAR(248) NOT NULL, temperatura FLOAT(4,2) NOT NULL, humedad INT(3)NOT NULL);

![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/creacion-de-bases-de-datos/assets/136390705/0b995683-d08e-4316-b687-2a3296430910)

### quito comando
SHOW TABLES;

### SEXTO COMANDO 
DESCRIBE clima;

![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/creacion-de-bases-de-datos/assets/136390705/270dc8ca-f47f-426d-a238-c0b38d7b07fe)

# AGREGAR DATOS

 INSERT INTO [nombre_tabla] (columnas) VALUES (valores);

  INSERT INTO clima (nombre,temperatura,humedad) VALUES ("uriel dominguez",21,50);
  #### para consultar
   SELECT * FROM clima;
   ![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/creacion-de-bases-de-datos/assets/136390705/0d05cb52-d17c-480d-ba19-cb33ed4443cb)

### consulta condicional

