## León, Guanajuato. MX :green_heart::bird::heart:
<p>La ciudad de <strong>León, Guanajuato</strong> actualmente tiene <em><strong>1 238 962</strong></em> habitantes (ONU, 2010) en una superficie de <em><strong>487</strong></em>  km cuadrados.</p>
<p>Por otra parte el estado de <strong>Guanajuato</strong> cuenta con <em><strong>5 853 677</strong></em>  habitantes en una superficie total de <em><strong>30 608</strong></em>  km cuadrados.</p>
<p><strong>México</strong> tiene <em><strong>128 649 656</strong></em> habitantes (CIA, 2017) en una superficie de <em><strong>1 964 375</strong></em> km cuadrados </p>

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
