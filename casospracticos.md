# Caso práctico
## 1º Comprueba la version de gninx con un comando
![a](https://github.com/1804marcos/nginx/blob/main/imagenes/Captura%20desde%202023-01-09%2008-27-34.png)
## 2º Donde estan los fichieros de configuracion en /etc/ngixn
![a](https://github.com/1804marcos/nginx/blob/main/imagenes/Captura%20desde%202023-01-09%2008-28-37.png)
## 3º Para modificar el html que viene definido hay que cambiar el documento /var/www/html/index.nginx-debian.html
![a](https://github.com/1804marcos/nginx/blob/main/imagenes/Captura%20desde%202023-01-09%2008-36-50.png)
## 4º Balanceo de carga
### Para este practica necesitamos 3 maquinas, 2 modificaremos el /var/www/html/index.nginx-debian.html 
igual que en el paso anterior para que nos muestre en cada una lo siguiente:
![a](https://github.com/1804marcos/nginx/blob/main/imagenes/Captura%20desde%202023-01-11%2008-53-30.png)
![a](https://github.com/1804marcos/nginx/blob/main/imagenes/secweb.PNG)
### Ahora nos vamos a la maquina que servira como balanceador de carga y en /etc/nginx/conf.d/load-balancing.com
añadimos las ip de los servidores de carga y el nombre del servidor:
![a](https://github.com/1804marcos/nginx/blob/main/imagenes/loadlbal.PNG)
### en el /etc/host añadimos la siguiente linea:
![a](https://github.com/1804marcos/nginx/blob/main/imagenes/Captura%20desde%202023-01-11%2008-36-25.png)

