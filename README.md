README - Crear un Repositorio en GitHub y Ejecutar Código de Operaciones Matemáticas
1. Creación de un Repositorio en GitHub
Sigue estos pasos para crear un repositorio en GitHub:

Accede a GitHub: Ingresa a GitHub y inicia sesión.

Crea un nuevo repositorio:

Haz clic en el botón “+” en la esquina superior derecha y selecciona “New repository”.

Ingresa un nombre para tu repositorio (ejemplo: operaciones-basicas).

Puedes agregar una descripción opcional.

Selecciona “Public” o “Private” según prefieras.

Marca la opción “Add a README file” si deseas incluir un archivo README desde el inicio.

Haz clic en “Create repository”.

Clonar el repositorio (opcional):

Si deseas trabajar localmente, copia la URL del repositorio y usa el siguiente comando en tu terminal:

git clone https://github.com/tu-usuario/operaciones-basicas.git

Subir archivos al repositorio:

Una vez dentro del repositorio clonado, puedes agregar archivos y realizar commits:

git add .
git commit -m “Primer commit”
git push origin main

2. Código de Operaciones Matemáticas Básicas
Este código en Python permite realizar operaciones aritméticas básicas con dos números ingresados por el usuario.

Código:

print(“Este programa te permite realizar operaciones de Aritmética básica”)

X = int(input(“Ingrese un dígito: “))
Y = int(input(“Ingrese un dígito: “))

Suma = X + Y
print(“El resultado de la Suma es: “, Suma)

Resta = X - Y
print(“El resultado de la Resta es: “, Resta)

Multiplicacion = X * Y
print(“El resultado de la Multiplicación es: “, Multiplicacion)

Division = X / Y
print(“El resultado de la División es: “, Division)

Potencia = X ** Y
print(“El resultado de la Potencia es: “, Potencia)

Modulo = X % Y
print(“El resultado del Módulo es: “, Modulo)

Cómo ejecutar el código:

Asegúrate de tener instalado Python en tu computadora.

Guarda el código en un archivo, por ejemplo, operaciones.py.

Abre una terminal o línea de comandos y navega hasta la carpeta donde guardaste el archivo.

Ejecuta el siguiente comando:

python operaciones.py

Ingresa los valores cuando el programa lo solicite y observa los resultados de las operaciones matemáticas.
