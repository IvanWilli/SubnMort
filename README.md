Este es el repositorio del paper "Estimaciones de esperanza de vida al nacer en áreas menores de la región pampeana", de N. Sacco, I. Williams y B. Lanza Queiroz. 

Para un recorrido ordenado:

- En `Ppal.R` se tiene el flujo de trabajo general, tomando insumos y realizando la estimación.

- En `data/deis_defunciones/Defunciones.R` se analiza la calidad del registro de defunciones.

- En `data/pob_expuestos/Expuestos.R` se trabaja la suavización de los expuestos.

- En `R/DefAm.R` se realiza la regionalización.

- En `R/Métodos.R` se presentan las funciones de estimación de los tres métodos aplicados, que puede ser reutilizados para otras experiencias.

- En `data/Estimaciones_e0_por_dpto.csv` se tienen los resultado de `e_0` presentados en el anexo del paper.

Nos hubiese gustado esté mas prolijo para una reproducibilidad más amena. Es una trabjo que arrancó hace un par de años con muchas lagunas intermedias y no tuvo como fin inicial el de que su repositorio sea interpretable por otras personas. Disculpas por eso [no sabíamos mucho `R` ni `dplyr` al momento de empezar el proyecto ;)].

Cualquier cosa consultarnos! 

Nicolas sacco: nsaccozeballos@gmail.com

Iván Williams: act.ivanwilliams@gmail.com

