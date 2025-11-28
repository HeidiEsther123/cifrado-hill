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
   
---
## Desencriptación

Para desencriptar el mensaje se debe calcular:
- El determinante de la matriz clave.
- El inverso multiplicativo del determinante módulo 26.
- La matriz inversa.

Posteriormente se aplica la operación inversa:
M = K⁻¹ × C (mod 26)

---
## Personalización del Proyecto

El proyecto cuenta con un diseño personalizado que incluye:
- Colores personalizados.
- Contenedores con sombras.
- Tipografía moderna.
- Visualización de la matriz del mensaje.
- Contador de caracteres.
- Mensajes de error visuales.


Todo el diseño fue realizado con CSS.

---
## Despliegue Web

El proyecto fue desplegado mediante GitHub Pages y se encuentra disponible en el siguiente enlace:

 https://heidiesther123.github.io/cifrado-hill/

---

## Control de Versiones

El desarrollo del proyecto cuenta con múltiples commits que documentan el avance de:
- Interfaz.
- Funcionalidades de cifrado.
- Funcionalidades de descifrado.
- Ajustes visuales.
- Correcciones.

Cumpliendo con el uso correcto de Git y GitHub.

---
## Conclusión

Este proyecto demuestra la aplicación del Álgebra Lineal en la criptografía mediante el uso de matrices, determinantes, módulos e inversas, integrando matemáticas, programación y diseño web en una sola aplicación.

Proyecto desarrollado como parte de la Unidad III de la materia Fundamentos de Álgebra.

---
