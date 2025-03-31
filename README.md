# consecionario de vehiculos
## programacion 1: orientada a objetos basica
## s25 evidencia de aprendizaje 1 
### darwin monsalve noreña 
### grupo: PREICA2501BO10016
### Docente: julian andrez loaiza 
### facultad de ingenieria y ciencias agropecuarias 
### tecnologia en desarrollo de software 
### Institucion universitaria digital de antioquia (iudigital) 
### 26 de febrero de 2025
# actividad de aprendizaje 1
## introduccion: 
Desarrolla un proyecto para un concesionario de vehículos, teniendo en cuenta las siguientes características:
 Los vehículos se clasifican en: autos, camionetas y motocicletas.
Todos los vehículos tienen un código, una marca, tipo (auto, camioneta, etc.), un modelo (año) y un kilometraje.
El concesionario necesita llevar un registro de las ventas realizadas, cada registro contiene la siguiente información:
a) Monto de la venta
b) Vehículo vendido (código)
c) Apellido
d) Nombre
e) Documento del comprador.

## Concluciones
#### Este proyecto no solo me ayudo a profundizar en java y la Poo (programacion orientada a objetos), sino que tambien me ayudo a reflexionar sobre la importacia de tener un codigo bien estructurado y organizado, para que este sea eficiente, Desde la creacion de clases hasta la gestion de datos con hashmap, cada parte de este proyecto fue un desafio para mi y mis compañeros de equipo con los que realize la actividad, pero sobre todo eso fue una grande oportunidad de aprendizaje.


# Solución del Ejercicio Práctico - Unidad 3

## Paso 1: Encontrar la derivada de la función de concentración

Función original: $f(t) = \sqrt{\frac{1.69}{0.6759t + 1}}$

Para resolver esta derivada, vamos a seguir el mismo método que aparece en la imagen:

1) Primero reescribimos la función como una composición:
   - $f(t) = \sqrt{g(t)}$ donde $g(t) = \frac{1.69}{0.6759t + 1}$

2) Para aplicar la regla de la cadena, definimos:
   - $h(x) = \sqrt{x} = x^{1/2}$ (función externa)
   - $g(t) = \frac{1.69}{0.6759t + 1}$ (función interna)

3) Aplicando la regla de la cadena: $f'(t) = h'(g(t)) \cdot g'(t)$

4) Calculamos la derivada de la función externa:
   - $h'(x) = \frac{1}{2}x^{-1/2} = \frac{1}{2\sqrt{x}}$

5) Calculamos la derivada de la función interna usando la regla del cociente:
   - Llamemos $U = 1.69$ (constante, por lo que $U' = 0$)
   - Llamemos $V = 0.6759t + 1$ donde $V' = 0.6759$
   - $g'(t) = \frac{U'V - UV'}{V^2} = \frac{0 \cdot V - U \cdot 0.6759}{V^2} = \frac{-1.69 \cdot 0.6759}{(0.6759t + 1)^2}$
   - $g'(t) = \frac{-1.142271}{(0.6759t + 1)^2}$

6) Sustituyendo en la regla de la cadena:
   - $f'(t) = h'(g(t)) \cdot g'(t)$
   - $f'(t) = \frac{1}{2\sqrt{g(t)}} \cdot \frac{-1.142271}{(0.6759t + 1)^2}$
   - $f'(t) = \frac{1}{2\sqrt{\frac{1.69}{0.6759t + 1}}} \cdot \frac{-1.142271}{(0.6759t + 1)^2}$

7) Simplificando:
   - $f'(t) = \frac{1}{2} \cdot \frac{\sqrt{0.6759t + 1}}{\sqrt{1.69}} \cdot \frac{-1.142271}{(0.6759t + 1)^2}$
   - $f'(t) = \frac{-1.142271}{2\sqrt{1.69}} \cdot \frac{\sqrt{0.6759t + 1}}{(0.6759t + 1)^2}$
   - $f'(t) = \frac{-1.142271}{2\sqrt{1.69}} \cdot \frac{1}{(0.6759t + 1)^{3/2}}$
   - $f'(t) = \frac{-1.142271}{2 \cdot 1.3} \cdot \frac{1}{(0.6759t + 1)^{3/2}}$
   - $f'(t) = \frac{-0.439335}{(0.6759t + 1)^{3/2}}$

Por lo tanto, la derivada de la función de concentración es:

$$f'(t) = \frac{-0.439335}{(0.6759t + 1)^{3/2}}$$

## Paso 2: Velocidad de reacción

Para calcular la velocidad de reacción a los 4.9 minutos, evaluamos la derivada en $t = 4.9$:

$$f'(4.9) = \frac{-0.439335}{(0.6759 \cdot 4.9 + 1)^{3/2}}$$

Calculamos el valor del denominador:
- $0.6759 \cdot 4.9 + 1 = 3.31191 + 1 = 4.31191$
- $(4.31191)^{3/2} = 4.31191 \cdot \sqrt{4.31191} = 4.31191 \cdot 2.0765 = 8.9535$

Sustituyendo:
$$f'(4.9) = \frac{-0.439335}{8.9535} = -0.0491$$

La velocidad de reacción a los 4.9 minutos es de $-0.0491$ $\frac{moles}{min}$

El signo negativo indica que la concentración del reactivo está disminuyendo con el tiempo, lo cual es coherente con la degradación del sellante por acción del catalizador.

## Paso 3: Concentración del reactivo

Para determinar la concentración del reactivo a los 4.9 minutos, evaluamos la función original en $t = 4.9$:

$$f(4.9) = \sqrt{\frac{1.69}{0.6759 \cdot 4.9 + 1}}$$

Calculamos:
- $0.6759 \cdot 4.9 + 1 = 3.31191 + 1 = 4.31191$
- $\frac{1.69}{4.31191} = 0.392$
- $\sqrt{0.392} = 0.626$

Por lo tanto, la concentración del reactivo a los 4.9 minutos es de 0.626 moles.

