# Prueba Práctica - Unidad IV

## Ingeniería de Requisitos (ISR-401)

**Estudiante:** Ponce Rivera Mery Helenmey

**Curso:** 4to "A" Software

**Docente:** Ing. Guerrero Ulloa Gleiston Ciceron

**Universidad:** Universidad Técnica Estatal de Quevedo

## Descripción

Repositorio correspondiente a la **Prueba Práctica de la Unidad IV** de la asignatura Ingeniería de Requisitos (ISR-401).

El trabajo desarrolla el caso **Sistema de Gestión de Pedidos** mediante diez actividades prácticas relacionadas con modelado UML, especificación y validación de requisitos, priorización MoSCoW, pruebas de aceptación, trazabilidad y gestión del cambio.

## Estructura del repositorio

```text
ISR401-UnidadIV-PruebaPractica-PonceMery/
│
├── main.tex
├── main.pdf
├── README.md
│
└── figuras/
    └── logo_uteq.png
```

## Contenido del desarrollo

* P1. Modelo de datos - Diagrama de clases UML.
* P2. Modelo funcional - Diagrama de actividades UML.
* P3. Modelo de comportamiento - Máquina de estados UML.
* P4. Consistencia entre las tres perspectivas.
* P5. Especificación de requisitos con esquema de atributos.
* P6. Priorización MoSCoW.
* P7. Validación por inspección ISO/IEC/IEEE 29148.
* P8. Pruebas de aceptación trazadas.
* P9. Matriz de trazabilidad.
* P10. Gestión del cambio y línea base.

## Compilación

El documento fue desarrollado en **LaTeX** y compilado mediante **pdfLaTeX**.

### Compilador

```text
pdfLaTeX
```

### Archivo principal

```text
main.tex
```

### Orden de compilación

Ejecutar:

```bash
pdflatex main.tex
pdflatex main.tex
```

El segundo proceso de compilación permite actualizar correctamente referencias internas, numeración y elementos generados por LaTeX.

## Dependencias

El documento utiliza los siguientes paquetes:

```text
inputenc
fontenc
babel
lmodern
geometry
graphicx
array
tabularx
booktabs
longtable
enumitem
ragged2e
microtype
xcolor
hyperref
fancyhdr
titlesec
tcolorbox
tikz
```

También utiliza las siguientes librerías de TikZ:

```text
babel
arrows.meta
positioning
shapes.geometric
calc
fit
backgrounds
```

## Figuras

El archivo:

```text
figuras/logo_uteq.png
```

corresponde al recurso gráfico institucional utilizado en la portada.

Los diagramas UML de clases, actividades y máquina de estados se generan directamente mediante **TikZ**, por lo que pueden reproducirse al compilar el archivo `main.tex`.

## Reproducibilidad

Para reproducir el documento:

1. Clonar o descargar este repositorio.
2. Verificar que se mantenga la carpeta `figuras`.
3. Ejecutar `pdflatex main.tex`.
4. Ejecutar nuevamente `pdflatex main.tex`.
5. El resultado será el archivo `main.pdf`.

## Repositorio

https://github.com/Mery-003/ISR401-UnidadIV-PruebaPractica-PonceMery
