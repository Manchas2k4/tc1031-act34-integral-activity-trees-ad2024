![Tec de Monterrey](images/logotecmty.png)
# Act 3.4 - Actividad Integral de Árboles (Evidencia Competencia)

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
En este repositorio encontrarás los archivos de entrada, así como las salidas esperadas que podrás usar para probar tu implementación. También encontrarás un archivo "main.cpp". Ahí deberás implementar tu solución. En el archivo deberás colocar en la parte superior, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: main.cpp
// Author: Edward Elric - A00123456
// Date: 01/01/2021
// =========================================================
```
<span style="text-decoration: underline;">De manera individual</span>, desarrolla la solución del siguiente problema:

Había una vez en un pequeño pueblo llamado Algoritmia, un joven programador llamado Luis. Luis era conocido por su destreza en la resolución de problemas algorítmicos y su pasión por la informática. Un día, el anciano sabio del pueblo, el Profesor Binary, le presentó un desafío intrigante: reconstruir un árbol binario utilizando solo dos de sus recorridos: el recorrido inorder y otro que podía ser el preorder o el postorder.

Luis aceptó el reto con entusiasmo. Sabía que los recorridos de un árbol binario contenían valiosa información sobre la estructura del árbol, pero nunca había intentado algo tan complejo. ¿Puedes ayudar con este reto?

## <span style="color: rgb(26, 99, 169);">**Entrada**</span>
La primera línea contiene un solo número entero t (2 <= t <= 6), que representa el número de niveles del árbol.

A continuación, siguen 2 líneas. Cada una de estas líneas contiene primero el tipo de recorrido (IN, PRE, POST) seguido por una cadena que representa el recorrido específico. Ten en cuenta que uno de los recorridos siempre será el recorrido inorder del árbol.

## <span style="color: rgb(26, 99, 169);">**Salida**</span>
El recorrido por niveles del árbol.

## <span style="color: rgb(26, 99, 169);">**Ejemplo de entrada 1**</span>
```
3
POS AGDC
IN CADG
```

## <span style="color: rgb(26, 99, 169);">**Ejemplo de salida 1**</span>
```
C D  AG
```

## <span style="color: rgb(26, 99, 169);">**Ejemplo de entrada 2**</span>
```
5
IN FAIVXGadZeRBKJHQ
PRE FZXIAVaGdKReBHJQ
```

## <span style="color: rgb(26, 99, 169);">**Ejemplo de salida 2**</span>
```
F Z  XK    IaRH        AVGdeBJQ
```

Para probar tu implementación, compila tu programa con el comando:
```
g++ -std=c++11 main.cpp -o app
```
Posteriormente, prueba con cada uno de los archivos de entrada de prueba que encontrarás en este repositorio (input1.txt, input2.txt, input3.txt, input4.txt). Los resultados que debes obtener se encuentran en los archivos llamados output1.txt, output1.txt, output1.txt y output1.txt. Para realizar las pruebas, puedes usar las siguientes líneas de código. Por ejemplo, si queremos probar con el archivo de prueba "input1.txt".
```
./app < input1.txt > mysolution1.txt
diff mysolution1.txt output1.txt
```
Si el segundo comando no tenga ninguna salida, sabrás que los resultados que obtuviste son los esperados. 

Por último, realiza una investigación y reflexión en forma individual de la importancia y eficiencia del uso de los diferentes algoritmos de ordenamiento y búsqueda en una situación problema de esta naturaleza, generando un documento llamado **"ReflexAct3.4.pdf"**

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **65%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (80%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (60%)** - pasa correctamente el 75% de los casos de prueba.
    - **Bien (40%)** - pasa correctamente el 50% de los casos de prueba.
    - **Insuficiente (20%)** - pasa correctamente menos del 50% de los casos de prueba.


- **10%** - 15% - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](https://github.com/Manchas2k4/tc1031)</span>
- **10%** - Especifican en cada uno de las funcionalidades la complejidad computacional como parte de su documentación.
- **15%** - Emplea los algoritmos y estructuras de datos más eficientes para la solución del problema.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Esta actividad forma parte tanto de tu calificación final del curso, así como del portafolio de evidencias de las competencias a desarrollar del curso, por lo que se te pide que en forma individual:
* Realices una entrega de  los archivos correspondientes de los algoritmos de ordenamiento y búsqueda, en la sección correspondiente dentro de esta plataforma, así como el documento de reflexión individual (**ReflexAct3.4.pdf**).
* Generes una carpeta en forma personal llamada **TC1031(Portafolio_Final)** que servirá como preparación para la entrega del portafolio de competencias que se realizará al final del curso, esta carpeta debe contener 5 carpetas:
    * Act1.3
    * Act2.3
    * **Act3.4** - coloca aquí tus archivos que solucionaron la <span style="text-decoration: underline;">actividad 3.4</span> así como el documento de reflexión individual sobre el impacto del TDA árbol en las tareas más comunes de la programación. (**ReflexAct3.4.pdf**).
    * Act4.3
    * Act5.2
