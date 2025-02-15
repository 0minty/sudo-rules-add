# -sudo-
<center>
Если у вас при использовании Linux появляется ошибка <b>is not sudoers file</b>, то проделайте следующие шаги, которые указаны ниже

<p align="center">
  <img src="https://github.com/user-attachments/assets/0a1ffca4-eb0c-4bd1-bf5a-42182b1117ee" alt="image">
</p>

</center>



1. Заходим под пользователя root используя команду ```su -```

   ![image](https://github.com/user-attachments/assets/8d589248-c5b3-41e0-b282-473b85e99d96)

2. Прописываем команду ```sudo visudo```, открывается такое окошко

   ![image](https://github.com/user-attachments/assets/1a50beba-92d0-4e25-be4a-694d6ed11bae)

3. Ищем такой пункт

   ![image](https://github.com/user-attachments/assets/0a737b08-4715-4231-a99b-24103c211b83)

4. Дописываем свою строчку ```Имя пользователя  ALL=(ALL:ALL) ALL```

   ![image](https://github.com/user-attachments/assets/390f5ca8-29ae-475b-8dea-fe72010c444e)

5. Сохраняем файл используя комбинацию ```ctrl + x```, потом нажимаем на ```Y```, и прожимаем ```Enter```

   ![image](https://github.com/user-attachments/assets/145c32a4-cadf-4a65-b64d-16e4b90c82dc)

6. Пишем команду ```exit``` или прожимаем комбинацию ```ctrl + D```

   ![image](https://github.com/user-attachments/assets/3921ec11-5ba7-4de3-8907-9354defb4730)

8. Проверяем команду ```sudo```, ошибку <b>is not sudoers file</b> не должно выводить!
  
  ![image](https://github.com/user-attachments/assets/c3dfe4c5-6d4c-4aa5-89e8-e6d416763039)


Всем успехов!


   
