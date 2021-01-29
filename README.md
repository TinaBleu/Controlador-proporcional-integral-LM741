# Controlador-proporcional-integral-LM741

El controlador está en simulink. Es recomendable que primero se inicie Matlab > Simulink y desde Simulink se abra el archivo que contiene al circuito. Los amplificadores operacionales no se modificaron para actual como el LM741. Las resistencias tienen valores de 10k y 50k. Esta hecho en la version 2020b de Matlab. 

Para obtener la funcion de transferencia ir a APPS > Controll system > Model lin. 

Ejecutar la opcion "Step" y arrastrar linsys1 al panel donde está Out

Ir a la ventana de comandos y ejecutar lo siguiente:

tf(linsys1)

El resultado debe de ser el siguiente:

ans =
 
  From input "Step" to output "PS-Simulink Converter":
  5 s + 200
  ---------
      s

NOTA: Si, se pueden cambiar los valores de las resistencias. 
