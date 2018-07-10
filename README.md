# Sistema Gestion Académica

## Integrantes

- Dwan Felipe Veloza Paez
- Anderson Fabian Solano Cubillos
- Charles Andres Hurtado Hidalgo

## MARCO TEÓRICO

### Serverless

Dentro de nuestra idea de negocio hemos decidido usar la informática sin servidores que básicamente nos permite mejorar el backend de nuestra propuesta Arquitectural de software al permitirnos escalar la aplicación.

![](https://d1.awsstatic.com/Test%20Images/MasonTests/Lambda_WebApplications.2139ddbc8a84f5564ee5846995f28c88e9db5c2d.png)

##### Sitio Web estático

En este módulo va a configurar Amazon Simple Storage Service (S3) para alojar los recursos estáticos para su aplicación web. En los posteriores módulos agregará la funcionalidad dinámica a estas páginas con JavaScript para llamar a las API RESTful remotas creadas con AWS Lambda y Amazon API Gateway.

##### Administración de usuarios

Amazon Cognito ofrece funciones de administración de usuarios y de autenticación para proteger la API del backend.

##### Backend sin servidor

Amazon DynamoDB ofrece una capa de persistencia en la que se pueden almacenar los datos por la función de Lambda de la API.

##### Api RESTful

JavaScript ejecutado en el navegador envía y recibe datos de una API de backend pública a través de Lambda y API Gateway.

##### Finalización de Recursos

Usted terminará un bucket de Amazon S3, un grupo de usuarios de Amazon Cognito, una función de AWS Lambda, una función de IAM, una tabla de DynamoDB, una API REST y un CloudWatch Log. Se recomienda eliminar los recursos que ya no utilice para evitar cargos no deseados.

### Miscrosevers


### Vista Introductoria

![](https://scontent.fclo1-2.fna.fbcdn.net/v/t1.0-9/34962286_1706231626162524_4713506640609935360_n.jpg?_nc_cat=0&_nc_eui2=AeFA3LABhPvfPXTEEhRH2xrynSd4duO703wb01H-4d4_EtHHYNwxuhy2ktDkXqoNOZ01OY3ys5Ae8Qeg-Hf6M3KRkzuOhidxlYetZCRlL1BrQw&oh=9dde1bffc4b4e574c5d69b7ca3ceb29a&oe=5BE9AF97)

### Vista Organizacional

![](https://scontent.fclo1-2.fna.fbcdn.net/v/t1.0-9/36124286_1706231242829229_5259527014066421760_n.jpg?_nc_cat=0&_nc_eui2=AeFgw3SnzZnwSA25rdmtcYSDc1zEJczX3vClRW_Ki5SJFx_SLUJO6-xGN0yRDLoVU0Q3ljlm8PZHimLHJsYYfkH58cefMyhM40gChdkngijhKA&oh=fe68cfd3fd798b47977763aa176355e3&oe=5BE47C19)

### Vista Actor-Cooperación

![](https://scontent.fclo1-2.fna.fbcdn.net/v/t1.0-9/36052210_1706232162829137_8419728177680613376_n.jpg?_nc_cat=0&_nc_eui2=AeGcLy-N4NJTXboSYbS2mpb8RF7cb1L67Iu9OTGolHoErYf2fi1agoB0ZKP0G_dyYTK5rZiDRkqBv4q3II2Aub-xEbxl0Ry5xrDdqbz2ookm1Q&oh=0c581a9886647b36d2965c0fa0ab5eae&oe=5BB2409C)

### Vista Funciones de Negocio

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Vista%20Funciones%20de%20Negocio.bmp)

### Vista Procesos de Negocio

#### Función Inscribir Aspirante

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20de%20inscripci%C3%B3n%20aspirante.bmp)

#### Función Activar Estudiante 

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20Activar%20estudiante.bmp)

#### Función Crear Recibo de Pago

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20Crear%20Recibo%20de%20pago.bmp)

#### Función Consignar

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20de%20consignar.bmp)

#### Función inscripción de materias

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20Inscripci%C3%B3n%20de%20materias.bmp)

#### Función Disponer Docente

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20Inscripci%C3%B3n%20de%20materias.bmp)

#### Función Gestor de Notas

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20gestor%20de%20notas.bmp)

#### Función Horario de clases

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20horario%20de%20clases.bmp)

#### Función Presupuesto Universitario

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20presupuesto%20Universidad.bmp)

#### Función Solicitar Apoyo alimentario

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Funci%C3%B3n%20solicitar%20Apoyo%20alimentario.bmp)

### Vista Aplicación Cooperación

![](https://github.com/Dwan13/GestionAcad-mica/blob/master/Im%C3%A1genes/CooApp.bmp?raw=true)

### Vista Aplicación-Negocio

#### Apoyo Alimentario

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Apoyo%20Alimentario.bmp)

#### Consignar

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Consignar.bmp)

#### Crear Estudiante

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Crear%20Estudiante.bmp)

#### Crear Recibo de pago

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Crear%20Recibo%20de%20pago.bmp)

#### Disponer Docente

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Disponer%20Docente.bmp)

#### Gestor de notas

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Gestor%20de%20notas.bmp)

#### Horario de clases

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Horario%20de%20clases.bmp)

#### Inscribir Materias

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Inscribir%20materias.bmp)

#### Inscribir Aspirante

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Inscripci%C3%B3n%20de%20aspirante.bmp)

#### Presupuesto Universitario

![](https://raw.githubusercontent.com/Dwan13/GestionAcad-mica/master/Im%C3%A1genes/Aplicaci%C3%B3n-Negoci%C3%B3n%20Presupuesto%20universidad.bmp)

### Vista de infraestructura

![](https://github.com/Dwan13/GestionAcad-mica/blob/master/Im%C3%A1genes/Infraestructura.bmp?raw=true)
