# FORM-AC-01 - Fallo en un sistema distribuido real

Análisis del incidente de red de Google Cloud del 2 de junio de 2019 para Aplicaciones Distribuidas (ISR-701), séptimo nivel, paralelo A, Universidad Técnica Estatal de Quevedo.

## Equipo

- Coronel Gomez Khriz Alexander (ver observación)
- Giraldo Cagua Diego Jose
- Loor Mendoza Byron Daniel
- Silva Triviño John Jairo

## Archivos del informe

- [Informe grupal compilado](informe.pdf)
- [Código fuente LaTeX](informe.tex)
- [Bibliografía](referencias.bib)

## Observación sobre la entrega

Al cierre de esta versión, el equipo no había recibido el apartado asignado a Coronel Gomez Khriz Alexander. El apartado de mitigación quedó pendiente porque el equipo no logró coordinar su integración en las últimas horas previas a la entrega.

## Compilación

Desde la raíz del repositorio, con XeLaTeX, Biber, Babel en español, tabularx y BibLaTeX con estilo IEEE instalados, ejecuta:

```sh
xelatex informe.tex
biber informe
xelatex informe.tex
xelatex informe.tex
```

El resultado se genera en `informe.pdf`.

## Material de trabajo

- [Informe oficial de Google Cloud](https://status.cloud.google.com/incident/cloud-networking/19009)
- [Árbol editable del equipo en Drive](https://drive.google.com/drive/folders/1wLKB4euVKZK7rVxNRx8UsTCUtD6WMwmS)
