# Budines Lab

Este directorio organiza recetas de budines como un laboratorio de iteraciones: se parte de una base, se cocina, se registra una resena tecnica y se propone la siguiente version.

## Objetivo
Desarrollar recetas optimizadas mediante pruebas controladas, con cambios pequenos y conclusiones utiles.

## Flujo de trabajo
1. Partir de una receta control en una carpeta de iteracion.
2. Cocinarla sin cambiar mas de una variable importante por prueba.
3. Registrar una resena tecnica del resultado.
4. Definir la siguiente iteracion con una hipotesis concreta.

## Convencion de nombres
- Cada iteracion vive en una carpeta con dos digitos: `00`, `01`, `02`, `03`.
- Dentro de cada carpeta debe haber al menos dos archivos: `RECETA.md` y `iteracion_N.md`.
- `RECETA.md` guarda la formula y el procedimiento de esa version.
- `iteracion_N.md` guarda el resultado real de la coccion y la decision para el siguiente paso.
- Si hace falta una mirada mas sensorial, se puede sumar una ficha de cata separada.

## Regla central
Cambiar una sola variable por iteracion. Si cambias grasa, liquido y harina al mismo tiempo, despues no sabras que explico el resultado.

## Estructura real
- `budin-base/iteraciones/00/RECETA.md` contiene la receta control.
- `budin-base/iteraciones/00/iteracion_0.md` contiene la evaluacion de esa coccion.
- `budin-base/iteraciones/01/` queda preparado para la primera iteracion derivada.
- `budin-base/plantillas/plantilla_receta_iteracion.md` sirve para escribir la receta de la nueva version.
- `budin-base/plantillas/plantilla_iteracion.md` sirve para documentar el resultado.
- `budin-base/plantillas/plantilla_cata.md` sirve para registrar una cata mas sensorial.

## Criterios de evaluacion
- Volumen: altura final y desarrollo en horno.
- Miga: fina, aireada, compacta o apelmazada.
- Humedad: centro, bordes y comportamiento al dia siguiente.
- Sabor: dulzor, aroma y balance graso.
- Terminacion: color, grieta, desmolde y corte.

## Como decidir la siguiente version
- Si falta humedad: subir liquido, sumar un ingrediente humectante o reemplazar parte de la manteca por aceite.
- Si falta volumen: revisar cremado, temperatura del horno o proporcion de leudante.
- Si la miga se endurece: bajar batido final o reducir harina efectiva.
- Si el sabor queda plano: ajustar sal, vainilla o ingredientes aromaticos.

## Siguiente objetivo sugerido
Consolidar un budin clasico equilibrado antes de abrir variantes como banana, citricos o frutos secos.