# ArduinoSensors

![alt tag](https://raw.githubusercontent.com/EIA-University/ArduinoSensors/master/Sensores.jpeg)
  
Es necesario una configuración de voltaje utliizando resistencias de 10k y 20k como se muestra en el esquematico.
La velocidad serial entre el arduino y e 9dof de 9600 baudos, a cual traera 18 datos de la siguiente manera

  /# a, b, c, d, e , f, g, h ,i $
  
  j, k ,l ,m ,n ,o ,p, q, r#

donde se tienen una dupla de datos A y B así los primeros 6 son de A y los otros de B
a,b,c = acelerometro A coordenadas x,y,z.
d,e,f = magnetometro A coordenadas x,y,z.
g,h,i = giroscopo A eje x,y,z.
j,k,l = acelerometro B coordenadas x,y,z.
m,n,o = magnetometro B coordenadas x,y,z.
p,q,r = giroscopo B eje x,y,z.
