***MODELLING***   

Edge Loops   
  A Key and left mouse button   
  SHIFT then A to add more loops   
 

**Acciones comunes**

- Borrar todo excepto los puntos: Utilizar nodo "ADD" con opcion "Delete Geometry but Keep Points"   
- Separa polygonos (SEPARATE en Maya) : utilizar nodo "FACET" con la opcion "Unique points"   
- Cerrar una curva: utilizar nodo "ENDS"   
- poner una expresion para desplazar un objeto respecto al bounding box: **bbox("../Base_line", D_YMAX)**
- pintar la dirección de las normales: nodo "COMB"
- Utilizar el nodo TRANSFORM para cambiar normales o velocidades en uno o varios puntos: poner el atributo (tipicamente v o N) en el nodo "Attributes" en vez de "*" que hay por defecto.
