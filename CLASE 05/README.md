# ENTREGAS

# Pulso: Visualización de un cuerpo invisible

## Descripción

Principalmente, el proyecto consta en la recolección de datos csv. emitidos por un electrocardiograma en un smartwatch y con un código, processing los lee e interpreta en una forma orgánica.

En lugar de representar los datos como un gráfico tradicional, el proyecto propone una interpretación donde el pulso se manifiesta como un cuerpo dinámico: una figura circular que se expande, contrae y deforma suavemente según las variaciones del ritmo cardiaco.

---

## Idea

El pulso deja de ser un número para convertirse en una presencia.

La visualización no busca explicar el dato, sino encarnarlo. La forma no representa directamente el corazón, sino que intenta dar cuenta de un fenómeno que normalmente no es visible, solo perceptible.

---

## Funcionamiento

- Los datos de ritmo cardiaco son registrados desde un smartwatch
- Se limpian y normalizan a un rango de 0 a 100
- Se importan a Processing mediante un archivo `.csv`
- Cada valor modifica el radio de una forma circular
- Se aplica suavizado para mantener continuidad
- La forma respira y se deforma en el tiempo

---

## Sistema visual

- **Forma**: Circular, para mantener estabilidad estructural  
- **Deformación**: Controlada por los datos del pulso  
- **Movimiento**: Oscilaciones que simulan respiración y latido  
- **Color**:
  - Azul → estados de menor intensidad  
  - Rojo → estados de mayor intensidad  

---

## Visualización

![](/.imagenes/captura.png)

---

## BITÁCORA

- El sujeto se expuso a una serie de situaciones de "estrés" en donde su pulso pudiera verse afectado.
- Eventualmente, me gustaría interpretar estos pulsos como sonidos.
- Lunes 06: El sujeto se presenta voluntario para el proyecto.
- Martes 07: El sujeto lloró.
- Miércoles 08: El sujeto tomó una siesta.
- Jueves 09: El sujeto fue a la universidad.
- El sujeto muestra sintomas depresivos fuertes

---

## Tecnologías utilizadas

- Processing (Java)
- Datos exportados desde smartwatch
- CSV para estructuración de datos

---

## Autor

William Salvador
