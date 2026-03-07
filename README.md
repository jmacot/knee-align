# Deformidades Coronales

Herramienta de analisis de deformidades coronales del miembro inferior basada en los algoritmos AKUMA (varo) y AKULA (valgo) de Ollivier et al. (KSSTA 2025).

## Acceso directo
[Abrir la aplicacion](https://jmacot.github.io/deformidad-coronal/)

## Funcionalidades
- Analisis de componentes de la deformidad (AKUMA para varo / AKULA para valgo): IAD%, EAD%, contribucion tibial y femoral
- Disclaimer de precaucion para AKULA (valgo) con desplegable explicativo
- Diagnostico diferencial: HTO vs DFO vs DLO vs UKA
- Planificacion de correccion con metodo Mikulicz y correccion Micicoi (α = (JLCA−2)/2)
- Presentacion "correccion osea real": correccion total → partes blandas (seesaw) → correccion osea real
- Visualizacion con flechas didacticas: mMPTA actual → (+X°) → mMPTA postop
- Calculo de altura de cuna tibial con formula de Hernigou: D × tan(α), anchura tibial editable
- Popover educativo sobre el efecto seesaw al clicar en el termino
- Exportacion PDF con pdfmake (informe preoperatorio completo)
- Clasificacion CPAK (MacDessi 2021)
- Visualizadores de rango interactivos para cada parametro
- Explicacion educativa paso a paso del razonamiento clinico
- Modo oscuro automatico

## Tecnologia
- HTML5, CSS3 y JavaScript puro
- Tipografias: Inter + Lora (Google Fonts)
- D3.js para graficas de contribucion
- pdfmake para exportacion PDF
- Sin frameworks adicionales

## Licencia
MIT
