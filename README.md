# cifrado-hill
Nombre Completo del Alumno: Heidi Esther Peña Betanzos
Grupo:1C
Maestro:Jorge Javier Pedroza Romero
Materia:Fundamentos de Algebra 

---

## Descripción del Proyecto

Este proyecto implementa el algoritmo de Cifrado Hill, un método de criptografía basado en el uso de álgebra lineal y operaciones con matrices.  
La aplicación permite encriptar y desencriptar mensajes utilizando una matriz clave de 2x2.  
El sistema trabaja con el alfabeto en mayúsculas (A–Z) y con aritmética módulo 26.

---

## Tecnologías Utilizadas
 HTML: estructura de la página 
 CSS: diseño y estilos visuales
 JavaScript: lógica del cifrado y descifrado  
 Git y GitHub: control de versiones
 GitHub Pages: despliegue web  
 
 ---
## Instrucciones de Uso

1. Abrir la página web del proyecto.
2. Escribir un mensaje con un máximo de 30 caracteres.
3. Ingresar los valores de la matriz clave 2x2.
4. Presionar el botón Encriptar para cifrar el mensaje.
5. Presionar el botón Desencriptar para recuperar el mensaje original.
6. El resultado se mostrará en pantalla.

Nota: La matriz clave debe tener determinante invertible módulo 26 para que el cifrado funcione correctamente.

---

## Fundamento Matemático del Cifrado Hill

El algoritmo se basa en la multiplicación de matrices.

Conversión de letras a números:
A = 0, B = 1, C = 2, ..., Z = 25

Matriz clave:
| a  b |
| c  d |

---
Proceso de encriptación:
1. El mensaje se divide en pares de letras.
2. Cada par se convierte en un vector numérico.
3. Se multiplica el vector por la matriz clave.
4. El resultado se reduce módulo 26.
5. El resultado numérico se convierte nuevamente en letras.

