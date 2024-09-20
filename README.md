# Compilacion de funciones Matematicas Financieras
en este repositorio se agrupan las fuciones y actividades informaticas en la materia de matematicas financiera en la licenciatura de Actuaria y Ciencias de datos de la UMSNH

## Funciones de interés simple

Con el siguiente codigo, puede usted cargar las funciones relativas a los cálculos de interés simple:

```
source("https://raw.githubusercontent.com/AngelReyesF/MatematicasFinancieras/refs/heads/main/FormulasInteresSimple.R")
```
A continuación se dan ejemplos de las formulas correspondientes

## Cálculo del Valor Futuro

Para ilustrar el ejemplo se tiene el siguente ejercicio VA=$1,000.00 i=24.00% anualizado r=2.00% mensual t=7 meses

Se realizan los calculos de VF
```
VF = VFinal(VA=1000,r=0.02,t=7)
```

## Cálculo del Valor Presente

Para ilustrar el ejemplo se tiene el siguente ejercicio VF=$1,140.00 i=24.00% anualizado r=2.00% mensual t=7 meses

Se realizan los calculos de VP
```
VP = VPresente(VF=1140,r=0.02,t=7)
```

## Cálculo del interes

Para ilustrar el ejemplo se tiene el siguente ejercicio VA=$1,000.00 VF=$1140.00 t=7 meses

Se realizan los calculos de r
```
r = rInteres(VA=1000,VF=1140,t=7)
```
A continuación se dan ejemplos de las formulas correspondientes

## Cálculo del tiempo trascurrido

Para ilustrar el ejemplo se tiene el siguente ejercicio VA=$1,000.00 VF=$1,140.00 i=24.00% anualizado r=2.00% mensual t=7 

Se realizan los calculos de t
```
t = tiempo(VA=1000,VF=1140,t=7)
```
