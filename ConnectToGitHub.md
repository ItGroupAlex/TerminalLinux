
#Подключаемся к GitHub используя SSH:   

a.) генерируем SSH-key: заходим, например в Git Bush, и вводим:   
							    `$ ssh-keygen`  
						  	  * при желании назначаем пароль;   
						  	  * открываем созданный публичный ключ *.pub и копируем содержимое текста.  
б.) вставляем в настройках Git Hub - SSH  
в.) подгружаем данные login & e-mail:  
		  `$ git config --global user.name "ItGroupAlex"`  
		  `$ git config --global user.email "ItGroupAlex@gmail.com"`  
