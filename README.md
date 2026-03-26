# Bruteforcecode
Codigo de fuerza bruta

Explicación del código:

Se definen varios strings con letras, números y símbolos mas comunes, los cuales, son todos unidos en uno solo.
El bucle "for letra in contraseña:", declara una variable que vera cada carácter de la contraseña por separado, y dentro de ese loop se ingresa otra que identificara todos los combinados anteriormente; de modo que si la variable "intento" es igual al carácter "letra", se guarde ese carácter en la variable "resultado"; Y cada vez que ese carácter no coincida marque como intento fallido.
Al final se descubre la contraseña y muestra el numero de intentos que tomo descifrarla

Como se ejecuta?
Tienes que poner una contraseña como una variable, y según la robustez que tenga se verá reflejado según el número de intentos

Ejemplos de salida:
contraseña = "hol#"

Salida:
Encontrado: hol#
Total de intentos: 90
Total de tiempo: 0.0005633831024169922

Reflexión: ¿Qué pasa si la contraseña tiene 8+ caracteres y usa mayúsculas, números y símbolos?
Si fuera una contraseña de más largA como de 8 caracteres o más, esta tardaría más en encontrarse, pero si se podría averiguar**
