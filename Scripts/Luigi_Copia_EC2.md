## Comandos que corremos desde la terminal de EC2

+ python3 -m luigi --module Luigi Tarea_60 --local-scheduler

+ scp -i /home/miguelmillan13/.ssh/id_rsa /home/miguelmillan13/Documentos/ITAM/Segundo_Semestre/Arquitectura_Datos/Proyecto/Luigi/Luigi.py ec2-user@ec2-18-233-96-69.compute-1.amazonaws.com:/home/ec2-user

+ python3 -m luigi --module Luigi Tarea_60 --local-scheduler

+ scp -i /home/miguelmillan13/.ssh/id_rsa /home/miguelmillan13/Documentos/ITAM/Segundo_Semestre/Arquitectura_Datos/Proyecto/Luigi/Luigi.py ec2-user@ec2-3-85-29-205.compute-1.amazonaws.com:/home/ec2-user/

+ python3 -m luigi --module Luigi Tarea_50 --local-scheduler

+ sh 00_install_packages.sh
