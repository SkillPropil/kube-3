# kube-3
## Задание 1
1) Создал деплоймент файл, проблема заключалась в том, что 80 порт был уже занят. Выяснил это посмотрев логи пода мультитул. Исправил исходя из официальной документации - подсунул ему env {http,https} портов \
2) До скейлинга
  <img width="835" alt="Снимок экрана 2024-09-12 в 00 51 21" src="https://github.com/user-attachments/assets/e0e42ac9-9585-4610-8832-9898bde390ac">
3) После
<img width="731" alt="Снимок экрана 2024-09-11 в 23 01 07" src="https://github.com/user-attachments/assets/59695f4a-385d-4b80-a017-0cacab35cc39">   
4) файл service1.yaml  
5) Скрин выполнения команды внутри пода  
<img width="749" alt="Снимок экрана 2024-09-11 в 23 05 24" src="https://github.com/user-attachments/assets/c3c74dcd-35b0-476b-b024-38125b669c49">  
## Задание 2  
Файлы deployment2.yaml и service2.yaml  
<img width="700" alt="Снимок экрана 2024-09-12 в 00 41 49" src="https://github.com/user-attachments/assets/e85e5cfe-d9ef-4318-82bc-5da6141c4da4">  
<img width="736" alt="Снимок экрана 2024-09-12 в 00 42 13" src="https://github.com/user-attachments/assets/48fee029-981d-4417-93a6-cad4a14f9bd6">  
