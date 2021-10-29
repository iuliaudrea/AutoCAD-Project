## Osia din față
<p align="justify">
  Pe osia din față sunt suprapuse următoarele componente: două roți pentru direcție, un sistem de prindere a hamurilor, suspensii și un sistem de prindere a suspensiilor. În figura următoare se poate observa modul în care acestea sunt poziționate.
</p>
<p align="center">
  <img src="./img/of_schita.png" height=250>
</p>

### Roți de direcție

<p align="justify">
  Am creat desenele 2D ale roților de direcție folosind <i>CIRCLE, OFFSET, LINE</i> și 
<i>TRIM</i>, după care am utilizat <i>PRESSPULL</i> pentru amândouă.
</p>

<p align="center">
  <img src="./img/roti_directie.png" height=350>
  <img src="./img/roti3d.png" height=350>
</p>

### Sistemul de prindere a hamurilor

<p align="justify">
Componenta pe care se atașează hamurile cailor a fost creată astfel: în 2D am folosit <i>LINE</i> și <i>CIRCLE</i>, iar în 3D am folosit <i>PRESSPULL</i> pornind de la schița ce corespunde perspectivei de sus, pentru a adăuga grosimea de 5 unități.
</p>
<p align="center">
  <img src="./img/cotari_hamuri.png" height=230>
  <img src="./img/sistem_hamuri.png" height=230>
</p>

### Suspensiile

<p align="justify">
În realizarea suspensiilor, am folosit <i>ARC, CIRCLE, LINE</i> și <i>MIRROR</i> pentru proiectarea 2D, iar pentru crearea obiectului 3D am folosit <i>PRESSPULL</i>.
</p>
<p align="center">
  <img src="./img/cotari_suspensii.png" height=190>
  <img src="./img/suspensii.png" height=190>
</p>


### Sistemul de prindere al suspensiilor

<p align="justify">
Pentru ca suspensiile să fie stabile, acestea sunt prinse cu ajutorul unui suport. Acesta a fost realizat cu funcția <i>EXTRUDE</i> aplicată pe desenele corespunzătoare 
vederii de sus.
</p>
<p align="center">
  <img src="./img/cotari_sup_susp.png" height=300>
  <img src="./img/sist_susp.png" height=300>
</p>


### Osia

<p align="justify">
Osia propriu-zisă a fost creată cu ajutorul comenzii <i>EXTRUDE</i> folosind: un pătrat pentru a adăuga lungimea de 150 de unități, un cerc pentru a adăuga lungimea de 20 de unități în ambele capete. Pe aceste margini cilindrice vor fi poziționate roțile.
</p>
<p align="center">
  <img src="./img/osie.png" width=600>
  </p>
  <p align="center">
  <img src="./img/osie3d.png" width=600>
</p>

### Asamblarea componentelor
Componentele au fost asamblate folosind folosind <i>3DROTATE</i> și <i>MOVE</i>.

<p align="center">
  <img src="./img/of.png" width=600>
</p>
