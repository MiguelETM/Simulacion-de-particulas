# Simulación de partículas

Simulación de un conjunto de partículas que se mueven bajo la acción de potencial de Lennard-Jones.  Este potencial es de la forma:
<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=\phi(r)=&space;-4&space;\epsilon\left[\left(\dfrac{\sigma}{r}&space;\right)^{6}&space;-&space;\left(\dfrac{\sigma}{r}&space;\right)^{12}&space;\right&space;]," target="_blank"><img src="https://latex.codecogs.com/gif.latex?\phi(r)=&space;-4&space;\epsilon\left[\left(\dfrac{\sigma}{r}&space;\right)^{6}&space;-&space;\left(\dfrac{\sigma}{r}&space;\right)^{12}&space;\right&space;]," title="\phi(r)= -4 \epsilon\left[\left(\dfrac{\sigma}{r} \right)^{6} - \left(\dfrac{\sigma}{r} \right)^{12} \right ]," /></a>
 </p>
 donde <a href="https://www.codecogs.com/eqnedit.php?latex=r" target="_blank"><img src="https://latex.codecogs.com/gif.latex?r" title="r" /></a> es la distancia de los centros de dos partículas, <a href="https://www.codecogs.com/eqnedit.php?latex=\sigma" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sigma" title="\sigma" /></a> es la distancia finita entre partículas para la cual el potencial es 0 y <a href="https://www.codecogs.com/eqnedit.php?latex=\epsilon" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\epsilon" title="\epsilon" /></a> indica la profundidad del pozo de pontencial.

 
 <p align="center">
  <img src="imagenes/lj.png" width="350" title="hover text">
</p>
 Este potencial tiene un comprtamiento interezante dado que este atractivo a grandes distancias y es repulsivo a corsas distancias.
 
 La simulación se realiza en 3 etapas distintas:
 1. Se genera una configuración inicial generando una determinada cantidad de particulas en una caja cuadrada de lado L.
 2. La configuración inicial generada se mueve buscando una configuración de mínimo potencial mediante una simulación de tipo Metrópolis.
 3. Se genera una animación que muestra como evoluciona el sistema.
