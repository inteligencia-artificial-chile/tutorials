## Asterisk en Instancia AWS EC2 (Centos)

### Paso 1 | Activar Instancia

Comenzaremos la creación de nuestra instancia desde el servicio EC2 en nuestra cuenta de AWS, activaremos una instancia
`Amazon Linux AMI 2018.03.0 (HVM), SSD Volume Type` del tipo `t2.micro` y dejamos el **Security Group** que se crea por
defecto. Por último, creamos un key pair llamado **asterisk.pem** y publicaremos nuestra Instancia.

<img src="https://s3.amazonaws.com/ia-chile/images/tutorials/capture_asterisk_step_1.png" width="50%" height="auto">

### Paso 2 | Instalación de dependencias

Ingresamos a nuestra instancia a través de ssh utilizando el archivo pem generado


