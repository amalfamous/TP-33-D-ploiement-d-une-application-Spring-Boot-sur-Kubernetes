## execute cette commande pour la bd:
docker run --name tp33-mysql  -e MYSQL_ROOT_PASSWORD=   -e MYSQL_ALLOW_EMPTY_PASSWORD=yes  -e MYSQL_DATABASE=tp33-k8s  -p 3306:3306  -d mysql:8.0

<img width="1919" height="1007" alt="image" src="https://github.com/user-attachments/assets/a9326fcd-4fb3-424e-a89f-a7f7e6952766" />

Manifest Kubernetes : Deployment:
<img width="1918" height="1007" alt="image" src="https://github.com/user-attachments/assets/d4297b91-ef7f-4a9d-ad39-896b85ec711c" />
<img width="1919" height="1006" alt="image" src="https://github.com/user-attachments/assets/e33478ee-469a-4101-a0ff-96190c6ce45a" />

Manifest Kubernetes : Service (NodePort): 
<img width="1004" height="203" alt="image" src="https://github.com/user-attachments/assets/4d375034-1015-4a1d-8d2c-016c1981c0a0" />

Liste des pods et services
<img width="1919" height="998" alt="image" src="https://github.com/user-attachments/assets/aaa59ae7-c281-4ca1-a4af-b136cbf59b26" />

Pour nettoyer le cluster :
<img width="808" height="236" alt="image" src="https://github.com/user-attachments/assets/4d13332d-6086-49c9-91e5-3adbea94831c" />
<img width="737" height="60" alt="image" src="https://github.com/user-attachments/assets/b41cd24a-3b0d-4625-9495-864b00591b10" />


<img width="927" height="295" alt="image" src="https://github.com/user-attachments/assets/751993cf-723d-4902-b6c1-f1072d8fa979" />
