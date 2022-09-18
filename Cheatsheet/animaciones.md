## transform
- rotate(deg,turn)
- translate(px,%, em)
- skew(deg)
- scale(num)

transform-origin: - el punto de origen que se considera para hacer la transformacion.

## transition
- transition: (propiedad a transformar) / (duracion segundos o milisegundos)

## @keyframes
- animation-name
- animation-duration
- animation-delay
- animation-iteration-count: cantidad de veces (se puede usar infinite)
- animation-direction
    - normal  (forwards).  
    - reverse  (backwards)
    - alternate - 
    - alternate-reverse  
- animation-timing-function //velocidad (linear)
- animation-fill-mode

## ej:
 @keyframes traslado{
     from{transform: translate(0);}
     to{transform: translateX(400px);}
 }
 ej2:
 @keyframes traslado{
     0%{transform: translate(0);}
     50%{transform: translateX(400px);}
     100%{transform: translateX(0);}
 }
 ej3:
 @keyframes traslado{
     0%{transform: translate(0);}
     50%{transform: translateX(400px) rotate(45deg);}
     100%{transform: translateX(0);}
 }

### Atajo
animation: name duration timing-function delay iteration-count direction
solo name y duration son obligatorios.