# Ejercicio 8

Deployment: 
![alt text](images/0.png)

Para obtener el puerto he accedido al log del pod y he revisado el Dockerfile de la imagen: 
![alt text](images/1.png)
![alt text](images/2.png)

Se crea el servicio y se hace un port forward
![alt text](images/3.png)
![alt text](images/4.png)

Para poder ver correctamente el balanceo del servicio uso el comando ``minikube service colors-service``, ya que  el portforward al servicio conectará a un pod aleatorio, pero mantendrá la sensión.

![alt text](images/image-2.png)
![alt text](images/image.png)
![alt text](images/image-1.png)
