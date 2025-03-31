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

Para encontrar la derivada implícita de $x^3 - y^3 = xy + 8$, voy a seguir estos pasos:

1) Primero, derivamos toda la ecuación con respecto a x:
   * Lado izquierdo: $\frac{d}{dx}(x^3 - y^3) = \frac{d}{dx}(x^3) - \frac{d}{dx}(y^3)$
   * Lado derecho: $\frac{d}{dx}(xy + 8) = \frac{d}{dx}(xy) + \frac{d}{dx}(8)$

2) Calculemos cada término:
   * $\frac{d}{dx}(x^3) = 3x^2$
   * $\frac{d}{dx}(y^3) = 3y^2 \cdot \frac{dy}{dx}$ (aplicando regla de la cadena)
   * $\frac{d}{dx}(xy) = x \cdot \frac{dy}{dx} + y \cdot 1 = x\frac{dy}{dx} + y$
   * $\frac{d}{dx}(8) = 0$

3) Sustituyendo en la ecuación:
   $3x^2 - 3y^2\frac{dy}{dx} = x\frac{dy}{dx} + y$

4) Agrupamos los términos con $\frac{dy}{dx}$:
   $3x^2 - y = 3y^2\frac{dy}{dx} + x\frac{dy}{dx}$
   $3x^2 - y = \frac{dy}{dx}(3y^2 + x)$

5) Despejamos $\frac{dy}{dx}$:
   $\frac{dy}{dx} = \frac{3x^2 - y}{3y^2 + x}$

Por lo tanto, la derivada implícita de $x^3 - y^3 = xy + 8$ es:
$\frac{dy}{dx} = \frac{3x^2 - y}{3y^2 + x}$

