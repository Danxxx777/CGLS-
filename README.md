# FORM-AC-01 - Fallo en un sistema distribuido real

Análisis del incidente de red de Google Cloud del 2 de junio de 2019 para Aplicaciones Distribuidas (ISR-701), séptimo nivel, paralelo A, Universidad Técnica Estatal de Quevedo.

## Integrantes que elaboraron el informe

- Giraldo Cagua Diego Jose
- Loor Mendoza Byron Daniel
- Silva Triviño John Jairo

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
