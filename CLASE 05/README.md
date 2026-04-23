# ENTREGAS

# Pulso: Visualización de un cuerpo invisible

## Descripción

Este proyecto explora la traducción de datos fisiológicos en una experiencia visual sensible. A partir del registro de ritmo cardiaco obtenido desde un smartwatch, se construye una visualización en Processing que transforma estos valores en una forma orgánica en constante cambio.

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

![Visualización](media/captura.png)

---

## Reflexión

Este proyecto propone una forma alternativa de entender los datos: no como información abstracta, sino como materia sensible.

El ritmo cardiaco, usualmente reducido a números, se convierte aquí en una forma que respira, se tensiona y cambia. En este proceso, el dato pierde su carácter puramente técnico y adquiere una dimensión perceptiva.

---

## Tecnologías utilizadas

- Processing (Java)
- Datos exportados desde smartwatch
- CSV para estructuración de datos

---

## Autor

William Salvador
