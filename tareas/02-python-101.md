## León, Guanajuato. MX :green_heart::bird::heart:
<p>La ciudad de <strong>León, Guanajuato</strong> actualmente tiene <em><strong>1 578 626</strong></em> habitantes (ONU, 2010) en una superficie de <em><strong>1219.76</strong></em> km <sup>2</sup>.</p>
<p>Por otra parte el estado de <strong>Guanajuato</strong> cuenta con <em><strong>5 853 677</strong></em>  habitantes en una superficie total de <em><strong>30 608</strong></em>  km <sup>2</sup>.</p>
<p><strong>México</strong> tiene <em><strong>128 649 656</strong></em> habitantes (CIA, 2017) en una superficie de <em><strong>1 964 189</strong></em> km cuadrados </p>

http://cuentame.inegi.org.mx/monografias/informacion/gto/sitios/default.aspx?tema=me&e=11
http://cuentame.inegi.org.mx/territorio/extension/default.aspx?tema=T

## Calcular la densidad poblacional
```math
Densidad = habitantes/superficie
```

## Código en Python para resolver el cálculo de la densidad poblacional
```python

def densidad_poblacional(poblacion, area_ciudad):
  densidad = poblacion / area_ciudad
  return densidad

print("La densidad poblacional de León, Guanajuato es: ", densidad_poblacional(1238962,487))
print("La densidad poblacional del estado de Guanajuato es: ", densidad_poblacional(5853677,30608))
print("La densidad poblacional de México es: ",densidad_poblacional(128649656,1964735))


```

## OUTPUT
```
La densidad poblacional de León, Guanajuato es:  129.42054174591723
La densidad poblacional del estado de Guanajuato es:  191.24663486670153
La densidad poblacional de México es:  65.47939340419956
```
