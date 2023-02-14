# Tareas
Calculadora de estaciones
<!DOCTYPE html>
<html>
<head>
  <title>Mes</title>
<script>
 let mes;
 mes=prompt('Ingrese el número de un mes:','');
 mes=parseInt(mes);
 // Si el numero de mes es mayor de 12
  if(mes>12)
 {
  alert("El numero de mes ingresado no existe")
 }
  else
 // Si el numero de mes es menor de 1
  if(mes<1)
 {
  alert("El numero de mes ingresado no existe")
 }
 // Si no el numero de mes 12, 1, 2 es igual           
  else
  if (mes==12 || mes==1 || mes==2)
 {
 alert("Este mes pertenece a invierno");
 }
 // Si no el numero de mes 3, 4, 5 es igual 
  else
 if (mes==3 || mes==4 || mes==5)
 {
 alert("Este mes pertenece a Primavera");
 }
// Si no el numero de mes 6, 7, 8 es igual 
  else
  if (mes==6 || mes==7 || mes==8)
 {
 alert("Este mes pertenece a Verano");
 }
 // Si no el numero de mes 9, 10, 11 es igual 
 else
   if (mes==9 || mes==10 || mes==11)
 {
 alert("Este mes pertenece a Otoño");
 }
 alert("Diana García / 23004864") 

</script>
  </head>
</html>
