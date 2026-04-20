Este proyecto muestra cómo desplegar un servidor web en AWS usando EC2 y Nginx.

✔️ Tecnologías:
AWS EC2
Ubuntu
Nginx

✔️ Pasos (importante):
Crear instancia
Conectarse por SSH
Instalar Nginx

✔️ Problema real:
Al reiniciar la instancia, la IP pública cambió debido a que AWS asigna IPs dinámicas. 
Solución: usar Elastic IP (pendiente de implementar).

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/4ae78c40-3853-48f3-a3b3-34b0d0d9caf7" />


<img width="500" height="250" alt="image" src="https://github.com/user-attachments/assets/8a85adcb-8d3c-4ad5-94ea-24cadeba84dd" />

## 🔒 Mejora implementada

Se configuró una Elastic IP en AWS para mantener una dirección IP fija, evitando cambios al reiniciar la instancia.

