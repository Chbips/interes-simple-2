# Compilación de funciones matematticas financieras

En este repositorio se agrupan las actividades realizadas en la materia matematicas financieras, en la licenciatura actuaría y ciencia de datos de la UMSNH

## Funciones de ínteres simple

Con el siguiente código puede usted cargar las funciones relativas a los cálculos de ínteres simple:

```{r}
source("https://raw.githubusercontent.com/Chbips/interes-simple-2/refs/heads/main/formula%20interes%20simplee.R")
```
A continuación se dan ejemplos del uso de las formulas correpondientes

### Cálculo del valor futuro

Para ilustrar el ejmplo se tiene el siguiente ejerccio
$VA$=$10,000.00
$i$=24% anualizado
$r$=2.00% mensual
$t$= 7 meses

Se realizan los calculos
```{r}
# Creamos objetos con los valores de entrada:
valorActual=1000
tasaPeriodo=0.02
nPeriodos=7
# Calculamos el valor futuro:
valorFuturo=valorFinalSimple(VA=valorActual,r=tasaPeriodo,t=nPeriodos)
# Imprimimos el resultado:
valorFuturo
```
